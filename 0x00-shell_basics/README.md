#!/bin/bash
Task 0: Script that prints the absolute path name of the current working directory - pwd

Task 1: Script to display the contents list of your current directory - ls

Task 2: Script to change directory to home without using any shell variables - cd

Task 3: Script to display current directory contents in a long format - ls -l

Task 4: Script to display current directory contents, including hidden files (starting with .). Use the long format - ls -la

Task 5: Script to Display current directory contents.
Long format
with user and group IDs displayed numerically
And hidden files (starting with .) - ls -na

Task 6: Script to create a directory named my_first_directory in the /tmp/ directory - mkdir /tmp/my_first_directory

Task 7: Script to move the file betty from /tmp/ to /tmp/my_first_directory - mv /tmp/betty /tmp/my_first_directory

Task 8: Script to  delete the file betty.
The file betty is in /tmp/my_first_directory - rm /tmp/my_first_directory/betty

Task 9: Script to delete the directory my_first_directory that is in the /tmp directory - rm -r /tmp/my_first_directory

Task 10: Script to change the working directory to the previous one - cd -

Task 11: Script to lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format - ls . .. /boot -la

Task 12: Script to print the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script - file /tmp/iamafile

Task 13: Script to create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory - ln -s /bin/ls __ls__

Task 14: Script to copy all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
You can consider that all HTML files have the extension .html - cp -u *.html ..

Task 15: Script to move all files beginning with an uppercase letter to the directory /tmp/u - mv [[:upper:]]* /tmp/u

Task 16: Script to delete all files in the current working directory that end with the character ~ - rm *~

Task 17: Script to create the directories welcome/, welcome/to/ and welcome/to/school in the current directory - mkdir -p welcome/to/school

Task 18: Script to lists all the files and directories of the current directory, separated by commas (,).
Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line - ls -xmpa

Task 19: Script to create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0 - 0	string SCHOOL School data
!:mime school
