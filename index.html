<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Latihan Mengetik</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      text-align: center;
      padding: 20px;
    }
    h1 {
      color: #333;
    }
    #textDisplay {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      max-width: 600px;
      margin: 20px auto;
      font-size: 18px;
      line-height: 1.5;
    }
    #textInput {
      width: 80%;
      padding: 10px;
      font-size: 16px;
      margin-top: 10px;
    }
    #stats {
      margin-top: 20px;
      font-size: 18px;
    }
    button {
      margin-top: 20px;
      padding: 10px 15px;
      font-size: 16px;
      background: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: #0056b3;
    }
    .correct { color: green; }
    .incorrect { color: red; }
  </style>
</head>
<body>

  <h1>Website Latihan Mengetik</h1>
  <p>Mulai mengetik untuk memulai timer</p>

  <div id="textDisplay"></div>
  <textarea id="textInput" rows="4" placeholder="Ketik disini..."></textarea>
  
  <div id="stats">
    <p>Waktu: <span id="time">60</span> detik</p>
    <p>WPM: <span id="wpm">0</span></p>
    <p>Akurasi: <span id="accuracy">100</span>%</p>
  </div>

  <button onclick="startGame()">Mulai Ulang</button>

  <script>
    const texts = [
      "Belajar mengetik membutuhkan latihan yang konsisten setiap hari.",
      "Kecepatan mengetik diukur dalam kata per menit atau WPM.",
      "Semakin sering berlatih, semakin cepat dan akurat kemampuan mengetik Anda."
    ];

    let timeLeft = 60;
    let timer;
    let isPlaying = false;
    let correctChars = 0;
    let totalChars = 0;
    let currentText = "";

    const textDisplay = document.getElementById("textDisplay");
    const textInput = document.getElementById("textInput");
    const timeEl = document.getElementById("time");
    const wpmEl = document.getElementById("wpm");
    const accuracyEl = document.getElementById("accuracy");

    function startGame() {
      clearInterval(timer);
      timeLeft = 60;
      correctChars = 0;
      totalChars = 0;
      isPlaying = false;
      textInput.value = "";
      timeEl.textContent = timeLeft;
      wpmEl.textContent = 0;
      accuracyEl.textContent = 100;
      currentText = texts[Math.floor(Math.random() * texts.length)];
      renderText();
    }

    function renderText() {
      textDisplay.innerHTML = "";
      currentText.split("").forEach(char => {
        const span = document.createElement("span");
        span.textContent = char;
        textDisplay.appendChild(span);
      });
    }

    textInput.addEventListener("input", () => {
      const input = textInput.value.split("");
      totalChars++;

      if (!isPlaying) {
        isPlaying = true;
        timer = setInterval(countDown, 1000);
      }

      const spanArray = textDisplay.querySelectorAll("span");
      let correctCount = 0;

      spanArray.forEach((charSpan, index) => {
        const char = input[index];
        if (char == null) {
          charSpan.classList.remove("correct", "incorrect");
        } else if (char === charSpan.textContent) {
          charSpan.classList.add("correct");
          charSpan.classList.remove("incorrect");
          correctCount++;
        } else {
          charSpan.classList.add("incorrect");
          charSpan.classList.remove("correct");
        }
      });

      correctChars = correctCount;

      let wordsTyped = correctChars / 5;
      let minutes = (60 - timeLeft) / 60;
      wpmEl.textContent = minutes > 0 ? Math.round(wordsTyped / minutes) : 0;
      accuracyEl.textContent = totalChars > 0 ? Math.round((correctChars / totalChars) * 100) : 100;
    });

    function countDown() {
      timeLeft--;
      timeEl.textContent = timeLeft;
      if (timeLeft <= 0) {
        clearInterval(timer);
        textInput.disabled = true;
      }
    }

    startGame();
  </script>

</body>
</html>
