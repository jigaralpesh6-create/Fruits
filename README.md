<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fresh Fruits</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #fdfdfd;
    }
    header {
      background: #ff9800;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #ffe0b2;
      padding: 10px;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 50px;
      background: url('https://images.unsplash.com/photo-1574226516831-e1dff420e12b') no-repeat center/cover;
      color: white;
    }
    .fruits {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .fruit-card {
      background: white;
      border-radius: 10px;
      padding: 15px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .fruit-card img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #ff9800;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>🍎 Fresh Fruits Store 🍌</h1>
  </header>
  
  <nav>
    <a href="#">Home</a>
    <a href="#">Fruits</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>
  
  <section class="hero">
    <h2>Healthy & Fresh Fruits Delivered to You!</h2>
    <p>Eat Fresh, Stay Healthy 🍇🍊</p>
  </section>
  
  <section class="fruits">
    <div class="fruit-card">
      <img src="https://images.unsplash.com/photo-1574226516831-e1dff420e12b" alt="Apple">
      <h3>Apple</h3>
      <p>Sweet and crunchy red apples.</p>
    </div>
    <div class="fruit-card">
      <img src="https://images.unsplash.com/photo-1574226516831-e1dff420e12b" alt="Banana">
      <h3>Banana</h3>
      <p>Rich in potassium and energy.</p>
    </div>
    <div class="fruit-card">
      <img src="https://images.unsplash.com/photo-1574226516831-e1dff420e12b" alt="Mango">
      <h3>Mango</h3>
      <p>King of fruits, sweet and juicy.</p>
    </div>
  </section>
  
  <footer>
    <p>&copy; 2025 Fresh Fruits | All Rights Reserved</p>
  </footer>
</body>
</html>
