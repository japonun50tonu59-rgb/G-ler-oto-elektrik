# Guler-oto-elektrik
<!DOCTYPE html>
<html lang="tr">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Güler Oto Elektrik | Oto Elektrik ve Elektronik Servisi</title>

    <meta name="description"
        content="Güler Oto Elektrik - Marş Motoru, Şarj Dinamosu, Akü, Araç Elektrik Arızaları, ECU Arıza Tespiti ve Oto Elektrik Hizmetleri">

    <meta name="keywords"
        content="Oto Elektrik, Güler Oto Elektrik, Akü, Marş Motoru, Şarj Dinamosu, ECU, Elektrik Arızası">

    <meta name="author" content="Güler Oto Elektrik">

    <link rel="stylesheet" href="css/style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap"
        rel="stylesheet">

    <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">

</head>

<body>

<header>

<div class="container">

<div class="logo">

<i class="fa-solid fa-car-battery"></i>

<span>GÜLER OTO ELEKTRİK</span>

</div>

<nav>

<ul>

<li><a href="#">Ana Sayfa</a></li>
<li><a href="#services">Hizmetler</a></li>
<li><a href="#about">Hakkımızda</a></li>
<li><a href="#comments">Yorumlar</a></li>
<li><a href="#contact">İletişim</a></li>

</ul>

</nav>

</div>

</header>

<section class="hero">

<div class="hero-content">

<h1>GÜLER OTO ELEKTRİK</h1>

<h2>Profesyonel Oto Elektrik ve Elektronik Servisi</h2>

<p>

Marş Motoru • Şarj Dinamosu • Akü • ECU • Elektrik Tesisatı • Bilgisayarlı Arıza Tespiti

</p>

<div class="hero-buttons">

<a href="#contact" class="btn">Bize Ulaşın</a>

<a href="https://wa.me/905555555555" class="btn-whatsapp">

<i class="fab fa-whatsapp"></i>

WhatsApp

</a>

</div>

</div>

</section>

<section id="services" class="services">

<h2>Hizmetlerimiz</h2>

<div class="service-box">

<div class="card">

<i class="fa-solid fa-car-battery"></i>

<h3>Akü Değişimi</h3>

<p>Kaliteli akü satışı ve montajı.</p>

</div>

<div class="card">

<i class="fa-solid fa-bolt"></i>

<h3>Elektrik Arızaları</h3>

<p>Profesyonel arıza tespiti ve onarımı.</p>

</div>

<div class="card">

<i class="fa-solid fa-gears"></i>

<h3>Marş & Şarj Dinamosu</h3>

<p>Bakım, tamir ve değişim hizmeti.</p>

</div>

<div class="card">

<i class="fa-solid fa-microchip"></i>

<h3>ECU Kontrolü</h3>

<p>Beyin arızalarının bilgisayarlı kontrolü.</p>

</div>

</div>

</section>

<section id="about" class="about">

<h2>Hakkımızda</h2>

<p>

Güler Oto Elektrik olarak kaliteli işçilik, uygun fiyat ve müşteri memnuniyetini ön planda tutuyoruz. Araç elektrik ve elektronik sistemlerinde profesyonel çözümler sunuyoruz.

</p>

</section>

<section id="comments" class="comments">

<h2>Müşteri Yorumları</h2>

<div class="comment">

★★★★★

<p>

"Hızlı servis ve güler yüzlü hizmet. Kesinlikle tavsiye ederim."

</p>

<strong>Ahmet K.</strong>

</div>

<div class="comment">

★★★★★

<p>

"Aracımın elektrik arızasını aynı gün çözdüler."

</p>

<strong>Mehmet D.</strong>

</div>

</section>

<section class="request">

<h2>Online Arıza Talep Formu</h2>

<form>

<input type="text" placeholder="Ad Soyad" required>

<input type="tel" placeholder="Telefon" required>

<input type="text" placeholder="Araç Markası">

<input type="text" placeholder="Araç Modeli">

<textarea placeholder="Arızayı detaylı anlatınız..."></textarea>

<button type="submit">Gönder</button>

</form>

</section>

<section id="contact" class="contact">

<h2>İletişim</h2>

<p><i class="fa-solid fa-phone"></i> 0555 555 55 55</p>

