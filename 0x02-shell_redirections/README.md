### 0x02. Shell, I/O Redirections and filters ###
1. echo "Hello, World" - A script that prints “Hello, World”,
2. echo "\"(Ôo)'" - A script that displays a confused smiley "(Ôo)'
3. cat /etc/passwd - Script to display the content of the /etc/passwd file
4. cat /etc/passwd /etc/hosts - Display the content of /etc/passwd and /etc/hosts
5. tail /etc/passwd - Display the last 10 lines of /etc/passwd
6. head /etc/passwd - Display the first 10 lines of /etc/passwd
7. head -3 iacta | tail -1 - Script that displays the third line of the file iacta.
8. echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)" - A shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a ne
9. ls -la > ls_cwd_content - a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it
10. tail -1 < iacta >> iacta - script that duplicates the last line of the file iacta.
11. find -name "*.js" -type f -delete - Script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
12.find . -type d ! -path . -print | wc -l - script that counts the number of directories and sub-directories in the current directory.
13. ls -1t | head -10 - a script that displays the 10 newest files in the current directory.
14. sort | uniq -u - Script that displays all users and their home directories, sorted by users.
15. grep "root" /etc/passwd - Display lines containing the pattern “root” from the file /etc/passwd
16. grep -c "bin" /etc/passwd - Display the number of lines that contain the pattern “bin” in the file /etc/passwd
17. grep -A 3 "root" /etc/passwd - Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
18. grep -v "bin" /etc/passwd - Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.`
