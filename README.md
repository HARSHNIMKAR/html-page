# html-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>The Fabric House</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f4f4f4;
        }

        /* Header */
        header {
            background-color: #1e272e;
            color: white;
            text-align: center;
            padding: 25px;
        }

        header h1 {
            margin: 0;
            font-size: 40px;
        }

        header p {
            margin: 5px 0 0;
            font-size: 18px;
        }

        /* Navigation */
        nav {
            background-color: #485460;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffd32a;
        }

        /* Banner */
        .banner {
            background-color: #808e9b;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        .banner h2 {
            font-size: 32px;
        }

        .banner button {
            margin-top: 15px;
            padding: 12px 25px;
            font-size: 16px;
            border: none;
            background-color: #ffd32a;
            cursor: pointer;
        }

        /* Products */
        .products {
            padding: 40px;
            text-align: center;
        }

        .product-box {
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
        }

        .product {
            background-color: white;
            width: 250px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .product h3 {
            color: #1e272e;
        }

        /* Footer */
        footer {
            background-color: #1e272e;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>The Fabric House</h1>
        <p>Quality Fabrics • Timeless Style</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#">Home</a>
        <a href="#">Fabrics</a>
        <a href="#">Men</a>
        <a href="#">Women</a>
        <a href="#">Contact</a>
    </nav>

    <!-- Banner -->
    <section class="banner">
        <h2>Premium Fabrics for Every Occasion</h2>
        <p>Silk • Cotton • Linen • Designer Wear</p>
        <button>Explore Collection</button>
    </section>

    <!-- Products Section -->
    <section class="products">
        <h2>Our Collections</h2>
        <div class="product-box">
            <div class="product">
                <h3>Cotton Fabrics</h3>
                <p>Soft, breathable & comfortable</p>
            </div>

            <div class="product">
                <h3>Silk Fabrics</h3>
                <p>Elegant & premium quality</p>
            </div>

            <div class="product">
                <h3>Designer Wear</h3>
                <p>Latest fashion trends</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 The Fabric House | All Rights Reserved</p>
    </footer>

</body>
</html>
