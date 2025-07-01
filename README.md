# Clicker-Game
<!DOCTYPE html>
<html>
<head>
  <title>Punch Game</title>
  <style>
    body { text-align: center; font-family: sans-serif; background: #fafafa; }
    button { font-size: 2em; padding: 1em; margin-top: 2em; }
  </style>
</head>
<body>
  <h1>Punch Clicker 👊</h1>
  <p>Score: <span id="score">0</span></p>
  <button id="punchBtn">PUNCH</button>

  <script>
    let score = 0;
    document.getElementById("punchBtn").onclick = () => {
      score++;
      document.getElementById("score").textContent = score;
    };
  </script>
</body>
</html>
