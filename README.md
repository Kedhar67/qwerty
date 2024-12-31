<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gopika's Homeopathy Clinic</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
        }
        header {
            background-color: #4caf50;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 10px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4caf50;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-bottom: 30px;
        }
        .section h2 {
            color: #4caf50;
        }
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #4caf50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #4caf50;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gopika's Homeopathy Clinic</h1>
        <p>Your Health, Our Priority</p>
    </header>
    <nav>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <div id="services" class="section">
            <h2>Our Services</h2>
            <p>We provide personalized homeopathic treatments for a variety of conditions, including:</p>
            <ul>
                <li>Chronic illnesses</li>
                <li>Allergies</li>
                <li>Stress and anxiety</li>
                <li>Pain management</li>
            </ul>
        </div>
        <div id="about" class="section">
            <h2>About Us</h2>
            <p>Our clinic is dedicated to providing holistic and natural solutions to improve your well-being. With years of experience in homeopathy, we focus on treating the root cause of health issues rather than just the symptoms.</p>
        </div>
        <div id="contact" class="section">
            <h2>Contact Us</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Homeopathy Clinic. All rights reserved.</p>
    </footer>
</body>
</html>
