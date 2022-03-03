### SHELL PERMISSIONS ###

1. su - Script that switches the current user to the user betty.
2. whoami- Script that prints the effective username of the current user.
3. groups - script that prints all the groups the current user is part of.
4. chown hello betty - script that changes the owner of the file hello to the user betty
5. touch hello - script that creates an empty file called hello.
6. chmod u+x hello - script that adds execute permission to the owner of the file hello.
7. chmod ug+x,o+r hello - script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
8. chmod a+x hello - script that adds execution permission to the owner, the group owner and the other users, to the file hello
9. chmod 007 hello - Write a script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions
10. chmod 753 hello - script that sets the mode of the file hello to this:
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
