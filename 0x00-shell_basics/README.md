# 0x00-shell_basics

This repository contains scripts that cover various aspects of working with the shell in Linux. The scripts are designed to help one learn the basics of using the shell and navigating the filesystem. Each script serves as a practical exercise to reinforce understanding of different shell commands and concepts.

## Repository Structure
- `0-current_working_directory`: Print the absolute path of the current working directory.
- `1-listit`: Display the contents of the current directory.
- `2-bring_me_home`: Change the working directory to the user's home directory.
- `3-listfiles`: Display current directory contents in a long format.
- `4-listmorefiles`: Display current directory contents, including hidden files, in a long format.
- `5-listfilesdigitonly`: Display current directory contents in a long format with user and group IDs displayed numerically.
- `6-firstdirectory`: Create a directory named `my_first_directory` in `/tmp/`.
- `7-movethatfile`: Move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.
- `8-firstdelete`: Delete the file `betty`.
- `9-firstdirdeletion`: Delete the directory `my_first_directory` in `/tmp/`.
- `10-back`: Change the working directory to the previous one.
- `11-lists`: List files and directories in the current directory, parent directory, and `/boot` in a specific order.
- `12-file_type`: Print the type of the file named `iamafile` in `/tmp/`.
- `13-symbolic_link`: Create a symbolic link to `/bin/ls` named `__ls__` in the current directory.
- `14-copy_html`: Copy all HTML files from the current directory to the parent directory.
- `100-lets_move`: Move files beginning with an uppercase letter to `/tmp/u/`.
- `101-clean_emacs`: Delete files ending with `~` in the current directory.
- `102-tree`: Create directories `welcome/`, `welcome/to/`, and `welcome/to/school` in the current directory.
- `103-commas`: List files and directories in the current directory separated by commas.
- `school.mgc`: A magic file to detect School data files.

## Usage
To test and run the scripts, make sure they are executable using `chmod u+x script_name`, and then run them with `./script_name`.
