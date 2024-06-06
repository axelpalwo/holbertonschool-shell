This repository its made for exercises about permissions
0- This script was made with su so you can change user
1- This script uses 'whoami' command to know the actual user
2- This script uses 'groups' command to know the groups of the actual user
3- This script changes the owner of a file with command 'chown betty hello'
4- This script creates an empty file with command 'touch'
5- This script uses chmod +rwx to add EXECUTE permissions
6-This script uses chmod u+x
7-This script uses chmod a+x
8-This script uses chmod 007
9-This script uses chmod 753
10-This script uses chmod --reference= to get references from a certain file to get permissions to another one
11-This script uses a selector to */ and flag -R recursive to add executing permissions to every subdirectory in the current work directory 
12-This script uses MkDir with flag -m to create a Dir with permissions
13-This script uses chown
14-This script uses the flag -R for recursive, Chown -R vincent:staff .
15-This script uses the flag -h for symbolic links
16-This script uses the flag --from of chown to change the owner IF it's another one chown --from OriginalOwner:OriginalGroup NewOwner:NewGroup File
