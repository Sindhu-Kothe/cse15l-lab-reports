Lab Report 1


Tutorial about how to log on to ieng6

## Installing VSCode. 
![Image](SS1.png)

* To install VSCode, go to this [link](https://code.visualstudio.com/)

* Also, download Java. A version after Java 14 is preffered. 

* VSCode could be used to edit Java files and GitHub pages, like this one. 


## Remoteley Connecting
![Image](SS2.png)

* I am using a Mac so I do not need to install OpenSSH but if you are using a Windows laptop, go to this [link](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)

* Now, look up your [course-specific account ](https://sdacs.ucsd.edu/~icc/index.php) for the course. You might have to change your password. My course specific account is cse15lwi22atw@ieng6.ucsd.edu

* Now, open a new terminal (Terminal -> New Terminal), and type the following code: 
> $ ssh cs15lwi22zz@ieng6.ucsd.edu



## Trying Some Commands
![Image](SS3.png)
* Different commands show different aspects of the file that is being run. 

* These are what some of the commands do:
    * cd ~ : change to home directory. 
    * cd: change directory
    * ls: lists all the files in current directory
        * ls - l: all the info about the file, long listed
        * ls-a: shows all the hidden files starting with .
        * ls-lt: lists all the files and when you last edited them in order of when they were last edited
    * pwd: **p**resent **w**orking **d**irectory




## Moving some files with scp
![Image](SS4.png)

* The command to copy files from one computer to a remote computer is called scp. 

* In the screenshot, we see that the variables that print out the locations of the file change. The first time, it prints out the details of my laptop. The second time, the details of the server are shown. 


## Setting an SSH key 

## Optimizing remote running