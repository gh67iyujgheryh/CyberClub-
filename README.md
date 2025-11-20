<html lang="kk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CyberClub — Компьютерлік клуб</title>
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
<style>
/* ===== Global ===== */
*{margin:0;padding:0;box-sizing:border-box;font-family:'Orbitron',sans-serif;}
body{overflow-x:hidden;background: linear-gradient(135deg, #0b0c10, #1f2833, #45a29e);background-size: 400% 400%;animation: gradientBG 15s ease infinite;}
@keyframes gradientBG{0%{background-position:0% 50%;}50%{background-position:100% 50%;}100%{background-position:0% 50%;}}
a{text-decoration:none;}

/* ===== Header ===== */
header{display:flex;justify-content:space-between;align-items:center;padding:20px 50px;background:rgba(0,0,0,0.8);position:sticky;top:0;z-index:10;}
header .logo{color:#66fcf1;font-size:30px;text-shadow:0 0 10px #66fcf1,0 0 20px #45a29e;}
nav a{margin-left:25px;color:#fff;font-weight:700;transition:0.3s;}
nav a:hover{color:#45a29e;text-shadow:0 0 10px #45a29e;}

/* ===== Hero ===== */
.hero{
  height:90vh;
  display:flex;
  justify-content:center;
  align-items:center;
  text-align:center;
  color:#66fcf1;
  background: url('https://sxodim.com/uploads/images/2023/07/21/355368e815a433f9a4755d2675c68a56.jpg') center/cover no-repeat;
  position:relative;
}
.hero .overlay{
  background: rgba(0,0,0,0.5);
  padding: 40px;
  border-radius: 20px;
}
.hero h1{
  font-size:60px;
  text-shadow:0 0 20px #66fcf1,0 0 40px #45a29e;
}
.hero p{
  font-size:24px;
  margin-top:20px;
  text-shadow:0 0 10px #66fcf1;
}
.hero button{
  margin-top:30px;
  padding:15px 40px;
  font-size:20px;
  color:#fff;
  border:none;
  border-radius:12px;
  background:#45a29e;
  box-shadow:0 0 10px #66fcf1;
  cursor:pointer;
  transition:0.3s;
}
.hero button:hover{
  box-shadow:0 0 20px #66fcf1,0 0 40px #45a29e;
  transform:scale(1.05);
}

/* ===== About / Club Section ===== */
.about{padding:70px 20px;text-align:center;color:#fff;}
.about h2{font-size:42px;margin-bottom:20px;color:#66fcf1;text-shadow:0 0 10px #66fcf1;}
.about p{max-width:800px;margin:auto;font-size:18px;line-height:1.6;}

/* ===== Games / Facilities ===== */
.games{padding:70px 20px;text-align:center;color:#fff;}
.games h2{font-size:42px;margin-bottom:40px;color:#66fcf1;text-shadow:0 0 10px #66fcf1;}
.grid{display:flex;flex-wrap:wrap;justify-content:center;gap:30px;}
.game{width:280px;background:rgba(0,0,0,0.7);border-radius:20px;overflow:hidden;box-shadow:0 0 15px #66fcf1;transition:0.5s;}
.game img{width:100%;height:180px;object-fit:cover;}
.game h3{color:#45a29e;margin:15px 0 5px 0;}
.game p{color:#fff;font-size:14px;margin-bottom:15px;}
.game:hover{transform:scale(1.05);box-shadow:0 0 25px #66fcf1,0 0 40px #45a29e;}

/* ===== Pricing ===== */
.pricing{padding:70px 20px;text-align:center;color:#fff;background:rgba(0,0,0,0.5);}
.pricing h2{font-size:42px;margin-bottom:40px;color:#66fcf1;text-shadow:0 0 10px #66fcf1;}
.pricing .plan{display:inline-block;width:250px;background:rgba(20,20,20,0.8);padding:30px;margin:15px;border-radius:20px;box-shadow:0 0 15px #66fcf1;transition:0.3s;}
.plan h3{color:#45a29e;margin-bottom:10px;}
.plan p{color:#fff;font-size:16px;margin-bottom:15px;font-weight:bold;}
.plan:hover{transform:scale(1.05);box-shadow:0 0 25px #66fcf1,0 0 40px #45a29e;}

/* ===== Contact ===== */
.contact{padding:70px 20px;text-align:center;color:#fff;}
.contact h2{font-size:42px;margin-bottom:20px;color:#66fcf1;text-shadow:0 0 10px #66fcf1;}
.contact p,a{font-size:18px;margin-bottom:10px;color:#fff;transition:0.3s;}
.contact a:hover{color:#45a29e;text-shadow:0 0 10px #45a29e;}

/* ===== Order Form ===== */
.order{padding:60px 20px;text-align:center;background:rgba(0,0,0,0.8);}
.order h2{font-size:40px;color:#66fcf1;margin-bottom:30px;text-shadow:0 0 10px #66fcf1;}
.order-box{max-width:500px;margin:auto;}
input,select,textarea{width:100%;padding:14px;margin-bottom:15px;border-radius:10px;border:2px solid #66fcf1;background:rgba(0,0,0,0.5);color:#fff;font-size:16px;}
button.order-btn{width:100%;padding:15px 25px;border:none;border-radius:12px;background:#45a29e;color:#fff;font-size:18px;cursor:pointer;box-shadow:0 0 10px #66fcf1,0 0 20px #45a29e;transition:0.3s;}
button.order-btn:hover{box-shadow:0 0 20px #45a29e,0 0 40px #66fcf1;transform:scale(1.05);}

/* ===== Footer ===== */
footer{padding:20px;text-align:center;background:rgba(0,0,0,0.9);color:#66fcf1;font-weight:bold;text-shadow:0 0 5px #66fcf1;}
</style>
</head>
<body>

<header>
  <div class="logo">CyberClub</div>
  <nav>
    <a href="#about">Клуб</a>
    <a href="#games">Ойындар</a>
    <a href="#pricing">Бағалар</a>
    <a href="#contact">Байланыс</a>
    <a href="#order">Брондау</a>
  </nav>
</header>

<section class="hero">
  <div class="overlay">
    <h1>CyberClub — Технологиялық ойын орталығы</h1>
    <p>Жоғары сапалы жабдықтар, заманауи атмосфера</p>
    <button onclick="location.href='#games'">Ойындарды көру</button>
  </div>
</section>

<section class="about" id="about">
  <h2>Біз туралы</h2>
  <p>CyberClub — компьютерлік ойындар мен киберспорт үшін заманауи клуб. Жоғары сапалы компьютерлер, VR жабдықтары, жарық және дыбыс эффектілері бар. Достарыңызбен көңілді уақыт өткізуге тамаша орын.</p>
</section>

<section class="games" id="games">
  <h2>Жабдықтар мен ойындар</h2>
  <div class="grid">
    <div class="game">
      <img src="https://chocolife.object.pscloud.io/static/upload/images/deal/for_deal_page/56000/55688/660x305/202206300464862bd79002071d.jpeg?1758091480">
      <h3>PC ойын залы</h3>
      <p>Топтық және жеке ойындар үшін жоғары өнімді компьютерлер.</p>
    </div>
    <div class="game">
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/ee/Reality_check_ESA384313.jpg">
      <h3>VR ойын бөлмесі</h3>
      <p>Қызықты және иммерсивті виртуалды шынайылық тәжірибесі.</p>
    </div>
    <div class="game">
      <img src="https://play-lh.googleusercontent.com/RLUIjdqGvj5eacjXsfNTNiNSIxnxjALS-HorVW2706bCF5ywGMHJlZsRAFJwfxpXkdA=w526-h296-rw">
      <h3>Sim Racing</h3>
      <p>Жарыс симуляторлары және брутальді көлік тәжірибесі.</p>
    </div>
  </div>
</section>

<section class="pricing" id="pricing">
  <h2>Баға пакеттері</h2>
  <div class="plan">
    <h3>1 сағат</h3>
    <p>1500 ₸</p>
  </div>
  <div class="plan">
    <h3>3 сағат</h3>
    <p>4000 ₸</p>
  </div>
  <div class="plan">
    <h3>Толық күн</h3>
    <p>12000 ₸</p>
  </div>
</section>

<section class="contact" id="contact">
  <h2>Байланыс</h2>
  <p>📞 Телефон: <a href="tel:+77000000000">+7 700 000 00 00</a></p>
  <p>📱 WhatsApp: <a href="https://wa.me/77000000000" target="_blank">Хабарласу</a></p>
  <p>📸 Instagram: <a href="#" target="_blank">@cyberclub_kz</a></p>
  <p>📍 Адрес: Алматы қ., Назарбаев даңғылы 120</p>
</section>

<section class="order" id="order">
  <h2>Брондау / Сұрақ қалдыру</h2>
  <div class="order-box">
    <input type="text" placeholder="Атыңыз" required>
    <input type="tel" placeholder="Телефон нөмірі" required>
    <select>
      <option>Қызмет таңдаңыз</option>
      <option>PC ойын залы</option>
      <option>VR бөлме</option>
      <option>Sim Racing</option>
    </select>
    <textarea rows="4" placeholder="Қосымша ақпарат"></textarea>
    <button class="order-btn" onclick="alert('Сіздің сұрауыңыз қабылданды! Менеджер хабарласады 😊')">Жіберу</button>
  </div>
</section>

<footer>
  © 2025 CyberClub — Компьютерлік клуб
</footer>

</body>
</html>
