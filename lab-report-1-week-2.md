# Lab Report 1 (Week 2)

## - Installing VScode
![Image](install.png)
> - go to the vscode website
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
![Image](remote.png)
> - after we setting the ssh key, we can run the command more easily on the server from the client


---

