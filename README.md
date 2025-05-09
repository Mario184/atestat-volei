Cod HTML Site Rețete și Informații Despre Mâncăruri
Sarmale
- Sarmalele sunt nelipsite de pe masa de Crăciun sau de la alte sărbători mari.
- Se folosesc foi de varză murată sau, în anumite zone, frunze de viță de vie.
- Umplutura conține carne tocată (de porc, vită sau amestec), orez și ceapă călită.
- Condimentele frecvent folosite sunt piperul, cimbrul și boiaua dulce.
- Sunt gătite lent, în oale de lut sau email, înăbușite cu suc de roșii.
- Sarmalele sunt servite cu mămăligă și smântână în multe regiuni.
Ciorbă de burtă
- Un preparat românesc apreciat pentru gustul acru și textura cremoasă.
- Se folosește burtă de vită prefiartă, oase pentru supă, morcov, țelină.
- Zeama se îngroașă cu gălbenuș de ou și smântână, fără a fierbe după aceea.
- Se servește cu oțet, ardei iute și mujdei de usturoi.
- Are o valoare nutrițională ridicată, datorită colagenului din burtă.
- Este considerată un remediu tradițional împotriva mahmurelii.
Mămăligă cu brânză
- Este un fel de mâncare simplu și tradițional, asociat cu zona rurală.
- Se prepară prin fierberea mălaiului în apă cu sare până devine consistent.
- Se servește cu brânză de burduf, telemea sau cașcaval ras.
- Uneori se adaugă smântână și ou ochi pentru un plus de savoare.
- În Maramureș, se servește cu jumări și cârnați.
- Este bogată în carbohidrați și săracă în grăsimi dacă se servește simplă.
Cozonac
- Cozonacul este desertul tradițional al Crăciunului și Paștelui.
- Aluatul dospit este îmbogățit cu ouă, lapte și unt pentru un gust bogat.
- Se umple cu nuci, cacao, stafide sau rahat în funcție de regiune.
- Se coace în tăvi unse și tapetate, de obicei la foc moderat.
- Glazura de ou îi oferă luciu și o crustă rumenă.
- Este un simbol al ospitalității și al tradiției culinare românești.
Papanași
- Desert specific Moldovei, cu origine incertă, dar răspândit național.
- Se prepară din brânză de vaci, ou, griș și făină.
- Forma clasică este de gogoșică cu un moț sferic deasupra.
- Se prăjesc în ulei încins până capătă crustă aurie.
- Se servesc cu smântână și dulceață (de vișine, afine, zmeură).
- Există și variante fierte, mai ușoare, servite cu zahăr și scorțișoară.
Plăcintă cu mere
- Desert clasic preparat din aluat fraged sau foi subțiri.
- Umplutura este făcută din mere rase, zahăr și scorțișoară.
- Uneori se adaugă nuci tocate sau stafide în umplutură.
- Este coptă până ce devine aurie, apoi pudrată cu zahăr.
- Se servește caldă sau rece, simplă sau cu frișcă.
- Foarte populară în toate regiunile țării, inclusiv în școli.

===== acasa.html =====
<html><body><h3>Explorați cele mai iubite rețete românești, adunate cu grijă din toate colțurile
țării.</h3></body></html>

===== banner.html =====
<html><body bgcolor="#FFF0F5"><h2 align="center">Bine ați venit pe site-ul nostru de rețete
tradiționale!</h2></body></html>

===== contact.html =====
<html><body><h3>Contact:</h3>
<p>Email: retetetraditionale@example.com</p>
<p>Telefon: 0722 000 000</p>
</body></html>

===== deserturi.html =====
<html>
<head>
<title>Deserturi</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<h2>Deserturi Tradiționale</h2>
<h3>Cozonac</h3>
<p>Cozonacul este un desert tradițional care se prepară cu ocazia sărbătorilor. Își are rădăcinile în
gospodăriile românești din secolul XIX și este făcut din aluat dospit, umplut cu nucă, cacao, rahat sau
mac.</p>
<h3>Papanași</h3>
<p>Papanașii sunt gogoși tradiționale din brânză de vaci, prăjite sau fierte, servite cu smântână și
dulceață. Se consumă din secolul XX și sunt specifice zonei Moldova.</p>
<h3>Plăcintă cu mere</h3>
<p>Plăcinta cu mere este un desert simplu și foarte răspândit în gospodăriile românești. Se prepară din
foi de aluat și un amestec de mere rase, scorțișoară și zahăr caramelizat.</p>
</body>
</html>

