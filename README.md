<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Darby Host</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f5f5f5;
color:#333;
}

header{
background:#6D28D9;
color:white;
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
}

header h2{
font-size:28px;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
font-weight:bold;
}

.hero{
background:linear-gradient(135deg,#6D28D9,#4C1D95);
color:white;
text-align:center;
padding:100px 20px;
}

.hero h1{
font-size:48px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
max-width:700px;
margin:auto;
line-height:1.6;
}

.button{
display:inline-block;
margin-top:30px;
padding:15px 35px;
background:white;
color:#6D28D9;
text-decoration:none;
font-weight:bold;
border-radius:8px;
}

.section{
padding:70px 8%;
}

.section h2{
text-align:center;
margin-bottom:40px;
font-size:34px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
text-align:center;
}

.price{
font-size:32px;
font-weight:bold;
margin:20px 0;
color:#6D28D9;
}

footer{
background:#111827;
color:white;
text-align:center;
padding:30px;
margin-top:60px;
}
</style>

</head>

<body>

<header>

<h2>Darby Host</h2>

<nav>
<a href="#">Home</a>
<a href="#">Hosting</a>
<a href="#">Domains</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>

</header>

<section class="hero">

<h1>Fast, Secure & Reliable Web Hosting</h1>

<p>
Power your website with reliable hosting solutions designed for businesses, creators and beginners.
</p>

<a href="#" class="button">Get Started</a>

</section>

<section class="section">

<h2>Our Hosting Plans</h2>

<div class="cards">

<div class="card">
<h3>Starter</h3>
<div class="price">₦2,500/mo</div>
<p>1 Website</p>
<p>Free SSL</p>
<p>10GB SSD Storage</p>
</div>

<div class="card">
<h3>Business</h3>
<div class="price">₦6,000/mo</div>
<p>50 Websites</p>
<p>Free Domain</p>
<p>Daily Backup</p>
</div>

<div class="card">
<h3>Premium</h3>
<div class="price">₦12,000/mo</div>
<p>Unlimited Websites</p>
<p>Priority Support</p>
<p>Advanced Security</p>
</div>

</div>

</section>

<section class="section">

<h2>Why Choose Darby Host?</h2>

<div class="cards">

<div class="card">
<h3>⚡ Fast Servers</h3>
<p>Optimized hosting for speed and reliability.</p>
</div>

<div class="card">
<h3>🔒 Secure</h3>
<p>Free SSL and advanced security protection.</p>
</div>

<div class="card">
<h3>💬 Support</h3>
<p>Friendly customer support whenever you need help.</p>
</div>

</div>

</section>

<footer>

<h2>Darby Host</h2>

<p>Powering Your Online Success</p>

<p>© 2026 Darby Host. All rights reserved.</p>

</footer>

</body>
</html>