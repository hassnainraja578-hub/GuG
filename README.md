<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday GuGu ❤️</title>
  <style>
    body {
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      padding: 50px;
      color: #fff;
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    p {
      font-size: 1.2em;
      margin: 20px 0;
    }
    .heart {
      font-size: 3em;
      animation: pulse 1s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
    .btn {
      background-color: #fff;
      color: #ff69b4;
      border: none;
      padding: 15px 25px;
      margin: 10px;
      font-size: 1em;
      border-radius: 30px;
      cursor: pointer;
      transition: transform 0.2s;
    }
    .btn:hover {
      transform: scale(1.1);
    }
    audio {
      display: none;
    }
  </style>
</head>
<body>
  <h1>🎉 Happy Birthday, GuGu!</h1>
  <div class="heart">❤️</div>
  <p>I love you more than words can express.</p>
  <p>May Allah bless you with endless joy, health, and success.</p>
  <p>You are the most precious part of my life, and I thank Allah for you every day.</p>
  <p style="font-size: 1.5em; font-weight: bold;">"جنم دن مبارک جان دیا ٹوٹیا"</p>

  <button class="btn" onclick="location.href='hearts.html'">💗 Click for Hearts</button>
  <button class="btn" onclick="location.href='stars.html'">🌟 Click for Stars</button>
  <button class="btn" onclick="location.href='quotes.html'">💬 Love Quotes</button>

  <audio autoplay loop>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
</body>
</html>
