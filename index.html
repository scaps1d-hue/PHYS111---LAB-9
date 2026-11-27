<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Collision Lab · Conservation of Momentum</title>
<style>
:root{--ink:#172038;--mut:#5f6b85;--line:#dfe4f0;--bg:#f2f4fb;--card:#ffffff;--acc:#b01e36;--acc2:#8a1429;--navy:#14213d;--b1:#12b5a5;--b2:#ff9414;--ok:#16a34a;--bad:#dc2626;
--th:#eef1fa;--fix:#e4e9f7;--calc:#fff6dc;--field:#ffffff;--soft:#f7f8fd;--goodbg:#e6f8ec;--badbg:#fde8e8;--warnbg:#fff4dc;--warnln:#f1cf86;--shadow:0 6px 22px rgba(20,33,61,.08)}
body.dark{--ink:#e9edf7;--mut:#9ba8c4;--line:#2c3757;--bg:#0c1222;--card:#161f36;--acc:#ff5d73;--acc2:#ff8d9c;--th:#202b49;--fix:#26325a;--calc:#3a3320;--field:#0f172b;--soft:#1b2540;--goodbg:#143424;--badbg:#44181c;--warnbg:#3b3018;--warnln:#6b5524;--shadow:0 6px 22px rgba(0,0,0,.35)}
*{box-sizing:border-box}
body{margin:0;font:15px/1.55 "Segoe UI",system-ui,-apple-system,Roboto,Arial,sans-serif;color:var(--ink);background:var(--bg);transition:background .25s,color .25s}
header.top{background:linear-gradient(115deg,#14213d 0%,#3b1638 55%,#b01e36 100%);color:#fff;padding:20px 26px 22px;display:flex;gap:20px;align-items:center;flex-wrap:wrap;position:relative;overflow:hidden}
header.top::before,header.top::after{content:"";position:absolute;border-radius:50%;pointer-events:none}
header.top::before{width:260px;height:260px;right:-60px;top:-120px;background:radial-gradient(circle,#ff941455,transparent 70%)}
header.top::after{width:200px;height:200px;right:180px;bottom:-140px;background:radial-gradient(circle,#12b5a555,transparent 70%)}
.logo{width:250px;height:92px;border:2px dashed #ffffff88;border-radius:14px;display:flex;align-items:center;justify-content:center;color:#5f6b85;font-size:12.5px;text-align:center;cursor:pointer;overflow:hidden;background:#fff;padding:6px;z-index:1;box-shadow:0 6px 18px rgba(0,0,0,.25)}
.logo img{max-width:100%;max-height:100%}
.titles{flex:1;min-width:260px;z-index:1}
.titles input{font:inherit;border:0;background:transparent;width:100%;color:#ffffffcc;padding:0}
.titles input.inst{font-size:16px;font-weight:700;color:#fff;letter-spacing:.4px;text-transform:uppercase}
.rights{font-size:11.5px;color:#ffffffb3;margin-top:1px}
.pagefoot{text-align:center;font-size:12.5px;color:var(--mut);padding:0 20px 26px}
.titles h1{margin:4px 0 0;font-size:27px;font-weight:800;letter-spacing:-.3px}
.titles h1 span{background:linear-gradient(90deg,#ffd166,#ff9414);-webkit-background-clip:text;background-clip:text;color:transparent}
.hside{z-index:1;min-width:210px;display:flex;flex-direction:column;gap:8px;align-items:flex-end}
.prog{width:210px;height:10px;border-radius:99px;background:#ffffff33;overflow:hidden}
#progBar{height:100%;width:0;border-radius:99px;background:linear-gradient(90deg,#12b5a5,#ffd166);transition:width .4s}
#progTxt{font-size:12.5px;color:#ffffffdd}
#themeBtn{border:1px solid #ffffff66;background:#ffffff1f;color:#fff;border-radius:99px;padding:5px 12px;font:inherit;font-size:13px;cursor:pointer}
nav{display:flex;gap:8px;flex-wrap:wrap;padding:12px 26px;background:var(--card);border-bottom:1px solid var(--line);position:sticky;top:0;z-index:20;box-shadow:0 4px 14px rgba(20,33,61,.06)}
nav button{border:1.5px solid var(--line);background:var(--card);border-radius:999px;padding:7px 15px 7px 10px;font:inherit;font-weight:600;font-size:13.5px;cursor:pointer;color:var(--ink);display:flex;align-items:center;gap:8px;transition:transform .12s,box-shadow .12s,background .2s}
nav button::before{content:"";width:16px;height:16px;border-radius:50%;flex:none;background:conic-gradient(var(--ok) calc(var(--p,0)*1%),var(--line) 0);box-shadow:inset 0 0 0 3.5px var(--card)}
nav button[data-s=sim]::before,nav button.rep::before{display:none}
nav button[data-s=sim],nav button.rep{padding-left:15px}
nav button:hover{transform:translateY(-1px);box-shadow:0 4px 10px rgba(20,33,61,.12)}
nav button.on{background:linear-gradient(120deg,var(--navy),#b01e36);border-color:transparent;color:#fff}
nav button.on::before{box-shadow:inset 0 0 0 3.5px #5a1a3a}
nav button.rep:not(.on){border-color:var(--acc);color:var(--acc)}
nav .sp{flex:1}
main{max-width:1200px;margin:0 auto;padding:22px 26px 70px}
.card{background:var(--card);border:1px solid var(--line);border-radius:18px;padding:20px 22px;margin-bottom:18px;box-shadow:var(--shadow)}
h2{font-size:19px;margin:0 0 12px;color:var(--ink);font-weight:800;display:flex;align-items:center;gap:10px;flex-wrap:wrap}
h2::before{content:"";width:6px;height:22px;border-radius:4px;background:linear-gradient(var(--b2),var(--acc))}
h3{font-size:15px;margin:14px 0 8px;font-weight:700}
.grid{display:grid;gap:16px}
.g2{grid-template-columns:1fr 1fr}
@media(max-width:860px){.g2{grid-template-columns:1fr}.hside{align-items:flex-start}}
label.f{display:flex;flex-direction:column;font-size:12.5px;font-weight:600;color:var(--mut);gap:4px}
input[type=text],input[type=number],input[type=date],select,textarea{font:inherit;border:1.5px solid var(--line);border-radius:10px;padding:7px 10px;background:var(--field);color:var(--ink);width:100%;transition:border-color .15s,box-shadow .15s}
textarea{min-height:78px;resize:vertical}
input:focus,select:focus,textarea:focus{outline:0;border-color:var(--b1);box-shadow:0 0 0 3px #12b5a533}
.btn{border:1.5px solid var(--line);background:var(--card);color:var(--ink);border-radius:10px;padding:8px 14px;font:inherit;font-weight:600;cursor:pointer;transition:transform .12s,box-shadow .12s}
.btn:hover{transform:translateY(-1px);box-shadow:0 4px 12px rgba(20,33,61,.14)}
.btn:active{transform:none}
.btn.pri{background:linear-gradient(120deg,#b01e36,#e2452f);border-color:transparent;color:#fff;box-shadow:0 4px 14px #b01e3655}
.btn.sm{padding:4px 10px;font-size:12.5px;border-radius:8px}
.btn[data-load]{border-color:var(--b1);color:var(--b1)}
.btn[data-rec]{background:var(--b2);border-color:var(--b2);color:#fff}
.btn[data-check]{border-color:var(--ok);color:var(--ok)}
canvas{width:100%;height:430px;display:block;border-radius:16px;background:#0d1730;box-shadow:inset 0 0 0 1px #2b3a66,0 10px 26px rgba(13,23,48,.35)}
.ctrl{display:flex;gap:10px;align-items:center;flex-wrap:wrap;margin-top:14px;background:var(--soft);border:1px solid var(--line);border-radius:14px;padding:10px 12px}
.ctrl .time{font-variant-numeric:tabular-nums;font-weight:700;border-radius:10px;padding:7px 12px;min-width:92px;text-align:right;background:#0d1730;color:#7ef0e2;font-family:Consolas,Menlo,monospace}
#bPlay{min-width:104px;font-size:15.5px}
input[type=range]{accent-color:var(--acc)}
input[type=checkbox],input[type=radio]{accent-color:var(--b1);width:16px;height:16px}
#elasV{background:var(--acc);color:#fff;border-radius:99px;padding:2px 10px;text-align:center;font-size:13px}
.tw{overflow-x:auto}
table{border-collapse:separate;border-spacing:0;width:100%;border:1px solid var(--line);border-radius:12px;overflow:hidden}
th,td{border-right:1px solid var(--line);border-bottom:1px solid var(--line);padding:6px 7px;text-align:center;font-size:13.5px}
tr>*:last-child{border-right:0}tr:last-child>*{border-bottom:0}
th{background:var(--th);font-weight:700;color:var(--ink)}
td.fix{background:var(--fix);font-weight:700}
td.calc{background:var(--calc)}
td input,td select{padding:5px 6px;text-align:center;min-width:58px}
td input[type=range]{padding:0;min-width:90px;margin-top:5px;display:block}
canvas{touch-action:none}
th input{width:64px!important;padding:2px 4px!important;text-align:center;font-size:12px!important;margin-top:3px}
td.acts{white-space:nowrap;background:transparent;text-align:left}
input.good,select.good{border-color:var(--ok);background:var(--goodbg)}
input.wrong,select.wrong{border-color:var(--bad);background:var(--badbg)}
.ball1{color:var(--b1);font-weight:800}.ball2{color:var(--b2);font-weight:800}
.kv{display:grid;grid-template-columns:repeat(2,1fr);gap:10px}
.kv div{border-radius:14px;padding:10px 12px;background:var(--soft);border:1px solid var(--line);border-left:5px solid var(--b1)}
.kv div:nth-child(2){border-left-color:var(--b2)}.kv div:nth-child(3){border-left-color:#4f6df5}.kv div:nth-child(4){border-left-color:var(--acc)}
.kv small{display:block;color:var(--mut);font-size:11.5px;font-weight:600}
.kv b{font-variant-numeric:tabular-nums;font-size:17px}
.meter{margin-top:12px}
.meter .lab{display:flex;justify-content:space-between;font-size:12.5px;font-weight:600;color:var(--mut)}
.meter .bar{height:12px;border-radius:99px;background:var(--line);overflow:hidden;margin-top:4px}
.meter .bar i{display:block;height:100%;width:100%;border-radius:99px;background:linear-gradient(90deg,#ff9414,#ffd166);transition:width .15s}
.meter .bar i.p{background:linear-gradient(90deg,#4f6df5,#12b5a5)}
.note{font-size:13px;color:var(--mut);font-weight:400}
.warn{font-size:13px;background:var(--warnbg);border:1px solid var(--warnln);border-radius:12px;padding:8px 12px;margin-top:10px;display:none}
.q{margin:14px 0}
.q p{margin:0 0 6px;font-weight:700}
.steps{margin:4px 0 12px;padding:0;list-style:none;counter-reset:st;font-size:14.5px}
.steps li{counter-increment:st;position:relative;padding:5px 0 5px 36px}
.steps li::before{content:counter(st);position:absolute;left:0;top:4px;width:24px;height:24px;border-radius:50%;background:linear-gradient(135deg,var(--b1),#4f6df5);color:#fff;font-weight:700;font-size:12.5px;display:flex;align-items:center;justify-content:center}
.eq{display:inline-block;background:var(--soft);border:1px solid var(--line);border-radius:10px;padding:4px 12px;font-weight:700;font-family:Cambria,"Times New Roman",serif;font-size:16px}
.tbar{display:flex;gap:8px;align-items:center;flex-wrap:wrap;margin:12px 0 8px}
.tbar>b:first-child{background:var(--navy);color:#fff;border-radius:8px;padding:3px 10px;font-size:13px}
#toast{position:fixed;left:50%;bottom:24px;transform:translateX(-50%);background:linear-gradient(120deg,#14213d,#b01e36);color:#fff;padding:10px 18px;border-radius:999px;font-size:14px;font-weight:600;opacity:0;transition:opacity .25s;pointer-events:none;z-index:50;box-shadow:0 8px 24px rgba(0,0,0,.3)}
#toast.show{opacity:1}
.sec{display:none}.sec.on{display:block;animation:fade .3s}
#trialsCard{display:none}
body[data-page] nav{display:none}
body[data-page=sim] #trialsCard{display:block}
body[data-page=report] td.acts,body[data-page=report] th.noprint{display:none}
.trow{display:flex;gap:10px;align-items:center;flex-wrap:wrap;padding:7px 10px;border:1px solid var(--line);border-radius:12px;margin:6px 0;background:var(--soft)}
.trow .nm{font-weight:700;min-width:64px}.trow .set{min-width:230px;font-variant-numeric:tabular-nums}
.trow input{width:84px}.trow .res{margin-left:auto;font-size:13px;font-weight:600;color:var(--mut)}.trow .res.ok{color:var(--ok)}
.tgrp{font-weight:800;margin:14px 0 4px;display:flex;gap:10px;align-items:center;flex-wrap:wrap}.tgrp input{width:90px}
#reportView{display:none}
.rtop{display:flex;gap:20px;align-items:center;flex-wrap:wrap}
.ring{width:96px;height:96px;border-radius:50%;flex:none;display:flex;align-items:center;justify-content:center;font-weight:800;font-size:22px;background:conic-gradient(var(--ok) calc(var(--p,0)*1%),var(--line) 0);position:relative}
.ring::before{content:"";position:absolute;inset:10px;border-radius:50%;background:var(--card)}
.ring span{position:relative}
.chips{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
.chip{border:1.5px solid var(--line);border-radius:99px;padding:4px 12px;font-size:12.5px;font-weight:600;background:var(--soft);color:var(--ink);cursor:pointer;font-family:inherit}
.chip.todo{border-color:var(--b2);color:var(--b2)}.chip.done{border-color:var(--ok);color:var(--ok);cursor:default}
.chip.ok{background:var(--goodbg);border-color:var(--ok);color:var(--ok);cursor:default}.chip.no{background:var(--badbg);border-color:var(--bad);color:var(--bad);cursor:default}
details.rp{background:var(--card);border:1px solid var(--line);border-radius:18px;margin-bottom:18px;box-shadow:var(--shadow);overflow:hidden}
details.rp>summary{list-style:none;cursor:pointer;padding:16px 22px;font-weight:800;font-size:17px;display:flex;align-items:center;gap:12px}
details.rp>summary::-webkit-details-marker{display:none}
details.rp>summary::before{content:"▸";color:var(--acc);transition:transform .2s}
details.rp[open]>summary::before{transform:rotate(90deg)}
details.rp>summary .pct{margin-left:auto;font-size:12.5px;font-weight:700;border-radius:99px;padding:3px 12px;background:var(--soft);border:1.5px solid var(--line)}
details.rp>summary .pct.full{background:var(--goodbg);border-color:var(--ok);color:var(--ok)}
details.rp>.in{padding:0 22px 20px}
.cover{display:grid;grid-template-columns:1fr 1fr;gap:18px}
@media(max-width:860px){.cover{grid-template-columns:1fr}}
.cover .rights{color:var(--mut)}
.cover img{max-height:84px;max-width:100%;background:#fff;border-radius:12px;padding:6px}
.charts{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-top:10px}
@media(max-width:860px){.charts{grid-template-columns:1fr}}
.charts>div{border:1px solid var(--line);border-radius:14px;background:var(--soft);padding:8px}
svg.ch{width:100%;height:auto;display:block}
svg.ch rect.bar{transition:opacity .15s}svg.ch g.grp:hover rect.bar{opacity:.75}
.qc{display:flex;gap:10px;align-items:center;flex-wrap:wrap;margin:4px 0 6px}.qc select,.qc input{width:120px}
.gsum{display:flex;gap:22px;align-items:center;flex-wrap:wrap}
.gsum .ring{width:120px;height:120px;font-size:24px}.gsum .ring small{font-size:12px;font-weight:600;color:var(--mut)}
.fbl{margin:8px 0 0;padding-left:20px;font-size:13.5px}.fbl li{margin:2px 0}
.wc{font-size:11.5px;color:var(--mut);text-align:right;margin-top:2px}
@keyframes fade{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}
.chk{display:flex;gap:8px;flex-wrap:wrap;font-size:13px}
.chk label{display:flex;gap:6px;align-items:center;border:1px solid var(--line);border-radius:99px;padding:4px 11px;background:var(--soft);cursor:pointer}
#reportView{background:#fff;color:#111;border:1px solid var(--line);border-radius:14px;padding:26px 30px;box-shadow:var(--shadow)}
@media print{
  body{background:#fff}
  header.top,nav,.sec:not(#sec-report),.noprint,#toast{display:none!important}
  #sec-report{display:block!important}
  main{max-width:none;padding:0}
  #reportView{display:block!important;border:0;padding:0;box-shadow:none}
}
</style>
<style>
body[data-page=sim] .prog,body[data-page=sim] #progTxt,body[data-page=sim] .pagefoot{display:none}
header.top{background:linear-gradient(115deg,#e11d48,#ff8a3d)}

/* momentum and kinetic energy are calculated by the students, so the lab does not show them */
#simCard table tr>*:nth-child(5),#simCard table tr>*:nth-child(6),#simCard table tr:last-child,#simCard .kv div:nth-child(3),#simCard .kv div:nth-child(4),#simCard .meter{display:none!important}
body.emb header.top{display:none}
body.emb main{padding-top:10px}
.trow .set input{width:66px;padding:5px 6px}
.trow{gap:8px}.trow .set{min-width:0}
</style>
</head>
<body data-page="sim">
<header class="top">
  <div class="logo" id="logoBox" title="Click to replace the logo image"><span>Click to add the official<br>university logo (PNG, JPG, SVG)</span></div>
  <input type="file" id="logoFile" accept="image/*" hidden>
  <div class="titles">
    <input class="inst" data-k="inst" value="American University of Ras Al Khaimah" aria-label="Institution">
    <input data-k="course" value="PHYS111" aria-label="Course code">
    <div class="rights">© 2026 American University of Ras Al Khaimah (AURAK). All rights reserved.</div>
    <h1>Lab 9: <span>Conservation of Momentum</span></h1>
  </div>
  <div class="hside"><button id="themeBtn" type="button">Dark mode</button><div class="prog"><div id="progBar"></div></div><span id="progTxt">Lab progress 0%</span></div>
</header>
<nav id="nav">
  <button data-s="info" class="on">Student details</button>
  <button data-s="sim">Simulator</button>
  <button data-s="p1a">Part 1A · Elastic, m₁ = m₂</button>
  <button data-s="p1b">Part 1B · Elastic, m₁ ≠ m₂</button>
  <button data-s="p2">Part 2 · Inelastic</button>
  <button data-s="concl">Lab assignment</button>
  <span class="sp"></span>
  <button data-s="report" class="rep">Digital report</button>
</nav>
<main>

<section class="sec on" id="sec-info">
  <div class="card">
    <h2>Student details</h2>
    <div class="grid g2">
      <label class="f">Date<input type="date" data-k="date"></label>
      <label class="f">Section<input type="text" data-k="sec"></label>
      <label class="f">Student 1 name<input type="text" data-k="n1"></label>
      <label class="f">Student 1 ID<input type="text" data-k="id1"></label>
      <label class="f">Student 2 name<input type="text" data-k="n2"></label>
      <label class="f">Student 2 ID<input type="text" data-k="id2"></label>
    </div>
  </div>
  <div class="card">
    <h2>Objectives</h2>
    <ol class="steps">
      <li>Study the types of collisions in one dimension between two balls using a simulation.</li>
      <li>Determine the kinetic energy and the linear momentum of each ball before and after the collision.</li>
      <li>Identify the main difference between the elastic collision and the inelastic collision.</li>
    </ol>
    <h2>Key relations</h2>
    <p style="margin:8px 0">Momentum: <span class="eq">m₁v₁ + m₂v₂ = m₁v₁′ + m₂v₂′</span> (holds for every collision when the net external force is zero).</p>
    <p style="margin:8px 0">Elastic: <span class="eq">½m₁v₁ᵢ² + ½m₂v₂ᵢ² = ½m₁v₁f² + ½m₂v₂f²</span>.</p>
    <p style="margin:8px 0">Perfectly inelastic: <span class="eq">m₁v₁ + m₂v₂ = (m₁ + m₂)v_f</span>, and K_f = ½(m₁ + m₂)v_f² &lt; K_i.</p>
    <h2 style="margin-top:14px">How to use this page</h2>
    <ol class="steps">
      <li>In each part, press <b>Load</b> on a table row to send its masses and velocities to the simulator.</li>
      <li>Press <b>Play</b>. The simulator pauses just after the balls collide.</li>
      <li>Press <b>Record</b> on the same row to copy the final velocities into the table, or type them yourself.</li>
      <li>Calculate the shaded quantities and enter them, with their units.</li>
      <li>When all parts are complete, open <b>Digital report</b>, review it, and press <b>Submit for grading</b>. Grading is automatic, out of 40, and is based on your own masses and initial velocities.</li>
    </ol>
    <div class="tbar noprint">
      <button class="btn" id="saveJson">Save progress to file</button>
      <button class="btn" id="loadJsonBtn">Open saved progress</button>
      <input type="file" id="loadJson" accept=".json" hidden>
      <button class="btn" id="clearAll">Clear all entries</button>
    </div>
  </div>
</section>

<section class="sec" id="sec-sim">
  <div class="card" id="simCard">
    <h2>Collision simulator <span class="note" id="loadedTag" style="font-weight:400"></span></h2>
    <canvas id="cv" height="430"></canvas>
    <div class="ctrl">
      <span class="time" id="tRead">0.00 s</span>
      <button class="btn" id="bReset" title="Return to the initial settings">⟲ Reset</button>
      <button class="btn pri" id="bPlay">▶ Play</button>
      <button class="btn" id="bStep" title="Advance 0.02 s">Step ▷|</button>
      <label><input type="radio" name="spd" value="1" checked> Normal</label>
      <label><input type="radio" name="spd" value="0.25"> Slow</label>
      <span style="flex:1"></span>
      <label style="display:flex;gap:8px;align-items:center">Elasticity
        <input type="range" id="elas" min="0" max="100" step="1" value="100" style="width:170px">
        <b id="elasV" style="min-width:44px">100%</b></label>
    </div>
    <div class="chk" style="margin-top:10px">
      <label><input type="checkbox" id="oVel" checked> Velocity arrows</label>
      <label><input type="checkbox" id="oMom"> Momentum arrows</label>
      <label><input type="checkbox" id="oCM"> Centre of mass</label>
      <label><input type="checkbox" id="oVal" checked> Values on balls</label>
      <label><input type="checkbox" id="oWall" checked> Reflecting border</label>
      <label><input type="checkbox" id="oAuto"> Pause after collision</label>
    </div>
    <div class="grid g2" style="margin-top:12px">
      <div>
        <table>
          <tr><th></th><th>Mass (kg)</th><th>Position (m)</th><th>Velocity (m/s)</th><th>Momentum (kg·m/s)</th><th>K (J)</th></tr>
          <tr><td class="ball1">Ball 1</td><td><input type="number" id="m1" step="0.1" min="0.1" max="3" value="1"><input type="range" id="m1r" min="0.1" max="3" step="0.1" aria-label="m1 slider"></td><td><input type="number" id="x1" step="0.1" value="-1"><input type="range" id="x1r" min="-3" max="3" step="0.05" aria-label="x1 slider"></td><td><input type="number" id="v1" step="0.1" value="1"><input type="range" id="v1r" min="-4" max="4" step="0.1" aria-label="v1 slider"></td><td id="p1o">–</td><td id="k1o">–</td></tr>
          <tr><td class="ball2">Ball 2</td><td><input type="number" id="m2" step="0.1" min="0.1" max="3" value="1"><input type="range" id="m2r" min="0.1" max="3" step="0.1" aria-label="m2 slider"></td><td><input type="number" id="x2" step="0.1" value="1"><input type="range" id="x2r" min="-3" max="3" step="0.05" aria-label="x2 slider"></td><td><input type="number" id="v2" step="0.1" value="0"><input type="range" id="v2r" min="-4" max="4" step="0.1" aria-label="v2 slider"></td><td id="p2o">–</td><td id="k2o">–</td></tr>
          <tr><th colspan="4" style="text-align:right">Total</th><th id="pto">–</th><th id="kto">–</th></tr>
        </table>
        <p class="note">Change mass, position and velocity with the sliders or boxes, or drag a ball along the track, at any time, even while the balls are moving. Dragging a ball works when the motion is paused. Changing a value starts a fresh measurement of the next collision. Positive velocity points right.</p>
      </div>
      <div>
        <h3 style="margin-top:0">First ball–ball collision</h3>
        <div class="kv">
          <div><small>v₁ before → after (m/s)</small><b id="cv1">–</b></div>
          <div><small>v₂ before → after (m/s)</small><b id="cv2">–</b></div>
          <div><small>P before → after (kg·m/s)</small><b id="cP">–</b></div>
          <div><small>K before → after (J)</small><b id="cK">–</b></div>
        </div>
        <div class="meter"><div class="lab"><span>Kinetic energy now vs start</span><span id="mK">100%</span></div><div class="bar"><i id="mKb"></i></div></div>
        <div class="meter"><div class="lab"><span>Total momentum now vs start</span><span id="mP">–</span></div><div class="bar"><i class="p" id="mPb"></i></div></div>
        <div class="warn" id="wallWarn">The balls bounced off a wall before they met. A wall exerts an external force, so the velocities just before the collision differ from the ones you set. Compare momentum just before and just after the ball–ball collision.</div>
        <p class="note">“Before” and “after” are measured at the instant of contact, so they are not affected by later wall bounces.</p>
      </div>
    </div>
  </div>
  <div class="card" id="trialsCard"><h2>Lab trials</h2><p class="note">Press <b>Load</b> on a trial, press <b>Play</b>, then press <b>Record</b>. Recorded final velocities are sent to your lab report. Choose your masses, start positions and initial velocities here or in the report; the report is marked against your choices.</p><div id="trials"></div></div>
</section>

<section class="sec" id="sec-p1a">
  <div class="card">
    <h2>Part 1A: Elastic collision, m₁ = m₂</h2>
    <ol class="steps">
      <li>Keep Elasticity = 100 % and choose equal masses.</li>
      <li>Load a row, press Play, and record v₁f and v₂f after the collision.</li>
      <li>Calculate P_i, P_f, K_i and K_f. For the last two rows choose your own initial velocities.</li>
    </ol>
    <div class="tbar"><b>Table 1</b> (6 marks) &nbsp; m₁ = m₂ = <input type="number" data-k="t1.m" step="0.1" min="0.1" max="3" style="width:90px" placeholder="kg"> kg</div>
    <div id="T1" class="tw"></div>
    <div class="q"><p>1) Is the momentum conserved? Explain. (2 marks)</p><textarea data-k="q1a1"></textarea></div>
    <div class="q"><p>2) Is the K.E. conserved? Explain. (2 marks)</p><textarea data-k="q1a2"></textarea></div>
  </div>
</section>

<section class="sec" id="sec-p1b">
  <div class="card">
    <h2>Part 1B: Elastic collision, m₁ ≠ m₂</h2>
    <ol class="steps">
      <li>Keep Elasticity = 100 %. Select m₁ = 2–3 kg and m₂ = 0.5–2 kg (m₂ &lt; m₁).</li>
      <li>Keep position 1 at −1 m and position 2 at 1 m.</li>
      <li>Load each row, press Play, and record v₁f and v₂f into Tables 2 and 3.</li>
    </ol>
    <div class="tbar"><b>Table 2</b> (6 marks) &nbsp; m₁ = <input type="number" data-k="t23.m1" step="0.1" min="0.1" max="3" style="width:90px" placeholder="kg"> kg &nbsp; m₂ = <input type="number" data-k="t23.m2" step="0.1" min="0.1" max="3" style="width:90px" placeholder="kg"> kg</div>
    <div id="T2" class="tw"></div>
    <div class="tbar"><b>Table 3</b> (6 marks)</div>
    <div id="T3" class="tw"></div>
    <div class="q"><p>1) Is the momentum conserved? Explain. (2 marks)</p><textarea data-k="q1b1"></textarea></div>
    <div class="q"><p>2) Is the K.E. conserved? Explain. (2 marks)</p><textarea data-k="q1b2"></textarea></div>
  </div>
</section>

<section class="sec" id="sec-p2">
  <div class="card">
    <h2>Part 2: Inelastic collision</h2>
    <ol class="steps">
      <li>Select Elasticity = 0 %. Keep position 1 at −1 m and position 2 at 1 m.</li>
      <li>Load each row, press Play, and record the common final velocity v_f into Tables 4 and 5.</li>
      <li>Calculate P_i, P_f, K_i and K_f.</li>
    </ol>
    <div class="tbar"><b>Table 4</b> (6 marks)</div>
    <div id="T4" class="tw"></div>
    <div class="q"><p>1. Is the momentum conserved? Explain. (2 marks)</p><textarea data-k="q2a1"></textarea></div>
    <div class="tbar"><b>Table 5</b> (6 marks)</div>
    <div id="T5" class="tw"></div>
    <div class="q"><p>1. Is the energy conserved? Explain. (2 marks)</p><textarea data-k="q2b1"></textarea></div>
    <div class="q"><p>2. Is there a pattern for the change of energy? (2 marks)</p><textarea data-k="q2b2"></textarea></div>
    <div class="q"><p>3. Calculate the fractional change of the kinetic energy and the percent loss of energy. Explain where this energy is lost. (2 marks)</p><textarea data-k="q2b3"></textarea></div>
  </div>
</section>

<section class="sec" id="sec-concl">
  <div class="card">
    <h2>Lab assignment</h2>
    <div id="assign"></div>
  </div>
</section>

<section class="sec" id="sec-report">
  <div id="reportLive" class="noprint"></div>
  <div id="reportView"></div>
</section>
</main>
<footer class="pagefoot noprint">© 2026 American University of Ras Al Khaimah (AURAK). All rights reserved.</footer>
<div id="toast"></div>

<script>
"use strict";
var DEFAULT_LOGO="data:image/png;base64,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";
/* ---------------- state ---------------- */
var S = {};
var KEY = "phy111_lab9_v1";
function $(id){return document.getElementById(id);}
function toast(msg){var t=$("toast");t.textContent=msg;t.classList.add("show");clearTimeout(toast._h);toast._h=setTimeout(function(){t.classList.remove("show");},2600);}
function persist(){try{localStorage.setItem(KEY,JSON.stringify(S));}catch(e){}}
function restore(){try{var s=localStorage.getItem(KEY);if(s){S=JSON.parse(s)||{};}}catch(e){S={};}}
function num(v){if(v===undefined||v===null||v==="")return NaN;return parseFloat(v);}
function f2(x){return isFinite(x)?x.toFixed(2):"–";}
function esc(s){return String(s==null?"":s).replace(/[&<>"]/g,function(c){return{"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[c];});}

/* ---------------- tables ---------------- */
var ROWS1=[[1,0],[2,-2],[3,-1],[null,null],[null,null]];
var ROWS23=[[2,-1],[3,1.5],[-1.5,3]];
var ROWS45=[[2,2,2,0],[2,2,2,-2],[1.5,3,2,0.5]];
function inp(k,cls,ph){return '<input type="number" step="0.01" data-k="'+k+'" class="'+(cls||"")+'" placeholder="'+(ph||"")+'">';}
function yn(k){return '<select data-k="'+k+'"><option value=""></option><option>Y</option><option>N</option></select>';}
function unit(k,def){return '<br><input type="text" data-k="'+k+'" placeholder="unit" title="Enter the unit" aria-label="unit">';}
function acts(t,r){return '<td class="acts noprint"><button class="btn sm" data-load="'+t+'.'+r+'">Load</button> <button class="btn sm" data-rec="'+t+'.'+r+'">Record</button></td>';}
function buildTables(){
  var h='<table><tr><th>V₁ᵢ<br>(m/s)</th><th>V₂ᵢ<br>(m/s)</th><th>V₁f<br>(m/s)</th><th>V₂f<br>(m/s)</th><th>Pᵢ = m₁v₁ᵢ + m₂v₂ᵢ<br>(kg·m/s)</th><th>P_f = m₁v₁f + m₂v₂f<br>(kg·m/s)</th><th>Kᵢ = ½m₁v₁ᵢ² + ½m₂v₂ᵢ²<br>(J)</th><th>K_f = ½m₁v₁f² + ½m₂v₂f²<br>(J)</th><th class="noprint" style="border:0;background:transparent"></th></tr>';
  ROWS1.forEach(function(r,i){
    var vi=r[0]===null?'<td>'+inp("t1."+i+".v1i","","choose")+'</td><td>'+inp("t1."+i+".v2i","","choose")+'</td>':'<td class="fix">'+r[0].toFixed(2)+'</td><td class="fix">'+r[1].toFixed(2)+'</td>';
    h+='<tr>'+vi+'<td>'+inp("t1."+i+".v1f")+'</td><td>'+inp("t1."+i+".v2f")+'</td><td class="calc">'+inp("t1."+i+".pi","c")+'</td><td>'+inp("t1."+i+".pf","c")+'</td><td class="calc">'+inp("t1."+i+".ki","c")+'</td><td>'+inp("t1."+i+".kf","c")+'</td>'+acts("t1",i)+'</tr>';
  });
  $("T1").innerHTML=h+'</table>'+bar("t1");
  h='<table><tr><th>V₁ᵢ<br>(m/s)</th><th>V₂ᵢ<br>(m/s)</th><th>V₁f'+unit("u.t2.v1f")+'</th><th>V₂f'+unit("u.t2.v2f")+'</th><th>Pᵢ = m₁v₁ᵢ + m₂v₂ᵢ<br>(kg·m/s)</th><th>P_f = m₁v₁f + m₂v₂f'+unit("u.t2.pf")+'</th><th>P_f = Pᵢ<br>(Y/N)</th><th class="noprint" style="border:0;background:transparent"></th></tr>';
  ROWS23.forEach(function(r,i){h+='<tr><td class="fix">'+r[0].toFixed(2)+'</td><td class="fix">'+r[1].toFixed(2)+'</td><td>'+inp("t23."+i+".v1f")+'</td><td>'+inp("t23."+i+".v2f")+'</td><td class="calc">'+inp("t23."+i+".pi","c")+'</td><td>'+inp("t23."+i+".pf","c")+'</td><td>'+yn("t23."+i+".pyn")+'</td>'+acts("t23",i)+'</tr>';});
  $("T2").innerHTML=h+'</table>'+bar("t2");
  h='<table><tr><th>V₁ᵢ<br>(m/s)</th><th>V₂ᵢ<br>(m/s)</th><th>V₁f'+unit("u.t3.v1f")+'</th><th>V₂f'+unit("u.t3.v2f")+'</th><th>KEᵢ = 0.5m₁v₁ᵢ² + 0.5m₂v₂ᵢ²<br>(J)</th><th>KE_f = 0.5m₁v₁f² + 0.5m₂v₂f²'+unit("u.t3.kf")+'</th><th>K_f = Kᵢ<br>(Y/N)</th></tr>';
  ROWS23.forEach(function(r,i){h+='<tr><td class="fix">'+r[0].toFixed(2)+'</td><td class="fix">'+r[1].toFixed(2)+'</td><td>'+inp("t23."+i+".v1f")+'</td><td>'+inp("t23."+i+".v2f")+'</td><td class="calc">'+inp("t23."+i+".ki","c")+'</td><td>'+inp("t23."+i+".kf","c")+'</td><td>'+yn("t23."+i+".kyn")+'</td></tr>';});
  $("T3").innerHTML=h+'</table>'+bar("t3");
  h='<table><tr><th>m₁<br>(kg)</th><th>m₂<br>(kg)</th><th>V₁ᵢ<br>(m/s)</th><th>V₂ᵢ<br>(m/s)</th><th>V_f'+unit("u.t4.vf")+'</th><th>Pᵢ = m₁v₁ᵢ + m₂v₂ᵢ<br>(kg·m/s)</th><th>P_f = (m₁ + m₂)v_f'+unit("u.t4.pf")+'</th><th>Pᵢ = P_f<br>(Y/N)</th><th class="noprint" style="border:0;background:transparent"></th></tr>';
  ROWS45.forEach(function(r,i){h+='<tr><td class="fix">'+r[0]+'</td><td class="fix">'+r[1]+'</td><td class="fix">'+r[2].toFixed(2)+'</td><td class="fix">'+r[3].toFixed(2)+'</td><td>'+inp("t45."+i+".vf")+'</td><td class="calc">'+inp("t45."+i+".pi","c")+'</td><td>'+inp("t45."+i+".pf","c")+'</td><td>'+yn("t45."+i+".pyn")+'</td>'+acts("t45",i)+'</tr>';});
  $("T4").innerHTML=h+'</table>'+bar("t4");
  h='<table><tr><th>m₁<br>(kg)</th><th>m₂<br>(kg)</th><th>V₁ᵢ<br>(m/s)</th><th>V₂ᵢ<br>(m/s)</th><th>V_f'+unit("u.t5.vf")+'</th><th>Kᵢ = 0.5m₁v₁ᵢ² + 0.5m₂v₂ᵢ²<br>(J)</th><th>K_f = 0.5(m₁ + m₂)v_f²'+unit("u.t5.kf")+'</th><th>K_f = Kᵢ<br>(Y/N)</th></tr>';
  ROWS45.forEach(function(r,i){h+='<tr><td class="fix">'+r[0]+'</td><td class="fix">'+r[1]+'</td><td class="fix">'+r[2].toFixed(2)+'</td><td class="fix">'+r[3].toFixed(2)+'</td><td>'+inp("t45."+i+".vf")+'</td><td class="calc">'+inp("t45."+i+".ki","c")+'</td><td>'+inp("t45."+i+".kf","c")+'</td><td>'+yn("t45."+i+".kyn")+'</td></tr>';});
  $("T5").innerHTML=h+'</table>'+bar("t5");
  var A=["A 55.0 kg ice skater stands at rest on the ice. A friend tosses the skater a 3.20 kg ball. The skater and the ball then move backwards across the ice with a speed of 4.20 m/s. What was the speed of the ball at the moment just before the skater caught it?",
  "A 1550 kg car is moving down the highway with a velocity of 25.0 m/s when it bumps into the car ahead of it, which has a mass of 550 kg and a velocity of 15.0 m/s. After the collision, the first car moves forward with 20.0 m/s. Assuming the collision was elastic, what will be the resulting velocity of the second car and in what direction? What is the final kinetic energy after the collision?",
  "A 5.00 kg mass is moving to the right with a velocity of 12.0 m/s. A 12.0 kg mass is moving to the left with a velocity of 2.00 m/s. Assuming that these two balls have a head-on collision and stick together, what will be the final velocity of the combination? How much energy was lost in this collision?",
  "A rope holds two carts together on a frictionless surface. A spring is compressed between the two carts. After the rope between the two carts is cut, the cart on the left with a mass of 10.0 kg moves away with a velocity of 24.5 cm/s. What is the velocity of the cart on the right that has a mass of 8.50 kg?",
  "A 40.0 kg man, riding on a 14.0 kg bicycle, is moving east at 12.0 m/s. The man jumps off the front of the bicycle and lands on the ground at 8.00 m/s eastward. What is the final velocity of the cart?"];
  window.ASSIGN=A;
  $("assign").innerHTML=A.map(function(q,i){return '<div class="q"><p>'+(i+1)+'. '+esc(q)+'</p>'+qctl("a"+(i+1))+'<textarea data-k="a'+(i+1)+'" placeholder="Show your working and final answer"></textarea></div>';}).join("");
}
function bar(t){return '';}

/* expected values from what the student recorded */
function rowVals(t,i){
  var m1,m2,v1i,v2i,v1f,v2f,vf;
  if(t==="t1"){m1=m2=num(S["t1.m"]);v1i=ROWS1[i][0]===null?num(S["t1."+i+".v1i"]):ROWS1[i][0];v2i=ROWS1[i][1]===null?num(S["t1."+i+".v2i"]):ROWS1[i][1];v1f=num(S["t1."+i+".v1f"]);v2f=num(S["t1."+i+".v2f"]);}
  else if(t==="t23"){m1=num(S["t23.m1"]);m2=num(S["t23.m2"]);v1i=ROWS23[i][0];v2i=ROWS23[i][1];v1f=num(S["t23."+i+".v1f"]);v2f=num(S["t23."+i+".v2f"]);}
  else{m1=ROWS45[i][0];m2=ROWS45[i][1];v1i=ROWS45[i][2];v2i=ROWS45[i][3];vf=num(S["t45."+i+".vf"]);v1f=v2f=vf;}
  return {m1:m1,m2:m2,v1i:v1i,v2i:v2i,v1f:v1f,v2f:v2f,
    pi:m1*v1i+m2*v2i,pf:m1*v1f+m2*v2f,ki:0.5*m1*v1i*v1i+0.5*m2*v2i*v2i,kf:0.5*m1*v1f*v1f+0.5*m2*v2f*v2f};
}
function close(a,b){return Math.abs(a-b)<=Math.max(0.02,0.01*Math.abs(b));}
function same(a,b){return Math.abs(a-b)<=Math.max(0.05,0.02*Math.max(Math.abs(a),Math.abs(b)));}
var CHECKS={t1:["t1",ROWS1.length,["pi","pf","ki","kf"],[]],t2:["t23",3,["pi","pf"],["pyn"]],t3:["t23",3,["ki","kf"],["kyn"]],t4:["t45",3,["pi","pf"],["pyn"]],t5:["t45",3,["ki","kf"],["kyn"]]};
function mark(k,ok){document.querySelectorAll('[data-k="'+k+'"]').forEach(function(e){e.classList.remove("good","wrong");if(ok!==null)e.classList.add(ok?"good":"wrong");});}
function check(tn){
  var c=CHECKS[tn],t=c[0],right=0,total=0,missing=0;
  for(var i=0;i<c[1];i++){
    var e=rowVals(t,i);
    c[2].forEach(function(q){var k=t+"."+i+"."+q,v=num(S[k]);
      if(!isFinite(e[q])||!isFinite(v)){mark(k,null);if(isFinite(e[q])||i<3)missing++;return;}
      total++;var ok=close(v,e[q]);if(ok)right++;mark(k,ok);});
    c[3].forEach(function(q){var k=t+"."+i+"."+q,v=S[k];
      var a=q==="pyn"?e.pi:e.ki,b=q==="pyn"?e.pf:e.kf;
      if(!v||!isFinite(a)||!isFinite(b)){mark(k,null);missing++;return;}
      total++;var ok=(v==="Y")===same(a,b);if(ok)right++;mark(k,ok);});
  }
  var m=$("msg-"+tn);
  m.textContent=total? right+" of "+total+" entries agree with your recorded velocities"+(missing?"; "+missing+" still empty or waiting for data.":"."):"Enter the masses, the final velocities and your calculated values first.";
}
function autoFill(){
  if(S.mode!=="auto")return;
  [["t1",ROWS1.length,["pi","pf","ki","kf"]],["t23",3,["pi","pf","ki","kf"]],["t45",3,["pi","pf","ki","kf"]]].forEach(function(c){
    for(var i=0;i<c[1];i++){var e=rowVals(c[0],i);c[2].forEach(function(q){var k=c[0]+"."+i+"."+q;S[k]=isFinite(e[q])?e[q].toFixed(2):"";});
      if(c[0]!=="t1"){S[c[0]+"."+i+".pyn"]=isFinite(e.pf)?(same(e.pi,e.pf)?"Y":"N"):"";S[c[0]+"."+i+".kyn"]=isFinite(e.kf)?(same(e.ki,e.kf)?"Y":"N"):"";}}
  });
}
function paint(skip){
  document.querySelectorAll("[data-k]").forEach(function(e){if(e===skip)return;var v=S[e.dataset.k];if(v===undefined){if(e.tagName==="INPUT"&&e.defaultValue&&!e.dataset.t){S[e.dataset.k]=e.defaultValue;return;}v="";}if(e.value!==String(v))e.value=v;});
  var auto=S.mode==="auto";
  document.querySelectorAll("input.c").forEach(function(e){e.readOnly=auto;});
  document.querySelectorAll('select[data-k$="yn"]').forEach(function(e){e.disabled=auto;});
  var lock=!!S.submitted;document.querySelectorAll("[data-k]").forEach(function(e){var k=e.dataset.k;if(k!=="fb"&&k!=="inst"&&k!=="course")e.disabled=lock;});
  if(typeof progress==="function")progress();if(typeof refreshLive==="function")refreshLive();if(typeof refreshTrials==="function")refreshTrials();
}
document.addEventListener("input",function(ev){
  var e=ev.target;if(!e.dataset||!e.dataset.k)return;
  S[e.dataset.k]=e.value;e.classList.remove("good","wrong");
  autoFill();paint(e);persist();
});
document.addEventListener("change",function(ev){var e=ev.target;if(e.dataset&&e.dataset.k){S[e.dataset.k]=e.value;autoFill();paint(e);persist();}});

/* ---------------- simulator ---------------- */
var W=3.2;                       // half-width of the track (m)
var sim={t:0,run:false,b:[{},{}],stuck:false,col:null,wallHit:false,pauseAt:null,loaded:null,init:null};
function rad(m){return 0.12+0.05*m;}
function clampM(v){v=num(v);if(!isFinite(v))v=1;return Math.min(3,Math.max(0.1,v));}
function readInit(){
  var m1=clampM($("m1").value),m2=clampM($("m2").value),x1=num($("x1").value),x2=num($("x2").value),v1=num($("v1").value),v2=num($("v2").value);
  if(!isFinite(x1))x1=-1;if(!isFinite(x2))x2=1;if(!isFinite(v1))v1=0;if(!isFinite(v2))v2=0;
  v1=Math.max(-4,Math.min(4,v1));v2=Math.max(-4,Math.min(4,v2));
  var r1=rad(m1),r2=rad(m2);
  x1=Math.max(-W+r1,Math.min(W-r1-2*r2-0.02,x1));
  x2=Math.max(x1+r1+r2+0.01,Math.min(W-r2,x2));
  return {m1:m1,m2:m2,x1:x1,x2:x2,v1:v1,v2:v2,e:num($("elas").value)/100};
}
function reset(){
  var i=readInit();sim.init=i;sim.t=0;sim.run=false;sim.stuck=false;sim.col=null;sim.wallHit=false;sim.pauseAt=null;sim.trail=[[],[]];sim.fx=[];
  sim.b[0]={m:i.m1,x:i.x1,v:i.v1,r:rad(i.m1)};sim.b[1]={m:i.m2,x:i.x2,v:i.v2,r:rad(i.m2)};
  $("x1").value=+i.x1.toFixed(2);$("x2").value=+i.x2.toFixed(2);$("bPlay").textContent="▶ Play";lockInputs(false);showCol();draw();readout();
}
var VARS=["m1","m2","x1","x2","v1","v2"];
function lockInputs(on){$("cv").style.cursor=sim.run?"default":"grab";}
function applyVar(){
  sim.loaded=null;$("loadedTag").textContent="";
  if(sim.t===0){reset();return;}
  var i=readInit();sim.init=i;sim.col=null;sim.stuck=false;sim.wallHit=false;sim.pauseAt=null;sim.trail=[[],[]];
  sim.b[0]={m:i.m1,x:i.x1,v:i.v1,r:rad(i.m1)};sim.b[1]={m:i.m2,x:i.x2,v:i.v2,r:rad(i.m2)};showCol();draw();readout();
}
function syncR(){VARS.forEach(function(id){var r=$(id+"r");if(document.activeElement!==r)r.value=$(id).value;});}
function advance(dt){
  var a=sim.b[0],b=sim.b[1],e=sim.init.e,wall=$("oWall").checked,guard=0;
  while(dt>1e-9&&guard++<40){
    var tn=dt,ev=null,gap=(b.x-b.r)-(a.x+a.r),cl=a.v-b.v;
    if(!sim.stuck&&cl>1e-12){var tc=Math.max(0,gap)/cl;if(tc<=tn){tn=tc;ev="c";}}
    if(wall){
      if(a.v<0){var t1=(a.x-a.r+W)/(-a.v);if(t1<tn){tn=Math.max(0,t1);ev="l";}}
      if(b.v>0){var t2=(W-b.r-b.x)/b.v;if(t2<tn){tn=Math.max(0,t2);ev="r";}}
    }
    a.x+=a.v*tn;b.x+=b.v*tn;sim.t+=tn;dt-=tn;
    if(ev==="c"){
      var p=a.m*a.v+b.m*b.v,M=a.m+b.m,v1=(p-b.m*e*(a.v-b.v))/M,v2=(p+a.m*e*(a.v-b.v))/M;
      if(!sim.col){sim.col={x:a.x+a.r,t:sim.t,v1b:a.v,v2b:b.v,v1a:v1,v2a:v2,wall:sim.wallHit};if($("oAuto").checked)sim.pauseAt=sim.t+0.3;else toast("Collision captured. Motion continues; press Record on the table row at any time.");showCol();}
      if(Math.abs(a.v-b.v)>0.05)addFx("c",a.x+a.r,Math.abs(a.v-b.v),e);a.v=v1;b.v=v2;if(e<1e-9)sim.stuck=true;b.x=a.x+a.r+b.r;
    }else if(ev==="l"){
      if(!sim.col)sim.wallHit=true;addFx("w",-W,Math.abs(a.v),1);a.v=-a.v;if(sim.stuck)b.v=a.v;a.x=-W+a.r;if(sim.stuck)b.x=a.x+a.r+b.r;
    }else if(ev==="r"){
      if(!sim.col)sim.wallHit=true;addFx("w",W,Math.abs(b.v),1);b.v=-b.v;if(sim.stuck)a.v=b.v;b.x=W-b.r;if(sim.stuck)a.x=b.x-a.r-b.r;
    }
    if(sim.pauseAt!==null&&sim.t>=sim.pauseAt-1e-9){sim.pauseAt=null;pause();toast("Paused just after the collision. Press Record on the table row.");break;}
  }
}
var REDUCE=window.matchMedia&&window.matchMedia("(prefers-reduced-motion: reduce)").matches;
function addFx(kind,x,speed,e){
  var n=kind==="c"?Math.round(14+8*Math.min(speed,6)):6,parts=[],i;
  for(i=0;i<n;i++){var an=kind==="c"?Math.random()*2*Math.PI:(x<0?-1:1)*(Math.PI/2)+Math.PI/2+(Math.random()-0.5)*2.2;
    parts.push({a:an,s:(40+Math.random()*120)*(0.5+Math.min(speed,6)/4),z:1.5+Math.random()*3,c:Math.random()});}
  sim.fx=sim.fx||[];sim.fx.push({kind:kind,x:x,t0:performance.now(),dur:kind==="c"?850:450,pow:Math.min(1,0.35+speed/5),e:e,parts:parts});
  if(sim.fx.length>8)sim.fx.shift();
}
function fxActive(){var now=performance.now();sim.fx=(sim.fx||[]).filter(function(f){return now-f.t0<f.dur;});return sim.fx.length>0;}
function pause(){sim.run=false;$("bPlay").textContent="▶ Play";}
var last=0;
function frame(ts){
  if(sim.run){var dt=Math.min(0.05,(ts-last)/1000);var sp=num(document.querySelector('input[name=spd]:checked').value);advance(dt*sp);draw();readout();}
  else if(fxActive())draw();
  last=ts;requestAnimationFrame(frame);
}
function readout(){
  var a=sim.b[0],b=sim.b[1];meters(a,b);setTimeout(syncR,0);
  $("tRead").textContent=sim.t.toFixed(2)+" s";
  $("p1o").textContent=f2(a.m*a.v);$("p2o").textContent=f2(b.m*b.v);$("pto").textContent=f2(a.m*a.v+b.m*b.v);
  $("k1o").textContent=f2(0.5*a.m*a.v*a.v);$("k2o").textContent=f2(0.5*b.m*b.v*b.v);$("kto").textContent=f2(0.5*a.m*a.v*a.v+0.5*b.m*b.v*b.v);
  if(sim.t>0){[["x1",a.x],["x2",b.x],["v1",a.v],["v2",b.v]].forEach(function(p){var el=$(p[0]);if(document.activeElement!==el)el.value=p[1].toFixed(2);});}
}
function showCol(){
  var c=sim.col,i=sim.init;
  if(!c){["cv1","cv2","cP","cK"].forEach(function(id){$(id).textContent="–";});$("wallWarn").style.display="none";return;}
  $("cv1").textContent=f2(c.v1b)+" → "+f2(c.v1a);$("cv2").textContent=f2(c.v2b)+" → "+f2(c.v2a);
  $("cP").textContent=f2(i.m1*c.v1b+i.m2*c.v2b)+" → "+f2(i.m1*c.v1a+i.m2*c.v2a);
  $("cK").textContent=f2(0.5*i.m1*c.v1b*c.v1b+0.5*i.m2*c.v2b*c.v2b)+" → "+f2(0.5*i.m1*c.v1a*c.v1a+0.5*i.m2*c.v2a*c.v2a);
  $("wallWarn").style.display=c.wall?"block":"none";
}
function meters(a,b){
  var i=sim.init;if(!i)return;
  var k0=0.5*i.m1*i.v1*i.v1+0.5*i.m2*i.v2*i.v2,k=0.5*a.m*a.v*a.v+0.5*b.m*b.v*b.v,pc=k0>1e-9?100*k/k0:100;
  $("mK").textContent=pc.toFixed(0)+"%  ("+f2(k)+" of "+f2(k0)+" J)";$("mKb").style.width=Math.max(0,Math.min(100,pc))+"%";
  var p0=i.m1*i.v1+i.m2*i.v2,p=a.m*a.v+b.m*b.v,same=Math.abs(p-p0)<0.005;
  $("mP").textContent=f2(p)+" of "+f2(p0)+" kg·m/s"+(same?"  ✓ conserved":"  (changed by a wall)");
  $("mPb").style.width=(Math.abs(p0)>1e-9?Math.max(0,Math.min(100,100*Math.abs(p)/Math.abs(p0))):100)+"%";
}
function draw(){
  var cv=$("cv"),dpr=window.devicePixelRatio||1,w=cv.clientWidth,h=cv.clientHeight;
  if(!w)return;
  if(cv.width!==Math.round(w*dpr)||cv.height!==Math.round(h*dpr)){cv.width=Math.round(w*dpr);cv.height=Math.round(h*dpr);}
  var g=cv.getContext("2d");g.setTransform(dpr,0,0,dpr,0,0);
  var pad=30,sc=(w-2*pad)/(2*W),X=function(x){return pad+(x+W)*sc;},yF=h-50;
  var bg=g.createLinearGradient(0,0,0,h);bg.addColorStop(0,"#0b1430");bg.addColorStop(0.75,"#1a2a58");bg.addColorStop(1,"#101a3a");g.fillStyle=bg;g.fillRect(0,0,w,h);
  var now=performance.now(),hit=null;(sim.fx||[]).forEach(function(f){if(f.kind==="c")hit=f;});
  var hAge=hit?(now-hit.t0)/hit.dur:9;
  if(hit&&hAge<0.3&&!REDUCE){var amp=9*hit.pow*Math.pow(1-hAge/0.3,2);g.translate((Math.random()-0.5)*amp,(Math.random()-0.5)*amp);}
  if(hit&&hAge<0.18){g.fillStyle="rgba(255,240,200,"+(0.28*(1-hAge/0.18)*hit.pow)+")";g.fillRect(-10,-10,w+20,h+20);}
  var sq=hit&&hAge<0.28?1-0.13*hit.pow*Math.sin(Math.PI*hAge/0.28):1;
  // grid
  g.lineWidth=1;
  for(var x=-3;x<=3.001;x+=0.5){var big=Math.abs(x-Math.round(x))<1e-6;g.strokeStyle=big?"rgba(255,255,255,.10)":"rgba(255,255,255,.045)";g.beginPath();g.moveTo(X(x),16);g.lineTo(X(x),yF);g.stroke();}
  // floor
  var fl=g.createLinearGradient(X(-W),0,X(W),0);fl.addColorStop(0,"#12b5a5");fl.addColorStop(0.5,"#4f6df5");fl.addColorStop(1,"#ff9414");
  g.strokeStyle=fl;g.lineWidth=4;g.lineCap="round";g.beginPath();g.moveTo(X(-W),yF+2);g.lineTo(X(W),yF+2);g.stroke();
  g.fillStyle="#b9c6ea";g.font="11.5px Segoe UI,Arial";g.textAlign="center";
  for(x=-3;x<=3.001;x+=0.5){big=Math.abs(x-Math.round(x))<1e-6;g.strokeStyle="#7f90c2";g.lineWidth=1;g.beginPath();g.moveTo(X(x),yF+6);g.lineTo(X(x),yF+(big?16:11));g.stroke();if(big)g.fillText(x.toFixed(0)+" m",X(x),yF+32);}
  // walls
  var wall=$("oWall").checked;
  [-W,W].forEach(function(xw){g.save();if(wall){g.shadowColor="#7ea2ff";g.shadowBlur=14;g.strokeStyle="#c9d6ff";g.lineWidth=5;}else{g.setLineDash([5,7]);g.strokeStyle="rgba(255,255,255,.3)";g.lineWidth=2;}
    g.beginPath();g.moveTo(X(xw),16);g.lineTo(X(xw),yF);g.stroke();g.restore();});
  // badge
  var e=sim.init?sim.init.e:1,lab=e>0.999?"ELASTIC":(e<0.001?"PERFECTLY INELASTIC":"PARTLY INELASTIC");
  g.font="bold 11.5px Segoe UI,Arial";var tw=g.measureText(lab).width+22;g.fillStyle=e>0.999?"#12b5a5":(e<0.001?"#e2452f":"#ff9414");
  rr(g,X(-W)+12,24,tw,22,11);g.fill();g.fillStyle="#fff";g.textAlign="left";g.fillText(lab,X(-W)+23,39);g.textAlign="center";
  var cols=[["#7ff5e6","#12b5a5","#0a6f66"],["#ffd08a","#ff9414","#b85c00"]];
  sim.trail=sim.trail||[[],[]];var labs=[];
  sim.b.forEach(function(b,i){
    var cx=X(b.x),r=b.r*sc,cy=yF-r,tr=sim.trail[i];
    if(sim.run){tr.push(b.x);if(tr.length>14)tr.shift();}
    tr.forEach(function(tx,j){g.globalAlpha=0.05+0.02*j;g.fillStyle=cols[i][1];g.beginPath();g.arc(X(tx),cy,r*(0.55+0.03*j),0,2*Math.PI);g.fill();});g.globalAlpha=1;
    g.fillStyle="rgba(0,0,0,.35)";g.beginPath();g.ellipse(cx,yF+3,r*0.9,5,0,0,2*Math.PI);g.fill();
    var gr=g.createRadialGradient(cx-r*0.35,cy-r*0.4,r*0.08,cx,cy,r);gr.addColorStop(0,"#fff");gr.addColorStop(0.18,cols[i][0]);gr.addColorStop(0.6,cols[i][1]);gr.addColorStop(1,cols[i][2]);
    g.save();g.translate(cx+(i?1:-1)*r*(1-sq)*0,yF);g.scale(sq,2-sq);g.translate(-cx,-yF);g.shadowColor=cols[i][1];g.shadowBlur=22+30*(1-sq)*4;g.beginPath();g.arc(cx,cy,r,0,2*Math.PI);g.fillStyle=gr;g.fill();g.restore();
    g.fillStyle="#fff";g.font="bold "+Math.max(13,Math.min(22,r*0.7))+"px Segoe UI,Arial";g.textBaseline="middle";g.fillText(String(i+1),cx,cy+1);g.textBaseline="alphabetic";
    labs.push({cx:cx,top:cy-r,b:b,i:i});
  });
  // arrows and value tags, stacked so they never overlap
  var showV=$("oVel").checked,showP=$("oMom").checked,showT=$("oVal").checked,ROW=20;
  labs.forEach(function(L){
    var b=L.b,lines=[];
    if(showT){lines.push(["m = "+b.m.toFixed(2)+" kg",cols[L.i][0],"600 12px Segoe UI,Arial"]);lines.push(["v = "+(b.v>0?"+":"")+b.v.toFixed(2)+" m/s","#ffffff","700 13px Segoe UI,Arial"]);
      if(showP)lines.push(["p = "+(b.m*b.v>0?"+":"")+(b.m*b.v).toFixed(2)+" kg·m/s","#b9c8ff","600 12px Segoe UI,Arial"]);}
    L.lines=lines;L.tw=0;lines.forEach(function(l){g.font=l[2];L.tw=Math.max(L.tw,g.measureText(l[0]).width);});L.tw+=22;L.th=lines.length?lines.length*17+12:0;
    L.vl=showV&&Math.abs(b.v)>1e-3?Math.max(14,Math.min(150,Math.abs(b.v)*34)):0;L.pl=showP&&Math.abs(b.v)>1e-3?Math.max(14,Math.min(150,Math.abs(b.m*b.v)*22)):0;
    L.rows=(showV?1:0)+(showP?1:0);L.H=10+L.rows*ROW+(L.th?L.th+8:0);
    L.ext=Math.max(L.tw/2,L.vl,L.pl)+8;L.base=L.top;
  });
  if(labs.length===2&&Math.abs(labs[0].cx-labs[1].cx)<labs[0].ext+labs[1].ext){
    var lo=labs[0].top>=labs[1].top?labs[0]:labs[1],hi=lo===labs[0]?labs[1]:labs[0];
    lo.base=Math.min(lo.top,hi.top);hi.base=lo.base-lo.H-4;
  }
  labs.forEach(function(L){
    var b=L.b,y=L.base-14,sgn=b.v<0?-1:1;
    if(L.base<L.top-2){g.strokeStyle="rgba(255,255,255,.35)";g.lineWidth=1;g.setLineDash([3,4]);g.beginPath();g.moveTo(L.cx,L.top-3);g.lineTo(L.cx,L.base-4);g.stroke();g.setLineDash([]);}
    if(showV){if(L.vl){arrow(g,L.cx,y,sgn*L.vl,"#5dff8f");g.font="700 10.5px Segoe UI,Arial";g.fillStyle="#5dff8f";g.textAlign="center";g.fillText("v",L.cx-sgn*9,y+4);}y-=ROW;}
    if(showP){if(L.pl){arrow(g,L.cx,y,sgn*L.pl,"#8fa8ff");g.font="700 10.5px Segoe UI,Arial";g.fillStyle="#8fa8ff";g.textAlign="center";g.fillText("p",L.cx-sgn*9,y+4);}y-=ROW;}
    if(L.th){var bx=Math.max(X(-W)+8,Math.min(X(W)-8-L.tw,L.cx-L.tw/2)),by=y+8-L.th;
      g.fillStyle="rgba(8,14,34,.82)";rr(g,bx,by,L.tw,L.th,9);g.fill();g.strokeStyle=cols[L.i][1];g.lineWidth=1.5;rr(g,bx,by,L.tw,L.th,9);g.stroke();
      g.textAlign="center";L.lines.forEach(function(l,k){g.font=l[2];g.fillStyle=l[1];g.fillText(l[0],bx+L.tw/2,by+19+k*17);});}
  });
  // collision animation
  (sim.fx||[]).forEach(function(f){
    var age=(now-f.t0)/f.dur;if(age<0||age>=1)return;
    var fx=X(f.x),fy=f.kind==="c"?yF-Math.min(sim.b[0].r,sim.b[1].r)*sc:yF-40,ease=1-Math.pow(1-age,3);
    g.save();
    if(f.kind==="c"){
      var glow=g.createRadialGradient(fx,fy,0,fx,fy,90*f.pow+40);glow.addColorStop(0,"rgba(255,244,200,"+(0.9*(1-age))+")");glow.addColorStop(0.4,"rgba(255,170,60,"+(0.45*(1-age))+")");glow.addColorStop(1,"rgba(255,120,40,0)");
      g.fillStyle=glow;g.beginPath();g.arc(fx,fy,(90*f.pow+40)*(0.4+0.6*ease),0,2*Math.PI);g.fill();
      [0,0.18].forEach(function(d){var a2=age-d;if(a2<=0)return;g.globalAlpha=Math.max(0,1-a2/(1-d));g.strokeStyle=d?"#7ef0e2":"#ffe58a";g.lineWidth=4*(1-a2)+1;g.shadowColor=g.strokeStyle;g.shadowBlur=16;g.beginPath();g.arc(fx,fy,10+(110*f.pow+30)*(1-Math.pow(1-a2,3)),0,2*Math.PI);g.stroke();});
      if(age<0.45){g.globalAlpha=1-age/0.45;g.strokeStyle="#fff";g.lineWidth=3;g.shadowBlur=14;g.shadowColor="#ffd166";for(var k=0;k<12;k++){var an=k*Math.PI/6+0.2,r1=14+60*ease*f.pow,r2=r1+10+22*f.pow*(1-age);g.beginPath();g.moveTo(fx+r1*Math.cos(an),fy+r1*Math.sin(an));g.lineTo(fx+r2*Math.cos(an),fy+r2*Math.sin(an));g.stroke();}}
      g.shadowBlur=0;g.globalAlpha=Math.max(0,1-age*1.1);g.font="900 "+(18+10*f.pow)+"px Segoe UI,Arial";g.textAlign="center";g.lineWidth=4;g.strokeStyle="#0b1430";var word=f.e<0.001?"STICK!":(f.e>0.999?"BOUNCE!":"IMPACT!");
      var ty=fy-70-40*ease;g.strokeText(word,fx,ty);g.fillStyle=f.e<0.001?"#ff8f7a":"#ffe58a";g.fillText(word,fx,ty);
    }
    var palette=f.kind==="c"?["#ffe58a","#ff9414","#7ef0e2","#ffffff"]:["#c9d6ff","#ffffff"];
    f.parts.forEach(function(p){var t=age*f.dur/1000,px=fx+Math.cos(p.a)*p.s*t,py=fy+Math.sin(p.a)*p.s*t+260*t*t;if(py>yF)py=yF-(py-yF)*0.4;
      g.globalAlpha=Math.max(0,1-age);g.fillStyle=palette[Math.floor(p.c*palette.length)];g.shadowColor=g.fillStyle;g.shadowBlur=8;g.beginPath();g.arc(px,py,p.z*(1-age*0.6),0,2*Math.PI);g.fill();});
    g.restore();
  });
  if($("oCM").checked){var a=sim.b[0],b2=sim.b[1],xc=(a.m*a.x+b2.m*b2.x)/(a.m+b2.m),px=X(xc),py=yF-14;g.strokeStyle="#fff";g.lineWidth=3;g.beginPath();g.moveTo(px-7,py-7);g.lineTo(px+7,py+7);g.moveTo(px+7,py-7);g.lineTo(px-7,py+7);g.stroke();g.font="11px Segoe UI,Arial";g.fillStyle="#fff";g.fillText("CM",px,py-12);}
}
function rr(g,x,y,w,h,r){g.beginPath();g.moveTo(x+r,y);g.arcTo(x+w,y,x+w,y+h,r);g.arcTo(x+w,y+h,x,y+h,r);g.arcTo(x,y+h,x,y,r);g.arcTo(x,y,x+w,y,r);g.closePath();}
function arrow(g,x,y,len,col){
  var s=len<0?-1:1,L=Math.max(14,Math.abs(len));g.save();g.shadowColor=col;g.shadowBlur=6;g.lineCap="round";
  g.strokeStyle=col;g.fillStyle=col;g.lineWidth=4;g.lineCap="butt";g.beginPath();g.moveTo(x,y);g.lineTo(x+s*(L-8),y);g.stroke();
  g.beginPath();g.moveTo(x+s*L,y);g.lineTo(x+s*(L-10),y-6);g.lineTo(x+s*(L-10),y+6);g.closePath();g.fill();g.restore();
}
$("bPlay").onclick=function(){
  if(sim.run){pause();return;}
  if(sim.t===0){sim.init=readInit();reset();}
  sim.run=true;lockInputs(true);this.textContent="❚❚ Pause";
};
$("bStep").onclick=function(){if(sim.t===0){reset();}lockInputs(true);pause();advance(0.02);draw();readout();};
$("bReset").onclick=function(){if(sim.init){$("x1").value=sim.init.x1;$("x2").value=sim.init.x2;$("v1").value=sim.init.v1;$("v2").value=sim.init.v2;}reset();};
["m1","m2","x1","x2","v1","v2"].forEach(function(id){$(id).addEventListener("change",applyVar);});
$("elas").oninput=function(){$("elasV").textContent=this.value+"%";applyVar();};
["oVel","oMom","oCM","oVal","oWall"].forEach(function(id){$(id).onchange=draw;});
window.addEventListener("resize",draw);
function unlink(){sim.loaded=null;$("loadedTag").textContent="";}
VARS.forEach(function(id){$(id+"r").addEventListener("input",function(){$(id).value=this.value;applyVar();});});
(function(){var cv=$("cv"),drag=null;
  function xAt(e){var r=cv.getBoundingClientRect();return (e.clientX-r.left-30)/((r.width-60)/(2*W))-W;}
  cv.addEventListener("pointerdown",function(e){if(sim.run)return;var x=xAt(e);drag=null;sim.b.forEach(function(b,i){if(Math.abs(x-b.x)<=b.r+0.06)drag=i;});if(drag!==null){cv.setPointerCapture(e.pointerId);cv.style.cursor="grabbing";}});
  cv.addEventListener("pointermove",function(e){if(drag===null)return;$(drag?"x2":"x1").value=xAt(e).toFixed(2);applyVar();cv.style.cursor="grabbing";});
  function end(){if(drag!==null){drag=null;cv.style.cursor="grab";}}
  cv.addEventListener("pointerup",end);cv.addEventListener("pointercancel",end);
})();

/* load / record between tables and simulator */
function rowSetup(t,i){
  if(t==="t1"){var m=num(S["t1.m"]),a=ROWS1[i][0]===null?num(S["t1."+i+".v1i"]):ROWS1[i][0],b=ROWS1[i][1]===null?num(S["t1."+i+".v2i"]):ROWS1[i][1];
    if(!isFinite(m))return "Enter the mass m₁ = m₂ above Table 1 first.";if(!isFinite(a)||!isFinite(b))return "Choose V₁ᵢ and V₂ᵢ for this row first.";return {m1:m,m2:m,v1:a,v2:b,e:100};}
  if(t==="t23"){var m1=num(S["t23.m1"]),m2=num(S["t23.m2"]);if(!isFinite(m1)||!isFinite(m2))return "Enter m₁ and m₂ above Table 2 first.";return {m1:m1,m2:m2,v1:ROWS23[i][0],v2:ROWS23[i][1],e:100};}
  return {m1:ROWS45[i][0],m2:ROWS45[i][1],v1:ROWS45[i][2],v2:ROWS45[i][3],e:0};
}
document.addEventListener("click",function(ev){
  var e=ev.target;
  if(e.dataset.load){
    var p=e.dataset.load.split("."),su=rowSetup(p[0],+p[1]);if(typeof su==="string"){toast(su);return;}
    $("m1").value=clampM(su.m1);$("m2").value=clampM(su.m2);$("x1").value=-1;$("x2").value=1;$("v1").value=su.v1;$("v2").value=su.v2;$("elas").value=su.e;$("elasV").textContent=su.e+"%";
    reset();sim.loaded=e.dataset.load;
    var names={t1:"Table 1",t23:"Tables 2 & 3",t45:"Tables 4 & 5"};$("loadedTag").textContent="· loaded: "+names[p[0]]+", row "+(+p[1]+1);
    show("sim");toast("Row loaded. Press Play.");
  }else if(e.dataset.rec){
    var q=e.dataset.rec.split(".");
    if(S.submitted){toast("The report has been submitted. Reopen it in the digital report to record again.");return;}
    if(sim.loaded!==e.dataset.rec){toast("Load this row into the simulator and run it first.");return;}
    if(!sim.col){toast("No collision yet. Press Play and wait for the balls to collide.");return;}
    if(q[0]==="t45"){S["t45."+q[1]+".vf"]=sim.col.v1a.toFixed(2);}
    else{S[q[0]+"."+q[1]+".v1f"]=sim.col.v1a.toFixed(2);S[q[0]+"."+q[1]+".v2f"]=sim.col.v2a.toFixed(2);}
    autoFill();paint();persist();
    toast(sim.col.wall?"Recorded. Note: the balls hit a wall before colliding.":"Final velocities recorded.");
  }else if(e.dataset.check){check(e.dataset.check);}
});

/* ---------------- navigation ---------------- */
function show(s){
  document.querySelectorAll(".sec").forEach(function(x){x.classList.toggle("on",x.id==="sec-"+s);});
  document.querySelectorAll("#nav button").forEach(function(b){b.classList.toggle("on",b.dataset.s===s);});
  var simSec=$("sec-sim"),card=$("simCard");
  // keep the simulator visible above each experiment part
  if(["p1a","p1b","p2"].indexOf(s)>=0){$("sec-"+s).insertBefore(card,$("sec-"+s).firstChild);}else{simSec.insertBefore(card,simSec.firstChild);}
  if(s==="report")buildReport();
  window.scrollTo(0,0);setTimeout(draw,30);
}
$("nav").addEventListener("click",function(ev){if(ev.target.dataset.s)show(ev.target.dataset.s);});

/* ---------------- logo, save, load ---------------- */
function showLogo(){var b=$("logoBox");if(S.logo){b.innerHTML='<img alt="Institution logo" src="'+S.logo+'">';b.style.borderStyle="solid";}else{b.innerHTML='<span>Click to add the official<br>university logo (PNG, JPG, SVG)</span>';b.style.borderStyle="dashed";}}
$("logoBox").onclick=function(){$("logoFile").click();};
$("logoFile").onchange=function(){var f=this.files[0];if(!f)return;var r=new FileReader();r.onload=function(){S.logo=r.result;showLogo();persist();toast("Logo added. It will appear on the report.");};r.readAsDataURL(f);};
function download(name,text,type){var a=document.createElement("a");a.href=URL.createObjectURL(new Blob([text],{type:type}));a.download=name;document.body.appendChild(a);a.click();setTimeout(function(){URL.revokeObjectURL(a.href);a.remove();},500);}
$("saveJson").onclick=function(){download("PHYS111_Lab9_progress.json",JSON.stringify(S),"application/json");};
$("loadJsonBtn").onclick=function(){$("loadJson").click();};
$("loadJson").onchange=function(){var f=this.files[0];if(!f)return;var r=new FileReader();r.onload=function(){try{S=JSON.parse(r.result)||{};if(!S.logo)S.logo=DEFAULT_LOGO;paint();showLogo();applyTheme();persist();toast("Saved progress opened.");}catch(e){toast("That file could not be read.");}};r.readAsText(f);};
var clearArmed=false;
$("clearAll").onclick=function(){
  if(!clearArmed){clearArmed=true;this.textContent="Press again to confirm clearing";var b=this;setTimeout(function(){clearArmed=false;b.textContent="Clear all entries";},4000);return;}
  var keep={inst:S.inst,course:S.course,logo:S.logo,mode:S.mode,theme:S.theme,attempts:S.attempts};S=keep;$("reportLive").innerHTML="";document.querySelectorAll(".good,.wrong").forEach(function(e){e.classList.remove("good","wrong");});paint();persist();clearArmed=false;this.textContent="Clear all entries";toast("All entries cleared.");
};

/* ---------------- report ---------------- */
function v(k){return esc(S[k]===undefined?"":S[k]);}
function ans(k){var t=S[k];return qstat(k)+'<div class="ans">'+(t?esc(t).replace(/\n/g,"<br>"):'<span class="blank">No answer entered</span>')+'</div>';}
function u(k,d){return S[k]?esc(S[k]):"unit: ____";}
function reportHTML(){
  var css='body{font:12.5pt/1.45 "Times New Roman",Times,serif;color:#111;margin:0}.rp{max-width:800px;margin:0 auto;padding:10px}'+
  '.hd{text-align:center;border-bottom:2px solid #a51c30;padding-bottom:10px;margin-bottom:14px}.hd img{max-height:80px;max-width:420px}.hd h1{font-size:15pt;margin:6px 0 2px}.hd h2{font-size:13pt;margin:2px 0;font-weight:bold}.hd h3{font-size:13pt;margin:6px 0 0}'+
  'table{border-collapse:collapse;border-radius:0;border:0;width:100%;margin:6px 0 12px}th,td{border:1px solid #333!important;padding:4px 6px;text-align:center;font-size:11pt;height:26px;color:#111}th{background:#eee}td.fix{background:#e3e9f2;font-weight:bold}td.l{text-align:left}'+
  'h4{font-size:13pt;margin:16px 0 4px;text-decoration:underline}p{margin:6px 0}.ans{border:1px solid #999;border-radius:4px;padding:6px 8px;min-height:38px;margin:2px 0 10px;white-space:normal}.blank{color:#999;font-style:italic}.meta{display:flex;justify-content:space-between;margin:8px 0}.ft{margin-top:18px;font-size:9.5pt;color:#555;border-top:1px solid #bbb;padding-top:6px}.pb{page-break-before:always}.charts{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin:8px 0;page-break-inside:avoid}.charts>div{border:1px solid #bbb;border-radius:6px;padding:4px}svg.ch{width:100%;height:auto;display:block;color:#111}.chip{font-size:10pt}.chip.ok{color:#15803d}.chip.no{color:#b91c1c}';
  var h='<div class="rp"><div class="hd">'+(S.logo?'<img alt="logo" src="'+S.logo+'"><br>':'')+'<h1>'+v("inst")+'</h1><h2>'+v("course")+'</h2><h3>Lab 9: Conservation of Momentum</h3></div>';
  h+='<div class="meta"><span><b>Date:</b> '+v("date")+'</span><span><b>Sec:</b> '+v("sec")+'</span></div>';
  h+='<table><tr><th style="width:8%"></th><th>Name</th><th style="width:30%">ID</th></tr><tr><td>1</td><td class="l">'+v("n1")+'</td><td>'+v("id1")+'</td></tr><tr><td>2</td><td class="l">'+v("n2")+'</td><td>'+v("id2")+'</td></tr></table>';
  h+=gradeStatic();
  // Part 1A
  h+='<h4>Part 1A. Elastic collision (m₁ = m₂)</h4><p><b>Table 1</b> (6 marks) &nbsp; m₁ = m₂ = '+(v("t1.m")||"____")+' kg</p><table><tr><th>V₁ᵢ (m/s)</th><th>V₂ᵢ (m/s)</th><th>V₁f (m/s)</th><th>V₂f (m/s)</th><th>Pᵢ (kg·m/s)</th><th>P_f (kg·m/s)</th><th>Kᵢ (J)</th><th>K_f (J)</th></tr>';
  ROWS1.forEach(function(r,i){var a=r[0]===null?v("t1."+i+".v1i"):r[0].toFixed(2),b=r[1]===null?v("t1."+i+".v2i"):r[1].toFixed(2);
    h+='<tr><td class="fix">'+a+'</td><td class="fix">'+b+'</td><td>'+v("t1."+i+".v1f")+'</td><td>'+v("t1."+i+".v2f")+'</td><td>'+v("t1."+i+".pi")+'</td><td>'+v("t1."+i+".pf")+'</td><td>'+v("t1."+i+".ki")+'</td><td>'+v("t1."+i+".kf")+'</td></tr>';});
  h+='</table><p>1) Is the momentum conserved? Explain. (2 marks)</p>'+ans("q1a1")+'<p>2) Is the K.E. conserved? Explain. (2 marks)</p>'+ans("q1a2")+dynHTML(PARTS[0],true);
  // Part 1B
  h+='<h4>Part 1B. Elastic collision (m₁ ≠ m₂)</h4><p><b>Table 2</b> (6 marks) &nbsp; m₁ = '+(v("t23.m1")||"____")+' kg &nbsp; m₂ = '+(v("t23.m2")||"____")+' kg</p><table><tr><th>V₁ᵢ (m/s)</th><th>V₂ᵢ (m/s)</th><th>V₁f ('+u("u.t2.v1f")+')</th><th>V₂f ('+u("u.t2.v2f")+')</th><th>Pᵢ = m₁v₁ᵢ + m₂v₂ᵢ (kg·m/s)</th><th>P_f = m₁v₁f + m₂v₂f ('+u("u.t2.pf")+')</th><th>P_f = Pᵢ (Y/N)</th></tr>';
  ROWS23.forEach(function(r,i){h+='<tr><td class="fix">'+r[0].toFixed(2)+'</td><td class="fix">'+r[1].toFixed(2)+'</td><td>'+v("t23."+i+".v1f")+'</td><td>'+v("t23."+i+".v2f")+'</td><td>'+v("t23."+i+".pi")+'</td><td>'+v("t23."+i+".pf")+'</td><td>'+v("t23."+i+".pyn")+'</td></tr>';});
  h+='</table><p><b>Table 3</b> (6 marks)</p><table><tr><th>V₁ᵢ (m/s)</th><th>V₂ᵢ (m/s)</th><th>V₁f ('+u("u.t3.v1f")+')</th><th>V₂f ('+u("u.t3.v2f")+')</th><th>KEᵢ (J)</th><th>KE_f ('+u("u.t3.kf")+')</th><th>K_f = Kᵢ (Y/N)</th></tr>';
  ROWS23.forEach(function(r,i){h+='<tr><td class="fix">'+r[0].toFixed(2)+'</td><td class="fix">'+r[1].toFixed(2)+'</td><td>'+v("t23."+i+".v1f")+'</td><td>'+v("t23."+i+".v2f")+'</td><td>'+v("t23."+i+".ki")+'</td><td>'+v("t23."+i+".kf")+'</td><td>'+v("t23."+i+".kyn")+'</td></tr>';});
  h+='</table><p>1) Is the momentum conserved? Explain. (2 marks)</p>'+ans("q1b1")+'<p>2) Is the K.E. conserved? Explain. (2 marks)</p>'+ans("q1b2")+dynHTML(PARTS[1],true);
  // Part 2
  h+='<h4 class="pb">Part 2. Inelastic collision</h4><p><b>Table 4</b> (6 marks)</p><table><tr><th>m₁ (kg)</th><th>m₂ (kg)</th><th>V₁ᵢ (m/s)</th><th>V₂ᵢ (m/s)</th><th>V_f ('+u("u.t4.vf")+')</th><th>Pᵢ = m₁v₁ᵢ + m₂v₂ᵢ (kg·m/s)</th><th>P_f = (m₁ + m₂)v_f ('+u("u.t4.pf")+')</th><th>Pᵢ = P_f (Y/N)</th></tr>';
  ROWS45.forEach(function(r,i){h+='<tr><td class="fix">'+r[0]+'</td><td class="fix">'+r[1]+'</td><td class="fix">'+r[2].toFixed(2)+'</td><td class="fix">'+r[3].toFixed(2)+'</td><td>'+v("t45."+i+".vf")+'</td><td>'+v("t45."+i+".pi")+'</td><td>'+v("t45."+i+".pf")+'</td><td>'+v("t45."+i+".pyn")+'</td></tr>';});
  h+='</table><p>1. Is the momentum conserved? Explain. (2 marks)</p>'+ans("q2a1");
  h+='<p><b>Table 5</b> (6 marks)</p><table><tr><th>m₁ (kg)</th><th>m₂ (kg)</th><th>V₁ᵢ (m/s)</th><th>V₂ᵢ (m/s)</th><th>V_f ('+u("u.t5.vf")+')</th><th>Kᵢ (J)</th><th>K_f = 0.5(m₁ + m₂)v_f² ('+u("u.t5.kf")+')</th><th>K_f = Kᵢ (Y/N)</th></tr>';
  ROWS45.forEach(function(r,i){h+='<tr><td class="fix">'+r[0]+'</td><td class="fix">'+r[1]+'</td><td class="fix">'+r[2].toFixed(2)+'</td><td class="fix">'+r[3].toFixed(2)+'</td><td>'+v("t45."+i+".vf")+'</td><td>'+v("t45."+i+".ki")+'</td><td>'+v("t45."+i+".kf")+'</td><td>'+v("t45."+i+".kyn")+'</td></tr>';});
  h+='</table><p>1. Is the energy conserved? Explain. (2 marks)</p>'+ans("q2b1")+'<p>2. Is there a pattern for the change of energy? (2 marks)</p>'+ans("q2b2")+'<p>3. Calculate the fractional change of the kinetic energy and the percent loss of energy. Explain where this energy is lost. (2 marks)</p>'+ans("q2b3")+dynHTML(PARTS[2],true);
  
  h+='<h4 class="pb">Lab assignment</h4>'+window.ASSIGN.map(function(q,i){return '<p>'+(i+1)+'. '+esc(q)+'</p>'+ans("a"+(i+1));}).join("");
  if(S.fb)h+='<h4>Instructor feedback</h4>'+ans("fb");
  h+='<div class="ft">© 2026 American University of Ras Al Khaimah (AURAK). All rights reserved.<br>Report generated on '+new Date().toLocaleString()+' from the PHYS111 Lab 9 collision simulator. Final velocities were '+(S.mode==="auto"?"recorded from the simulator and the calculated columns were filled automatically.":"recorded from the simulator or entered by the student; calculated columns were entered by the student.")+'</div></div>';
  return {css:css,body:h};
}
function buildReport(){
  var r=reportHTML();
  $("reportView").innerHTML='<style>@media print{#reportView '+r.css.replace(/\}(?=[^}]*\{)/g,"}#reportView ").replace("#reportView body{","#reportView .rp{")+'}</style>'+r.body;
  buildLive();
}
function downloadReport(){var r=reportHTML();var name=(S.n1||"student").replace(/[^A-Za-z0-9]+/g,"_");
  download("PHYS111_Lab9_Report_"+name+".html",'<!DOCTYPE html><html lang="en"><head><meta charset="utf-8"><title>PHYS111 Lab 9 Report</title><style>'+r.css+'</style></head><body>'+r.body+'</body></html>',"text/html");}



/* ---------------- interactive report ---------------- */
var PARTS=[
 {id:"p1a",t:"t1",n:5,title:"Part 1A · Elastic collision, m₁ = m₂",tabs:[["T1","Table 1 (6 marks)"]],head:'m₁ = m₂ = <input type="number" step="0.1" data-k="t1.m" style="width:90px"> kg',qs:[["q1a1","1) Is the momentum conserved? Explain. (2 marks)"],["q1a2","2) Is the K.E. conserved? Explain. (2 marks)"]]},
 {id:"p1b",t:"t23",n:3,title:"Part 1B · Elastic collision, m₁ ≠ m₂",tabs:[["T2","Table 2 (6 marks)"],["T3","Table 3 (6 marks)"]],head:'m₁ = <input type="number" step="0.1" data-k="t23.m1" style="width:90px"> kg &nbsp; m₂ = <input type="number" step="0.1" data-k="t23.m2" style="width:90px"> kg',qs:[["q1b1","1) Is the momentum conserved? Explain. (2 marks)"],["q1b2","2) Is the K.E. conserved? Explain. (2 marks)"]]},
 {id:"p2",t:"t45",n:3,title:"Part 2 · Inelastic collision",tabs:[["T4","Table 4 (6 marks)"],["T5","Table 5 (6 marks)"]],head:"",qs:[["q2a1","Table 4 · 1. Is the momentum conserved? Explain. (2 marks)"],["q2b1","Table 5 · 1. Is the energy conserved? Explain. (2 marks)"],["q2b2","2. Is there a pattern for the change of energy? (2 marks)"],["q2b3","3. Calculate the fractional change of the kinetic energy and the percent loss of energy. Explain where this energy is lost. (2 marks)"]]}];
var SECNAME={info:"Student details",p1a:"Part 1A",p1b:"Part 1B",p2:"Part 2",concl:"Lab assignment"};
function secDone(s){var d=NEED[s].filter(function(k){return S[k]!==undefined&&String(S[k]).trim()!=="";}).length;return [d,NEED[s].length];}
function val(t,i,q){var x=num(S[t+"."+i+"."+q]);return isFinite(x)?x:rowVals(t,i)[q];}
function trials(p){var out=[];for(var i=0;i<p.n;i++){var r={n:i+1,pi:val(p.t,i,"pi"),pf:val(p.t,i,"pf"),ki:val(p.t,i,"ki"),kf:val(p.t,i,"kf")};if(isFinite(r.pi)&&isFinite(r.pf)&&isFinite(r.ki)&&isFinite(r.kf))out.push(r);}return out;}
function chartSVG(title,rows,ka,kb){
  var Wd=520,H=236,L=44,R=12,T=40,B=34,vals=[0];rows.forEach(function(r){vals.push(r[ka],r[kb]);});
  var mx=Math.max.apply(null,vals),mn=Math.min.apply(null,vals);if(mx-mn<1e-9){mx=1;}var pad=(mx-mn)*0.14;mx+=mx>0?pad:0;mn-=mn<0?pad:0;
  var Y=function(v){return T+(mx-v)/(mx-mn)*(H-T-B);},gw=(Wd-L-R)/rows.length,bw=Math.min(44,gw*0.3),o='<svg class="ch" viewBox="0 0 '+Wd+' '+H+'" xmlns="http://www.w3.org/2000/svg" font-family="Segoe UI,Arial,sans-serif" role="img" aria-label="'+esc(title)+'">';
  o+='<text x="'+L+'" y="18" font-size="13.5" font-weight="700" fill="currentColor">'+esc(title)+'</text>';
  o+='<rect x="'+(Wd-190)+'" y="8" width="11" height="11" rx="3" fill="#4f6df5"/><text x="'+(Wd-174)+'" y="18" font-size="11.5" fill="currentColor">Before</text><rect x="'+(Wd-112)+'" y="8" width="11" height="11" rx="3" fill="#ff9414"/><text x="'+(Wd-96)+'" y="18" font-size="11.5" fill="currentColor">After</text>';
  for(var k=0;k<=4;k++){var tv=mn+(mx-mn)*k/4,ty=Y(tv);o+='<line x1="'+L+'" x2="'+(Wd-R)+'" y1="'+ty+'" y2="'+ty+'" stroke="currentColor" stroke-opacity=".13"/><text x="'+(L-6)+'" y="'+(ty+4)+'" font-size="10.5" text-anchor="end" fill="currentColor" fill-opacity=".7">'+tv.toFixed(Math.abs(mx-mn)<4?1:0)+'</text>';}
  o+='<line x1="'+L+'" x2="'+(Wd-R)+'" y1="'+Y(0)+'" y2="'+Y(0)+'" stroke="currentColor" stroke-opacity=".55"/>';
  rows.forEach(function(r,i){var cx=L+gw*(i+0.5);o+='<g class="grp">';
    [[r[ka],cx-bw-2,"#4f6df5","before"],[r[kb],cx+2,"#ff9414","after"]].forEach(function(b){var y0=Y(0),y1=Y(b[0]),top=Math.min(y0,y1),hh=Math.max(1.5,Math.abs(y1-y0));
      o+='<rect class="bar" x="'+b[1]+'" y="'+top+'" width="'+bw+'" height="'+hh+'" rx="4" fill="'+b[2]+'"><title>Trial '+r.n+' '+b[3]+': '+b[0].toFixed(2)+'</title></rect><text x="'+(b[1]+bw/2)+'" y="'+(b[0]>=0?top-4:top+hh+12)+'" font-size="10.5" font-weight="600" text-anchor="middle" fill="currentColor">'+b[0].toFixed(2)+'</text>';});
    o+='<text x="'+cx+'" y="'+(H-10)+'" font-size="11.5" text-anchor="middle" fill="currentColor">Trial '+r.n+'</text></g>';});
  return o+'</svg>';
}
function analysisRows(p){return trials(p).map(function(r){var pc=same(r.pi,r.pf),kc=same(r.ki,r.kf),loss=r.ki>1e-9?100*(r.ki-r.kf)/r.ki:0;return {n:r.n,dp:r.pf-r.pi,loss:loss,pc:pc,kc:kc};});}
function dynHTML(p,stat){
  var rows=trials(p);if(!rows.length)return stat?"":'<p class="note">Charts and analysis appear here as soon as a trial has its final velocities recorded.</p>';
  var h='<div class="charts"><div>'+chartSVG("Total momentum (kg·m/s)",rows,"pi","pf")+'</div><div>'+chartSVG("Total kinetic energy (J)",rows,"ki","kf")+'</div></div>';
  if(S.ra!=="off"){h+='<table style="margin-top:12px"><tr><th>Trial</th><th>ΔP = P_f − Pᵢ (kg·m/s)</th><th>Momentum</th><th>K.E. change (%)</th><th>Kinetic energy</th></tr>';
    analysisRows(p).forEach(function(a){h+='<tr><td class="fix">'+a.n+'</td><td>'+a.dp.toFixed(2)+'</td><td><span class="chip '+(a.pc?"ok":"no")+'">'+(a.pc?"Conserved":"Not equal: wall hit before impact?")+'</span></td><td>'+(-a.loss).toFixed(1)+'</td><td><span class="chip '+(a.kc?"ok":"no")+'">'+(a.kc?"Conserved":a.loss.toFixed(0)+"% lost")+'</span></td></tr>';});
    h+='</table>';}
  return h;
}
function ta(k,ph){return qctl(k)+'<textarea data-k="'+k+'" placeholder="'+(ph||"Type your answer")+'"></textarea><div class="wc" data-wc="'+k+'"></div>';}
function buildLive(){
  var h='<div class="card"><div class="rtop"><div class="ring" id="rRing"><span id="rPct">0%</span></div><div style="flex:1;min-width:260px"><h2 style="margin-bottom:4px">Interactive digital report</h2><div class="note">Everything here is live: edit any field, table cell or answer and the charts, analysis and progress update instantly. Changes are shared with the lab tabs.</div><div class="chips" id="rChips"></div></div>'+
   '<div style="display:flex;flex-direction:column;gap:8px"><button class="btn pri" id="rPrint">Print / save as PDF</button><button class="btn" id="rDown">Download report (.html)</button><button class="btn" id="rCsv">Download data (.csv)</button><button class="btn" id="rAuto"></button></div></div></div>';
  h+='<details class="rp" open data-sec="info"><summary>Cover page<span class="pct"></span></summary><div class="in"><div class="cover"><div>'+(S.logo?'<img alt="Institution logo" src="'+S.logo+'">':'')+'<div style="font-weight:800;font-size:17px;margin-top:8px">'+v("course")+' · Lab 9: Conservation of Momentum</div><div class="rights">© 2026 American University of Ras Al Khaimah (AURAK). All rights reserved.</div>'+
   '<div class="grid g2" style="margin-top:12px"><label class="f">Date<input type="date" data-k="date"></label><label class="f">Section<input type="text" data-k="sec"></label><label class="f">Student 1 name<input type="text" data-k="n1"></label><label class="f">Student 1 ID<input type="text" data-k="id1"></label><label class="f">Student 2 name<input type="text" data-k="n2"></label><label class="f">Student 2 ID<input type="text" data-k="id2"></label></div></div>'+
   '<div id="gradeTable"></div></div></div></details>';
  h+='<div class="card" id="gradeBox"></div>';
  PARTS.forEach(function(p){
    h+='<details class="rp" open data-sec="'+p.id+'"><summary>'+p.title+'<span class="pct"></span></summary><div class="in">';
    p.tabs.forEach(function(t,j){h+='<div class="tbar"><b>'+t[1]+'</b>'+(j===0&&p.head?' &nbsp; '+p.head:'')+'</div><div class="tw">'+$(t[0]).querySelector("table").outerHTML+'</div>';});
    h+='<h3>Charts and automatic analysis</h3><div id="dyn-'+p.id+'"></div>';
    p.qs.forEach(function(q){h+='<div class="q"><p>'+q[1]+'</p>'+ta(q[0])+'</div>';});
    h+='</div></details>';});
  h+='<details class="rp" open data-sec="concl"><summary>Lab assignment<span class="pct"></span></summary><div class="in">'+
    window.ASSIGN.map(function(q,i){return '<div class="q"><p>'+(i+1)+'. '+esc(q)+'</p>'+ta("a"+(i+1),"Show your working and final answer")+'</div>';}).join("")+'</div></details>';
  h+='<details class="rp" open><summary>Instructor feedback</summary><div class="in"><textarea data-k="fb" placeholder="Comments from the instructor"></textarea></div></details>';
  $("reportLive").innerHTML=h;paint();refreshLive();
}
function refreshLive(){
  if(!$("rRing"))return;
  var done=0,tot=0,chips="";
  Object.keys(NEED).forEach(function(s){var d=secDone(s);done+=d[0];tot+=d[1];
    chips+=d[0]===d[1]?'<span class="chip done">✓ '+SECNAME[s]+'</span>':'<button class="chip todo" data-go="'+s+'" title="Open this part">'+SECNAME[s]+': '+(d[1]-d[0])+' left</button>';
    var el=document.querySelector('details.rp[data-sec="'+s+'"] .pct');if(el){el.textContent=d[0]+" / "+d[1];el.classList.toggle("full",d[0]===d[1]);}});
  var pc=Math.round(100*done/tot);$("rRing").style.setProperty("--p",pc);$("rPct").textContent=pc+"%";$("rChips").innerHTML=chips;
  $("rAuto").textContent=S.ra==="off"?"Show automatic analysis":"Hide automatic analysis";
  PARTS.forEach(function(p){$("dyn-"+p.id).innerHTML=dynHTML(p);});
  renderGrade();
  document.querySelectorAll("[data-wc]").forEach(function(e){var t=(S[e.dataset.wc]||"").trim();e.textContent=t?t.split(/\s+/).length+" words":"";});
}
function csvData(){
  var L=[["Lab 9: Conservation of Momentum"],["Date",S.date||"","Section",S.sec||""],["Student 1",S.n1||"",S.id1||"","Student 2",S.n2||"",S.id2||""],[],["Part","Trial","m1 (kg)","m2 (kg)","v1i (m/s)","v2i (m/s)","v1f (m/s)","v2f (m/s)","Pi (kg m/s)","Pf (kg m/s)","Ki (J)","Kf (J)"]];
  PARTS.forEach(function(p){for(var i=0;i<p.n;i++){var e=rowVals(p.t,i),g=function(q){return S[p.t+"."+i+"."+q]||"";};if(!isFinite(e.v1i))continue;
    L.push([p.id,i+1,isFinite(e.m1)?e.m1:"",isFinite(e.m2)?e.m2:"",e.v1i,e.v2i,isFinite(e.v1f)?e.v1f:"",isFinite(e.v2f)?e.v2f:"",g("pi"),g("pf"),g("ki"),g("kf")]);}});
  return L.map(function(r){return r.map(function(c){c=String(c);return /[",\n]/.test(c)?'"'+c.replace(/"/g,'""')+'"':c;}).join(",");}).join("\r\n");
}
document.addEventListener("click",function(ev){
  var e=ev.target;
  if(e.dataset&&e.dataset.go){if(PAGE==="report"){var d=document.querySelector('details.rp[data-sec="'+e.dataset.go+'"]');if(d){d.open=true;d.scrollIntoView({behavior:"smooth"});}}else show(e.dataset.go);}
  else if(e.id==="rPrint"){buildReport();window.print();}
  else if(e.id==="rDown"){downloadReport();}
  else if(e.id==="rCsv"){download("PHYS111_Lab9_data.csv","﻿"+csvData(),"text/csv");}
  else if(e.id==="rAuto"){S.ra=S.ra==="off"?"on":"off";persist();refreshLive();}
});



/* ---------------- automatic grading (out of 40) ---------------- */
var QC={q1a1:["y1a1","Momentum conserved?","Y"],q1a2:["y1a2","Kinetic energy conserved?","Y"],q1b1:["y1b1","Momentum conserved?","Y"],q1b2:["y1b2","Kinetic energy conserved?","Y"],q2a1:["y2a1","Momentum conserved?","Y"],q2b1:["y2b1","Kinetic energy conserved?","N"],q2b2:["y2b2","Is there a pattern?","Y"]};
var AN={a1:[["an1","Speed of the ball (m/s)",76.39]],a2:[["an2a","Velocity of second car (m/s)",29.09],["an2b","Final kinetic energy (J)",542727]],a3:[["an3a","Final velocity (m/s)",2.118],["an3b","Energy lost (J)",345.9]],a4:[["an4","Speed of right cart (cm/s)",28.82]],a5:[["an5","Final velocity of bicycle (m/s)",23.43]]};
var GT=[{name:"Table 1",t:"t1",n:5,cells:["v1f","v2f","pi","pf","ki","kf"],units:[]},
 {name:"Table 2",t:"t23",n:3,cells:["v1f","v2f","pi","pf","pyn"],units:[["u.t2.v1f","m/s"],["u.t2.v2f","m/s"],["u.t2.pf","kgm/s"]]},
 {name:"Table 3",t:"t23",n:3,cells:["ki","kf","kyn"],units:[["u.t3.v1f","m/s"],["u.t3.v2f","m/s"],["u.t3.kf","j"]]},
 {name:"Table 4",t:"t45",n:3,cells:["vf","pi","pf","pyn"],units:[["u.t4.vf","m/s"],["u.t4.pf","kgm/s"]]},
 {name:"Table 5",t:"t45",n:3,cells:["ki","kf","kyn"],units:[["u.t5.vf","m/s"],["u.t5.kf","j"]]}];
var LBL={v1f:"V₁f",v2f:"V₂f",vf:"V_f",pi:"Pᵢ",pf:"P_f",ki:"Kᵢ",kf:"K_f",pyn:"P_f = Pᵢ (Y/N)",kyn:"K_f = Kᵢ (Y/N)"};
function qctl(k){
  if(QC[k])return '<div class="qc"><b>'+QC[k][1]+'</b><select data-k="'+QC[k][0]+'" aria-label="'+QC[k][1]+'"><option value=""></option><option value="Y">Yes</option><option value="N">No</option></select><span class="note">Then explain your choice (at least 5 words).</span></div>';
  if(k==="q2b3")return '<div class="qc"><b>Percent K.E. loss:</b> Trial 1 <input type="number" step="0.1" data-k="l1"> % &nbsp; Trial 2 <input type="number" step="0.1" data-k="l2"> % &nbsp; Trial 3 <input type="number" step="0.1" data-k="l3"> %</div>';
  if(AN[k])return '<div class="qc">'+AN[k].map(function(a){return '<b>'+a[1]+'</b><input type="number" step="any" data-k="'+a[0]+'">';}).join(" &nbsp; ")+'</div>';
  return "";
}
function qstat(k){
  if(QC[k])return '<p><b>'+QC[k][1]+'</b> '+({Y:"Yes",N:"No"}[S[QC[k][0]]]||"—")+'</p>';
  if(k==="q2b3")return '<p><b>Percent K.E. loss:</b> Trial 1: '+v("l1")+' %, Trial 2: '+v("l2")+' %, Trial 3: '+v("l3")+' %</p>';
  if(AN[k])return '<p>'+AN[k].map(function(a){return '<b>'+a[1]+':</b> '+(v(a[0])||"—");}).join(" &nbsp; ")+'</p>';
  return "";
}
/* outcome of the first ball-ball collision for the student's own initial conditions (start positions -1 m and 1 m, reflecting border) */
function expected(m1,m2,v1,v2,e){
  var a={x:-1,v:v1,r:rad(m1)},b={x:1,v:v2,r:rad(m2)},n=0;
  while(n++<60){
    var gap=(b.x-b.r)-(a.x+a.r),cl=a.v-b.v,tc=cl>1e-12?Math.max(0,gap)/cl:Infinity,tl=a.v<0?(a.x-a.r+W)/(-a.v):Infinity,tr=b.v>0?(W-b.r-b.x)/b.v:Infinity,t=Math.min(tc,tl,tr);
    if(!isFinite(t))return null;a.x+=a.v*t;b.x+=b.v*t;
    if(t===tc){var p=m1*a.v+m2*b.v,M=m1+m2;return {v1:(p-m2*e*(a.v-b.v))/M,v2:(p+m1*e*(a.v-b.v))/M};}
    if(t===tl)a.v=-a.v;else b.v=-b.v;
  }
  return null;
}
function expRow(t,i){
  var m1,m2,v1,v2,e=1;
  if(t==="t1"){m1=m2=num(S["t1.m"]);v1=ROWS1[i][0]===null?num(S["t1."+i+".v1i"]):ROWS1[i][0];v2=ROWS1[i][1]===null?num(S["t1."+i+".v2i"]):ROWS1[i][1];}
  else if(t==="t23"){m1=num(S["t23.m1"]);m2=num(S["t23.m2"]);v1=ROWS23[i][0];v2=ROWS23[i][1];}
  else{m1=ROWS45[i][0];m2=ROWS45[i][1];v1=ROWS45[i][2];v2=ROWS45[i][3];e=0;}
  if(![m1,m2,v1,v2].every(isFinite))return null;m1=clampM(m1);m2=clampM(m2);
  var f=expected(m1,m2,v1,v2,e);if(!f)return null;
  var o={v1f:f.v1,v2f:f.v2,vf:f.v1,pi:m1*v1+m2*v2,pf:m1*f.v1+m2*f.v2,ki:0.5*m1*v1*v1+0.5*m2*v2*v2,kf:0.5*m1*f.v1*f.v1+0.5*m2*f.v2*f.v2};
  o.pyn=same(o.pi,o.pf)?"Y":"N";o.kyn=same(o.ki,o.kf)?"Y":"N";return o;
}
function normU(u){u=String(u||"").toLowerCase().replace(/[\s·.*⋅]/g,"");return u==="joule"||u==="joules"?"j":u;}
function grade(){
  var R={tables:[],marks:{},fb:[],data:0};
  GT.forEach(function(T){var ok=0,tot=0;
    T.units.forEach(function(u){tot++;var g=normU(S[u[0]])===u[1];if(g)ok++;R.marks[u[0]]=g;if(!g)R.fb.push(T.name+": unit of a column should be "+(u[1]==="kgm/s"?"kg·m/s":u[1]==="j"?"J":u[1])+".");});
    for(var i=0;i<T.n;i++){var ex=expRow(T.t,i);T.cells.forEach(function(c){tot++;var k=T.t+"."+i+"."+c,yn=/yn$/.test(c),g=!!ex&&(yn?S[k]===ex[c]:close(num(S[k]),ex[c]));if(g)ok++;
      if(R.marks[k]!==false)R.marks[k]=g;
      if(!g)R.fb.push(T.name+", trial "+(i+1)+": "+LBL[c]+(ex?" should be "+(yn?ex[c]:ex[c].toFixed(2))+" for your initial conditions.":" cannot be graded (mass or initial velocities missing, or the balls never collide)."));});}
    var sc=Math.round(6*ok/tot*100)/100;R.tables.push({name:T.name,ok:ok,tot:tot,score:sc});R.data+=sc;});
  var an=0;
  Object.keys(QC).forEach(function(q){var c=QC[q],right=S[c[0]]===c[2],words=(S[q]||"").trim().split(/\s+/).filter(Boolean).length,pts=right?(words>=5?1:0.5):0;an+=pts;R.marks[c[0]]=right;
    if(!right)R.fb.push(c[1]+" The correct choice is "+(c[2]==="Y"?"Yes":"No")+".");else if(pts<1)R.fb.push(c[1]+" Correct choice, but the explanation is missing or too short (half mark).");});
  for(var i=0;i<3;i++){var ex=expRow("t45",i),want=ex&&ex.ki>1e-9?100*(ex.ki-ex.kf)/ex.ki:NaN,g=isFinite(want)&&Math.abs(num(S["l"+(i+1)])-want)<=1;if(g)an++;R.marks["l"+(i+1)]=g;if(!g)R.fb.push("Percent K.E. loss, trial "+(i+1)+": should be "+want.toFixed(1)+" %.");}
  R.analysis=an;R.aok=0;R.atot=0;
  Object.keys(AN).forEach(function(k){AN[k].forEach(function(a){R.atot++;var x=Math.abs(num(S[a[0]])),g=isFinite(x)&&Math.abs(x-a[2])<=0.02*a[2];if(g)R.aok++;R.marks[a[0]]=g;if(!g)R.fb.push("Assignment: "+a[1]+" is not correct.");});});
  var m1=num(S["t23.m1"]),m2=num(S["t23.m2"]);if(isFinite(m1)&&isFinite(m2)&&!(m1>=2&&m1<=3&&m2>=0.5&&m2<=2&&m2<m1))R.fb.push("Part 1B: the masses should satisfy m₁ = 2–3 kg, m₂ = 0.5–2 kg and m₂ < m₁ (noted, no marks deducted).");
  R.data=Math.round(R.data*10)/10;R.total=Math.round((R.data+R.analysis)*10)/10;return R;
}
function gradeRows(g){return '<tr><td class="l">Expt/Data collection (Tables 1–5)</td><td>30</td><td>'+(g?g.data.toFixed(1):"")+'</td></tr><tr><td class="l">Analysis/Calculations (questions)</td><td>10</td><td>'+(g?g.analysis.toFixed(1):"")+'</td></tr><tr><td class="l">Laboratory assignment (checked, not counted)</td><td></td><td>'+(g?g.aok+" of "+g.atot+" correct":"")+'</td></tr><tr><th>Total</th><th>40</th><th>'+(g?g.total.toFixed(1):"")+'</th></tr>';}
function gradeStatic(){
  var g=S.submitted?grade():null,h='<p><b>Breakdown of marks for the lab</b></p><table><tr><th>Objective of evaluation</th><th>Max. marks</th><th>Marks obtained</th></tr>'+gradeRows(g)+'</table>';
  if(g)h+='<p>Graded automatically on '+esc(new Date(S.submitted).toLocaleString())+' (attempt '+(S.attempts||1)+'), using the student\'s own masses and initial velocities. '+g.tables.map(function(t){return t.name+": "+t.score.toFixed(2)+"/6";}).join(" · ")+'</p>';
  else h+='<p><i>Not yet submitted for grading.</i></p>';
  return h;
}
var subArmed=false;
function renderGrade(){
  var box=$("gradeBox"),tb=$("gradeTable");if(!box)return;
  if(!S.submitted){
    document.querySelectorAll("#reportLive .good,#reportLive .wrong").forEach(function(e){e.classList.remove("good","wrong");});
    tb.innerHTML='<table><tr><th>Objective of evaluation</th><th>Max.</th><th>Marks obtained</th></tr>'+gradeRows(null)+'</table><p class="note">Marks appear here automatically after you submit.</p>';
    box.innerHTML='<h2>Automatic grading</h2><div class="gsum"><div style="flex:1;min-width:260px" class="note">Your report is graded out of 40 as soon as you submit it: 30 marks for the five data tables and 10 marks for the questions. Every expected value is worked out from <b>your own</b> masses and initial velocities. After submitting, the report is locked.'+(S.attempts?' Previous attempts: '+S.attempts+'.':'')+'</div><button class="btn pri" id="rSubmit">'+(subArmed?"Press again to confirm":"Submit for grading")+'</button></div>';
    return;
  }
  var g=grade(),pc=Math.round(100*g.total/40);
  Object.keys(g.marks).forEach(function(k){mark(k,g.marks[k]);});
  tb.innerHTML='<table><tr><th>Objective of evaluation</th><th>Max.</th><th>Marks obtained</th></tr>'+gradeRows(g)+'</table><p class="note">Graded automatically (attempt '+(S.attempts||1)+').</p>';
  box.innerHTML='<h2>Automatic grading</h2><div class="gsum"><div class="ring" style="--p:'+pc+'"><span>'+g.total.toFixed(1)+'<br><small>out of 40</small></span></div><div style="flex:1;min-width:280px"><div class="chips">'+g.tables.map(function(t){return '<span class="chip '+(t.ok===t.tot?"ok":"no")+'">'+t.name+": "+t.score.toFixed(2)+" / 6</span>";}).join("")+'<span class="chip '+(g.analysis===10?"ok":"no")+'">Questions: '+g.analysis.toFixed(1)+' / 10</span><span class="chip '+(g.aok===g.atot?"ok":"no")+'">Assignment check: '+g.aok+' of '+g.atot+'</span></div>'+
    '<p class="note" style="margin:8px 0 0">Submitted '+esc(new Date(S.submitted).toLocaleString())+'. Correct entries are marked green and incorrect ones red in the tables below.</p></div><button class="btn" id="rReopen">Reopen for editing</button></div>'+
    (g.fb.length?'<details style="margin-top:10px"'+(g.fb.length<=8?" open":"")+'><summary style="cursor:pointer;font-weight:700">Feedback ('+g.fb.length+' items)</summary><ul class="fbl">'+g.fb.map(function(x){return "<li>"+esc(x)+"</li>";}).join("")+'</ul></details>':'<p style="margin:10px 0 0;font-weight:700;color:var(--ok)">Everything is correct. Well done.</p>');
}
document.addEventListener("click",function(ev){
  var e=ev.target;
  if(e.id==="rSubmit"){
    if(!subArmed){subArmed=true;renderGrade();setTimeout(function(){subArmed=false;renderGrade();},5000);return;}
    subArmed=false;S.submitted=new Date().toISOString();S.attempts=(S.attempts||0)+1;S._grade=grade().total;persist();paint();toast("Submitted. Your grade is "+S._grade.toFixed(1)+" out of 40.");
  }else if(e.id==="rReopen"){S.submitted="";delete S._grade;persist();document.querySelectorAll(".good,.wrong").forEach(function(x){x.classList.remove("good","wrong");});paint();toast("Report reopened. Submit again when you are ready.");}
});

/* ---------------- page modes and trial list ---------------- */
var PAGE=document.body.dataset.page||"";
function buildTrials(){
  var h='<div class="tgrp">Part 1A · Elastic, m₁ = m₂ = <input type="number" step="0.1" min="0.1" max="3" data-k="t1.m" placeholder="kg"> kg</div>';
  ROWS1.forEach(function(r,i){h+='<div class="trow"><span class="nm">Trial '+(i+1)+'</span><span class="set">'+(r[0]===null?'v₁ᵢ = <input type="number" step="0.1" data-k="t1.'+i+'.v1i" placeholder="choose"> v₂ᵢ = <input type="number" step="0.1" data-k="t1.'+i+'.v2i" placeholder="choose"> m/s':'v₁ᵢ = '+r[0].toFixed(2)+' m/s, v₂ᵢ = '+r[1].toFixed(2)+' m/s')+'</span><button class="btn sm" data-load="t1.'+i+'">Load</button><button class="btn sm" data-rec="t1.'+i+'">Record</button><span class="res" data-res="t1.'+i+'"></span></div>';});
  h+='<div class="tgrp">Part 1B · Elastic, m₁ = <input type="number" step="0.1" min="0.1" max="3" data-k="t23.m1" placeholder="2–3"> kg, m₂ = <input type="number" step="0.1" min="0.1" max="3" data-k="t23.m2" placeholder="0.5–2"> kg</div>';
  ROWS23.forEach(function(r,i){h+='<div class="trow"><span class="nm">Trial '+(i+1)+'</span><span class="set">v₁ᵢ = '+r[0].toFixed(2)+' m/s, v₂ᵢ = '+r[1].toFixed(2)+' m/s</span><button class="btn sm" data-load="t23.'+i+'">Load</button><button class="btn sm" data-rec="t23.'+i+'">Record</button><span class="res" data-res="t23.'+i+'"></span></div>';});
  h+='<div class="tgrp">Part 2 · Perfectly inelastic (elasticity 0 %)</div>';
  ROWS45.forEach(function(r,i){h+='<div class="trow"><span class="nm">Trial '+(i+1)+'</span><span class="set">m₁ = '+r[0]+' kg, m₂ = '+r[1]+' kg, v₁ᵢ = '+r[2].toFixed(2)+', v₂ᵢ = '+r[3].toFixed(2)+' m/s</span><button class="btn sm" data-load="t45.'+i+'">Load</button><button class="btn sm" data-rec="t45.'+i+'">Record</button><span class="res" data-res="t45.'+i+'"></span></div>';});
  $("trials").innerHTML=h;
}
function refreshTrials(){
  document.querySelectorAll("[data-res]").forEach(function(e){var k=e.dataset.res,t=k.split(".")[0],txt="";
    if(t==="t45"){if(S[k+".vf"])txt="✓ v_f = "+S[k+".vf"]+" m/s";}else if(S[k+".v1f"]&&S[k+".v2f"])txt="✓ v₁f = "+S[k+".v1f"]+", v₂f = "+S[k+".v2f"]+" m/s";
    e.textContent=txt||"not recorded yet";e.classList.toggle("ok",!!txt);});
}

/* ---------------- progress and theme ---------------- */
var NEED=(function(){
  var n={info:["date","sec","n1","id1"],p1a:["t1.m","q1a1","q1a2","y1a1","y1a2"],p1b:["t23.m1","t23.m2","q1b1","q1b2","y1b1","y1b2","u.t2.v1f","u.t2.v2f","u.t2.pf","u.t3.v1f","u.t3.v2f","u.t3.kf"],p2:["q2a1","q2b1","q2b2","q2b3","y2a1","y2b1","y2b2","l1","l2","l3","u.t4.vf","u.t4.pf","u.t5.vf","u.t5.kf"],concl:["a1","a2","a3","a4","a5","an1","an2a","an2b","an3a","an3b","an4","an5"]},i;
  for(i=0;i<3;i++){["v1f","v2f","pi","pf","ki","kf"].forEach(function(q){n.p1a.push("t1."+i+"."+q);});
    ["v1f","v2f","pi","pf","ki","kf","pyn","kyn"].forEach(function(q){n.p1b.push("t23."+i+"."+q);});
    ["vf","pi","pf","ki","kf","pyn","kyn"].forEach(function(q){n.p2.push("t45."+i+"."+q);});}
  return n;})();
function progress(){
  var done=0,tot=0;
  Object.keys(NEED).forEach(function(s){var d=NEED[s].filter(function(k){return S[k]!==undefined&&String(S[k]).trim()!=="";}).length;
    done+=d;tot+=NEED[s].length;var b=document.querySelector('#nav button[data-s="'+s+'"]');if(b)b.style.setProperty("--p",Math.round(100*d/NEED[s].length));});
  var pc=Math.round(100*done/tot);if(S._pct!==pc){S._pct=pc;persist();}$("progBar").style.width=pc+"%";$("progTxt").textContent=pc===100?"Lab complete. Open the digital report.":"Lab progress "+pc+"%";
}
function applyTheme(){document.body.classList.toggle("dark",S.theme==="dark");$("themeBtn").textContent=S.theme==="dark"?"Light mode":"Dark mode";}
$("themeBtn").onclick=function(){S.theme=S.theme==="dark"?"light":"dark";applyTheme();persist();};

/* ---------------- start ---------------- */
document.querySelectorAll(".sec textarea[data-k]").forEach(function(t){var c=qctl(t.dataset.k);if(c)t.insertAdjacentHTML("beforebegin",c);});
buildTables();buildTrials();restore();if(!S.logo)S.logo=DEFAULT_LOGO;paint();paint();showLogo();applyTheme();
S.mode="student";
reset();requestAnimationFrame(frame);
if(PAGE)show(PAGE);
if(PAGE)window.addEventListener("storage",function(ev){if(ev.key===KEY){restore();if(!S.logo)S.logo=DEFAULT_LOGO;paint();}});
</script>
<script>
/* link to the lab report: masses come in through the address, recorded velocities go back by message */
(function(){
  var h=location.hash,g=function(re){var x=re.exec(h);return x?parseFloat(x[1]):NaN;},ma=g(/-ma([\d.]+)/),m1=g(/-mb([\d.]+)/),m2=g(/-mc([\d.]+)/);
  function setM(a,b,c,fresh){if(fresh)S={logo:S.logo,theme:S.theme,inst:S.inst,course:S.course,mode:"student"};S["t1.m"]=String(a);S["t23.m1"]=String(b);S["t23.m2"]=String(c);
    if(!fresh)Object.keys(S).forEach(function(k){if(/^t(1|23)\.\d\.(v1f|v2f)$/.test(k))delete S[k];});persist();paint();}
  if(isFinite(ma)&&isFinite(m1)&&isFinite(m2))setM(ma,m1,m2,true);
  window.addEventListener("hashchange",function(){h=location.hash;var a=g(/-ma([\d.]+)/),b=g(/-mb([\d.]+)/),c=g(/-mc([\d.]+)/);if(isFinite(a)&&isFinite(b)&&isFinite(c)&&(String(a)!==S["t1.m"]||String(b)!==S["t23.m1"]||String(c)!==S["t23.m2"])){setM(a,b,c,false);toast("Masses updated from your lab report.");}});
  if(window.parent!==window)document.body.classList.add("emb");
  (function(){var m=document.getElementById("oMom");m.checked=false;var l=m.closest("label");if(l)l.style.display="none";
    var w=document.getElementById("wallWarn");if(w)w.textContent="The balls bounced off a wall before they met. A wall exerts an external force, so the velocities just before the collision differ from the ones you set.";
    document.querySelectorAll("#simCard .grid.g2 h3").forEach(function(h){h.textContent="First ball–ball collision: velocities";});
    var ps=document.querySelectorAll("#simCard .grid.g2 p.note");if(ps[0])ps[0].insertAdjacentHTML("beforeend"," Momentum and kinetic energy are not shown here: calculate them yourself in the report.");})();
  var tgt=window.parent!==window?window.parent:window.opener;
  /* every trial's initial conditions are editable here and shared with the report */
  var IC={t1:ROWS1.map(function(r){return r.concat([-1,1]);}),t2:ROWS23.map(function(r){return r.concat([-1,1]);}),t4:ROWS45.map(function(r){return r.concat([-1,1]);})},LOCK=false;
  function posOf(k){var p=k.split("."),r=IC[p[0]==="t1"?"t1":p[0]==="t23"?"t2":"t4"][+p[1]],o=p[0]==="t45"?4:2;return [nv(r[o]),nv(r[o+1])];}
  var _rs=rowSetup;
  rowSetup=function(t,i){
    var okv=function(v){return isFinite(v)&&Math.abs(v)<=4;},okm=function(m){return isFinite(m)&&m>=0.1&&m<=3;};
    if(t==="t1"&&!(okv(num(S["t1."+i+".v1i"]))&&okv(num(S["t1."+i+".v2i"]))))return "Enter both initial velocities for this trial first (−4 to 4 m/s).";
    if(t==="t23"&&!(okv(ROWS23[i][0])&&okv(ROWS23[i][1])))return "Enter both initial velocities for this trial first (−4 to 4 m/s).";
    if(t==="t45"&&!(okm(ROWS45[i][0])&&okm(ROWS45[i][1])&&okv(ROWS45[i][2])&&okv(ROWS45[i][3])))return "Enter masses (0.1 to 3 kg) and initial velocities (−4 to 4 m/s) for this trial first.";
    var ps=posOf(t+"."+i);if(!(isFinite(ps[0])&&isFinite(ps[1])&&ps[0]<ps[1]))return "Enter start positions with ball 1 to the left of ball 2.";
    return _rs(t,i);};
  function nv(x){return x===null||x===undefined||x===""||!isFinite(x)?NaN:+x;}
  function applyIC(){
    for(var i=0;i<5;i++){ROWS1[i]=[null,null];var a=nv(IC.t1[i][0]),b=nv(IC.t1[i][1]);S["t1."+i+".v1i"]=isFinite(a)?String(a):"";S["t1."+i+".v2i"]=isFinite(b)?String(b):"";}
    for(i=0;i<3;i++){ROWS23[i]=[nv(IC.t2[i][0]),nv(IC.t2[i][1])];ROWS45[i]=IC.t4[i].slice(0,4).map(nv);}
    persist();render();
  }
  function fld(id,v,ph){return '<input type="number" step="0.1" data-ic="'+id+'" value="'+(isNaN(nv(v))?"":v)+'" placeholder="'+(ph||"")+'"'+(LOCK?" disabled":"")+'>';}
  function btns(k){return '<button class="btn sm" data-load="'+k+'">Load</button><button class="btn sm" data-rec="'+k+'">Record</button><span class="res" data-res="'+k+'"></span>';}
  function render(){
    var h='<div class="tgrp">Part 1A · Elastic, m₁ = m₂ = <input type="number" step="0.1" min="0.1" max="3" data-k="t1.m"> kg</div>';
    IC.t1.forEach(function(r,i){h+='<div class="trow"><span class="nm">Trial '+(i+1)+'</span><span class="set">x₁ = '+fld("t1c"+i,r[2])+' x₂ = '+fld("t1d"+i,r[3])+' m &nbsp; v₁ᵢ = '+fld("t1a"+i,r[0],"choose")+' v₂ᵢ = '+fld("t1b"+i,r[1],"choose")+' m/s</span>'+btns("t1."+i)+'</div>';});
    h+='<div class="tgrp">Part 1B · Elastic, m₁ = <input type="number" step="0.1" min="2" max="3" data-k="t23.m1"> kg, m₂ = <input type="number" step="0.1" min="0.5" max="2" data-k="t23.m2"> kg</div>';
    IC.t2.forEach(function(r,i){h+='<div class="trow"><span class="nm">Trial '+(i+1)+'</span><span class="set">x₁ = '+fld("t2c"+i,r[2])+' x₂ = '+fld("t2d"+i,r[3])+' m &nbsp; v₁ᵢ = '+fld("t2a"+i,r[0])+' v₂ᵢ = '+fld("t2b"+i,r[1])+' m/s</span>'+btns("t23."+i)+'</div>';});
    h+='<div class="tgrp">Part 2 · Perfectly inelastic (elasticity 0 %)</div>';
    IC.t4.forEach(function(r,i){h+='<div class="trow"><span class="nm">Trial '+(i+1)+'</span><span class="set">m₁ = '+fld("t4m"+i,r[0])+' m₂ = '+fld("t4n"+i,r[1])+' kg &nbsp; x₁ = '+fld("t4c"+i,r[4])+' x₂ = '+fld("t4d"+i,r[5])+' m &nbsp; v₁ᵢ = '+fld("t4a"+i,r[2])+' v₂ᵢ = '+fld("t4b"+i,r[3])+' m/s</span>'+btns("t45."+i)+'</div>';});
    document.getElementById("trials").innerHTML=h;paint();
  }
  function setLocal(id,v){var m=/^t(1|2|4)([abcdmn])(\d)$/.exec(id);if(!m)return;var i=+m[3],x=isNaN(nv(v))?null:+v;
    if(m[1]==="1")IC.t1[i]["abcd".indexOf(m[2])]=x;else if(m[1]==="2")IC.t2[i]["abcd".indexOf(m[2])]=x;else IC.t4[i]["mnabcd".indexOf(m[2])]=x;
    var key=(m[1]==="1"?"t1.":m[1]==="2"?"t23.":"t45.")+i;["v1f","v2f","vf"].forEach(function(q){delete S[key+"."+q];});if(sim.loaded===key){sim.loaded=null;document.getElementById("loadedTag").textContent="";}}
  document.getElementById("trials").addEventListener("change",function(ev){var id=ev.target.dataset&&ev.target.dataset.ic;if(!id)return;
    setLocal(id,ev.target.value);applyIC();
    if(tgt){try{tgt.postMessage({type:"phys111-lab9-ic-set",id:id,v:ev.target.value===""?null:ev.target.value},"*");}catch(err){}}});
  window.addEventListener("message",function(e){var d=e.data;if(!d||d.type!=="phys111-lab9-ic")return;
    LOCK=!!d.locked;
    ["t1","t2","t4"].forEach(function(t){d[t].forEach(function(r,i){r.forEach(function(v,k){var o=nv(IC[t][i][k]),n2=nv(v);if(o!==n2&&!(isNaN(o)&&isNaN(n2)))setLocal(t+(t==="t4"?"mnabcd".charAt(k):"abcd".charAt(k))+i,v);});});});
    if(String(d.ma)!==S["t1.m"]||String(d.m1)!==S["t23.m1"]||String(d.m2)!==S["t23.m2"])setM(d.ma,d.m1,d.m2,false);
    applyIC();});
  applyIC();
  /* Load uses the trial's own start positions */
  document.addEventListener("click",function(ev){var k=ev.target.dataset&&ev.target.dataset.load;if(!k||sim.loaded!==k)return;
    var ps=posOf(k);document.getElementById("x1").value=ps[0];document.getElementById("x2").value=ps[1];reset();});
  if(tgt){try{tgt.postMessage({type:"phys111-lab9-hello"},"*");}catch(err){}}
  document.addEventListener("click",function(ev){
    var e=ev.target;if(!e.dataset||!e.dataset.rec||!tgt)return;var k=e.dataset.rec;
    if(sim.loaded!==k||!sim.col)return;
    var p=k.split("."),msg={type:"phys111-lab9-record",t:p[0],i:+p[1]};
    if(p[0]==="t45")msg.vf=S[k+".vf"];else{msg.v1f=S[k+".v1f"];msg.v2f=S[k+".v2f"];}
    try{tgt.postMessage(msg,"*");}catch(err){}
  });
  document.getElementById("trials").addEventListener("change",function(ev){var k=ev.target.dataset&&ev.target.dataset.k;if(k!=="t1.m"&&k!=="t23.m1"&&k!=="t23.m2")return;
    if(!tgt)return;try{tgt.postMessage({type:"phys111-lab9-mass",ma:S["t1.m"],m1:S["t23.m1"],m2:S["t23.m2"]},"*");}catch(err){}});
  window.addEventListener("message",function(e){var d=e.data;if(!d||d.type!=="phys111-lab9-mass-ack")return;
    if(!d.ok||d.locked)setM(d.ma,d.m1,d.m2,false);else{Object.keys(S).forEach(function(k){if(/^t(1|23)\.\d\.(v1f|v2f)$/.test(k))delete S[k];});persist();paint();}
    toast(d.locked?"The report is already submitted, so the masses cannot change.":d.ok?"Masses saved to your lab report.":"Not allowed: Part 1A 0.1–3 kg; Part 1B m₁ = 2–3 kg, m₂ = 0.5–2 kg, m₂ < m₁.");});
  window.addEventListener("message",function(e){var d=e.data;if(d&&d.type==="phys111-lab9-record-ack")toast(d.locked?"The report is already submitted, so nothing was changed.":"Final velocities sent to your lab report.");});
})();
</script>
</body>
</html>
