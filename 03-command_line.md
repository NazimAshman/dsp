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

ls:  lists files and folders in a directory
cd: change directory
cd ..: move directory up one step
pwd: prints working directory
mkdir: make directory
rmdir: deleted an empty directory
touch: creates new file
cp: copies files or directories
mv: moving a file from one directory to another, can also be used to rename files
rm: deletes files and directories (-r deletes the children too)
Tab: autocomplete
cat: outputs the contents of a file to the terminal
> : replace
>> : append
wc : outputs number of lines, words and characters in a file.
sort : sorts standard input alphabetically
uniq : filters out adjacent duplicant lines
grep : global regular expression print
sed: stream editor, similar to find and replace. Example: sed 's/snow/rain/' forests.txt . This seacrehs forest.txt for snow and replaces it with rain.
nano : command line text editor
alias : let's you store shortcuts


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

ls: lists all files and folders within a directory.
ls -a: lists all contents, including hidden files and directories
ls -l: lists all contents of a directory in long format
ls -lh: long listing with Human readable file sizes
ls -lah: long listing of all files and folders(including hidden) with Human readable file sizes
ls -t: order files and directories by the time they were last modified
ls -Glp: long listing with group names excluded, directories displayed with /


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:


ls -t,ls -a,ls -l,ls -R,ls -u.

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

xargs converts input from standard input into arguments to a command. Common example is used in combination with the find command. Exampl: find /tmp -mtime +14 | xargs rm. This finds files that are older than 2 weeks and deletes them.

 

