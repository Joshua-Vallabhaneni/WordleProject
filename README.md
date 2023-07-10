# Wordle Game

This program is a text-based implementation of the popular game Wordle.
The objective of the game is to guess a hidden word within a limited number of attempts.

## Instructions

1. The program is written in Java and can be compiled and executed using a Java compiler.
2. The main class of the program is `Portal`, which contains the `main` method and serves as the entry point for the program.
3. The program utilizes two additional classes: `Word` and `WordleGame`.
4. The `Word` class represents a single word and provides various methods for manipulating and accessing its properties.
5. The `WordleGame` class handles the game logic, user interaction, and gameplay mechanics.
6. The program prompts the user to guess the hidden word and provides feedback on the correctness of the guess.
7. The game continues until the user either correctly guesses the word or runs out of guesses.
8. The available letters and the current combination of correct guesses are displayed to the user after each guess.

## Usage

To run the program, follow these steps:

1. Compile the program using a Java compiler:

   ```shell
   javac Portal.java
2. Execute the compiled program: java Portal
3. Follow the prompts to enter your guesses and interact with the game.

## Classes
Portal
The Portal class serves as the entry point for the program and contains the main method. It initializes an instance of WordleGame and starts the game by invoking the startPrompts method.

Word
The Word class represents a single word. It contains methods for manipulating and accessing the properties of a word, such as its characters, length, and validity. It also provides methods for replacing characters and generating a star-filled string representation of the word.

WordleGame
The WordleGame class handles the game logic and user interaction. It prompts the user to enter guesses, checks the correctness of the guesses, and provides feedback to the user. The class also manages the available letters, the number of guesses remaining, and the current combination of correct guesses.

## Contributions
This program was created by Pranavh Joshua Vallabhaneni.
