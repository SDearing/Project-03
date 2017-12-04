# Project-03
Third Project of Video Games Design HND course at West Herts College 
## Project Outline ##
Design a system that will allow the player to enter up to 3 random letters. The system will return the best, largest, valid English word that can be made up if the 3 letters (blanks are no allowed). For example: TCA should return CAT, OZR should return OR, ZZA should return A.
## Functional Specifications ##
* The program will need to have a dictionary document implemented into it
*	The program will need to be able to store the user’s input of 3 random letters
*	The program must ensure that the input is 3 letters in length
*	The program will need to be able to split the string of the input into separate letters
*	These letters will then have to be compared to the dictionary to see what words can be made
*	The program will then need to determine which word to pick, by finding the longest word it can create
*	If the program cannot make a 3 letter word the program will need to either create a 2 or 1 letter word depending on what can be made
*	The program should then be able to create and display that word to the user
## Non-functional Specifications ##
* The program will need to clearly show the user what the answer to their algorithm is.
* The program will need to show to the user when they need to type in an input
* The program will need to direct the user what they need to type in, for example telling the user that their input should only be 3 characters long
## Flowchart ##
![alt text](https://github.com/SDearing/Project-03/blob/master/RepositoryAssets/flowchart.png)
### Flowchart Explanation ###
The first part of the algorithm is to collect the data for the program, this involves getting the dictionary file and receiving the user's anagram. Once that has been collected we then need to ensure the user's input is lower case, this is because the words in the dictionary file are in lower case so the users input needs to be the same case so that they can be compared. Then the program will get all words from the dictionary file that are the same length or smaller than the user's input (3 letters). Then each word will be compared with the users anagram, if there is a matching letter in the word, that word is then given a point for each matching letter. Once all the words have been compared to the anagram, the word with the most points is then chosen as the best answer and presented to the user.    
## User Story ##
The program will start with explaining to the user what the purpose of the program is, the program will then ask the user for an anagram that should be 3 characters.

![User Story1](https://github.com/SDearing/Project-03/blob/master/RepositoryAssets/UserStory1.PNG)<br/>
However if the user types in an input that isn't 3 characters long, the program will loop and ask for an input again untill an input of 3 characters is entered.

![User Story2](https://github.com/SDearing/Project-03/blob/master/RepositoryAssets/UserStory2.PNG)<br/>

Once the correct input has been entered, the user’s anagram will then be solved and presented to the user.
![User Story3](https://github.com/SDearing/Project-03/blob/master/RepositoryAssets/UserStory3.PNG)<br/>

## Development Plan ##
### Programming Language ###
The programming language I am going to use to complete this project is C++, this is because one of the requirements of the project is that it needs to be coded in C++.
### IDE ###
To code this program I will use an IDE (Integrated Development Environment) from the website repl.it. This website is helpful as it works as a compiler for a very large range of programming languages. Using this IDE will be helpful as it will provide me with more code insight, this is because the repl IDE knows the keywords of C++ and other languages, meaning that they will be highlighted so that they will stand out so I can easily understand the structure of my code. Another benefit of using an IDE is that it has debugging tools and a built in compiler, which means I can thoroughly test my code before I upload it, and it helps me identify possible errors within my code.
### Coding Standards ###
* In my coding I will use single line comments on most lines of code stating its purpose in the programv so that anyone reading the code can easily see how the sections of code work.
* My variables in the code will be written in CamelCase and will be named after the purpose the variable will serve.
* I will seperate sections of code so that the code is presented clearly, and so someone can more easily understand the code. 
### Overall Look ###
This program will be text-based, meaning that the program will all be presented by text. The program will start by presenting to the user how the program will work, meaning that the program will tell the user that the program is a anagram solver and that they need to input their 3 letter anagram. Once the user has entered an input, the program will present that it is solving the anagram and will then give the best answer it can give.

