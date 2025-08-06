<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Meena - Donation & Fundraising</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f5f7fa;
    }

    header {
      background-color: #2d89e5;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    nav {
      background-color: #1c5fa4;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    .hero {
      padding: 60px 20px;
      background-image: url('https://images.unsplash.com/photo-1509099836639-18ba1795216d');
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
    }

    .hero h2 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2em;
      max-width: 600px;
      margin: auto;
    }

    .content {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
      background: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .content h3 {
      color: #2d89e5;
      margin-bottom: 15px;
    }

    .donation-form {
      display: flex;
      flex-direction: column;
    }

    .donation-form input,
    .donation-form textarea,
    .donation-form select,
    .donation-form button {
      margin-bottom: 15px;
      padding: 10px;
      font-size: 1em;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    .donation-form button {
      background-color: #2d89e5;
      color: white;
      border: none;
      cursor: pointer;
    }

    .donation-form button:hover {
      background-color: #256cba;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #1c5fa4;
      color: white;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 2em;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>HopeFund</h1>
    <p>Together We Can Make a Difference</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#donate">Donate</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Support Our Mission</h2>
    <p>Your donation helps us provide food, shelter, and hope to those in need.</p>
  </section>

  <section class="content" id="about">
    <h3>About Us</h3>
   <p>
    HopeFund is a dedicated non-profit organization committed to bringing positive change to underprivileged communities through compassion, support, and action. We aim to provide essential resources like food, education, and healthcare to those in need. Every donation, no matter how big or small, directly contributes to life-changing programs that empower individuals and uplift communities. By supporting HopeFund, you become part of a mission that believes in hope, humanity, and a better future for all. Join us today—your generosity can make a world of difference.
  </p>
    <p>HopeFund is a non-profit organization committed to improving the lives of underprivileged communities. We work with local partners to distribute essential resources and create opportunities for sustainable development.</p>
  </section>

  <section class="content" id="donate">
    <h3>Make a Donation</h3>
    <form class="donation-form">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Email Address" required>
      <input type="number" placeholder="Donation Amount (₹)" required>
      <select required>
        <option value="">Select Payment Method</option>
        <option value="upi">UPI</option>
        <option value="card">Credit/Debit Card</option>
        <option value="paypal">PayPal</option>
      </select>
      <textarea placeholder="Leave a message (optional)" rows="3"></textarea>
      <button type="submit">Donate Now</button>
    </form>
  </section>

  <footer id="contact">
    <p>Contact us: support@meenafund.org | © 2025 meenaFund</p>
  </footer>

</body>
</html>
