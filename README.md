# Restaurant-website-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Delight Bites</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background-color: #8B0000; color: white; padding: 1rem; text-align: center; }
    nav { background: #333; display: flex; justify-content: center; }
    nav a { color: white; padding: 1rem; text-decoration: none; }
    nav a:hover { background: #555; }
    section { padding: 2rem; }
    .hero { background: url('https://source.unsplash.com/1600x600/?restaurant,food') center/cover; height: 300px; }
    .menu { display: flex; flex-wrap: wrap; gap: 1rem; }
    .menu-item { background: #f8f8f8; padding: 1rem; border: 1px solid #ccc; flex: 1 1 200px; }
    footer { background: #222; color: #eee; text-align: center; padding: 1rem; }
  </style>
</head>
<body>
  <header>
    <h1>Delight Bites</h1>
    <p>Where every bite brings delight</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero"></div>

  <section id="about">
    <h2>About Us</h2>
    <p>At Delight Bites, we serve fresh, handmade dishes inspired by flavors from around the world. Whether you're craving a quick lunch or a luxurious dinner, we’ve got something for everyone.</p>
  </section>

  <section id="menu">
    <h2>Our Menu</h2>
    <div class="menu">
      <div class="menu-item">
        <h3>Grilled Chicken Bowl</h3>
        <p>Served with rice, avocado, and spicy aioli.</p>
      </div>
      <div class="menu-item">
        <h3>Veggie Pasta</h3>
        <p>Penne pasta tossed in a creamy mushroom sauce.</p>
      </div>
      <div class="menu-item">
        <h3>Chocolate Lava Cake</h3>
        <p>Warm, gooey and topped with vanilla ice cream.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@delightbites.com</p>
    <p>Phone: (123) 456-7890</p>
    <p>123 Flavor Street, Foodie Town</p>
  </section>

  <footer>
    <p>&copy; 2025 Delight Bites. All rights reserved.</p>
  </footer>
</body>
</html>
