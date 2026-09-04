<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meadow & Rose | Romantic Vintage & Thrift Boutique</title>
    <!-- Google Fonts for the Romantic Aesthetic -->
    <link rel="preconnect" href="https://googleapis.com">
    <link rel="preconnect" href="https://gstatic.com" crossorigin>
    <link href="https://googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,600;1,400&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">
    
    <style>
        /* Color Palette & Base Styles */
        :root {
            --bg-cream: #fbf9f4;
            --rose-dust: #c8968e;
            --rose-dark: #a6726b;
            --meadow-sage: #8da192;
            --text-charcoal: #333333;
            --font-serif: 'Cormorant Garamond', serif;
            --font-sans: 'Montserrat', sans-serif;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--bg-cream);
            color: var(--text-charcoal);
            font-family: var(--font-sans);
            font-size: 14px;
            line-height: 1.6;
        }

        /* Announcement Bar */
        .announcement-bar {
            background-color: var(--meadow-sage);
            color: white;
            text-align: center;
            padding: 8px;
            font-size: 11px;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        /* Navigation Header */
        header {
            text-align: center;
            padding: 40px 20px;
        }

        header h1 {
            font-family: var(--font-serif);
            font-size: 42px;
            font-weight: 400;
            letter-spacing: 4px;
            color: var(--text-charcoal);
            text-transform: lowercase;
        }

        header p {
            font-family: var(--font-serif);
            font-style: italic;
            font-size: 16px;
            color: #777;
            margin-top: 5px;
        }

        nav {
            margin-top: 20px;
            border-top: 1px solid #eae1d4;
            border-bottom: 1px solid #eae1d4;
            padding: 15px 0;
        }

        nav a {
            color: var(--text-charcoal);
            text-decoration: none;
            margin: 0 20px;
            letter-spacing: 1px;
            text-transform: uppercase;
            font-size: 12px;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--rose-dust);
        }

        /* Hero / Story Banner */
        .hero-section {
            max-width: 800px;
            margin: 40px auto;
            text-align: center;
            padding: 0 20px;
        }

        .hero-section h2 {
            font-family: var(--font-serif);
            font-size: 28px;
            font-weight: 400;
            margin-bottom: 15px;
            color: var(--rose-dark);
        }

        .hero-section p {
            font-size: 15px;
            color: #555;
            max-width: 600px;
            margin: 0 auto;
        }

        /* Product Drop Grid */
        .shop-container {
            max-width: 1100px;
            margin: 60px auto;
            padding: 0 20px;
        }

        .section-title {
            font-family: var(--font-serif);
            font-size: 32px;
            font-weight: 400;
            text-align: center;
            margin-bottom: 40px;
            letter-spacing: 1px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 40px;
        }

        .product-card {
            background: white;
            border: 1px solid #eae1d4;
            padding: 15px;
            text-align: center;
            position: relative;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.03);
        }

        /* Placeholder images mimicking romantic thrift photos */
        .product-image {
            width: 100%;
            height: 380px;
            background-color: #f4efeb;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--rose-dark);
            font-family: var(--font-serif);
            font-style: italic;
            font-size: 18px;
            margin-bottom: 15px;
            border-bottom: 1px solid #fbf9f4;
        }

        .product-title {
            font-family: var(--font-serif);
            font-size: 20px;
            color: var(--text-charcoal);
            margin-bottom: 5px;
        }

        .product-meta {
            font-size: 12px;
            color: #777;
            margin-bottom: 10px;
            font-style: italic;
        }

        .buy-btn {
            display: inline-block;
            background-color: var(--rose-dust);
            color: white;
            padding: 10px 24px;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 11px;
            letter-spacing: 2px;
            margin-top: 10px;
            transition: background-color 0.3s;
            border: none;
            cursor: pointer;
            width: 100%;
        }

        .buy-btn:hover {
            background-color: var(--rose-dark);
        }

        .sold-out-badge {
            position: absolute;
            top: 25px;
            right: 25px;
            background-color: rgba(255, 255, 255, 0.9);
            color: #999;
            padding: 5px 12px;
            font-size: 10px;
            text-transform: uppercase;
            letter-spacing: 1px;
            border: 1px solid #ddd;
        }

        /* Footer */
        footer {
            background-color: #f3ede2;
            text-align: center;
            padding: 40px 20px;
            margin-top: 80px;
            font-size: 12px;
            color: #666;
            border-top: 1px solid #eae1d4;
        }

        footer p {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <!-- Announcement Bar -->
    <div class="announcement-bar">
        ✨ Next Curated Vintage Drop: Sunday at 7 PM EST ✨
    </div>

    <!-- Header Section -->
    <header>
        <h1>meadow & rose</h1>
        <p>carefully curated, romantic thrift & vintage wear</p>
        
        <nav>
            <a href="#shop">Shop the Drop</a>
            <a href="#about">Our Philosophy</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- About / Story Section -->
    <section class="hero-section" id="about">
        <h2>Whimsical pieces looking for a second story.</h2>
        <p>Welcome to Meadow & Rose. We spend hours hunting through vintage racks and hidden corners to bring you soft, romantic, one-of-a-kind garments. Every item is hand-selected, deeply loved, and meticulously measured to help you find your perfect fit.</p>
    </section>

    <!-- Shop Collection Section -->
    <section class="shop-container" id="shop">
        <h3 class="section-title">The Romantic Collection</h3>
        
        <div class="grid">
            <!-- Product Item 1 -->
            <div class="product-card">
                <div class="product-image">✦ 1990s Floral Blouse Photo ✦</div>
                <h4 class="product-title">Meadow Picnic Blouse</h4>
                <p class="product-meta">Size Small | Bust: 34"</p>
                <button class="buy-btn">View Details</button>
            </div>

            <!-- Product Item 2 -->
            <div class="product-card">
                <div class="product-image">✦ Satin Slip Dress Photo ✦</div>
                <h4 class="product-title">Dusty Rose Slip Dress</h4>
                <p class="product-meta">Size Medium | Waist: 28"</p>
                <button class="buy-btn">View Details</button>
            </div>

            <!-- Product Item 3 (Example of a Sold Out item) -->
            <div class="product-card">
                <span class="sold-out-badge">Sold Out</span>
                <div class="product-image" style="opacity: 0.6;">✦ Knit Cardigan Photo ✦</div>
                <h4 class="product-title" style="color: #999;">Cottagecore Knit Cardigan</h4>
                <p class="product-meta">Size Free | Chunky Cotton</p>
                <button class="buy-btn" style="background-color: #ddd; cursor: not-allowed;" disabled>Sold Out</button>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer id="contact">
        <p>© 2026 Meadow & Rose Vintage. All items are final sale due to their unique, thrifted nature.</p>
        <p>Follow our thrift journeys on Instagram: <strong>@MeadowAndRose</strong></p>
    </footer>

</body>
</html>
