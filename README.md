# RE-CONNECT-SA
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>RE Connect SA - Digital Marketing Solutions</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <div class="logo">
                <h1>RE Connect SA</h1>
            </div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="hero">
        <h2>Elevating Your Digital Presence</h2>
        <p>Expert Digital Marketing Solutions for Your Business Growth</p>
        <a href="#contact" class="cta-button">Get Started</a>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about">
        <h2>Who We Are</h2>
        <p>RE Connect SA is your trusted digital marketing partner, specializing in comprehensive marketing strategies to help businesses connect with their target audience online.</p>
        <p>Our mission is to empower businesses to succeed in the digital world by providing innovative, effective, and cost-efficient marketing solutions.</p>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="service-item">
            <h3>Social Media Management</h3>
            <p>Manage platforms, create content, engage with followers, and grow your brand.</p>
        </div>
        <div class="service-item">
            <h3>SEO & SEM</h3>
            <p>Optimize websites and implement pay-per-click strategies to boost your visibility.</p>
        </div>
        <div class="service-item">
            <h3>PPC Campaigns</h3>
            <p>Cost-effective, targeted ads to bring qualified leads to your business.</p>
        </div>
        <div class="service-item">
            <h3>Content Creation</h3>
            <p>Develop engaging content for blogs, websites, and social media.</p>
        </div>
        <div class="service-item">
            <h3>Brand Strategy</h3>
            <p>Building and refining your digital presence and branding strategies.</p>
        </div>
    </section>

    <!-- Contact Us Section -->
    <section id="contact" class="contact">
        <h2>Get in Touch</h2>
        <form action="mailto:rolentelvis@gmail.com" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
        <p>Or reach us at <strong>0680607619</strong> or email <strong>rolentelvis@gmail.com</strong>.</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 RE Connect SA. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
/* General Styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #0057B7;
    padding: 20px;
    color: white;
}

header nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

header nav ul li {
    margin-left: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background-color: #FFA500;
    color: white;
    padding: 60px 20px;
    text-align: center;
}

.hero h2 {
    margin: 0;
    font-size: 36px;
}

.hero p {
    font-size: 20px;
}

.cta-button {
    background-color: #0057B7;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
    display: inline-block;
}

.services {
    padding: 40px 20px;
    text-align: center;
}

.services .service-item {
    margin: 20px 0;
}

.contact {
    background-color: #ffffff;
    padding: 40px 20px;
    text-align: center;
}

.contact form {
    max-width: 500px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

.contact form label {
    margin-bottom: 5px;
}

.contact form input,
.contact form textarea {
    margin-bottom: 15px;
    padding: 10px;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact form button {
    background-color: #0057B7;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}
