## Lab report 1
-----

### Installing VSCode:

I installed VSCode from the internet previously by following the instructions for MAC OS on the website. The following screenshot is of my installed VSCode:


![ ](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-03-31%20at%204.15.12%20PM.png)
### Remotely Connecting

To remotely connect to the server, I used the command ssh followed by my CSE 15L account. This lead to the terminal prompting for some answers such as whether to connect to continue connecting followed my my account password. The following screenshot demonstrates the terminal prompts: 


![ ](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-03-31%20at%204.24.14%20PM.png)

### Trying some commands

After successfully connecting to the remote computer, I experimented with some commands to get the hang of using the terminal as well as understanding how these commands work and what outputs they give. I used the the ls command to list all the files: 

![ ](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-03-31%20at%204.31.27%20PM.png)

### Moving files with scp

I created a java file called WhereAmI.java which tells me the name of the user, operating system, directory, etc then using the command `scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:` I move the files to the remote server which can be seen when the `ls` command is used as can be seen in the screenshot below.

![ ](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-03-31%20at%204.41.24%20PM.png)

### Setting an SSH key

An ssh key is then set up to make logging into the remote server faster and less cumbersome. This is done by using the `ssh-keygen` command to create a public and private key which are then saved and used to log in to the server. The process is seen in the screenshot below 

![ ](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-03-31%20at%205.42.40%20PM.png)

### Optimizing remote running

The last step was to figure out how to run commands even faster. This can be done by using ssh followed by my account name and the the command I want to run in quotes. The one command does it all since there a ssh key set up already. It can be seen in the screenshot below
![ ](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-03-31%20at%205.42.50%20PM.png)








