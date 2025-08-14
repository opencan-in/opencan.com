<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Opencan - Opening Ideas, Creating Futures</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #222;
        }
        header {
            background-color: #1a1a1a;
            color: white;
            padding: 20px 40px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
            opacity: 0.8;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            text-align: center;
            color: #ff6600;
            margin-bottom: 20px;
        }
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 2px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        .card h3 {
            color: #ff6600;
        }
        footer {
            background-color: #1a1a1a;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 0.9rem;
        }
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.8rem;
            }
            nav a {
                display: block;
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Opencan</h1>
    <p>Opening Ideas, Creating Futures</p>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>About Us</h2>
    <p>
        Opencan is a next-gen digital brand built to open doors for creators, businesses, and dreamers.
        We believe every idea deserves a stage, and we’re here to make it happen – from innovative concepts to real-world execution.
        With creativity, technology, and community at our core, Opencan is more than a brand – it’s a movement to inspire and empower.
    </p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">
            <h3>Digital Content Creation</h3>
            <p>Branding, social media, and premium design for your business or personal brand.</p>
        </div>
        <div class="card">
            <h3>E-Commerce Solutions</h3>
            <p>Shopify, dropshipping, and online store setup to bring your products to life.</p>
        </div>
        <div class="card">
            <h3>Community Projects</h3>
            <p>Collaborations, events, and campaigns that bring people together.</p>
        </div>
        <div class="card">
            <h3>Business Tools</h3>
            <p>Guides, templates, and resources to help startups grow.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Instagram: <a href="https://instagram.com/opencan" target="_blank">@opencan</a></p>
</section>

<footer>
    &copy; 2025 Opencan. All Rights Reserved.
</footer>

</body>
</html>
