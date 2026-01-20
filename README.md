<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ujjain Pet Care Organisation</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Ujjain Pet Care Organisation 🐾</h1>
    <p>Serving animals with love, care, and compassion</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#care">Care</a>
    <a href="#order">Order</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Us</h2>
    <p>
        Ujjain Pet Care Organisation is dedicated to animal wellbeing.
        Every product we sell is chosen with love, safety, and kindness
        for pets and stray animals alike.
    </p>
</section>

<section id="products">
    <h2>Our Products</h2>
    <div class="products">
        <div class="card">
            <h3>Pet Food</h3>
            <p>Healthy food for dogs, cats, birds & more.</p>
        </div>
        <div class="card">
            <h3>Toys</h3>
            <p>Safe and fun toys for happy pets.</p>
        </div>
        <div class="card">
            <h3>Accessories</h3>
            <p>Leashes, collars, beds, bowls & essentials.</p>
        </div>
    </div>
</section>

<section id="care">
    <h2>We Care for Every Life ❤️</h2>
    <p>
        Animals are family. We believe in gentle care,
        responsible pet ownership, and compassion.
    </p>
</section>

<section id="order">
    <h2>Order on WhatsApp 📱</h2>
    <p>Click below to order or ask about products:</p>

    <a class="whatsapp-btn"
       href="https://wa.me/919302042958"
       target="_blank">
       Chat on WhatsApp
    </a>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>📍 Ujjain, India</p>
    <p>📞 +91 93020 42958</p>
</section>

<footer>
    <p>© 2026 Ujjain Pet Care Organisation | Made with love for animals 🐶🐱</p>
</footer>

</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #fffaf3;
    color: #333;
}

header {
    background-color: #ffb703;
    text-align: center;
    padding: 30px 15px;
}

nav {
    background-color: #8ecae6;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 10px;
}

nav a {
    margin: 8px 12px;
    color: #023047;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 30px 15px;
    max-width: 900px;
    margin: auto;
}

.products {
    display: flex;
    flex-direction: column;
    gap: 20px;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.whatsapp-btn {
    display: inline-block;
    background-color: #25D366;
    color: white;
    padding: 15px 25px;
    border-radius: 30px;
    text-decoration: none;
    font-size: 18px;
    font-weight: bold;
}

footer {
    background-color: #023047;
    color: white;
    text-align: center;
    padding: 15px;
}

/* Desktop layout */
@media (min-width: 768px) {
    .products {
        flex-direction: row;
    }
}
