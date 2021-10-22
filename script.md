[<------ Prev  ](./immagini.md)

---

# Testa con occhi

```javascript
    function setup() {
      createCanvas(400, 400);
      fill(255);
    }

    function draw() {
      background(255);

      // testa quadrata
      fill(255);
      rect(10, 10, 380, 380);

      if (mouseIsPressed) fill(0);
      else fill(255);

      // occhi
      circle(100, 200, 100);
      circle(300, 200, 100);
    }
```

```javascript
    function setup() {
      createCanvas(400, 400);
      fill(255);
    }

    function draw() {
      background(255);

      // testa quadrata
      fill(255);
      rect(10, 10, 380, 380);

      if (mouseIsPressed) {
        // occhi quadrati neri
        fill(255);
        rect(50, 150, 100, 100);
        rect(250, 150, 100, 100);
      } else {
        // occhi tondi bianchi
        fill(0);
        circle(100, 200, 100);
        circle(300, 200, 100);
      }
    }
```

# Matita

```javascript
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
```

# Cerchio serpentone

```javascript
    function setup() {
     createCanvas(400, 400);
    }
    function draw() {
     if (mouseIsPressed) {
     fill(0);
     } else {
     fill(255);
     }
     ellipse(mouseX, mouseY, 80, 80);
    }
```

---

[<------ Prev  ](./immagini.md)
