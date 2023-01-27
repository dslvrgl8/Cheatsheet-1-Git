# Bash Commands Cheatsheet

Here's a cheatsheet I'm using to remember some of the most common `bash` commands

# Navigating the file system

## **:The `cd` command:**
This is a command that stands for `change directory` and is commonly used to navigate throughout the file system
### Within cd:
#### `.` Current Directory
#### `..` Parent Directory
#### `~` Logged into user's home directory
#### `/` Root (top level) directory

## **:List Directory:**
`ls` lists all the files within a directory, with `ls -a` showing the hidden files

## **:Create a Directory:**
- `mkdir` creates directories
- `touch` creates files within
- if wanting to make a directory and change directories to the one you created, `mkdir _____ && cd _____`

## **:Moving Files:**
Use `mv` to move files, and be sure to specify where its going
- `mv` can also be used to __rename__ a file, very useful

## **:Deleting Directories:**
Use `rm` followed by `~r`, must be very careful, deletes permanently. Computer will safeguard in some instances

## **:Moving Multiple Files:**
Use `mv *.___`, and it will move all with that particular name, eg, socks will move all files starting with socks

## **:Copying Files and Directories:**
Use `cp` to copy, and add entire directories by ading `-R` option


# Github and Git Commands

## **:Git commands:**
- `git init` initializes local repository
- `git status` checks and reports on the staus of your repo, inofmr you of changes that will be included: 
     - git also does not care about empty folders
- `git commit -m "<Message>` commits all to local repository
    - MAKE SURE TO SAY WHAT YOU DID FOR EACH!!