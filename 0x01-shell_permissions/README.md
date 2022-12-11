## TASKS DONE INSIDE THE 0x01-shell_permissions DIRECTORY

	0 -Created the file 0-iam_betty, it runs a script that switches the current user to the user betty.

	1 -The file 1-who_am_i contains a script that prints the effective username of the current user.

	2 -The '2-groups' file contains a script that prints all groups the current user is part of.

	3 -Created the file 3-new_owner, it changes the owner of the file 'hello' to betty.

	4 -The file 4-empty contains a script that creates an empty file named hello.

	5 -Created the file 5-execute, it adds the execute permission to the owner of the file hello.

	6 -The file 6-multiple_permissions writes a script that adds execute permission to the owner and the group owner, and read permission to
	 other users, to the file hello.

	7 -Created the file 7-everybody, it runs  a script that adds execution permission to the owner, the group owner and the other users, 
	to the file hello.

	8 -The file 8-James_Bond Write a script that sets the permission to the file hello as follows:



Owner: no permission at all

Group: no permission at all

Other users: all the permissions

	9 -The file 9-John_Doe Write a script that sets the mode of the file hello to this:



-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

	10 -The file 10-mirror_permissions contains a script that  sets the mode of the file hello the same as olleh’s mode.



The file hello will be in the working directory

The file olleh will be in the working directory.

	11 -Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

	12 -Create a script that creates a directory called my_dir with permissions 751 in the working directory

	13 -Write a script that changes the group owner to school for the file hello

