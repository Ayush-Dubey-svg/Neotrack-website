<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Neotrack - Pharmacy Supply Chain Startup | neotrackpharmacy.com</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
    }

    header {
      background: #053218;
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 999;
    }

    header .logo {
      font-size: 1.5rem;
      font-weight: bold;
    }

    nav a {
      color: #fff;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 100px 2rem;
      min-height: 100vh;
    }

    #home {
      background: #eaf6ff;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    #about, #services, #contact {
      background: #f9f9f9;
    }

    h1, h2 {
      margin-bottom: 1rem;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
    }

    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      Neotrack
    </div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home">
    <div class="container">
      <h1>Welcome to Neotrack</h1>
      <p>Empowering the pharmacy supply chain with smart, reliable solutions.</p>
      <img src="https://i.postimg.cc/xj6LJ6y6/05d1d4fc-e604-44e9-b1ef-a4d6a0e4b35b-removalai-preview.png" alt="Neotrack Logo" style="margin-top: 20px; width: 900px; height: 426px; object-fit: contain;">
    </div>
  </section>

  <section id="about">
    <div class="container">
      <h2>About Us</h2>
      <p>Neotrack is a startup revolutionizing the pharmacy supply chain industry through cutting-edge logistics and inventory tracking solutions. Our platform ensures real-time visibility and optimized delivery across pharmaceutical networks.</p>
    </div>
  </section>

  <section id="services">
    <div class="container">
      <h2>Our Services</h2>
      <ul>
        <li>Smart Inventory Management</li>
        <li>Real-time Supply Chain Tracking</li>
        <li>Optimized Distribution Channels</li>
        <li>Data-Driven Analytics & Insights</li>
      </ul>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <p>Reach out for partnership inquiries, support, or more information about Neotrack.</p>
      <p>Email: adityasingh.lm10@gmail.com</p>
      <p>Phone: +91-7488056320, +91-9302989076</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Neotrack. All rights reserved. | <a href="https://neotrackpharmacy.com" style="color:#fff; text-decoration:none;">neotrackpharmacy.com</a></p>
  </footer>

  <script>
    // Optional JavaScript for smooth section focus
    document.querySelectorAll('nav a').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        target.scrollIntoView({ behavior: 'smooth' });
      });
    });
  </script>
</body>
</html>
