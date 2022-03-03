su change user
whoami -print current user
less etc/group
chown change ownership
touch create an empty file
chmod u+x add execute permission to a user
chmod ug+x,o+r hello Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod a+x add execute permission to all
chmod 007 
    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions
chmod 753 Write a script that sets the mode of the file hello to this:-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
chmod --reference=olleh hello mirror permissions
chmod a+X * adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

