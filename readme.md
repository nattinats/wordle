# Wordle in JavaScript

A game of Wordle built using [the Word Dictionary from Rapid API](https://rapidapi.com/twinword/api/word-dictionary/)

Inspired by Ania Kubow.

## How to run locally

Run the following set of commands to install the developer dependencies and start the developer servers.

### Install the developer dependencies

```
npm install
```

### Start the backend-server

```
npm run start:backend
```

### Start the frontend-server

The following command starts a simple http server for the frontend application.

Run in a different terminal than the backend-server.

```
npx http-server
```

## About the app

This app is a fullstack application / game.
It clones Wordle.
The idea is that the user has to guess a pre-defined word.

The backend has two API endpoints;
One that returns a list of words the application will use,
and one that checks if a user inputted word is valid.

The frontend has several functions to make sure a user can get information about the guess.
The user is a shown a color indicator on each letter when the guess is done.
Grey means letter not in word
Yellow means letter in word, but is placed wrong
Green means letter is correctly guessed.

Guess the word in as few steps as possible.
