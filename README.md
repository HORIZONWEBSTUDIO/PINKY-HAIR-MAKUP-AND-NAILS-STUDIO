<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pinky's Hair, Make-up & Nails Studio</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:Montserrat,sans-serif;color:#222;background:#fff}
html{scroll-behavior:smooth}
header{position:fixed;top:0;width:100%;background:rgba(255,255,255,.92);backdrop-filter:blur(10px);z-index:99}
nav{max-width:1200px;margin:auto;padding:18px;display:flex;justify-content:space-between}
nav a{text-decoration:none;color:#222;margin-left:18px;font-weight:600}
.logo{font-family:'Playfair Display',serif;color:#c59a5f;font-size:1.4rem}
.hero{height:100vh;background:linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),url('https://images.unsplash.com/photo-1512496015851-a90fb38ba796?auto=format&fit=crop&w=1600&q=80') center/cover;display:flex;align-items:center;justify-content:center;text-align:center;color:#fff}
.hero h1{font-family:'Playfair Display',serif;font-size:4rem}
.hero p{max-width:700px;margin:20px auto}
.btn{display:inline-block;padding:14px 26px;border-radius:40px;text-decoration:none;margin:8px;font-weight:700}
.primary{background:#c59a5f;color:#fff}
.secondary{border:2px solid #fff;color:#fff}
section{padding:90px 20px}
.container{max-width:1200px;margin:auto}
.title{text-align:center;margin-bottom:40px}
.title h2{font-family:'Playfair Display',serif;font-size:2.5rem}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:25px}
.card{padding:28px;border-radius:22px;background:#fff;box-shadow:0 10px 30px rgba(0,0,0,.08);transition:.3s}
.card:hover{transform:translateY(-8px)}
.pink{background:#fff7f9}
.stats{background:linear-gradient(135deg,#f7d7e0,#c59a5f);color:#fff}
.stats .grid{text-align:center}
.statnum{font-size:3rem;font-weight:700}
.contact{background:#111;color:#fff}
.contact form{display:grid;gap:12px;max-width:700px;margin:auto}
input,textarea{padding:14px;border:none;border-radius:10px}
footer{text-align:center;padding:25px;background:#000;color:#aaa}
.whatsapp{position:fixed;right:20px;bottom:20px;background:#25D366;color:#fff;padding:14px 18px;border-radius:50px;text-decoration:none;font-weight:700}
@media(max-width:768px){.hero h1{font-size:2.4rem} nav div:last-child{display:none}}
</style>
</head>
<body>

<header>
<nav>
<div class="logo">Pinky's Hair, Make-up & Nails Studio</div>
<div>
<a href="#about">About</a>
<a href="#courses">Courses</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>
</div>
</nav>
</header>

<section class="hero">
<div>
<h1>Transform Your Beauty.<br>Build Your Future.</h1>
<p>Premium salon services, bridal makeovers, nail artistry and ISO-certified beauty training. Certified by Shahnaz Husain • Since 2011.</p>

<a href="#courses" class="btn secondary">Explore Courses</a>
</div>
</section>

<section id="about">
<div class="container">
<div class="title"><h2>Why Choose Us</h2></div>
<div class="grid">
<div class="card"><h3>Certified Excellence</h3><p>Certified by Shahnaz Husain with years of professional expertise.</p></div>
<div class="card"><h3>ISO Certified Courses</h3><p>National & international beauty training programs.</p></div>
<div class="card"><h3>Luxury Experience</h3><p>Modern techniques, premium products and personalized care.</p></div>
<div class="card"><h3>Since 2011</h3><p>Trusted by thousands of clients and students.</p></div>
</div>
</div>
</section>

<section id="courses" class="pink">
<div class="container">
<div class="title"><h2>Academy & Training</h2></div>
<div class="grid">
<div class="card"><h3>HD & Bridal Makeup</h3></div>
<div class="card"><h3>Hair Styling & Treatments</h3></div>
<div class="card"><h3>Skin Treatments</h3></div>
<div class="card"><h3>Nail Art Courses</h3></div>
<div class="card"><h3>Mehndi Design</h3></div>
</div>
</div>
</section>

<section id="services">
<div class="container">
<div class="title"><h2>Premium Services</h2></div>
<div class="grid">
<div class="card"><h3>Bridal HD Makeup</h3></div>
<div class="card"><h3>Celebrity & Party Makeup</h3></div>
<div class="card"><h3>Hair Care & Styling</h3></div>
<div class="card"><h3>Advanced Skin Care</h3></div>
<div class="card"><h3>Professional Nail Art</h3></div>
<div class="card"><h3>Destination Wedding Packages</h3></div>
</div>
</div>
</section>

<section class="stats">
<div class="container">
<div class="grid">
<div><div class="statnum">15+</div><p>Years Experience</p></div>
<div><div class="statnum">50000+</div><p>Happy Clients</p></div>
<div><div class="statnum">1000+</div><p>Students Trained</p></div>
<div><div class="statnum">100+</div><p>Bridal Projects</p></div>
</div>
</div>
</section>

<section>
<div class="container">
<div class="title"><h2>Specializations</h2></div>
<div class="grid">
<div class="card"><h3>Freelancing Services</h3><p>Salon experience at your location.</p></div>
<div class="card"><h3>Destination Weddings</h3><p>Travel-ready bridal beauty packages.</p></div>
<div class="card"><h3>Brand Collaborations</h3><p>Events, sponsorships and commercial partnerships.</p></div>
</div>
</div>
</section>

<section id="contact" class="contact">
<div class="container">
<div class="title"><h2>Contact Us</h2></div>

    <div style="text-align:center;padding:20px;">
      <a href="https://www.instagram.com/content_creator_make_up_artist/" target="_blank"
      style="display:inline-block;padding:16px 30px;background:#E1306C;color:white;text-decoration:none;border-radius:40px;font-weight:700;font-size:18px;">
      Contact Us on Instagram
      </a>
    </div>
    
<div style="text-align:center;margin-top:20px;">
<a href="https://www.instagram.com/content_creator_make_up_artist/" target="_blank"
style="display:inline-block;padding:14px 24px;background:#E1306C;color:white;text-decoration:none;border-radius:30px;font-weight:700;">
Follow Us on Instagram
</a>
</div>

</div>
</section>

<footer>
© 2026 Pinky's Hair, Make-up & Nails Studio. All Rights Reserved.
</footer>


</body>
</html>
