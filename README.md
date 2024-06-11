<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanamgzavri - Georgian Ride-Sharing Platform</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Tanamgzavri</div>
            <ul>
                <li><a href="#how-it-works">How It Works</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h1>Welcome to Tanamgzavri</h1>
            <p>Connecting travelers for affordable and convenient carpooling across Georgia.</p>
            <button>Get Started</button>
        </section>

        <section id="how-it-works">
            <h2>How It Works</h2>
            <div class="steps">
                <div class="step">
                    <h3>1. Post a Trip</h3>
                    <p>Share your travel plans and find people going your way.</p>
                </div>
                <div class="step">
                    <h3>2. Find a Ride</h3>
                    <p>Search for available trips and book your seat.</p>
                </div>
                <div class="step">
                    <h3>3. Enjoy the Journey</h3>
                    <p>Travel with trusted companions and save on travel costs.</p>
                </div>
            </div>
        </section>

        <section id="features">
            <h2>Features</h2>
            <ul>
                <li>User-friendly interface</li>
                <li>Secure payment system</li>
                <li>Real-time trip updates</li>
                <li>Driver and passenger ratings</li>
            </ul>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Tanamgzavri is dedicated to making travel across Georgia more affordable and convenient by connecting drivers and passengers for shared trips. Whether you are commuting daily or planning a long-distance journey, Tanamgzavri is here to help you travel smarter and greener.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Tanamgzavri. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

header {
    background-color: #3a7d44;
    color: #fff;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo {
    font-size: 1.5em;
}

header ul {
    list-style: none;
    display: flex;
    gap: 15px;
}

header ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 20px;
}

#hero {
    text-align: center;
    padding: 50px;
    background-color: #ffffff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 30px;
}

#hero h1 {
    margin-bottom: 10px;
}

#hero p {
    margin-bottom: 20px;
}

#hero button {
    background-color: #3a7d44;
    color: #fff;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    font-size: 1em;
}

#how-it-works, #features, #about, #contact {
    background-color: #ffffff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 20px;
    margin-bottom: 30px;
}

.steps {
    display: flex;
    gap: 20px;
}

.steps .step {
    flex: 1;
    text-align: center;
}

form {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

form label {
    font-weight: bold;
}

form input, form textarea, form button {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background-color: #3a7d44;
    color: #fff;
    border: none;
    cursor: pointer;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #3a7d44;
    color: #fff;
}
