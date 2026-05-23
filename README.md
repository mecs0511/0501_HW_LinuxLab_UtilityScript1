# This Is What My Script Does

My script has to directories that makes it easier to locate files quickly because related files are grouped together logically.

Multiple directories help automate scripts more efficiently since the script knows exactly where to read input files and where to save results or backups.

Sample files are used in my script to test the script or program to make sure it works correctly before using real data.

They help demonstrate how input and output should look, making it easier to troubleshoot errors and verify results.

Printing status messages in the terminal give real-time feedback so I can see what the script is doing and if each step is working correctly.

I write content into a file because creates a permanent record of results that can be saved, reviewed later, and used for reporting or debugging.

Keeping a duplicate in case the original is lost or deleted and the duplicate of the original file in another location while keeping the original unchanged.

Organizing data by placing it in the correct folder or storage location for easier access can be why you would want to move files.

It also removes temporary files or folders to free up storage space and to help improve system performance. or deleting temporary files reduces clutter and can prevent errors caused by 

outdated or unnecessary data.

I displayed the contents of a directory to help verify that the correct files and folders were created or copied during a script or terminal tasks.

My script also has a printing working directory which prevents mistakes by ensuring the script is running in the correct directory before creating, moving, or deleting files.

The script will include the current date and time in a report or log file to track when actions, updates, or script executions occurred and it makes 

troubleshooting easier by providing a timeline of events and helping identify when errors or changes happened. 

I have a final report or summary file confirms that the script completed successfully and produced the expected output and this

also allows me to quickly review the collected information, results, or logged activities without opening the file separately.







# Definitions For Each Linux Command Used In The Script1. 

1. #!/bin/bash

Definition:

This is called the shebang line. It tells Linux to use the Bash shell interpreter to run the script.

Why It Was Used:

It ensures the script runs using Bash so all Bash commands and syntax work correctly.

2. mkdir

mkdir -p ~/practice_script/docs

Definition:

mkdir stands for make directory. It creates folders/directories.

Why It Was Used:

It was used to create folders to organize documents, logs, and archived files.

3. -p

Definition:

-p is an option used with mkdir. It creates parent directories if they do not exist and avoids errors if the directory already exists.

Why It Was Used:

It allows the script to safely create nested folders like:

~/practice_script/docs

4. ~

Definition:

~ represents the current user’s home directory.

Why It Was Used:

It makes the script portable because it automatically saves files inside the current user’s home folder.

5. touch

touch ~/practice_script/docs/file1.txt

Definition:

touch creates a new empty file.

Why It Was Used:

It was used to create the text files:

file1.txt
file2.txt

6. echo

echo "This is file 1"

Definition:

echo displays text on the terminal or sends text into a file.

Why It Was Used:

It was used to add text content into the files.

7. 

Definition:

is an output redirection operator. It writes output to a file and overwrites existing content.

Why It Was Used:

It was used to place the first line of text into each file.

Example:

echo "This is file 1" > ~/practice_script/docs/file1.txt

8. 

Definition:

appends text to the end of a file without deleting existing content.

Why It Was Used:

It was used to add a second line to file1.txt.

9. cat

cat ~/practice_script/docs/file1.txt

Definition:

cat stands for concatenate. It displays the contents of a file.

Why It Was Used:

It was used to show the text stored inside file1.txt.

10. cp

cp ~/practice_script/docs/file1.txt ~/practice_script/archive/

Definition:

cp means copy. It duplicates files or directories.

Why It Was Used:

It was used to create a backup copy of file1.txt inside the archive folder.

11. mv

mv ~/practice_script/docs/file2.txt ~/practice_script/archive/

Definition:

mv means move. It moves or renames files and folders.

Why It Was Used:

It was used to move file2.txt from the docs folder into the archive folder.

12. ls

ls -l ~/practice_script/

Definition:

ls lists files and directories.

Why It Was Used:

It was used to display the contents of the practice_script folder.

13. -l

Definition:

-l is an option for ls that shows a long listing format with detailed information such as:

permissions
owner
file size
modification date

Why It Was Used:

It provides more detailed information about the files and folders.

14. pwd

pwd

Definition:

pwd stands for print working directory.

Why It Was Used:

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

Why It Was Used:

chmod +x gives a script executable permission so it can be run directly.

Example:

chmod +x script.sh

This allows the script to execute like:

./script.sh
