## Project Purpose and Components
As the first project of the class, project 1 simply required students to work with visual studio code and the command terminal on a basic level.

## What I Learned
This project really just served as a refresher on previous classes I'd taken in the minor (in terms of using visual studio), as well as an elaboration on the first two labs where I was learning about the command terminal for the first time.

## Code
### p1-date.ja
/*
    CIT 281 Project 1
    Name: Sophia Lynsky
*/

//Part 4
console.log(["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"] [new Date().getDay()])

### p1-random.js
/*
    CIT 281 Project 1
    Name: Sophia Lynsky
*/

//Part 5

// Returns a random number between min (inclusive) and max (exclusive)
function getRandomInteger(min, max) {
    return Math.floor(Math.random() * (max - min) + min);
}

let alphabet = ["a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p","q","r","s","t","u","v","w","x","y","z"]

let randomLetter = getRandomInteger(0,26)
let lettersLength = getRandomInteger(5,26)
let text = ""

for (i=0; i<lettersLength; i++) {
    text += alphabet[randomLetter];
}

### [Home Page](https://slynsky.github.io)
