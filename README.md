<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Saroj Kunwar</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      padding: 20px;
    }

    .container {
      background: rgba(255, 255, 255, 0.1);
      padding: 30px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
      animation: fadeIn 2s ease-in-out;
    }

    img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid #fff;
      object-fit: cover;
      margin-bottom: 20px;
    }

    h1 {
      font-size: 2.2em;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1em;
      line-height: 1.5;
      margin-bottom: 20px;
    }

    .social a {
      text-decoration: none;
      color: white;
      margin: 0 10px;
      font-size: 1.4em;
      transition: transform 0.3s ease;
    }

    .social a:hover {
      transform: scale(1.2);
      color: #ffd700;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="https://i.ibb.co/CKdTD7xz/1752939425088-1.jpg" alt="Saroj Kunwar">
    <h1>Saroj Kunwar</h1>
    <p>
      Hello! I'm Saroj Kunwar. I’m passionate about learning, growing every day, and supporting my friends.
      I always try to bring positivity and energy in everything I do. <br>
      My friends describe me as a helpful and kind person.
    </p>
    <div class="social">
      <a href="https://www.facebook.com/share/19eDPtmxKe/" target="_blank">📘 Facebook</a>
      <a href="https://vm.tiktok.com/ZSHpfs8tgHUFF-5iHUv/" target="_blank">🎵 TikTok</a>
    </div>
  </div>
</body>
</html>
