## 0-iam_betty,My name is Betty
Create a script that switches the current user to the user betty.

You should use exactly 8 characters for your command (+1 character for the new line)
You can assume that the user betty will exist when we will run your script
## 1-who_am_i,Who am I
a script that prints the effective username of the current user.
## 2-groups,Groups
a script that prints all the groups the current user is part of.
## 3-new_owner,New owner
a script that changes the owner of the file hello to the user betty.
## 4-empty, Empty!
a script that creates an empty file called hello.
## 5-execute,Execute
a script that adds execute permission to the owner of the file hello.
## 6-multiple_permissions,Multiple permissions
a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
## 7-everybody, Everybody!
a script that adds execution permission to the owner, the group owner and the other users, to the file hello
## 8-James_Bond,James Bond
a script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions
## 9-John_Doe,John Doe
a script that sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
## 10-mirror_permissions,Look in the mirror
a script that sets the mode of the file hello the same as olleh’s mode.
## 11-directories_permissions,Directories
a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
## 12-directory_permissions,More directories
a script that creates a directory called my_dir with permissions 751 in the working directory.
## 13-change_group,Change group
a script that changes the group owner to school for the file hello
