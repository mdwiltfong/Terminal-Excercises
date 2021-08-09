**Part I**
1. make a directory called first

*mkdir first*
1. change directory to the first folder

*cd first*
1. create a file called person.txt

*touch person.txt*
1. change the name of person.txt to another.txt

*mv person.txt another.txt*
1. make a copy of the another.txt file and call it copy.txt

*cp another.txt copy.txt*
1. remove the copy.txt file

*rm copy.txt*
1. make a copy of the first folder and call it second

*cp -r first second*
1. delete the second folder

*rm -rf second*

**Part II**

1. What does the man command do? Type in man rm. How do you scroll and get out?

    The man command, when run before a linux command, will give you additional details of the command. It essentially prints a manual on how to use the command. You can scroll through the file by pressing enter. You can exit the manual by pressing "q".
1. Look at the man page for ls. What does the -l flag do? What does the -a flag do?

    The -l flag prints the list of documents in a directory but uses a long list format. The -a flag lists all hidden files.

1. How do you jump between words in the terminal?

    ctrl+left/right
1. How do you get to the end of a line in terminal?

    Press the "end" key.
1. How do you move your cursor to the beginning in terminal?

    Press the "home" key.
1. How do you delete a word (without pressing backspace multiple times) in terminal?
    Control+w to delete the word where the cursor is located.

1. What is the difference between a terminal and shell?

    Shell is the program which actually processes commands and generates outputs, 
    while a terminal is a program that runs shell programs.

1. What is an absolute path?

    An absolute path is the path to a file or folder from the root.

1. What is an relative path?

    The path in regards to your current working directory. 

1. What is a flag? Give three examples of flags you have used.

    Flags are extensions to a command. Such als ls -a will list all items in a directory, even the hidden ones. ls -l will generate a long list format of items in a directory. rm -rf will forcibly remove a directory even if it has multiple items. 

1. What do the r and f flags do with the rm command?

    Forcibly removes directories even if they are not empty. 
