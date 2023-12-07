# This is the readme file for shell permissions -ALX

## Task 0
### My name is Betty
A script that switches the current user to the user betty >> 0-iam_betty

## Task 1
### Who am I
A script that prints the effective username of the current user

## Task 2
### Groups
A script that prints all the groups the current user is in

## Task 3
### New Owner
A script that changes the owner of the file "hello" to the user betty.

## Task 4
### Empty!
A script that create an empty file called hello

## Task 5
### Execute
A script that adds execute permissions to the owner of the file hello NB: you should give read permissions to other users >> 5-execute

## Task 6
### Multiple Permissions
A script that add execute permissions to owner and group owner and read permission to other users >> 6-multiple_permissions.

## Task 7
### Everybody!
A script that adds executable privileges to all users. >> 7-everybody

## Task 8
### James Bond
A script that scraps all privileges from everyone except other users, they have all permissions >> 8-James_Bond.

## Task 9
### John Doe
A script that sets the mode of the file hello to this: -rwxr-x-wx >> 9-John_Doe

## Task 10
### Look in the mirror
A script that changes the mode of one file 'hello' to mirror another file 'olleh' >> 10-mirror_permissions.

## Task 11
### Directories
A script that changes the persions for just subdirectories in the current working directory. Giving executable permissions to the owner, group owner and other users >> 11-directories_permissions

## Task 12
### More directories
This script creates a file my_dir and sets it with permissions 751 at the same time. use the flag --mode=[mode] >> 12-directory_permissions

## Task 13
### Change group
A script that changes the group owner to school for the file hello >> 13-change_group

## Task 14
### Owner and group
A scipt that changes the owner to vincent and the group owner to staff for all files and directories. We are going to use chown: check man chown.. flag used is -R >> 100-change_owner_and_group

## Task 15
### Symbolic links
A script that changes the owner and group owner of a symbolic link. use man chown. I used the flaf -h in this code >> 101-symbolic_link_permissions

## Task 16
### If only
A script that changes the owner of a file hello to betty if it is owned by the user guillaume. I used chown and the --from flag.

## Task 17
### Star Wars
A script that plays the Star Wars IV episode in the terminal >> 103-Star_wars
