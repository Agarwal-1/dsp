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

>>* show current working directory path: pwd
  * change directory: cd
  * creating a directory: mkdir
  * deleting a directory: rmdir
  * creating a file using `touch` command :touch
  * deleting a file: rm
  * renaming a file: mv
  * listing hidden files: ls -a
  * copying a file from one directory to another: CP
  *outputs the contents of a file to the terminal: cat

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
`ls`  -lists all files in the directory
`ls -a`  -all files (including hidden)
`ls -l`  -displays long form
`ls -lh`  -long form, human readable
`ls -lah`  -long form, all files, human readable
`ls -t`  -orders files and directories by when they were last modified
`ls -Glp`- long form excluding owners name, long form lists, displays directories with a /


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

ls -R: displays subdirectories
ls -i: enables the command to be case insensitive
ls -r: recursive, deletes directories and child directories
ls -u: displays file by last time accessed
ls -x: displays files as rows

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > Xargs takes output of a command and passes it as an argument of another command
xargs find -name "*.txt".  The find command will search all text files in the current directory for name.

 

