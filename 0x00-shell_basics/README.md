Task 0 - prints the absolute path name of the current working directory - pwd

Task 1 - Display the contents list of your current directory - ls

Task 2 - Write a script that changes the working directory to the user’s home directory, without any shell variables - cd

Task 3 - Display current directory contents in a long format - ls -l

Task 4 - Display current directory contents, including hidden files (starting with .). Use the long format - ls -al

Task 5 - Display current directory contents.
Long format, with user and group IDs displayed numerically, And hidden files (starting with .) - ls -lna

Task 6 - Create a script that creates a directory named my_first_directory in the /tmp/ directory - mkdir /tmp/my_firs_directory

Task 7 - Move the file betty from /tmp/ to /tmp/my_first_directory - mv /tmp/betty /tmp/my_first_directory

Task 8 - Delete the file betty from /tmp/my_first_directory - rm /tmp/my_first_directory/betty

Task 9 - Delete the directory my_first_directory that is in the /tmp directory - rm -r /tmp/my_first_directory

Task 10 - Write a script that changes the working directory to the previous one - cd -

Task 11 - Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format - ls -al . .. /boot

Task 12 - Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script - file /tmp/iamafile

Task 13 - Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory - ln -s /bin/ls _ls_

Task 14 - Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
You can consider that all HTML files have the extension .html - cp -u *.html ..

Task 15 - Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
You can assume that the directory /tmp/u will exist when we will run your script - mv *[[:upper:]] /tmp/u

Task 16 - Create a script that deletes all files in the current working directory that end with the character ~ - rm *~

Task 17 - Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
You are only allowed to use two spaces (and lines) in your script, not more - mkdir -p welcome/to/school

Task 18 - Write a command that lists all the files and directories of the current directory, separated by commas (,)
Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line - ls -xamp

Task 19 - Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0 - 0 string SCHOOL School data !:mime school
