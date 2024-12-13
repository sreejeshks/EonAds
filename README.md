<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Marketing Agency</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Digital Marketing Agency</h1>
            <nav>
                <ul>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Grow Your Business With Us</h2>
            <p>We offer top-notch digital marketing services to help you achieve your goals.</p>
            <a href="#contact" class="btn">Get Started</a>
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service">
                    <h3>SEO Optimization</h3>
                    <p>Boost your website's search engine ranking and visibility.</p>
                </div>
                <div class="service">
                    <h3>Social Media Marketing</h3>
                    <p>Engage your audience and grow your brand on social media platforms.</p>
                </div>
                <div class="service">
                    <h3>Content Creation</h3>
                    <p>Create high-quality content that resonates with your audience.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>We are a passionate team of digital marketers dedicated to helping businesses thrive online.</p>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Our Portfolio</h2>
            <div class="portfolio-items">
                <div class="portfolio-item">
                    <img src="project1.jpg" alt="Project 1">
                    <h3>Project 1</h3>
                </div>
                <div class="portfolio-item">
                    <img src="project2.jpg" alt="Project 2">
                    <h3>Project 2</h3>
                </div>
                <div class="portfolio-item">
                    <img src="project3.jpg" alt="Project 3">
                    <h3>Project 3</h3>
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="/submit-form" method="POST">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Digital Marketing Agency. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
