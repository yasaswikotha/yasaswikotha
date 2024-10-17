<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Product Landing Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            line-height: 1.6;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2rem;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x600') no-repeat center center/cover;
            height: 600px;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
        }
        .hero h2 {
            font-size: 4rem;
        }
        .hero p {
            font-size: 1.5rem;
            margin: 20px 0;
        }
        .hero button {
            padding: 10px 20px;
            font-size: 1.2rem;
            color: #fff;
            background-color: #e63946;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .features {
            display: flex;
            justify-content: space-around;
            margin: 40px 0;
            padding: 20px;
        }
        .feature {
            text-align: center;
            padding: 20px;
        }
        .feature h3 {
            margin-bottom: 10px;
        }
        .pricing {
            background: #f4f4f4;
            padding: 40px 0;
            text-align: center;
        }
        .pricing h2 {
            margin-bottom: 30px;
        }
        .pricing .price {
            display: inline-block;
            background-color: #e63946;
            color: white;
            padding: 20px;
            border-radius: 10px;
            font-size: 2rem;
        }
        .testimonials {
            padding: 40px 0;
            text-align: center;
        }
        .testimonial {
            margin-bottom: 20px;
        }
        .testimonial p {
            font-style: italic;
        }
        .cta {
            background: #333;
            color: white;
            padding: 40px;
            text-align: center;
        }
        .cta button {
            padding: 15px 30px;
            font-size: 1.5rem;
            background-color: #e63946;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        footer {
            background: #222;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Awesome Product</h1>
        <nav>
            <ul>
                <li><a href="#features">Features</a></li>
                <li><a href="#pricing">Pricing</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#cta">Get Started</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div>
            <h2>Welcome to Awesome Product</h2>
            <p>Transform the way you do business with our solution.</p>
            <button>Learn More</button>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="features">
        <div class="feature">
            <h3>Feature 1</h3>
            <p>Explanation of the first feature of the product.</p>
        </div>
        <div class="feature">
            <h3>Feature 2</h3>
            <p>Explanation of the second feature of the product.</p>
        </div>
        <div class="feature">
            <h3>Feature 3</h3>
            <p>Explanation of the third feature of the product.</p>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="pricing">
        <h2>Pricing</h2>
        <div class="price">$29.99 / month</div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="testimonials">
        <h2>What Our Customers Say</h2>
        <div class="testimonial">
            <p>"This product changed my life! It's incredible!"</p>
            <p>- Happy Customer</p>
        </div>
        <div class="testimonial">
            <p>"Unbelievable results. Worth every penny."</p>
            <p>- Satisfied Client</p>
        </div>
    </section>

    <!-- Call-to-Action Section -->
    <section id="cta" class="cta">
        <h2>Ready to Get Started?</h2>
        <button>Join Now</button>
    </section>

    <!-- Footer -->
    <footer>
        <p>Copyright &copy; 2024 Awesome Product. All Rights Reserved.</p>
    </footer>

</body>
</html>

