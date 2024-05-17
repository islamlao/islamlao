<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>e.art - Pixel Art</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>e.art - Pixel Art</h1>
  </header>
  <main>
    <div class="canvas">
      <!-- Pixel canvas goes here -->
    </div>
    <div class="tools">
      <!-- Drawing tools and color palette goes here -->
    </div>
    <button id="saveBtn">Save Drawing</button>
    <button id="shareBtn">Share Drawing</button>
  </main>
  <footer>
    <p>&copy; 2024 e.art - All rights reserved.</p>
  </footer>
  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #f8f8f8;
  margin: 0;
  padding: 0;
}

header {
  background-color: #ff8c00;
  color: white;
  padding: 20px;
}

main {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  padding: 20px;
}

.canvas {
  width: 400px;
  height: 400px;
  border: 2px solid black;
  margin-right: 20px;
}

.tools {
  margin-right: 20px;
}

footer {
  background-color: #ff8c00;
  color: white;
  text-align: center;
  padding: 10px 0;
}
