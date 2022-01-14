# Lab Report 1: How to log into `ieng6`
## 1. Install [Visual Studio Code](https://code.visualstudio.com/Download)
![](install1.PNG)
Download and install VSCode from its website by downloading an installer for your OS and then opening said installer from your downloads folder.

## 2. Remotely connecting
1. Open VSCode, open whatever project you want to play with, and then open a new terminal.
2. In this terminal, type `ssh` followe dby your ieng6 username (like `cse15lwi22XXX@ieng6.ucsd.edu`)<br>
![](SSH1.PNG)<br>
3. Once you have successfully logged in, type `logout` to log yourself out.

## 3. Trying some commands
Try typing some of these commands into the terminal while you are logged into SSH
* `cd ~`
* `cd`
* `ls -lat`
* `ls -a`
* `pwd`
* `mkdir`<br/>
The results will look a lot like this:
![](s3_1.png)
![](s3_2.png)

## 4. Moving files with SCP
If you are trying to move a file from your computer into the server, use the `scp` command.<br/>
Example: `scp <filename>.java cs15lwi22XXX@ieng6.ucsd.edu:~/`<br/>
Successful results should look something like this:<br>
![](s4_1.png)<br/>
You can also now run `java` and `javac` commands from inside the server:<br>
![](s4_2.png)

## 5. Getting an SSH key
Follow these commands to make a key so you can log in without a passcode:<br>
![](s5_1.png)
![](s5_2.png)

## 6. Working even faster
Once you have the SSH key, you can type commands with after your login command in order to have an even faster and more efficient workflow:<br>
![](s6.png)