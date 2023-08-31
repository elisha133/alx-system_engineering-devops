# 0x01-shell_permissions

Welcome to the **0x01-shell_permissions** project! This project focuses on understanding and applying Linux file permissions and various commands related to permissions and user management.

## Table of Contents

1. [About Bash projects](#about-bash-projects)
2. [Learning Objectives](#learning-objectives)
3. [Requirements](#requirements)
4. [Tasks](#tasks)
   - [Task 0: My name is Betty](#task-0-my-name-is-betty)
   - [Task 1: Who am I](#task-1-who-am-i)
   - [Task 2: Groups](#task-2-groups)
   - [Task 3: New owner](#task-3-new-owner)
   - [Task 4: Empty!](#task-4-empty)
   - [Task 5: Execute](#task-5-execute)
   - [Task 6: Multiple permissions](#task-6-multiple-permissions)
   - [Task 7: Everybody!](#task-7-everybody)
   - [Task 8: James Bond](#task-8-james-bond)
   - [Task 9: John Doe](#task-9-john-doe)
   - [Task 10: Look in the mirror](#task-10-look-in-the-mirror)
   - [Task 11: Directories](#task-11-directories)
   - [Task 12: More directories](#task-12-more-directories)
   - [Task 13: Change group](#task-13-change-group)
   - [Task 14: Owner and group](#task-14-owner-and-group)
   - [Task 15: Symbolic links](#task-15-symbolic-links)
   - [Task 16: If only](#task-16-if-only)
   - [Task 17: Star Wars](#task-17-star-wars)

## About Bash projects

This project involves working with Bash scripts to perform various tasks related to Linux file permissions, user management, and related commands. Your scripts should be concise and adhere to specific requirements outlined in the project guidelines.

## Learning Objectives

By completing the tasks in this project, you will achieve the following learning objectives:

- Gain an understanding of Linux file permissions.
- Explain the purpose of commands like `chmod`, `sudo`, `su`, `chown`, and `chgrp`.
- Learn how to represent file permissions using numeric values.
- Know how to change permissions, owner, and group of a file.
- Understand the limitations of a normal user in changing ownership (`chown`) of files.
- Learn how to run commands with root privileges using `sudo`.
- Understand how to change user ID or become a superuser.
- Explore other relevant commands and man pages for user and group management.

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- Scripts will be tested on Ubuntu 20.04 LTS
- Do not use backticks, `&&`, `||`, or `;`
- All files must be executable

## Tasks

The project comprises several tasks, each designed to enhance your understanding of Linux permissions and commands. Below is a list of tasks and their descriptions:

### Task 0: My name is Betty

Create a script that switches the current user to the user betty. The script should be no longer than 8 characters.

### Task 1: Who am I

Write a script that prints the effective username of the current user.

### Task 2: Groups

Write a script that prints all the groups the current user is part of.

### Task 3: New owner

Write a script that changes the owner of the file hello to the user betty.

### Task 4: Empty!

Write a script that creates an empty file called hello.

### Task 5: Execute

Write a script that adds execute permission to the owner of the file hello.

### Task 6: Multiple permissions

Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

### Task 7: Everybody!

Write a script that adds execution permission to the owner, the group owner, and other users for the file hello.

### Task 8: James Bond

Write a script that sets specific permissions for the file hello:
- Owner: no permission at all
- Group: no permission at all
- Other users: all permissions

### Task 9: John Doe

Write a script that sets the mode of the file hello to a specific pattern.

### Task 10: Look in the mirror

Write a script that sets the mode of the file hello the same as the mode of another file, olleh.

### Task 11: Directories

Create a script that adds execute permission to all subdirectories of the current directory for the owner, group owner, and all other users.

### Task 12: More directories

Create a script that creates a directory called my_dir with specific permissions in the working directory.

### Task 13: Change group

Write a script that changes the group owner of the file hello to a specific group.

### Task 14: Owner and group

Write a script that changes the owner and group owner of all files and directories in the working directory to specific values.

### Task 15: Symbolic links

Write a script that changes the owner and group owner of a symbolic link to specific values.

### Task 16: If only

Write a script that changes the owner of the file hello to betty, but only if the current owner is guillaume.

### Task 17: Star Wars

Write a script that plays the Star Wars Episode IV in the terminal.

Feel free to explore each task's script and execute them to better understand the concepts and commands covered in this project. Good luck, and happy scripting!
