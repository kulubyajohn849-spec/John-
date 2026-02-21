
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kulubya King | Golden Empire</title>

<style>

/* RESET */
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Segoe UI', sans-serif;
}

/* GOLD BACKGROUND */
body{
    background: linear-gradient(135deg, #FFD700, #FFC000, #FFB000);
    min-height:100vh;
    color:#111;
}

/* NAVIGATION */
nav{
    position:fixed;
    width:100%;
    top:0;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    backdrop-filter: blur(10px);
    background: rgba(255,255,255,0.2);
    box-shadow:0 8px 32px rgba(0,0,0,0.1);
    z-index:1000;
}

nav h2{
    font-weight:700;
}

nav ul{
    list-style:none;
    display:flex;
    gap:25px;
}

nav ul li a{
    text-decoration:none;
    color:#111;
    font-weight:500;
    transition:0.3s;
}

nav ul li a:hover{
    color:white;
}

/* HERO SECTION */
.hero{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:0 10%;
}

.hero-content{
    background: rgba(255,255,255,0.25);
    padding:50px;
    border-radius:20px;
    backdrop-filter: blur(15px);
    box-shadow:0 8px 32px rgba(0,0,0,0.2);
    animation: fadeIn 2s ease;
}

.hero h1{
    font-size:48px;
    margin-bottom:20px;
}

.hero p{
    font-size:18px;
    margin-bottom:30px;
}

.btn{
    padding:12px 30px;
    border:none;
    border-radius:30px;
    background:black;
    color:gold;
    cursor:pointer;
    font-size:16px;
    transition:0.4s;
}

.btn:hover{
    transform:scale(1.1);
    background:#222;
}

/* SECTIONS */
section{
    padding:100px 10%;
}

.section-title{
    text-align:center;
    font-size:32px;
    margin-bottom:40px;
}

.cards{
    display:flex;
    gap:30px;
    flex-wrap:wrap;
    justify-content:center;
}

.card{
    background: rgba(255,255,255,0.25);
    backdrop-filter: blur(10px);
    padding:30px;
    width:300px;
    border-radius:20px;
    text-align:center;
    box-shadow:0 8px 32px rgba(0,0,0,0.15);
    transition:0.4s;
}

.card:hover{
    transform:translateY(-10px);
}

/* FOOTER */
footer{
    text-align:center;
    padding:30px;
    background: rgba(0,0,0,0.1);
}

/* ANIMATIONS */
@keyframes fadeIn{
    from{opacity:0; transform:translateY(20px);}
    to{opacity:1; transform:translateY(0);}
}

/* RESPONSIVE */
@media(max-width:768px){
    .hero h1{
        font-size:32px;
    }

    nav ul{
        display:none;
    }
}

</style>
</head>

<body>

<nav>
    <h2>Kulubya King</h2>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<div class="hero" id="home">
    <div class="hero-content">
        <h1>Build Your Golden Future</h1>
        <p>Modern Web Design | Animation | Responsive Layout</p>
        <button class="btn">Get Started</button>
    </div>
</div>

<section id="services">
    <h2 class="section-title">Our Services</h2>
    <div class="cards">
        <div class="card">
            <h3>Web Design</h3>
            <p>Beautiful and modern user interfaces.</p>
        </div>
        <div class="card">
            <h3>Responsive Layout</h3>
            <p>Perfect on mobile, tablet and desktop.</p>
        </div>
        <div class="card">
            <h3>Animations</h3>
            <p>Smooth transitions and engaging effects.</p>
        </div>
    </div>
</section>

<section id="about">
    <h2 class="section-title">About Us</h2>
    <div class="cards">
        <div class="card">
            <p>We create elegant, high-quality web experiences with premium styling and clean code.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2 class="section-title">Contact</h2>
    <div class="cards">
        <div class="card">
            <p>Email: info@example.com</p>
            <p>Phone: +256709653345</p>
        </div>
    </div>
</section>

<footer>
    © 2026 Kulubya King | All Rights Reserved
</footer>

</body>
</html>
