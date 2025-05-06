# Number Guessing Game

A simple command-line game where users guess a randomly generated number between 1 and 1000. The game stores user data and statistics in a PostgreSQL database.

## What It Does

- Prompts the user for a username
- Greets returning users with stats on past games
- Generates a random number between 1 and 1000
- Accepts user guesses and provides feedback until correct
- Tracks the number of guesses per game
- Stores user game history in a PostgreSQL database

## How It Works

The script checks if a user exists in the database. If they do, it retrieves their game history. If not, it adds them. During the game, it validates input, provides hints, and logs the number of attempts. After a successful guess, it records the game stats to the database.

## Tools Used

- Bash
- PostgreSQL
- Git for version control
