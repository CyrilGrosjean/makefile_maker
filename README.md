# Makefile Maker
This makefile generator was created by Cyril Grosjean.

## How to use
`./update_makefile _[binary_name] [flags]_`

You can run the program without arguments.
The default binary name will be 'a.out'

The program detect automatically your .c files (if they are src files or tests files)

# Debug mode

Your .c files will be compilated with g3 flag.

# FLAGS

-d: Create a Makefile with the g3 flag.

-t: Create a Makefile with the tests_run mode.

-csfml: Create a Makefile for graphical programs.

-ncurses: Create a Makefile for ncurses programs.

-lib: Your .c files will be compilated with your .a file.

# WARNING

The Makefile generator don't include in src files your .c files in the repository bonus.
The program don't read .c files in repositories before your open repository.

# TIP

Move the file into an repository in your environement path or use an alias on it:
alias update_makefile [link to your path]/update_makefile.

Then you can use anywhere this script without move it.