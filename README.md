<!doctype html>
<html lang="fa" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#10152b">
<title>عددباز | بازی و ریاضی</title>
<style>
:root{--bg:#0b1020;--panel:#151d35;--panel2:#1b2644;--ink:#f6f7ff;--muted:#aab5d2;--cyan:#56e0e0;--yellow:#ffd166;--pink:#ff6b9a;--green:#71e6a2;--line:#2b385b;--shadow:0 18px 50px #02061766}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:radial-gradient(ellipse at 10% 0%,#233a68 0,transparent 38%),radial-gradient(ellipse at 100% 30%,#311e57 0,transparent 34%),var(--bg);color:var(--ink);font-family:Tahoma,"Segoe UI",Arial,sans-serif;min-height:100vh}button,input{font:inherit}button{cursor:pointer;border:0}.wrap{width:min(1120px,calc(100% - 32px));margin:auto}.topbar{display:flex;align-items:center;justify-content:space-between;padding:22px 0;gap:12px}.brand{display:flex;align-items:center;gap:10px;font-weight:900;font-size:1.25rem}.logo{display:grid;place-items:center;width:42px;height:42px;border-radius:14px;background:linear-gradient(135deg,var(--cyan),#8c7bff);color:#10152b;font-size:1.35rem;box-shadow:0 8px 22px #56e0e044}.tag{font-size:.8rem;color:var(--muted);border:1px solid var(--line);border-radius:99px;padding:8px 12px}.screen{display:none;animation:appear .25s ease}.screen.active{display:block}@keyframes appear{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}h1,h2,h3{margin:0 0 12px;line-height:1.45}h1{font-size:clamp(2rem,5vw,3.8rem);letter-spacing:-1px}h2{font-size:clamp(1.4rem,3vw,2rem)}h3{font-size:1.08rem}p{color:var(--muted);line-height:1.9;margin:0 0 16px}.hero{padding:clamp(24px,6vw,68px) 0 30px;display:grid;grid-template-columns:1.2fr .8fr;gap:28px;align-items:center}.eyebrow{display:inline-flex;align-items:center;gap:8px;color:var(--cyan);font-weight:800;font-size:.88rem;margin-bottom:14px}.hero h1 span{color:var(--cyan)}.hero-art{position:relative;min-height:260px;display:grid;place-items:center}.orb{width:min(280px,70vw);aspect-ratio:1;border-radius:35% 65% 57% 43%/42% 40% 60% 58%;background:linear-gradient(145deg,#56e0e033,#9d83ff33);border:1px solid #ffffff1c;display:grid;place-items:center;transform:rotate(-8deg)}.big-number{font-size:clamp(5rem,13vw,9rem);font-weight:1000;color:var(--yellow);text-shadow:0 12px 0 #d18b25,0 20px 45px #ffd16644;transform:rotate(8deg)}.float{position:absolute;padding:12px 17px;border-radius:16px;background:#202b4b;border:1px solid #3c4b73;box-shadow:var(--shadow);font-weight:900}.f1{top:15%;right:5%;color:var(--cyan)}.f2{bottom:12%;left:4%;color:var(--pink)}.choices{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px;margin:22px 0 58px}.choice{padding:25px;text-align:right;border-radius:24px;background:linear-gradient(145deg,#192440,#111a30);border:1px solid var(--line);box-shadow:var(--shadow);color:var(--ink);transition:.2s;min-height:190px}.choice:hover{transform:translateY(-4px);border-color:#56e0e088}.choice-icon{font-size:2rem;margin-bottom:18px;display:block}.choice p{font-size:.92rem;margin-bottom:14px}.arrow{color:var(--cyan);font-weight:900}.panel{background:linear-gradient(145deg,#17213c,#11182d);border:1px solid var(--line);border-radius:24px;padding:clamp(18px,3vw,30px);box-shadow:var(--shadow);margin:18px 0 28px}.section-head{display:flex;align-items:center;justify-content:space-between;gap:14px;flex-wrap:wrap;margin-bottom:18px}.btn{padding:12px 18px;border-radius:13px;background:var(--cyan);color:#0b1724;font-weight:900;transition:.18s}.btn:hover{filter:brightness(1.08);transform:translateY(-1px)}.btn.secondary{background:#263453;color:var(--ink);border:1px solid #3a4a70}.btn.pink{background:var(--pink);color:#25101a}.btn.small{padding:9px 12px;font-size:.88rem}.toolbar{display:flex;gap:9px;flex-wrap:wrap}.tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:20px}.tab{padding:10px 15px;border:1px solid var(--line);border-radius:12px;background:#10182d;color:var(--muted);font-weight:800}.tab.active{background:#263b55;border-color:var(--cyan);color:var(--cyan)}.calc-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px}.field label{display:block;color:var(--muted);font-size:.9rem;margin-bottom:8px}.field input{width:100%;padding:14px 15px;border:1px solid #3a496d;border-radius:13px;background:#0b1225;color:var(--ink);outline:none}.field input:focus{border-color:var(--cyan);box-shadow:0 0 0 3px #56e0e01a}.display{margin:16px 0 12px;padding:20px;border-radius:16px;background:#0b1225;border:1px solid var(--line);font-size:clamp(1.2rem,4vw,2rem);font-weight:900;overflow-wrap:anywhere}.display .result{color:var(--green)}.hint{font-size:.85rem;color:var(--muted);margin-top:10px}.keypad{display:grid;grid-template-columns:repeat(4,1fr);gap:9px;margin-top:14px}.key{background:#253252;color:var(--ink);padding:14px 5px;border-radius:12px;font-weight:900}.key.op{color:var(--cyan)}.key.equal{background:var(--cyan);color:#091522}.game-hud{display:flex;gap:10px;flex-wrap:wrap}.stat{padding:9px 13px;border:1px solid var(--line);border-radius:12px;color:var(--muted);background:#0d1529;font-size:.9rem}.stat b{color:var(--yellow)}.game-stage{position:relative;overflow:hidden;border-radius:20px;border:1px solid #3b4b73;background:linear-gradient(#111b3a,#283b5b 75%,#263453);height:clamp(260px,43vw,390px);margin:16px 0 14px;touch-action:manipulation}.stars{position:absolute;inset:0;background-image:radial-gradient(#fff 1px,transparent 1px),radial-gradient(#9deaff 1px,transparent 1px);background-size:47px 47px,71px 71px;background-position:4px 12px,27px 33px;opacity:.42}.moon{position:absolute;top:24px;left:9%;width:42px;height:42px;border-radius:50%;background:var(--yellow);box-shadow:0 0 30px #ffd16666}.hill{position:absolute;bottom:45px;left:-5%;width:110%;height:100px;background:#1d765e;border-radius:50% 50% 0 0/50% 50% 0 0;opacity:.8}.ground{position:absolute;bottom:0;left:0;right:0;height:48px;background:repeating-linear-gradient(135deg,#56d6a0 0 15px,#2a9b7c 15px 30px);border-top:5px solid #a0f4c8}.player{position:absolute;bottom:48px;left:16%;width:58px;height:58px;border-radius:16px;background:linear-gradient(145deg,#ffe08a,#ffad43);color:#32210b;font-size:1.7rem;font-weight:1000;display:grid;place-items:center;border:3px solid #fff2b0;box-shadow:0 8px 0 #b96a2d;z-index:3;transition:bottom .12s}.player.jump{bottom:135px}.enemy{position:absolute;bottom:52px;right:-70px;width:54px;height:54px;border-radius:15px;background:linear-gradient(145deg,#ff8bb0,#f3477d);color:#37101f;display:grid;place-items:center;font-size:1.35rem;font-weight:1000;border:2px solid #ffc2d5;box-shadow:0 7px 0 #a92e5a;z-index:2}.enemy.fly{animation:moveEnemy 3.3s linear forwards}@keyframes moveEnemy{from{right:-65px}to{right:110%}}.game-message{position:absolute;inset:0;display:grid;place-items:center;text-align:center;padding:24px;background:#091020aa;z-index:5}.game-message.hidden{display:none}.message-card{max-width:420px;padding:23px;border-radius:20px;background:#17213cf2;border:1px solid #53648b}.message-card p{margin-bottom:15px}.game-controls{display:flex;gap:10px;justify-content:center;flex-wrap:wrap}.footnote{border-top:1px solid #ffffff12;padding:22px 0 30px;color:#8390b1;font-size:.82rem;display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap}.toast{min-height:24px;color:var(--green);font-weight:800;font-size:.9rem;margin-top:10px}.math-note{padding:14px;border-radius:14px;background:#0e1830;border:1px dashed #465981;color:var(--muted);line-height:1.9;margin-top:14px}.math-note strong{color:var(--cyan)}.hidden{display:none!important}
@media(max-width:760px){.hero{grid-template-columns:1fr;text-align:center;padding-top:28px}.hero-art{min-height:210px;grid-row:1}.hero-copy{grid-row:2}.eyebrow{justify-content:center}.choices{grid-template-columns:1fr;margin-bottom:35px}.choice{min-height:unset}.calc-grid{grid-template-columns:1fr}.topbar{padding:15px 0}.tag{font-size:.72rem}.game-stage{height:290px}.player{left:12%}.footnote{justify-content:center;text-align:center}}
@media(prefers-reduced-motion:reduce){*,*::before,*::after{animation-duration:.01ms!important;transition-duration:.01ms!important;scroll-behavior:auto!important}}
</style>
</head>
<body>
<div class="wrap">
<header class="topbar">
  <div class="brand"><div class="logo">∑</div><span>عددباز</span></div>
  <div class="tag">بازی کن · کشف کن · یاد بگیر</div>
</header>
<main>
<section id="home" class="screen active">
  <div class="hero">
    <div class="hero-copy">
      <div class="eyebrow">✦ دنیای بازی و ریاضی</div>
      <h1>با عددها <span>بازی کن!</span></h1>
      <p>یک ماجراجویی کوچک برای ذهن‌های کنجکاو؛ وارد بازی شو، یا با ماشین‌حساب و ابزارهای بخش‌پذیری ریاضی را تمرین کن.</p>
    </div>
    <div class="hero-art" aria-hidden="true"><div class="orb"><div class="big-number">۲</div></div><div class="float f1">ب.م.م</div><div class="float f2">ک.م.م</div></div>
  </div>
  <div class="choices">
    <button class="choice" onclick="showScreen('game')"><span class="choice-icon">🎮</span><h2>ورود به بازی</h2><p>عدد قهرمان را هدایت کن، عددهای مناسب را جمع کن و از بقیه بپر!</p><span class="arrow">شروع ماجراجویی ←</span></button>
    <button class="choice" onclick="showScreen('math')"><span class="choice-icon">🧮</span><h2>بخش ریاضی</h2><p>ماشین‌حساب ساده، ب.م.م و ک.م.م دو عدد را سریع حساب کن.</p><span class="arrow">رفتن به ریاضی ←</span></button>
  </div>
</section>
<section id="math" class="screen">
  <div class="section-head"><div><div class="eyebrow">✦ ابزارهای هوشمند</div><h1 style="font-size:clamp(1.8rem,4vw,2.7rem)">آزمایشگاه ریاضی</h1><p>محاسبه کن و جواب را مرحله‌به‌مرحله ببین.</p></div><button class="btn secondary" onclick="showScreen('home')">← صفحهٔ اصلی</button></div>
  <div class="panel">
    <div class="tabs"><button class="tab active" data-tab="basic" onclick="switchTab('basic')">ماشین‌حساب</button><button class="tab" data-tab="gcd" onclick="switchTab('gcd')">ب.م.م و ک.م.م</button></div>
    <div id="basicPanel">
      <div class="field"><label for="calcDisplay">عبارت ریاضی</label><input id="calcDisplay" inputmode="decimal" autocomplete="off" placeholder="مثلاً 12 + 8 × 2" value=""></div>
      <div class="keypad">
        <button class="key" onclick="calcKey('7')">۷</button><button class="key" onclick="calcKey('8')">۸</button><button class="key" onclick="calcKey('9')">۹</button><button class="key op" onclick="calcKey('/')">÷</button>
        <button class="key" onclick="calcKey('4')">۴</button><button class="key" onclick="calcKey('5')">۵</button><button class="key" onclick="calcKey('6')">۶</button><button class="key op" onclick="calcKey('*')">×</button>
        <button class="key" onclick="calcKey('1')">۱</button><button class="key" onclick="calcKey('2')">۲</button><button class="key" onclick="calcKey('3')">۳</button><button class="key op" onclick="calcKey('-')">−</button>
        <button class="key" onclick="calcKey('0')">۰</button><button class="key" onclick="calcKey('.')">.</button><button class="key" onclick="clearCalc()">C</button><button class="key op" onclick="calcKey('+')">+</button>
      </div>
      <div class="toolbar" style="margin-top:12px"><button class="btn" onclick="calculate()">= محاسبه</button><button class="btn secondary" onclick="backspaceCalc()">⌫ پاک کردن آخر</button></div>
      <div id="calcResult" class="display">پاسخ: <span class="result">—</span></div><div id="calcToast" class="toast" role="status"></div>
      <p class="hint">می‌توانی عبارت را تایپ کنی یا از دکمه‌ها استفاده کنی. از پرانتز هم پشتیبانی می‌شود.</p>
    </div>
    <div id="gcdPanel" class="hidden">
      <div class="calc-grid">
        <div class="field"><label for="numA">عدد اول (عدد صحیح مثبت)</label><input id="numA" type="number" min="1" max="1000000000" step="1" value="24" inputmode="numeric"></div>
        <div class="field"><label for="numB">عدد دوم (عدد صحیح مثبت)</label><input id="numB" type="number" min="1" max="1000000000" step="1" value="36" inputmode="numeric"></div>
      </div>
      <div class="toolbar" style="margin-top:16px"><button class="btn" onclick="findGcdLcm()">حساب کن</button><button class="btn secondary" onclick="setPair(18,30)">نمونهٔ دیگر</button></div>
      <div class="display">ب.م.م = <span id="gcdResult" class="result">۱۲</span></div>
      <div class="display">ک.م.م = <span id="lcmResult" class="result">۷۲</span></div>
      <div class="math-note" id="mathSteps"><strong>روش:</strong> بزرگ‌ترین عددی که هر دو عدد بر آن بخش‌پذیرند، ب.م.م است. ک.م.م از رابطهٔ (عدد اول × عدد دوم) ÷ ب.م.م به دست می‌آید.</div>
      <div id="gcdToast" class="toast" role="status"></div>
    </div>
  </div>
  <div class="panel"><h3>یادآوری کوتاه</h3><p style="margin:0">**ب.م.م** یعنی بزرگ‌ترین مقسومٌ‌علیه مشترک. **ک.م.م** یعنی کوچک‌ترین مضرب مشترک. هر دو عدد باید عدد صحیح مثبت باشند.</p></div>
</section>
<section id="game" class="screen">
  <div class="section-head"><div><div class="eyebrow">✦ مرحلهٔ بخش‌پذیری</div><h1 style="font-size:clamp(1.8rem,4vw,2.7rem)">دوندهٔ عددی</h1><p>عدد قهرمان را با عددهای روی مسیر هماهنگ کن.</p></div><button class="btn secondary" onclick="showScreen('home')">← صفحهٔ اصلی</button></div>
  <div class="panel">
    <div class="section-head"><div class="game-hud"><div class="stat">قهرمان: <b id="heroNum">۲</b></div><div class="stat">امتیاز: <b id="score">۰</b></div><div class="stat">جان: <b id="lives">۳</b></div></div><button class="btn secondary small" onclick="resetGame()">↻ شروع دوباره</button></div>
    <div class="game-stage" id="gameStage">
      <div class="stars"></div><div class="moon"></div><div class="hill"></div><div class="ground"></div>
      <div class="player" id="player">۲</div>
      <div id="enemy" class="enemy">۸</div>
      <div class="game-message" id="gameMessage"><div class="message-card"><h2 id="messageTitle">آماده‌ای؟</h2><p id="messageText">عددهایی را بگیر که بر عدد قهرمان بخش‌پذیرند. از عددهای دیگر بپر تا جانت کم نشود!</p><button class="btn" id="startBtn" onclick="startGame()">شروع بازی</button></div></div>
    </div>
    <div class="game-controls"><button class="btn" onclick="jump()">⤴ پرش</button><button class="btn secondary" onclick="collectAction()">✦ گرفتن عدد</button><button class="btn secondary" onclick="pauseGame()">Ⅱ مکث</button></div>
    <p class="hint">کامپیوتر: کلید فاصله یا ↑ برای پرش، کلید Enter برای گرفتن عدد. موبایل: از دکمه‌های پایین بازی استفاده کن.</p>
    <div id="gameToast" class="toast" role="status"></div>
  </div>
</section>
</main>
<footer class="footnote"><span>عددباز · تمرین با بازی</span><span>طراحی واکنش‌گرا برای موبایل و کامپیوتر</span></footer>
</div>
<script>
const $=id=>document.getElementById(id);
function showScreen(id){document.querySelectorAll('.screen').forEach(s=>s.classList.toggle('active',s.id===id));window.scrollTo({top:0,behavior:'smooth'});if(id!=='game'&&gameRunning)pauseGame(true)}
function switchTab(tab){document.querySelectorAll('.tab').forEach(t=>t.classList.toggle('active',t.dataset.tab===tab));$('basicPanel').classList.toggle('hidden',tab!=='basic');$('gcdPanel').classList.toggle('hidden',tab!=='gcd')}
function fa(n){return String(n).replace(/\d/g,d=>'۰۱۲۳۴۵۶۷۸۹'[+d])}
function calcKey(k){$('calcDisplay').value+=k;$('calcToast').textContent=''}
function clearCalc(){$('calcDisplay').value='';$('calcResult').innerHTML='پاسخ: <span class="result">—</span>';$('calcToast').textContent=''}
function backspaceCalc(){$('calcDisplay').value=$('calcDisplay').value.slice(0,-1)}
function calculate(){const raw=$('calcDisplay').value.trim();if(!raw){$('calcToast').textContent='اول یک عبارت وارد کن.';return}if(!/^[0-9+\-*/().\s]+$/.test(raw)||/[a-zA-Z]/.test(raw)){$('calcToast').textContent='عبارت معتبر نیست؛ فقط عدد و عملگرهای ریاضی را وارد کن.';return}try{const val=Function('"use strict";return ('+raw+')')();if(typeof val!=='number'||!Number.isFinite(val))throw Error();$('calcResult').innerHTML='پاسخ: <span class="result">'+fa(Number(val.toFixed(8)))+'</span>';$('calcToast').textContent='محاسبه با موفقیت انجام شد.'}catch(e){$('calcToast').textContent='عبارت ریاضی را بررسی کن.'}}
$('calcDisplay').addEventListener('keydown',e=>{if(e.key==='Enter')calculate()});
function gcd(a,b){while(b){[a,b]=[b,a%b]}return a}
function findGcdLcm(){const a=Number($('numA').value),b=Number($('numB').value);if(!Number.isInteger(a)||!Number.isInteger(b)||a<1||b<1||a>1e9||b>1e9){$('gcdToast').textContent='لطفاً دو عدد صحیح مثبت تا یک میلیارد وارد کن.';return}const g=gcd(a,b),l=a/g*b;$('gcdResult').textContent=fa(g);$('lcmResult').textContent=fa(l);$('mathSteps').innerHTML='<strong>روش محاسبه:</strong> ب.م.مِ '+fa(a)+' و '+fa(b)+' برابر '+fa(g)+' است. سپس ک.م.م = ('+fa(a)+' × '+fa(b)+') ÷ '+fa(g)+' = <strong>'+fa(l)+'</strong>.';$('gcdToast').textContent='جواب‌ها آماده‌اند!'}
function setPair(a,b){$('numA').value=a;$('numB').value=b;findGcdLcm()}
let hero=2,score=0,lives=3,gameRunning=false,jumpTimer=null,enemyTimer=null,spawnTimer=null,paused=false,enemyValue=8;
function randomHero(){return Math.floor(Math.random()*9)+2}
function randomEnemy(){return Math.floor(Math.random()*99)+1}
function updateHud(){$('heroNum').textContent=fa(hero);$('player').textContent=fa(hero);$('score').textContent=fa(score);$('lives').textContent=fa(lives)}
function startGame(){if(gameRunning)return;gameRunning=true;paused=false;$('gameMessage').classList.add('hidden');$('gameToast').textContent='';spawnEnemy();spawnTimer=setInterval(()=>{if(gameRunning&&!paused&&!$('enemy').classList.contains('fly'))spawnEnemy()},3500)}
function spawnEnemy(){if(!gameRunning||paused)return;const en=$('enemy');clearTimeout(enemyTimer);en.classList.remove('fly');en.style.right='-65px';enemyValue=randomEnemy();en.textContent=fa(enemyValue);en.style.background=enemyValue%hero===0?'linear-gradient(145deg,#83f5b5,#38c98b)':'linear-gradient(145deg,#ff8bb0,#f3477d)';void en.offsetWidth;en.classList.add('fly');const duration=3300;enemyTimer=setTimeout(()=>{if(!gameRunning||paused)return;const jumping=$('player').classList.contains('jump');if(enemyValue%hero===0){if(!jumping){lives--; $('gameToast').textContent='عدد مناسب را از دست دادی!'}else{$('gameToast').textContent='از عدد بخش‌پذیر پریدی؛ این یکی را بگیر!'}}else if(!jumping){lives--;$('gameToast').textContent='اوه! عدد '+fa(enemyValue)+' بر '+fa(hero)+' بخش‌پذیر نبود.'}else{score++;hero=randomHero();$('gameToast').textContent='آفرین! از عدد نامناسب پریدی؛ قهرمان حالا '+fa(hero)+' است.'}updateHud();if(lives<=0){endGame(false);return}if(score>=10){endGame(true);return}spawnEnemy()},duration)}
function jump(){if(!gameRunning){$('gameToast').textContent='برای شروع، دکمهٔ شروع بازی را بزن.';return}if(paused)return;const p=$('player');p.classList.add('jump');clearTimeout(jumpTimer);jumpTimer=setTimeout(()=>p.classList.remove('jump'),650)}
function collectAction(){if(!gameRunning||paused){$('gameToast').textContent='اول بازی را شروع کن.';return}const en=$('enemy');const stage=$('gameStage').getBoundingClientRect(),er=en.getBoundingClientRect();if(er.left<stage.left+stage.width*.55&&er.right>stage.left+stage.width*.08){if(enemyValue%hero===0){score++;hero=randomHero();$('gameToast').textContent='گرفتی! عدد قهرمان به '+fa(hero)+' تغییر کرد.';en.classList.remove('fly');clearTimeout(enemyTimer);updateHud();if(score>=10)endGame(true);else setTimeout(spawnEnemy,500)}else{$('gameToast').textContent='این عدد بر '+fa(hero)+' بخش‌پذیر نیست؛ بهتر است از رویش بپری!';lives--;updateHud();if(lives<=0)endGame(false)}}else $('gameToast').textContent='صبر کن عدد به قهرمان نزدیک‌تر شود.'}
function pauseGame(silent=false){if(!gameRunning)return;paused=!paused;if(paused){clearInterval(spawnTimer);clearTimeout(enemyTimer);$('enemy').classList.remove('fly');if(!silent){$('messageTitle').textContent='بازی مکث شد';$('messageText').textContent='هر وقت آماده بودی ادامه بده.';$('startBtn').textContent='ادامهٔ بازی';$('startBtn').onclick=resumeGame;$('gameMessage').classList.remove('hidden')}}else resumeGame()}
function resumeGame(){paused=false;$('gameMessage').classList.add('hidden');$('startBtn').textContent='شروع بازی';$('startBtn').onclick=startGame;spawnEnemy();clearInterval(spawnTimer);spawnTimer=setInterval(()=>{if(gameRunning&&!paused&&!$('enemy').classList.contains('fly'))spawnEnemy()},3500)}
function endGame(win){gameRunning=false;paused=false;clearInterval(spawnTimer);clearTimeout(enemyTimer);$('enemy').classList.remove('fly');$('messageTitle').textContent=win?'برنده شدی! 🎉':'یک دور دیگر؟';$('messageText').textContent=win?'۱۰ امتیاز گرفتی؛ قهرمان بخش‌پذیری هستی!':'امتیازت '+fa(score)+' بود. دوباره تلاش کن و عددهای مناسب را بگیر.';$('startBtn').textContent='بازی دوباره';$('startBtn').onclick=resetGame;$('gameMessage').classList.remove('hidden')}
function resetGame(){clearInterval(spawnTimer);clearTimeout(enemyTimer);clearTimeout(jumpTimer);gameRunning=false;paused=false;hero=randomHero();score=0;lives=3;$('player').classList.remove('jump');$('enemy').classList.remove('fly');updateHud();$('messageTitle').textContent='آماده‌ای؟';$('messageText').textContent='عددهایی را بگیر که بر عدد قهرمان بخش‌پذیرند. از عددهای دیگر بپر تا جانت کم نشود!';$('startBtn').textContent='شروع بازی';$('startBtn').onclick=startGame;$('gameMessage').classList.remove('hidden');$('gameToast').textContent=''}
document.addEventListener('keydown',e=>{if(!$('game').classList.contains('active'))return;if(e.code==='Space'||e.code==='ArrowUp'){e.preventDefault();jump()}if(e.code==='Enter')collectAction()});
updateHud();findGcdLcm();
</script>
</body>
</html>
