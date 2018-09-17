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

> > show current working directory path -- 'pwd'
 creating a directory 'mkdir'
 deleting a directory 'rm'
 creating a file 'touch'
 deleting a file 'rm'
 renaming a file 'mv'
 listing hidden files 'attrib'
 copying a file from one directory to another 'cp' then list directory
 copying a directory and moving it to another 'cp -R'
 open a file 'open'
 find a text pattern in a file 'grep'
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

> > `ls`  lists files in directory
`ls -a`  includes files starting with '.'
`ls -l`  adds permissions
`ls -lh`  long format with readable filesize
`ls -lah`  long format, sorts alphabetically
`ls -t`  sorts by date
`ls -Glp`  long format, sorts alphabetically

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 'ls -R' -- lists subdirectories
'ls -d' -- lists directories
'ls -1' -- gives each entry a line
'ls -u' -- displays by access time
'ls -m' -- separates by commas (for csv use?)

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > Executes commands using standard input a number of times based on input. This can be used for any command, though echo is the standard.

**xargs -L 1 find '*.txt'**  lists all of the text files in the directory.

 