<p><i class="fa-solid fa-location-dot"></i> Çerkezköy / Tekirdağ</p>

<p><i class="fa-solid fa-clock"></i> Pazartesi - Cumartesi : 08:00 - 19:00</p>

</section>

<a href="https://wa.me/905555555555" class="whatsapp">

<i class="fab fa-whatsapp"></i>

</a>

<footer>

<p>© 2026 Güler Oto Elektrik | Tüm Hakları Saklıdır.</p>

</footer>

<script src="js/script.js"></script>

</body>

</html>
/* =======================================
   GÜLER OTO ELEKTRİK
   style.css - Bölüm 1
======================================= */

/* Google Font */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');

/* Genel Ayarlar */
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0d0d0d;
    color:#fff;
    line-height:1.6;
}

/* Ortak Container */
.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

/* ==========================
   HEADER
========================== */

header{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    background:rgba(0,0,0,.92);
    backdrop-filter:blur(10px);
    z-index:999;
    box-shadow:0 2px 15px rgba(255,0,0,.15);
}

header .container{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:18px 0;
}

.logo{
    display:flex;
    align-items:center;
    gap:10px;
}

.logo i{
    color:#ff2b2b;
    font-size:32px;
}

.logo span{
    color:#fff;
    font-size:24px;
    font-weight:700;
}

/* Menü */

nav ul{
    list-style:none;
    display:flex;
    gap:30px;
}

nav ul li a{
    color:#fff;
    text-decoration:none;
    font-weight:500;
    transition:.3s;
}

nav ul li a:hover{
    color:#ff2b2b;
}

/* ==========================
   HERO
========================== */

.hero{
    height:100vh;

    background:
    linear-gradient(rgba(0,0,0,.75),rgba(0,0,0,.75)),
    url("../images/hero.jpg"); <img width="1200" height="797" alt="otoelektrik" src="https://github.com/user-attachments/assets/50163cb5-6514-4529-a31d-018e3d6abe30" />



    background-size:cover;
    background-position:center;

    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;

    padding:20px;
}

.hero-content{
    max-width:900px;
}

.hero h1{

    font-size:62px;

    color:#ff2b2b;

    text-shadow:0 0 25px red;

    margin-bottom:20px;

}

.hero h2{

    font-size:34px;

    margin-bottom:20px;

}

.hero p{

    font-size:20px;

    color:#ddd;

    margin-bottom:40px;

}

/* Butonlar */

.hero-buttons{

    display:flex;

    justify-content:center;

    gap:20px;

    flex-wrap:wrap;

}

.btn{

    background:#ff2b2b;

    color:#fff;

    padding:16px 35px;

    text-decoration:none;

    border-radius:50px;

    font-weight:600;

    transition:.3s;

}

.btn:hover{

    background:#fff;

    color:#000;

}

.btn-whatsapp{

    background:#25D366;

    color:#fff;

    padding:16px 35px;

    border-radius:50px;

    text-decoration:none;

    font-weight:600;

    transition:.3s;

}

.btn-whatsapp:hover{

    transform:translateY(-5px);

    box-shadow:0 0 20px #25D366;

}

/* Bölüm Başlıkları */

section{

    padding:100px 20px;

}

section h2{

    text-align:center;

    font-size:40px;

    color:#ff2b2b;

    margin-bottom:50px;

}
/* ==========================================
   HİZMETLER
========================================== */

.services{
    background:#111;
}

.service-box{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
}

.card{

    background:#1b1b1b;

    border-radius:15px;

    padding:35px;

    text-align:center;

    transition:.35s;

    border:1px solid rgba(255,255,255,.05);

}

.card:hover{

    transform:translateY(-12px);

    box-shadow:0 15px 40px rgba(255,0,0,.35);

}

.card i{

    font-size:55px;

    color:#ff2b2b;

    margin-bottom:20px;

}

.card h3{

    margin-bottom:15px;

}

.card p{

    color:#bbb;

}

/* ==========================================
   HAKKIMIZDA
========================================== */

.about{

    background:#181818;

    text-align:center;

}

.about p{

    max-width:900px;

    margin:auto;

    font-size:18px;

    color:#ddd;

    line-height:1.9;

}

