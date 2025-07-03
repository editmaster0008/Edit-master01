<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Edit Master 01</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Edit Master 01 - Free Photo Editor</h1>
  <input type="file" id="upload" accept="image/*">
  <canvas id="canvas"></canvas>
  <div class="tools">
    <button onclick="applyFilter('grayscale')">Gray</button>
    <button onclick="applyFilter('invert')">Invert</button>
    <button onclick="applyFilter('sepia')">Sepia</button>
    <button onclick="resetImage()">Reset</button>
  </div>
  <script src="script.js"></script>
</body>
</html>
