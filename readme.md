# Wordle in JavaScript

A game of Wordle with the benefit of two different API's at RapidAPI.

Inspired by Ania Kubow.

## How to run locally

Run the following commands to install developer dependencies and start the developer server.

```
npm install
npm run start
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
