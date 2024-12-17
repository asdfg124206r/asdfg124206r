- 👋 Hi, I’m @asdfg124206r
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
asdfg124206r/asdfg124206r is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marketing Website</title>
    <link rel="stylesheet" href="styles.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        /* General Styles */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        h1, h2, h3, p {
            margin: 0;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        /* Header */
        header {
            background-color: #1e90ff;
            color: #fff;
            padding: 20px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header .logo {
            font-size: 24px;
            font-weight: 600;
        }
        header nav a {
            margin-left: 20px;
            font-weight: 600;
        }
        /* Hero Section */
        .hero {
            background-color: #f4f4f4;
            text-align: center;
            padding: 100px 10%;
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 18px;
            color: #555;
            margin-bottom: 20px;
        }
        .hero button {
            background-color: #1e90ff;
            color: #fff;
            border: none;
            padding: 12px 24px;
            font-size: 18px;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .hero button:hover {
            background-color: #0073e6;
        }
        /* Features Section */
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 50px 10%;
            background-color: #fff;
        }
        .feature {
            text-align: center;
            max-width: 300px;
            margin: 20px;
        }
        .feature h3 {
            font-size: 24px;
            margin: 10px 0;
        }
        .feature p {
            color: #555;
        }
        /* Footer */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 10%;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">YourBrand</div>
        <nav>
            <a href="#features">Features</a>
            <a href="#contact">Contact</a>
            <a href="#about">About</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Grow Your Business with Us</h1>
        <p>Your success starts here. Let us help you achieve your marketing goals.</p>
        <button>Get Started</button>
    </section>

    <!-- Features Section -->
    <section id="features" class="features">
        <div class="feature">
            <h3>Custom Strategy</h3>
            <p>We build tailored marketing strategies to meet your business goals.</p>
        </div>
        <div class="feature">
            <h3>SEO Optimization</h3>
            <p>Rank higher on search engines and drive more traffic to your site.</p>
        </div>
        <div class="feature">
            <h3>Social Media</h3>
            <p>Engage and grow your audience on social media platforms.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 YourBrand | All rights reserved.</p>
    </footer>
</body>
</html>
