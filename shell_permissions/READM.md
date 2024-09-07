0-iam_betty
This script switches the current user to the user betty.

The command used in the script is exactly 8 characters long (plus 1 newline character), adhering to the specified constraint.
You can assume that the user betty exists on the system when the script is executed.
Usage:
Run the script using the following command:./0-iam_betty
Command in the Script:
The script contains the following single command to switch to the user betty:su betty
su betty: Switches the current session to the betty user.
1-who_am_i
This script prints the effective username of the current user.

Usage:
Run the script using the following command
./1-who_am_i
Command in the Script:
The script contains the following command:
whoami
whoami: Outputs the effective username of the current user

create_hello.sh
This script creates an empty file named hello.

Usage:
Run the script using the following command:

./create_hello.sh
Command in the Script:
The script contains the following command:

touch hello
touch hello: Creates an empty file called hello in the current directory. If the file already exists, it updates its timestamp without altering its contents.
add_execute_permission.sh
This script adds execute permission for the owner of the file hello.
Command in the Script:
chmod u+x hello
chmod u+x hello: Grants execute permission to the owner of the file hello.


update_permissions.sh
This script sets permissions for the file hello:

Adds execute permission for the owner and group.
Adds read permission for others.
Command in the Script:
chmod u+x,g+x,o+r hello

set_permissions.sh
This script sets the file hello to have the following permissions:

rwxr-x-wx
Command in the Script:
chmod 753 hello
