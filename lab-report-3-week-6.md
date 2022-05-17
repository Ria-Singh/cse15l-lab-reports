## Lab report 3
-----
# Part 1 - Streamlining ssh Configuration
this image shows the config file
![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-05-16%20at%209.24.36%20PM.png)

now a quick command can be used to log into the remote account
![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-05-16%20at%209.28.54%20PM.png)

Below is how i copied DemoFile.txt to the remote account
![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-05-16%20at%209.36.11%20PM.png)

# PART 2: Setup Github Access from ieng6
This is my public ssh key on github
![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-05-16%20at%209.43.41%20PM.png)

After copying my public ssh key, I am unable to make changes to my git as I am getting the following error
![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-05-16%20at%209.48.10%20PM.png)

# Part 3 - Copy whole directories with scp -r
Copying the markdown-parser directory to ieng6:
![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-05-16%20at%2010.04.49%20PM.png)

![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-05-16%20at%2010.04.58%20PM.png)

![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-05-16%20at%2010.05.06%20PM.png)

Now while being logged in ieng6, compiling and running my tests:

![](https://github.com/Ria-Singh/cse15l-lab-reports/blob/main/Screenshot%202022-05-16%20at%2010.20.46%20PM.png)

my tests are failing because the refernce to the file sin my .java file is to the absolute path of those files in my computer since that never
gives me a filenotfound exception. The tests will run correctly once I fix the file


