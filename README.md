!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dantechnology | Home</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #1e1e1e;
      color: white;
      padding: 20px;
    }
    .header-container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://via.placeholder.com/1200x400') center/cover no-repeat;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .services ul {
      list-style: none;
      padding: 0;
    }
    .services li {
      margin-bottom: 10px;
    }
    .gallery img {
      width: 30%;
      margin: 1%;
      border-radius: 8px;
    }
    .contact input, .contact textarea {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    .footer {
      background-color: #1e1e1e;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    button {
      background-color: #007bff;
      border: none;
      color: white;
      padding: 10px 20px;
      margin-top: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    @media (max-width: 768px) {
      .gallery img {
        width: 100%;
        margin-bottom: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="header-container">
      <img src="https://via.placeholder.com/150x50?text=Dantech+Logo" alt="Dantechnology Logo" style="height: 50px;" />
      <nav>
        <a href="#">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <h2>Empowering You Through Technology</h2>
    <p>Creative Designs, Professional Services & Tech Solutions</p>
    <button>Get Started</button>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>At Dantechnology, we bring creativity and innovation to your doorstep. Whether it's visual content, branding, or remote academic support, our team is here to help you succeed.</p>
  </section>

  <section id="services" class="section services">
    <h2>What We Do</h2>
    <ul>
      <li>🎉 Custom Birthday Card Designs</li>
      <li>🎨 Business Logo Creation</li>
      <li>🧾 Accurate & Fast Data Entry Services</li>
      <li>🎬 Video Editing for Social Media & Promotions</li>
      <li>🌍 Online Course Support for Clients Overseas</li>
    </ul>
  </section>

  <section id="gallery" class="section gallery">
    <h2>Gallery</h2>
    <p>See some of our past work:</p>
    <img src="https://via.placeholder.com/300x200" alt="Sample 1" />
    <img src="https://via.placeholder.com/300x200" alt="Sample 2" />
    <img src="https://via.placeholder.com/300x200" alt="Sample 3" />
  </section>

  <section id="contact" class="section contact">
    <h2>Contact Us</h2>
    <p><strong>Phone:</strong> 07034646828</p>
    <p><strong>Address:</strong> Block 13, House 15, Housing Estate, Ikangba, Ijebu Ode, Ogun State, Nigeria</p>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <div class="footer">
    <p>&copy; 2025 Dantechnology. All rights reserved.</p>
  </div>

</body>
</html>
