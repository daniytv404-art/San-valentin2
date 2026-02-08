<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>San Valentín 💖</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #ffe6f0;
      margin-top: 100px;
    }

    h1 {
      font-size: 36px;
      color: #ff4d88;
    }

    #buttons {
      margin-top: 40px;
      position: relative;
      height: 200px;
    }

    button {
      font-size: 20px;
      padding: 12px 30px;
      margin: 10px;
      cursor: pointer;
      border: none;
      border-radius: 10px;
    }

    #yes {
      background-color: #ff4d88;
      color: white;
    }

    #no {
      background-color: #cccccc;
      position: absolute;
    }

    #message {
      margin-top: 30px;
      font-size: 22px;
      color: #444;
    }

    #yay {
      display: none;
      margin-top: 30px;
    }
  </style>
</head>

<body>

  <h1>Gabriela, ¿serías mi San Valentín? 💘</h1>

  <div id="buttons">
    <button id="yes" onclick="yesClick()">Sí</button>
    <button id="no" onmouseover="moveNo()">No</button>
  </div>

  <p id="message">Acepta mmwebo 😌</p>

  <div id="yay">
    <h2>¡YAAAAY! 🎉💖</h2>
    <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="300">
  </div>

  <script>
    function moveNo() {
      const noBtn = document.getElementById("no");
      const container = document.getElementById("buttons");

      const maxX = container.clientWidth - noBtn.clientWidth;
      const maxY = container.clientHeight - noBtn.clientHeight;

      const randomX = Math.floor(Math.random() * maxX);
      const randomY = Math.floor(Math.random() * maxY);

      noBtn.style.left = randomX + "px";
      noBtn.style.top = randomY + "px";
    }

    function yesClick() {
      document.getElementById("buttons").style.display = "none";
      document.getElementById("message").style.display = "none";
      document.getElementById("yay").style.display = "block";
    }
  </script>

</body>
</html>
