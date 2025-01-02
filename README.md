# Belizeantourcompany2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Belizean Tour Company</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background: url('https://example.com/hero-image.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        header h1 {
            font-size: 3rem;
            margin: 0;
        }
        header p {
            font-size: 1.5rem;
            margin: 10px 0 0;
        }
        nav {
            background: #007BFF;
            padding: 10px 20px;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: space-around;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            margin: 0;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
        }
        .tours {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .tour {
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            width: 300px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .tour img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .tour h3 {
            margin: 10px;
        }
        .tour p {
            margin: 10px;
            color: #555;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Belizean Adventures</h1>
        <p>Experience the beauty and wonder of Belize!</p>
    </header>
    <nav>
        <ul>
            <li><a href="#tours">Tours</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="tours">
        <h2>Our Tours</h2>
        <div class="tours">
            <div class="tour">
                <img src="https://example.com/jungle-tour.jpg" alt="Jungle Adventure">
                <h3>Jungle Adventure</h3>
                <p>Explore the lush jungles of Belize with expert guides.</p>
            </div>
            <div class="tour">
                <img src="https://example.com/snorkeling.jpg" alt="Snorkeling Experience">
                <h3>Snorkeling Experience</h3>
                <p>Dive into crystal-clear waters and discover marine life.</p>
            </div>
            <div class="tour">
                <img src="https://example.com/mayan-ruins.jpg" alt="Mayan Ruins">
                <h3>Mayan Ruins</h3>
                <p>Visit ancient sites and learn about Belize's rich history.</p>
            </div>
        </div>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>We are a passionate team dedicated to showcasing the best of Belize. Join us for unforgettable adventures and cultural experiences!</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@belizeadventures.com | Phone: +501-123-4567</p>
    </section>
    <footer>
        <p>&copy; 2025 Belizean Adventures. All rights reserved.</p>
    </footer>
</body>
</html>
