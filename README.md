# CPLUS Login System
Create an account with this program and interact with the program using your accounts!
## Aim
The aim of this project is to let users store their ID and passwords. Future work would include features that let users interact with their accounts. This program is written in C++.

The program is divided into phases (WIP):
* Phase 1A (12 May 2021): The program is able to store User ID and password to a file. Users would be able to register their accounts using this program.
* Phase 1B (14 May 2021): The program can read all the stored IDs and passwords in a file.
* Phase 1C (15 May 2021): Users can now login using their existing ID and password if they have already registered. The program will also prevent registration using existing user IDs.
* Phase 2A (19 Jul 2021): Several quality fixes such as allowing users to cancel registration and users would only receive one error message when the ID or password input using registration does not match the requirements. Added an account balance for each user and allows users to access their accounts after logging in. 
* Phase 2B (7 Aug 2021): Split the code into 3 files: the main file, function file, and header file. Users can now reset their password if they forgot their password after registering.

## Guide
* 'login' : Contains the program that is used to register or login to user's accounts.
* 'main.cpp': Contains the main function file, written in C++. This includes the main menu and prompt to register or login.
* 'functions.cpp': Contains the functions used for this program including registering an account and logging in, written in C++.
* 'functions.h': Header file that contains all C++ macros, function prototypes and classes for this program.
* 'loginfile.txt': Contains the file that stores user ID and passwords. 

## Setting Up
This program is written using Visual Studio Code in Ubuntu, but can be run using any mainstream operating system and can be written in any IDE. 
In order to modify this program and compile it, pleasure ensure you have a G++ compiler. [Steven Zeil's tutorial](https://www.cs.odu.edu/~zeil/cs250PreTest/latest/Public/installingACompiler/) provides a great guide to set up the compiler.
Any command-line interpreter can be used to run the program (Windows CMD, Ubuntu Terminal, etc.).

