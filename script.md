# Matita

    function setup() {
      createCanvas(400, 400);
      background(0);
      fill(255);
    }

    function draw() {
      if (mouseIsPressed) fill(255);
      else fill(0);
      circle(mouseX, mouseY, 4);
      //circle(400-mouseX, 400-mouseY, 4);
    }
