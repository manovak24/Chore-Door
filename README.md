# Project Name
> Chore Door - CodeCademy project that consits of a signle-page website game utlizing HTML, CSS and JavaScript. 

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
This project is part of the CodeCademy Web Development course section that focuses on building interactive JavaScript websites.

Building on the functionality of this project. I decided to include a score board at the bottom indicating the current score and the users high score.

## Technologies
* JavaScript - version ES6
* HTML
*CSS

## Setup
Clone respository from https://github.com/manovak24/chore_door

## Code Examples
```js
const gameOver = (status) => {
    if (status === 'win') {
        startButton.innerHTML = 'You win! Play again?';
        score++;
        currentStreak.innerText = score;
        if (score > highScore) {
            highScore++;
            bestStreak.innerText = highScore;
        }
    } else {
        startButton.innerHTML = 'Game over! Play again?';
        score = 0;
        currentStreak.innerText = score;
    };
    currentlyPlaying = false;
};
```

## Features
List of features ready and TODOs for future development
* Game fully functional
* Scoreboard to keep track of players current score and high score

To-do list:
* Create a more appealing layout and style with CSS

## Status
Project is: _finished_

## Contact
Created by [@manovak24](https://github.com/manovak24) - feel free to contact me!