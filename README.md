<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ألعاب HTML5 الاحترافية</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
<style>
  body {
    font-family: 'Cairo', sans-serif;
    margin: 0;
    background: linear-gradient(135deg, #1f1f1f, #121212);
    color: #fff;
  }
  header {
    background: linear-gradient(90deg, #ff7f50, #ff4500);
    padding: 25px 0;
    text-align: center;
    box-shadow: 0 4px 10px rgba(0,0,0,0.3);
  }
  header h1 {
    margin: 0;
    font-size: 2.2rem;
    color: #fff;
    letter-spacing: 1px;
  }
  .container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 20px;
    padding: 20px;
  }
  .game-card {
    background-color: #1f1f1f;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 6px 20px rgba(0,0,0,0.6);
    transition: transform 0.3s, box-shadow 0.3s;
    position: relative;
  }
  .game-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 12px 30px rgba(0,0,0,0.8);
  }
  .game-card img {
    width: 100%;
    height: 160px;
    object-fit: cover;
    display: block;
    border-bottom: 2px solid #ff7f50;
  }
  .game-card h3 {
    margin: 12px 10px 5px;
    font-size: 1.1rem;
    color: #ff7f50;
  }
  .game-card p {
    margin: 0 10px 12px;
    font-size: 0.9rem;
    color: #ccc;
  }
  .play-btn {
    display: inline-block;
    margin: 0 0 15px 10px;
    padding: 8px 15px;
    background-color: #ff7f50;
    color: #fff;
    text-decoration: none;
    border-radius: 8px;
    transition: 0.3s;
    box-shadow: 0 4px 8px rgba(0,0,0,0.4);
  }
  .play-btn:hover {
    background-color: #ff4500;
    transform: scale(1.05);
  }
  footer {
    text-align: center;
    padding: 15px;
    background-color: #1f1f1f;
    color: #aaa;
    margin-top: 20px;
  }
</style>
</head>
<body>

<header>
  <h1>ألعاب HTML5 الاحترافية</h1>
</header>

<main class="container">

  <!-- مثال Game Card -->
  <!-- كرر هذا البلوك لكل لعبة وأضف الروابط والصور الحقيقية -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/_K3Jq9n1I3BPC8lQxR9W4NYjzUqG9bMoyM_M7g5hHj0jvS0wJ8hLfNYn_ZD3hY0nJQ=w600-h315-p-k" alt="City Car Driving: Stunt Master">
    <h3>City Car Driving: Stunt Master</h3>
    <p>لعبة قيادة سيارات ثلاثية الأبعاد مع حركات استعراضية مذهلة.</p>
    <a href="https://poki.com/ar/g/city-car-driving-stunt-master" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- كرر هذا لكل الألعاب السابقة + الـ12 الجديدة -->

</main>

<footer>
  &copy; 2025 جميع الحقوق محفوظة
</footer>

</body>
</html>
