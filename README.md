<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Emmy Space</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-image: url(''); /* Background image placeholder */
      background-size: cover;
      background-repeat: no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      width: 100%;
      max-width: 800px;
      opacity: 0.3; /* Make everything initially locked */
      pointer-events: none; /* Disable clicks */
    }
    .box {
      background-color: #007bff;
      color: #fff;
      padding: 20px;
      text-align: center;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
      font-size: 18px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .password-section {
      text-align: center;
      background-color: rgba(255, 255, 255, 0.8);
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      width: 300px;
    }
    .password-input {
      width: 100%;
      padding: 10px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .unlock-btn {
      margin-top: 10px;
      padding: 10px;
      font-size: 16px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .hidden-section {
      display: none;
    }
  </style>
</head>
<body>
  <div class="password-section">
    <h2>Enter Password to Access</h2>
    <input type="password" id="password" class="password-input" placeholder="Enter Password">
    <button class="unlock-btn" onclick="unlockPage()">Unlock</button>
  </div>

  <div class="container hidden-section">
    <a href="https://emmy-space-link" class="box">WiFi Hacking</a>
    <a href="https://emmy-space-link" class="box">Android Hack</a>
    <a href="https://emmy-space-link" class="box">Hacking Tool</a>
    <a href="https://emmy-space-link" class="box">Dark Web Course</a>
    <a href="https://emmy-space-link" class="box">Android Editor Tools</a>
    <a href="https://emmy-space-link" class="box">Deploy Bots Free</a>
  </div>

  <script>
    function unlockPage() {
      const password = document.getElementById('password').value;
      if (password === 'FUCKYOUBITCH') {
        document.querySelector('.password-section').style.display = 'none';
        document.querySelector('.container').style.opacity = '1';
        document.querySelector('.container').style.pointerEvents = 'auto';
        document.querySelector('.hidden-section').style.display = 'grid';
      } else {
        alert('Incorrect password. Please try again.');
      }
    }
  </script>
</body>
</html>
