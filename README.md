<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>ZeeBagz - Premium West Coast Cannabis</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="navbar">
            <h1>ZeeBagz</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Products</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="welcome-message" id="welcomeMessage">
            <h2>Welcome to ZeeBagz!</h2>
            <p>You've found the best quality cannabis from the West Coast. Enjoy our premium products with top-notch quality and service.</p>
            <button onclick="showMessage()">Start Exploring</button>
        </div>
    </section>

    <section class="guarantee">
        <h2>Our Guarantee</h2>
        <p>We pride ourselves on providing the finest cannabis straight from the West Coast. Quality is our top priority!</p>
    </section>

    <footer>
        <p>&copy; 2024 ZeeBagz - Premium Cannabis from the West Coast</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
}

header {
    background-color: #4CAF50;
    padding: 1rem 0;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 2rem;
}

.navbar h1 {
    color: white;
    font-size: 2rem;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.hero {
    background-image: url('https://via.placeholder.com/1920x600'); /* You can replace with an actual image */
    background-size: cover;
    background-position: center;
    color: white;
    text-align: center;
    padding: 5rem 2rem;
}

.welcome-message h2 {
    font-size: 3rem;
}

.welcome-message p {
    font-size: 1.25rem;
    margin: 20px 0;
}

button {
    padding: 10px 20px;
    background-color: #FFD700;
    border: none;
    cursor: pointer;
    font-size: 1rem;
}

button:hover {
    background-color: #FFA500;
}

.guarantee {
    text-align: center;
    padding: 2rem;
    background-color: #f4f4f4;
}

footer {
    text-align: center;
    padding: 1rem;
    background-color: #333;
    color: white;
}

footer p {
    font-size: 1rem;
}
// Function to show a welcome message to new users
function showMessage() {
    const welcomeMessage = document.getElementById('welcomeMessage');
    welcomeMessage.innerHTML = "<h2>Thank you for visiting ZeeBagz!</h2><p>We are excited to provide you with the best cannabis from the West Coast. Explore our collection and enjoy the premium experience!</p>";
}
