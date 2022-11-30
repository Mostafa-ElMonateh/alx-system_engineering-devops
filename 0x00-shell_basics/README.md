0-current_working_directory script prints the present working directory.
1-listit script prints the list.
2-bring_me_home script makes me go to the home.
3-listfiles script prints the list in a long format.
4-listmorefiles script prints the list with hidden files in a long format.
5-listfilesdigitonly script prints a current directory contents in a log form with user and group IDs displayed numerically and hidden files.
6-firstdirectory script creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile script moves /tmp/betty to /tmp/my_first_directory.
8-firstdelete script deletes /tmp/my_first_directory/betty .
9-firstdirdeletion script deletes /tmp/my_first_directory .
10-back script changes the working directory to the previous one.
11-lists script lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type script prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13-symbolic_link script Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
14-copy_html script copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
100-lets_move script moves all files beginning with an uppercase letter to the directory /tmp/u.
101-clean_emacs script deletes all files in the current working directory that end with the character ~.
102-tree script creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. You are only allowed to use two spaces (and lines) in your script, not more.
103- 103-commas script lists all the files and directories of the current directory, separated by commas (,).
- Directory names should end with a slash (/)
- Files and directories starting with a dot (.) should be listed
- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
- Only digits and letters are used to sort; Digits should come first
- You can assume that all the files we will test with will have at least one letter or one digit
- The listing should end with a new line.
school.mgc is a magic file.
