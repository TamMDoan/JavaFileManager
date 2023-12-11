# FileManager

An amazingly useless tool!
Write a short summary of what each command does and 
how it is used. Give a real example of what the user 
would see using each command. Edit the Help for FileManager 
file with your explanatory text.

## Possible Commands
- `help` : outputs the possible commands to the console. 
- `list` : outputs the files found in a folder. If there are no files, a message saying the folder is empty will print out.
- `info` : outputs the name, absolute and relative path, size, creation and modified time of a file or folder. 
- `mkdir` : creates a folder at the specified path. If there's an illegal character, there will be a message saying so. Otherwise, a success or failure message will print out.
- `rename` : renames an existing file/folder. A user would be prompted to enter an existing file/folder name and the new name. If the file name already exists, there will be a message saying so. Otherwise, a success or failure message will print out.
- `copy`, `move` :  copies and moves a given file/folder to a new specified destination. A user would be asked for the path of the file/folder and a destination path. If the move was successful, there would be a message saying so. If not, it'll say moved or copy failed.
- `delete` : deletes file/folder. A user would see a message saying a file/folder was successfully deleted or that it couldn't be deleted.
- `quit` the file manager shell
- In the case of invalid commands, a message will print out saying so.

