# Wild_rose_stitch
The Wild Rose Stitch – A handmade crochet brand by Nasrin Khan,  specializing in elegant rose bracelets and custom handcrafted pieces.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Wild Rose Stitch | Nasrin Khan</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#fdf8f5;
color:#333;
}

header{
background:white;
padding:15px 50px;
display:flex;
justify-content:space-between;
align-items:center;
box-shadow:0 2px 10px rgba(0,0,0,0.05);
position:sticky;
top:0;
z-index:1000;
}

.logo img{
height:60px;
}

nav a{
text-decoration:none;
margin-left:25px;
color:#444;
font-weight:500;
}

nav a:hover{
color:#8b1e3f;
}

.hero{
height:90vh;
background:url('photo1.jpg') center/cover no-repeat;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
position:relative;
}

.hero::before{
content:"";
position:absolute;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,0.45);
}

.hero-content{
position:relative;
z-index:2;
}

.hero h2{
font-size:50px;
font-family:'Playfair Display',serif;
}

.hero p{
margin:20px 0;
font-size:20px;
}

.btn{
display:inline-block;
padding:12px 30px;
background:#8b1e3f;
color:white;
text-decoration:none;
border-radius:30px;
transition:0.3s;
}

.btn:hover{
background:#b8325a;
}

.section{
padding:80px 10%;
text-align:center;
}

.section h3{
font-family:'Playfair Display',serif;
font-size:35px;
margin-bottom:20px;
color:#8b1e3f;
}

.gallery{
display:flex;
gap:30px;
flex-wrap:wrap;
justify-content:center;
margin-top:40px;
}

.gallery img{
width:300px;
height:400px;
object-fit:cover;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
transition:0.3s;
}

.gallery img:hover{
transform:scale(1.05);
}

footer{
background:#8b1e3f;
color:white;
padding:20px;
text-align:center;
margin-top:50px;
}
</style>
</head>

<body>

<header>
<div class="logo">
<img src="logo.png" alt="Wild Rose Stitch Logo">
</div>

<nav>
<a href="#">Home</a>
<a href="#">Gallery</a>
<a href="#">Contact</a>
</nav>
</header>

<section class="hero">
<div class="hero-content">
<h2>Woven with Love</h2>
<p>Handmade Artistry by Nasrin Khan</p>
<a href="#" class="btn">Explore Collection</a>
</div>
</section>

<section class="section">
<h3>Our Handmade Collection</h3>
<p>Beautiful crochet rose bracelets crafted with care and passion.</p>

<div class="gallery">
<img src="photo1.jpg" alt="">
<img src="photo2.jpg" alt="">
<img src="photo3.jpg" alt="">
</div>
</section>

<section class="section">
<h3>About The Brand</h3>
<p>
Every piece is lovingly handcrafted by Nasrin Khan.  
The Wild Rose Stitch is all about elegance, warmth, and meaningful handmade artistry.
</p>
</section>

<footer>
<p>© 2026 The Wild Rose Stitch | Designed with Love</p>
</footer>

</body>
</html>
