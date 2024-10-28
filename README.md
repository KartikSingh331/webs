<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CAFE_4_U</title>
    <link rel="icon" href=
    "https://img.freepik.com/free-photo/delicious-coffee-beans-cup_23-2150691429.jpg?t=st=1728827935~exp=1728831535~hmac=7e4adc3b779386902d5012d8098f8db0f9724334b079a6d82fbec85d3b190098&w=360"
            type="image/x-icon" />
 <style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f3f1e7;
    color: #333;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #8c5a39;
    color: white;
}
.logo{
    height: 30px;
    width: 30px;
    display: flex;
    flex-direction: row;

}


header .logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

.hero {
    height: 400px;
    background-image: url('https://static.vecteezy.com/system/resources/thumbnails/030/163/508/small_2x/the-best-coffee-shops-in-the-world-ai-generated-photo.jpg');
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
}

.hero-content {
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    padding: 50px;
    text-align: center;
    border-radius: 10px;
}

.menu {
    padding: 50px;
    text-align: center;
}

.menu-items {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.menu-item {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

.menu-item:hover {
    transform: scale(1.05);
}

.menu-item img {
    width: 100%;
    border-radius: 10px;
}

.reviews {
    padding: 50px;
    background-color: #f0ebe0;
    text-align: center;
}

.review-carousel {
    display: flex;
    overflow: hidden;
    animation: slide 10s infinite;
}

.review-card {
    min-width: 100%;
    padding: 20px;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin: 0 10px;
}

@keyframes slide {
    0% {transform: translateX(0);}
    50% {transform: translateX(-100%);}
    100% {transform: translateX(0);}
}

footer {
    background-color: #8c5a39;
    color: white;
    text-align: center;
    padding: 20px;
}
 </style>
</head>

<body>
    <!-- Header -->
    <header>
        <div class="logo">
        <img src="https://img.freepik.com/free-photo/delicious-coffee-beans-cup_23-2150691429.jpg?t=st=1728827935~exp=1728831535~hmac=7e4adc3b779386902d5012d8098f8db0f9724334b079a6d82fbec85d3b190098&w=360">
            <h>CAFE_4_U</h></div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>WELCOME IN CAFE_4_U</h1>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="menu">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="https://c.ndtvimg.com/2022-01/vd7hic64_coffee-unsplash_625x300_21_January_22.jpg?im=FaceCrop,algorithm=dnn,width=1200,height=675" alt="Espresso">
                <h3>Espresso</h3>
                <p>₹252.18 ($3.00)</p>
                <p>A shot of pure coffee goodness.</p>
            </div>
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR1BQ1p6PE8TzT3Ry4RvlJK_y6sZNJldufR1A&s" alt="Cappuccino">
                <h3>Cappuccino</h3>
                <p>₹673.10 ($8.00)</p>
                <p>A delightful blend of coffee and milk foam.</p>
            </div>
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS8EWg5M7VsLlnYDiEx9oNxZ_FCKsWoZgjOU36KmbHQwcMl5BWjuZSQXj9LOxc1KTGOZ74&usqp=CAU" alt="Flat white">
                <h3>Flat white</h3>
                <p>₹336.55($4.00)</p>
                <p>The smooth,velvety microfoam that gives the coffee a flat appearance.</p>
            </div>
            <div class="menu-item">
                <img src="https://im.indiatimes.in/content/2024/Mar/south-indian-filter-coffee-served-in-a-traditional-brass-or-stainless-steel-cup-free-photo-1_65ea824a9f0cf.jpg?w=640&h=427&cc=1&webp=1&q=75" alt="Cortado">
                <h3>Cortado</h3>
                <p>₹294.48($3.5.00)</p>
                <p>Roasted Beans with delicious taste.</p>
            </div>
            
        </div>
    </section>

    <!-- Customer Reviews Section -->
    <section class="reviews">
        <h2>Customer Reviews</h2>
        <div class="review-carousel">
            <div class="review-card">
                <p>"Amazing coffee! Will come back for sure!"</p>
                <p>- Ankit pandit</p>
                <p>★★★★★</p>
            </div>
            <div class="review-card">
                <p>"A best place to relax and enjoy "</p>
                <p>- Sahil singh</p>
                <p>★★★★★</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact">
        <div class="footer-content">
            <p>Opening Hours: Mon-Sat 8:30 AM - 9:00 PM</p>
            <p>Address: Sitapur road near Sewa Hospital 226201</p>
            <p>Contact: (+91) 9794604437</p>
        </div>
    </footer>
</body>
</html>
