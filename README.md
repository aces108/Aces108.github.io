<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1"><meta name="theme-color" content="#0b0b14">
<title>Pause — Azubi Hub</title>
<style>
:root{--bg:#0b0b14;--card:#171725;--card2:#202035;--text:#f6f4ff;--muted:#a7a5bf;--pink:#ff58c8;--lime:#d9ff65;--blue:#7e8cff;--line:#33334b;--orange:#ffad5c}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:radial-gradient(ellipse at 5% 0%,#3b174b 0,transparent 35%),radial-gradient(ellipse at 100% 15%,#142f52 0,transparent 32%),var(--bg);color:var(--text);font-family:Inter,system-ui,Segoe UI,Arial,sans-serif}button,input,textarea,select{font:inherit}.wrap{max-width:1200px;margin:auto;padding:18px 18px 60px}.nav{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap}.brand{display:flex;gap:10px;align-items:center;font-weight:1000;letter-spacing:-.8px}.brandmark{width:45px;height:45px;border-radius:15px;display:grid;place-items:center;background:linear-gradient(135deg,var(--pink),#8876ff);font-size:24px;box-shadow:0 0 30px #ff58c84a}.navlinks{display:flex;gap:8px;flex-wrap:wrap}.navlinks a{color:var(--muted);text-decoration:none;padding:9px 11px;border:1px solid var(--line);border-radius:11px;font-size:12px}.navlinks a:hover{color:var(--lime);border-color:var(--lime)}.status{font-size:12px;color:var(--lime);border:1px solid #d9ff6540;border-radius:99px;padding:8px 11px;background:#d9ff650c}.hero{display:grid;grid-template-columns:1.2fr .8fr;gap:24px;align-items:center;padding:52px 0 36px}.eyebrow{font-size:11px;font-weight:950;letter-spacing:2px;color:var(--lime);text-transform:uppercase}.hero h1{font-size:clamp(42px,7vw,82px);line-height:.92;letter-spacing:-4px;margin:15px 0}.hero h1 span{background:linear-gradient(90deg,var(--pink),#b7a0ff,var(--lime));background-clip:text;color:transparent}.hero p{max-width:610px;color:var(--muted);line-height:1.7;font-size:16px}.actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:20px}.btn{border:0;border-radius:12px;padding:11px 15px;font-weight:850;cursor:pointer;background:var(--pink);color:#1c1020;transition:.15s}.btn:hover{transform:translateY(-2px);filter:brightness(1.08)}.btn.alt{background:#ffffff0c;color:var(--text);border:1px solid var(--line)}.btn.lime{background:var(--lime);color:#1b220d}.btn.blue{background:var(--blue);color:#111426}.heroart{position:relative;min-height:300px;border:1px solid var(--line);border-radius:28px;overflow:hidden;background:linear-gradient(150deg,#251338,#111b35 60%,#28213c);display:grid;place-items:center}.heroart:before,.heroart:after{content:"";position:absolute;border-radius:50%;filter:blur(1px)}.heroart:before{width:210px;height:210px;background:#ff58c826;top:-65px;right:-45px}.heroart:after{width:160px;height:160px;background:#d9ff6520;bottom:-55px;left:-30px}.heroemoji{font-size:clamp(65px,10vw,110px);z-index:1;filter:drop-shadow(0 15px 18px #0008);animation:float 4s ease-in-out infinite}.sticker{position:absolute;z-index:2;padding:9px 12px;border-radius:12px;font-size:12px;font-weight:1000;transform:rotate(-8deg);background:var(--lime);color:#1a200b}.sticker.s1{top:25px;left:20px}.sticker.s2{right:15px;bottom:34px;background:var(--pink);transform:rotate(7deg);color:#210e21}.sticker.s3{bottom:23px;left:22px;background:#fff;color:#161625;transform:rotate(-5deg)}@keyframes float{0%,100%{transform:translateY(0) rotate(-3deg)}50%{transform:translateY(-13px) rotate(3deg)}}.ticker{overflow:hidden;border-block:1px solid var(--line);background:#ffffff05;white-space:nowrap;padding:12px 0;color:var(--lime);font-size:12px;font-weight:950;letter-spacing:1px}.ticker span{display:inline-block;min-width:100%;animation:marquee 24s linear infinite}@keyframes marquee{to{transform:translateX(-100%)}}.sectionhead{display:flex;align-items:end;justify-content:space-between;gap:15px;margin:36px 0 15px}.sectionhead h2{font-size:25px;letter-spacing:-1px;margin:5px 0}.sectionhead p{margin:0;color:var(--muted);font-size:13px}.grid{display:grid;grid-template-columns:repeat(12,minmax(0,1fr));gap:15px}.card{min-width:0;border:1px solid var(--line);border-radius:20px;padding:19px;background:linear-gradient(145deg,#202033ee,#151520f2);box-shadow:0 15px 35px #0002}.s8{grid-column:span 8}.s6{grid-column:span 6}.s4{grid-column:span 4}.s12{grid-column:span 12}.head{display:flex;gap:11px;align-items:center;margin-bottom:15px}.iconbox{height:43px;width:43px;border-radius:14px;display:grid;place-items:center;background:#ffffff0c;font-size:22px;flex-shrink:0}.head h3{margin:0 0 3px;font-size:18px;letter-spacing:-.4px}.sub{color:var(--muted);font-size:12px;margin:0;line-height:1.5}.big{font-size:clamp(21px,3vw,30px);line-height:1.2;font-weight:900;letter-spacing:-.8px;margin:18px 0;min-height:65px}.result{color:var(--lime);font-weight:800;font-size:13px;min-height:22px;margin-top:11px}.row{display:flex;gap:8px;flex-wrap:wrap;align-items:center}.pill{border:1px solid var(--line);border-radius:99px;padding:7px 10px;color:var(--muted);font-size:11px}.tiles{display:grid;grid-template-columns:repeat(3,1fr);gap:9px}.tile{border:1px solid var(--line);border-radius:14px;padding:13px 10px;background:#ffffff06;cursor:pointer;text-align:left;color:var(--text);min-height:90px}.tile:hover{border-color:var(--pink);background:#ff58c80d}.tile strong{display:block;margin:7px 0 4px;font-size:13px}.tile small{color:var(--muted);font-size:11px;line-height:1.3;display:block}.tile .em{font-size:25px}.options{display:grid;grid-template-columns:1fr 1fr;gap:9px}.option{border:1px solid var(--line);background:#ffffff07;border-radius:13px;color:var(--text);padding:14px;min-height:60px;text-align:left;cursor:pointer;font-weight:800}.option:hover,.option.selected{border-color:var(--pink);background:#ff58c817}.arena{background:#0c0c14;border:1px solid var(--line);border-radius:15px;min-height:125px;display:grid;place-items:center;text-align:center;padding:20px;cursor:pointer;user-select:none;margin:10px 0}.arena strong{font-size:20px}.arena p{color:var(--muted);font-size:12px}.arena.wait{background:#51202d}.arena.ready{background:#24442e}.bingo{display:grid;grid-template-columns:repeat(3,1fr);gap:7px;margin:12px 0}.bingo button{border:1px solid var(--line);background:#ffffff07;color:var(--text);border-radius:10px;min-height:69px;padding:8px 5px;font-size:11px;font-weight:800;cursor:pointer}.bingo button.done{border-color:var(--lime);background:#d9ff6517;color:var(--lime)}.meter{height:9px;background:#ffffff13;border-radius:99px;overflow:hidden;margin:12px 0}.meter div{height:100%;background:linear-gradient(90deg,var(--pink),var(--lime));width:50%;transition:width .3s}.inputrow{display:flex;gap:8px}.inputrow input,.inputrow textarea,.inputrow select{min-width:0;flex:1;background:#101018;border:1px solid var(--line);border-radius:12px;padding:12px;color:var(--text);outline:none}.feed{display:grid;gap:8px;margin-top:12px}.feeditem{display:flex;gap:10px;padding:12px;border:1px solid #ffffff0b;background:#ffffff06;border-radius:12px;overflow-wrap:anywhere}.feeditem b{color:var(--lime);font-size:12px}.feeditem p{margin:3px 0 0;line-height:1.45;font-size:13px}.memegrid{display:grid;grid-template-columns:repeat(4,1fr);gap:11px}.meme{overflow:hidden;border-radius:15px;border:1px solid var(--line);background:#101019}.memeart{aspect-ratio:1/1;display:grid;place-items:center;font-size:clamp(42px,6vw,70px);position:relative;overflow:hidden}.memeart:after{content:"";position:absolute;inset:0;background:linear-gradient(135deg,#ffffff12,transparent 55%)}.meme:nth-child(1) .memeart{background:linear-gradient(135deg,#40316d,#e85ba6)}.meme:nth-child(2) .memeart{background:linear-gradient(135deg,#133d42,#d9ff65)}.meme:nth-child(3) .memeart{background:linear-gradient(135deg,#2c2455,#777bff)}.meme:nth-child(4) .memeart{background:linear-gradient(135deg,#73351e,#ffad5c)}.meme:nth-child(5) .memeart{background:linear-gradient(135deg,#173c63,#57d5ff)}.meme:nth-child(6) .memeart{background:linear-gradient(135deg,#4b1f37,#ff7ca9)}.meme:nth-child(7) .memeart{background:linear-gradient(135deg,#293b22,#a5df57)}.meme:nth-child(8) .memeart{background:linear-gradient(135deg,#222,#888)}.memetxt{padding:10px}.memetxt strong{font-size:12px;line-height:1.4;display:block}.memetxt button{margin-top:8px;width:100%;padding:7px;border:1px solid var(--line);background:#ffffff08;color:var(--muted);border-radius:9px;font-size:11px;cursor:pointer}.prompt{padding:14px;border-radius:13px;border:1px solid var(--line);background:#ffffff06;margin:8px 0}.prompt strong{color:var(--pink)}.prompt p{font-size:13px;color:#d9d8e7;line-height:1.5;margin:6px 0 0}.quizanswers{display:grid;gap:8px}.quizanswers button{padding:11px;text-align:left;background:#ffffff08;border:1px solid var(--line);color:var(--text);border-radius:11px;cursor:pointer}.quizanswers button:hover{border-color:var(--blue)}.countdown{font-size:44px;font-weight:1000;letter-spacing:-2px;margin:8px 0}.footer{text-align:center;color:var(--muted);font-size:11px;line-height:1.7;padding:30px 0}.toast{position:fixed;bottom:20px;left:50%;transform:translateX(-50%);background:var(--lime);color:#171b0b;padding:12px 17px;border-radius:12px;font-weight:900;display:none;z-index:10;box-shadow:0 10px 30px #0007}.toast.show{display:block}@media(max-width:800px){.hero{grid-template-columns:1fr;padding-top:35px}.heroart{min-height:240px}.s8,.s6,.s4{grid-column:span 12}.memegrid{grid-template-columns:repeat(2,1fr)}.tiles{grid-template-columns:1fr 1fr}.hero h1{letter-spacing:-2px}.navlinks{display:none}}@media(max-width:420px){.memegrid{grid-template-columns:1fr 1fr}.tiles{grid-template-columns:1fr}.card{padding:15px}.wrap{padding-inline:12px}}
</style>

<style>
:root{--bg:#101116;--card:#191b23;--card2:#20232d;--text:#f2f3f7;--muted:#a1a5b3;--pink:#e6a2d6;--lime:#b9f27c;--blue:#91a7ff;--line:#303440;--orange:#ffad5c}
body{background:radial-gradient(ellipse at 12% 0%,#252b39 0,transparent 35%),var(--bg);font-family:Inter,ui-sans-serif,system-ui,-apple-system,Segoe UI,Arial,sans-serif}
.wrap{max-width:1120px}.brandmark{border-radius:11px;background:var(--lime);box-shadow:none;color:#151811}.hero h1{letter-spacing:-3px}.hero h1 span{background:none;color:var(--lime)}.heroart{border-radius:20px;background:linear-gradient(145deg,#252b38,#171921 60%,#292333)}.heroart:before,.heroart:after{opacity:.5}.heroemoji{filter:drop-shadow(0 12px 18px #0006)}.sticker{background:#222632;color:var(--lime);border:1px solid #ffffff20;transform:none!important}.sticker.s2{background:#292333;color:#f2d3ec}.sticker.s3{background:#20232d;color:#e5e7ef}.ticker{color:var(--muted);border-color:var(--line);background:#ffffff03}.card{border-radius:17px;background:linear-gradient(145deg,#1d2029,#171920);box-shadow:none}.iconbox{border-radius:12px;background:#ffffff09}.btn{border-radius:10px;transition:transform .15s}.btn.lime{background:var(--lime);color:#171b12}.btn:not(.alt):not(.secondary){background:var(--lime);color:#171b12}.memeart{filter:saturate(.75)}.sectionhead h2{letter-spacing:-.7px}.sub,.notice{color:var(--muted)}.pill{border-color:var(--line)}.footer{color:var(--muted)}
</style>


<style>
/* Erweiterungen: Video-Lounge, mehr Memes und lokale Duelle */
.extra-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px}
.extra-meme{border:1px solid var(--line);border-radius:14px;padding:15px;background:#ffffff05;min-height:145px;display:flex;flex-direction:column;justify-content:space-between}
.extra-meme .emoji{font-size:30px;margin-bottom:10px}.extra-meme strong{font-size:13px;line-height:1.45}
.video-frame{width:100%;aspect-ratio:9/16;border:0;border-radius:14px;background:#090a0e;max-height:560px}
.video-wide{aspect-ratio:16/9;max-height:none}
.video-shell{margin-top:12px;border:1px solid var(--line);border-radius:16px;padding:12px;background:#0d0e13}
.scoreboard{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:10px;margin:12px 0}
.scorebox{border:1px solid var(--line);border-radius:14px;padding:13px;background:#ffffff05}
.scorebox strong{display:block;font-size:15px;margin-bottom:5px}.scorebox .score{font-size:30px;font-weight:900;color:var(--lime)}
.game-question{font-size:clamp(20px,3vw,28px);font-weight:900;line-height:1.25;margin:18px 0}
.game-choices{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.game-choices button{padding:13px;border:1px solid var(--line);background:#ffffff08;color:var(--text);border-radius:12px;text-align:left;cursor:pointer}
.game-choices button:hover{border-color:var(--lime)}
.notice{font-size:12px;line-height:1.55;color:var(--muted)}
@media(max-width:800px){.extra-grid{grid-template-columns:repeat(2,minmax(0,1fr))}}
@media(max-width:480px){.extra-grid{grid-template-columns:1fr}.game-choices{grid-template-columns:1fr}}
</style>


<style>
.arcade-grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.arcade-card{border:1px solid var(--line);border-radius:18px;padding:15px;background:linear-gradient(145deg,#171725,#101019);min-width:0}
.arcade-head{display:flex;align-items:flex-start;justify-content:space-between;gap:10px;margin-bottom:12px}
.arcade-head h3{margin:0 0 5px}.arcade-head p{margin:0;color:var(--muted);font-size:13px;line-height:1.5}
.arcade-canvas{display:block;width:100%;height:auto;aspect-ratio:16/10;border-radius:13px;border:1px solid #ffffff1c;background:#0a0c17;touch-action:manipulation}
.arcade-controls{display:flex;gap:8px;flex-wrap:wrap;align-items:center;margin-top:11px}
.arcade-stat{font-size:12px;color:var(--muted);margin-left:auto}
.arcade-help{font-size:12px;line-height:1.55;color:var(--muted);margin:10px 0 0}
.arcade-mobile{display:flex;gap:8px;margin-top:9px}
.arcade-mobile button{flex:1}
@media(max-width:760px){.arcade-grid{grid-template-columns:1fr}.arcade-stat{margin-left:0;width:100%}}
</style>

</head>
<body>
<div class="wrap">
<header class="nav">
 <div class="brand"><div class="brandmark">☕</div><div>PAUSE<span style="color:var(--pink)"> / AZUBI HUB</span></div></div>
 <nav class="navlinks"><a href="#games">MINI-GAMES</a><a href="#memes">MEME-ZONE</a><a href="#talk">PAUSENWAND</a><a href="#videos">VIDEOS</a><a href="#duelle">DUELLE</a><a href="#arcade">ARCADE</a><a href="#quiz">QUIZ</a></nav>
 <div class="status">● PAUSENMODUS / ON</div>
</header>
<section class="hero">
 <div><div class="eyebrow">Der digitale Aufenthaltsraum für Azubis</div>
 <h1>Ausbildung?<br><span>Später.</span><br>Jetzt Pause.</h1>
 <p>Brainrot, Büro-Bingo, absurde Fragen und Mini-Games für die heilige Zeit zwischen „Kannst du mal kurz?“ und Feierabend. Schnapp dir deine Crew. 🫡</p>
 <div class="actions"><a href="#games"><button class="btn lime">🎮 Spielen gehen</button></a><a href="#memes"><button class="btn alt">💀 Meme-Zone</button></a></div></div>
 <div class="heroart"><div class="sticker s1">+999 AURA</div><div class="heroemoji">🗿☕</div><div class="sticker s2">PAUSENMODUS</div><div class="sticker s3">PAUSE / PLAY</div></div>
</section>
<div class="ticker"><span>☕ KAFFEE • 🗿 AURA • 📎 EXCEL ENDGEGNER • 💀 NPC-MODUS • 🚽 SKIBIDI • 🧠 BRAINROT • 💤 FEIERABEND LOADING • ☕ KAFFEE • 🗿 AURA • 📎 EXCEL ENDGEGNER • 💀 NPC-MODUS • 🚽 SKIBIDI •</span></div>

<div class="sectionhead" id="games"><div><div class="eyebrow">01 / Beschäftigungstherapie</div><h2>Mini-Games</h2><p>Für fünf Minuten. Oder zwölf Runden.</p></div></div>
<main class="grid">
<section class="card s8"><div class="head"><div class="iconbox">💬</div><div><h3>Wer würde eher …?</h3><p class="sub">Diskussionen, die ein Team wirklich braucht.</p></div></div><div class="big" id="question">Wer würde eher „Bin gleich da“ schreiben und 20 Minuten später kommen?</div><div class="row"><button class="btn" id="nextQ">Neue Frage ↗</button><button class="btn alt" id="copyQ">Frage kopieren</button></div><div class="result" id="qResult"></div></section>
<section class="card s4"><div class="head"><div class="iconbox">✨</div><div><h3>Aura-Scanner</h3><p class="sub">Zertifiziert von niemandem.</p></div></div><div class="countdown" id="aura">+999</div><div id="auraText" class="sub">Aura: stabil.</div><div class="meter"><div id="auraBar"></div></div><button class="btn lime" id="auraBtn">Aura messen</button></section>
<section class="card s6"><div class="head"><div class="iconbox">⚡</div><div><h3>Reaktionstest</h3><p class="sub">Klick erst, wenn das Feld grün wird!</p></div></div><div class="arena" id="arena"><div><strong id="arenaTitle">Bereit, Legende?</strong><p id="arenaText">Start drücken und warten …</p></div></div><div class="row"><button class="btn blue" id="startReaction">Start</button><span class="pill" id="bestTime">Bestzeit: –</span></div><div class="result" id="reactionResult"></div></section>
<section class="card s6"><div class="head"><div class="iconbox">📋</div><div><h3>Azubi-Bingo</h3><p class="sub">Markier die Dinge, die du schon erlebt hast.</p></div></div><div class="bingo" id="bingo"></div><div class="row"><span class="pill" id="bingoCount">0 / 9</span><button class="btn alt" id="resetBingo">Zurücksetzen</button></div></section>
<section class="card s6" id="quiz"><div class="head"><div class="iconbox">🧠</div><div><h3>Das unnötige Wissen-Quiz</h3><p class="sub">Beweise, dass dein Gehirn noch online ist.</p></div></div><div class="big" id="quizQ">Welches Tier macht den berühmten „bruh“-Move am besten?</div><div class="quizanswers" id="quizAnswers"></div><div class="result" id="quizResult">Eine Antwort wählen.</div><button class="btn alt" id="nextQuiz" style="margin-top:10px">Nächste Frage</button></section>
<section class="card s6"><div class="head"><div class="iconbox">🎲</div><div><h3>Ausreden-Generator</h3><p class="sub">Satire. Bitte nicht der Personalabteilung schicken.</p></div></div><div class="big" id="excuse">„Mein Wecker hat geklingelt, aber mein Körper hat den Antrag auf Aufstehen abgelehnt.“</div><div class="row"><button class="btn" id="newExcuse">Neue Ausrede</button><button class="btn alt" id="copyExcuse">Kopieren</button></div></section>
<section class="card s6"><div class="head"><div class="iconbox">🆚</div><div><h3>Entweder-oder: Brainrot Edition</h3><p class="sub">Deine Wahl sagt alles über dich aus.</p></div></div><div class="big" id="eitherQuestion">Ein Leben lang Skibidi sagen oder jeden Satz mit Bruder beenden?</div><div class="options" id="eitherOptions"></div><div class="result" id="eitherResult">Wähle dein Schicksal.</div><button class="btn alt" id="nextEither" style="margin-top:10px">Neue Entscheidung</button></section>
<section class="card s6"><div class="head"><div class="iconbox">🧘</div><div><h3>30-Sekunden-Reset</h3><p class="sub">Schultern runter. Kiefer locker. Einmal atmen.</p></div></div><div class="countdown" id="breathNum">30</div><p class="sub" id="breathText">Ein Mini-Reset für deinen Kopf. Atme ruhig und bequem.</p><div class="row"><button class="btn lime" id="breathStart">Reset starten</button><button class="btn alt" id="breathStop">Stop</button></div></section>
</main>

<div class="sectionhead" id="memes"><div><div class="eyebrow">02 / Visuelle Überforderung</div><h2>Meme-Ecke</h2><p>Originale Emoji-Meme-Karten – kein externer Bildlink nötig.</p></div></div>
<section class="card">
 <div class="memegrid" id="memegrid">
  <article class="meme"><div class="memeart">🗿📈</div><div class="memetxt"><strong>Wenn du einmal „Guten Morgen“ sagst und plötzlich Teamleitung bist.</strong><button data-copy="Wenn du einmal Guten Morgen sagst und plötzlich Teamleitung bist.">Spruch kopieren</button></div></article>
  <article class="meme"><div class="memeart">☕😭</div><div class="memetxt"><strong>Ich ohne Kaffee: Bitte wenden Sie sich an jemand Kompetentes.</strong><button data-copy="Ich ohne Kaffee: Bitte wenden Sie sich an jemand Kompetentes.">Spruch kopieren</button></div></article>
  <article class="meme"><div class="memeart">📎🔥</div><div class="memetxt"><strong>Excel sagt #WERT! — ich auch, Bruder.</strong><button data-copy="Excel sagt #WERT! — ich auch, Bruder.">Spruch kopieren</button></div></article>
  <article class="meme"><div class="memeart">🧍‍♂️💨</div><div class="memetxt"><strong>Wenn jemand „kurze Besprechung“ sagt und du langsam rückwärts gehst.</strong><button data-copy="Wenn jemand kurze Besprechung sagt und du langsam rückwärts gehst.">Spruch kopieren</button></div></article>
  <article class="meme"><div class="memeart">🧠🚫</div><div class="memetxt"><strong>Mein Gehirn ab 14:45 Uhr: Wir schließen jetzt.</strong><button data-copy="Mein Gehirn ab 14:45 Uhr: Wir schließen jetzt.">Spruch kopieren</button></div></article>
  <article class="meme"><div class="memeart">🦅💅</div><div class="memetxt"><strong>Wenn du die Aufgabe beim ersten Versuch richtig machst.</strong><button data-copy="Wenn du die Aufgabe beim ersten Versuch richtig machst.">Spruch kopieren</button></div></article>
  <article class="meme"><div class="memeart">🚽👑</div><div class="memetxt"><strong>Wenn du die Aufgabe beim ersten Versuch richtig machst.</strong><button data-copy="Wenn du die Aufgabe beim ersten Versuch richtig machst.">Spruch kopieren</button></div></article>
  <article class="meme"><div class="memeart">📧💀</div><div class="memetxt"><strong>„Zur Kenntnis genommen“ — mein passiv-aggressives Alter Ego.</strong><button data-copy="Zur Kenntnis genommen — mein passiv-aggressives Alter Ego.">Spruch kopieren</button></div></article>
 </div>
 <div class="row" style="margin-top:14px"><button class="btn" id="memeMix">Meme-Mix würfeln 🎲</button><button class="btn alt" id="memeCopyAll">Alle Sprüche kopieren</button></div>
</section>

<div class="sectionhead"><div><div class="eyebrow">03 / Kleine Challenges</div><h2>Challenge des Tages 🏆</h2><p>Für dich oder die Azubi-Crew.</p></div></div>
<section class="grid">
 <div class="card s4"><div class="head"><div class="iconbox">🎤</div><div><h3>Wort-Verbot</h3><p class="sub">Eine Mini-Challenge</p></div></div><div class="big" id="challenge">Sag 5 Minuten lang nicht „ja“.</div><button class="btn" id="newChallenge">Neue Challenge</button></div>
 <div class="card s4"><div class="head"><div class="iconbox">🤝</div><div><h3>Icebreaker</h3><p class="sub">Wenn keiner weiß, was er sagen soll</p></div></div><div class="big" id="icebreaker">Was ist dein komplett unnötiges Talent?</div><button class="btn" id="newIce">Neue Frage</button></div>
 <div class="card s4"><div class="head"><div class="iconbox">📝</div><div><h3>Kompliment-Maschine</h3><p class="sub">Gib jemandem eine kleine gute Vibe-Dosis.</p></div></div><div class="big" id="compliment">Du bist der Grund, warum Gruppenarbeiten überhaupt funktionieren.</div><button class="btn lime" id="newCompliment">Noch eins ✨</button></div>
</section>

<div class="sectionhead" id="talk"><div><div class="eyebrow">04 / Das digitale schwarze Brett</div><h2>Pausenwand 📣</h2><p>Notizen, Mood und Insider für dieses Gerät.</p></div></div>
<section class="card">
 <div class="inputrow"><input id="postName" maxlength="24" placeholder="Nickname (optional)"><input id="postInput" maxlength="220" placeholder="Was geht in der Azubi-Welt?"><button class="btn" id="postBtn">Posten</button></div>
 <div class="feed" id="feed"><div class="feeditem"><span>☕</span><div><b>PAUSENBOT</b><p>Willkommen im PAUSE / AZUBI HUB. Trinken nicht vergessen. Und nein: 17 offene Tabs sind kein Multitasking.</p></div></div></div>
 <p class="sub" style="margin-top:12px">Privatsphäre-Hinweis: Die Pausenwand speichert nichts online und ist nur in diesem Browser sichtbar. Für einen echten gemeinsamen Live-Chat braucht es Hosting plus eine Datenbank oder einen Chat-Dienst. Bitte keine vertraulichen Betriebsdaten posten.</p>
</section>

<div class="sectionhead" id="more-memes"><div><div class="eyebrow">05 / Mehr Material für die Gruppenchat-Hölle</div><h2>Mehr Memes</h2><p>Neue Vorlagen zum Teilen oder als Inspiration für euren Gruppenchat.</p></div></div>
<section class="card">
  <div class="extra-grid" id="extraMemes">
    <article class="extra-meme"><div><div class="emoji">🧍‍♂️📧</div><strong>„Hast du kurz Zeit?“ — und plötzlich ist dein Kalender bis Donnerstag voll.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">🖨️🧎</div><strong>Ich vor dem Drucker: Wir können das auf die leichte oder auf die sehr leichte Art machen.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">☕🫥</div><strong>Der erste Kaffee wirkt. Der zweite macht mich wieder gesellschaftsfähig.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">📊🧠</div><strong>Excel geöffnet. Gehirn geschlossen.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">🕒🏃</div><strong>17:00 Uhr: Ich war heute nie hier.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">📞💀</div><strong>Wenn das Telefon klingelt und du plötzlich sehr beschäftigt aussiehst.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">🧠🔄</div><strong>Ich lese dieselbe Mail zum vierten Mal und hoffe, dass sie sich von allein erklärt.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">🗂️🫡</div><strong>Ordner sortiert. Dateien benannt. Leben trotzdem nicht im Griff.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">🥪⏳</div><strong>Die Pause ist kurz, aber der Snack ist eine vollwertige Lebensentscheidung.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">👀💻</div><strong>Wenn jemand hinter dir steht und du so tust, als wäre das gerade deine wichtigste Aufgabe.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">📅🫠</div><strong>Montag geplant. Dienstag improvisiert. Mittwoch akzeptiert.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
    <article class="extra-meme"><div><div class="emoji">🏆🧾</div><strong>Der wahre Skill: wissen, wo die Datei gespeichert wurde.</strong></div><button class="btn alt copy-extra">Text kopieren</button></article>
  </div>
  <div class="row" style="margin-top:14px"><button class="btn" id="extraMemeShuffle">Memes mischen</button><button class="btn alt" id="randomMemeCaption">Zufälligen Spruch anzeigen</button></div>
  <div class="result" id="randomMemeResult"></div>
</section>

<div class="sectionhead" id="videos"><div><div class="eyebrow">06 / Video-Pause</div><h2>Reels, TikToks & Videos</h2><p>Link einfügen und schauen, ob die Plattform das Einbetten erlaubt.</p></div></div>
<section class="card">
  <div class="head"><div class="iconbox">▶</div><div><h3>Video-Lounge</h3><p class="sub">YouTube, TikTok oder Instagram-Reels direkt hier versuchen.</p></div></div>
  <div class="inputrow"><input id="videoUrl" type="url" placeholder="Video-Link einfügen …" aria-label="Video-Link"><button class="btn" id="loadVideo">Öffnen</button></div>
  <div class="row" style="margin-top:10px">
    <button class="btn alt videoQuick" data-url="https://www.youtube.com/">YouTube</button>
    <button class="btn alt videoQuick" data-url="https://www.tiktok.com/">TikTok</button>
    <button class="btn alt videoQuick" data-url="https://www.instagram.com/reels/">Instagram Reels</button>
  </div>
  <div id="videoStatus" class="notice" style="margin-top:12px">Füge einen konkreten Video-Link ein. Wenn der Player blockiert wird, kannst du das Video über „In neuem Tab öffnen“ starten.</div>
  <div class="video-shell" id="videoShell" hidden>
    <div class="row" style="justify-content:space-between;margin-bottom:10px"><span class="pill" id="videoPlatform">Video</span><a id="videoExternal" class="btn alt" href="#" target="_blank" rel="noopener noreferrer">In neuem Tab öffnen ↗</a></div>
    <iframe id="videoFrame" class="video-frame" title="Eingebettetes Video" allow="autoplay; encrypted-media; picture-in-picture; fullscreen" allowfullscreen loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
  </div>
  <p class="notice" style="margin-top:12px">Hinweis: Instagram und TikTok verhindern das Einbetten mancher Videos oder verlangen Login/Cookies. Das liegt an den Plattformen, nicht an der Seite. Auf manchen Arbeitsnetzwerken können Video-Seiten gesperrt sein.</p>
</section>

<div class="sectionhead" id="duelle"><div><div class="eyebrow">07 / Kleine Rivalität</div><h2>Duell-Modus</h2><p>Zu zweit oder in Teams am selben Gerät – Punkte zählen.</p></div></div>
<section class="grid">
  <section class="card s6">
    <div class="head"><div class="iconbox">⚔️</div><div><h3>Azubi-Quiz-Duell</h3><p class="sub">Abwechselnd antworten. Richtige Antwort = 1 Punkt.</p></div></div>
    <div class="inputrow"><input id="playerOne" maxlength="20" value="Team 1" aria-label="Name Team 1"><input id="playerTwo" maxlength="20" value="Team 2" aria-label="Name Team 2"></div>
    <div class="scoreboard"><div class="scorebox"><strong id="nameOne">Team 1</strong><div class="score" id="scoreOne">0</div><small class="sub">Punkte</small></div><div class="scorebox"><strong id="nameTwo">Team 2</strong><div class="score" id="scoreTwo">0</div><small class="sub">Punkte</small></div></div>
    <div class="pill" id="turnLabel">Team 1 ist dran</div>
    <div class="game-question" id="duelQuestion">Was ist die Tastenkombination zum Speichern?</div>
    <div class="game-choices" id="duelChoices"></div>
    <div class="result" id="duelResult">Runde starten und Punkte sammeln.</div>
    <div class="row" style="margin-top:12px"><button class="btn alt" id="nextDuel">Nächste Frage</button><button class="btn alt" id="resetDuel">Punkte zurücksetzen</button></div>
  </section>
  <section class="card s6">
    <div class="head"><div class="iconbox">⚡</div><div><h3>Wer klickt schneller?</h3><p class="sub">Zwei Spieler, ein Gerät, abwechselnd auf Grün reagieren.</p></div></div>
    <div class="scoreboard"><div class="scorebox"><strong id="reactNameOne">Team 1</strong><div class="score" id="reactScoreOne">–</div><small class="sub">Zeit in ms</small></div><div class="scorebox"><strong id="reactNameTwo">Team 2</strong><div class="score" id="reactScoreTwo">–</div><small class="sub">Zeit in ms</small></div></div>
    <div class="arena" id="duelArena"><div><strong id="duelArenaTitle">Bereit?</strong><p id="duelArenaText">Erst Team 1, dann Team 2. Nicht zu früh klicken.</p></div></div>
    <div class="row"><button class="btn" id="duelReactStart">Runde starten</button><button class="btn alt" id="duelReactReset">Reset</button></div>
    <div class="result" id="duelReactResult"></div>
  </section>
  <section class="card s12">
    <div class="head"><div class="iconbox">🗳️</div><div><h3>Meme-Caption-Battle</h3><p class="sub">Beide schreiben eine Caption zum selben Bild. Danach stimmt die Gruppe ab.</p></div></div>
    <div class="heroart" style="min-height:150px;border-radius:14px;margin-bottom:12px"><div class="heroemoji" id="captionEmoji" style="animation:none;font-size:60px">🖨️💀</div></div>
    <div class="inputrow"><input id="captionOne" placeholder="Caption von Team 1"><input id="captionTwo" placeholder="Caption von Team 2"></div>
    <div class="row" style="margin-top:10px"><button class="btn" id="captionPrompt">Neues Meme-Motiv</button><button class="btn alt" id="captionVoteOne">Punkt für Team 1</button><button class="btn alt" id="captionVoteTwo">Punkt für Team 2</button></div>
    <div class="result" id="captionResult">Schreibt eure Sprüche, lest sie vor und stimmt ab.</div>
  </section>
</section>
<p class="notice" style="margin-top:12px">Wichtig: Diese Version speichert Punkte nur in der geöffneten Seite. Das sind lokale Mehrspieler-Spiele auf einem Gerät, noch keine Online-Lobby. Damit mehrere Azubis von verschiedenen Handys gleichzeitig gegeneinander spielen, braucht die Website zusätzlich einen gemeinsamen Server/Realtime-Dienst.</p>


<div class="sectionhead" id="arcade"><div><div class="eyebrow">08 / Highscore statt Langeweile</div><h2>Arcade</h2><p>Zwei kleine Spiele direkt im Browser. Keine Installation, keine Anmeldung.</p></div></div>
<section class="arcade-grid">
  <article class="arcade-card">
    <div class="arcade-head"><div><h3>☕ Azubi Runner</h3><p>Spring über Kartons, sammle Kaffee und knack deinen Highscore.</p></div><span class="pill">2D</span></div>
    <canvas id="runnerCanvas" class="arcade-canvas" width="800" height="500" aria-label="2D-Spiel Azubi Runner"></canvas>
    <div class="arcade-controls"><button class="btn" id="runnerStart">Spiel starten</button><button class="btn alt" id="runnerPause">Pause</button><span class="arcade-stat">Score: <b id="runnerScore">0</b> · Best: <b id="runnerBest">0</b></span></div>
    <div class="arcade-mobile"><button class="btn alt" id="runnerJump">Springen ↑</button><button class="btn alt" id="runnerDuck">Ducken ↓</button></div>
    <p class="arcade-help">Steuerung: Leertaste / ↑ zum Springen, ↓ zum Ducken. Am Handy die Buttons verwenden. Kaffee gibt Bonuspunkte.</p>
  </article>
  <article class="arcade-card">
    <div class="arcade-head"><div><h3>🛣️ Office Rush</h3><p>Weiche Hindernissen aus und überlebe den Büro-Parcours in 3D-Optik.</p></div><span class="pill">Pseudo-3D</span></div>
    <canvas id="rushCanvas" class="arcade-canvas" width="800" height="500" aria-label="Pseudo-3D-Spiel Office Rush"></canvas>
    <div class="arcade-controls"><button class="btn" id="rushStart">Spiel starten</button><button class="btn alt" id="rushPause">Pause</button><span class="arcade-stat">Score: <b id="rushScore">0</b> · Best: <b id="rushBest">0</b></span></div>
    <div class="arcade-mobile"><button class="btn alt" id="rushLeft">← Links</button><button class="btn alt" id="rushJump">Springen ↑</button><button class="btn alt" id="rushRight">Rechts →</button></div>
    <p class="arcade-help">Steuerung: ← / → oder A / D wechseln die Spur, ↑ / Leertaste springt. Am Handy die Buttons verwenden.</p>
  </article>
</section>

<footer class="footer">PAUSE / AZUBI HUB · Für die heilige Pause zwischen „Kannst du kurz?“ und „Schönen Feierabend!“<br>Eine Spaß-Seite, kein offizielles Ausbildungsportal. Spielt fair und macht niemanden im Betrieb bloß. 💜</footer>
</div><div class="toast" id="toast">Kopiert! ✨</div>
<script>
const $=id=>document.getElementById(id);
function toast(t='Kopiert! ✨'){let el=$('toast');el.textContent=t;el.classList.add('show');setTimeout(()=>el.classList.remove('show'),1700)}
async function copyText(t){try{await navigator.clipboard.writeText(t);toast()}catch(e){let x=document.createElement('textarea');x.value=t;document.body.append(x);x.select();document.execCommand('copy');x.remove();toast()}}
const questions=['Wer würde eher „Bin gleich da“ schreiben und 20 Minuten später kommen?','Wer würde eher eine E-Mail mit „Mit freundlichen Grüßen“ an die eigene Mutter schicken?','Wer würde eher den Drucker anschreien wie einen Endgegner?','Wer würde eher „kurze Rückfrage“ sagen und 45 Minuten reden?','Wer würde eher in der Pause verschwinden und mit Snacks zurückkommen?','Wer würde eher nicken, obwohl absolut nichts verstanden wurde?','Wer würde eher aus Versehen „Allen antworten“ drücken?','Wer würde eher die Excel-Datei „final_final_WIRKLICHfinal“ nennen?','Wer würde eher am Freitag um 13 Uhr geistig schon im Wochenende sein?','Wer würde eher einen Termin vergessen, den er selbst eingetragen hat?','Wer würde eher fünf Minuten nach Feierabend noch eine Mail lesen?','Wer würde eher die Berufsschule als Schlaflabor nutzen?','Wer würde eher eine 3-Minuten-Aufgabe 3 Tage aufschieben?','Wer würde eher „Das dauert nur kurz“ sagen und dann den ganzen Nachmittag brauchen?'];let qi=0;
$('nextQ').onclick=()=>{$('question').textContent=questions[qi++%questions.length];$('qResult').textContent=''};
$('copyQ').onclick=()=>copyText($('question').textContent);
const auraLines=['+900 Aura: Kaffee korrekt balanciert.','-400 Aura: „Kannst du mal kurz?“ gehört.','NPC-Modus aktiviert. Blick ins Leere.','Legendärer Pausen-Move entdeckt.','+999 Aura: Aufgabe beim ersten Versuch erledigt.','Aura wird gerade im Drucker gestaut.','Deine Aura arbeitet heute mobil.','Boss-Level: Du hast die Mail ohne Tippfehler verschickt.','Aura kritisch: Montag wurde erkannt.'];function aura(){let n=Math.floor(Math.random()*2001)-500;$('aura').textContent=(n>0?'+':'')+n;$('auraText').textContent=auraLines[Math.floor(Math.random()*auraLines.length)];$('auraBar').style.width=Math.max(0,Math.min(100,(n+500)/20))+'%'}$('auraBtn').onclick=aura;aura();
let state='idle',timer=null,start=0,best=null;function arena(c,t,p){$('arena').className='arena '+(c||'');$('arenaTitle').textContent=t;$('arenaText').textContent=p}
$('startReaction').onclick=()=>{if(state==='wait'||state==='ready')return;state='wait';arena('wait','Nicht klicken …','Warte auf GRÜN. Zu früh = Aura minus.');timer=setTimeout(()=>{state='ready';start=performance.now();arena('ready','JETZT KLICKEN!','Jetzt!')},900+Math.random()*3200)};
$('arena').onclick=()=>{if(state==='wait'){clearTimeout(timer);state='idle';arena('','Zu früh 💀','Du bist in die Falle getappt. Nochmal!');$('reactionResult').textContent='Reaktionszeit: emotional 0 ms.'}else if(state==='ready'){let n=Math.round(performance.now()-start);state='idle';arena('',n+' ms','Noch eine Runde?');$('reactionResult').textContent=n<220?'Ninja-Reflexe. Bist du ein Bot?!':n<330?'Stark, die Maus hat Aura.':'Solide. Der Montag war wohl lang.';if(best===null||n<best){best=n;$('bestTime').textContent='Bestzeit: '+best+' ms'}}};
const bingoItems=['„Kurze Rückfrage“','Drucker streikt','Kaffee ist leer','„Bin gleich zurück“','Meeting hätte Mail sein können','Passwort vergessen','Aufgabe für gestern','„Haben wir immer so gemacht“','Feierabend-Gedanken'];function buildBingo(){$('bingo').innerHTML='';bingoItems.forEach(x=>{let b=document.createElement('button');b.textContent=x;b.onclick=()=>{b.classList.toggle('done');let all=[...$('bingo').children],n=all.filter(z=>z.classList.contains('done')).length;$('bingoCount').textContent=n+' / 9';let lines=[[0,1,2],[3,4,5],[6,7,8],[0,3,6],[1,4,7],[2,5,8],[0,4,8],[2,4,6]];if(lines.some(l=>l.every(i=>all[i].classList.contains('done'))))toast('BINGO! Pausen-Legende 🏆')};$('bingo').append(b)});$('bingoCount').textContent='0 / 9'}$('resetBingo').onclick=buildBingo;buildBingo();
const quiz=[{q:'Welches Tier macht den berühmten „bruh“-Move am besten?',a:['Katze 🐈','Capybara 🦫','Drucker 🖨️'],correct:1,why:'Capybara = maximal entspannt, minimal Drama.'},{q:'Was bedeutet „NPC-Energie“ hier am ehesten?',a:['Nebenfigur-Vibes','Nobelpreis-Chemie','Neuer Passwort-Code'],correct:0,why:'NPC steht für Non-Player Character – die Meme-Version von Autopilot.'},{q:'Was ist die stärkste Büro-Superkraft?',a:['Excel ohne Fehler','Drucker verstehen','Pünktlich Feierabend'],correct:2,why:'Pünktlicher Feierabend ist ein legendärer Skill.'},{q:'Was bedeutet „ziemlich ikonisch“?',a:['Das ist peak / ikonisch','Ein Kinoticket','Ein Excel-Format'],correct:0,why:'Internet-Slang für etwas besonders Dramatisches oder Beeindruckendes.'},{q:'Welche Taste speichert meistens?',a:['Ctrl + S','Ctrl + Panik','Alt + Feierabend'],correct:0,why:'Ctrl + S. Und trotzdem bitte regelmäßig speichern.'}];let qz=0;function showQuiz(){let d=quiz[qz%quiz.length];$('quizQ').textContent=d.q;$('quizAnswers').innerHTML='';d.a.forEach((a,i)=>{let b=document.createElement('button');b.textContent=a;b.onclick=()=>{$('quizAnswers').querySelectorAll('button').forEach(x=>x.disabled=true);$('quizResult').textContent=(i===d.correct?'Richtig! 🧠 ':'Leider nein. 💀 ')+d.why;b.style.borderColor=i===d.correct?'var(--lime)':'var(--pink)'};$('quizAnswers').append(b)});$('quizResult').textContent='Eine Antwort wählen.'} $('nextQuiz').onclick=()=>{qz++;showQuiz()};showQuiz();
const excuses=['„Mein Wecker hat geklingelt, aber mein Körper hat den Antrag auf Aufstehen abgelehnt.“','„Ich war pünktlich, nur in einer anderen Zeitzone.“','„Mein WLAN hat die Motivation nicht geladen.“','„Ich habe die Aufgabe mental schon erledigt.“','„Ich musste kurz meine Aura aufladen.“','„Mein Kalender hat den Termin als optional interpretiert.“','„Ich war nicht zu spät. Die anderen waren zu früh.“','„Die Datei war fertig, aber mein Laptop brauchte emotionale Unterstützung.“','„Ich habe auf Speichern gedrückt. In meinem Herzen.“'];$('newExcuse').onclick=()=>$('excuse').textContent=excuses[Math.floor(Math.random()*excuses.length)];$('copyExcuse').onclick=()=>copyText($('excuse').textContent);
const either=[['Ein Leben lang Skibidi sagen oder jeden Satz mit Bruder beenden?','🚽 Skibidi forever','🗿 Bruder-Modus'],['Eine Woche ohne Kaffee oder ohne Handy?','☕ Kein Kaffee','📱 Kein Handy'],['Immer 10 Minuten zu früh oder 3 Minuten zu spät?','⏰ Zu früh','🏃 Zu spät'],['Nur noch Sprachnachrichten oder nur E-Mails?','🎙️ Sprachnachrichten','📧 E-Mails'],['Chef für einen Tag oder unsichtbar für eine Stunde?','👑 Chef-Modus','👻 Unsichtbar'],['NPC-Musik oder Bossmusik beim Betreten eines Raums?','🕹️ NPC-Musik','🎮 Bossmusik']];let ei=0;function showEither(){let d=either[ei%either.length];$('eitherQuestion').textContent=d[0];$('eitherOptions').innerHTML='';d.slice(1).forEach(t=>{let b=document.createElement('button');b.className='option';b.textContent=t;b.onclick=()=>{$('eitherOptions').querySelectorAll('button').forEach(x=>x.classList.remove('selected'));b.classList.add('selected');$('eitherResult').textContent='Mutige Wahl. Du musst jetzt damit leben. 💀'};$('eitherOptions').append(b)});$('eitherResult').textContent='Wähle dein Schicksal.'}$('nextEither').onclick=()=>{ei++;showEither()};showEither();
const challenges=['Sag 5 Minuten lang nicht „ja“.','Mach jemandem ein ehrliches Kompliment.','Erkläre deinen heutigen Mood nur mit drei Emojis.','Finde den unnötigsten Gegenstand auf deinem Schreibtisch.','Sprich 60 Sekunden lang wie ein Nachrichtensprecher.','Erfinde einen neuen Namen für euren Drucker.','Mach 30 Sekunden Schulter-Reset.','Lass jemanden deinen Aura-Score bestimmen.'];$('newChallenge').onclick=()=>$('challenge').textContent=challenges[Math.floor(Math.random()*challenges.length)];
const ice=['Was ist dein komplett unnötiges Talent?','Welcher Snack beschreibt deine Persönlichkeit?','Was wäre dein Endgegner im Büro?','Wenn dein Tag ein Meme wäre, welches?','Welche Kleinigkeit macht dich sofort glücklich?','Was würdest du mit einem unerwarteten freien Tag machen?','Welches Tier wäre dein Arbeitskollege?'];$('newIce').onclick=()=>$('icebreaker').textContent=ice[Math.floor(Math.random()*ice.length)];
const compliments=['Du bist der Grund, warum Gruppenarbeiten überhaupt funktionieren.','Deine Vibes machen die Pause besser.','Du erklärst Dinge, ohne dass man sich dumm fühlt.','Du bringst mehr Ordnung rein als jede Excel-Tabelle.','Dein Humor ist heute offiziell betriebsnotwendig.','Du hast eine stabile Hauptfiguren-Energie.'];$('newCompliment').onclick=()=>$('compliment').textContent=compliments[Math.floor(Math.random()*compliments.length)];
$('memegrid').addEventListener('click',e=>{let b=e.target.closest('button[data-copy]');if(b)copyText(b.dataset.copy)});$('memeMix').onclick=()=>{let cards=[...$('memegrid').children];cards.sort(()=>Math.random()-.5).forEach(c=>$('memegrid').append(c));toast('Meme-Reihenfolge neu gewürfelt 🎲')};$('memeCopyAll').onclick=()=>copyText([...$('memegrid').querySelectorAll('.memetxt strong')].map(x=>x.textContent).join('\n\n'));
$('postBtn').onclick=post;$('postInput').addEventListener('keydown',e=>{if(e.key==='Enter')post()});function post(){let val=$('postInput').value.trim();if(!val)return;let name=$('postName').value.trim()||'Azubi';let item=document.createElement('div');item.className='feeditem';let emoji=document.createElement('span');emoji.textContent=['☕','🗿','💀','✨','📣'][Math.floor(Math.random()*5)];let content=document.createElement('div'),bold=document.createElement('b'),p=document.createElement('p');bold.textContent=name;p.textContent=val;content.append(bold,p);item.append(emoji,content);$('feed').prepend(item);$('postInput').value=''}
let breathTimer=null,remaining=30;$('breathStart').onclick=()=>{if(breathTimer)return;remaining=30;$('breathNum').textContent=remaining;$('breathText').textContent='Atme ruhig ein … und langsam wieder aus.';breathTimer=setInterval(()=>{remaining--;$('breathNum').textContent=remaining;if(remaining<=0){clearInterval(breathTimer);breathTimer=null;$('breathText').textContent='Reset geschafft. Du hast dir die Pause verdient. ✨';toast('Reset abgeschlossen 🌿')}},1000)};$('breathStop').onclick=()=>{clearInterval(breathTimer);breathTimer=null;remaining=30;$('breathNum').textContent='30';$('breathText').textContent='Ein Mini-Reset für deinen Kopf. Atme ruhig und bequem.'};

// Extra-Memes
document.querySelectorAll('.copy-extra').forEach(btn=>btn.addEventListener('click',()=>{
 const text=btn.parentElement.querySelector('strong').textContent;
 if(typeof copyText==='function') copyText(text);
}));
document.getElementById('extraMemeShuffle').onclick=()=>{
 const grid=document.getElementById('extraMemes');
 [...grid.children].sort(()=>Math.random()-.5).forEach(el=>grid.append(el));
};
const extraCaptions=[...document.querySelectorAll('#extraMemes strong')].map(x=>x.textContent);
document.getElementById('randomMemeCaption').onclick=()=>{
 document.getElementById('randomMemeResult').textContent=extraCaptions[Math.floor(Math.random()*extraCaptions.length)];
};

// Video lounge: try official embed formats, with a new-tab fallback.
function showVideo(raw){
 const url=(raw||'').trim(); if(!url){document.getElementById('videoStatus').textContent='Bitte zuerst einen Video-Link einfügen.';return;}
 let parsed; try{parsed=new URL(url)}catch(e){document.getElementById('videoStatus').textContent='Das sieht nicht nach einem gültigen Link aus.';return;}
 if(!['https:','http:'].includes(parsed.protocol)){document.getElementById('videoStatus').textContent='Bitte einen http- oder https-Link verwenden.';return;}
 const host=parsed.hostname.toLowerCase().replace(/^www\./,'');
 let embed='',label='Video',ratio='video-frame';
 if(host==='youtu.be'||host.endsWith('youtube.com')){
   let id=host==='youtu.be'?parsed.pathname.split('/').filter(Boolean)[0]:(parsed.searchParams.get('v')||(parsed.pathname.match(/\/(?:shorts|embed)\/([^/?]+)/)||[])[1]);
   if(id){embed='https://www.youtube-nocookie.com/embed/'+encodeURIComponent(id);label='YouTube';ratio+=' video-wide';}
   else {document.getElementById('videoStatus').textContent='Das ist eine YouTube-Seite, aber kein konkreter Video-Link. Öffne ein Video und kopiere dessen URL.';window.open(url,'_blank','noopener');return;}
 } else if(host==='tiktok.com'||host.endsWith('.tiktok.com')){
   const match=parsed.pathname.match(/\/video\/(\d+)/);
   if(match){embed='https://www.tiktok.com/player/v1/'+match[1]+'?music_info=1&description=1';label='TikTok';}
 } else if(host==='instagram.com'||host.endsWith('.instagram.com')){
   const match=parsed.pathname.match(/\/(reel|reels|p|tv)\/([^/]+)/);
   if(match){embed='https://www.instagram.com/'+match[1]+'/'+match[2]+'/embed';label='Instagram';}
 } else if(host==='vimeo.com'||host.endsWith('.vimeo.com')){
   const match=parsed.pathname.match(/\/(\d+)/);
   if(match){embed='https://player.vimeo.com/video/'+match[1];label='Vimeo';ratio+=' video-wide';}
 }
 document.getElementById('videoShell').hidden=false;
 document.getElementById('videoExternal').href=url;
 document.getElementById('videoPlatform').textContent=label;
 const frame=document.getElementById('videoFrame'); frame.className=ratio;
 if(embed){frame.src=embed;document.getElementById('videoStatus').textContent='Player geladen – falls er leer bleibt, nutze „In neuem Tab öffnen“. Die Plattform kann das Einbetten blockieren.';}
 else {frame.removeAttribute('src');document.getElementById('videoStatus').textContent='Für diesen Link gibt es hier keinen passenden eingebetteten Player. Du kannst ihn in einem neuen Tab öffnen.';window.open(url,'_blank','noopener');}
}
document.getElementById('loadVideo').onclick=()=>showVideo(document.getElementById('videoUrl').value);
document.getElementById('videoUrl').addEventListener('keydown',e=>{if(e.key==='Enter')showVideo(e.target.value)});
document.querySelectorAll('.videoQuick').forEach(b=>b.onclick=()=>{document.getElementById('videoUrl').value=b.dataset.url;window.open(b.dataset.url,'_blank','noopener');});

// Local pass-and-play quiz duel.
const duelQs=[
 {q:'Welche Tastenkombination speichert meistens?',a:['Ctrl + S','Ctrl + P','Alt + F4','Shift + Panik'],c:0},
 {q:'Was ist bei einer E-Mail eine Blindkopie?',a:['CC','BCC','PDF','ZIP'],c:1},
 {q:'Wie viele Minuten hat eine Viertelstunde?',a:['10','12','15','20'],c:2},
 {q:'Welche Dateiendung hat eine typische Excel-Datei?',a:['.xlsx','.mp3','.png','.exe'],c:0},
 {q:'Was ist die beste Reaktion auf „kurze Frage“?',a:['Kalender öffnen','Innerlich seufzen','Beides','Laptop zuklappen'],c:2},
 {q:'Wofür steht PDF?',a:['Portable Document Format','Personal Data Folder','Pretty Difficult File','Print Done Fast'],c:0},
 {q:'Was rettet den Bürotag oft?',a:['Kaffee','Druckerfehler','Meeting','Passwort abgelaufen'],c:0},
 {q:'Welche Taste macht meistens einen Zeilenumbruch?',a:['Esc','Enter','Tab','Caps Lock'],c:1},
 {q:'Was ist ein Meeting, das auch eine Mail hätte sein können?',a:['Effizienz','Ein Klassiker','Ein Betriebssystem','Ein Dateiformat'],c:1},
 {q:'Was bedeutet „EOD“ im Arbeitskontext oft?',a:['End of Day','Excel on Demand','Email of Doom','End of Download'],c:0}
];
let dqIndex=0,dqTurn=0,dqScores=[0,0],dqLocked=false;
function duelNames(){
 const a=document.getElementById('playerOne').value.trim()||'Team 1',b=document.getElementById('playerTwo').value.trim()||'Team 2';
 document.getElementById('nameOne').textContent=a;document.getElementById('nameTwo').textContent=b;
 document.getElementById('reactNameOne').textContent=a;document.getElementById('reactNameTwo').textContent=b;
}
function renderDuel(){
 duelNames();const q=duelQs[dqIndex%duelQs.length];document.getElementById('duelQuestion').textContent=q.q;
 document.getElementById('turnLabel').textContent=(dqTurn===0?(document.getElementById('playerOne').value.trim()||'Team 1'):(document.getElementById('playerTwo').value.trim()||'Team 2'))+' ist dran';
 const box=document.getElementById('duelChoices');box.innerHTML='';dqLocked=false;
 q.a.forEach((answer,i)=>{const b=document.createElement('button');b.textContent=answer;b.onclick=()=>{if(dqLocked)return;dqLocked=true;const ok=i===q.c;if(ok)dqScores[dqTurn]++;document.getElementById('scoreOne').textContent=dqScores[0];document.getElementById('scoreTwo').textContent=dqScores[1];document.getElementById('duelResult').textContent=ok?'Richtig – Punkt für '+(dqTurn===0?(document.getElementById('playerOne').value.trim()||'Team 1'):(document.getElementById('playerTwo').value.trim()||'Team 2'))+'!':'Leider falsch. Richtige Antwort: '+q.a[q.c];[...box.children].forEach((el,j)=>{el.disabled=true;if(j===q.c)el.style.borderColor='var(--lime)';else if(j===i)el.style.borderColor='var(--pink)';});};box.append(b);});
 document.getElementById('duelResult').textContent='Antwort auswählen.';
}
document.getElementById('nextDuel').onclick=()=>{dqIndex++;dqTurn=1-dqTurn;renderDuel()};
document.getElementById('resetDuel').onclick=()=>{dqIndex=0;dqTurn=0;dqScores=[0,0];document.getElementById('scoreOne').textContent='0';document.getElementById('scoreTwo').textContent='0';renderDuel()};
document.getElementById('playerOne').addEventListener('input',duelNames);document.getElementById('playerTwo').addEventListener('input',duelNames);renderDuel();

// Reaction duel, two players take turns on one device.
let drRound=0,drState='idle',drTimer=null,drStart=0,drTimes=[null,null];
function duelArena(title,txt,cls=''){const a=document.getElementById('duelArena');a.className='arena '+cls;document.getElementById('duelArenaTitle').textContent=title;document.getElementById('duelArenaText').textContent=txt;}
function updateReactScores(){document.getElementById('reactScoreOne').textContent=drTimes[0]===null?'–':drTimes[0]+' ms';document.getElementById('reactScoreTwo').textContent=drTimes[1]===null?'–':drTimes[1]+' ms';}
document.getElementById('duelReactStart').onclick=()=>{if(drState==='wait'||drState==='ready')return;drState='wait';duelArena('Nicht klicken …',(drRound===0?'Team 1':'Team 2')+' ist dran. Warte auf Grün.','wait');drTimer=setTimeout(()=>{drState='ready';drStart=performance.now();duelArena('JETZT KLICKEN!','Jetzt!','ready');},1000+Math.random()*2500);};
document.getElementById('duelArena').onclick=()=>{if(drState==='wait'){clearTimeout(drTimer);drState='idle';duelArena('Zu früh!','Punkt für den Gegner.');document.getElementById('duelReactResult').textContent='Zu früh geklickt – Runde neu starten.';drTimes[drRound]=9999;drRound=1-drRound;updateReactScores();}else if(drState==='ready'){drTimes[drRound]=Math.round(performance.now()-drStart);drState='idle';duelArena(drTimes[drRound]+' ms','Nächster ist '+(drRound===0?'Team 2':'Team 1')+' – jetzt Start drücken.');drRound=1-drRound;updateReactScores();if(drTimes[0]!==null&&drTimes[1]!==null){let win=drTimes[0]===drTimes[1]?'Unentschieden':drTimes[0]<drTimes[1]?(document.getElementById('playerOne').value.trim()||'Team 1')+' gewinnt!':(document.getElementById('playerTwo').value.trim()||'Team 2')+' gewinnt!';document.getElementById('duelReactResult').textContent=win;}}};
document.getElementById('duelReactReset').onclick=()=>{clearTimeout(drTimer);drRound=0;drState='idle';drTimes=[null,null];updateReactScores();duelArena('Bereit?','Erst Team 1, dann Team 2. Nicht zu früh klicken.');document.getElementById('duelReactResult').textContent='';};
const captionPrompts=[['🖨️💀','Drucker hat den Auftrag abgelehnt'],['☕🫠','Kaffee leer, System instabil'],['📧👀','„Nur zur Info“ um 16:59 Uhr'],['📊🔥','Excel sieht anders aus als im Kopf'],['🧍‍♂️🚪','Wenn jemand „kurze Besprechung“ sagt'],['🗂️🫥','Die Datei ist irgendwo. Ganz sicher.'],['🕒🏃','Feierabend wurde gesichtet']];
let cp=0;document.getElementById('captionPrompt').onclick=()=>{cp=(cp+1)%captionPrompts.length;document.getElementById('captionEmoji').textContent=captionPrompts[cp][0];document.getElementById('captionResult').textContent='Motiv: '+captionPrompts[cp][1]+'. Schreibt eure Captions und stimmt ab.'};
document.getElementById('captionVoteOne').onclick=()=>{dqScores[0]++;document.getElementById('scoreOne').textContent=dqScores[0];document.getElementById('captionResult').textContent='Punkt für '+(document.getElementById('playerOne').value.trim()||'Team 1')+'.';};
document.getElementById('captionVoteTwo').onclick=()=>{dqScores[1]++;document.getElementById('scoreTwo').textContent=dqScores[1];document.getElementById('captionResult').textContent='Punkt für '+(document.getElementById('playerTwo').value.trim()||'Team 2')+'.';};


// ---------------- Arcade: 2D Azubi Runner ----------------
(()=>{
 const c=document.getElementById('runnerCanvas'),ctx=c.getContext('2d');
 const scoreEl=document.getElementById('runnerScore'),bestEl=document.getElementById('runnerBest');
 let running=false,paused=false,over=false,last=0,spawn=0,score=0,speed=330,obstacles=[],coffee=[],dust=[];
 const floor=408,player={x:130,y:floor-66,w:48,h:66,vy:0,ground:true,duck:false};
 let best=0;try{best=Number(localStorage.getItem('azubiRunnerBest')||0)}catch(e){} bestEl.textContent=best;
 function reset(){score=0;speed=330;spawn=0;obstacles=[];coffee=[];dust=[];player.y=floor-player.h;player.vy=0;player.ground=true;player.duck=false;over=false;paused=false;scoreEl.textContent='0';}
 function jump(){if(!running){start();return}if(over){start();return}if(player.ground&&!paused){player.vy=-700;player.ground=false;}}
 function start(){reset();running=true;last=performance.now();requestAnimationFrame(loop)}
 function rect(x,y,w,h,col){ctx.fillStyle=col;ctx.fillRect(x,y,w,h)}
 function draw(t){
  const g=ctx.createLinearGradient(0,0,0,500);g.addColorStop(0,'#17172e');g.addColorStop(1,'#25233d');ctx.fillStyle=g;ctx.fillRect(0,0,800,500);
  // windows and skyline
  for(let i=0;i<7;i++){rect(i*130+20,65,68,105,'#252d4b');for(let j=0;j<3;j++)rect(i*130+29+j*18,78,9,13,'#7e8cff55')}
  rect(0,floor,800,92,'#20202e');rect(0,floor,800,5,'#d9ff65');
  for(let x=-(t*.22%80);x<820;x+=80)rect(x,floor+45,42,4,'#ffffff22');
  // coffee collectibles
  coffee.forEach(o=>{ctx.font='32px system-ui';ctx.fillText('☕',o.x,o.y)});
  obstacles.forEach(o=>{if(o.type==='box'){rect(o.x,o.y,o.w,o.h,'#a56b4d');rect(o.x+5,o.y+7,o.w-10,7,'#e7b28b');rect(o.x+o.w/2-3,o.y,6,o.h,'#6e473b')}else{rect(o.x,o.y,o.w,o.h,'#7e8cff');rect(o.x+6,o.y+6,o.w-12,8,'#b8c1ff');rect(o.x+6,o.y+o.h-10,o.w-12,4,'#343c79') }});
  // player
  const ph=player.duck&&player.ground?36:66,py=player.duck&&player.ground?floor-ph:player.y;
  rect(player.x+5,py+9,player.w-10,ph-8,'#d9ff65');rect(player.x+10,py+18,player.w-20,15,'#20202e');rect(player.x+30,py+20,5,5,'#fff');
  rect(player.x+3,py+ph-4,15,4,'#ff58c8');rect(player.x+28,py+ph-4,15,4,'#ff58c8');
  ctx.fillStyle='#f6f4ff';ctx.font='bold 18px system-ui';ctx.fillText('PAUSE / RUN',22,32);
  if(!running||over||paused){ctx.fillStyle='#050611bb';ctx.fillRect(0,0,800,500);ctx.textAlign='center';ctx.fillStyle='#fff';ctx.font='bold 34px system-ui';ctx.fillText(over?'Game Over':paused?'Pausiert':'AZUBI RUNNER',400,220);ctx.font='18px system-ui';ctx.fillStyle='#d9ff65';ctx.fillText(over?'Start drücken und neuen Highscore holen':paused?'Pause drücken zum Weiterspielen':'Drück „Spiel starten“ oder Leertaste',400,260);ctx.textAlign='left'}
 }
 function loop(now){
  if(!running)return;const dt=Math.min((now-last)/1000,.04);last=now;
  if(!paused&&!over){
   score+=dt*10;speed+=dt*4;spawn-=dt;
   if(spawn<=0){let type=Math.random()<.72?'box':'cabinet';obstacles.push({x:830,y:type==='box'?floor-48:floor-85,w:type==='box'?42:54,h:type==='box'?48:85,type});spawn=Math.max(.65,1.4-Math.min(score/1000,.55))+Math.random()*.65;
    if(Math.random()<.8)coffee.push({x:900,y:floor-95-Math.random()*80})}
   obstacles.forEach(o=>o.x-=speed*dt);coffee.forEach(o=>o.x-=speed*dt);
   obstacles=obstacles.filter(o=>o.x+o.w>0);coffee=coffee.filter(o=>o.x>-30);
   player.vy+=1700*dt;player.y+=player.vy*dt;if(player.y>=floor-player.h){player.y=floor-player.h;player.vy=0;player.ground=true}
   const ph=player.duck&&player.ground?36:66,py=player.duck&&player.ground?floor-ph:player.y;
   for(const o of obstacles){if(player.x+player.w-7>o.x&&player.x+8<o.x+o.w&&py+ph-5>o.y+5&&py+7<o.y+o.h){over=true;running=false;break}}
   coffee=coffee.filter(o=>{if(player.x+player.w>o.x&&player.x<o.x+30&&Math.abs((player.y+20)-o.y)<70){score+=25;return false}return true});
   scoreEl.textContent=Math.floor(score);if(Math.floor(score)>best){best=Math.floor(score);bestEl.textContent=best;try{localStorage.setItem('azubiRunnerBest',best)}catch(e){}}
  }
  draw(now);if(running)requestAnimationFrame(loop);
 }
 document.getElementById('runnerStart').onclick=start;
 document.getElementById('runnerPause').onclick=()=>{if(!running&&over)return;if(!running)return;paused=!paused;};
 document.getElementById('runnerJump').onclick=jump;
 document.getElementById('runnerDuck').onpointerdown=()=>player.duck=true;
 document.getElementById('runnerDuck').onpointerup=()=>player.duck=false;
 document.getElementById('runnerDuck').onpointerleave=()=>player.duck=false;
 window.addEventListener('keydown',e=>{if(['ArrowUp','ArrowDown',' '].includes(e.key)&&document.activeElement.tagName!=='INPUT'&&document.activeElement.tagName!=='TEXTAREA'){e.preventDefault();if(e.repeat)return;if(e.key==='ArrowDown')player.duck=true;else jump()}});
 window.addEventListener('keyup',e=>{if(e.key==='ArrowDown')player.duck=false});
 draw(0);
})();

// ---------------- Arcade: pseudo-3D Office Rush ----------------
(()=>{
 const c=document.getElementById('rushCanvas'),ctx=c.getContext('2d');
 let running=false,paused=false,over=false,last=0,score=0,speed=0.45,spawn=0,lane=1,jumping=0,items=[],best=0;
 const scoreEl=document.getElementById('rushScore'),bestEl=document.getElementById('rushBest');
 try{best=Number(localStorage.getItem('officeRushBest')||0)}catch(e){}bestEl.textContent=best;
 function reset(){score=0;speed=.45;spawn=.4;lane=1;jumping=0;items=[];over=false;paused=false;scoreEl.textContent='0'}
 function start(){reset();running=true;last=performance.now();requestAnimationFrame(loop)}
 function move(n){lane=Math.max(0,Math.min(2,lane+n))}
 function jump(){if(!running){start();return}if(!over&&!paused)jumping=1}
 function project(z){return {y:120+Math.pow(z,1.65)*380,x:400+(z*260),w:40+z*450}}
 function draw(now){
  const sky=ctx.createLinearGradient(0,0,0,500);sky.addColorStop(0,'#141a37');sky.addColorStop(1,'#3b3151');ctx.fillStyle=sky;ctx.fillRect(0,0,800,500);
  // distant office skyline
  for(let i=0;i<10;i++){let x=i*92-12;let h=55+(i*37%80);ctx.fillStyle=i%2?'#252c4b':'#20243e';ctx.fillRect(x,145-h,68,h);for(let y=155-h;y<140;y+=17)for(let xx=x+9;xx<x+60;xx+=17){ctx.fillStyle='#d9ff6522';ctx.fillRect(xx,y,7,7)}}
  // road trapezoid
  ctx.fillStyle='#171923';ctx.beginPath();ctx.moveTo(310,125);ctx.lineTo(490,125);ctx.lineTo(790,500);ctx.lineTo(10,500);ctx.closePath();ctx.fill();
  ctx.strokeStyle='#d9ff6588';ctx.lineWidth=4;ctx.beginPath();ctx.moveTo(310,125);ctx.lineTo(10,500);ctx.moveTo(490,125);ctx.lineTo(790,500);ctx.stroke();
  for(let i=1;i<=2;i++){ctx.strokeStyle='#ffffff55';ctx.lineWidth=3;ctx.beginPath();ctx.moveTo(400+(i-1)*60,125);ctx.lineTo(400+(i-1)*60-200,500);ctx.stroke()}
  // moving lane markers
  for(let k=0;k<9;k++){let z=((k/9+(now/1500*speed)%1)%1);let y=130+z*z*370;let wid=2+z*6;ctx.fillStyle='#ffffff88';ctx.fillRect(400-wid/2,y,wid,8+z*24)}
  items.forEach(o=>{const p=project(o.z),x=400+(o.lane-1)*p.w*.43;const size=16+o.z*72;ctx.save();ctx.translate(x,p.y);ctx.fillStyle=o.type==='coffee'?'#d9ff65':o.type==='cart'?'#ff58c8':'#7e8cff';ctx.fillRect(-size/2,-size,size,size);ctx.fillStyle='#141423';ctx.fillRect(-size/2+size*.18,-size*.75,size*.64,size*.15);ctx.fillStyle='#fff';ctx.font=`${Math.max(10,size*.48)}px system-ui`;ctx.textAlign='center';ctx.fillText(o.type==='coffee'?'☕':o.type==='cart'?'▦':'!',0,-size*.22);ctx.restore()});
  // player perspective character
  const px=400+(lane-1)*95,py=415-(jumping>0?Math.sin(jumping*Math.PI)*100:0);
  ctx.fillStyle='#d9ff65';ctx.fillRect(px-23,py-58,46,58);ctx.fillStyle='#1a1b2a';ctx.fillRect(px-14,py-45,28,15);ctx.fillStyle='#fff';ctx.fillRect(px+5,py-42,4,4);ctx.fillStyle='#ff58c8';ctx.fillRect(px-25,py-7,18,7);ctx.fillRect(px+7,py-7,18,7);
  ctx.fillStyle='#fff';ctx.font='bold 18px system-ui';ctx.fillText('OFFICE RUSH',22,32);
  if(!running||paused||over){ctx.fillStyle='#050611bb';ctx.fillRect(0,0,800,500);ctx.textAlign='center';ctx.fillStyle='#fff';ctx.font='bold 32px system-ui';ctx.fillText(over?'Crash!':paused?'Pausiert':'OFFICE RUSH',400,220);ctx.font='18px system-ui';ctx.fillStyle='#d9ff65';ctx.fillText(over?'Neustart und neue Bestzeit?':paused?'Pause drücken zum Weiterspielen':'Wechsle die Spur und weich aus!',400,260);ctx.textAlign='left'}
 }
 function loop(now){if(!running)return;let dt=Math.min((now-last)/1000,.04);last=now;
  if(!paused&&!over){score+=dt*12;speed=Math.min(.95,speed+dt*.006);spawn-=dt;
   if(spawn<=0){const ln=Math.floor(Math.random()*3);items.push({lane:ln,z:0,type:Math.random()<.2?'coffee':Math.random()<.5?'cart':'box'});spawn=Math.max(.5,1.1-score/1500)+Math.random()*.35}
   items.forEach(o=>o.z+=dt*speed);items=items.filter(o=>o.z<1.1);
   if(jumping>0)jumping+=dt*1.9;if(jumping>=1){jumping=0}
   for(const o of items){if(o.z>.91&&o.z<1.02&&o.lane===lane){if(o.type==='coffee'){score+=35;o.z=1.2}else if(jumping===0){over=true;running=false;break}}}
   scoreEl.textContent=Math.floor(score);if(Math.floor(score)>best){best=Math.floor(score);bestEl.textContent=best;try{localStorage.setItem('officeRushBest',best)}catch(e){}}
  }draw(now);if(running)requestAnimationFrame(loop)}
 document.getElementById('rushStart').onclick=start;document.getElementById('rushPause').onclick=()=>{if(running)paused=!paused};
 document.getElementById('rushLeft').onclick=()=>move(-1);document.getElementById('rushRight').onclick=()=>move(1);document.getElementById('rushJump').onclick=jump;
 window.addEventListener('keydown',e=>{if(document.activeElement.tagName==='INPUT'||document.activeElement.tagName==='TEXTAREA')return;if(['ArrowLeft','ArrowRight','ArrowUp',' '].includes(e.key)){e.preventDefault();if(e.repeat)return;if(e.key==='ArrowLeft'||e.key.toLowerCase()==='a')move(-1);else if(e.key==='ArrowRight'||e.key.toLowerCase()==='d')move(1);else jump()}else if(e.key.toLowerCase()==='a')move(-1);else if(e.key.toLowerCase()==='d')move(1)});
 draw(0);
})();

</script>
</body></html>
