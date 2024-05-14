# dyadya
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Personal Webpage</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #ffffff;
            border-bottom: 1px solid #e0e0e0;
            padding: 20px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        section {
            padding: 40px;
            max-width: 800px;
            margin: auto;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #ffffff;
            border-top: 1px solid #e0e0e0;
        }
        .content {
            margin: 20px 0;
        }
        .content h2 {
            margin-bottom: 15px;
            color: #555;
        }
        .portfolio-item {
            border: 1px solid #ddd;
            padding: 10px;
            margin-bottom: 20px;
            background-color: #fff;
        }
    </style>
</head>
<body>

<header>
    <h1>Your Name</h1>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact Me</a>
        <a href="#blog">Blog</a>
    </nav>
</header>

<section id="about">
    <div class="content">
        <h2>About Me</h2>
        <p>Welcome to my personal webpage! Here you can learn more about me, view my portfolio, get in touch, and read my blog.</p>
    </div>
</section>

<section id="portfolio">
    <div class="content">
        <h2>Portfolio</h2>
        <div class="portfolio-item">
            <h3>Project Title 1</h3>
            <p>Description of your project. It can include details about the work, technologies used, and the outcome.</p>
        </div>
        <div class="portfolio-item">
            <h3>Project Title 2</h3>
            <p>Description of your project. It can include details about the work, technologies used, and the outcome.</p>
        </div>
        <!-- Add more projects as needed -->
    </div>
</section>

<section id="contact">
    <div class="content">
        <h2>Contact Me</h2>
        <p>If you would like to get in touch, please email me at <a href="mailto:your-email@example.com">your-email@example.com</a>.</p>
    </div>
</section>

<section id="blog">
    <div class="content">
        <h2>Blog</h2>
        <p>Welcome to my blog! Here you'll find my thoughts on various topics.</p>
        <!-- Blog posts can be added here -->
    </div>
</section>

<footer>
    <p>&copy; 2024 Your Name. All rights reserved.</p>
</footer>

</body>
</html>
