## 0-hello_world,Hello World
a script that prints “Hello, World”, followed by a new line to the standard output.
## 1-confused_smiley,Confused smiley
a script that displays a confused smiley "(Ôo)'.
## 2-hellofile,Let's display a file
Display the content of the /etc/passwd file.
## 3-twofiles,What about 2?
Display the content of /etc/passwd and /etc/hosts
## 4-lastlines,Last lines of a file
Display the last 10 lines of /etc/passwd
## 5-firstlines,I'd prefer the first ones actually
Display the first 10 lines of /etc/passwd
## 6-third_line,Line #2
a script that displays the third line of the file iacta.
## 7-file, It is a good file that cuts iron without making a noise
a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
## 8-cwd_state,Save current state of directory
a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
## 9-duplicate_last_line,Duplicate last line
a script that duplicates the last line of the file iacta
## 10-no_more_js,No more javascript
a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
## 11-directories,Don't just count your directories, make your directories count
a script that counts the number of directories and sub-directories in the current directory.
## 12-newest_files,What’s new
a script that displays the 10 newest files in the current directory.
## 13-unique,Being unique is better than being perfect
a script that takes a list of words as input and prints only words that appear exactly once.
## 14-findthatword,It must be in that file
Display lines containing the pattern “root” from the file /etc/passwd
## 15-countthatword,Count that word
Display the number of lines that contain the pattern “bin” in the file /etc/passwd
## 16-whatsnext,What's next?
Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
## 17-hidethisword,I hate bins
Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
## 18-letteronly,Letters only please
Display all lines of the file /etc/ssh/sshd_config starting with a letter.
## 19-AZ,A to Z
Replace all characters A and c from input to Z and e respectively.
## 20-hiago,Without C, you would live in hiago
Create a script that removes all letters c and C from input.
## 21-reverse,esreveR
a script that reverse its input.
## 22-users_and_homes,DJ Cut Killer
a script that displays all users and their home directories, sorted by users.
## 100-empty_casks,Empty casks make the most noise
a command that finds all empty files and directories in the current directory and all sub-directories.

Only the names of the files and directories should be displayed (not the entire path)
Hidden files should be listed
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep
## 101-gifs,A gif is worth ten thousand words
a script that lists all the files with a .gif extension in the current directory and all its sub-directories.

Hidden files should be listed
Only regular files (not directories) should be listed
The names of the files should be displayed without their extensions
The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep
## 102-acrostic,Acrostic
a script that decodes acrostics that use the first letter of each line.

The ‘decoded’ message has to end with a new line
You are not allowed to use grep, egrep, fgrep or rgrep
## 103-the_biggest_fan,The biggest fan
a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

Order by number of requests, most active host or IP at the top
You are not allowed to use grep, egrep, fgrep or rgrep
