# 1. The Shell
echo command outputs the text next to it. date outputs the current month, day, 
time, and year. whoami prints out the PC user. 

# 2. pwd (Print Working Directory)
pwd displays your current file path

# 3. cd (Change Directory)
cd and cd . takes you to your current directory. Also cd followed by
the name of a file path takes you to that location. 
cd .. takes you to the directory that is above you. cd ~ takes you to the 
home directory. cd - takes you to the previous directory.

# 4. ls (List Directories)
ls shows all the contents of the current directory. ls followed by a file path
shows all that location's contents. ls -a shows all contents including the 
hidden files. ls -l shows detailed information of all the files. ls -l and ls -a
can be combined like so: ls -la or ls -al to perform them at the same time. 

# 5. touch
touch followed by any name creates a file with that name. You can inlude
.file ext after the name to specify the type of file.

# 6. file
file command gives a detail description of the type of file follwoing the file
command

# 7. cat
cat displays file contents and can combine them

# 8. less
less command displays the contents of the file in a different page in the shell allowing you to navigate through it using other commands:
q - Used to quit out of less and go back to your shell.
Page up, Page down, Up and Down - Navigate using the arrow keys and page keys.
g - Moves to beginning of the text file.
G - Moves to the end of the text file.
/search - You can search for specific text inside the text document. Prefacing the words you want to search with /
h - If you need a little help about how to use less while you’re in less, use help.

# 9. history
history displays a list of the past commands you used. The up and down arrow keys can be used to scroll through previous commands. !! runs a your most recent command. Pressing 
ctrl-R followed by typing shows matches to valid commands that match with what you typed. clear clears up the shell terminal. Pressing tab after typing autocompletes what you 
intend to type

# 10. cp (Copy)
cp copies a specific file to a file path that you set it to. You can use wildcards such as: " * ", ?, and [] to specify what to copy. Using the -r flag will copy all the contents in a specific directory to a file path. Using i- notifies you before overwriting a file. 

# 11. mv (Move)
mv allows you to rename and move files to other locations. You can also use the -i flag with this command and -b to create a backup of a file. 

# 12. mkdir (Make Directory)
mkdir is used to make a new folder and then -p can be used with it to make subfolders

# 13. rm (Remove)
rm removes files and rmdir removes folders. -f is used with rm to remove regardless of protection, i- asks you if you want to remove, and -r removes all files and subfolders.

# 14. find
find allows you to search for a specific file in a folder by its name (-name) and/or type (-type)

# 15. help
help gives you a description of a specific command and can do so for a program (--help)

# 16. man
man gives you a manual of a specific command

# 17. whatis
whatis gives a description of what a specific command does

# 18. alias
alias allows you to use a name to execute a specific command. You would add it in ~/.bashrc to make it permanent and remove it using the unalias command.

# 19. exit
exit and logout are used to close the terminal
