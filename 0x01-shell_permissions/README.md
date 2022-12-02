1. su -l betty switches the current user to the user betty
2. whoami prints the effective username of the current user
3. groups prints all the groups the current user is part of
4. sudo chown betty hello changes the owner of the file hello to the user betty
5. touch hello creates an empty file called hello
6. chmod 744 hello adds execute permission to the owner of the file hello
7. chmod 774 hello adds execute permission to the owner and the group owner, and read permission to other users
8. chmod 777 hello adds execution permission to the owner, the group owner and the other users, to the file hello
9. chmod 007 hello sets the permission to the file hello as follows: no permission at all to owner; no permission at all to group; all the permissions to other users
10. chmod 753 
