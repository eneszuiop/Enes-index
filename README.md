<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Enes</title>
  <style>
    body {
      background-color: #ffe6e6;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .heart-svg {
      width: 300px;
      height: 300px;
      position: relative;
      margin-bottom: 40px;
    }

    .heart-svg svg {
      width: 100%;
      height: 100%;
    }

    .heart-text {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      font-size: 32px;
      font-weight: bold;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.4);
    }

    .bottom-text {
      font-size: 40px;
      color: #cc0000;
      font-weight: bold;
      text-align: center;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
    }
  </style>
</head>
<body>
  <div class="heart-svg">
    <svg viewBox="0 0 32 29.6">
      <path fill="red" d="M23.6,0c-3.4,0-6.4,2.3-7.6,5.6C14.8,2.3,11.8,0,8.4,0C3.8,0,0,3.8,0,8.4c0,9.5,16,21.2,16,21.2
      s16-11.7,16-21.2C32,3.8,28.2,0,23.6,0z"/>
    </svg>
    <div class="heart-text">Autos</div>
  </div>
  <div class="bottom-text">ENES SEIN PROJECT</div>
</body>
</html>
