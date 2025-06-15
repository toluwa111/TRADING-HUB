<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Trading Hub</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; line-height: 1.6; }
    header { position: fixed; top: 0; width: 100%; background: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1); z-index: 1000; }
    .nav { display: flex; justify-content: space-between; align-items: center; padding: 1rem 2rem; max-width: 1200px; margin: 0 auto; }
    .nav ul { list-style: none; display: flex; gap: 1.5rem; }
    .nav ul li a { text-decoration: none; color: #333; font-weight: bold; }
    .nav ul li a:hover { color: #007bff; }
    .hero { height: 100vh; background: url('https://via.placeholder.com/1200x600') no-repeat center/cover; display: flex; align-items: center; justify-content: center; text-align: center; color: #fff; background-color: rgba(0,0,0,0.5); background-blend-mode: overlay; }
    .hero h1 { font-size: 3rem; margin-bottom: 1rem; }
    .hero p { font-size: 1.2rem; margin-bottom: 2rem; }
    .hero .btn { padding: 0.8rem 2rem; background: #007bff; color: #fff; text-decoration: none; border-radius: 5px; }
    .hero .btn:hover { background: #0056b3; }
    .sections { max-width: 1200px; margin: 5rem auto; padding: 0 2rem; display: grid; gap: 2rem; }
    .section { padding: 2rem; background: #f9f9f9; border-radius: 5px; text-align: center; }
    .section h2 { margin-bottom: 1rem; }
    footer { background: #333; color: #fff; text-align: center; padding: 2rem; margin-top: 5rem; }
    footer a { color: #007bff; text-decoration: none; }
    footer a:hover { text-decoration: underline; }
    @media (max-width: 768px) {
      .nav ul { flex-direction: column; gap: 1rem; }
      .hero h1 { font-size: 2rem; }
      .sections { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <header>
    <nav class="nav">
      <div class="logo">Your Trading Hub</div>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <div>
      <h1>Welcome to Your Trading Journey</h1>
      <p>Master forex, metals, and more with expert insights.</p>
      <a href="#services" class="btn">Get Started</a>
    </div>
  </section>

  <section id="about" class="sections">
    <div class="section">
      <h2>About Us</h2>
      <p>Learn to trade like a pro with strategies tailored to your goals, from $500 to $100,000.</p>
    </div>
  </section>

  <section id="services" class="sections">
    <div class="section">
      <h2>Our Services</h2>
      <p>Technical analysis, risk management, and live trading sessions for EUR/USD, XAG/USD, and more.</p>
    </div>
  </section>

  <section id="contact" class="sections">
    <div class="section">
      <h2>Contact</h2>
      <p>Reach out at yourtradinghub@example.com to start your journey.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Your Trading Hub. All rights reserved. <a href="#privacy">Privacy Policy</a> | <a href="#terms">Terms</a></p>
  </footer>
</body>
</html>
