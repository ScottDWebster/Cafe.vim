# Cafe.vim
A simple vim plugin for compiling and running Java code

This is a very simple plugin that adds three functions and a menu allowing the user to easily compile or run the current file.  The functions are:

1. cdFileDir(): This function changes the current directory to the location of the file in the current buffer.
2. JavaCompile(): This function runs cdFileDir and then asynchronously executes javac to compile the file in the current buffer.
3. JavaRun(): This function rund cdFileDir and then asynchronously executes java to run the compiled version of the file in the current buffer.

The menu:
  - Alt-C opens the Cafe menu
  - Once the Cafe menu is open
    - 'd' runs cdFileDir()
    - 'c' runs JavaCompile()
    - 'r' runs JavaRun()

It currently only supports Windows and Vim 8 or later.
