# Assignment_2
<!--page number 1-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VirtuArt Auctions</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f8f8;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 50px;
            background: white;
            border-bottom: 1px solid #ccc;
            flex-wrap: wrap;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
            padding: 0;
            margin: 0;
            flex-wrap: wrap;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
        .login-btn {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .search-bar {
            margin: 20px 0;
            display: flex;
            justify-content: center;
        }
        .search-bar input {
            padding: 10px;
            width: 80%;
            max-width: 300px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        h1 {
            margin-top: 10px;
            font-size: 32px;
            font-weight: bold;
        }
        .banner {
            position: relative;
            width: 90%;
            max-width: 1000px;
            margin: 20px auto;
            overflow: hidden;
        }
        .banner img {
            width: 100%;
            display: block;
            border-radius: 5px;
        }
        .banner-text {
            position: absolute;
            bottom: 10%;
            left: 5%;
            background: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 20px;
            border-radius: 5px;
            text-align: left;
            max-width: 90%;
        }
        .banner-text h3 {
            margin: 0;
            font-size: 14px;
            color: #ddd;
            text-transform: uppercase;
        }
        .banner-text h2 {
            margin: 5px 0;
            font-size: 24px;
        }
        .banner-text p {
            margin: 0;
            font-size: 14px;
        }
        .banner-text button {
            background: gold;
            border: none;
            padding: 10px;
            margin-top: 10px;
            cursor: pointer;
            border-radius: 5px;
            font-weight: bold;
        }
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                align-items: center;
                text-align: center;
            }
            nav ul {
                flex-direction: column;
                text-align: center;
            }
            .banner-text {
                bottom: 5%;
                left: 5%;
                max-width: 80%;
            }
            .banner-text h2 {
                font-size: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">VIRTUART</div>
        <nav>
            <ul>
                <li><a href="#">Auctions+</a></li>
                <li><a href="#">BUY</a></li>
                <li><a href="#">SELL</a></li>
                <li><a href="#">DEPARTMENTS</a></li>
                <li><a href="#">SERVICES+</a></li>
                <li><a href="#">REACH US</a></li>
            </ul>
        </nav>
        <button class="login-btn">Login/Register</button>
    </header>
    
    <section class="search-bar">
        <input type="text" placeholder="Search">
    </section>

    <h1>Auctions On The Way</h1>
    
    <section class="banner">
        <img src="chandelier.jpg" alt="Auction Item">
        <div class="banner-text">
            <h3>ANTIQUE & SILVER</h3>
            <h2>Imperial Treasures</h2>
            <p>Feb 25 - 27, 2025</p>
            <button>VIEW CATALOGUE</button>
        </div>
    </section>
</body>
</html>

<!--page number 2-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VirtuArt Auctions</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f8f8;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 50px;
            background: white;
            border-bottom: 1px solid #ccc;
            flex-wrap: wrap;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
            padding: 0;
            margin: 0;
            flex-wrap: wrap;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
        .login-btn {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .search-bar {
            margin: 20px 0;
            display: flex;
            justify-content: center;
        }
        .search-bar input {
            padding: 10px;
            width: 80%;
            max-width: 300px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        h1 {
            margin-top: 10px;
            font-size: 32px;
            font-weight: bold;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            max-width: 1000px;
            margin: auto;
            text-align: left;
            padding: 20px;
        }
        .text-section {
            flex: 1 1 300px;
            padding: 20px;
        }
        .auction-items {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .auction-item {
            background: black;
            color: white;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
            max-width: 200px;
        }
        .auction-item img {
            width: 100%;
            border-radius: 5px;
        }
        .category-btn {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 20px;
            margin: 10px 0;
        }
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                align-items: center;
                text-align: center;
            }
            nav ul {
                flex-direction: column;
                text-align: center;
            }
            .content {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">VIRTUART</div>
        <nav>
            <ul>
                <li><a href="#">Auctions+</a></li>
                <li><a href="#">BUY</a></li>
                <li><a href="#">SELL</a></li>
                <li><a href="#">DEPARTMENTS</a></li>
                <li><a href="#">SERVICES+</a></li>
                <li><a href="#">REACH US</a></li>
            </ul>
        </nav>
        <button class="login-btn">Login/Register</button>
    </header>
    
    <section class="search-bar">
        <input type="text" placeholder="Search">
    </section>

    <h1>Auctions On The Way</h1>
    
    <section class="content">
        <div class="text-section">
            <p>Over the years, we have curated a wide range of online auctions in India, covering a diverse array of categories. Our portfolio boasts an impressive collection of Modern Indian Art from famous painters, exquisite vintage jewellery, fine silverware, rare timepieces, luxurious textiles, coveted celebrity memorabilia, rare books, numismatic treasures, philatelic gems, and even vintage cars. Take a look at the offerings in our upcoming online auctions.</p>
        </div>
        <div class="auction-items">
            <div class="auction-item">
                <img src="modern_masters.jpg" alt="Modern Masters">
                <p>Imperial Treasures <br> February 25 - 27, 2025</p>
            </div>
            <div class="auction-item">
                <img src="silver_lion.jpg" alt="Silver Lion">
                <p>Modern Masters - March 25 <br> Yet to be Announced</p>
            </div>
        </div>
    </section>
    <button class="category-btn">ARTS</button>
</body>
</html>


<!--page number 3-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VirtuArt Auctions</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f8f8;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 50px;
            background: white;
            border-bottom: 1px solid #ccc;
            flex-wrap: wrap;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
            padding: 0;
            margin: 0;
            flex-wrap: wrap;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
        .login-btn {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .search-bar {
            margin: 20px 0;
            display: flex;
            justify-content: center;
        }
        .search-bar input {
            padding: 10px;
            width: 80%;
            max-width: 300px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        h1 {
            margin-top: 10px;
            font-size: 32px;
            font-weight: bold;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            max-width: 1000px;
            margin: auto;
            text-align: left;
            padding: 20px;
        }
        .text-section {
            flex: 1 1 300px;
            padding: 20px;
        }
        .auction-items {
            display: flex;
            flex-wrap: nowrap;
            gap: 20px;
            overflow-x: auto;
            padding-bottom: 20px;
        }
        .auction-item {
            background: black;
            color: white;
            padding: 10px;
            border-radius: 10px;
            text-align: center;
            max-width: 200px;
            flex: 0 0 auto;
        }
        .auction-item img {
            width: 100%;
            border-radius: 10px;
        }
        .category-btn {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 20px;
            margin: 10px 0;
        }
        .carousel-controls {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 10px;
        }
        .carousel-btn {
            background: black;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 50%;
            cursor: pointer;
        }
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                align-items: center;
                text-align: center;
            }
            nav ul {
                flex-direction: column;
                text-align: center;
            }
            .content {
                flex-direction: column;
                align-items: center;
            }
            .auction-items {
                flex-wrap: wrap;
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">VIRTUART</div>
        <nav>
            <ul>
                <li><a href="#">Auctions+</a></li>
                <li><a href="#">BUY</a></li>
                <li><a href="#">SELL</a></li>
                <li><a href="#">DEPARTMENTS</a></li>
                <li><a href="#">SERVICES+</a></li>
                <li><a href="#">REACH US</a></li>
            </ul>
        </nav>
        <button class="login-btn">Login/Register</button>
    </header>
    
    <section class="search-bar">
        <input type="text" placeholder="Search">
    </section>

    <h1>Most Recent Auctions</h1>
    
    <button class="category-btn">ART</button>
    
    <section class="content">
        <div class="auction-items">
            <div class="auction-item">
                <img src="auction1.jpg" alt="Auction 1">
                <button class="category-btn">VIEW RESULT</button>
            </div>
            <div class="auction-item">
                <img src="auction2.jpg" alt="Auction 2">
                <button class="category-btn">VIEW RESULT</button>
            </div>
            <div class="auction-item">
                <img src="auction3.jpg" alt="Auction 3">
                <button class="category-btn">VIEW RESULT</button>
            </div>
            <div class="auction-item">
                <img src="auction4.jpg" alt="Auction 4">
                <button class="category-btn">VIEW RESULT</button>
            </div>
        </div>
    </section>
    
    <div class="carousel-controls">
        <button class="carousel-btn">◀</button>
        <button class="carousel-btn">▶</button>
    </div>
</body>
</html>


<!--page number 4-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Info Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100vh;
            justify-content: center;
        }
        .header {
            font-size: 48px;
            font-weight: bold;
            margin-bottom: 30px;
        }
        .button-container {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .button {
            background: black;
            color: white;
            padding: 15px 60px;
            border: none;
            border-radius: 30px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
        }
        .top-right {
            position: absolute;
            top: 20px;
            right: 20px;
        }
    </style>
</head>
<body>
    <div class="top-right">
        <button class="button">ART</button>
    </div>
    <div class="header">INFO</div>
    <div class="button-container">
        <button class="button">Login here</button>
        <button class="button">NAME</button>
        <button class="button">CONTACT</button>
        <button class="button">EMAIL</button>
    </div>
</body>
</html>


<!--page number 5-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hidden Gems</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100vh;
            justify-content: center;
        }
        .top-right {
            position: absolute;
            top: 20px;
            right: 20px;
        }
        .art-button {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 20px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
        }
        .header {
            font-size: 60px;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .image-container {
            width: 250px;
            height: 250px;
            border-radius: 20px;
            overflow: hidden;
        }
        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <div class="top-right">
        <button class="art-button">ART</button>
    </div>
    <div class="header">Hidden Gems</div>
    <div class="gallery">
        <div class="image-container" style="background-color: #d9c2a3;"><img src="image1.jpg" alt="Art 1"></div>
        <div class="image-container" style="background-color: #d1272c;"><img src="image2.jpg" alt="Art 2"></div>
        <div class="image-container" style="background-color: #b5bba5;"><img src="image3.jpg" alt="Art 3"></div>
    </div>
</body>
</html>


<!--page number 6-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curated Series</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100vh;
            justify-content: center;
        }
        .top-right {
            position: absolute;
            top: 20px;
            right: 20px;
        }
        .art-button {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 20px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
        }
        .header {
            font-size: 60px;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .filter-button {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 20px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            margin-bottom: 20px;
        }
        .gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .image-container {
            width: 250px;
            height: 300px;
            border-radius: 20px;
            overflow: hidden;
        }
        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .image-label {
            margin-top: 10px;
            font-size: 16px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="top-right">
        <button class="art-button">ART</button>
    </div>
    <div class="header">Curated Series</div>
    <button class="filter-button">BLACK AND WHITE</button>
    <div class="gallery">
        <div class="image-container" style="background-color: #f5f5f5;"><img src="zen.jpg" alt="Zen"><div class="image-label">ZEN</div></div>
        <div class="image-container" style="background-color: #d9d9d9;"><img src="lily.jpg" alt="Lily"><div class="image-label">LILY</div></div>
        <div class="image-container" style="background-color: #e0e0e0;"><img src="dundun.jpg" alt="Dundun"><div class="image-label">DUNDUN</div></div>
    </div>
</body>
</html>


<!--page number 7-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curated Series</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        .top-right {
            position: absolute;
            top: 20px;
            right: 20px;
        }
        .art-button {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 20px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
        }
        .container {
            background: #dcdcf7;
            padding: 40px;
            border-radius: 50px;
            text-align: center;
            width: 80%;
            max-width: 900px;
            position: relative;
        }
        .header-text {
            font-size: 36px;
            font-weight: bold;
            color: #333;
            margin-bottom: 20px;
        }
        .browse-button {
            background: black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 10px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            margin-top: 20px;
        }
        .image-container {
            position: absolute;
            width: 150px;
            height: 200px;
        }
        .left-image {
            left: -80px;
            top: 50%;
            transform: translateY(-50%);
        }
        .right-image {
            right: -80px;
            top: 50%;
            transform: translateY(-50%);
            opacity: 0.6;
        }
        .image-container img {
            width: 100%;
            height: 100%;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="top-right">
        <button class="art-button">ART</button>
    </div>
    <div class="container">
        <div class="image-container left-image">
            <img src="left-art.jpg" alt="Left Art">
        </div>
        <div class="header-text">Elevate your look with our outstanding collection</div>
        <button class="browse-button">Browse Art</button>
        <div class="image-container right-image">
            <img src="right-art.jpg" alt="Right Art">
        </div>
    </div>
</body>
</html>


<!--page number 8-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Virtuart Footer</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

    <!-- Header -->
    <header>
        <div class="menu-icon">☰</div>
        <div class="logo">VIRTUART</div>
        <button class="art-btn">ART</button>
    </header>

    <!-- Footer -->
    <footer>
        <div class="footer-container">
            
            <!-- Column 1: Know More -->
            <div class="footer-section">
                <h4>Know More</h4>
                <ul>
                    <li><a href="#">Buy</a></li>
                    <li><a href="#">Sell</a></li>
                    <li><a href="#">Request an Estimate</a></li>
                    <li><a href="#">Blog</a></li>
                </ul>
            </div>

            <!-- Column 2: Services -->
            <div class="footer-section">
                <h4>Services</h4>
                <ul>
                    <li><a href="#">Client Advisory</a></li>
                    <li><a href="#">Restoration</a></li>
                    <li><a href="#">Collection Services</a></li>
                    <li><a href="#">Museum Services</a></li>
                    <li><a href="#">Post sale services</a></li>
                    <li><a href="#">Private services</a></li>
                    <li><a href="#">Storage</a></li>
                </ul>
            </div>

            <!-- Column 3: About -->
            <div class="footer-section">
                <h4>About</h4>
                <ul>
                    <li><a href="#">Who we are</a></li>
                    <li><a href="#">Press</a></li>
                    <li><a href="#">Careers</a></li>
                </ul>
            </div>

            <!-- Column 4: Discover -->
            <div class="footer-section">
                <h4>Discover</h4>
                <ul>
                    <li><a href="#">Record Price Artwork</a></li>
                    <li><a href="#">FAQ's</a></li>
                </ul>
            </div>

        </div>

        <!-- Newsletter -->
        <div class="newsletter">
            <h4>SIGN UP AND SAVE</h4>
            <p>Sign up now and be the first to know about exclusive offers, art.</p>
            <div class="email-signup">
                <input type="email" placeholder="Enter your email">
                <button>📧</button>
            </div>
        </div>

        <!-- Social Media Icons -->
        <div class="social-icons">
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-y


