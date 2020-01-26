# Makefile Maker
This makefile generator was created by Cyril Grosjean.

# How to use
./update_makefile [binary_name] [flags]

You can run the program without arguments.
The default binary name will be 'a.out'

The program detect automatically your .c files (if they are src files or tests files)

# Debug mode

You can run your program with the command: make debug
Your .c files will be compilated with g3 flag.

# FLAGS

-d: Create a Makefile with the debug mode.

-t: Create a Makefile with the tests_run mode.

-csfml: Create a Makefile for graphical programs.

-ncurses: Create a Makefile for ncurses programs.

# WARNING

The Makefile generator don't include in src files your .c files in the repository bonus.
The program don't read .c files in repositories before your open repository.
