<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tilak Raval - Space Robotics</title>
    <style>
        /* General Styling */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(120deg, #1e1e2f, #0d0d20);
            color: #fff;
            overflow-x: hidden;
        }
        h1, h2, h3 {
            text-align: center;
            margin: 20px 0;
        }
        p {
            text-align: center;
            max-width: 800px;
            margin: 10px auto;
            line-height: 1.8;
        }

        /* Navbar Styling */
        nav {
            background: rgba(0, 0, 0, 0.8);
            padding: 10px 20px;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        nav a {
            color: #ffcc00;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            color: #ff6600;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            background: url('https://i.imgur.com/JZNtGYk.jpg') no-repeat center center/cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
        .hero h1 {
            font-size: 3.5em;
            margin: 0;
            text-shadow: 0 0 10px #000;
        }
        .hero p {
            font-size: 1.2em;
            margin: 10px 0;
        }

        /* Sections */
        section {
            padding: 50px 20px;
            text-align: center;
        }
        .section-title {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #ffcc00;
        }

        /* Cards */
        .cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .card {
            background: rgba(255, 255, 255, 0.1);
            border: 2px solid #ffcc00;
            border-radius: 15px;
            padding: 20px;
            width: 300px;
            text-align: left;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-10px);
        }
        .card h3 {
            color: #ffcc00;
        }
        .card a {
            color: #ffcc00;
            text-decoration: none;
        }
        .card a:hover {
            text-decoration: underline;
        }

        /* Footer */
        footer {
            text-align: center;
            background: rgba(0, 0, 0, 0.8);
            padding: 20px;
            color: #fff;
        }
        footer a {
            color: #ffcc00;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Hero Section -->
    <div class="hero">
        <h1>Welcome to Tilak Raval's Space Lab</h1>
        <p>🚀 Exploring the galaxies of robotics, AI, and IoT innovations 🌌</p>
    </div>

    <!-- About Section -->
    <section id="about">
        <h2 class="section-title">About Me</h2>
        <p>
            Aspiring Robotics & AI enthusiast specializing in autonomous systems and machine learning.
            Passionate about building robots that transform the future. Award-winning robotics competitor.
        </p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2 class="section-title">My Projects</h2>
        <div class="cards">
            <div class="card">
                <h3>Surveillance Robot</h3>
                <p>
                    A robot designed for real-time monitoring using Raspberry Pi. Features advanced movement and camera controls.
                </p>
                <a href="https://youtu.be/fgOO7rFT87U" target="_blank">Watch Video</a>
            </div>
            <div class="card">
                <h3>Maze Runner Robot</h3>
                <p>
                    Secured 2nd place at L.D. College Fest. Demonstrated strategic pathfinding and efficient navigation.
                </p>
                <a href="https://youtu.be/TaC9ipbxV9w" target="_blank">Watch Video</a>
            </div>
            <div class="card">
                <h3>Hand Gesture Robot</h3>
                <p>
                    Innovative robot controlled via OpenCV-based gesture recognition using ESP32.
                </p>
                <a href="https://youtu.be/DPfzIaQ385M" target="_blank">Watch Video</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2 class="section-title">Contact Me</h2>
        <p>Email: <a href="mailto:tilak25012003.ris@gmail.com">tilak25012003.ris@gmail.com</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/tilak-tr10" target="_blank">linkedin.com/in/tilak-tr10</a></p>
        <p>GitHub: <a href="https://github.com/Tilak-TR10" target="_blank">github.com/Tilak-TR10</a></p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Tilak Raval - All Rights Reserved</p>
    </footer>
</body>
</html>
