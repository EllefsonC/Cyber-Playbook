Most of these commands will be pulled from random points around the internet, so if you see some that are in an order you recognize that is why.

"ls" is the List command, which lists files and directories, options that can be apphended are -l for long format, -a to include hidden, and -h for human-readable format. Ex: -ls -a

"cd" is the change directory command

"pwd" is the command to print current working directory along with it's path

"mkdir" is used to create a new directory

"rmdir" to remove a directory, but ownly for empty directories

"rm" is used to remove files or directories,  -r can be added after to remove directories recursively, and -f can force removal without confirmation

"echo" is used to repeat what you input to the terminal. Quotes are only needed if posted phrase contains spaces.

"whoami" will tell the user you're logged into

"cat" is used to output files, short for concatenating. Ex.: cat todo.txt  (this will output todo text file)

"find" is used to search within every folder in a working directory for the file that you need. Ex.: find -name *.txt looks for any file that has a .txt file extention using the * wild card.

"grep" allows you to search contents of a file for specefic value you need, great for finding IP address needed so usful for foresnics. 

"&" allows you to backfournd commands

"&&" allows you to do multiple commands in the same line, command 2 will only operate after command 1 is successful

">" is an output redirector. Ex.: echo hey > welcome, creates file if it does not exist and adds "hey" to it,it will overwrite content.

">>" is an output redirector but will not overwrite file but will apphend new info to bottom.

"|" is called a pipe, and is used to redirect an output to another destination. This is usually used in conjunction with the "grep" command (globally search for a regular expression and print matching lines)

"||" acts as an "or" statement. ex: false || echo Hello
Hello would be printed to terminal. If it were true instead of false, then nothing would have printed.
