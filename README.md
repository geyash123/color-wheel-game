<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Color Wheel Game</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="game-container">
    <h1>Color Wheel Game 🎨</h1>
    <div class="instructions">
      <p>Try to stop the wheel on the target color! Press <b>SPIN</b> to start, then press <b>STOP</b> when you think it's on the right color.</p>
    </div>

    <div class="target-color" id="target-color">Target: Red</div>

    <div class="wheel-container">
      <div class="pointer"></div>
      <div class="wheel" id="wheel"></div>
    </div>

    <div class="controls">
      <button id="spin-btn">SPIN</button>
      <button id="stop-btn" disabled>STOP</button>
    </div>

    <div class="result" id="result"></div>
    <div class="score">
      <div>Score: <span id="score">0</span></div>
      <div>Attempts: <span id="attempts">0</span></div>
    </div>
  </div>

  <!-- ===================== -->
  <!-- README STYLE SECTION  -->
  <!-- ===================== -->
  <section style="max-width:800px;margin:50px auto;padding:20px;background:#fff;border-radius:15px;box-shadow:0 5px 15px rgba(0,0,0,0.2);">
    <h2>📖 About This Game</h2>
    <p>This project is a fun and simple <b>Color Wheel Game</b> built with <b>HTML, CSS, and JavaScript</b>.</p>

    <h3>🎮 How to Play</h3>
    <ol>
      <li>Click <b>SPIN</b> to start the wheel.</li>
      <li>Click <b>STOP</b> when you think the pointer is on the target color.</li>
      <li>If you land on the target, you score a point! 🎉</li>
    </ol>

    <h3>🚀 Deployment</h3>
    <p>You can host this project on:</p>
    <ul>
      <li><a href="https://vercel.com" target="_blank">Vercel</a></li>
      <li>GitHub Pages</li>
    </ul>

    <h3>👨‍💻 Author</h3>
    <p>Created by <b>geyash123</b>. ✨ Feel free to fork, modify, and improve this project!</p>
  </section>

  <script src="game.js"></script>
</body>
</html>