===== galerie.html =====
<html>
<head>
<title>Galerie Foto</title>
<link rel="stylesheet" href="style.css">
<style>
.slideshow-container {
position: relative;
max-width: 600px;
margin: auto;
}
.slides {
display: none;
width: 100%;
}
.prev, .next {
cursor: pointer;
position: absolute;
top: 50%;
width: auto;
padding: 16px;
margin-top: -22px;
color: white;
font-weight: bold;
font-size: 18px;
transition: 0.6s ease;
border-radius: 0 3px 3px 0;
user-select: none;
background-color: rgba(0,0,0,0.5);
}
.next {
right: 0;
border-radius: 3px 0 0 3px;
}
.prev:hover, .next:hover {
background-color: rgba(0,0,0,0.8);
}
</style>
</head>
<body>
<h2>Galerie Foto</h2>
<div class="slideshow-container">
<img class="slides" src="galerie1.jpg" alt="Sarmale">
<img class="slides" src="galerie2.jpg" alt="Cozonac">
<img class="slides" src="galerie3.jpg" alt="Papanași">
<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>
</div>
<script>
let slideIndex = 0;
showSlides();
function showSlides() {
let i;
let slides = document.getElementsByClassName("slides");
for (i = 0; i < slides.length; i++) {
slides[i].style.display = "none";
}
slideIndex++;
if (slideIndex > slides.length) {slideIndex = 1}
slides[slideIndex-1].style.display = "block";
setTimeout(showSlides, 3000); // Change image every 3 seconds
}
function plusSlides(n) {
slideIndex += n - 1;
showSlides();
}
</script>
</body>
</html>

===== index.html =====
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="style.css">
<title>Rețete Culinare Tradiționale</title>
<meta charset="UTF-8">
</head>
<frameset rows="15%,15%,70%">
<frame src="sus.html" name="C1">
<frame src="banner.html" name="C2">
<frame src="acasa.html" name="C3">
</frameset>
</html>

===== retete.html =====
<html>
<head>
<title>Rețete Principale</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<h2>Rețete Principale</h2>
<h3>Sarmale</h3>
<p>Originea sarmalelor este influențată de tradițiile otomane. Acestea sunt făcute din foi de varză
murată umplute cu un amestec de carne tocată (de porc sau amestec porc-vită), orez, ceapă și
condimente.</p>
<h3>Ciorbă de burtă</h3>
<p>Ciorba de burtă este o specialitate românească ce datează din perioada medievală. Este preparată
din burtă de vită fiartă, oase de vită pentru supă, oțet, smântână și ouă, și este servită cu ardei iute și
mujdei.</p>
<h3>Mămăligă cu brânză</h3>
<p>Mămăliga este un preparat tradițional din porumb, de origine dacică. Este servită alături de brânză
telemea și smântână, uneori completată cu ouă prăjite sau cârnați.</p>
</body>
</html>

===== style.css =====
body {
font-family: Arial, sans-serif;
background-color: #fffaf0;
color: #333;
margin: 20px;
}
h2, h3 {
color: #8B0000;
text-align: center;
}
ul {
list-style-type: square;
padding-left: 20px;
}
a {
margin: 0 10px;
color: #006400;
text-decoration: none;
}
a:hover {
text-decoration: underline;
}

===== sus.html =====
<html>
<body bgcolor="#FFFAF0">
<table width="100%">
<tr>
<td><img src="logo.jpg" height="50" /></td>
<td><script>
var azi=new Date();
var s="";
if(azi.getHours()<12) s="Bună dimineața!<br>";
else if(azi.getHours()<18) s="Bună ziua!<br>";
else s="Bună seara!<br>";
document.write(s);
document.write(azi.getDate()+"."+(azi.getMonth()+1)+"."+azi.getFullYear());
</script></td>
<td>
<a href="acasa.html" target="C3">Acasă</a> |
<a href="retete.html" target="C3">Rețete</a> |
<a href="deserturi.html" target="C3">Deserturi</a> |
<a href="contact.html" target="C3">Contact</a> | <a href="galerie.html" target="C3">Galerie</a>
</td>
</tr>
</table>
</body>
</html>
