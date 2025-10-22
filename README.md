# Quickscoot
It's a platform where people can find the EV/ two-wheeler on rental basis 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>QuickScoot - EV Rentals Thane</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <h1>QuickScoot</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#vehicles">Vehicles</a>
    <a href="#booking">Booking</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="home">
  <h2>Rent EV Bikes & Scooters in Thane</h2>
  <p>Eco-friendly, fast, and affordable rentals for students, professionals, and delivery partners.</p>
</section>

<section id="vehicles">
  <h2>Our Vehicles</h2>
  <div class="vehicle-list">
    <div class="vehicle">
      <h3>Activa 125</h3>
      <p>Daily ₹200 | Weekly ₹1200</p>
    </div>
    <div class="vehicle">
      <h3>iQube Electric</h3>
      <p>Daily ₹250 | Weekly ₹1500</p>
    </div>
  </div>
</section>

<section id="booking">
  <h2>Book Your Ride</h2>
  <form action="https://docs.google.com/forms/d/e/YOUR_FORM_ID/formResponse" target="_blank">
    <input type="text" name="entry.123456" placeholder="Full Name" required>
    <input type="tel" name="entry.234567" placeholder="Phone Number" required>
    <input type="text" name="entry.345678" placeholder="Vehicle (Activa/iQube)" required>
    <input type="date" name="entry.456789" placeholder="Booking Date" required>
    <input type="number" name="entry.567890" placeholder="Days to Rent" required>
    <button type="submit">Book Now</button>
  </form>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>📍 Kalyan & Thane, Maharashtra</p>
  <p>📞 +91 9324542080</p>
  <p>💬 WhatsApp: <a href="https://wa.me/919324542080" target="_blank">Chat Now</a></p>
</section>

<footer>
  <p>&copy; 2025 QuickScoot. All rights reserved.</p>
</footer>
</body>
</html>
body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
header { background: #28a745; color: white; padding: 10px 20px; display: flex; justify-content: space-between; align-items: center;}
header nav a { color: white; margin-left: 15px; text-decoration: none; font-weight: bold;}
section { padding: 40px 20px; }
.vehicle-list { display: flex; gap: 20px; }
.vehicle { background: #f1f1f1; padding: 20px; border-radius: 10px; flex: 1; text-align: center;}
form input, form button { display: block; width: 100%; padding: 10px; margin-bottom: 10px; border-radius: 5px; border: 1px solid #ccc;}
form button { background: #28a745; color: white; border: none; cursor: pointer; }
form button:hover { background: #218838; }
footer { text-align: center; padding: 20px; background: #222; color: white;}
