# rock-paper-scissors
## Introduction (Written before starting project)
This project is a simple game of Rock, Paper, Scissors written in Javascript, that can be played in the console of any web browser's developer tools. The game can be played against a computer opponent, who randomly chooses one of the three options. The player can choose their own option, then the two are compared and a winner is declared (or a draw declared in case of a draw).

I foresee this as being a pretty simple project for me to handle. I have quite a bit of general programming experience (especially in the field of game design and programming), as well as a decent amount of experience with debugging Javascript. Considering that this is just meant to be played in the console, and there's nothing graphical involved in it (or anything other than basic logic), I assume it'll be a very easy project to knock out quickly.
## Post Project Notes
As I had expected, this project was pretty straightforward and I really only encountered one small issue during it, which boiled down to a simple syntax error. My `printOutcome()` function was calling `console.log()` to print the result of a game instead of returning the result, and I was also calling it with `console.log(printOutcome(...))`. Because of this, it was printing the outcome as intended, but was also printing another line with `undefined`. It was an easy fix once I realized what I would done, and I just changed the `console.log()` statements inside the function to `return` statements instead, as they should have been.

Since I wasn't expecting much of a challenge, I was mostly treating this just as a refresher exercise for writing Javascript. I did decide to experiment a little bit though, and used some inline if statements in the `playRound()` function. They were a bit tricky to wrap my head around from a syntax perspective at first, but after some research and writing a few, I got the hang of them pretty quickly.