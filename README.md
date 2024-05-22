function setup() {
  createCanvas(600, 600);
   background("cyan");
}

function draw() {

  stroke("blue");
  fill("purple");
  
  //console.log(mouseIsProssed);
  
  if (mouseIsPressed) {
    rect(mouseX, mouseY, 20,35);
  }
  
}
