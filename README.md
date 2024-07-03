# First-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background: #575757;
        }
        .container {
            padding: 20px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Simple Website</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of the website.</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>This is the about section of the website. You can add some information about yourself or your website here.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>This is the contact section. You can provide contact details or a form here.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 My Simple Website. All rights reserved.</p>
    </footer>
</body>
</html>