/* ==========================================
   MÜŞTERİ YORUMLARI
========================================== */

.comments{

    background:#111;

}

.comment{

    background:#1d1d1d;

    margin:20px auto;

    max-width:800px;

    padding:30px;

    border-left:5px solid #ff2b2b;

    border-radius:12px;

    transition:.3s;

}

.comment:hover{

    transform:scale(1.02);

}

.comment p{

    margin:15px 0;

    color:#ddd;

}

.comment strong{

    color:#ff2b2b;

}

/* ==========================================
   ARIZA TALEP FORMU
========================================== */

.request{

    background:#181818;

}

.request form{

    max-width:700px;

    margin:auto;

}

.request input,
.request textarea{

    width:100%;

    margin-bottom:18px;

    padding:16px;

    border:none;

    border-radius:10px;

    background:#252525;

    color:#fff;

    font-size:16px;

}

.request textarea{

    min-height:160px;

    resize:vertical;

}

.request button{

    width:100%;

    background:#ff2b2b;

    color:#fff;

    border:none;

    padding:18px;

    font-size:18px;

    border-radius:10px;

    cursor:pointer;

    transition:.3s;

}

.request button:hover{

    background:#d60000;

}

/* ==========================================
   İLETİŞİM
========================================== */

.contact{

    background:#111;

    text-align:center;

}

.contact p{

    margin:15px 0;

    font-size:18px;

}

.contact i{

    color:#ff2b2b;

    margin-right:10px;

}

/* ==========================================
   WHATSAPP
========================================== */

.whatsapp{

    position:fixed;

    right:25px;

    bottom:25px;

    width:65px;

    height:65px;

    background:#25D366;

    border-radius:50%;

    display:flex;

    justify-content:center;

    align-items:center;

    color:white;

    font-size:34px;

    text-decoration:none;

    box-shadow:0 10px 30px rgba(0,0,0,.4);

    transition:.3s;

    z-index:9999;

}

.whatsapp:hover{

    transform:scale(1.15);

}

/* ==========================================
   FOOTER
========================================== */

footer{

    background:#000;

    padding:30px;

    text-align:center;

    color:#aaa;

    border-top:1px solid #222;

}
/* ======================================
   GÜLER OTO ELEKTRİK
   script.js
====================================== */

// Sayfa yüklendiğinde
window.addEventListener("load", () => {
    document.body.classList.add("loaded");
});

// Header arka planı
const header = document.querySelector("header");

window.addEventListener("scroll", () => {
    if (window.scrollY > 80) {
        header.classList.add("active");
    } else {
        header.classList.remove("active");
    }
});

// Sayfa kaydırma animasyonu
const observer = new IntersectionObserver((entries) => {

    entries.forEach((entry) => {

        if(entry.isIntersecting){

            entry.target.classList.add("show");

        }

    });

});

document.querySelectorAll(".card,.comment,.about,.request,.contact")
.forEach((el)=>{
    observer.observe(el);
});

// Sayaç Animasyonu

const counters=document.querySelectorAll(".counter h2");

counters.forEach(counter=>{

let start=0;

const target=Number(counter.innerText.replace("+",""));

const speed=25;

const update=()=>{

start+=Math.ceil(target/100);

if(start<target){

counter.innerText=start+"+";

setTimeout(update,speed);

}else{

counter.innerText=target+"+";

}

}

update();

});

// WhatsApp Butonu Animasyonu

const whatsapp=document.querySelector(".whatsapp");

setInterval(()=>{

whatsapp.classList.toggle("pulse");

},1200);

// Form Kontrolü

const form=document.querySelector("form");

if(form){

form.addEventListener("submit",(e)=>{

e.preventDefault();

alert("Talebiniz başarıyla alınmıştır. En kısa sürede sizinle iletişime geçeceğiz.");

form.reset();

});

}

// Yukarı Çık Butonu

const topButton=document.createElement("div");

topButton.innerHTML="↑";

topButton.className="topButton";

document.body.appendChild(topButton);

window.addEventListener("scroll",()=>{

if(window.scrollY>500){

topButton.style.display="flex";

}else{

topButton.style.display="none";

}

});

topButton.onclick=()=>{

window.scrollTo({

top:0,

behavior:"smooth"

});

};
