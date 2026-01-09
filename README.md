<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Project Preview</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      height: 100%;
      background: #f0f4f8;
    }

    .cover {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      height: 100vh;
      background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
      color: white;
      border-radius: 20px;
      margin: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      padding: 20px;
      transition: transform 0.3s;
    }

    .cover:hover {
      transform: scale(1.05);
    }

    .cover h1 {
      font-size: 3em;
      margin: 0.2em 0;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.3);
    }

    .cover p {
      font-size: 1.5em;
      margin: 0.2em 0;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
    }

    .button {
      margin-top: 20px;
      padding: 12px 30px;
      font-size: 1em;
      background-color: #ffcb05;
      border: none;
      border-radius: 50px;
      color: #333;
      cursor: pointer;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s, transform 0.3s;
    }

    .button:hover {
      background-color: #ffc107;
      transform: translateY(-3px);
    }

    /* إضافة عناصر كرتونية صغيرة */
    .cloud {
      position: absolute;
      width: 100px;
      height: 60px;
      background: white;
      border-radius: 50px;
      opacity: 0.6;
      animation: float 10s infinite linear;
    }

    .cloud:nth-child(1) { top: 50px; left: 100px; animation-duration: 12s;}
    .cloud:nth-child(2) { top: 120px; left: 300px; animation-duration: 15s;}
    .cloud:nth-child(3) { top: 200px; left: 50px; animation-duration: 10s;}

    @keyframes float {
      0% { transform: translateX(0); }
      100% { transform: translateX(800px); }
    }
  </style>
</head>
<body>
  <div class="cover">
    <h1>My Cool Project</h1>
    <p>GitHub Preview Made Fun</p>
    <a href="#" class="button">Explore</a>
    <div class="cloud"></div>
    <div class="cloud"></div>
    <div class="cloud"></div>
  </div>
</body>
</html>
