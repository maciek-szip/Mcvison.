<!doctype html>
<html lang="pl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>MCVision • Grand Final</title>

<style>
:root{
 --bg:#05050b;
 --panel:#0d0d18;
 --panel2:#131326;
 --text:#fff;
 --muted:#a9a8c2;
 --pink:#ff197f;
 --violet:#7b4dff;
 --cyan:#00e5ff;
 --gold:#ffd76a;
 --line:#292943;
}

*{box-sizing:border-box}

html{
 scroll-behavior:smooth;
}

body{
 margin:0;
 background:var(--bg);
 color:var(--text);
 font-family:Inter,system-ui,-apple-system,Segoe UI,sans-serif;
}

a{
 color:inherit;
 text-decoration:none;
}

header{
 position:fixed;
 top:0;
 left:0;
 right:0;
 z-index:50;
 background:#05050bcc;
 backdrop-filter:blur(16px);
 border-bottom:1px solid #ffffff10;
}

.nav{
 max-width:1220px;
 margin:auto;
 padding:18px 22px;
 display:flex;
 align-items:center;
 justify-content:space-between;
}

.logo{
 font-size:26px;
 font-weight:1000;
 letter-spacing:-1px;
}

.navlinks{
 display:flex;
 gap:24px;
}

.navlinks a{
 font-size:12px;
 font-weight:900;
 color:#aaa9c3;
}

.navlinks a:hover{
 color:white;
}

