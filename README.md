# Introduction to Go Programming

Welcome to this beginner-friendly guide to Go programming!<br>
Below, you'll find a series of exercises designed to help you grasp the basics of Go, along with helpful resources and tips.


## Installation
To get started with Go, you'll need to install the Go language on your system.<br>
The installation process may vary depending on your operating system. Here is a comprehensive guide to help you through the installation process: [Install Go](https://go.dev/doc/install).


## Compilation and Execution
- Once you've written your Go code, you'll need to compile it to run. Here's a quick guide on how to do it:

- Save your code in a file with a .go extension.
- Open a terminal or command prompt.
- Navigate to the directory containing your file.
- Run ```go build yourfilename.go``` to compile your program.
- Execute the compiled program by running ```./yourfilename``` (on Unix systems) or ```yourfilename.exe``` (on Windows).


## Exercise 1:
Using a loop, print every number between 1 and 100 !


## Exercise 2:
Code a "add" function that adds two numbers together.<br>
This function takes 2 parameters:

- The number on the left of the '+' operator
- The number on the right of the '+' operator<br>

```
add(2, 2) -> 4
```

You can add any other operation !


## Exercise 3:
Write a "countLetter" function to count all letters from a file and print it.<br>
This function take 1 parameter:

- The file path of your file.<br>

```
countLetter("myFile")
```


## Exercise 4:
Write a "countWord" function whose objective is to count the number of times a word appears in a sentence.<br>
This function takes 2 parameters:
- The sentence you will search through.
- The word you look for in the sentence.<br>

```
countWord("My cat is playing with my dog!", "my") -> 2
```


## Exercise 5:
Make a simple "isFileSame" function to check if two files have the same content !
This function takes 2 parameters:<br>
- The path to the first file to check
- The path to the second file to compare with the first file

```
isFileSame(firstFile.txt, secondFile.txt) -> false
isFileSame(firstFile.txt, fileWithSameContent.txt) -> true
```


## Exercise 6:
Now, let's make an "appendTofile" function which appends a string to a file !<br>
That function takes 2 parameters:

The file you want to append to.
The string you want to append to your file.

```
appendToFile("myFile", "append this") -> if file empty : "append this"
appendToFile("myFile", "append this") -> if file is not empty : "... append this"
```


## Exercise 7:
Now to test all of your functions, make some unit tests !


## Final Task: Build a Command-Line Quiz Game
For your final exercise, create a simple command-line quiz game in Go. This project will help you understand user input handling and basic control structures in Go.

### Objectives:
Design a Quiz: Create a set of questions (e.g., simple math or general knowledge questions) and store them.
Ask Questions: Display each question to the user and ask for their answer.
Input Handling: Capture the user's input and check it against the correct answers.
Score Tracking: Keep track of the number of correct answers and display the score after the quiz ends.

### Tips:
- Use arrays or slices to store your questions and answers.
- Explore Go's fmt package for input and output operations.
- Add a timer feature as an additional challenge, where users have a limited time to answer all questions.
  
This task will solidify your understanding of Go's syntax and standard library, especially around handling user inputs and simple data structures.<br>Enjoy coding your quiz game!
