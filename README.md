<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Paws & Walks</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Walking dogs</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>We are two kids walking dogs</h2>
    <p>We walk your and more!</p>
    <a href="#contact" class="cta-button">Book a Walk</a>
  </section>

  <section id="services" class="section">
    <h2>Our Services</h2>
    <ul>
      <li><strong>Every 30-Mins of Walk:</ strong> $15</li>
      <li><strong>Cleaning dog crap in back yard and front :</strong> quote on size </li>
      <li><strong>Feeding and letting dog out :</strong> $10 </li>
    </ul>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>
      We will walk your dog to keep them healthy and fit. We also do it with multiple dogs
    </p>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" required />

      <label for="email">Email:</label>
      <input type="email" id="email" required />

      <label for="message">Information about dog (Size, friendliness, what you want and how to pay) :</label>
      <textarea id="message" rows="4" required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Walking dogs All rights reserved.</p>
  </footer>
</body>
</html>

body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  background: #f9f9f9;
  color: #333;
}

header {
  background: #4CAF50;
  color: white;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav a {
  color: white;
  margin-left: 15px;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  text-align: center;
  padding: 60px 20px;
  background: url('https://images.unsplash.com/photo-1518717758536-85ae29035b6d') center/cover no-repeat;
  color: white;
}

.cta-button {
  background: #ff9800;
  color: white;
  padding: 10px 20px;
  margin-top: 20px;
  display: inline-block;
  text-decoration: none;
  border-radius: 4px;
}

.section {
  padding: 40px 20px;
  max-width: 800px;
  margin: auto;
}

form {
  display: flex;
  flex-direction: column;
}

input, textarea {
  margin-bottom: 15px;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button {
  background: #4CAF50;
  color: white;
  padding: 10px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 20px;
}
