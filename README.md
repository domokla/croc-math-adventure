# Krokodilos Matek

A simple, child-friendly web game built with HTML, CSS, and vanilla JavaScript.

## What is this?

**Krokodilos Matek** is a small browser-based math game where the player helps a crocodile decide:

- which number or expression is bigger
- which comparison sign is correct: `<`, `>` or `=`
- whether a math statement is true or false

The goal is to help children around ages 6-8 practice basic addition, subtraction, and comparisons in a playful way.

## Tech Stack

- everything is contained in a single `index.html` file
- no framework and no external dependencies
- plain HTML, CSS, and vanilla JavaScript
- designed to work on both mobile and desktop
- reward images are loaded from the `images/` folder

## How the Game Works

- each round contains 5 questions
- question types are randomly mixed
- the player gets immediate feedback after each answer
- the crocodile emoji turns toward the bigger side after the answer
- the next question appears after a short delay

## Question Types

The game mixes the following kinds of questions:

1. Simple comparison
   - example: `4 ? 5`
2. Expression vs number
   - example: `3+5 ? 4`
3. Expression vs expression
   - example: `2+3 ? 4+1`
4. True / False statement
   - example: `2+4 > 3`
5. Chain comparison
   - example: `3 < 5 < 8`

## Rules

- numbers stay between 0 and 20
- only `+` and `-` operations are used
- expressions never produce negative results
- questions are intentionally simple and easy to read

## Scoring and Reward

- the final result is shown as `X / 5`
- if the player gets at least 4 correct answers, a random reward image is shown from the `images/` folder
- if the player gets fewer than 4 correct answers, an encouraging message is displayed
- the `Új játék` button starts a new round

## Project Files

- `index.html`: the full game in a single file
- `images/`: reward pictures used at the end of successful rounds

## Possible Future Improvements

- difficulty levels
- sounds or extra animations
- score tracking across multiple rounds
- themed or seasonal reward image sets
