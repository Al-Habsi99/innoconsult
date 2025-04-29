<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>InnoConsult - Innovation & Startup Consulting</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      line-height: 1.6;
      background: #f9f9f9;
    }
    header {
      background: #0d1b2a;
      color: white;
      padding: 1em 2em;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2em;
      margin-top: 0.5em;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: #1b263b;
      color: white;
      padding: 4em 2em;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5em;
    }
    .hero p {
      font-size: 1.2em;
    }
    .section {
      padding: 3em 2em;
      max-width: 1000px;
      margin: auto;
    }
    .section h2 {
      color: #0d1b2a;
      margin-bottom: 1em;
      text-align: center;
    }
    .services, .testimonials {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5em;
    }
    .card {
      background: white;
      padding: 1.5em;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 0.75em;
      margin-bottom: 1em;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contact-form button {
      background: #0d1b2a;
      color: white;
      padding: 0.75em 1.5em;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #0d1b2a;
      color: white;
      text-align: center;
      padding: 1.5em;
      margin-top: 2em;
    }
  </style>
</head>
<body>

<header>
  <h1>InnoConsult</h1>
  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>Empowering Entrepreneurs. Accelerating Innovation.</h1>
  <p>Expert consulting to turn your tech vision into real-world success.</p>
</section>

<section id="services" class="section">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">
      <h3>Startup Advisory</h3>
      <p>Validate your business model and define go-to-market strategy.</p>
    </div>
    <div class="card">
      <h3>Innovation Consulting</h3>
      <p>Integrate emerging technologies and develop your product roadmap.</p>
    </div>
    <div class="card">
      <h3>Tech Solutions</h3>
      <p>Plan your MVP, choose the right stack, and execute smartly.</p>
    </div>
    <div class="card">
      <h3>Funding Support</h3>
      <p>Create strong pitch decks and prepare for investor engagement.</p>
    </div>
  </div>
</section>

<section id="about" class="section">
  <h2>About Us</h2>
  <p style="text-align: center; max-width: 700px; margin: auto;">
    We are a team of technologists, strategists, and startup veterans helping innovators overcome challenges, scale efficiently, and bring breakthrough ideas to market.
  </p>
</section>

<section id="testimonials" class="section">
  <h2>Testimonials</h2>
  <div class="testimonials">
    <div class="card">
      <p>“InnoConsult helped us pivot and secure seed funding within 3 months!”</p>
      <strong>– Jane D., Founder, TechStart</strong>
    </div>
    <div class="card">
      <p>“Their insights on AI integration were game-changing.”</p>
      <strong>– Carlos M., CEO, HealthSoft</strong>
    </div>
  </div>
</section>

<section id="contact" class="section">
  <h2>Contact Us</h2>
  <form class="contact-form">
    <input type="text" placeholder="Your Name" required />
    <input type="email" placeholder="Your Email" required />
    <textarea rows="5" placeholder="Your Message" required></textarea>
    <button type="submit">Let's Talk Innovation!</button>
  </form>
</section>

<footer>
  &copy; 2025 InnoConsult. All rights reserved.
</footer>

</body>
</html>
