# Indikraft.in-task-1
First completed task of Indikraft 
<!--Indikraft.in internship Task1-->
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HandCrafted Aura</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Roboto&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background: #fefcf9;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #fff6e5;
      padding: 20px 50px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 28px;
      color: #c87d3f;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 80px 50px;
      /*ye img unsplash.com nam ki website se liya gya h*/
      background: url('https://images.unsplash.com/photo-1544986581-efac024faf62') no-repeat center/cover;
      color: #fff;
      height: 80vh;
      animation: fadeIn 2s ease-in-out;
    }
    .hero-text {
      max-width: 50%;
    }
    .hero h2 {
      font-size: 48px;
      margin-bottom: 20px;
      font-family: 'Playfair Display', serif;
    }
    .hero p {
      font-size: 18px;
      margin-bottom: 30px;
    }
    .hero button {
      background: #c87d3f;
      border: none;
      padding: 12px 25px;
      color: #fff;
      font-size: 16px;
      cursor: pointer;
      border-radius: 4px;
      transition: background 0.3s ease;
    }
    .hero button:hover {
      background: #a8642f;
    }
    .features {
      padding: 60px 50px;
      background: #fff;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      animation: slideIn 1.5s ease-out;
    }
    .feature {
      text-align: center;
      padding: 20px;
      border: 1px solid #f0e1c0;
      border-radius: 10px;
      background: #fffdf9;
      transition: transform 0.3s;
    }
    .feature:hover {
      transform: translateY(-5px);
    }
    .feature img {
      width: 80px;
      margin-bottom: 15px;
    }
    footer {
      background: #fff6e5;
      padding: 20px 50px;
      text-align: center;
      font-size: 14px;
    }@keyframes fadeIn {
  0% { opacity: 0; transform: translateY(20px); }
  100% { opacity: 1; transform: translateY(0); }
}

@keyframes slideIn {
  0% { opacity: 0; transform: translateX(-30px); }
  100% { opacity: 1; transform: translateX(0); }
}

  </style>
</head>
<body>
  <header>
    <h1>HandCrafted Aura</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#features">Features</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section class="hero">
    <div class="hero-text">
      <h2>Feel the Soul of Handmade</h2>
      <p>Explore a collection of carefully crafted, soulful art pieces made with love and tradition.</p>
      <button>Shop Now</button>
    </div>
  </section>  <section class="features" id="features">
    <div class="feature">
      <!--ye img flaticon website se liya gya h-->
      <img src="https://cdn-icons-png.flaticon.com/512/1256/1256650.png" alt="Natural Material">
      <h3>Eco-Friendly</h3>
      <p>All crafts made with 100% natural and sustainable materials.</p>
    </div>
    <div class="feature">
      <!--ye img flaticon website se liya gya h-->
      <img src="https://cdn-icons-png.flaticon.com/512/3533/3533740.png" alt="Artisan">
      <h3>Handmade by Experts</h3>
      <p>Each piece tells a story—crafted by local artisans with decades of experience.</p>
    </div>
    <div class="feature">
      <!--ye img flaticon website se liya gya h-->
      <img src="https://cdn-icons-png.flaticon.com/512/1828/1828911.png" alt="Unique">
      <h3>Truly Unique</h3>
      <p>No two pieces are the same. Own something that's one of a kind.</p>
    </div>
  </section>  <footer id="contact">
    <p>&copy; 2025 HandCrafted Aura. All rights reserved.</p>
  </footer>
</body>
</html>
