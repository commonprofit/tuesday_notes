# Basic Command Line Notes, 2017-06-20

## Basic concepts
(words in allcaps are hypothetical variables)

### The Terminal

* Most modern software / web development takes place in a Bash terminal that is or emulates a Unix / Linux operating system.
* We can do some programming directly in the terminal, but for the most part it is uses to quickly navigate around the computer and use special software that is only accessable from the command line.
* Despite the "desktop" experience we are accustomed to in Finder, the command line makes the computer look like it really is: a bunch of files and folders.
* `~` is shorthand for the user's directory.
* `/` by it self is shorthand for the root directory.
* Directories and files with names preceded by a dot (eg. `.ssh`) are "hidden" and won't appear in Finder.

### Commands for navigating the Terminal
* `ls` list what is in the current directory
* `ls PATH_TO_DIRECTORY/` list what is in the directory following the command
* `ls -a` list all the stuff in the directory, even if it is "hidden" (see above)
* `ls -la` list all the stuff in the directory, including hidden files, and their permissions
* `cd PATH_TO_DIRECTORY/` change directory to the one following the command
* `cd ../` chand to the directory above this one
* `pwd` print the current "working" directory
* `command + k` clears the terminal window (on a Mac)

### Commands for file manipulation in the Terminal
* `touch FILE_NAME.txt` makes a file of whatver type you want (but has no metadata)
* `mv FILE_NAME.txt NEW_FILE_NAME.txt` renames a file or moves it (if you specify a new directory)
* `cp FILE_NAME.txt COPIED_FILE_NAME.txt` copies a file
* `rm FILE_NAME.txt` deletes the file (no trash stage, so be sure!)
* `mdkir DIRECTORY_NAME` makes a new directory
* `rm -rf DIRECTORY_NAME` deletes the directory and everything in it (be careful! This is forever delete!)
* `cat FILE_NAME.txt` print out the contents of a file to the commandline

# Other useful things we did that we did not discuss:
1. Set up a `rsa.pub` key so that we could use `ssh` to push and pull to Github.

2. Play a little with `nano` and `vim` text editors.

# TODO for the week of the 26th

1. Symlink sublime text to open with commandline: `ln -sv "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl`

2. Make sure we get [Sourcetree](https://www.sourcetreeapp.com) working so that we can look at the subway map

3. HTML / CSS basics (make static webpage)
