# Shell, permissions
This repository contains scripts that deal with permissions in linux

1. 0-iam_betty: This script switches the current user to the user betty.

2. 1-who_am_i: This script prints the effective username of the current user.

3. 2-groups: This script prints all the groups the current user is part of.

4. 3-new_owner: This script changes the owner of the file hello to the user betty.

5. 4-empty: This script creates an empty file called hello.

6. 5-execute: This script executes permission to the owner of the file hello.

7. 6-multiple_permissions: This script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

8. 7-everybody: This script adds execution permission to the owner, the group owner and the other users, to the file hello.

9. 8-James_Bond: This script sets the permission to the file hello as follows:

         Owner: no permission at all
      	 Group: no permission at all
      	 Other users: all the permissions

10. 9-John_Doe: This script sets the mode of the file hello to this:

    		-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
    
	The file hello will be in the working directory
    	There will be no use of commas for this script

11. 10-mirror_permissions: This script sets the mode of the file hello the same as olleh’s mode.

        This file hello will be in the working directory
    	The file olleh will be in the working directory

12. 11-directories_permissions: This script adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

13. 12-directory_permissions: This script creates a directory called my_dir with permissions 751 in the working directory.