.hero{
 min-height:720px;
 display:grid;
 place-items:center;
 text-align:center;
 position:relative;
 overflow:hidden;
 background:
 radial-gradient(circle at 50% 20%,#7b4dff44,transparent 30%),
 radial-gradient(circle at 20% 80%,#ff197f22,transparent 30%),
 #05050b;
}

.hero:before{
 content:"";
 position:absolute;
 width:700px;
 height:700px;
 border-radius:50%;
 border:1px solid #ffffff12;
 animation:spin 25s linear infinite;
}

.hero:after{
 content:"";
 position:absolute;
 inset:0;
 background:
 radial-gradient(circle,#ffffff 1px,transparent 2px) 0 0/90px 90px;
 opacity:.07;
}

@keyframes spin{
 from{transform:rotate(0)}
 to{transform:rotate(360deg)}
}

.hero-inner{
 position:relative;
 z-index:2;
 padding:120px 20px 70px;
 max-width:1000px;
}

.current{
 display:inline-block;
 background:#ff174f22;
 border:1px solid #ff174f88;
 color:#ff5479;
 padding:10px 18px;
 border-radius:999px;
 font-size:12px;
 font-weight:1000;
 letter-spacing:.12em;
 margin-bottom:24px;
 box-shadow:0 0 25px #ff174f22;
}

.eyebrow{
 color:var(--cyan);
 font-weight:900;
 letter-spacing:.2em;
 font-size:12px;
 margin-bottom:20px;
}

h1{
 font-size:clamp(70px,15vw,180px);
 line-height:.8;
 margin:0;
 letter-spacing:-.08em;
 text-shadow:
 0 0 25px #ff197f88,
 0 0 80px #7b4dff55;
}

h1 span{
 color:var(--pink);
}

.hero-sub{
 max-width:720px;
 margin:35px auto;
 color:var(--muted);
 font-size:18px;
 line-height:1.7;
}

.cta{
 display:inline-flex;
 padding:15px 25px;
 border-radius:999px;
 background:linear-gradient(90deg,var(--pink),var(--violet));
 font-weight:1000;
 box-shadow:0 0 35px #ff197f44;
}

.stage{
 margin-top:-90px;
 padding:0 22px 80px;
 position:relative;
 z-index:3;
}

.stagebox{
 max-width:1220px;
 height:400px;
 margin:auto;
 border-radius:35px;
 overflow:hidden;
 position:relative;
 background:
 radial-gradient(circle at 50% 100%,#ff197f33,transparent 25%),
 linear-gradient(#15152b,#05050b);
 border:1px solid #ffffff16;
 box-shadow:0 30px 100px #000;
}

.stagebox:after{
 content:"";
 position:absolute;
 left:8%;
 right:8%;
 bottom:0;
 height:120px;
 background:
 radial-gradient(ellipse,#7b4dff66,transparent 65%);
 filter:blur(15px);
}

.spot{
 position:absolute;
 width:220px;
 height:600px;
 background:linear-gradient(transparent,#ff197f33,transparent);
 transform-origin:top;
 filter:blur(8px);
}

.s1{
 left:10%;
 transform:rotate(25deg);
 animation:beam 4s infinite alternate;
}

.s2{
 left:40%;
 transform:rotate(-8deg);
 animation:beam 3s infinite alternate-reverse;
}

.s3{
 right:10%;
 transform:rotate(-25deg);
 animation:beam 5s infinite alternate;
}

@keyframes beam{
 from{opacity:.3}
 to{opacity:.9}
}

.stage-content{
 position:absolute;
 inset:0;
 display:grid;
 place-items:center;
 align-content:center;
 text-align:center;
 z-index:2;
}

.stage-logo{
 font-size:clamp(35px,7vw,85px);
 font-weight:1000;
 letter-spacing:-.06em;
 text-shadow:0 0 35px #fff5;
}

.stage-logo i{
 color:var(--pink);
 font-style:normal;
}

.lights{
 display:flex;
 gap:20px;
 margin-top:30px;
}

.light{
 width:10px;
 height:10px;
 background:white;
 border-radius:50%;
 box-shadow:
 0 0 15px white,
 0 0 35px var(--cyan);
 animation:pulse 1.4s infinite alternate;
}

.light:nth-child(2){animation-delay:.2s}
.light:nth-child(3){animation-delay:.4s}
.light:nth-child(4){animation-delay:.6s}
.light:nth-child(5){animation-delay:.8s}

@keyframes pulse{
 from{opacity:.2;transform:scale(.7)}
 to{opacity:1;transform:scale(1.5)}
}

.section{
 max-width:1220px;
 margin:auto;
 padding:80px 22px;
}

.head{
 display:flex;
 justify-content:space-between;
 align-items:end;
 gap:20px;
 margin-bottom:30px;
}

.head h2{
 font-size:clamp(32px,5vw,60px);
 margin:0;
 letter-spacing:-.05em;
}

.head p{
 color:var(--muted);
}

.controls input{
 background:#111122;
 color:white;
 border:1px solid #ffffff18;
 padding:14px 18px;
 border-radius:15px;
 outline:none;
 width:280px;
}

.cards{
 display:grid;
 grid-template-columns:repeat(4,1fr);
 gap:16px;
}

.card{
 min-height:390px;
 display:flex;
 flex-direction:column;
 justify-content:space-between;
 padding:22px;
 border-radius:25px;
 background:
 linear-gradient(145deg,#15152b,#0b0b15);
 border:1px solid #ffffff10;
 position:relative;
 overflow:hidden;
 transition:.3s;
}

.card:hover{
 transform:translateY(-8px);
 border-color:#ff197f66;
 box-shadow:0 20px 60px #ff197f18;
}

.card:before{
 content:"";
 position:absolute;
 width:180px;
 height:180px;
 background:#7b4dff22;
 border-radius:50%;
 filter:blur(40px);
 right:-70px;
 top:-70px;
}

.ed{
 display:flex;
 justify-content:space-between;
 align-items:center;
 position:relative;
 z-index:2;
}

.ednum{
 font-size:11px;
 font-weight:1000;
 letter-spacing:.12em;
 color:#aaa9c3;
}

.flag{
 font-size:38px;
 filter:drop-shadow(0 0 10px #fff2);
}

.country{
 font-size:28px;
 font-weight:1000;
 margin-top:35px;
 position:relative;
}

.winner{
 color:var(--gold);
 font-size:12px;
 font-weight:1000;
 margin-top:8px;
}

.song{
 color:#c6c5d9;
 margin-top:22px;
 font-weight:700;
}

.score{
 margin-top:30px;
}

.scoretop{
 display:flex;
 justify-content:space-between;
 color:#88879f;
 font-size:11px;
 font-weight:1000;
}

.scoretop b{
 color:white;
 font-size:25px;
}

.bar{
 height:5px;
 background:#ffffff0d;
 border-radius:20px;
 margin-top:8px;
 overflow:hidden;
}

.fill{
 height:100%;
 background:linear-gradient(90deg,var(--pink),var(--violet));
 border-radius:20px;
 box-shadow:0 0 15px #ff197f88;
}

.actions{
 display:flex;
 gap:8px;
 margin-top:20px;
}

.play,
.details{
 border:0;
 padding:11px 13px;
 border-radius:12px;
 font-size:11px;
 font-weight:1000;
 cursor:pointer;
}

.play{
 background:linear-gradient(90deg,var(--pink),var(--violet));
 color:white;
}

.details{
 background:#ffffff0d;
 color:white;
}

.player{
 position:fixed;
 bottom:20px;
 left:50%;
 transform:translateX(-50%);
 z-index:55;
 width:min(650px,calc(100% - 30px));
 background:#10101ddd;
 border:1px solid #ffffff16;
 backdrop-filter:blur(18px);
 border-radius:22px;
 padding:12px;
 box-shadow:0 20px 80px #000;
}

.playerrow{
 display:flex;
 align-items:center;
 gap:14px;
}

.disc{
 width:48px;
 height:48px;
 border-radius:50%;
 background:
 radial-gradient(circle,#fff 0 5px,transparent 6px),
 conic-gradient(var(--pink),var(--violet),var(--cyan),var(--pink));
 animation:disc 3s linear infinite;
 flex:none;
}

.disc.paused{
 animation-play-state:paused;
}

@keyframes disc{
 to{transform:rotate(360deg)}
}

.ptext{
 flex:1;
 min-width:0;
}

.ptext strong{
 display:block;
 white-space:nowrap;
 overflow:hidden;
 text-overflow:ellipsis;
}

.ptext small{
 color:var(--muted);
}

.pbtn{
 border:0;
 background:white;
 color:#08080e;
 width:42px;
 height:42px;
 border-radius:50%;
 font-size:17px;
 cursor:pointer;
}

footer{
 border-top:1px solid var(--line);
 padding:55px 22px 100px;
 text-align:center;
 color:var(--muted);
 font-size:13px;
}

.modal{
 position:fixed;
 inset:0;
 z-index:60;
 background:#000b;
 display:none;
 place-items:center;
 padding:20px;
}

.modal.show{
 display:grid;
}

.modalbox{
 max-width:540px;
 width:100%;
 background:#111122;
 border:1px solid #ffffff22;
 border-radius:25px;
 padding:26px;
 box-shadow:0 30px 100px #000;
}

.close{
 float:right;
 background:#ffffff0d;
 color:white;
 border:0;
 border-radius:10px;
 padding:7px 10px;
 cursor:pointer;
}

.scorearchive{
 padding:72px 22px 30px;
 position:relative;
}

.archiveHead{
 max-width:1220px;
 margin:0 auto 24px;
 display:flex;
 justify-content:space-between;
 gap:20px;
 align-items:end;
 flex-wrap:wrap;
}

.archiveKicker{
 color:var(--pink);
 font-weight:900;
 letter-spacing:.12em;
 text-transform:uppercase;
 font-size:12px;
}

.archiveHead h2{
 font-size:clamp(30px,5vw,56px);
 margin:7px 0 0;
 letter-spacing:-.04em;
}

.archiveHead p{
 color:var(--muted);
 max-width:700px;
 margin:8px 0 0;
}

.archiveTabs{
 max-width:1220px;
 margin:0 auto 18px;
 display:flex;
 gap:9px;
 flex-wrap:wrap;
}

.archiveTab{
 border:1px solid #ffffff18;
 background:#101021;
 color:#b9b8d1;
 padding:10px 14px;
 border-radius:999px;
 cursor:pointer;
 font-weight:900;
 transition:.2s;
}

.archiveTab:hover,
.archiveTab.active{
 background:linear-gradient(90deg,#ff197f,#7b4dff);
 color:#fff;
 border-color:transparent;
 box-shadow:0 0 20px #7b4dff44;
}

.archivePanel{
 max-width:1220px;
 margin:auto;
 background:linear-gradient(135deg,#0d0d19ee,#17132bee);
 border:1px solid #ffffff12;
 border-radius:26px;
 overflow:hidden;
 box-shadow:0 25px 70px #0008;
}

.archiveTop{
 padding:22px 24px;
 border-bottom:1px solid #ffffff10;
 display:flex;
 align-items:center;
 justify-content:space-between;
 gap:16px;
 flex-wrap:wrap;
}

.archiveTitle{
 font-size:22px;
 font-weight:1000;
}

.archiveMeta{
 color:var(--muted);
 font-size:13px;
}

.tableWrap{
 overflow:auto;
 max-height:620px;
}

.scoreTable{
 width:100%;
 border-collapse:collapse;
 min-width:560px;
}

.scoreTable th{
 position:sticky;
 top:0;
 background:#111124f5;
 backdrop-filter:blur(10px);
 color:#aaa9c3;
 text-transform:uppercase;
 letter-spacing:.1em;
 font-size:11px;
 text-align:left;
 padding:14px 18px;
 z-index:2;
}

.scoreTable td{
 padding:13px 18px;
 border-top:1px solid #ffffff09;
 font-weight:700;
}

.scoreTable tr{
 transition:.2s;
}

.scoreTable tbody tr:hover{
 background:#ffffff07;
 transform:translateX(2px);
}

.scoreTable .pos{
 width:70px;
 color:#8e8da8;
 font-weight:1000;
}

.scoreTable .countryCell{
 display:flex;
 align-items:center;
 gap:10px;
}

.scoreTable .flagCell{
 font-size:23px;
 filter:drop-shadow(0 0 7px #ffffff20);
}

.scoreTable .pts{
 text-align:right;
 font-size:18px;
}

.scoreTable .champ td{
 background:linear-gradient(90deg,#ffd76a12,transparent);
 color:#fff;
}

.scoreTable .champ .pos{
 color:var(--gold);
}

.scoreTable .champ .pts{
 color:var(--gold);
 text-shadow:0 0 12px #ffd76a66;
}

.archiveNote{
 padding:14px 20px;
 color:#85849d;
 font-size:12px;
 border-top:1px solid #ffffff0b;
}

@media(max-width:950px){
 .cards{
  grid-template-columns:repeat(2,1fr);
 }

 .hero{
  min-height:650px;
 }
}

@media(max-width:600px){
 .navlinks{
  display:none;
 }

 .cards{
  grid-template-columns:1fr;
 }

 .head{
  align-items:flex-start;
  flex-direction:column;
 }

 .stage{
  margin-top:-70px;
 }

 h1{
  letter-spacing:-5px;
 }
}
</style>
</head>

<body>

<div id="app">

<header>
<div class="nav">

<div class="logo">
MC<span style="color:#ff197f">Vision</span> ✦
</div>

<div class="navlinks">
<a href="#winners">WINNERS</a>
<a href="#ranking">POINTS</a>
<a href="#tables">TABLES</a>
<a href="#about">ABOUT</a>
</div>

</div>
</header>


<section class="hero">

<div class="hero-inner">

<div class="current">
🔴 NA ŻYWO • OBECNIE TRWA 9. EDYCJA
</div>

<div class="eyebrow">
MCVision • Grand Final • Hall of Fame
</div>

<h1>
MC<span>VISION</span>
</h1>

<div class="hero-sub">
Największa noc muzyki. Osiem edycji za nami,
a teraz trwa 9. edycja MCVision — walka o kolejne
zwycięstwo właśnie się rozkręca.
</div>

<a class="cta" href="#winners">
🏆 ZOBACZ ZWYCIĘZCÓW
</a>

</div>

</section>


<section class="stage">

<div class="stagebox">

<div class="spot s1"></div>
<div class="spot s2"></div>
<div class="spot s3"></div>

<div class="stage-content">

<div class="stage-logo">
WELCOME TO <i>MCVISION</i>
</div>

<div class="lights">
<i class="light"></i>
<i class="light"></i>
<i class="light"></i>
<i class="light"></i>
<i class="light"></i>
</div>

<div style="margin-top:22px;color:#a9a8c2;font-weight:800;letter-spacing:2px">
THE WINNERS STAGE
</div>

</div>

</div>

</section>


<section class="section" id="winners">

<div class="head">

<div>
<h2>🏆 Zwycięzcy</h2>
<p>Każda edycja. Jeden zwycięzca. Jedna historia.</p>
</div>

<div class="controls">
<input id="search" placeholder="Szukaj zwycięzcy lub utworu…">
</div>

</div>

<div class="cards" id="cards"></div>

</section>


<section class="section" id="ranking">

<div class="head">

<div>
<h2>📊 Archiwum punktacji</h2>
<p>Punktacja wszystkich zwycięzców.</p>
</div>

</div>

<div id="rankingList"></div>

</section>


<section class="section" id="about">

<div style="max-width:760px">

<h2>MCVision</h2>

<p style="color:var(--muted);font-size:17px;line-height:1.8">

Fanowski konkurs inspirowany widowiskami muzycznymi.
Dane zwycięzców i tytuły zostały wpisane zgodnie z Twoją listą.
Przyciski odsłuchu prowadzą do wyszukiwarki YouTube,
dzięki czemu strona nie przechowuje chronionych nagrań.

</p>

</div>

</section>


<section class="scorearchive" id="tables">

<div class="archiveHead">

<div>

<div class="archiveKicker">
ARCHIWUM WYNIKÓW
</div>

<h2>
Pełne tabele punktacji
</h2>

<p>
Wyniki z przesłanych plansz zostały przepisane
do prawdziwych, responsywnych tabel HTML — bez
wklejania grafik. Kliknij edycję, aby przełączać finały.
</p>

</div>

</div>


<div class="archiveTabs" id="archiveTabs"></div>


<div class="archivePanel">

<div class="archiveTop">

<div class="archiveTitle" id="archiveTitle"></div>

<div class="archiveMeta" id="archiveMeta"></div>

</div>


<div class="tableWrap">

<table class="scoreTable">

<thead>

<tr>

<th>Miejsce</th>

<th>Kraj</th>

<th style="text-align:right">
Łączne punkty
</th>

</tr>

</thead>

<tbody id="archiveBody"></tbody>

</table>

</div>


<div class="archiveNote">
★ Zwycięzca jest wyróżniony.
Dane odwzorowują kolejność i punktację
widoczną na przesłanych tabelach.
</div>

</div>

</section>


<footer>
MCVision © 2026 • Fan project • Muzyka i materiały należą do ich właścicieli.
</footer>


<div class="player">

<div class="playerrow">

<div class="disc" id="disc"></div>

<div class="ptext">

<strong id="now">
MCVision • wybierz utwór
</strong>

<small>
Odtwarzacz demonstracyjny — kliknij ▶ przy zwycięzcy,
aby otworzyć odsłuch.
</small>

</div>

<button class="pbtn" id="pause">
▶
</button>

</div>

</div>


<div class="modal" id="modal">

<div class="modalbox">

<button class="close" id="close">
✕
</button>

<div id="modalContent"></div>

</div>

</div>

</div>


<script>

const archiveTables = [

{
title:"Edycja 1",
meta:"Grand Final",
rows:[
["🇹🇳","Tunisia",329],
["🇳🇬","Nigeria",314],
["🇪🇬","Egypt",283],
["🇲🇺","Mauritius",264],
["🇲🇦","Morocco",250],
["🇨🇮","Ivory Coast",220],
["🇸🇳","Senegal",214],
["🇺🇬","Uganda",214],
["🇧🇼","Botswana",198],
["🇦🇴","Angola",188],
["🇧🇫","Burkina Faso",184],
["🇹🇿","Tanzania",174],
["🇹🇬","Togo",160],
["🇬🇭","Ghana",159],
["🇿🇲","Zambia",141],
["🇰🇪","Kenya",125],
["🇩🇿","Algeria",124],
["🇸🇿","Eswatini",111],
["🇨🇲","Cameroon",85],
["🇨🇩","DR Congo",85]
]
},

{
title:"Edycja 2",
meta:"Afcvision 2027 • Grand Final",
rows:[
["🇲🇹","Malta",456],
["🇨🇬","Congo",351],
["🇰🇪","Kenya",294],
["🇲🇬","Madagascar",205],
["🇪🇬","Egypt",182],
["🇦🇴","Angola",162],
["🇹🇬","Togo",139],
["🇧🇼","Botswana",133],
["🇳🇬","Nigeria",133],
["🇹🇳","Tunisia",118],
["🇩🇿","Algeria",111],
["🇲🇱","Mali",104],
["🇳🇦","Namibia",99],
["🇧🇯","Benin",95],
["🇷🇼","Rwanda",88],
["🇸🇳","Senegal",87],
["🇲🇺","Mauritius",78],
["🇲🇦","Morocco",76],
["🇹🇿","Tanzania",67],
["🇸🇦","Saudi Arabia",63],
["🇿🇲","Zambia",57],
["🇱🇸","Lesotho",45],
["🇨🇩","DR Congo",34],
["🇺🇬","Uganda",28],
["🇨🇻","Cape Verde",0]
]
},

{
title:"Edycja 3",
meta:"Eurovision 2026 • Grand Final",
rows:[
["🇹🇿","Tanzania",206],
["🇲🇺","Mauritius",186],
["🇩🇯","Djibouti",178],
["🇩🇿","Algeria",176],
["🇲🇬","Madagascar",176],
["🇺🇬","Uganda",168],
["🇲🇼","Malawi",163],
["🇿🇦","South Africa",151],
["🇸🇳","Senegal",150],
["🇰🇪","Kenya",120],
["🇪🇸","Spain",93],
["🇫🇷","France",87],
["🇪🇹","Ethiopia",83],
["🇲🇻","Maldives",51]
]
},

{
title:"Edycja 4",
meta:"Eurovision 2017 • Grand Final",
rows:[
["🇺🇬","Uganda",320],
["🇸🇳","Senegal",290],
["🇦🇴","Angola",250],
["🇲🇺","Mauritius",237],
["🇧🇷","Brazil",230],
["🇲🇹","Malta",230],
["🇲🇦","Morocco",226],
["🇬🇭","Ghana",222],
["🇳🇬","Nigeria",220],
["🇹🇿","Tanzania",184],
["🇲🇱","Mali",183],
["🇿🇦","South Africa",183],
["🇨🇲","Cameroon",178],
["🇩🇿","Algeria",156],
["🇨🇮","Ivory Coast",156],
["🇹🇳","Tunisia",156],
["🇪🇬","Egypt",151],
["🇿🇼","Zimbabwe",148],
["🇬🇷","Greece",136],
["🇨🇩","DR Congo",123],
["🇰🇪","Kenya",105],
["🇪🇹","Ethiopia",40]
]
},

{
title:"Edycja 5",
meta:"Eurovision 2026 • Grand Final",
rows:[
["🇦🇺","Australia",215],
["🇻🇪","Venezuela",206],
["🇯🇵","Japan",190],
["🇹🇳","Tunisia",156],
["🇹🇭","Thailand",152],
["🇨🇦","Canada",120],
["🇵🇱","Poland",116],
["🇺🇿","Uzbekistan",116],
["🇲🇬","Madagascar",108],
["🇳🇱","Netherlands",105],
["🇿🇦","South Africa",103],
["🇹🇷","Türkiye",84],
["🇨🇷","Costa Rica",79],
["🇫🇯","Fiji Islands",71],
["🇫🇴","Faroe Islands",50]
]
},

{
title:"Edycja 6",
meta:"Grand Final",
rows:[
["🇱🇺","Luxembourg",247],
["🇦🇲","Armenia",214],
["🇦🇺","Australia",203],
["🇱🇧","Lebanon",201],
["🇵🇱","Poland",190],
["🇨🇦","Canada",186],
["🇯🇲","Jamaica",183],
["🇳🇴","Norway",179],
["🇨🇾","Cyprus",166],
["🇳🇬","Nigeria",164],
["🇰🇷","South Korea",162],
["🇭🇷","Croatia",157],
["🇬🇶","Equatorial Guinea",156],
["🇬🇪","Georgia",156],
["🇨🇭","Switzerland",153],
["🇳🇿","New Zealand",142],
["🇱🇹","Lithuania",96]
]
},

{
title:"Edycja 7",
meta:"MCvision 2033 • Grand Final",
rows:[
["🇮🇹","Italy",416],
["🇹🇳","Tunisia",318],
["🇦🇹","Austria",314],
["🇦🇿","Azerbaijan",312],
["🇸🇲","San Marino",338],
["🇱🇺","Luxembourg",315],
["🇵🇭","Philippines",314],
["🇩🇰","Denmark",297],
["🇩🇪","Germany",289],
["🇨🇦","Canada",272],
["🇨🇿","Czechia",268],
["🇲🇹","Malta",248],
["🇺🇦","Ukraine",240],
["🇧🇬","Bulgaria",226],
["🇷🇸","Serbia",216],
["🇱🇧","Lebanon",206],
["🇬🇷","Greece",196],
["🇳🇦","Namibia",178],
["🇹🇷","Türkiye",167],
["🇷🇺","Russia",156],
["🇧🇪","Belgium",148],
["🇬🇧","England",121]
]
},

{
title:"Edycja 8",
meta:"MCvision 2034 • Grand Final",
rows:[
["🇪🇬","Egypt",386],
["🇮🇹","Italy",324],
["🇨🇷","Costa Rica",285],
["🇵🇱","Poland",279],
["🇰🇵","North Korea",232],
["🇨🇲","Cameroon",223],
["🇱🇺","Luxembourg",182],
["🇦🇺","Australia",206],
["🇸🇬","Singapore",198],
["🇬🇧","Northern Ireland",124],
["🇲🇹","Malta",92],
["🇫🇯","Fiji Islands",61]
]
}

];


let archiveIndex=0;


function renderArchiveTabs(){

 const el=document.getElementById("archiveTabs");

 el.innerHTML=archiveTables
 .map((t,i)=>`
 <button
 class="archiveTab ${i===archiveIndex?"active":""}"
 onclick="showArchive(${i})">
 ${t.title}
 </button>
 `)
 .join("");

}


function showArchive(i){

 archiveIndex=i;

 const t=archiveTables[i];

 document.getElementById("archiveTitle")
 .textContent=t.title;

 document.getElementById("archiveMeta")
 .textContent=
 t.meta+" • "+t.rows.length+" uczestników";


 document.getElementById("archiveBody").innerHTML=

 t.rows.map((r,j)=>`

 <tr class="${j===0?"champ":""}">

 <td class="pos">
 ${j+1}
 </td>

 <td>

 <div class="countryCell">

 <span class="flagCell">
 ${r[0]}
 </span>

 <span>
 ${r[1]}
 </span>

 </div>

 </td>

 <td class="pts">
 ${r[2]}
 
