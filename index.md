## Project Purpose and Components
As the first project of the class, project 1 simply required students to work with visual studio code and the command terminal on a basic level.

## What I Learned
This project really just served as a refresher on previous classes I'd taken in the minor (in terms of using visual studio), as well as an elaboration on the first two labs where I was learning about the command terminal for the first time.

## Code
### p1-date.js
/*<br>
    CIT 281 Project 1<br>
    Name: Sophia Lynsky<br>
*/<br>

//Part 4<br>
console.log(["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"] [new Date().getDay()])<br>

### p1-random.js
/*<br>
    CIT 281 Project 1<br>
    Name: Sophia Lynsky<br>
*/<br>

//Part 5<br>

// Returns a random number between min (inclusive) and max (exclusive)<br>
function getRandomInteger(min, max) {<br>
    return Math.floor(Math.random() * (max - min) + min);<br>
}<br>

let alphabet = ["a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p","q","r","s","t","u","v","w","x","y","z"]<br>

let randomLetter = getRandomInteger(0,26)<br>
let lettersLength = getRandomInteger(5,26)<br>
let text = ""<br>

for (i=0; i<lettersLength; i++) {<br>
    text += alphabet[randomLetter];<br>
}<br>

### [Home Page](https://slynsky.github.io)
