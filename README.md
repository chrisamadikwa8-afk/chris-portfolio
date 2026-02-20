<!DOCTYPE html>  <html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Apexora Group</title>  <style>  
/* *{  
    margin:0;  
    padding:0;#42445Aindex.htmlindex.htmlpadding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    padding:0;#42445Aindex.htmlindex.html  
    box-sizing:border-box;  
    font-family: 'Segoe UI', sans-serif;  
} */  
  
html{  
    scroll-behavior: smooth;  
}  
  
body{  
    background:#0b1120;  
    color:white;  
}  
  
/* Header */  
header{  
    display:flex;  
    justify-content:space-between;  
    align-items:center;  
    padding:20px 8%;  
    background:#111827;  
    position:sticky;  
    top:0;  
    z-index:999;  
}  
  
.logo{  
    font-size:22px;  
    font-weight:bold;  
    color:#3b82f6;  
}  
  
nav a{  
    text-decoration:none;  
    color:white;  
    margin-left:20px;  
    font-size:14px;  
    transition:0.3s;  
}  
  
nav a:hover{  
    color:#3b82f6;  
}  
  
/* Hero */  
.hero{  
    text-align:center;  
    padding:100px 20px;  
    opacity:0;  
    transform:translateY(50px);  
    transition:1s;  
}  
  
.hero h1{  
    font-size:36px;  
    margin-bottom:20px;  
}  
  
.hero p{  
    max-width:500px;  
    margin:0 auto 30px;  
    font-size:15px;  
    color:#cbd5e1;  
}  
  
.btn{  
    padding:12px 28px;  
    background:#3b82f6;  
    border:none;  
    border-radius:6px;  
    font-weight:bold;  
    cursor:pointer;  
    transition:0.3s;  
}  
  
.btn:hover{  
    background:white;  
    color:black;  
    transform:scale(1.05);  
}  
  
/* Sections */  
section{  
    opacity:0;  
    transform:translateY(50px);  
    transition:1s;  
}  
  
.services{  
    padding:70px 8%;  
    background:#0f172a;  
    text-align:center;  
}  
  
.services h2{  
    margin-bottom:40px;  
}  
  
.grid{  
    display:grid;  
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));  
    gap:20px;  
}  
  
.card{  
    background:#1e293b;  
    padding:25px;  
    border-radius:10px;  
    transition:0.3s;  
}  
  
.card h3{  
    margin-bottom:10px;  
    color:#3b82f6;  
}  
  
.card:hover{  
    transform:translateY(-10px);  
}  
  
/* About */  
.about{  
    padding:70px 8%;  
    background:#111827;  
    text-align:center;  
}  
  
/* Contact */  
.contact{  
    padding:70px 8%;  
    text-align:center;  
}  
  
input, textarea{  
    width:100%;  
    padding:12px;  
    margin:10px 0;  
    border-radius:5px;  
    border:1px solid #ccc;  
}  
  
footer{  
    text-align:center;  
    padding:20px;  
    background:#111827;  
    font-size:14px;  
}  
  
/* WhatsApp Button */  
.whatsapp{  
    position:fixed;  
    bottom:20px;  
    right:20px;  
    background:#25D366;  
    color:white;  
    padding:12px 18px;  
    border-radius:30px;  
    text-decoration:none;  
    font-weight:bold;  
    box-shadow:0 5px 15px rgba(0,0,0,0.3);  
    z-index:1000;  
}  
  
.whatsapp:hover{  
    background:#1ebe5d;  
}  
</style>  </head>  <body>  <header>  
<div class="logo">Apexora Group</div>  
<nav>  
<a href="#hero">Home</a>  
<a href="#services">Services</a>  
<a href="#about">About</a>  
<a href="#contact">Contact</a>  
</nav>  
</header>  <section class="hero" id="hero">  
<h1>Leading Innovation. Delivering Excellence.</h1>  
<p>Apexora Group provides modern business solutions, digital strategy, and technology services to help companies grow faster and smarter.</p>  
<button class="btn" onclick="alert('Thank you! We will contact you shortly!')">Work With Us</button>  
</section>  <section class="services" id="services">  
<h2>Our Core Services</h2>  
<div class="grid">  
<div class="card">  
<h3>Business Consulting</h3>  
<p>Strategic planning and expert advice to scale your operations.</p>  
</div>  
<div class="card">  
<h3>Digital Solutions</h3>  
<p>Modern websites, systems, and automation tools.</p>  
</div>  
<div class="card">  
<h3>Brand Development</h3>  
<p>Strong brand identity that positions you ahead of competitors.</p>  
</div>  
</div>  
</section>  <section class="about" id="about">  
<h2>About Us</h2>  
<p>We are a team dedicated to helping businesses succeed online with modern solutions and creative strategies. Our mission is to take your business to the next level.</p>  
</section>  <section class="contact" id="contact">  
<h2>Contact Us</h2>  
<input type="text" placeholder="Your Name">  
<input type="email" placeholder="Your Email">  
<textarea rows="5" placeholder="Your Message"></textarea>  
<button class="btn" onclick="alert('Message sent! We will reply soon.')">Send Message</button>  
</section>  <footer>  
© 2026 Apexora Group. All Rights Reserved.  
</footer>  <!-- WhatsApp Button -->  <a href="https://wa.me/2348033170605" class="whatsapp" target="_blank">  
    💬 Chat on WhatsApp  
</a>  <script>  
// Scroll animations  
const sections = document.querySelectorAll('section, .hero');  
const options = {threshold: 0.1};  
  
const observer = new IntersectionObserver((entries, observer) => {  
    entries.forEach(entry => {  
        if(entry.isIntersecting){  
            entry.target.style.opacity = 1;  
            entry.target.style.transform = 'translateY(0)';  
        }  
    });  
}, options);  
  
sections.forEach(section => observer.observe(section));  
</script>  </body>  
</html>
