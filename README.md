<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width,initial-scale=1"><meta name="theme-color" content="#0b0b14">
<title>Pause — Azubi Hub</title>
<style>
:root{--bg:#0b0b14;--card:#171725;--card2:#202035;--text:#f6f4ff;--muted:#a7a5bf;--pink:#ff58c8;--lime:#d9ff65;--blue:#7e8cff;--line:#33334b;--orange:#ffad5c}
*{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;background:radial-gradient(ellipse at 5% 0%,#3b174b 0,transparent 35%),radial-gradient(ellipse at 100% 15%,#142f52 0,transparent 32%),var(--bg);color:var(--text);font-family:Inter,system-ui,Segoe UI,Arial,sans-serif}button,input,textarea,select{font:inherit}.wrap{max-width:1080px;margin:auto;padding:18px 18px 60px}.nav{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap}.brand{display:flex;gap:10px;align-items:center;font-weight:1000;letter-spacing:-.8px}.brandmark{width:45px;height:45px;border-radius:15px;display:grid;place-items:center;background:linear-gradient(135deg,var(--pink),#8876ff);font-size:24px;box-shadow:0 0 30px #ff58c84a}.navlinks{display:flex;gap:8px;flex-wrap:wrap}.navlinks a{color:var(--muted);text-decoration:none;padding:9px 11px;border:1px solid var(--line);border-radius:11px;font-size:12px}.navlinks a:hover{color:var(--lime);border-color:var(--lime)}.status{font-size:12px;color:var(--lime);border:1px solid #d9ff6540;border-radius:99px;padding:8px 11px;background:#d9ff650c}.hero{display:grid;grid-template-columns:1.2fr .8fr;gap:24px;align-items:center;padding:52px 0 36px}.eyebrow{font-size:11px;font-weight:950;letter-spacing:2px;color:var(--lime);text-transform:uppercase}.hero h1{font-size:clamp(42px,7vw,82px);line-height:.92;letter-spacing:-4px;margin:15px 0}.hero h1 span{background:linear-gradient(90deg,var(--pink),#b7a0ff,var(--lime));background-clip:text;color:transparent}.hero p{max-width:610px;color:var(--muted);line-height:1.7;font-size:16px}.actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:20px}.btn{border:0;border-radius:12px;padding:11px 15px;font-weight:850;cursor:pointer;background:var(--pink);color:#1c1020;transition:.15s}.btn:hover{transform:translateY(-2px);filter:brightness(1.08)}.btn.alt{background:#ffffff0c;color:var(--text);border:1px solid var(--line)}.btn.lime{background:var(--lime);color:#1b220d}.btn.blue{background:var(--blue);color:#111426}.heroart{position:relative;min-height:300px;border:1px solid var(--line);border-radius:28px;overflow:hidden;background:linear-gradient(150deg,#251338,#111b35 60%,#28213c);display:grid;place-items:center}.heroart:before,.heroart:after{content:"";position:absolute;border-radius:50%;filter:blur(1px)}.heroart:before{width:210px;height:210px;background:#ff58c826;top:-65px;right:-45px}.heroart:after{width:160px;height:160px;background:#d9ff6520;bottom:-55px;left:-30px}.heroemoji{font-size:clamp(65px,10vw,110px);z-index:1;filter:drop-shadow(0 15px 18px #0008);animation:float 4s ease-in-out infinite}.sticker{position:absolute;z-index:2;padding:9px 12px;border-radius:12px;font-size:12px;font-weight:1000;transform:rotate(-8deg);background:var(--lime);color:#1a200b}.sticker.s1{top:25px;left:20px}.sticker.s2{right:15px;bottom:34px;background:var(--pink);transform:rotate(7deg);color:#210e21}.sticker.s3{bottom:23px;left:22px;background:#fff;color:#161625;transform:rotate(-5deg)}@keyframes float{0%,100%{transform:translateY(0) rotate(-3deg)}50%{transform:translateY(-13px) rotate(3deg)}}.ticker{overflow:hidden;border-block:1px solid var(--line);background:#ffffff05;white-space:nowrap;padding:12px 0;color:var(--lime);font-size:12px;font-weight:950;letter-spacing:1px}.ticker span{display:inline-block;min-width:100%;animation:marquee 24s linear infinite}@keyframes marquee{to{transform:translateX(-100%)}}.sectionhead{display:flex;align-items:end;justify-content:space-between;gap:15px;margin:36px 0 15px}.sectionhead h2{font-size:25px;letter-spacing:-1px;margin:5px 0}.sectionhead p{margin:0;color:var(--muted);font-size:13px}.grid{display:grid;grid-template-columns:repeat(12,minmax(0,1fr));gap:15px}.card{min-width:0;border:1px solid var(--line);border-radius:20px;padding:19px;background:linear-gradient(145deg,#202033ee,#151520f2);box-shadow:0 15px 35px #0002}.s8{grid-column:span 8}.s6{grid-column:span 6}.s4{grid-column:span 4}.s12{grid-column:span 12}.head{display:flex;gap:11px;align-items:center;margin-bottom:15px}.iconbox{height:43px;width:43px;border-radius:14px;display:grid;place-items:center;background:#ffffff0c;font-size:22px;flex-shrink:0}.head h3{margin:0 0 3px;font-size:18px;letter-spacing:-.4px}.sub{color:var(--muted);font-size:12px;margin:0;line-height:1.5}.big{font-size:clamp(21px,3vw,30px);line-height:1.2;font-weight:900;letter-spacing:-.8px;margin:18px 0;min-height:65px}.result{color:var(--lime);font-weight:800;font-size:13px;min-height:22px;margin-top:11px}.row{display:flex;gap:8px;flex-wrap:wrap;align-items:center}.pill{border:1px solid var(--line);border-radius:99px;padding:7px 10px;color:var(--muted);font-size:11px}.tiles{display:grid;grid-template-columns:repeat(3,1fr);gap:9px}.tile{border:1px solid var(--line);border-radius:14px;padding:13px 10px;background:#ffffff06;cursor:pointer;text-align:left;color:var(--text);min-height:90px}.tile:hover{border-color:var(--pink);background:#ff58c80d}.tile strong{display:block;margin:7px 0 4px;font-size:13px}.tile small{color:var(--muted);font-size:11px;line-height:1.3;display:block}.tile .em{font-size:25px}.options{display:grid;grid-template-columns:1fr 1fr;gap:9px}.option{border:1px solid var(--line);background:#ffffff07;border-radius:13px;color:var(--text);padding:14px;min-height:60px;text-align:left;cursor:pointer;font-weight:800}.option:hover,.option.selected{border-color:var(--pink);background:#ff58c817}.arena{background:#0c0c14;border:1px solid var(--line);border-radius:15px;min-height:125px;display:grid;place-items:center;text-align:center;padding:20px;cursor:pointer;user-select:none;margin:10px 0}.arena strong{font-size:20px}.arena p{color:var(--muted);font-size:12px}.arena.wait{background:#51202d}.arena.ready{background:#24442e}.bingo{display:grid;grid-template-columns:repeat(3,1fr);gap:7px;margin:12px 0}.bingo button{border:1px solid var(--line);background:#ffffff07;color:var(--text);border-radius:10px;min-height:69px;padding:8px 5px;font-size:11px;font-weight:800;cursor:pointer}.bingo button.done{border-color:var(--lime);background:#d9ff6517;color:var(--lime)}.meter{height:9px;background:#ffffff13;border-radius:99px;overflow:hidden;margin:12px 0}.meter div{height:100%;background:linear-gradient(90deg,var(--pink),var(--lime));width:50%;transition:width .3s}.inputrow{display:flex;gap:8px}.inputrow input,.inputrow textarea,.inputrow select{min-width:0;flex:1;background:#101018;border:1px solid var(--line);border-radius:12px;padding:12px;color:var(--text);outline:none}.feed{display:grid;gap:8px;margin-top:12px}.feeditem{display:flex;gap:10px;padding:12px;border:1px solid #ffffff0b;background:#ffffff06;border-radius:12px;overflow-wrap:anywhere}.feeditem b{color:var(--lime);font-size:12px}.feeditem p{margin:3px 0 0;line-height:1.45;font-size:13px}.memegrid{display:grid;grid-template-columns:repeat(4,1fr);gap:11px}.meme{overflow:hidden;border-radius:15px;border:1px solid var(--line);background:#101019}.memeart{aspect-ratio:1/1;display:grid;place-items:center;font-size:clamp(42px,6vw,70px);position:relative;overflow:hidden}.memeart:after{content:"";position:absolute;inset:0;background:linear-gradient(135deg,#ffffff12,transparent 55%)}.meme:nth-child(1) .memeart{background:linear-gradient(135deg,#40316d,#e85ba6)}.meme:nth-child(2) .memeart{background:linear-gradient(135deg,#133d42,#d9ff65)}.meme:nth-child(3) .memeart{background:linear-gradient(135deg,#2c2455,#777bff)}.meme:nth-child(4) .memeart{background:linear-gradient(135deg,#73351e,#ffad5c)}.meme:nth-child(5) .memeart{background:linear-gradient(135deg,#173c63,#57d5ff)}.meme:nth-child(6) .memeart{background:linear-gradient(135deg,#4b1f37,#ff7ca9)}.meme:nth-child(7) .memeart{background:linear-gradient(135deg,#293b22,#a5df57)}.meme:nth-child(8) .memeart{background:linear-gradient(135deg,#222,#888)}.memetxt{padding:10px}.memetxt strong{font-size:12px;line-height:1.4;display:block}.memetxt button{margin-top:8px;width:100%;padding:7px;border:1px solid var(--line);background:#ffffff08;color:var(--muted);border-radius:9px;font-size:11px;cursor:pointer}.prompt{padding:14px;border-radius:13px;border:1px solid var(--line);background:#ffffff06;margin:8px 0}.prompt strong{color:var(--pink)}.prompt p{font-size:13px;color:#d9d8e7;line-height:1.5;margin:6px 0 0}.quizanswers{display:grid;gap:8px}.quizanswers button{padding:11px;text-align:left;background:#ffffff08;border:1px solid var(--line);color:var(--text);border-radius:11px;cursor:pointer}.quizanswers button:hover{border-color:var(--blue)}.countdown{font-size:44px;font-weight:1000;letter-spacing:-2px;margin:8px 0}.footer{text-align:center;color:var(--muted);font-size:11px;line-height:1.7;padding:30px 0}.toast{position:fixed;bottom:20px;left:50%;transform:translateX(-50%);background:var(--lime);color:#171b0b;padding:12px 17px;border-radius:12px;font-weight:900;display:none;z-index:10;box-shadow:0 10px 30px #0007}.toast.show{display:block}@media(max-width:800px){.hero{grid-template-columns:1fr;padding-top:35px}.heroart{min-height:240px}.s8,.s6,.s4{grid-column:span 12}.memegrid{grid-template-columns:repeat(2,1fr)}.tiles{grid-template-columns:1fr 1fr}.hero h1{letter-spacing:-2px}.navlinks{display:none}}@media(max-width:420px){.memegrid{grid-template-columns:1fr 1fr}.tiles{grid-template-columns:1fr}.card{padding:15px}.wrap{padding-inline:12px}}
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


<style>
.random-video-layout{display:grid;grid-template-columns:minmax(220px,340px) 1fr;gap:18px;align-items:center}
.random-video-frame{width:100%;aspect-ratio:9/16;max-height:560px;background:#070810;border-radius:16px;overflow:hidden;border:1px solid var(--line)}
.random-video-frame iframe{width:100%;height:100%;border:0}
.random-video-info{display:flex;flex-direction:column;align-items:flex-start;gap:10px}.random-video-info h3{margin:0;font-size:24px}
.memory-board{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:8px}
.memory-card{aspect-ratio:1/1;border:1px solid var(--line);border-radius:12px;background:linear-gradient(145deg,#24243b,#12121f);color:var(--text);font-size:clamp(20px,3vw,34px);font-weight:900;cursor:pointer;transition:transform .12s,border-color .12s}
.memory-card:hover{border-color:var(--lime);transform:translateY(-1px)}
.memory-card.flipped,.memory-card.matched{background:#d9ff6517;border-color:var(--lime)}
.memory-card.matched{cursor:default;opacity:.72}
@media(max-width:760px){.random-video-layout{grid-template-columns:1fr}.random-video-frame{max-width:360px;margin:0 auto;width:100%}.random-video-info{align-items:stretch}}
</style>


<style>
.leaderboard-table th{color:var(--muted);font-size:12px;text-transform:uppercase;letter-spacing:.5px}
.leaderboard-table td{padding:12px 10px;border-bottom:1px solid #ffffff0c}
.leaderboard-table tbody tr:first-child td:first-child{font-weight:900;color:var(--lime)}
.multi-top{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap;margin-bottom:16px}
.multi-controls{display:flex;gap:10px;flex-wrap:wrap;align-items:center;margin-bottom:14px}
.multi-join{display:flex;gap:8px;flex:1;min-width:210px}
.multi-join input{min-width:0;width:100%;border:1px solid var(--line);border-radius:12px;background:#ffffff08;color:var(--text);padding:11px 13px;text-transform:uppercase}
.room-code-panel{display:flex;gap:12px;align-items:center;flex-wrap:wrap;background:#d9ff6510;border:1px solid #d9ff6544;border-radius:14px;padding:12px;margin:10px 0 16px}
.room-code-panel span{font-size:10px;letter-spacing:1.5px;color:var(--muted);font-weight:900}.room-code-panel strong{font-size:25px;letter-spacing:5px;color:var(--lime)}
.multi-game-layout{display:grid;grid-template-columns:minmax(0,1.6fr) minmax(210px,.8fr);gap:16px;align-items:start}
.multi-side{border:1px solid var(--line);border-radius:14px;padding:14px;background:#ffffff04}
.multi-side h3{margin:0 0 12px}.multi-score-list{list-style:none;margin:0;padding:0;display:grid;gap:8px}
.multi-score-list li{display:flex;justify-content:space-between;gap:8px;padding:10px;border:1px solid var(--line);border-radius:10px;background:#ffffff05}
.multi-score-list .me{border-color:var(--lime);color:var(--lime)}
.multi-mobile{max-width:280px;margin-left:auto;margin-right:auto}
@media(max-width:800px){.multi-game-layout{grid-template-columns:1fr}.multi-join{order:2}.multi-controls>.btn{flex:1}}
</style>


<style>
/* Extra-Breite: gestaltete Seitenrails, ohne den Content zu überdecken */
.side-rail{position:fixed;top:50%;transform:translateY(-50%);width:138px;min-height:610px;display:flex;flex-direction:column;align-items:center;gap:17px;z-index:0;pointer-events:none;color:#f2f3f7;opacity:.96}
.rail-left{left:max(14px,calc((100vw - 1370px)/2))}.rail-right{right:max(14px,calc((100vw - 1370px)/2))}
.rail-logo{width:58px;height:58px;display:grid;place-items:center;border-radius:19px;background:linear-gradient(140deg,#ff58c8,#8a78ff);font-size:31px;font-weight:1000;box-shadow:0 0 35px #ff58c82b;transform:rotate(-7deg)}.rail-logo span{color:#d9ff65}
.rail-label{writing-mode:vertical-rl;letter-spacing:3px;font-size:10px;color:#9295aa;font-weight:900}
.rail-card{width:122px;min-height:120px;border:1px solid #ffffff1d;border-radius:20px;padding:13px;background:linear-gradient(145deg,#24263a,#151620);display:flex;flex-direction:column;gap:5px;transform:rotate(-3deg);box-shadow:0 14px 35px #0004}
.rail-card span{font-size:9px;letter-spacing:2px;color:#a9adc0;font-weight:900}.rail-card strong{font-size:29px;letter-spacing:-2px}.rail-card small{font-size:10px;line-height:1.3;color:#a9adc0}.rail-pink strong{color:#ff58c8}.rail-lime{transform:rotate(3deg)}.rail-lime strong{color:#d9ff65}
.rail-sticker{font-size:10px;font-weight:1000;letter-spacing:1px;padding:10px 12px;border-radius:9px;background:#d9ff65;color:#171b0b;transform:rotate(7deg);box-shadow:0 7px 18px #0003}.rail-sticker-blue{background:#91a7ff;color:#101323;transform:rotate(-6deg)}
.rail-orbit{position:relative;width:100px;height:100px;border:1px solid #ff58c84c;border-radius:50%;animation:railspin 16s linear infinite}.rail-orbit:before,.rail-orbit:after{content:"";position:absolute;inset:12px;border:1px dashed #91a7ff66;border-radius:50%}.rail-orbit:after{inset:27px;border-color:#d9ff6566}.rail-orbit i,.rail-orbit b,.rail-orbit em{position:absolute;width:10px;height:10px;border-radius:50%;background:#ff58c8;box-shadow:0 0 18px #ff58c8;left:5px;top:40px}.rail-orbit b{background:#d9ff65;left:65px;top:17px}.rail-orbit em{background:#91a7ff;left:42px;top:79px}
.rail-mini-game{width:120px;padding:10px;border:1px solid #ffffff1b;background:#151722;border-radius:17px;transform:rotate(4deg)}.mini-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:5px}.mini-grid i{height:25px;border-radius:6px;display:grid;place-items:center;background:#ffffff0a;color:#91a7ff;font-style:normal}.mini-grid i:nth-child(3n+1){color:#ff58c8}.mini-grid i:nth-child(5){color:#d9ff65}.rail-mini-game small{display:block;text-align:center;font-size:8px;letter-spacing:2px;color:#9295aa;margin-top:9px}
.rail-ticker{writing-mode:vertical-rl;font-size:9px;letter-spacing:3px;color:#6f7286;font-weight:900;flex:1;max-height:100px;overflow:hidden}
@keyframes railspin{to{transform:rotate(360deg)}}
.multi-game-layout{gap:20px}.multi-game-layout>div:first-child{min-width:0}.arcade-canvas{border-radius:18px;border:1px solid #ffffff1a;box-shadow:0 0 0 1px #ff58c812,0 18px 50px #0005}.multi-side{background:linear-gradient(155deg,#1d2030,#11131b);border:1px solid #ffffff15;border-radius:18px;padding:16px}.multi-side h3{font-size:16px;letter-spacing:-.4px}.multi-score-list li{padding:10px 11px;border:1px solid #ffffff0c;background:#ffffff05;border-radius:11px}.multi-score-list li.me{border-color:#d9ff6566;background:#d9ff6510}.multi-score-list strong{color:#d9ff65}.multi-mobile{justify-content:center}.multi-mobile #multiBoost{margin-left:8px}.random-video-frame{box-shadow:0 20px 50px #0005;border:1px solid #ffffff20}
@media(max-width:1480px){.side-rail{display:none}.wrap{max-width:1120px}}
@media(max-width:800px){.wrap{max-width:100%}.multi-game-layout{grid-template-columns:1fr}.rail-left,.rail-right{display:none}}
</style>

</head>
<body>
<div class="side-rail rail-left" aria-hidden="true">
  <div class="rail-logo">P<span>/</span></div><div class="rail-label">PAUSENMODUS</div>
  <div class="rail-card rail-pink"><span>MOOD</span><strong>404</strong><small>Motivation not found</small></div>
  <div class="rail-sticker">KURZ WEG.</div><div class="rail-orbit"><i></i><b></b><em></em></div>
  <div class="rail-ticker">AZUBI LIFE · PAUSE · REPEAT · </div>
</div>
<div class="side-rail rail-right" aria-hidden="true">
  <div class="rail-clock">☕</div><div class="rail-label">STATUS: ÜBERLEBT</div>
  <div class="rail-card rail-lime"><span>ENERGIE</span><strong>12%</strong><small>Bitte Kaffee nachfüllen</small></div>
  <div class="rail-sticker rail-sticker-blue">NO MEETINGS</div><div class="rail-mini-game"><div class="mini-grid"><i>✦</i><i>·</i><i>●</i><i>·</i><i>◆</i><i>·</i><i>·</i><i>●</i><i>✦</i></div><small>PAUSEN-PIXEL</small></div>
  <div class="rail-ticker">NICHT STÖREN · IM FLOW · </div>
</div>
<div class="wrap">
<header class="nav">
 <div class="brand"><div class="brandmark">☕</div><div>PAUSE<span style="color:var(--pink)"> / AZUBI HUB</span></div></div>
 <nav class="navlinks"><a href="#games">MINI-GAMES</a><a href="#memes">MEME-ZONE</a><a href="#talk">PAUSENWAND</a><a href="#videos">VIDEOS</a><a href="#duelle">DUELLE</a><a href="#arcade">ARCADE</a><a href="#rangliste">RANGLISTE</a><a href="#multiplayer">MULTIPLAYER</a><a href="#quiz">QUIZ</a></nav>
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



<div class="sectionhead" id="videos"><div><div class="eyebrow">06 / Kurz mal weg</div><h2>Random Video Feed</h2><p>Ein Klick – nächster Clip. Du musst keine Links einfügen.</p></div></div>
<section class="card">
  <div class="random-video-layout">
    <div class="random-video-frame"><iframe id="randomVideoFrame" title="TikTok Comedy Feed" allow="autoplay; encrypted-media; gyroscope; picture-in-picture; web-share; fullscreen" allowfullscreen loading="eager" referrerpolicy="strict-origin-when-cross-origin"></iframe></div>
    <div class="random-video-info">
      <span class="pill" id="randomVideoTag">Video-Feed</span>
      <h3 id="randomVideoTitle">Lade einen Clip …</h3>
      <p class="sub" id="randomVideoDescription">Zufällige TikTok-Clips. Autoplay startet stumm; wenn dein Browser blockiert, einmal auf den Player tippen.</p>
      <div class="row"><button class="btn" id="nextRandomVideo">Nächstes Video ↗</button><button class="btn alt" id="openRandomVideo">Auf TikTok öffnen</button></div>
      <div class="row" style="margin-top:8px"><button class="btn alt" id="toggleAutoplay">Auto-Feed: An</button><button class="btn alt" id="randomVideoSearch">TikTok öffnen</button></div>
      <div class="result" id="videoLoadStatus">Der Clip wird geladen …</div>
    </div>
  </div>
  <p class="notice" style="margin-top:12px">Der Feed nutzt echte TikTok-Einbettungen und versucht, Clips stumm automatisch zu starten. TikTok stellt keinen frei nutzbaren, endlosen For-You-Feed ohne API bereit. Wenn Autoplay oder Einbettungen im Browser/Arbeitsnetz blockiert sind, einmal in den Player klicken oder TikTok direkt öffnen.</p>
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



<div class="sectionhead" id="arcade"><div><div class="eyebrow">08 / Arcade</div><h2>Arcade Zone</h2><p>Drei überarbeitete Spiele mit stabiler Steuerung, Neustart und Bestwerten.</p></div></div>
<section class="arcade-grid">
  <article class="arcade-card">
    <div class="arcade-head"><div><h3>🐍 Neon Snake</h3><p>Sammle Punkte, wachse und beiß dich nicht selbst.</p></div><span class="pill">2D · Klassiker</span></div>
    <canvas id="snakeCanvas" class="arcade-canvas" width="640" height="448" aria-label="Neon Snake"></canvas>
    <div class="arcade-controls"><button class="btn" id="snakeStart">Start / Neustart</button><button class="btn alt" id="snakePause">Pause</button><span class="arcade-stat">Punkte: <b id="snakeScore">0</b> · Best: <b id="snakeBest">0</b></span></div>
    <div class="arcade-mobile"><button class="btn alt" id="snakeUp">↑</button></div><div class="arcade-mobile"><button class="btn alt" id="snakeLeft">←</button><button class="btn alt" id="snakeDown">↓</button><button class="btn alt" id="snakeRight">→</button></div>
    <p class="arcade-help">Pfeiltasten oder WASD. Am Handy die Richtungstasten verwenden. Nach einem Crash kannst du direkt neu starten.</p>
  </article>
  <article class="arcade-card">
    <div class="arcade-head"><div><h3>🧱 Brick Breaker</h3><p>Zerstöre alle Blöcke, ohne den Ball fallen zu lassen.</p></div><span class="pill">Arcade</span></div>
    <canvas id="brickCanvas" class="arcade-canvas" width="640" height="400" aria-label="Brick Breaker"></canvas>
    <div class="arcade-controls"><button class="btn" id="brickStart">Start / Neustart</button><button class="btn alt" id="brickPause">Pause</button><span class="arcade-stat">Punkte: <b id="brickScore">0</b> · Leben: <b id="brickLives">3</b></span></div>
    <div class="arcade-mobile"><button class="btn alt" id="brickLeft">← Links</button><button class="btn alt" id="brickRight">Rechts →</button></div>
    <p class="arcade-help">Pfeiltasten / A und D oder bewege den Mauszeiger über das Spielfeld. Am Handy die Buttons verwenden.</p>
  </article>
  <article class="arcade-card">
    <div class="arcade-head"><div><h3>🧠 Memory Match</h3><p>Finde alle Paare mit möglichst wenigen Zügen.</p></div><span class="pill">Denkspiel</span></div>
    <div id="memoryBoard" class="memory-board" aria-label="Memory Spielfeld"></div>
    <div class="arcade-controls"><button class="btn" id="memoryRestart">Neues Spiel</button><span class="arcade-stat">Züge: <b id="memoryMoves">0</b> · Paare: <b id="memoryPairs">0</b>/8</span></div>
    <div class="result" id="memoryMessage">Zwei Karten aufdecken und ein Paar finden.</div>
    <p class="arcade-help">Merke dir die Symbole. Gleiche Karten bleiben offen, unterschiedliche drehen sich wieder um.</p>
  </article>
</section>


<div class="sectionhead" id="rangliste"><div><div class="eyebrow">09 / Highscores</div><h2>Rangliste</h2><p>Deine Bestwerte auf diesem Browser plus Live-Ergebnisse aus eurer Multiplayer-Runde.</p></div></div>
<section class="card">
  <div class="row" style="justify-content:space-between;align-items:center;gap:12px">
    <div><h3 style="margin:0 0 5px">Lokale Highscores</h3><p class="sub">Diese Tabelle bleibt auf diesem Gerät gespeichert.</p></div>
    <button class="btn alt" id="refreshLeaderboard">Aktualisieren</button>
  </div>
  <div class="leaderboard-wrap" style="overflow-x:auto;margin-top:14px">
    <table class="leaderboard-table" style="width:100%;border-collapse:collapse;min-width:360px">
      <thead><tr><th style="text-align:left;padding:10px;border-bottom:1px solid var(--line)">Spiel</th><th style="text-align:right;padding:10px;border-bottom:1px solid var(--line)">Bestwert</th><th style="text-align:right;padding:10px;border-bottom:1px solid var(--line)">Spieler</th></tr></thead>
      <tbody id="leaderboardRows"><tr><td colspan="3" style="padding:12px;color:var(--muted)">Noch keine Bestwerte.</td></tr></tbody>
    </table>
  </div>
  <p class="notice" style="margin-top:10px">Hinweis: Eine globale Rangliste über alle Besucher benötigt eine gemeinsame Datenbank. Diese Version speichert lokale Highscores und zeigt die Rangliste der aktuellen Online-Lobby live an.</p>
</section>

<div class="sectionhead" id="multiplayer"><div><div class="eyebrow">10 / Zusammen spielen</div><h2>Neon Arena Online</h2><p>Erstelle einen Raumcode, teile ihn mit anderen Azubis und sammelt gleichzeitig Energie-Orbs.</p></div></div>
<section class="card">
  <div class="multi-top">
    <div><h3 style="margin:0 0 5px">NEON RUSH // Battle Arena</h3><p class="sub">Echtzeit-Rennen · bis zu 4 Spieler · Gold = 1 Punkt · Pink = 3 Punkte · Shift = Turbo</p></div>
    <span class="pill" id="multiStatus">Nicht verbunden</span>
  </div>
  <div class="multi-controls">
    <input id="playerNameInput" maxlength="18" placeholder="Dein Spielername" aria-label="Dein Spielername" style="min-width:145px;max-width:200px;border:1px solid var(--line);border-radius:12px;background:#ffffff08;color:var(--text);padding:11px 13px">
    <button class="btn" id="createRoom">Raum erstellen</button>
    <div class="multi-join"><input id="roomCodeInput" maxlength="6" placeholder="Raumcode" aria-label="Raumcode"><button class="btn alt" id="joinRoom">Beitreten</button></div>
    <button class="btn alt" id="leaveRoom">Verlassen</button>
  </div>
  <div class="room-code-panel" id="roomCodePanel" hidden><span>DEIN RAUMCODE</span><strong id="roomCodeDisplay">------</strong><button class="btn alt" id="copyRoomCode">Code kopieren</button></div>
  <div class="multi-game-layout">
    <div><canvas id="multiCanvas" width="900" height="520" class="arcade-canvas" aria-label="Neon Arena Multiplayer"></canvas>
      <div class="arcade-mobile multi-mobile"><button class="btn alt" id="multiUp">↑</button></div>
      <div class="arcade-mobile multi-mobile"><button class="btn alt" id="multiLeft">←</button><button class="btn alt" id="multiDown">↓</button><button class="btn alt" id="multiRight">→</button><button class="btn lime" id="multiBoost">⚡ BOOST</button></div>
    </div>
    <div class="multi-side">
      <h3>Live-Rangliste</h3>
      <ol id="multiScores" class="multi-score-list"><li>Erstelle einen Raum oder tritt bei.</li></ol>
      <div class="result" id="multiMessage">WASD / Pfeiltasten bewegen · SHIFT = Turbo-Boost · sammle Gold- und Pink-Orbs und schnapp deinen Freunden die Punkte weg.</div>
      <p class="notice">Die Verbindung läuft direkt zwischen den Spielern über PeerJS. Dafür muss der Browser das PeerJS-CDN und den Verbindungsserver erreichen können. Wenn es im UKSH-Netz blockiert ist, teste die Seite in einem privaten Netzwerk.</p>
    </div>
  </div>
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

// Video lounge logic is initialized in the current random-feed module below.

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




// ---------------- TikTok Feed: echter TikTok-Player + Autoplay ----------------
(()=>{
 const videos=[
  {id:'7295497071224769834',title:'The Office: Chaos im Büro',tag:'TikTok · Office',url:'https://www.tiktok.com/@theoffice/video/7295497071224769834'},
  {id:'7480587764673613102',title:'The Office: nächster Clip',tag:'TikTok · Comedy',url:'https://www.tiktok.com/@theoffice/video/7480587764673613102'},
  {id:'7260931030322793771',title:'The Office: Büro-Moment',tag:'TikTok · Office',url:'https://www.tiktok.com/@theoffice/video/7260931030322793771'},
  {id:'7217113001453718827',title:'The Office: Comedy Cut',tag:'TikTok · Comedy',url:'https://www.tiktok.com/@theoffice/video/7217113001453718827'},
  {id:'7214876954166578475',title:'The Office: weiterer Clip',tag:'TikTok · Office',url:'https://www.tiktok.com/@theoffice/video/7214876954166578475'}
 ];
 let current=-1,auto=true,autoTimer=null,loadTimer=null;
 const frame=document.getElementById('randomVideoFrame'),status=document.getElementById('videoLoadStatus');
 function loadVideo(){
  let index=Math.floor(Math.random()*videos.length);if(videos.length>1&&index===current)index=(index+1)%videos.length;
  current=index;const v=videos[index];
  frame.src='https://www.tiktok.com/player/v1/'+v.id+'?autoplay=1&muted=1&loop=0&controls=1&progress_bar=1&play_button=1&volume_control=1&fullscreen_button=1&rel=1';
  document.getElementById('randomVideoTitle').textContent=v.title;document.getElementById('randomVideoTag').textContent=v.tag;
  document.getElementById('randomVideoDescription').textContent='TikTok-Player · startet stumm, sofern dein Browser Autoplay erlaubt.';
  status.textContent='TikTok-Clip wird geladen und stumm gestartet …';
  clearTimeout(loadTimer);loadTimer=setTimeout(()=>{status.textContent='Wenn der Player leer bleibt: einmal auf den Player klicken oder TikTok direkt öffnen. Manche Netzwerke blockieren TikTok.';},9000);
 }
 frame.addEventListener('load',()=>{status.textContent='Player geladen. Autoplay hängt von Browser- und TikTok-Einstellungen ab.';clearTimeout(loadTimer)});
 window.addEventListener('message',e=>{if(!e.origin||!e.origin.includes('tiktok.com')||!e.data||e.data['x-tiktok-player']!==true)return; if(e.data.type==='onStateChange'&&e.data.value===0&&auto)loadVideo(); if(e.data.type==='onPlayerError'&&e.data.value){status.textContent='TikTok meldet einen Player-Fehler. Öffne den Clip direkt oder wähle den nächsten.';}});
 document.getElementById('nextRandomVideo').onclick=loadVideo;
 document.getElementById('openRandomVideo').onclick=()=>{if(current>=0)window.open(videos[current].url,'_blank','noopener')};
 document.getElementById('randomVideoSearch').onclick=()=>window.open('https://www.tiktok.com/search?q=office%20memes%20funny','_blank','noopener');
 document.getElementById('toggleAutoplay').onclick=()=>{auto=!auto;document.getElementById('toggleAutoplay').textContent='Auto-Feed: '+(auto?'An':'Aus');status.textContent=auto?'Nächster Clip startet nach Videoende automatisch.':'Auto-Wechsel ausgeschaltet.';};
 loadVideo();
})();

// ---------------- Persistent local game leaderboard ----------------
(()=>{
 const KEY='azubiHubScoresV2';
 function getScores(){try{return JSON.parse(localStorage.getItem(KEY)||'{}')}catch(e){return {}}}
 function saveScore(game,score){
   const scores=getScores();const player=(localStorage.getItem('azubiHubPlayerName')||'Du').slice(0,20);
   if(!scores[game]||Number(score)>Number(scores[game].score))scores[game]={score:Number(score),player,when:new Date().toISOString()};
   try{localStorage.setItem(KEY,JSON.stringify(scores))}catch(e){}
   render();
 }
 function render(){
  const scores=getScores(),rows=document.getElementById('leaderboardRows');
  const games=[['Neon Snake',scores['Neon Snake']||{score:0,player:'–'}],['Brick Breaker',scores['Brick Breaker']||{score:0,player:'–'}],['Memory Match',scores['Memory Match']||{score:0,player:'–'}]];
  rows.innerHTML='';
  games.forEach(([name,v])=>{const tr=document.createElement('tr');[name,String(v.score),v.player||'Du'].forEach((t,i)=>{const td=document.createElement('td');td.textContent=t;td.style.textAlign=i?'right':'left';td.style.padding='12px 10px';td.style.borderBottom='1px solid #ffffff0c';tr.appendChild(td)});rows.appendChild(tr)});
 }
 window.azubiSaveScore=saveScore;
 document.getElementById('refreshLeaderboard').onclick=render;
 render();
})();

// ---------------- Neon Snake (fixed-step game loop) ----------------
(()=>{
 const c=document.getElementById('snakeCanvas'),ctx=c.getContext('2d'),cols=20,rows=14,cell=32;
 let snake,dir,nextDir,food,score,running=false,paused=false,dead=false,timer=null;
 const scoreEl=document.getElementById('snakeScore'),bestEl=document.getElementById('snakeBest');
 let best=0;try{best=Number(localStorage.getItem('neonSnakeBest')||0)}catch(e){}bestEl.textContent=best;
 function randFood(){let f;do{f={x:Math.floor(Math.random()*cols),y:Math.floor(Math.random()*rows)}}while(snake.some(p=>p.x===f.x&&p.y===f.y));return f}
 function draw(){
  ctx.fillStyle='#090b16';ctx.fillRect(0,0,c.width,c.height);ctx.strokeStyle='#ffffff0a';
  for(let x=0;x<=cols;x++){ctx.beginPath();ctx.moveTo(x*cell,0);ctx.lineTo(x*cell,c.height);ctx.stroke()}
  for(let y=0;y<=rows;y++){ctx.beginPath();ctx.moveTo(0,y*cell);ctx.lineTo(c.width,y*cell);ctx.stroke()}
  if(food){ctx.fillStyle='#ff58c8';ctx.beginPath();ctx.arc(food.x*cell+cell/2,food.y*cell+cell/2,cell*.34,0,Math.PI*2);ctx.fill()}
  (snake||[]).forEach((p,i)=>{ctx.fillStyle=i===0?'#d9ff65':'#7e8cff';ctx.beginPath();ctx.roundRect(p.x*cell+2,p.y*cell+2,cell-4,cell-4,7);ctx.fill()});
  if(!running||paused||dead){ctx.fillStyle='#070814cc';ctx.fillRect(0,0,c.width,c.height);ctx.textAlign='center';ctx.fillStyle='#fff';ctx.font='bold 30px system-ui';ctx.fillText(dead?'Game Over':paused?'Pausiert':'NEON SNAKE',c.width/2,c.height/2-8);ctx.fillStyle='#d9ff65';ctx.font='16px system-ui';ctx.fillText(dead?'Start / Neustart drücken':paused?'Pause drücken zum Weiterspielen':'Start drücken und pinke Punkte sammeln',c.width/2,c.height/2+24);ctx.textAlign='left'}
 }
 function tick(){if(!running||paused||dead)return;dir=nextDir;const h={x:snake[0].x+dir.x,y:snake[0].y+dir.y};
  if(h.x<0||h.x>=cols||h.y<0||h.y>=rows||snake.some((p,i)=>i>0&&p.x===h.x&&p.y===h.y)){dead=true;running=false;clearInterval(timer);window.azubiSaveScore?.('Neon Snake',score);draw();return}
  snake.unshift(h);if(h.x===food.x&&h.y===food.y){score+=10;scoreEl.textContent=score;food=randFood();if(score>best){best=score;bestEl.textContent=best;try{localStorage.setItem('neonSnakeBest',best)}catch(e){}}}else snake.pop();draw()
 }
 function reset(){if(timer)clearInterval(timer);snake=[{x:7,y:7},{x:6,y:7},{x:5,y:7}];dir={x:1,y:0};nextDir={x:1,y:0};food=randFood();score=0;dead=false;paused=false;running=true;scoreEl.textContent='0';draw();timer=setInterval(tick,115)}
 function setDir(x,y){if(!dir|| (x===-dir.x&&y===-dir.y))return;nextDir={x,y}}
 document.getElementById('snakeStart').onclick=reset;
 document.getElementById('snakePause').onclick=()=>{if(!running)return;paused=!paused;draw()};
 document.getElementById('snakeUp').onclick=()=>setDir(0,-1);document.getElementById('snakeDown').onclick=()=>setDir(0,1);document.getElementById('snakeLeft').onclick=()=>setDir(-1,0);document.getElementById('snakeRight').onclick=()=>setDir(1,0);
 window.addEventListener('keydown',e=>{if(document.activeElement.matches('input,textarea'))return;const map={arrowup:[0,-1],w:[0,-1],arrowdown:[0,1],s:[0,1],arrowleft:[-1,0],a:[-1,0],arrowright:[1,0],d:[1,0]};const k=e.key.toLowerCase();if(map[k]){e.preventDefault();setDir(...map[k])}});
 draw();
})();

// ---------------- Brick Breaker with normalized pointer input ----------------
(()=>{
 const c=document.getElementById('brickCanvas'),ctx=c.getContext('2d');
 let paddle={x:270,w:100,h:12},ball={x:320,y:330,vx:210,vy:-230,r:8},bricks=[],score=0,lives=3,running=false,paused=false,over=false,last=0,raf=null;
 const scoreEl=document.getElementById('brickScore'),livesEl=document.getElementById('brickLives');
 function reset(){if(raf)cancelAnimationFrame(raf);paddle.x=(c.width-paddle.w)/2;ball={x:c.width/2,y:c.height-50,vx:210,vy:-230,r:8};bricks=[];for(let r=0;r<5;r++)for(let col=0;col<9;col++)bricks.push({x:25+col*66,y:35+r*28,w:58,h:17,alive:true,row:r});score=0;lives=3;running=false;paused=false;over=false;scoreEl.textContent=score;livesEl.textContent=lives;draw()}
 function start(){if(over||bricks.length===0)reset();running=true;paused=false;last=performance.now();if(raf)cancelAnimationFrame(raf);raf=requestAnimationFrame(loop)}
 function draw(){ctx.fillStyle='#090b16';ctx.fillRect(0,0,c.width,c.height);bricks.forEach(b=>{if(!b.alive)return;ctx.fillStyle=['#ff58c8','#7e8cff','#d9ff65','#ffad5c','#55d6be'][b.row];ctx.beginPath();ctx.roundRect(b.x,b.y,b.w,b.h,4);ctx.fill()});ctx.fillStyle='#f6f4ff';ctx.beginPath();ctx.roundRect(paddle.x,c.height-28,paddle.w,paddle.h,6);ctx.fill();ctx.fillStyle='#d9ff65';ctx.beginPath();ctx.arc(ball.x,ball.y,ball.r,0,Math.PI*2);ctx.fill();if(!running||paused||over){ctx.fillStyle='#070814cc';ctx.fillRect(0,0,c.width,c.height);ctx.textAlign='center';ctx.fillStyle='#fff';ctx.font='bold 29px system-ui';ctx.fillText(over?(lives===0?'Game Over':'Gewonnen!'):paused?'Pausiert':'BRICK BREAKER',c.width/2,c.height/2-8);ctx.fillStyle='#d9ff65';ctx.font='16px system-ui';ctx.fillText(over?'Start / Neustart für eine neue Runde':paused?'Pause drücken zum Weiterspielen':'Start drücken und den Ball halten',c.width/2,c.height/2+24);ctx.textAlign='left'}}
 function loop(now){if(!running)return;const dt=Math.min((now-last)/1000,.025);last=now;if(!paused&&!over){ball.x+=ball.vx*dt;ball.y+=ball.vy*dt;if(ball.x<ball.r){ball.x=ball.r;ball.vx=Math.abs(ball.vx)}if(ball.x>c.width-ball.r){ball.x=c.width-ball.r;ball.vx=-Math.abs(ball.vx)}if(ball.y<ball.r){ball.y=ball.r;ball.vy=Math.abs(ball.vy)}
  if(ball.y+ball.r>=c.height-36&&ball.y-ball.r<=c.height-16&&ball.x>=paddle.x&&ball.x<=paddle.x+paddle.w&&ball.vy>0){ball.y=c.height-36-ball.r;ball.vy=-Math.abs(ball.vy);ball.vx+=((ball.x-(paddle.x+paddle.w/2))/(paddle.w/2))*90}
  bricks.forEach(b=>{if(!b.alive)return;if(ball.x+ball.r>b.x&&ball.x-ball.r<b.x+b.w&&ball.y+ball.r>b.y&&ball.y-ball.r<b.y+b.h){b.alive=false;ball.vy*=-1;score+=10;scoreEl.textContent=score}});
  if(ball.y>c.height+10){lives--;livesEl.textContent=lives;if(lives<=0){over=true;running=false;window.azubiSaveScore?.('Brick Breaker',score)}else{ball={x:paddle.x+paddle.w/2,y:c.height-50,vx:(Math.random()>.5?1:-1)*210,vy:-230}}}
  if(bricks.every(b=>!b.alive)){over=true;running=false;window.azubiSaveScore?.('Brick Breaker',score)}
 }draw();if(running)raf=requestAnimationFrame(loop)}
 function movePaddle(clientX){const r=c.getBoundingClientRect();paddle.x=Math.max(0,Math.min(c.width-paddle.w,(clientX-r.left)/r.width*c.width-paddle.w/2));if(!running)draw()}
 c.addEventListener('mousemove',e=>movePaddle(e.clientX));c.addEventListener('touchmove',e=>{e.preventDefault();movePaddle(e.touches[0].clientX)},{passive:false});
 document.getElementById('brickStart').onclick=start;document.getElementById('brickPause').onclick=()=>{if(running){paused=!paused;draw()}};
 document.getElementById('brickLeft').onclick=()=>{paddle.x=Math.max(0,paddle.x-45);draw()};document.getElementById('brickRight').onclick=()=>{paddle.x=Math.min(c.width-paddle.w,paddle.x+45);draw()};
 window.addEventListener('keydown',e=>{if(document.activeElement.matches('input,textarea'))return;const k=e.key.toLowerCase();if(['arrowleft','arrowright','a','d'].includes(k)){e.preventDefault();paddle.x=Math.max(0,Math.min(c.width-paddle.w,paddle.x+(k==='arrowleft'||k==='a'?-35:35)));if(!running)draw()}});
 reset();
})();

// ---------------- Memory Match with score saving ----------------
(()=>{
 const symbols=['☕','📎','💾','🖨️','📁','🧠','🕒','📧'];let deck=[],open=[],matched=new Set(),moves=0,locked=false;
 const board=document.getElementById('memoryBoard'),movesEl=document.getElementById('memoryMoves'),pairsEl=document.getElementById('memoryPairs'),msg=document.getElementById('memoryMessage');
 function shuffle(a){for(let i=a.length-1;i>0;i--){const j=Math.floor(Math.random()*(i+1));[a[i],a[j]]=[a[j],a[i]]}return a}
 function start(){deck=shuffle([...symbols,...symbols]);open=[];matched=new Set();moves=0;locked=false;movesEl.textContent='0';pairsEl.textContent='0';msg.textContent='Zwei Karten aufdecken und ein Paar finden.';board.innerHTML='';deck.forEach((sym,i)=>{const b=document.createElement('button');b.className='memory-card';b.type='button';b.textContent='?';b.setAttribute('aria-label','Verdeckte Karte');b.onclick=()=>flip(i,b);board.appendChild(b)})}
 function flip(i,b){if(locked||matched.has(i)||open.includes(i))return;b.textContent=deck[i];b.classList.add('flipped');b.setAttribute('aria-label',deck[i]);open.push(i);if(open.length===2){moves++;movesEl.textContent=moves;const [a,d]=open;if(deck[a]===deck[d]){matched.add(a);matched.add(d);[a,d].forEach(k=>{board.children[k].classList.add('matched');board.children[k].classList.remove('flipped')});pairsEl.textContent=matched.size/2;open=[];if(matched.size===deck.length){msg.textContent='Alle Paare in '+moves+' Zügen gefunden.';window.azubiSaveScore?.('Memory Match',Math.max(0,100-moves));}}else{locked=true;setTimeout(()=>{[a,d].forEach(k=>{const el=board.children[k];el.textContent='?';el.classList.remove('flipped');el.setAttribute('aria-label','Verdeckte Karte')});open=[];locked=false},700)}}}
 document.getElementById('memoryRestart').onclick=start;start();
})();

// ---------------- PeerJS room-based live multiplayer: Neon Arena ----------------
function ensurePeerLibrary(){
 return new Promise((resolve,reject)=>{
  if(typeof Peer!=='undefined'){resolve();return}
  let script=document.getElementById('peerjs-lazy-script');
  if(script){
   if(script.dataset.failed==='1'){reject(new Error('PeerJS konnte nicht geladen werden'));return}
   script.addEventListener('load',()=>typeof Peer!=='undefined'?resolve():reject(new Error('PeerJS ist nicht verfügbar')),{once:true});
   script.addEventListener('error',()=>reject(new Error('PeerJS-CDN nicht erreichbar')),{once:true});
   return;
  }
  script=document.createElement('script');script.id='peerjs-lazy-script';script.src='https://unpkg.com/peerjs@1.5.4/dist/peerjs.min.js';script.async=true;
  const timeout=setTimeout(()=>{script.dataset.failed='1';reject(new Error('Zeitüberschreitung beim Laden von PeerJS'))},9000);
  script.onload=()=>{clearTimeout(timeout);typeof Peer!=='undefined'?resolve():reject(new Error('PeerJS ist nicht verfügbar'))};
  script.onerror=()=>{clearTimeout(timeout);script.dataset.failed='1';reject(new Error('PeerJS-CDN nicht erreichbar'))};
  document.head.appendChild(script);
 });
}
(()=>{

 const canvas=document.getElementById('multiCanvas'),ctx=canvas.getContext('2d');
 const status=document.getElementById('multiStatus'),msg=document.getElementById('multiMessage'),codePanel=document.getElementById('roomCodePanel'),codeDisplay=document.getElementById('roomCodeDisplay'),scoresEl=document.getElementById('multiScores');
 let peer=null,conn=null,isHost=false,roomCode='',players={},orbs=[],gameRunning=false,remaining=60,lastTick=0,hostTimer=null,orbTimer=null,playerId='',keys={},touch={x:0,y:0},lastState=null;const hostConnections=new Set();
 const palette=['#d9ff65','#ff58c8','#7e8cff','#ffad5c'];
 function setStatus(t){status.textContent=t}
 function makeId(){return 'azubihub-'+Math.random().toString(36).slice(2,7)}
 function clean(){if(hostTimer)clearInterval(hostTimer);if(orbTimer)clearInterval(orbTimer);hostTimer=orbTimer=null;gameRunning=false}
 function resetArena(){players={};orbs=[];remaining=60;lastTick=Date.now();for(let i=0;i<5;i++)spawnOrb();draw();renderScores()}
 function spawnOrb(){const rare=Math.random()<.22;orbs.push({x:35+Math.random()*(canvas.width-70),y:45+Math.random()*(canvas.height-80),r:rare?13:9,type:rare?'boost':'coin',value:rare?3:1,phase:Math.random()*Math.PI*2})}
 function localName(){const field=document.getElementById('playerNameInput');const typed=field&&field.value.trim();if(typed){try{localStorage.setItem('azubiHubPlayerName',typed)}catch(e){}return typed.slice(0,18)}return (localStorage.getItem('azubiHubPlayerName')||'Azubi').slice(0,18)}
 function addPlayer(id,name){players[id]={id,name:(name||'Azubi').slice(0,18),x:70+Math.random()*(canvas.width-140),y:70+Math.random()*(canvas.height-140),r:17,score:0,color:palette[Object.keys(players).length%palette.length],input:{x:0,y:0}}}
 function renderScores(){
  const list=Object.values(players).sort((a,b)=>b.score-a.score);scoresEl.innerHTML='';
  if(!list.length){scoresEl.innerHTML='<li>Erstelle einen Raum oder tritt bei.</li>';return}
  list.forEach((p,i)=>{const li=document.createElement('li');li.className=p.id===playerId?'me':'';const name=document.createElement('span');name.textContent=(i+1)+'. '+p.name;const score=document.createElement('strong');score.textContent=p.score+' pts';li.append(name,score);scoresEl.appendChild(li)});
 }
 function draw(){
  const now=performance.now()/1000;
  const bg=ctx.createLinearGradient(0,0,canvas.width,canvas.height);bg.addColorStop(0,'#10162b');bg.addColorStop(.5,'#0a0c18');bg.addColorStop(1,'#1b1027');ctx.fillStyle=bg;ctx.fillRect(0,0,canvas.width,canvas.height);
  // glowing grid with animated scanline
  ctx.strokeStyle='#a9b5ff12';ctx.lineWidth=1;const offset=(now*8)%40;
  for(let x=-40+offset;x<canvas.width;x+=40){ctx.beginPath();ctx.moveTo(x,0);ctx.lineTo(x,canvas.height);ctx.stroke()}
  for(let y=0;y<canvas.height;y+=40){ctx.beginPath();ctx.moveTo(0,y);ctx.lineTo(canvas.width,y);ctx.stroke()}
  ctx.strokeStyle='#ff58c828';ctx.lineWidth=2;ctx.strokeRect(9,9,canvas.width-18,canvas.height-18);
  // neon arena rings
  for(let i=0;i<3;i++){ctx.beginPath();ctx.strokeStyle=['#7e8cff13','#ff58c813','#d9ff6510'][i];ctx.lineWidth=2;ctx.arc(canvas.width/2,canvas.height/2,70+i*40+Math.sin(now+i)*4,0,Math.PI*2);ctx.stroke()}
  orbs.forEach(o=>{const pulse=1+Math.sin(now*4+(o.phase||0))*.16;const color=o.type==='boost'?'#ff58c8':'#d9ff65';ctx.save();ctx.translate(o.x,o.y);ctx.rotate(now*.8);ctx.shadowColor=color;ctx.shadowBlur=o.type==='boost'?27:18;ctx.fillStyle=color;ctx.beginPath();if(o.type==='boost'){for(let i=0;i<8;i++){const a=i*Math.PI/4;const r=(i%2?o.r*.65:o.r)*pulse;ctx.lineTo(Math.cos(a)*r,Math.sin(a)*r)}}else{ctx.arc(0,0,o.r*pulse,0,Math.PI*2)}ctx.closePath();ctx.fill();ctx.shadowBlur=0;ctx.strokeStyle='#ffffffaa';ctx.stroke();ctx.restore()});
  Object.values(players).forEach(p=>{const color=p.color||'#91a7ff';ctx.save();ctx.shadowColor=color;ctx.shadowBlur=24;ctx.fillStyle=color;ctx.beginPath();ctx.arc(p.x,p.y,22,0,Math.PI*2);ctx.fill();ctx.shadowBlur=0;ctx.strokeStyle='#ffffffbb';ctx.lineWidth=2;ctx.beginPath();ctx.arc(p.x,p.y,22,0,Math.PI*2);ctx.stroke();ctx.fillStyle='#0a0b16';ctx.beginPath();ctx.arc(p.x+6,p.y-4,4,0,Math.PI*2);ctx.fill();ctx.beginPath();ctx.arc(p.x-6,p.y-4,4,0,Math.PI*2);ctx.fill();ctx.fillStyle='#fff';ctx.textAlign='center';ctx.font='bold 13px system-ui';ctx.fillText(p.name,p.x,p.y-33);ctx.fillStyle=color;ctx.font='bold 10px system-ui';ctx.fillText((p.score||0)+' PTS',p.x,p.y+38);ctx.restore()});
  ctx.fillStyle='#ffffff';ctx.font='900 15px system-ui';ctx.fillText('NEON RUSH',18,28);ctx.fillStyle='#d9ff65';ctx.font='bold 18px system-ui';ctx.fillText(String(Math.ceil(remaining)).padStart(2,'0')+'s',canvas.width-60,28);
  if(!gameRunning){ctx.fillStyle='#060712c9';ctx.fillRect(0,0,canvas.width,canvas.height);ctx.textAlign='center';ctx.fillStyle='#fff';ctx.font='900 34px system-ui';ctx.fillText(roomCode?'READY TO RUSH?':'NEON RUSH',canvas.width/2,canvas.height/2-20);ctx.fillStyle='#d9ff65';ctx.font='bold 15px system-ui';ctx.fillText(roomCode?'Host: Runde starten · Gäste: bereit machen':'Raum erstellen und Freunde reinholen',canvas.width/2,canvas.height/2+12);ctx.fillStyle='#ff58c8';ctx.font='bold 12px system-ui';ctx.fillText('GOLD +1   /   PINK +3   /   SHIFT = TURBO',canvas.width/2,canvas.height/2+42);ctx.textAlign='left'}
 }
 function snapshot(){return {type:'state',players:Object.values(players),orbs,remaining,gameRunning,roomCode}}
 function broadcast(){if(!isHost)return;const data=snapshot();hostConnections.forEach(c=>{if(c.open){try{c.send(data)}catch(e){}}})}
 function startMatch(){if(!isHost){msg.textContent='Nur der Host kann die Runde starten.';return}if(Object.keys(players).length<1)return;remaining=60;Object.values(players).forEach(p=>p.score=0);orbs=[];for(let i=0;i<7;i++)spawnOrb();gameRunning=true;lastTick=Date.now();msg.textContent='LOS! Gold-Orbs = 1 Punkt, pinke Boost-Orbs = 3 Punkte. SHIFT gibt dir extra Speed.';draw();broadcast()}
 function hostStep(){
  const now=Date.now(),dt=Math.min((now-lastTick)/1000,.05);lastTick=now;
  if(gameRunning){
   remaining=Math.max(0,remaining-dt);
   Object.values(players).forEach(p=>{const input=p.input||{};p.x=Math.max(18,Math.min(canvas.width-18,p.x+(input.x||0)*(input.boost?350:210)*dt));p.y=Math.max(38,Math.min(canvas.height-18,p.y+(input.y||0)*(input.boost?350:210)*dt));});
   Object.values(players).forEach(p=>{const ix=orbs.findIndex(o=>Math.hypot(o.x-p.x,o.y-p.y)<p.r+(o.r||10)+8);if(ix>=0){const value=orbs[ix].value||1;orbs.splice(ix,1);p.score+=value;spawnOrb()}});
   if(remaining<=0){gameRunning=false;msg.textContent='Runde beendet! Gewinner: '+Object.values(players).sort((a,b)=>b.score-a.score)[0]?.name; }
   renderScores();broadcast();
  }
  draw();
 }
 function setupHost(){
  clean();isHost=true;roomCode=Math.random().toString(36).slice(2,8).toUpperCase();playerId='host';
  resetArena();addPlayer(playerId,localName());codePanel.hidden=false;codeDisplay.textContent=roomCode;document.getElementById('roomCodeInput').value=roomCode;
  if(typeof Peer==='undefined'){setStatus('PeerJS nicht geladen');msg.textContent='Das Multiplayer-Modul konnte nicht geladen werden. Prüfe deine Internetverbindung oder den Netzwerkfilter.';return}
  peer=new Peer('azubihub-'+roomCode.toLowerCase());
  peer.on('open',()=>{setStatus('Raum offen');msg.textContent='Raum erstellt. Teile den Code mit anderen Azubis.';hostTimer=setInterval(hostStep,50);});
  peer.on('connection',c=>{if(Object.keys(players).length>=4){c.on('open',()=>{try{c.send({type:'full'})}catch(e){}});setTimeout(()=>c.close(),250);return}hostConnections.add(c);wireConnection(c);c.on('close',()=>{hostConnections.delete(c);if(players[c.peer]){delete players[c.peer];renderScores();broadcast()}});});
  peer.on('error',e=>{setStatus('Verbindung fehlgeschlagen');msg.textContent='Raum konnte nicht erstellt werden: '+(e.type||'Netzwerkfehler')+'. Versuche einen neuen Raum oder ein anderes Netzwerk.';});
  // Host can start via the same room button after it has been created.
  document.getElementById('createRoom').textContent='Runde starten';
 }
 function wireConnection(c){
  c.on('open',()=>{
   if(!isHost){setStatus('Verbinde …');c.send({type:'join',id:peer.id,name:localName()});}
  });
  c.on('data',data=>{
   if(isHost){
    if(data.type==='join'){
     if(Object.keys(players).length>=4){c.send({type:'full'});c.close();return}
     addPlayer(data.id,data.name);
     c.send({type:'welcome',id:data.id,roomCode,players:Object.values(players),orbs,remaining,gameRunning});
     renderScores();broadcast();msg.textContent=data.name+' ist beigetreten.';
    }
    if(data.type==='input'&&players[data.id])players[data.id].input=data.input;
   }else{
    if(data.type==='welcome'){playerId=data.id;players={};(data.players||[]).forEach(p=>players[p.id]=p);orbs=data.orbs||[];remaining=data.remaining||60;gameRunning=!!data.gameRunning;roomCode=data.roomCode;renderScores();draw();setStatus('Verbunden');msg.textContent='Du bist in Raum '+roomCode+'. Sammle die gelben Energie-Orbs.';}
    if(data.type==='state'){players={};(data.players||[]).forEach(p=>players[p.id]=p);orbs=data.orbs||[];remaining=data.remaining||0;gameRunning=!!data.gameRunning;renderScores();draw();}
    if(data.type==='full'){msg.textContent='Der Raum ist voll (max. 4 Spieler).';setStatus('Raum voll');}
   }
  });
  c.on('close',()=>{if(!isHost){setStatus('Verbindung getrennt');msg.textContent='Die Verbindung zum Host wurde getrennt.';}});
  c.on('error',()=>{setStatus('Verbindungsfehler');msg.textContent='Verbindung unterbrochen. Bitte erneut beitreten.';});
 }
 document.getElementById('createRoom').onclick=async()=>{
  if(isHost&&peer){if(!gameRunning)startMatch();return}
  setStatus('Multiplayer wird geladen …');msg.textContent='Die normalen Spiele funktionieren unabhängig davon. Einen Moment bitte …';
  try{await ensurePeerLibrary()}catch(e){setStatus('Multiplayer nicht verfügbar');msg.textContent='PeerJS konnte nicht geladen werden. Prüfe Internet/Netzwerkfilter; die lokalen Spiele funktionieren trotzdem.';return}
  if(peer)peer.destroy();hostConnections.clear();document.getElementById('createRoom').textContent='Runde starten';setupHost();
 };
 document.getElementById('joinRoom').onclick=async()=>{
  const code=document.getElementById('roomCodeInput').value.trim().toUpperCase();
  if(!/^[A-Z0-9]{6}$/.test(code)){msg.textContent='Bitte einen sechsstelligen Raumcode eingeben.';return}
  setStatus('Multiplayer wird geladen …');
  try{await ensurePeerLibrary()}catch(e){setStatus('Multiplayer nicht verfügbar');msg.textContent='PeerJS konnte nicht geladen werden. Prüfe Internet/Netzwerkfilter; die lokalen Spiele funktionieren trotzdem.';return}
  clean();isHost=false;roomCode=code;codePanel.hidden=true;playerId='guest-pending';peer=new Peer();
  peer.on('open',()=>{conn=peer.connect('azubihub-'+code.toLowerCase(),{reliable:true});wireConnection(conn);});
  peer.on('error',e=>{setStatus('Verbindung fehlgeschlagen');msg.textContent='Raum nicht erreichbar ('+(e.type||'Netzwerkfehler')+'). Prüfe den Code und ob der Host noch online ist.';});
 };
 document.getElementById('leaveRoom').onclick=()=>{clean();if(peer)peer.destroy();hostConnections.clear();peer=null;conn=null;isHost=false;roomCode='';playerId='';players={};orbs=[];codePanel.hidden=true;setStatus('Nicht verbunden');msg.textContent='Du hast den Raum verlassen.';draw();renderScores();document.getElementById('createRoom').textContent='Raum erstellen'};
 document.getElementById('copyRoomCode').onclick=async()=>{try{await navigator.clipboard.writeText(roomCode);msg.textContent='Raumcode kopiert: '+roomCode}catch(e){msg.textContent='Dein Raumcode ist '+roomCode+'. Markiere ihn zum Kopieren.'}};
 function sendInput(){const x=(keys.right?1:0)-(keys.left?1:0),y=(keys.down?1:0)-(keys.up?1:0);const input={x,y,boost:!!keys.boost};if(isHost){if(players[playerId])players[playerId].input=input}else if(conn&&conn.open)conn.send({type:'input',id:playerId,input});}
 function keyChange(e,on){const k=e.key.toLowerCase();const map={arrowleft:'left',a:'left',arrowright:'right',d:'right',arrowup:'up',w:'up',arrowdown:'down',s:'down',shift:'boost'};if(map[k]){keys[map[k]]=on;e.preventDefault();sendInput()}}
 window.addEventListener('keydown',e=>{if(document.activeElement.matches('input,textarea'))return;keyChange(e,true)});window.addEventListener('keyup',e=>keyChange(e,false));
 [['multiUp','up'],['multiDown','down'],['multiLeft','left'],['multiRight','right'],['multiBoost','boost']].forEach(([id,key])=>{const b=document.getElementById(id);b.onpointerdown=e=>{e.preventDefault();keys[key]=true;sendInput()};['pointerup','pointerleave','pointercancel'].forEach(ev=>b.addEventListener(ev,()=>{keys[key]=false;sendInput()}));});
 // Host creates the match timer as soon as its room opens; guests update their movement input on a small interval.
 const nameField=document.getElementById('playerNameInput');try{nameField.value=localStorage.getItem('azubiHubPlayerName')||''}catch(e){}nameField.addEventListener('change',()=>{if(nameField.value.trim())try{localStorage.setItem('azubiHubPlayerName',nameField.value.trim().slice(0,18))}catch(e){}});
 setInterval(sendInput,80);
 draw();renderScores();
})();

</script>
</body></html>
