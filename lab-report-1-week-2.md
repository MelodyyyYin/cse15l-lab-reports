# Lab Report 1 (Week 2)

## - Installing VScode
![Image](install.png)
> - go to the vscode website [vscode](https://code.visualstudio.com/)
> - download the right version and install it on your computer

![Image](vscode.png)
> - it should be look like this!


---



## - Remotely Connecting
![Image](connect.png)
> - open a new terminal
> - enter `ssh cs15lwi22aee@ieng6.ucsd.edu`
> - type the right password


---
## - Trying Some Commands
![Image](commands.png)
Here are some commands!
> - cd = change directory
> - ls = shows files
> - mkdir = makes a folder
> - ls -l = shows files with more info
> - pwd = prints working directory
> - cp = copy

---
## - Moving Files with scp
![Image](move.png)
> - create a java file
> - enter command `scp WhereAmI.java cs15lwi22aee@ieng6.ucsd.edu:~/` and Password
> - the file we create on our local computer will save to the server

---
## - Setting an SSH Key
![Image](sshkey.png)
> - to set the keys, we use command `ssh-keygen`
> - save the key in the file: /Users/yueyin/.ssh/id_rsa
> - enter the empty passphrase twice

![Image](sshkeys.png)
> - the keys is set up and we can run the command from the client to the server without entering the password

---
## - Optimizing Remote Running

![Image](last1.png)
> - enter command `ssh cs15lwi22aee@ieng6.ucsd.edu "ls -la"`(I use 41 keystrokes to run this command, but we could use up head arrow to run the same command next time to save some time)

> - after we setting the ssh key, we can run the command more easily on the remote server from the client

![Image](last2.png)
> - this one I use 12 keystrokes by using the up head arrow to run the command


![Image](remote.png)
> - I use 69 keystrokes on executing the java file
> = the `;` could help us to type all the command first and run it one by one


---

