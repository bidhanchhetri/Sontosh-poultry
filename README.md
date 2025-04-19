<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sontosh Poultry Feed - Ranipool, Gangtok</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #2d6a4f;
      --secondary: #40916c;
      --accent: #95d5b2;
      --light: #f9f9f9;
    }body {
  font-family: 'Poppins', sans-serif;
  background: var(--light);
  margin: 0;
  padding: 0;
  color: #333;
}

header {
  background-color: var(--primary);
  color: white;
  padding: 20px;
  text-align: center;
}

nav {
  display: flex;
  justify-content: center;
  background: var(--secondary);
  padding: 10px;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 15px;
  font-weight: bold;
  transition: color 0.3s;
}

nav a:hover {
  color: var(--accent);
}

.hero {
  background: linear-gradient(135deg, #95d5b2, #74c69d);
  color: white;
  padding: 80px 20px;
  text-align: center;
  animation: gradientBG 10s infinite alternate;
}

@keyframes gradientBG {
  from { background-position: left; }
  to { background-position: right; }
}

.section {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}

.products {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.product {
  background: white;
  border-radius: 15px;
  padding: 20px;
  width: 250px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  text-align: center;
  transition: transform 0.3s, box-shadow 0.3s;
}

.product:hover {
  transform: scale(1.03);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.product img {
  width: 100%;
  border-radius: 10px;
  height: 160px;
  object-fit: cover;
}

footer {
  background: var(--primary);
  color: white;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}

  </style>
</head>
<body>
  <header>
    <h1>Sontosh Poultry Feed</h1>
    <p>Quality Feed & Medicines for All Your Animals</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>
  <section class="hero">
    <h2>Your Trusted Animal Feed Store in Ranipool, Gangtok</h2>
    <p>Supplying feed and medicines for poultry, pigs, dogs, cats, and cows</p>
  </section>
  <section class="section" id="about">
    <h2>About Us</h2>
    <p>Welcome to <strong>Sontosh Poultry Feed</strong>, proudly owned by Mr. Sontosh Poudyal. We provide the best quality feed and medicine for poultry, pigs, dogs, cats, and cows. Located in the heart of Ranipool, Gangtok, our goal is to support farmers and pet owners with trusted and affordable products.</p>
  </section>
  <section class="section" id="products">
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://5.imimg.com/data5/SELLER/Default/2023/10/355091144/VM/WA/PA/64033518/power-feed-finisher-500x500.jpg" alt="Power Feed Finisher">
        <h3>Poultry Feed</h3>
        <p>High-nutrition feed for chickens, chicks, and layers.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1616840237035-3b9ddc99d1fd" alt="Poultry Medicine">
        <h3>Poultry Medicine</h3>
        <p>Effective medicines to ensure the health of your flock.</p>
      </div>
      <div class="product">
        <img src="https://5.imimg.com/data5/SELLER/Default/2023/8/335017579/JN/AB/NC/47064036/fat-pig-feed-500x500.jpg" alt="Fat Pig Feed">
        <h3>Pig Feed</h3>
        <p>Nutrient-rich feed for healthy pigs.</p>
      </div>
      <div class="product">
        <img src="https://www.pedigree.in/cdn/shop/files/1.2Kg-Chicken-Veg-FOP-NV.jpg?v=1697534131" alt="Pedigree Dog Food">
        <h3>Dog Feed</h3>
        <p>Wholesome food for active and healthy dogs.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1592194996308-7b43878e84a6" alt="Cat Feed">
        <h3>Cat Feed</h3>
        <p>Delicious and balanced food for cats of all ages.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1583592735345-7e9712d8724e" alt="Cow Feed">
        <h3>Cow Feed</h3>
        <p>Premium feed to support milk production and strength.</p>
      </div>
    </div>
  </section>
  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p><strong>Store Name:</strong> Sontosh Poultry Feed</p>
    <p><strong>Owner:</strong> Sontosh Poudyal</p>
    <p><strong>Location:</strong> Ranipool, Gangtok, Sikkim</p>
    <p><strong>Phone:</strong> <a href="tel:8945812423">8945812423</a></p>
    <p>We're here to serve you with quality and care!</p>
  </section>
  <footer>
    <p>&copy; 2025 Sontosh Poultry Feed. All rights reserved.</p>
  </footer>
</body>
</html>
