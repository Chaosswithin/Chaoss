<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chaoss Within</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e1e;
            color: #e74c3c;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1a1a1a;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            color: #e74c3c;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }
        section {
            padding: 20px;
        }
        .section-title {
            font-size: 2em;
            border-bottom: 2px solid #e74c3c;
            margin-bottom: 20px;
        }
        .shop-item, .appointment-form, .contact-info {
            background-color: #2e2e2e;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
        }
        .shop-item img {
            width: 100%;
            max-width: 300px;
            display: block;
            margin: 0 auto 10px;
        }
        .appointment-form input, .appointment-form textarea, .contact-info input, .contact-info textarea {
            width: calc(100% - 40px);
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }
        .appointment-form button, .contact-info button {
            padding: 10px 20px;
            background-color: #e74c3c;
            border: none;
            border-radius: 5px;
            color: #fff;
            font-size: 1em;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1a1a1a;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Chaoss Within</h1>
        <p>Nail Tech & Spiritual Advisor</p>
    </header>
    <nav>
        <a href="#shop">Shop</a>
        <a href="#appointment">Request Appointment</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="shop">
        <h2 class="section-title">Shop</h2>
        <div class="shop-item">
            <img src="nail-art.jpg" alt="Nail Art">
            <h3>Handmade Nail Art</h3>
            <p>Beautiful, custom-designed nail art pieces. Prices vary by design.</p>
        </div>
        <div class="shop-item">
            <img src="oracle-cards.jpg" alt="Oracle Cards">
            <h3>Oracle Card Readings</h3>
            <p>Insightful Oracle readings to guide you. $30 per session.</p>
        </div>
        <div class="shop-item">
            <img src="craft-item.jpg" alt="Craft Item">
            <h3>Homemade Crafts</h3>
            <p>Unique, handcrafted items to add a touch of magic to your space.</p>
        </div>
    </section>
    <section id="appointment">
        <h2 class="section-title">Request Appointment</h2>
        <div class="appointment-form">
            <form action="submit_appointment.php" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="What service are you interested in?" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </div>
    </section>
    <section id="contact">
        <h2 class="section-title">Contact</h2>
        <div class="contact-info">
            <form action="submit_contact.php" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
            <p>You can also reach us at <a href="mailto:contact@chaosswithin.com">contact@chaosswithin.com</a>.</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Chaoss Within. All rights reserved.</p>
    </footer>
</body>
</html>
