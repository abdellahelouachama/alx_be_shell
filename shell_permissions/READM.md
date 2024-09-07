#!/bin/bash
0-iam_betty
Description: This script switches the current user to the user betty. The command used in the script is exactly 8 characters long, plus 1 newline character.

Command in the Script:
su betty

1-who_am_i
Description: This script prints the effective username of the current user.

Command in the Script:
whoami

4-empty
Description: This script creates an empty file named hello in the current directory.

Command in the Script:
touch hello

5-execute
Description: This script adds execute permission to the owner of the file hello.

Command in the Script:
chmod u+x hello

6-multiple_permissions
Description: This script adds execute permission for the owner and the group, and read permission for others, to the file hello.

Command in the Script:
chmod u+x,g+x,o+r hello

9-John_Doe
Description: This script sets the permissions of the file hello to -rwxr-x-wx.

Command in the Script:
chmod 753 hello
