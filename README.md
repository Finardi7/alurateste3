<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>p5.js Project</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.5.0/p5.js"></script>
    <style>
        body {
            margin: 0;
            overflow: hidden;
        }
    </style>
</head>
<body>
    <script>
        // Código p5.js aqui
        function setup() {
            createCanvas(windowWidth, windowHeight);
            background(200);
        }

        function draw() {
            fill(255, 0, 0);
            ellipse(mouseX, mouseY, 50, 50);
        }

        function windowResized() {
            resizeCanvas(windowWidth, windowHeight);
        }
    </script>
</body>
</html>
