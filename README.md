#Workshop 0

## Workshop 0:
Current Sketch:[ https://editor.p5js.org/melisssa/full/DW77RT8X7 ](https://melissss4.github.io/Workshop-0/) 

Notes:
From workshop:
Keep code as simplified and short as possible
To keep code in the save, but not have it working use: control /

From coding my project:
Using the p5.js primitive shapes, I experimented with the square and worked on changing the colour, changing the background, getting it to move and getting it to follow the mouse. Having 0 experience coding, I was able to see that this wasn’t as daunting as I expected. This is the code I used to create the shape, colour it, and have it follow my mouse. 


let x = 0 ;

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(100, 100, 10);
  
//   fill(150, 0, 100);
//   rect(mouseX, mouseY, 40, 60)
  
//   x= x + 3


}

I wanted to keep my variables simple and similar to the workshop as I have no experience with coding, so wanted to ease myself into it. Keeping the variable to just the simple X, giving it the initial value of 0, I am able to set up a changabe and adaptable code that I am able to edit if I need to in the future. My code did not contain any conditional formatting yet, so I made sure to practice working with these to  add in a ‘let’ or ‘if’ statement. My code turned into:

let x = 0;

function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(100, 100, 10);

  fill(150, 0, 100);
  rect(mouseX, mouseY, 40, 60);
  
  x = x + 3; // x increases by 3 each frame
}



