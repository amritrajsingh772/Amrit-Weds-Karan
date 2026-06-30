# Amrit-Weds-Karan
<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Amrit & Karanbir | Wedding</title>

<style>

@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600;700&family=Poppins:wght@300;400;500&display=swap');

* {

    margin: 0;

    padding: 0;

    box-sizing: border-box;

}

body {

    background: #fffaf3;

    color: #4a3525;

    font-family: 'Poppins', sans-serif;

}

h1,h2,h3 {

    font-family: 'Cormorant Garamond', serif;

}

.hero {

    min-height: 100vh;

    background: linear-gradient(

        rgba(255,250,243,.85),

        rgba(255,250,243,.95)

    );

    display:flex;

    align-items:center;

    justify-content:center;

    text-align:center;

    padding:30px;

}

.logo {

    width:220px;

    margin-bottom:20px;

}

.hero h1 {

    font-size:70px;

    color:#a67c2d;

}

.hero p {

    font-size:20px;

    letter-spacing:2px;

}

.date {

    margin-top:25px;

    font-size:26px;

    color:#8b5e20;

}

section {

    padding:70px 10%;

    text-align:center;

}

.section-title {

    font-size:45px;

    margin-bottom:35px;

    color:#a67c2d;

}

.card-container {

    display:flex;

    gap:30px;

    justify-content:center;

    flex-wrap:wrap;

}

.card {

    background:white;

    width:320px;

    padding:35px;

    border-radius:20px;

    box-shadow:0 10px 30px rgba(0,0,0,.08);

}

.card h3 {

    font-size:32px;

    color:#a67c2d;

    margin-bottom:15px;

}

.card p {

    line-height:1.7;

}

.family {

    background:#f7ead8;

}

.person {

    margin:25px;

}

.person h3 {

    font-size:35px;

}

.events {

    background:#fff;

}

.countdown {

    font-size:35px;

    color:#a67c2d;

    margin-top:20px;

}

.rsvp {

    background:#f7ead8;

}

button {

    background:#a67c2d;

    color:white;

    border:none;

    padding:15px 40px;

    border-radius:30px;

    font-size:16px;

    cursor:pointer;

}

footer {

    padding:30px;

    text-align:center;

    background:#4a3525;

    color:white;

}

@media(max-width:700px){

    .hero h1 {

        font-size:45px;

    }

    .section-title {

        font-size:35px;

    }

}

</style>

</head>

<body>

<section class="hero">

<div>

<!-- Replace this image with your A+K transparent logo -->

<img class="logo" src="AK-logo.png">

<h1>AMRIT<br>&<br>KARANBIR</h1>

<p>Two souls • One journey • Forever together</p>

<div class="date">

November 25, 2026

<br>

Manka by Cherish, Karnal

</div>

</div>

</section>

<section class="family">

<h2 class="section-title">With Blessings Of Our Families</h2>

<div class="person">

<h3>Groom</h3>

<p>

<strong>AMRIT RAJ SINGH</strong><br>

S/O S. Harwant Singh & Sdn. Davinder Kaur

</p>

</div>

<div class="person">

<h3>Bride</h3>

<p>

<strong>KARANBIR KAUR</strong><br>

D/O Late S. Jagtar Singh Gill & Sdn. Gurjeet Kaur Gill

</p>

</div>

</section>

<section>

<h2 class="section-title">Counting The Days</h2>

<div class="countdown" id="timer"></div>

</section>

<section class="events">

<h2 class="section-title">Wedding Celebrations</h2>

<div class="card-container">

<div class="card">

<h3>Shagun</h3>

<p>

<strong>November 22, 2026</strong>

<br>

Avani Gardens, Amritsar

<br><br>

A beautiful Punjabi tradition celebrating

the coming together of two families.

The Shagun ceremony marks the beginning

of wedding celebrations with blessings,

love, and exchange of good wishes.

</p>

</div>

<div class="card">

<h3>Anand Karaj</h3>

<p>

<strong>November 25, 2026</strong>

<br>

Manka by Cherish, Karnal

<br><br>

The sacred Sikh wedding ceremony where

the couple takes four Laavan around

Sri Guru Granth Sahib Ji, promising a life

of love, equality, commitment, and spiritual

companionship.

</p>

</div>

<div class="card">

<h3>Reception</h3>

<p>

<strong>November 27, 2026</strong>

<br>

The Golden Tulip, Amritsar

<br><br>

An evening of celebration, happiness,

music, and togetherness as family and

friends gather to bless the newly married

couple.

</p>

</div>

</div>

</section>

<section class="rsvp">

<h2 class="section-title">Join Our Celebration</h2>

<p>

Your presence and blessings will make our wedding

celebrations even more special.

</p>

<br>

<button>

RSVP

</button>

</section>

<footer>

With love,

<br>

Amrit & Karanbir

<br>

2026

</footer>

<script>

const weddingDate = new Date("November 25, 2026 12:00:00").getTime();

setInterval(function(){

let now = new Date().getTime();

let distance = weddingDate - now;

let days = Math.floor(distance/(1000*60*60*24));

let hours = Math.floor(

(distance%(1000*60*60*24))/(1000*60*60)

);

let minutes = Math.floor(

(distance%(1000*60*60))/(1000*60)

);

let seconds = Math.floor(

(distance%(1000*60))/1000

);

document.getElementById("timer").innerHTML =

days+" Days "+hours+" Hours "+minutes+" Minutes "+seconds+" Seconds";

},1000);

</script>

</body>

</html>