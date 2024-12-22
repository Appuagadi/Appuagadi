<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-commerce Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>ShopEasy</h1>
        <nav>
            <ul>
                <li><a href="#electronics">Electronics</a></li>
                <li><a href="#appliances">Appliances</a></li>
                <li><a href="#fashion">Fashion</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="electronics">
            <h2>Electronics</h2>
            <div class="product">
                <img src="phone.jpg" alt="Phone">
                <p>Smartphone - $699</p>
            </div>
            <div class="product">
                <img src="laptop.jpg" alt="Laptop">
                <p>Laptop - $999</p>
            </div>
        </section>
        <section id="appliances">
            <h2>Home Appliances</h2>
            <div class="product">
                <img src="fridge.jpg" alt="Fridge">
                <p>Refrigerator - $799</p>
            </div>
            <div class="product">
                <img src="microwave.jpg" alt="Microwave">
                <p>Microwave - $199</p>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 ShopEasy. All rights reserved.</p>
    </footer>
</body>
</html>

CSS Code:

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 0;
    margin: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

.product {
    display: inline-block;
    margin: 15px;
    text-align: center;
}

.product img {
    width: 150px;
    height: auto;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}


<!---
Appuagadi/Appuagadi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
