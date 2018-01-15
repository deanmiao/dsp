# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > 
* pwd --show current working directory path
* mkdir --creating a directory
* rm -r <foldername>/ --deleting a directory
* touch <fileName> --creating a file using `touch` command
* rm <fileName> --deleting a file
* mv filename.txt filename2.txt --renaming a file
* ls -a --listing hidden files
* cp image.jpg <folderName>/ --copying a file from one directory to another
* cd ../../.. --go up certain numbers of levels in a directory
* cd <folderName> --change directory
* cd / --go to root
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh` 
`ls -lah` 
`ls -t`  
`ls -Glp`  

> > 
`ls`  list files in current directory
`ls -a`  list all files including hidden files in current directory
`ls -l`  list certain type of files only "ls -l x.csv"
`ls -lh` list files in details
`ls -lah`  list files in details in human readable format
`ls -t`  sort the list of files by modification time
`ls -Glp`  long listing append indicators to directories

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 
`ls -u` Displays files by the file access time
`ls -m` Displays the names as a comma-separated list
`ls -r` Displays files in reverse order
`ls -t` Displays newest files first. (based on timestamp)
`ls -1` Displays each entry on a line


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs is a command to build and execute commands from standard input
An example would be to find a specific item using xargs. Xargs executes each space separated command once
find /path -type f -print | xargs rm

 

