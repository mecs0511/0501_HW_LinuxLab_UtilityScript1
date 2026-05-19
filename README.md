Definitions for Each Linux Command Used in the Script1. 

1. #!/bin/bash

Definition:
This is called the shebang line. It tells Linux to use the Bash shell interpreter to run the script.

Why It Was Used

It ensures the script runs using Bash so all Bash commands and syntax work correctly.

2. mkdir

mkdir -p ~/practice_script/docs
Definition:

mkdir stands for make directory. It creates folders/directories.

Why It Was Used

It was used to create folders to organize documents, logs, and archived files.

3. -p
Definition:

-p is an option used with mkdir. It creates parent directories if they do not exist and avoids errors if the directory already exists.

Why It Was Used

It allows the script to safely create nested folders like:

~/practice_script/docs

4. ~
Definition:

~ represents the current user’s home directory.

Why It Was Used

It makes the script portable because it automatically saves files inside the current user’s home folder.

5. touch

touch ~/practice_script/docs/file1.txt
Definition:

touch creates a new empty file.

Why It Was Used

It was used to create the text files:

file1.txt
file2.txt

6. echo

echo "This is file 1"
Definition:

echo displays text on the terminal or sends text into a file.

Why It Was Used

It was used to add text content into the files.

7. >
> 
Definition:

> is an output redirection operator. It writes output to a file and overwrites existing content.

Why It Was Used

It was used to place the first line of text into each file.

Example:

echo "This is file 1" > ~/practice_script/docs/file1.txt

8. >>
>>
Definition:

>> appends text to the end of a file without deleting existing content.

Why It Was Used

It was used to add a second line to file1.txt.

9. cat

cat ~/practice_script/docs/file1.txt
Definition:

cat stands for concatenate. It displays the contents of a file.

Why It Was Used

It was used to show the text stored inside file1.txt.

10. cp

cp ~/practice_script/docs/file1.txt ~/practice_script/archive/
Definition:

cp means copy. It duplicates files or directories.

Why It Was Used

It was used to create a backup copy of file1.txt inside the archive folder.

11. mv

mv ~/practice_script/docs/file2.txt ~/practice_script/archive/
Definition:

mv means move. It moves or renames files and folders.

Why It Was Used

It was used to move file2.txt from the docs folder into the archive folder.

12. ls

ls -l ~/practice_script/
Definition:

ls lists files and directories.

Why It Was Used

It was used to display the contents of the practice_script folder.

13. -l
Definition:

-l is an option for ls that shows a long listing format with detailed information such as:

permissions
owner
file size
modification date
Why It Was Used

It provides more detailed information about the files and folders.

14. pwd

pwd
Definition:

pwd stands for print working directory.

Why It Was Used

It shows the current directory where the user is working.

15. date

date
Definition:

date displays the current system date and time.

Why It Was Used

It was used to show when the script was executed.

16. chmod

chmod +x
Definition:

chmod changes file permissions.

Why It Was Used

chmod +x gives a script executable permission so it can be run directly.

Example:

chmod +x script.sh

This allows the script to execute like:

./script.sh
