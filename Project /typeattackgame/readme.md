                                                                PROJECT PROPOSAL 
Members:
•	Sheikh Naveed Azeemi (23K-0003)
•	Rao Ghulam Mohiuddin (23K-0001)
•	Ghulam Murtaza Qazi (23K-0020)
Game Overview
 The game will be a console-based typing game where the player has to type words that appear on the screen within a certain time limit. The words will be displayed on  the screen and the player has to type them before they disappear.
Libraries
The game will include standard C libraries such as stdio.h for input/output, stdlib.h for dynamic memory allocation, and time.h for random number generation and timing functions.
Data Structures
   -  simple Arrays and 2D arrays will be used  to represent the game screen.
   - Strings will be used to store the words.
    - Pointers will be used to dynamically allocate memory for the words.
Game Logic
   - While loop, if-else statements and switch cases will be used  for the main game loop and to handle user inputs and game inputs.  we will also  be using  bitwise operators  for some operations like checking if a word has reached the bottom of the screen. And  recursion for some tasks like generating random words.
File Processing
   - It will Store a list of words in a file and use file processing functions to read from this file and populate your word structures.
Pointers and Dynamic Memory Management
   It will use pointers to access your arrays and structures and  dynamic memory management functions like malloc and free to allocate and deallocate memory for your words.
                                                                
The target was to make a typing attack game where the player will  have to enter the letters as soon as  the letters  will be shown on the screen under a certain time . the user will be allowed to choose his level of difficulty between easy, intermediate and hard level . and the score will be given on the basis of how much letters have the user entered in the certain time limit .
We have used different library functions including:
 #include<time.h>         //for calculating speed & displaying current time
#include<windows.h>      //for gotoxy func
#include<conio.h>        //for background color , to clear screen  etc
#include<stdlib.h> , #include<string.h>   and #include<unistd.h> .
Apart from library functions we also used loops , conditions, nest loops and conditional statements , functions , recursion , arrays , filing , structure and pointers to make our code run accurately and efficiently with smooth interaction .The gotoxy function was mainly used to insert certain element on the specific coordinate of the display screen .whereas library (time.h) was  used to display current time and to calculate the typing time and other measuring measurements during the code running.


                                                  MAJOR PROBLEMS FACED DURING CODE BUILDING :
                                                  
The measure problem faced during the code creation was setting a particular element on certain coordinate of the display screen. it was difficult to do that with simple printf function, as it was making our code more complex and hard to read. so after a lot of research from google and YouTube, we found a <windows.h >libraray’s function, gotoxy, which is used to display certain things at a specific coordinate. Consecutively, we also faced the problem with gotoxy function was that it was not runnable on new versions of VS code or any other online IDE , so we used dev c++ as our IDE as gotoxy was workable on dev C++. Another major difficulty we faced while creating the code was to give the game a proper runtime sequence and to clear and remove small runtime errors which were coming while running the code to make the code run as per the user's instructions. other problems include code-logic building and errors and problems coming during the creation of the code, which we faced at the moment of creation  but were resolved later with time and more learning the code.


                                                LOGIC / ALGORITHM USED ,ANY CHAANCE OF IMPROVEMENT :
What  We have tried is to avoid any complexity so any reader could easily understand our code .The user will enter his credentials in the form of name and password. then will choose the game difficulty level and time limit for the game. The major logic of this code is that  when certain letter comes on the screen and if the user enter the same letter as on the screen, it will be stored in the score; otherwise, it will be removed from the score. second was to speed up the alteration of the letters with respect to the game difficulty for which we used <time.h >library  to run a code for certain amount of time, to show current time and date and to speed up the letters alteration and display other factors with respect to it. the amount of improvement that might be possible depends on how much harder and more attractive, we want to make the game. like in our game, one letter comes at a time, and the user's ability is checked on a per-letter basis. what we can improve is that we can display a whole sentence or a phrase on the same time. also include special characters and numbers. also we can make make the interface more attractive by using borders with different colors, but what we  thought while making the code that a simple background would be best for our game.

                                                 
                                                                

