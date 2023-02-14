Shell, I/O Redirection

*What do the commands head, tail, find, wc, sort, uniq, grep, tr do
*How to redirect standard output to a file
*How to get standard input from a file instead of the keyboard
*How to send the output from one program to the input of another program
*How to combine commands and filters with redirections

Bash scripts to automate Shell, I/O Redirection tasks

0. 0-hello_world - This script prints “Hello, World”
1. 1-confused_smiley - This script displays a confused smiley "(Ôo)'.
2. 2-hellofile - This script displays the content of the /etc/passwd file. 
3. 3-twofiles - This script displays the content of /etc/passwd and /etc/hosts
4. 4-lastlines - This script displays the last 10 lines of /etc/passwd
5. 5-firstlines - This script displays the first 10 lines of /etc/passwd
6. 6-third_line - This script displays the third line of the file iacta
7. 7-file - This script creates creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8. 8-cwd_state - This script writes writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
9. 9-duplicate_last_line - This script duplicates the last line of the file iacta
10. 10-no_more_js - This script deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11. 11-directories - This script counts the number of directories and sub-directories in the current directory.
12. 12-newest_files - This script displays the 10 newest files in the current directory.
13. 13-unique - This script takes a list of words as input and prints only words that appear exactly once.
14. 14-findthatword - This script displays lines containing the pattern “root” from the file /etc/passwd
15. 15-countthatword - This script displays the number of lines that contain the pattern “bin” in the file /etc/passwd
16. 16-whatsnext - This script displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
17. 17-hidethisword - This script displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18. 18-letteronly - This script displays all lines of the file /etc/ssh/sshd_config starting with a letter.
19. 19-AZ - This script replaces all characters A and c from input to Z and e respectively.
20. 20-hiago - This script removes all letters c and C from input.
21. 21-reverse - This script reverse its input.
22. 22-users_and_homes - This script displays all users and their home directories, sorted by users.23. 100-empty_casks - This script writes a command that finds all empty files and directories in the current directory and all sub-directories.
24. 101-gifs - This script writes a script that lists all the files with a .gif extension in the current directory and all its sub-directories.
25. 102-acrostic - This script decodes acrostics that use the first letter of each line.
26. 103-the_biggest_fan - This script parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
