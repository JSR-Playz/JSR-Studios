<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JSR Studios</title>
    <style>
        /* General reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #121212;
            color: white;
            line-height: 1.6;
        }

        /* Global styles */
        a {
            text-decoration: none;
            color: #00E676;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #00B248;
        }

        h1, h2, h3 {
            font-weight: bold;
        }

        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }

        /* Hero Section */
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: url('https://example.com/futuristic-bg.jpg') no-repeat center center/cover; /* Add your background */
            text-align: center;
            position: relative;
            color: white;
            background-color: #1C1C1C;
        }

        .hero-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.7);
        }

        .hero-content {
            z-index: 1;
            position: relative;
        }

        .hero h1 {
            font-size: 4em;
            letter-spacing: 2px;
            animation: fadeInDown 1s ease-in-out;
        }

        .hero p {
            font-size: 1.5em;
            margin: 20px 0;
            animation: fadeInUp 1.5s ease-in-out;
        }

        .hero button {
            padding: 15px 40px;
            font-size: 1.2em;
            background-color: #00E676;
            border: none;
            color: #121212;
            border-radius: 50px;
            cursor: pointer;
            transition: background-color 0.3s ease;
            animation: fadeInUp 2s ease-in-out;
        }

        .hero button:hover {
            background-color: #00B248;
        }

        /* Stats Section */
        .stats {
            display: flex;
            justify-content: space-around;
            text-align: center;
            padding: 60px 0;
            background-color: #1A1A1A;
        }

        .stats div {
            margin: 0 20px;
        }

        .stats h2 {
            font-size: 3.5em;
            color: #00E676;
            font-weight: bold;
        }

        .stats p {
            font-size: 1.2em;
            color: #E0E0E0;
        }

        /* Section Styling */
        .section {
            text-align: center;
            padding: 50px 20px;
        }

        .section h2 {
            font-size: 2.5em;
            color: #00E676;
            margin-bottom: 20px;
            letter-spacing: 1.5px;
        }

        .section p {
            font-size: 1.2em;
            max-width: 800px;
            margin: 0 auto;
            color: #CCCCCC;
        }

        .section ul {
            list-style: none;
            padding: 0;
            margin: 30px 0;
        }

        .section ul li {
            margin: 15px 0;
            font-size: 1.2em;
            padding: 15px;
            background-color: #1C1C1C;
            border-radius: 10px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .section ul li:hover {
            transform: translateY(-5px);
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.5);
        }

        /* Footer */
        .footer {
            background-color: #1A1A1A;
            padding: 30px;
            text-align: center;
            color: #00E676;
        }

        /* Animations */
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .stats {
                flex-direction: column;
                padding: 30px 0;
            }

            .hero h1 {
                font-size: 3em;
            }

            .hero p {
                font-size: 1.2em;
            }

            .hero button {
                font-size: 1em;
                padding: 12px 30px;
            }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <h1>Welcome to JSR Studios</h1>
            <p>Where Creativity Begins and Fun Never Ends!</p>
            <button>Explore Now</button>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="stats">
        <div>
            <h2>600+</h2>
            <p>Subscribers</p>
        </div>
        <div>
            <h2>3</h2>
            <p>Active Projects</p>
        </div>
        <div>
            <h2>100%</h2>
            <p>Creativity Guaranteed</p>
        </div>
    </section>

    <!-- Goals Section -->
    <section class="section">
        <h2>Our Goals</h2>
        <p>JSR Studio is working towards:</p>
        <ul>
            <li>Starting the Blitz Battles Project</li>
            <li>Reaching 600 Subscribers by October!</li>
            <li>Launching the CB Battles Winter Update</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section class="section">
        <h2>Our Projects</h2>
        <p>Current and upcoming projects include:</p>
        <ul>
            <li>Blitz Battles</li>
            <li>CB Battles Winter Update</li>
        </ul>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>© 2024 JSR Studios. All rights reserved.</p>
    </footer>

</body>
</html>
