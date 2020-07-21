### File

* _None_

### Instructions

* With a partner, spend a few moments outlining all the steps and conditions that go into a single game of rock paper scissors.

* Try to break it down into steps that you could code out.

* Think of basic elements like loops, if-else statements, arrays, alerts, etc.

* Be prepared to share your outlines approach.

1. prompt rock, paper, or scissors
2. generate rock, paper, or scissors


var myChoice = prompt("rock, papers, or scissors?")
console.log(myChoice);

var options = ["rock", "paper", "scissors"];
var theirChoice = options[Math.floor(Math.random() * 3)];

alert(theirChoice);
console.log(theirChoice);

if (theirChoice == myChoice) {
  alert("draw! play again");
  console.log();
} else {
  alert("someone lost!")
}

else if (theirChoice == "scissors") {
  alert("you win!"); 
} else {
  alert("you lose!);
}

[0] < [1] 
[1] < [2]
[2] < [0]

var myChoice = prompt("rock, paper, or scissors?")
console.log(myChoice);

var options = ["rock", "paper", "scissors"];
var theirChoice = options[Math.floor(Math.random() * 3)];

alert(theirChoice);
console.log(theirChoice);

if (myChoice == "rock") {
  function rockPapersScissors(theirChoice) {
    var winner = "";
      switch (theirChoice) {
        case "rock":
          winner = "draw! play again!"
          break;
        case "paper":
          winner = "computer wins!"
          break;
        case "scissors":
          winner = "you win!"
          break;
      }
    console.log(winner);
    alert(winner);
  } 
  rockPapersScissors(theirChoice);
} else if (myChoice == "paper") {
  function rockPapersScissors(theirChoice) {
    var winner = "";
      switch (theirChoice) {
        case "rock":
          winner = "you win!"
          break;
        case "paper":
          winner = "draw! play again!"
          break;
        case "scissors":
          winner = "computer wins!"
          break;
      }
    console.log(winner);
    alert(winner);
  } 
  rockPapersScissors(theirChoice);
} else {
  function rockPapersScissors(theirChoice) {
    var winner = "";
      switch (theirChoice) {
        case "rock":
          winner = "computer wins!"
          break;
        case "paper":
          winner = "you win!"
          break;
        case "scissors":
          winner = "draw! play again!"
          break;
      }
    console.log(winner);
    alert(winner);
  }
  rockPapersScissors(theirChoice)
}
