<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Do You Love Me? 💞</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      height: 100vh;
      background: linear-gradient(135deg, #ffb6c1, #ff69b4, #ff1493);
      overflow: hidden;
      color: white;
      text-align: center;
      transition: background 1s ease;
    }
    h1 {
      font-size: 28px;
      margin-bottom: 20px;
      text-shadow: 0 0 12px rgba(255,255,255,0.6);
    }
    img {
      max-width: 180px;
      border-radius: 15px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.3);
      margin: 20px;
      transition: transform 0.4s ease;
    }
    img:hover { transform: scale(1.05); }

    button {
      padding: 10px 20px;
      font-size: 16px;
      border: none;
      border-radius: 8px;
      background: white;
      color: #ff1493;
      margin: 10px;
      cursor: pointer;
      font-weight: bold;
      transition: transform 0.3s ease, background 0.3s;
    }
    button:hover { transform: scale(1.1); background: #ffe6f0; }

    #noButton {
      position: relative;
    }

    /* Floating hearts */
    .heart {
      position: fixed;
      bottom: -10px;
      color: #fff;
      animation: float 6s linear infinite;
      opacity: 0.8;
    }
    @keyframes float {
      0% { transform: translateY(0) scale(0.8); opacity: 0.8; }
      100% { transform: translateY(-100vh) scale(1.5); opacity: 0; }
    }

    .love-message {
      opacity: 0;
      font-size: 22px;
      font-weight: 600;
      color: #fff8f8;
      margin-top: 20px;
      transition: opacity 1s ease;
    }
    .love-message.show {
      opacity: 1;
    }
  </style>
</head>
<body>
  <h1 id="heading">Do you love me? 😊</h1>
  <img id="image" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGJ0b2Ztdjh6MXNlMTVzZXZuaGd4bG9vYnhyMXV3aDM0MWZ3OHRoNCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/c76IJLufpNwSULPk77/giphy.gif" alt="Cute Love GIF">
  <div>
    <button id="yesButton">Yes 💗</button>
    <button id="noButton" onmouseover="moveButton()">No 😜</button>
  </div>
  <div class="love-message" id="loveText">I love you too 💞<br>I’ll never cheat you — you’re my forever ❤️</div>

  <script>
    const yesButton = document.getElementById('yesButton');
    const noButton = document.getElementById('noButton');
    const heading = document.getElementById('heading');
    const image = document.getElementById('image');
    const loveText = document.getElementById('loveText');

    function moveButton() {
      const newX = Math.floor(Math.random() * (window.innerWidth - noButton.offsetWidth));
      const newY = Math.floor(Math.random() * (window.innerHeight - noButton.offsetHeight));
      noButton.style.position = 'absolute';
      noButton.style.left = newX + 'px';
      noButton.style.top = newY + 'px';
    }

    yesButton.addEventListener('click', () => {
      heading.textContent = "Hehe, I knew it! 😘";
      image.src = "https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZXE0aWZlaDM3bnlqamZma3drcGU1MzVzc3FwMmt2c3E1bDQyYnA2dCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/bA5cblwksWXDOwSzUI/giphy.gif";
      yesButton.style.display = "none";
      noButton.style.display = "none";
      loveText.classList.add("show");
      startHearts();
      startMusic();
      document.body.style.background = "linear-gradient(135deg, #ff69b4, #ff1493, #c71585)";
    });

    // Floating hearts generator
    function startHearts() {
      setInterval(() => {
        const heart = document.createElement('div');
        heart.classList.add('heart');
        heart.textContent = '💖';
        heart.style.left = Math.random() * 100 + 'vw';
        heart.style.fontSize = Math.random() * 24 + 16 + 'px';
        heart.style.animationDuration = (Math.random() * 3 + 3) + 's';
        document.body.appendChild(heart);
        setTimeout(() => heart.remove(), 6000);
      }, 300);
    }

    // Simple soft melody (Justin Bieber "Baby" inspired)
    const ctx = new (window.AudioContext || window.webkitAudioContext)();
    function play(freq, start, dur) {
      const osc = ctx.createOscillator();
      const gain = ctx.createGain();
      osc.type = "sine";
      osc.frequency.value = freq;
      osc.connect(gain);
      gain.connect(ctx.destination);
      gain.gain.setValueAtTime(0.1, start);
      gain.gain.exponentialRampToValueAtTime(0.001, start + dur);
      osc.start(start);
      osc.stop(start + dur);
    }
    function babyMelody() {
      const now = ctx.currentTime;
      const notes = [392,440,494,523,494,440,392,330,349,392,440,392];
      notes.forEach((n, i) => play(n, now + i * 0.35, 0.3));
    }
    function startMusic() {
      ctx.resume();
      babyMelody();
      setInterval(babyMelody, 8000);
    }
  </script>
</body>
</html>
