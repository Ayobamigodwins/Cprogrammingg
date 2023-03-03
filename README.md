First C program test file
Gcc 
From the Terminal window, you can view which directory is current by typing:

* pwd

You can change directories by typing:

* cd .. (to move up one level in the directory tree)
* or
* cd DIR_NAME (to move down one level into the directory named "DIR_NAME")

You can list all of the files in the current directory by typing:

* ls

And finally, you can compile your source file with the command:

* gcc -o runme hello.c

In this case, "runme" is the name of the executable file that will be created if your code compiles successfully, and "hello.c" is the name of the source file. In the screenshot below, you can see that a new file called "runme" was created in the same directory as the source file.
To run the executable, you must type:

* ./runme

which means: "execute the program named "runme" which is the current directory

