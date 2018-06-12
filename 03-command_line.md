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

> > * show current working directory path -- pwd
* creating a directory -- mkdir
* deleting a directory -- rm -r
* creating a file using `touch` command -- touch abc.txt
* deleting a file -- rm 
* renaming a file -- mv old.txt new.txt
* listing hidden files -- ls -a
* copying a file from one directory to another -- cp a/abc.txt b/
* move a file -- mv abc.txt a/
* Redirect text to a file  -- echo "Hello" > hello.txt
* output the contents of a file --cat abc.txt
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

> >`ls`  -- list all files in directories
`ls -a`  -- list hiden files as well
`ls -l`  -- list details of all the files
`ls -lh` -- list long format with readable file size 
`ls -lah` -- list long format with readable file size of hidden files as well 
`ls -t`  -- 	sort by time & date
`ls -Glp` --  list long format but removes owner name

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -a, ls -l, ls -d, ls -R,   

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > It lets buld and execute commands from standard input
echo 'one two three' | xargs mkdir

 

