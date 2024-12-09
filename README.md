# shacha.github.io
 
taxi-service-website/
│
├── index.html         (Home)
├── about.html        (About Us)
├── services.html     (Services)
├── booking.html      (Booking Form)
├── contact.html      (Contact Us)
│
└── css/
    └── style.css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to [Your Taxi Service]</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Welcome to Taxi on link </h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Us</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="booking.html">Book Now</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section class="hero">
            <h2>Reliable, Fast, and Affordable Rides</h2>
            <p>Your trusted taxi service provider for city rides and long distances.</p>
            <a href="booking.html" class="btn">Book a Ride</a>
        </section>
        
        <section class="features">
            <div>
                <h3>Professional Drivers</h3>
                <p>Experienced, courteous drivers ready for every ride.</p>
            </div>
            <div>
                <h3>Easy Booking</h3>
                <p>Book your cab in just a few clicks.</p>
            </div>
            <div>
                <h3>Affordable Prices</h3>
                <p>Pay only for your ride with no hidden fees.</p>
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 [Your Taxi Service]. All rights reserved.</p>
    </footer>
</body>
</html>
3. CSS: Styling
style.css
css
Copiar código
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body & Font */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

/* Header */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin: 10px 0;
}

header nav ul li {
    margin: 0 15px;
}

header nav ul li a {
    text-decoration: none;
    color: white;
}

/* Hero Section */
.hero {
    background: #555;
    color: white;
    text-align: center;
    padding: 50px 20px;
    border-bottom: 5px solid #f4a261;
}

.hero .btn {
    margin-top: 15px;
    padding: 10px 20px;
    background: #f4a261;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

/* Features Section */
.features {
    display: flex;
    justify-content: space-around;
    text-align: center;
    padding: 20px;
    background: #f4f4f4;
    gap: 10px;
}

.features div {
    flex: 1;
    padding: 10px;
}

/* Footer */
footer {
    text-align: center;
    padding: 10px 0;
    background: #333;
    color: white;
}

<form action="#" method="POST">
  <label for="name">Your Name:</label>
  <input type="text" id="name" name="name" required>
  
  <label for="pickup">Pickup Location:</label>
  <input type="text" id="pickup" name="pickup" required>
  
  <label for="dropoff">Drop-off Location:</label>
  <input type="text" id="dropoff" name="dropoff" required>
  
  <label for="date">Date & Time:</label>
  <input type="datetime-local" id="date" name="date" required>
  
  <button type="submit">Book Now</button>
</form>
