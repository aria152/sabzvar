<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>سبزوار شهر زندگی</title>
  <style>
    @font-face {
      font-family: "IranNastaliq";
      src: url("https://cdn.fontcdn.ir/Font/Persian/IranNastaliq/IranNastaliq.woff2") format("woff2");
    }
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/6/67/Old_paper_texture.jpg');
      background-size: cover;
      background-position: center;
      font-family: "IranNastaliq", serif;
      color: #2d2d2d;
      direction: rtl;
    }
    h1 {
      font-size: 3.5rem;
      text-align: center;
      background-color: rgba(255,255,255,0.7);
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(0,0,0,0.2);
    }
    #form-container {
      margin-top: 30px;
      background: rgba(255,255,255,0.8);
      padding: 20px;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    input[type="text"] {
      padding: 10px;
      font-size: 1rem;
      border-radius: 10px;
      border: 1px solid #ccc;
      width: 200px;
      margin-bottom: 10px;
    }
    button {
      padding: 10px 20px;
      font-size: 1rem;
      border: none;
      background-color: #4CAF50;
      color: white;
      border-radius: 10px;
      cursor: pointer;
    }
    #response {
      margin-top: 15px;
      font-size: 1.2rem;
      color: green;
    }
  </style>
</head>
<body>
  <h1>سبزوار شهر زندگی</h1>

  <div id="form-container">
    <p>هرچی دوست داری بنویس:</p>
    <input type="text" id="userInput" placeholder="بنویس اینجا...">
    <br>
    <button onclick="sayBravo()">ارسال</button>
    <div id="response"></div>
  </div>

  <script>
    function sayBravo() {
      const input = document.getElementById('userInput').value.trim();
      const response = document.getElementById('response');
      if (input.length > 0) {
        response.textContent = "آفرین 👏";
      } else {
        response.textContent = "یه چیزی بنویس اول!";
      }
    }
  </script>
</body>
</html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>پس‌زمینه قدیمی</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Tahoma', sans-serif;
      background: url('https://www.transparenttextures.com/patterns/old-wall.png');
      background-color: #f5e6cc;
      background-size: cover;
      color: #3e3e3e;
      direction: rtl;
    }

    .overlay {
      background-color: rgba(255, 255, 255, 0.7);
      backdrop-filter: blur(2px);
      padding: 2rem;
      margin: 2rem;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }
  </style>
</head>
<body>
  <div class="overlay">
    <h1> دنبال چیی!</h1>
    <p>خب برو دیگه
    </p>
  </div>
</body>
</html>
