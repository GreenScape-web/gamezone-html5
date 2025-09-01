<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ألعاب HTML5 الاحترافية</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    background-color: #121212;
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
    font-size: 2rem;
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
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 6px 15px rgba(0,0,0,0.4);
    transition: transform 0.3s, box-shadow 0.3s;
  }
  .game-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.6);
  }
  .game-card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    display: block;
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
    margin: 0 0 15px;
    padding: 8px 15px;
    background-color: #ff7f50;
    color: #fff;
    text-decoration: none;
    border-radius: 6px;
    transition: 0.3s;
  }
  .play-btn:hover {
    background-color: #ff4500;
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

  <!-- Game 1 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/_K3Jq9n1I3BPC8lQxR9W4NYjzUqG9bMoyM_M7g5hHj0jvS0wJ8hLfNYn_ZD3hY0nJQ=w600-h315-p-k" alt="City Car Driving: Stunt Master">
    <h3>City Car Driving: Stunt Master</h3>
    <p>لعبة قيادة سيارات ثلاثية الأبعاد مع حركات استعراضية مذهلة.</p>
    <a href="https://poki.com/ar/g/city-car-driving-stunt-master" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 2 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/W1jGl5ogkWgFvJ4dZG9-M8rzUoLltJG3V-2Xh7jU8d5XQ6e8whkLr0s4Bnbc1Lq0E-A=w600-h315-p-k" alt="Monkey Mart">
    <h3>Monkey Mart</h3>
    <p>ادخل عالم إدارة المتاجر وبيع المنتجات للعملاء.</p>
    <a href="https://poki.com/ar/g/monkey-mart" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 3 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/5Hq2vPZrM7GJvTkxOThK5_9f0c4_CsFqVlhvRKEiQpZJpS7-HEpYxOX0N8HksuHP7Q=w600-h315-p-k" alt="Moto X3M">
    <h3>Moto X3M</h3>
    <p>سباق دراجات نارية مليء بالتحديات والمراحل الصعبة.</p>
    <a href="https://poki.com/ar/g/moto-x3m" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 4 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/xWv1dS6hRz8lkM4Bwr8vIydrXt2uQ-O9ZB0XYhZg2ZzpBmxsLwJtT5g6y0V4Jtx3HA=w600-h315-p-k" alt="Combat Online">
    <h3>Combat Online</h3>
    <p>لعبة إطلاق نار متعددة اللاعبين مع خرائط متنوعة.</p>
    <a href="https://poki.com/ar/g/combat-online" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 5 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/6U0B7g6tE0V5a5U6gn2z0e3pU6jH0R59vK_9cI5J8jQkNYP7D2q4A3g=w600-h315-p-k" alt="Subway Surfers">
    <h3>Subway Surfers</h3>
    <p>اركض لأبعد مسافة وتجنب العقبات لجمع المكافآت.</p>
    <a href="https://poki.com/ar/g/subway-surfers" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 6 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/Q5K7nT8fV7RzD4z7gO7aF0I5cM8xT3l8H3C5bU7hR9T7jV1N4m=w600-h315-p-k" alt="Minefun.io">
    <h3>Minefun.io</h3>
    <p>تعدين وبناء هياكل في عالم متعدد اللاعبين.</p>
    <a href="https://poki.com/ar/g/minefun-io" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 7 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/3X7V2jK0R9T8L5fP6Q8zN4M7jY2B8L5tV4K3gQ7R1S0fN3u=w600-h315-p-k" alt="Mr Racer - Car Racing">
    <h3>Mr Racer - Car Racing</h3>
    <p>سباق سيارات مع مسارات متنوعة ومنافسات مثيرة.</p>
    <a href="https://poki.com/ar/g/mr-racer-car-racing" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 8 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/1J8P4hS6K2T7L9V0B3D5C6F8G1M3H7J9Q2W4Y5R6S7V0B=w600-h315-p-k" alt="Blocky Blast Puzzle">
    <h3>Blocky Blast Puzzle</h3>
    <p>حل الألغاز عن طريق ترتيب القطع لتفجيرها.</p>
    <a href="https://poki.com/ar/g/blocky-blast-puzzle" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 9 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/9L7D5J3H1G8K2F6B0R5P4T7S3C9D1W5Q2E4Y6N7R8U0V=w600-h315-p-k" alt="Vectaria.io">
    <h3>Vectaria.io</h3>
    <p>قتال متعدد اللاعبين في بيئة ثلاثية الأبعاد.</p>
    <a href="https://poki.com/ar/g/vectaria-io" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 10 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/4Q7E5F3P8G1H2J6K0R5T9L3V1S7C2B5N8W3X4Y6Z0R=w600-h315-p-k" alt="Red Ball 4">
    <h3>Red Ball 4</h3>
    <p>تحكم بكرة حمراء لتجاوز العقبات وحل الألغاز.</p>
    <a href="https://poki.com/ar/g/red-ball-4" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 11 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/2B7D9E5F0G4H1J8K3L6M0N9P2R5S7T4V1W3X6Y8Z0B=w600-h315-p-k" alt="Scary Teacher 3D">
    <h3>Scary Teacher 3D</h3>
    <p>قم بإزعاج المعلمة المخيفة في مغامرة ممتعة.</p>
    <a href="https://poki.com/ar/g/scary-teacher-3d" target="_blank" class="play-btn">العب الآن</a>
  </div>

  <!-- Game 12 -->
  <div class="game-card">
    <img src="https://play-lh.googleusercontent.com/5J8F2G3H0K6L1M9N4P7Q0R2S5T8V3W1X6Y0Z4B7C9D=w600-h315-p-k" alt="Highway Bike Simulator">
    <h3>Highway Bike Simulator</h3>
    <p>محاكاة قيادة دراجة نارية على الطرق السريعة.</p>
    <a href="https://poki.com/ar/g/highway-bike-simulator" target="_blank" class="play-btn">العب الآن</a>
  </div>

</main>

<footer>
  &copy; 2025 جميع الحقوق محفوظة
</footer>

</body>
</html>
