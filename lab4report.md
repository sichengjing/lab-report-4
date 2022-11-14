# Lab report 4
## Part 1
### Changing the name of the start parameter and its uses to base

```
/start<Enter>dwibase<Esc>ndwibase<Esc>ndwibase<Esc>n:wq<Enter>
```
### Step 1
```
vim DocSearchServer.java
```
![Image](1.png)
To start, log in to the remote account and clone the repository, and put it in the week6-skill-demo2 directory.

### Step 2
```
/start<Enter>
```
![Image](2.png)
Finding the first "start".

### Step 3
```
dw
```
![Image](3.png)
Deleting the first "start".

### Step 4
```
ibase<Esc>
```
![Image](4.png)
Entering the insert mode, typing "base", and then going back to the normal mode.

### Step 5
```
n
```
![Image](5.png)
Finding the next "start".

### Step 6
```
dwibase<Esc>
```
![Image](6.png)
Changing this "start" into "base".

### Step 7
```
ndwibase<Esc>
```
![Image](7.png)
Finding the next "start" and changing it into "base".

### Step 8
```
n:wq<Enter>
```
![Image](8.png)
Once all the "start" are changed except the last one, save the file and leave.

## Part 2
3'11" for the first method and 2'20" for the second method. No difficulties coming up.

### Answer 1
I prefer the second style, because it is faster and save time for doing scp.

### Answer 2
Nothing will affect this decision, because no matter what kind of project it is, this method will save much time for copying files from local to remote and logging in.
