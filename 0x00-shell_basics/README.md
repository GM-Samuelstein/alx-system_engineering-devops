<h1 align="center" >0x00:  SHELL BASICS</h1>
This directory contains some executable scripts that perform different basic shell functions. Below, you will find a short description of what each script is doing.

| Script Name | Description|
| --- | --- |
| **0-current_working_directory** | *Prints the absolute path name of the current working directory.* |
| **1-listit** | *Displays the contents list of the current working directory.* |
| **2-bring_me_home** | *Changes the working directory to the user's home directory.* |
| **3-listfiles** | *Displays current directory's contents in a long format.* |
| **4-listmorefiles** | *Displays current directory's contents, including hidden files (files starting with ```.```), in a long format.* |
| **5-listfilesdigitonly** | *Displays current directory's contents, including hidden files (files starting with ```.```), in a long format, with user and group IDs displayed numerically.* |
| **6-firstdirectory** | *Creates a directory named ```my_first_directory``` in the ```/tmp/``` directory.* |
| **7-movethatfile** | *Moves the file ```betty``` from ```/tmp/``` to ```/tmp/my_first_directory```.* |
| **8-firstdelete** | *Deletes the file ```betty``` from ```/tmp/my_frist_directory```.* |
| **9-firstdirdeletion** | *Deletes the directory ```my_fist_directory``` that is in the ```/tmp``` directory.* | 
| **10-back** | *Changes the working directory to the previous one.* |
| **11-lists** | *Lists all files (including the hidden files) in the current directory, the parent of the working directory and the ```/boot``` directory, in that order, all in the long format.* |
| **12-file_type** | *Prints the type of a file named ```iamafile``` that is in the ```/tmp``` directory.* |
| **13-symbolic_link** | *Creates a symbolic link named ```__ls__``` to ```/bin/ls``` in the current working directory.* |
| **14-copy_html** | *Copies all HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.* |
| **100-lets_move** | *Moves all files beginning with an uppercase letter to the ```/tmp/u``` directory.* |
| **101-clean_emacs** | *Deletes all files in the current working directory that ends with character ```~```.* |
| **102-tree** | *Creates the directories ```welcome/``` , ```welcome/to/``` and ```welcome/to/school``` in the current directory.* |
| **103-commas** | *Lists all the files and directories of the current working directory, separated by (```,```).* |
| **school.mgc** | *Creates a magic file ```school.mgc``` that can be used with the command ```file``` to detect ```School``` data files.* [^1]|

[^1]: Additionally, you have to compile the magic file and also render it usable. You do that by typing the following on the command line: ```file -C -m school.mgc``` and ```file --mime-type -m school.mgc```.
