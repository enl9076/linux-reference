# linux-reference
Simple Linux reference guide

Terminal commands
* cp: copy; use -r flag to copy a directory and all of its contents
* mv: move
* rm: remove a file or directory; add -r flag to remove a directory and its contents
* less/more: interactively view the contents of a file; use q to exit
* mkdir: make a new directory
* cat: print out the contents of a file
* head/tail: use in conjunction with -n N to print out N number of lines from a file to the console
* grep: search for text in files; use -r flag to recursively search directories/files
* find: locate a file by its name
* whoami: display username
* chmod: change the permissions of a file or directory
* chown: allows the user to change the owner of a file or directory (requires `sudo`)
* which: tells you the location of an installed command line program
* export: set an environment variable (name of variable must be capital)
* $? : use echo with this command to print out the exit code of the last run command

Other useful things:
Ctrl + C to interrupt a command or program
kill [PID]: manually kill a process that cannot be interrupted with ctrl c; PID is the process ID # that can be found by running ps aux
