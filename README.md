<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Clothing Brand</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #333; color: white; padding: 1rem; text-align: center; }
        nav { margin-top: 1rem; }
        nav a { color: white; margin: 0 1rem; text-decoration: none; }
        .hero { background-image: url('https://via.placeholder.com/1200x400?text=Hero+Image'); background-size: cover; height: 400px; display: flex; align-items: center; justify-content: center; color: white; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
        .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; padding: 2rem; }
        .product { background: white; padding: 1rem; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
        .product img { width: 100%; height: 200px; object-fit: cover; }
        footer { background-color: #333; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
        @media (max-width: 600px) { .products { grid-template-columns: 1fr; } }
    </style>
</head>
<body>
    <header>
        <h1>Your Clothing Brand</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#shop">Shop</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    
    <section id="home" class="hero">
        <h2>Welcome to Our Collection</h2>
        <p>Discover stylish, high-quality clothing for every occasion.</p>
    </section>
    
    <section id="shop" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/250x200?text=T-Shirt" alt="T-Shirt">
            <h3>Casual T-Shirt</h3>
            <p>$25.00</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250x200?text=Jeans" alt="Jeans">
            <h3>Denim Jeans</h3>
            <p>$50.00</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250x200?text=Jacket" alt="Jacket">
            <h3>Leather Jacket</h3>
            <p>$100.00</p>
            <button>Add to Cart</button>
        </div>
        <!-- Add more products as needed -->
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>We create sustainable, trendy clothing with a focus on comfort and style.</p>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: info@yourbrand.com | Phone: (123) 456-7890</p>
    </section>
    
    <footer>
        <p>&copy; 2023 Your Clothing Brand. All rights reserved.</p>
    </footer>
</body>
</html>
