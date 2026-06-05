
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Beauty of Nature</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:Arial,sans-serif;
background:#111;
color:white;
line-height:1.6;
}

header{
background:#000;
padding:20px;
text-align:center;
position:sticky;
top:0;
}

header h1{
color:#4CAF50;
}

nav a{
color:white;
text-decoration:none;
margin:0 10px;
}

.hero{
height:80vh;
background:url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=1600') center/cover;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
}

.hero-content{
background:rgba(0,0,0,0.6);
padding:25px;
border-radius:10px;
}

.hero h2{
font-size:40px;
margin-bottom:10px;
}

section{
padding:50px 20px;
}

.section-title{
text-align:center;
color:#4CAF50;
margin-bottom:25px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:10px;
transition:.3s;
}

.gallery img:hover{
transform:scale(1.05);
}

.about{
max-width:800px;
margin:auto;
text-align:center;
}

.contact{
text-align:center;
}

.btn{
display:inline-block;
padding:12px 25px;
background:#4CAF50;
color:white;
text-decoration:none;
border-radius:5px;
margin-top:10px;
}

footer{
background:#000;
text-align:center;
padding:20px;
margin-top:20px;
}
</style>
</head>

<body>

<header>
<h1>The Beauty of Nature</h1>
<p>Mr. Hazra's Mobile Photography</p>

<nav>
<a href="#about">About</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</nav>
</header>

<div class="hero">
<div class="hero-content">
<h2>Capturing Nature's Beauty</h2>
<p>Photography by Mr. Hazra</p>
</div>
</div>

<section id="about">
<h2 class="section-title">About Me</h2>
<div class="about">
<p>
Welcome to The Beauty of Nature.
I am Surajit Hazra, passionate about capturing nature through mobile photography.
Every image reflects the beauty of forests, rivers, skies, sunsets and landscapes.
</p>
</div>
</section>

<section id="gallery">
<h2 class="section-title">Nature Gallery</h2>

<div class="gallery">
<img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?w=800">
<img src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e?w=800">
<img src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e?w=800">
<img src="https://images.unsplash.com/photo-1465146344425-f00d5f5c8f07?w=800">
<img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?w=800">
<img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=800">
</div>

</section>

<section id="contact">
<h2 class="section-title">Contact</h2>

<div class="contact">
<p><strong>Photographer:</strong> Surajit Hazra</p>
<p><strong>Instagram:</strong> @Mr.alonedude</p>
<p><strong>Email:</strong> surajitthealonedude@gmail.com</p>

<a class="btn"
href="mailto:surajitthealonedude@gmail.com">
Send Email
</a>
</div>

</section>

<footer>
<p>© 2026 The Beauty of Nature | Mr. Hazra's Mobile Photography</p>
</footer>

</body>
</html>
