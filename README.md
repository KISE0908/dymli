<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>dymli</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">dymli</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <h1>Welcome to dymli</h1>
            <p>Your one-stop shop for stylish and comfortable shoes.</p>
        </section>

        <section id="products">
            <h2>Our Products</h2>
            <div class="product-grid">
                <div class="product-card">
                    <img src="shoe/download.jpg" alt="Shoe 1">
                    <h3>Sporty Sneakers</h3>
                    <p>$59.99</p>
                    <button>Add to Cart</button>
                </div>
                <div class="product-card">
                    <img src="shoe/loafers.jpg" alt="Shoe 2">
                    <h3>Classic Loafers</h3>
                    <p>$79.99</p>
                    <button>Add to Cart</button>
                </div>
                <div class="product-card">
                    <img src="heels" alt="Shoe 3">
                    <h3>Elegant Heels</h3>
                    <p>$89.99</p>
                    <button>Add to Cart</button>
                </div>
                <div class="product-card">
                    <img src="shoe/sandals.jpg" alt="Shoe 4">
                    <h3>Casual Sandals</h3>
                    <p>$39.99</p>
                    <button>Add to Cart</button>
                </div>
            </div>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>At dymli, we believe in quality and style. Our shoes are crafted with care to ensure comfort and durability.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:Uche Olowu</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:olowuuche1@gmail.com</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:08137879565</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 dymli. All rights reserved.</p>
    </footer>
</body>
</html>
