<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Bell Marketing Agency</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f5f7fb;
color:#333;
}

header{
background:#0f172a;
color:white;
padding:20px 10%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
z-index:1000;
}

header h2{
color:#38bdf8;
}

nav a{
color:white;
margin-left:20px;
text-decoration:none;
}

.hero{
height:90vh;
display:flex;
align-items:center;
justify-content:center;
flex-direction:column;
background:linear-gradient(135deg,#0f172a,#2563eb);
color:white;
text-align:center;
}

.hero h1{
font-size:50px;
margin-bottom:20px;
}

.hero button{
padding:12px 25px;
border:none;
background:#38bdf8;
color:white;
font-size:16px;
cursor:pointer;
border-radius:6px;
}

section{
padding:80px 10%;
}

.title{
text-align:center;
margin-bottom:50px;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.service-box{
background:white;
padding:30px;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
transition:0.4s;
}

.service-box:hover{
transform:translateY(-10px);
}

.portfolio-filter{
text-align:center;
margin-bottom:30px;
}

.portfolio-filter button{
padding:10px 18px;
margin:5px;
border:none;
background:#2563eb;
color:white;
cursor:pointer;
border-radius:5px;
}

.portfolio{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.portfolio-card{
background:white;
border-radius:10px;
overflow:hidden;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
text-align:center;
}

.portfolio-card img{
width:100%;
height:200px;
object-fit:cover;
cursor:pointer;
}

.portfolio-card a{
display:inline-block;
margin:10px;
padding:8px 18px;
background:#2563eb;
color:white;
text-decoration:none;
border-radius:5px;
}

.counter-section{
background:#2563eb;
color:white;
display:flex;
justify-content:space-around;
text-align:center;
padding:60px 10%;
}

.counter h2{
font-size:40px;
}

.pricing{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.price-box{
background:white;
padding:40px;
text-align:center;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.blog{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.blog-box{
background:white;
padding:20px;
border-radius:10px;
}

.contact form{
display:flex;
flex-direction:column;
gap:15px;
max-width:500px;
margin:auto;
}

.contact input,.contact textarea{
padding:10px;
border:1px solid #ccc;
border-radius:5px;
}

.contact button{
background:#2563eb;
color:white;
padding:10px;
border:none;
cursor:pointer;
}

footer{
background:#0f172a;
color:white;
text-align:center;
padding:20px;
}

iframe{
width:100%;
height:300px;
border:none;
border-radius:10px;
margin-top:20px;
}

.popup{
display:none;
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,0.8);
justify-content:center;
align-items:center;
}

.popup img{
max-width:80%;
border-radius:10px;
}

.popup span{
position:absolute;
top:20px;
right:40px;
font-size:30px;
color:white;
cursor:pointer;
}

</style>
</head>

<body>

<header>
<h2>Bell Marketing</h2>
<nav>
<a href="#">Home</a>
<a href="#services">Services</a>
<a href="#portfolio">Portfolio</a>
<a href="#pricing">Pricing</a>
<a href="#blog">Blog</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero">
<h1>Grow Your Business With Digital Marketing 🚀</h1>
<p>SEO • Social Media • Website Development</p>
<button>Get Started</button>
</section>

<section>
<div class="title">
<h2>About Our Agency</h2>
</div>
<p style="text-align:center">
We are a modern digital marketing agency helping brands grow online using SEO,
social media marketing, paid ads, and website development.
</p>
</section>

<section id="services">
<div class="title">
<h2>Our Services</h2>
</div>

<div class="services">

<div class="service-box">
<h3>SEO Optimization</h3>
<p>Rank your website on Google search results.</p>
</div>

<div class="service-box">
<h3>Social Media Marketing</h3>
<p>Grow your brand on Instagram & Facebook.</p>
</div>

<div class="service-box">
<h3>Website Development</h3>
<p>Modern responsive business websites.</p>
</div>

<div class="service-box">
<h3>Google Ads</h3>
<p>Run high converting paid advertising campaigns.</p>
</div>

</div>
</section>

<section id="portfolio">

<div class="title">
<h2>Our Portfolio</h2>
</div>

<div class="portfolio-filter">
<button onclick="filterSelection('all')">All</button>
<button onclick="filterSelection('web')">Web</button>
<button onclick="filterSelection('seo')">SEO</button>
<button onclick="filterSelection('marketing')">Marketing</button>
</div>

<div class="portfolio">

<div class="portfolio-card web">
<img src="https://images.unsplash.com/photo-1551434678-e076c223a692">
<h3>E-commerce Website</h3>
<a href="#">View Project</a>
</div>

<div class="portfolio-card seo">
<img src="https://images.unsplash.com/photo-1559027615-cd4628902d4a">
<h3>SEO Campaign</h3>
<a href="#">View Project</a>
</div>

<div class="portfolio-card marketing">
<img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085">
<h3>Marketing Strategy</h3>
<a href="#">View Project</a>
</div>

</div>

</section>

<section class="counter-section">

<div class="counter">
<h2>500+</h2>
<p>Clients</p>
</div>

<div class="counter">
<h2>1200+</h2>
<p>Projects</p>
</div>

<div class="counter">
<h2>10+</h2>
<p>Years Experience</p>
</div>

</section>

<section id="pricing">

<div class="title">
<h2>Pricing Plans</h2>
</div>

<div class="pricing">

<div class="price-box">
<h3>Starter</h3>
<h2>$299</h2>
<p>SEO + Social Media</p>
</div>

<div class="price-box">
<h3>Professional</h3>
<h2>$699</h2>
<p>SEO + Ads + Marketing</p>
</div>

<div class="price-box">
<h3>Enterprise</h3>
<h2>$1299</h2>
<p>Full Digital Marketing</p>
</div>

</div>

</section>

<section id="blog">

<div class="title">
<h2>Latest Blog</h2>
</div>

<div class="blog">

<div class="blog-box">
<h3>Top SEO Strategies 2025</h3>
<p>Learn how to rank your website on Google.</p>
</div>

<div class="blog-box">
<h3>Social Media Growth Tips</h3>
<p>How to grow your Instagram followers.</p>
</div>

<div class="blog-box">
<h3>Why Your Business Needs a Website</h3>
<p>Website importance for modern businesses.</p>
</div>

</div>

</section>

<section id="contact" class="contact">

<div class="title">
<h2>Contact Us</h2>
</div>

<form>

<input type="text" placeholder="your name">

<input type="email" placeholder="Your Email">

<textarea placeholder="Your Message"></textarea>

<button>Send Message</button>

</form>

<h3 style="text-align:center;margin-top:40px">Our Location</h3>

<iframe src="https://maps.google.com/maps?q=San%20Francisco&t=&z=13&ie=UTF8&iwloc=&output=embed"></iframe>

</section>

<div id="popup" class="popup">
<span onclick="closePopup()">✖</span>
<img id="popup-img">
</div>

<footer>
<p>© 2026 Bell Marketing Agency</p>
</footer>

<script>

function filterSelection(category){

let cards=document.getElementsByClassName("portfolio-card");

for(let i=0;i<cards.length;i++){

if(category==="all"){
cards[i].style.display="block";
}

else if(cards[i].classList.contains(category)){
cards[i].style.display="block";
}

else{
cards[i].style.display="none";
}

}

}

let images=document.querySelectorAll(".portfolio-card img");

images.forEach(img=>{
img.addEventListener("click",function(){
document.getElementById("popup").style.display="flex";
document.getElementById("popup-img").src=this.src;
});
});

function closePopup(){
document.getElementById("popup").style.display="none";
}

</script>

</body>
</html>
