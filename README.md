# Ex02 Commercial Website
## Date:27.02.2026
# Name:INFANCIA FELCY.P
# REG NO:212223040067

## AIM:
To create a commercial website using CSS Flexbox.

## ALGORITHM:
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
# index.htlm
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Experiment-2</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<!-- HEADER -->
<header>
    <div class="logo">Herbal Glow🌿</div>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
        <a href="#account">Account</a>
    </nav>
</header>

<!-- HERO SECTION -->
<section id="home" class="hero">
    <div class="hero-text">
        <h1>Natural Wellness, Pure Beauty</h1>
        <p>Discover premium herbal products for healthy living.</p>
        <button>Shop Now</button>
    </div>
</section>

<!-- PRODUCTS -->
<section id="products" class="products">
    <h2>Our Herbal Collection</h2>
    <div class="product-container">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1505576399279-565b52d4ac71" alt="">
            <h3>Herbal Tea</h3>
            <p>Relaxing and detoxifying blends.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1596755389378-c31d21fd1273" alt="">
            <h3>Essential Oils</h3>
            <p>Pure natural aroma for wellness.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1556228720-195a672e8a03" alt="">
            <h3>Organic Skincare</h3>
            <p>Glow naturally with herbal care.</p>
        </div>

    </div>
</section>

<!-- ABOUT -->
<section id="about" class="about">
    <h2>About Us</h2>
    <p>
        Herbal Glow brings nature closer to you with premium, eco-friendly,
        and sustainable herbal products crafted with love.
    </p>
</section>

<!-- CONTACT -->
<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: support@herbalglow.com</p>
    <p>Phone: +91 81222 XXXXX</p>
</section>

<!-- ACCOUNT -->
<section id="account" class="account">
    <h2>User Account</h2>
    <button>Login</button>
    <button>Sign Up</button>
</section>

<!-- FOOTER -->
<footer>
    <p>Follow us:
        Instagram | Facebook | Twitter
    </p>
    <p>© 2026 Herbal Glow. All rights reserved.</p>
</footer>

</body>
</html>
```
style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background: #f8fdf8;
    color: #333;
}

/* HEADER */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #1b5e20;
    padding: 20px 50px;
}

.logo {
    color: white;
    font-size: 24px;
    font-weight: bold;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    transition: 0.3s;
}

nav a:hover {
    color: #c8e6c9;
}

/* HERO */
.hero {
    height: 90vh;
    background: url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6') center/cover;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero-text {
    background: rgba(0,0,0,0.5);
    padding: 40px;
    border-radius: 15px;
    color: white;
}

.hero button {
    margin-top: 15px;
    padding: 12px 25px;
    border: none;
    background: #66bb6a;
    color: white;
    cursor: pointer;
    transition: 0.3s;
}

.hero button:hover {
    background: #388e3c;
}

/* PRODUCTS */
.products {
    padding: 60px 30px;
    text-align: center;
}

.product-container {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
    margin-top: 30px;
}

.card {
    background: white;
    width: 280px;
    border-radius: 12px;
    box-shadow: 0 6px 15px rgba(0,0,0,0.15);
    overflow: hidden;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-8px);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card h3 {
    margin: 15px 0 10px;
}

/* SECTIONS */
.about, .contact, .account {
    padding: 50px;
    text-align: center;
}

.account button {
    margin: 10px;
    padding: 10px 20px;
    border: none;
    background: #2e7d32;
    color: white;
    border-radius: 6px;
    cursor: pointer;
}

/* FOOTER */
footer {
    background: #1b5e20;
    color: white;
    text-align: center;
    padding: 20px;
}
```

## OUTPUT
<img width="1888" height="782" alt="image" src="https://github.com/user-attachments/assets/1c698fad-f8fd-4467-b240-8a3a9f487483" />

<img width="1887" height="916" alt="image" src="https://github.com/user-attachments/assets/51ef7dcf-b7e3-406a-8b29-72cb4994f3ff" />

<img width="1872" height="901" alt="image" src="https://github.com/user-attachments/assets/5d543734-34db-4e29-be07-e07ededd5416" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
