## hello_world — Autotools Project
This project demonstrates a simple C program built using GNU Autotools.
The program consists of three source files: main.c, func.c, and func.h.

## 1. Initialize Autotools
Run the following command to generate all required Autotools files:

autoreconf --install

## 2. Configure the project

./configure

For small project possible use the option: --disable-dependency-tracking 

This step checks your system and prepares the Makefile.

## 3. Build the project

make

This compiles the program and produces the binary hello_world.

## 4. Install the program

sudo make install

This installs:
 - the binary → /usr/local/bin/hello_world
 - the header → /usr/local/include/func.h

# 5. Clean all build files
To remove all generated files and delete installed files:

sudo make clean-all

After this command, only the following files remain in the project directory:
*.c, *.h, *.am, *.ac.

## 6. Run the program
After installation run:

hello_world