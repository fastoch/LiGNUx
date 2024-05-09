to print the current working directory (absolute path): `pwd`    

to create a directory in the working directory: `mkdir dirname`  

to create a directory in another directory: `mkdir path/dirname`

to get into this new directory: `cd dirname`  or `cd path/dirname`  

to go back to your home directory: `cd` or `cd ~`  

>[!tip]
>your home directory is represented with a tilde ~ in the cmd prompt

to go one level up (parent directory): `cd ..`  

to go to the root of the file system: `cd /`  

to remove an empty directory: `rmdir dirname` or `rm -d dirname`

to remove a non-empty directory: `rm -rf dirname` (-r = recursive, -f = force)  

>[!caution]
>be very careful when using `rm -rf`, as this cmd can destroy your entiresystem!

To be prompted before deletion: `rm -rfi dirname`