# Internet-speed-test
 Fast Internet speed test

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mera Website</internet speed test>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- speed test -->
    <header>
        <nav>
            <div class="logo">MeraLogo</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h1>Welcome to My Website</h1>
        <p>Aapke liye behtareen services</p>
        <a href="#contact" class="btn">Contact Us</a>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>Hamare baare mein information yahan likhein</p>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Hamari Services</h2>
        <div class="service-cards">
            <div class="card">
                <h3>Service 1</h3>
                <p>Service ki description</p>
            </div>
            <div class="card">
                <h3>Service 2</h3>
                <p>Service ki description</p>
            </div>
            <div class="card">
                <h3>Service 3</h3>
                <p>Service ki description</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Aapka Naam" required>
            <input type="email" placeholder="Aapka Email" required>
            <textarea placeholder="Aapka Message" rows="5" required></textarea>
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Mera Website. Sabhi rights reserved.</p>
    </footer>
</body>
</html>

/* General Styles */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Header */
header {
    background: #0077b6;
    color: #fff;
    padding: 20px 0;
}

header nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 90%;
    margin: auto;
}

header nav .logo {
    font-size: 28px;
    font-weight: bold;
    color: #fff;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

/* Hero Section */
.hero {
    background: #00b4d8;
    color: #fff;
    padding: 100px 20px;
    text-align: center;
}

.hero .btn {
    display: inline-block;
    padding: 12px 25px;
    background: #023e8a;
    color: #fff;
    text-decoration: none;
    margin-top: 20px;
    border-radius: 5px;
}

/* Sections */
section {
    padding: 60px 20px;
    text-align: center;
}

.service-cards {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    background: #fff;
    padding: 25px;
    border-radius: 5px;
    width: 280px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Contact Form */
.contact form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    max-width: 400px;
    margin: auto;
}

.contact form input,
.contact form textarea {
    padding: 12px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

.contact form .btn {
    background: #0077b6;
    border: none;
    color: #fff;
    cursor: pointer;
}

/* Footer */
footer {
    background: #023e8a;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}
