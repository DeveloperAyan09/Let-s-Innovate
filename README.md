# Let-s-Innovate
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #232f3e;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background-color: #131a22;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
            margin: 5px;
        }
        nav input[type="text"] {
            padding: 5px;
            border: none;
            border-radius: 3px;
        }
        main {
            padding: 20px;
        }
        .product {
            background: #ffffff;
            padding: 15px;
            margin: 10px;
            border: 1px solid #ddd;
            display: inline-block;
            width: calc(25% - 40px);
            vertical-align: top;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .product h3 {
            font-size: 1.2em;
            margin: 10px 0;
        }
        .product p {
            font-size: 0.9em;
            color: #555;
        }
        .product button {
            padding: 10px;
            background-color: #ff9900;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 3px;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #232f3e;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 768px) {
            .product {
                width: calc(50% - 40px);
            }
        }
        @media (max-width: 480px) {
            .product {
                width: calc(100% - 40px);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Amazon Clone</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Categories</a>
        <a href="#">Deals</a>
        <a href="#">Cart</a>
        <input type="text" placeholder=" 🔍 Search">
    </nav>
    <main>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product Image">
            <h3>Product 1</h3>
            <p>$99.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product Image">
            <h3>Product 2</h3>
            <p>$199.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product Image">
            <h3>Product 3</h3>
            <p>$299.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product Image">
            <h3>Product 4</h3>
            <p>$399.99</p>
            <button>Add to Cart</button>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Amazon Clone. All rights reserved.</p>
    </footer>
</body>
</html>
