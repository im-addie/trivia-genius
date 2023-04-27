# Trivia Genius

## Collaborators - JRS Winter 2023 Cohort
Addie Pasok - https://github.com/im-addie

Charlie Bolin - https://github.com/kennethbolin

Damaris Torrent - https://github.com/DamarisTorrent

Dante Wanders - https://github.com/Dantewanders


## Overview
Trivia Genius is a full-stack web application created by the Winter 2023 Cohort of JRS Coding School. Our idea was to help users cure their boredom by playing a classic game of trivia with our available game mode, Quick Play, that would allow users to play a game for 3 minutes and keep track of their score.

The application features user accounts with a login/registration system and settings that allows them to change their password. Along with the playable trivia game, we have a landing page that gives a brief overview of what the game is. Lastly, there is a "How To Play" page where it quickly runs through how each game mode works.

## Installation

1. Open integrated terminals for the "api" and "ui" folders.
2. In each terminal, run `npm install` to install dependencies
3. Make sure you have an instance of Docker running.
4. Create a database named `workoutbud_db`. 
6. In the "api" intergrated terminal, run `npx knex migrate:latest` and `npx knex seed:run` to create and seed tables

## Starting the app
1. Using both intergrated terminals, run `npm start` to start the app! 
  * This should automatically open your browser with the link http://localhost:3000 to access the app.

2. To start, create an account! Click the login button on the navbar. In this page, it has a link "create an account" which will take you to the register page to create an account!
