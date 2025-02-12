<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WI'AM COMMUNICATION</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #E0E0E0;
            transition: all 0.3s ease-in-out;
            scroll-behavior: smooth;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #1F1F1F;
            padding: 15px 50px;
            color: #FFD700;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.3);
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: #FFD700;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #E0E0E0;
        }
        .hero {
            text-align: center;
            padding: 100px 20px;
            background: url('hero-bg.jpg') no-repeat center center/cover;
            color: #FFD700;
            animation: fadeIn 1.5s ease-in;
        }
        .cta-button {
            background-color: #FFD700;
            padding: 10px 20px;
            color: #121212;
            font-weight: bold;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s, transform 0.2s;
        }
        .cta-button:hover {
            background-color: #E0E0E0;
            transform: scale(1.05);
        }
        section {
            padding: 50px;
            text-align: center;
            transition: transform 0.3s ease-in-out;
        }
        section:hover {
            transform: scale(1.02);
        }
        .service-box {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 30px 0;
        }
        .service-card {
            background-color: #1F1F1F;
            padding: 20px;
            width: 300px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s;
        }
        .service-card:hover {
            transform: scale(1.05);
        }
        .contact-form {
            text-align: center;
            padding: 50px;
            background-color: #1F1F1F;
        }
        .contact-form h2 {
            color: #FFD700;
        }
        .form-container {
            display: flex;
            flex-direction: column;
            max-width: 400px;
            margin: 0 auto;
        }
        .form-container input, .form-container textarea {
            margin-bottom: 15px;
            padding: 10px;
            font-size: 16px;
            background-color: #2A2A2A;
            color: #FFD700;
            border: 1px solid #FFD700;
            border-radius: 5px;
            transition: all 0.3s;
        }
        .form-container input:focus, .form-container textarea:focus {
            background-color: #3A3A3A;
            border-color: #E0E0E0;
        }
        .form-container button {
            background-color: #FFD700;
            color: #121212;
            padding: 10px;
            font-size: 16px;
            border: none;
            cursor: pointer;
            transition: background 0.3s;
        }
        .form-container button:hover {
            background-color: #E0E0E0;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1F1F1F;
            color: #FFD700;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">WI'AM COMMUNICATION</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Our Work</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home" class="hero">
        <h1>Creating Meaningful Connections Through Impactful Communication</h1>
        <p>From strategy to execution, we bring your brand to life across all channels.</p>
        <a href="#contact" class="cta-button">Let's Collaborate</a>
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>Wi'am Communication is a dynamic agency dedicated to crafting compelling brand stories and impactful campaigns. With a passion for innovation, we specialize in ATL and digital communication, experiential marketing, corporate and public events, and content development. Our expertise spans across industries, delivering strategic solutions that connect brands with their audiences in meaningful ways.</p>
        <p>Our mission is to redefine communication by blending creativity with strategy, ensuring maximum engagement and impact. We believe in fostering long-term relationships with our clients by delivering excellence in every project we undertake.</p>
    </section>
    
    <section id="services">
        <h2>Our Services</h2>
        <div class="service-box">
            <div class="service-card">ATL Communication</div>
            <div class="service-card">Digital Communication</div>
            <div class="service-card">Experiential Strategy & Campaign Design</div>
            <div class="service-card">Corporate & Public Events</div>
            <div class="service-card">Global Events & Campaigns</div>
            <div class="service-card">Reach & Activation</div>
            <div class="service-card">Digital Experiential Solutions</div>
            <div class="service-card">Gifts and Sourcing</div>
            <div class="service-card">Content Development & Show Production</div>
        </div>
    </section>
    
    <section id="contact" class="contact-form">
        <h2>Contact Us</h2>
        <div class="form-container">
            <input type="text" placeholder="Name">
            <input type="tel" placeholder="Phone Number">
            <input type="email" placeholder="Email">
            <textarea placeholder="Message"></textarea>
            <button type="submit">Send Message</button>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2025 WI'AM COMMUNICATION. All rights reserved.</p>
    </footer>
</body>
</html>
