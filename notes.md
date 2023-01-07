# Intro to Web Development
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

---

*ITALICS*

__BOLD__

1. Organized list
2. Ain't it sweet
    1. Hello

* Unorganized List
* Ain't it pretty
    * World

`This is a code snippet`

```
This
is
a
code
block
```

## Development Websites
* mozilla.org
* javascript.info

# Source Code and GitHub

## Git Help for MTEC

1. git status
2. git add < . --all [filename] >
3. git commit -m ""
4. git status to verify
5. git push 

### Branches

1. git branch >> will find out what branch you are in and what branches that have already been created
2. git branch [branchName]
    * git checkout -b [branchName]
3. 


### Merge and Diff
1. git checkout -b [branchName]
2. make changes to files
3. git add and commit
4. git push
5. git merge main
6. git diff main [branchName]

### Merge Errors
* When working with branches make sure to pull before you push your code it helps avoiding merge problemscd 

## Bash Shell
* Bash is a command line shell
    * gives you UNIX commands
    * effciently to run complex tasks
* Dominant shell on UNIX
* The UNIX philosoply
    * Write programs that do one thing and do it well
    * Write programs to work well
    * Write programs to handle text streams
        * because that is a universal interface
* Copying Command
    * `cp -R source_dir target_dir`
    * you can have multiple directories for the source directory even a files will work
* Remove Command
    * rm will permantently remove files
    * rmdir will remove empty directories
    * rm -r will remove directories and everything in it 
        * be careful with this command there is no going back
* Inspect Command
    * -i
        * `rm -ri` will ask you if want to remove directory and files one by one
* You can checkout on commits
    *     do git log to find the unique commit source name to checkout to
