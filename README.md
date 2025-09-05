<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sound Space Custom Maps</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 40px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }

    input[type="text"] {
      padding: 10px;
      width: 60%;
      max-width: 400px;
      border-radius: 25px;
      border: none;
      margin-bottom: 30px;
      font-size: 1em;
    }

    .button-container {
      margin: 20px 0;
    }

    .tag-button {
      background-color: #222;
      color: white;
      border: none;
      border-radius: 25px;
      padding: 10px 20px;
      margin: 5px;
      cursor: pointer;
      font-size: 1em;
      transition: background-color 0.2s;
    }

    .tag-button:hover {
      background-color: #444;
    }

    .section-title {
      font-size: 1.3em;
      margin-top: 30px;
      margin-bottom: 10px;
      color: #aaa;
    }
  </style>
</head>
<body>
  <h1>Sound Space Custom Maps</h1>

  <input type="text" placeholder="Search maps...">

  <div class="section-title">Difficulty Tags</div>
  <div class="button-container">
    <button class="tag-button">Tasukete</button>
    <button class="tag-button">Brrrr</button>
    <button class="tag-button">Logic</button>
    <button class="tag-button">Hard</button>
    <button class="tag-button">Medium</button>
    <button class="tag-button">Easy</button>
  </div>

  <div class="section-title">Style Tags</div>
  <div class="button-container">
    <button class="tag-button">Streams</button>
    <button class="tag-button">Walls</button>
    <button class="tag-button">Tech</button>
    <button class="tag-button">Jumps</button>
  </div>
</body>
</html>
