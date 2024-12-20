<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Professional Portfolio of Noorulain - Web Developer">
    <meta name="keywords" content="Web Developer, Portfolio, Full Stack, HTML, CSS, JavaScript, React, Node.js">
    <meta name="author" content="Noorulain">
    <title>Noorulain - Web Developer Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to My Professional Portfolio</h1>
            <p>Your Expert Web Developer</p>
            <a href="#about" class="cta-btn">Learn More About Me</a>
        </div>
    </section>

    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! I'm Noorulain, a passionate web developer with a love for creating innovative and dynamic websites. I specialize in both front-end and back-end development and strive to create websites that are not only functional but also visually appealing.</p>
        </div>
    </section>

    <section id="skills" class="section">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>HTML5, CSS3, JavaScript</li>
                <li>React, Node.js</li>
                <li>UI/UX Design</li>
                <li>WordPress & E-commerce Development</li>
                <li>Full Stack Development</li>
                <li>Responsive Web Design</li>
            </ul>
        </div>
    </section>

    <section id="portfolio" class="section">
        <div class="container">
            <h2>Description</h2>
            <div class="portfolio-items">
                Welcome to my portfolio, where creativity meets technology. Here, I showcase my most impactful and diverse projects that reflect my journey as a dedicated web developer and designer. Each project demonstrates my commitment to delivering exceptional user experiences through intuitive design, robust functionality, and modern web practices.

From e-commerce platforms that facilitate seamless shopping experiences to dynamic content-driven websites and personal portfolio pages, my work spans various industries and needs. I prioritize clean code, responsive layouts, and efficient solutions tailored to client specifications and industry standards.

Explore my featured projects below to see firsthand the skills, tools, and technologies I’ve applied to bring ideas to life. With a focus on user-centric development and an eye for detail, I strive to create websites that not only look good but perform flawlessly."
                <!-- Portfolio Item Example -->
        
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Contact Me</h2>
            <p>If you're interested in working together, feel free to get in touch!</p>
            <form action="submit_form.php" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Noorulain. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
