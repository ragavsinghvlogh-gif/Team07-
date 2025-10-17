<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Homepage</title>
    <link rel="stylesheet" href="style.css"> </head>
<body>

    <header>
        <div class="logo">MyBrand</div>
        <nav>
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
        <button class="menu-toggle">☰</button> </header>

    <main class="hero-section" id="home">
        <h1>Welcome to Our Digital World!</h1>
        <p>We craft beautiful and functional web experiences for amazing clients.</p>
        <button class="cta-button" id="ctaBtn">Get Started Today</button>
    </main>

    <section class="content-section" id="about">
        <h2>Who We Are</h2>
        <p>Founded in 2023, we're a passionate team of developers and designers committed to delivering excellence. Our focus is on **innovation, quality, and client satisfaction.**</p>
    </section>

    <section class="content-section" id="services">
        <h2>What We Offer</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Web Design</h3>
                <p>Modern, responsive layouts that look great on any device.</p>
            </div>
            <div class="service-card">
                <h3>Development</h3>
                <p>Clean, efficient code for fast and scalable applications.</p>
            </div>
            <div class="service-card">
                <h3>Consulting</h3>
                <p>Expert advice to guide your project from concept to launch.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 MyBrand. All rights reserved.</p>
        <div class="social-links">
            <a href="#">Facebook</a> | <a href="#">Twitter</a>
        </div>
    </footer>

    <script src="script.js"></script> </body>
</html>
/* Base Styles & Reset */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

/* Header & Navigation */
header {
    background: #007bff; /* Primary Brand Color */
    color: white;
    padding: 1rem 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky; /* Keeps the header visible when scrolling */
    top: 0;
    z-index: 1000;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    padding: 0.5rem 1rem;
    transition: background-color 0.3s;
}

nav a:hover, nav a.active {
    background-color: #0056b3;
    border-radius: 4px;
}

.menu-toggle {
    display: none; /* Hide on desktop */
    background: none;
    border: none;
    color: white;
    font-size: 1.5rem;
    cursor: pointer;
}

/* Hero Section */
.hero-section {
    background: url('placeholder-image.jpg') no-repeat center center/cover; /* Replace with your image */
    background-color: #e9ecef;
    min-height: 50vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 2rem 5%;
    color: #333;
}

.hero-section h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero-section p {
    font-size: 1.25rem;
    margin-bottom: 1.5rem;
}

.cta-button {
    background-color: #28a745; /* Action Color */
/* Base Styles & Reset */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

/* Header & Navigation */
header {
    background: #007bff; /* Primary Brand Color */
    color: white;
    padding: 1rem 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky; /* Keeps the header visible when scrolling */
    top: 0;
    z-index: 1000;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    padding: 0.5rem 1rem;
    transition: background-color 0.3s;
}

nav a:hover, nav a.active {
    background-color: #0056b3;
    border-radius: 4px;
}

.menu-toggle {
    display: none; /* Hide on desktop */
    background: none;
    border: none;
    color: white;
    font-size: 1.5rem;
    cursor: pointer;
}

/* Hero Section */
.hero-section {
    background: url('placeholder-image.jpg') no-repeat center center/cover; /* Replace with your image */
    background-color: #e9ecef;
    min-height: 50vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 2rem 5%;
    color: #333;
}

.hero-section h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero-section p {
    font-size: 1.25rem;
    margin-bottom: 1.5rem;
}

.cta-button {
    background-color: #28a745; /* Action Color */
    color: white;
    padding: 0.75rem 1.5rem;
    font-size: 1rem;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.2s;
}

.cta-button:hover {
    background-color: #1e7e34;
    transform: scale(1.05);
}

/* Content Sections */
.content-section {
    padding: 4rem 5%;
    max-width: 1200px;
    margin: 0 auto;
}

.content-section:nth-child(even) {
    background-color: #fff; /* Alternate background for contrast */
}

h2 {
    text-align: center;
    margin-bottom: 2rem;
    font-size: 2rem;
    color: #007bff;
}

/* Services Grid */
.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    text-align: center;
}

.service-card {
    background: white;
    padding: 1.5rem;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Footer */
footer {
    background: #343a40;
    color: white;
    text-align: center;
    padding: 1.5rem 5%;
    font-size: 0.9rem;
}

.social-links a {
    color: #adb5bd;
    margin: 0 10px;
    text-decoration: none;
}

.social-links a:hover {
    color: white;
}

/* --- Media Queries for Responsiveness (Mobile View) --- */
@media (max-width: 768px) {
    /* Mobile Header */
    nav {
        display: none; /* Hide navigation by default on small screens */
        flex-direction: column;
        width: 100%;
        position: absolute;
        top: 60px; /* Below the header */
        left: 0;
        background: #007bff;
        padding: 10px 0;
        text-align: center;
    }

    nav.open {
        display: flex; /* Show when the 'open' class is added by JS */
    }

    nav a {
        margin: 0;
        padding: 10px 0;
        border-bottom: 1px solid #0056b3;
    }

    .menu-toggle {
        display: block; /* Show the menu button */
    }

    /* Mobile Hero */
    .hero-section h1 {
        font-size: 2rem;
    }

    .hero-section p {
        font-size: 1rem;
    }

    .content-section {
        padding: 2rem 5%;
    }
}
  nav a {
        margin: 0;
        padding: 10px 0;
        border-bottom: 1px solid #0056b3;
    }

    .menu-toggle {
        display: block; /* Show the menu button */
    }

    /* Mobile Hero */
    .hero-section h1 {
        font-size: 2rem;
    }

    .hero-section p {
        font-size: 1rem;
    }

    .content-section {
        padding: 2rem 5%;
    }
}


