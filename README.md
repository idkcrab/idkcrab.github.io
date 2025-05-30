<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>crab.animator</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #0d0d0d;
      color: #eee;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      text-align: center;
    }
    h1 {
      font-size: 3rem;
      color: #00ffff;
    }
    p {
      color: #ccc;
      font-size: 1.2rem;
    }
    .btn {
      margin-top: 20px;
      padding: 10px 20px;
      background: #00ffff;
      color: #000;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
      transition: 0.2s;
    }
    .btn:hover {
      background: #00cccc;
    }
  </style>
</head>
<body>
  <h1>Welcome to crab.animator</h1>
  <p>Animations. Chaos. Crabs.</p>
  <button class="btn" onclick="alert('🦀 You clicked the crab button!')">Click Me</button>
</body>
</html>
