# Shell, I/O redirections

1. 0-hello_world: This script prints “Hello, World”, followed by a new line to the standard output.

2. 1-confused_smiley: This script displays a confused smiley "(Ôo)'.

3. 2-hellofile: This script displays the content of the /etc/passwd file.

4. 3-twofiles: This script displays the content of /etc/passwd and /etc/hosts

5. 4-lastlines: This script displays the last 10 lines of /etc/passwd.

6. 5-firstlines: This script displays he first 10 lines of /etc/passwd

7. 6-third_line: This script displays the third line of the file iacta. The file iacta will be in the working directory. It's done without the use of sed.

8. 7-file: This script creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

9. 8-cwd_state: This script writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

10. 9-duplicate_last_line: This script duplicates the last line of the file iacta. The file iacta will be in the working directory

11. 10-no_more_js: This script deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

12. 11-directories: This script counts the number of directories and sub-directories in the current directory. The current and parent directories should not be taken into account. Hidden directories should be counted

13.  12-newest_files: This script displays the 10 newest files in the current directory.

     Requirements:
     One file per line
     Sorted from the newest to the oldest	

14. 13-unique: This script takes a list of words as input and prints only words that appear exactly once.

       Input format: One line, one word
       Output format: One line, one word
       Words should be sorted

15. 14-findthatword: This script lines containing the pattern “root” from the file /etc/passwd.

16. 15-countthatword: This script displays the number of lines that contain the pattern “bin” in the file /etc/passwd.

17. 16-whatsnext: This script displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

18. 17-hidethisword: This script displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.

19. 18-letteronly: This script displays all lines of the file /etc/ssh/sshd_config starting with a letter. Include capital letters as well

20. 19-AZ: This script replaces all characters A and c from input to Z and e respectively.

21. 20-hiago: This script removes all letters c and C from input.

22. 21-reverse: This script reverses its input.

23. 22-users_and_homes: This script displays all users and their home directories, sorted by users. Based on the the /etc/passwd file

24. 100-empty_cask: This script finds all empty files and directories in the current directory and all sub-directories.

    Only the names of the files and directories should be displayed (not the entire path).
    Hidden files should be listed.
    One file name per line.
    The listing should end with a new line.
    You are not allowed to use basename, grep, egrep, fgrep or rgrep.

25. 101-gifs: This script lists all the files with a .gif extension in the current directory and all its sub-directories.

    Hidden files should be listed
    Only regular files (not directories) should be listed.
    The names of the files should be displayed without their extensions.
    The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, fil    e .b should be listed before file a, and file Rona should be listed after file jay).
    One file name per line.
    The listing should end with a new line.
    You are not allowed to use basename, grep, egrep, fgrep or rgrep.

25. 102-acrostic: An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. Read more.

Create a script that decodes acrostics that use the first letter of each line.

    The ‘decoded’ message has to end with a new line.
    You are not allowed to use grep, egrep, fgrep or rgrep.

26. 103-the_biggest_fan: This script  parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

      Order by number of requests, most active host or IP at the top.
      You are not allowed to use grep, egrep, fgrep or rgrep.