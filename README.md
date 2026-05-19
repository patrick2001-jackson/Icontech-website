<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ICONTECH</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#0f172a;
    color:white;
}

/* HEADER */

header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 10%;
    background:#020617;
}

.logo{
    font-size:30px;
    font-weight:bold;
    color:cyan;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    transition:0.3s;
}

nav a:hover{
    color:cyan;
}

/* HERO SECTION */

.hero{
    height:90vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    flex-direction:column;
    background:linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.7)),
    url('https://images.unsplash.com/photo-1516321318423-f06f85e504b3');
    background-size:cover;
    background-position:center;
}

.hero h1{
    font-size:60px;
    color:cyan;
}

.hero p{
    margin-top:20px;
    font-size:20px;
    width:70%;
}

.hero button{
    margin-top:30px;
    padding:15px 35px;
    border:none;
    background:cyan;
    font-size:18px;
    cursor:pointer;
    border-radius:8px;
    transition:0.3s;
}

.hero button:hover{
    background:white;
}

/* SERVICES */

.services{
    padding:80px 10%;
    text-align:center;
}

.services h2{
    font-size:40px;
    margin-bottom:50px;
    color:cyan;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1e293b;
    padding:30px;
    border-radius:15px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-10px);
    background:#334155;
}

.card h3{
    margin-bottom:15px;
    color:cyan;
}

/* CONTACT */

.contact{
    padding:80px 10%;
    text-align:center;
    background:#020617;
}

.contact h2{
    color:cyan;
    margin-bottom:20px;
}

.contact p{
    margin:10px 0;
    font-size:18px;
}

/* FOOTER */

footer{
    text-align:center;
    padding:20px;
    background:#000;
    color:#aaa;
}

</style>
</head>

<body>

<!-- HEADER -->

<header>

<div class="logo">ICONTECH</div>

<nav>
<a href="#">Home</a>
<a href="#">Services</a>
<a href="#">Portfolio</a>
<a href="#">Contact</a>
</nav>

</header>

<!-- HERO -->

<section class="hero">

<h1>WELCOME TO ICONTECH</h1>

<p>
INNOVATE • DEVELOP • ELEVATE
</p>

<button>Get Started</button>

</section>

<!-- SERVICES -->

<section class="services">

<h2>OUR SERVICES</h2>

<div class="cards">

<div class="card">
<h3>Graphic Design</h3>
<p>Creative posters, branding and business advertisements.</p>
</div>

<div class="card">
<h3>Website Development</h3>
<p>Modern and responsive websites for businesses.</p>
</div>

<div class="card">
<h3>Digital Marketing</h3>
<p>Promoting brands through social media and online platforms.</p>
</div>

<div class="card">
<h3>Printing Services</h3>
<p>High quality printing for banners, cards and posters.</p>
</div>

</div>

</section>

<!-- CONTACT -->

<section class="contact">

<h2>CONTACT US</h2>

<p>📞 +255 710 104 208</p>
<p>📞 +255 620 104 208</p>

<p>📧 icontech@gmail.com</p>
<p>📧 info@icontech.go.tz</p>

<p>
WhatsApp | Facebook | Instagram | X
</p>

</section>

<!-- FOOTER -->

<footer>

© 2026 ICONTECH | All Rights Reserved

</footer>

</body>
</html>
