<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zion Dimka | Fiverr Services</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
<style>
    body {
        font-family: 'Poppins', sans-serif;
        margin: 0;
        padding: 0;
        line-height: 1.6;
        color: #2c2c2c;
        background: #f9f9f9;
        scroll-behavior: smooth;
    }

    /* Sticky Navbar */
    nav {
        position: sticky;
        top: 0;
        z-index: 1000;
        display: flex;
        justify-content: center;
        background-color: #2c2c2c;
        box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    nav a {
        color: #fff;
        padding: 14px 20px;
        text-decoration: none;
        transition: 0.3s;
    }

    nav a:hover {
        background-color: #1dbf73;
    }

    header {
        background: url('https://source.unsplash.com/1600x400/?creative,work') center/cover no-repeat;
        color: #fff;
        padding: 60px 20px;
        text-align: center;
        position: relative;
    }

    header::after {
        content: "";
        position: absolute;
        top: 0; left: 0;
        width: 100%; height: 100%;
        background: rgba(29, 191, 115, 0.3);
    }

    header h1, header p {
        position: relative;
        z-index: 1;
        animation: fadeInDown 1s ease forwards;
    }

    @keyframes fadeInDown {
        0% {opacity: 0; transform: translateY(-20px);}
        100% {opacity: 1; transform: translateY(0);}
    }

    section {
        padding: 50px 20px;
        max-width: 1000px;
        margin: auto;
        background-color: #fff;
        margin-bottom: 20px;
        border-radius: 10px;
        box-shadow: 0 6px 20px rgba(0,0,0,0.05);
        opacity: 0;
        transform: translateY(30px);
        transition: all 0.8s ease-out;
    }

    section.visible {
        opacity: 1;
        transform: translateY(0);
    }

    h2 {
        color: #1dbf73;
        text-align: center;
        margin-bottom: 30px;
    }

    .services, .portfolio {
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
        justify-content: center;
    }

    .card {
        flex: 1 1 250px;
        background-color: #fff;
        padding: 20px;
        border-radius: 10px;
        text-align: center;
        box-shadow: 0 6px 15px rgba(0,0,0,0.05);
        transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
        transform: translateY(-10px);
        box-shadow: 0 10px 30px rgba(0,0,0,0.15);
    }

    .card img {
        width: 100%;
        border-radius: 10px;
        margin-bottom: 15px;
    }

    a.button {
        display: inline-block;
        margin-top: 15px;
        padding: 12px 20px;
        background-color: #1dbf73;
        color: #fff;
        text-decoration: none;
        border-radius: 5px;
        transition: background-color 0.3s, transform 0.3s;
    }

    a.button:hover {
        background-color: #17a25e;
        transform: scale(1.05);
    }

    footer {
        text-align: center;
        padding: 20px 0;
        background-color: #2c2c2c;
        color: #fff;
    }

    /* Back to Top Button */
    #backToTop {
        position: fixed;
        bottom: 30px;
        right: 30px;
        background-color: #1dbf73;
        color: white;
        padding: 12px 16px;
        border-radius: 50%;
        text-decoration: none;
        font-size: 20px;
        display: none;
        z-index: 1000;
        transition: background-color 0.3s, transform 0.3s;
    }

    #backToTop:hover {
        background-color: #17a25e;
        transform: scale(1.1);
    }

    /* Social Media Icons */
    #social-icons {
        position: fixed;
        left: 10px;
        bottom: 50px;
        display: flex;
        flex-direction: column;
        gap: 10px;
        z-index: 1000;
    }

    #social-icons a {
        background-color: #1dbf73;
        color: white;
        padding: 10px 12px;
        border-radius: 5px;
        text-decoration: none;
        font-weight: bold;
        transition: background-color 0.3s;
    }

    #social-icons a:hover {
        background-color: #17a25e;
    }

</style>
</head>
<body>

<header>
    <h1>Zion Dimka</h1>
    <p>Your Go-To Script & Logo Designer | YouTube Script Specialist</p>
</header>

<nav>
    <a href="#about">About Me</a>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Zion Dimka, a passionate freelancer offering professional script writing, logo design, and YouTube content scripting. I focus on delivering high-quality work that exceeds expectations.</p>
</section>

<section id="services">
    <h2>My Services</h2>
    <div class="services">
        <div class="card">
            <img src="https://source.unsplash.com/300x200/?script,writing" alt="Script Writing">
            <h3>Script Writing</h3>
            <p>Engaging and professional scripts for YouTube, presentations, and more.</p>
        </div>
        <div class="card">
            <img src="https://source.unsplash.com/300x200/?logo,design" alt="Logo Design">
            <h3>Logo Design</h3>
            <p>Creative logos that perfectly represent your brand.</p>
        </div>
        <div class="card">
            <img src="https://source.unsplash.com/300x200/?youtube,content" alt="YouTube Scripts">
            <h3>YouTube Scripts</h3>
            <p>Tailored scripts to boost your YouTube content and engagement.</p>
        </div>
    </div>
</section>

<section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio">
        <div class="card">
            <img src="https://source.unsplash.com/300x200/?creative,logo" alt="Portfolio 1">
            <p>Sample Logo Design</p>
        </div>
        <div class="card">
            <img src="https://source.unsplash.com/300x200/?writing,script" alt="Portfolio 2">
            <p>Sample Script</p>
        </div>
        <div class="card">
            <img src="https://source.unsplash.com/300x200/?youtube,video" alt="Portfolio 3">
            <p>YouTube Script Sample</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Interested in working together? Reach out via Fiverr or email!</p>
    <a class="button" href="https://www.fiverr.com/ziondimka" target="_blank">Visit My Fiverr</a>
</section>

<footer>
    <p>&copy; 2025 Zion Dimka. All rights reserved.</p>
</footer>

<!-- Back to Top Button -->
<a href="#" id="backToTop">&#8679; Top</a>

<!-- Social Media Icons -->
<div id="social-icons">
    <a href="https://www.fiverr.com/ziondimka" target="_blank">Fiverr</a>
    <a href="https://www.facebook.com" target="_blank">Facebook</a>
    <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
</div>

<script>
// Fade-in sections on scroll
const sections = document.querySelectorAll('section');
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if(entry.isIntersecting){
            entry.target.classList.add('visible');
        }
    });
}, { threshold: 0.2 });

sections.forEach(section => observer.observe(section));

// Back to Top Button Script
const backToTop = document.getElementById('backToTop');
window.addEventListener('scroll', () => {
    if(window.scrollY > 300){
        backToTop.style.display = 'block';
    } else {
        backToTop.style.display = 'none';
    }
});
</script>

</body>
</html>
