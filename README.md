# MariaEliza
<!DOCTYPE html>
<html lang="en">
  <head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.4/p5.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.4/addons/p5.sound.min.js"></script>
    <link rel="stylesheet" type="text/css" href="style.css">
    <meta charset="utf-8" />

  </head>
  <body>
    <main>
    </main>
    <script src="sketch.js"></script>
  </body>
</html>

function setup() {
  createCanvas(900, 800);//tamanho da tela
  background("white");//cor da tela
}

function draw() {
  stroke("yellow");//cor de fora
  fill("orange");//cor de dentro

  // console.log(mouseIsPressed)

  if (mouseIsPressed) {
    rect(mouseX, mouseY, 15, 15);//regula o tamanho
  }
}
