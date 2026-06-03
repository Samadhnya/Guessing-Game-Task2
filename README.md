# Guess the Number Game

## Overview

The Guess the Number Game is a simple Java console application where the computer generates a random number between 1 and 100. The player must guess the correct number with the help of hints provided by the program. The game continues until the correct number is guessed.

## Features

* Random number generation between 1 and 100.
* User-friendly console interaction.
* Input validation for incorrect entries.
* Hints after each guess.
* Attempt counter.
* Score calculation based on the number of attempts.
* Educational and beginner-friendly Java project.

## Technologies Used

* Java
* Scanner Class
* Random Class

## How the Game Works

1. The program generates a random number between 1 and 100.
2. The user enters a guess.
3. The program checks the guess and displays:

   * "Greater" if the guess is higher than the secret number.
   * "Smaller" if the guess is lower than the secret number.
   * "Right" if the guess is correct.
4. The game tracks the number of attempts.
5. Points are awarded based on the number of attempts taken.

## Scoring System

| Attempts   | Points |
| ---------- | ------ |
| 1          | 10     |
| 2          | 9      |
| 3          | 8      |
| 4          | 7      |
| 5          | 6      |
| 6          | 5      |
| 7          | 4      |
| 8          | 3      |
| 9          | 2      |
| 10 or more | 1      |

## How to Run

Compile the program:

```bash
javac task2.java
```

Run the program:

```bash
java task2
```

## Author

Samadhnya Meshram

## License

Educational Purpose Only

This project is created for learning and academic purposes. Users are free to study, modify, and use the code for educational activities.

