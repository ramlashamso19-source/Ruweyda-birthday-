<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Happy 18th Birthday Ruweyda 🎂</title>
<meta name="description" content="A little birthday surprise for you. Turn your sound on 💗">
<meta property="og:type" content="website">
<meta property="og:title" content="Happy 18th Birthday Ruweyda 🎂">
<meta property="og:description" content="A little birthday surprise for you. Turn your sound on 💗">
<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="Happy 18th Birthday Ruweyda 🎂">
<meta name="twitter:description" content="A little birthday surprise for you. Turn your sound on 💗">
<meta name="theme-color" content="#04141a">
<style>:root{padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}body{margin:0}</style>
</head>
<body>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Klee+One:wght@600&family=Shippori+Mincho+B1:wght@700;800&family=Zen+Maru+Gothic:wght@400;500;700&display=swap">
<style>
  /* Layout: one full-screen stage. A single canvas paints the whole world (aurora sky, lanterns,
     cake, garden, fireworks); each scene lays its text over it. Committed single dark look. */
  :root {
    --night: #04141a;
    --deep: #06302a;
    --emerald: #0f7a55;
    --mint: #a8f5cc;
    --lime: #c9ff6b;
    --gold: #ffd86b;
    --pink: #ff8fc0;
    --cream: #eafff3;
    --glass: rgba(4, 22, 24, 0.84);
    --font-display: "Shippori Mincho B1", "Hiragino Mincho ProN", "Georgia", serif;
    --font-body: "Zen Maru Gothic", "Hiragino Maru Gothic ProN", system-ui, -apple-system, "Segoe UI", sans-serif;
    --font-hand: "Klee One", "Segoe Script", cursive;
    color-scheme: dark;
  }
  * { box-sizing: border-box; }
  html, body { height: 100%; }
  body {
    background: var(--night);
    color: var(--cream);
    font-family: var(--font-body);
    font-size: 16px;
    overflow: hidden;
  }
  .app { position: relative; height: 100%; overflow: hidden; background: var(--night); }
  #cv { position: absolute; inset: 0; width: 100%; height: 100%; display: block; touch-action: manipulation; }
  .vig {
    position: absolute; inset: 0; pointer-events: none; z-index: 1;
    background: radial-gradient(ellipse at 50% 45%, transparent 55%, rgba(0, 8, 10, 0.55) 100%);
  }
  .fade {
    position: absolute; inset: 0; z-index: 30; background: #02100f; opacity: 0; pointer-events: none;
    transition: opacity 0.7s ease;
  }
  .fade.on { opacity: 1; pointer-events: auto; }

  .scene {
    position: absolute; inset: 0; z-index: 5; display: none; flex-direction: column; align-items: center;
    text-align: center; pointer-events: none;
    padding-block: 64px 28px;
    padding-left: max(16px, env(safe-area-inset-left, 0px));
    padding-right: max(16px, env(safe-area-inset-right, 0px));
  }
  .scene.on { display: flex; animation: sceneIn 0.9s ease-out both; }
  @keyframes sceneIn { from { opacity: 0; transform: translateY(10px); } }
  .scene button, .scene .card { pointer-events: auto; }

  .kicker {
    margin: 0; display: inline-block; padding: 4px 14px; background: var(--gold); color: var(--deep);
    transform: skewX(-10deg); font: 800 0.85rem var(--font-body); letter-spacing: 0.14em; text-transform: uppercase;
  }
  .t-big {
    margin: 0; font-family: var(--font-display); font-weight: 800; line-height: 1.02; text-wrap: balance;
    text-shadow: 0 3px 0 var(--deep), 0 0 30px rgba(6, 48, 42, 0.8);
  }
  .t-big em {
    display: block; font-style: normal; color: var(--lime);
    text-shadow: 0 4px 0 var(--deep), 0 0 40px rgba(201, 255, 107, 0.5);
    animation: track 2.2s ease-out both;
  }
  @keyframes track { from { letter-spacing: 0.35em; opacity: 0; filter: blur(8px); } }
  .jp { margin: 0; font-size: clamp(1rem, 3.4vw, 1.3rem); font-weight: 700; letter-spacing: 0.3em; color: var(--gold); text-shadow: 0 2px 10px var(--deep); }
  .lead {
    margin: 0; max-width: 34ch; font-size: clamp(1rem, 3.2vw, 1.15rem); font-weight: 500; line-height: 1.5;
    color: var(--cream); text-shadow: 0 1px 10px var(--deep), 0 0 3px var(--deep);
  }
  .note { margin: 0; font-size: 0.9rem; color: var(--mint); text-shadow: 0 1px 8px var(--deep), 0 0 3px var(--deep), 0 0 3px var(--deep); }

  .pill {
    min-height: 50px; padding: 12px 28px; border: 3px solid var(--deep); border-radius: 999px; cursor: pointer;
    background: var(--lime); color: var(--deep); font: 700 1.05rem var(--font-body);
    box-shadow: 0 4px 0 var(--deep); transition: transform 0.12s ease, box-shadow 0.12s ease;
  }
  .pill:hover { transform: translateY(-2px); box-shadow: 0 6px 0 var(--deep); }
  .pill:active { transform: translateY(3px); box-shadow: 0 1px 0 var(--deep); }
  .ghost {
    min-height: 46px; padding: 10px 22px; border: 2px solid rgba(168, 245, 204, 0.6); border-radius: 999px; cursor: pointer;
    background: rgba(4, 22, 24, 0.55); color: var(--cream); font: 700 0.95rem var(--font-body);
  }
  .ghost:hover { border-color: var(--lime); }
  button:focus-visible { outline: 3px solid var(--gold); outline-offset: 3px; }

  /* gate */
  #s-gate { justify-content: center; gap: 16px; padding-block: 28px; }
  #s-gate .t-big { font-size: clamp(2.8rem, 15vw, 6.4rem); letter-spacing: 0.04em; }
  #s-gate .t-big span { display: block; font-size: 0.26em; letter-spacing: 0.32em; color: var(--mint); font-weight: 700; margin-bottom: 8px; text-transform: uppercase; }
  /* intro */
  #s-intro { gap: 12px; padding-top: clamp(70px, 13vh, 120px); }
  #s-intro .t-big { font-size: clamp(2.1rem, 8vw, 4.4rem); }
  #s-intro .t-big em { font-size: 1.3em; }
  .sub {
    position: absolute; left: 0; right: 0; bottom: 17%; z-index: 6; text-align: center; pointer-events: none;
    padding-left: max(20px, env(safe-area-inset-left, 0px)); padding-right: max(20px, env(safe-area-inset-right, 0px));
    font: 700 clamp(1.05rem, 3.6vw, 1.45rem)/1.35 var(--font-body); color: #fff; min-height: 2.8em;
    text-shadow: -2px -2px 0 #000, 2px -2px 0 #000, -2px 2px 0 #000, 2px 2px 0 #000, 0 0 14px rgba(0, 0, 0, 0.7);
  }
  .sub.pop { animation: subIn 0.5s ease-out both; }
  @keyframes subIn { from { opacity: 0; transform: translateY(8px); } }
  .skip { position: absolute; bottom: 5%; }
  /* cake */
  #s-cake { gap: 10px; }
  #s-cake h2, #s-garden h2, #s-finale h2 {
    margin: 0; font-family: var(--font-display); font-weight: 800; font-size: clamp(1.8rem, 6.5vw, 3rem); line-height: 1.1;
    text-shadow: 0 3px 0 var(--deep), 0 0 26px rgba(6, 48, 42, 0.8); text-wrap: balance;
  }
  .bottom { position: absolute; left: 0; right: 0; bottom: 4%; display: flex; flex-direction: column; align-items: center; gap: 12px;
    padding-left: max(16px, env(safe-area-inset-left, 0px)); padding-right: max(16px, env(safe-area-inset-right, 0px)); }
  .blow {
    --p: 0%; min-width: 240px; min-height: 60px; font-size: 1.15rem; touch-action: none; user-select: none; -webkit-user-select: none;
    background: linear-gradient(90deg, var(--lime) var(--p), rgba(201, 255, 107, 0.3) var(--p));
    color: #f4fff8; text-shadow: 0 1px 3px var(--deep);
  }
  .wish { margin: 0; min-height: 1.6em; font: 600 1.35rem var(--font-hand); color: var(--gold); text-shadow: 0 2px 10px var(--deep); opacity: 0; transition: opacity 0.8s ease; }
  .wish.show { opacity: 1; }
  /* garden */
  #s-garden { gap: 10px; }
  .later { opacity: 0; pointer-events: none !important; transition: opacity 0.8s ease; }
  .later.show { opacity: 1; pointer-events: auto !important; }
  /* letter */
  #s-letter { justify-content: center; padding-block: 56px 20px; }
  .card {
    width: min(640px, 100%); max-height: 100%; display: flex; flex-direction: column; gap: 14px;
    padding: clamp(18px, 4vw, 30px); text-align: left; background: var(--glass);
    -webkit-backdrop-filter: blur(10px); backdrop-filter: blur(10px);
    border: 2px solid rgba(168, 245, 204, 0.45); border-top: 6px solid var(--lime); border-radius: 18px;
    box-shadow: 0 24px 70px rgba(0, 0, 0, 0.6), 8px 8px 0 var(--emerald);
  }
  .lt { overflow-y: auto; min-height: 0; display: grid; gap: 1em; align-content: start; flex: 1 1 auto; max-height: calc(100svh - 230px); overscroll-behavior: contain; }
  .lt p { margin: 0; }
  .b-dear { font: 600 clamp(1.7rem, 6vw, 2.3rem) var(--font-hand); color: var(--lime); }
  .b-cheer { font: 800 clamp(1.4rem, 5.4vw, 2.2rem)/1.2 var(--font-display); color: var(--gold); overflow-wrap: anywhere; }
  .b-p { font-size: clamp(1rem, 2.7vw, 1.12rem); font-weight: 500; line-height: 1.8; }
  .b-with { font-weight: 700; margin-top: 0.4em !important; }
  .b-sig { font: 600 clamp(1.8rem, 6vw, 2.4rem) var(--font-hand); color: var(--lime); }
  .cardfoot { display: flex; justify-content: space-between; align-items: center; gap: 12px; flex-wrap: wrap; }
  .pg { font-size: 0.85rem; font-weight: 700; letter-spacing: 0.14em; color: var(--mint); }
  /* finale */
  #s-finale { gap: 10px; padding-top: clamp(64px, 10vh, 100px); }
  #s-finale .t-big { font-size: clamp(1.1rem, 4vw, 1.6rem); letter-spacing: 0.3em; color: var(--mint); text-transform: uppercase; font-weight: 700; }
  #s-finale h2 { font-size: clamp(2.6rem, 11vw, 5rem); color: var(--lime); text-shadow: 0 4px 0 var(--deep), 0 0 40px rgba(201, 255, 107, 0.5); }
  .row { display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; }
  .row .pill, .row .ghost { min-height: 44px; padding: 8px 16px; font-size: 0.92rem; }
  /* hud */
  .hud {
    position: absolute; top: 10px; left: 0; right: 0; z-index: 10; display: flex; justify-content: space-between; align-items: center;
    pointer-events: none;
    padding-left: max(16px, env(safe-area-inset-left, 0px)); padding-right: max(16px, env(safe-area-inset-right, 0px));
  }
  .dots { display: flex; gap: 7px; }
  .dots i { width: 8px; height: 8px; border-radius: 50%; background: rgba(168, 245, 204, 0.3); }
  .dots i.on { background: var(--lime); box-shadow: 0 0 10px var(--lime); }
  #snd { pointer-events: auto; min-height: 38px; padding: 6px 16px; font-size: 0.85rem; }
  @media (prefers-reduced-motion: reduce) {
    .scene.on, .t-big em, .sub.pop { animation: none; }
    .pill, .fade { transition: none; }
  }
</style>

<div class="app" id="app">
  <canvas id="cv" aria-label="An animated birthday film for Ruweyda"></canvas>
  <div class="vig"></div>

  <div class="hud" id="hud" hidden>
    <div class="dots" id="dots" aria-hidden="true"><i></i><i></i><i></i><i></i><i></i></div>
    <button class="ghost" id="snd" type="button" aria-pressed="false">Sound on</button>
  </div>

  <section class="scene on" id="s-gate">
    <h1 class="t-big"><span>A birthday film for</span>Ruweyda</h1>
    <p class="lead">Episode 18. It starts when you press play.</p>
    <button class="pill" id="play" type="button">&#9654; Press play</button>
    <p class="note">Turn your sound on for the full show.</p>
  </section>

  <section class="scene" id="s-intro">
    <p class="kicker">Episode 18</p>
    <h1 class="t-big">Happy Birthday,<em>Ruweyda</em></h1>
    <p class="jp" lang="ja">誕生日おめでとう</p>
    <div class="sub" id="sub" aria-live="polite"></div>
    <button class="ghost skip" id="skipIntro" type="button">Skip &rsaquo;</button>
  </section>

  <section class="scene" id="s-cake">
    <h2>Make a wish</h2>
    <p class="lead">Close your eyes and think of it. Then hold the button to blow out the candles.</p>
    <div class="bottom">
      <p class="wish" id="wishMsg" aria-live="polite">Your wish is floating up to the stars &#10024;</p>
      <button class="pill blow" id="blow" type="button">Hold to blow &#128168;</button>
      <button class="ghost" id="skipCake" type="button">Skip &rsaquo;</button>
    </div>
  </section>

  <section class="scene" id="s-garden">
    <h2>18 flowers, one for every year</h2>
    <p class="lead">Tap the garden to plant more.</p>
    <div class="bottom"><button class="pill later" id="toLetter" type="button">Read your letter &rsaquo;</button></div>
  </section>

  <section class="scene" id="s-letter">
    <article class="card">
      <div class="lt" id="lt"></div>
      <div class="cardfoot">
        <span class="pg" id="pg">1 / 4</span>
        <button class="pill" id="lnext" type="button">Skip typing</button>
      </div>
    </article>
  </section>

  <section class="scene" id="s-finale">
    <p class="t-big">Happy Birthday</p>
    <h2>Ruweyda</h2>
    <p class="lead">Here is to 18, and everything after.</p>
    <div class="bottom">
      <p class="note">Tap the sky to launch fireworks.</p>
      <div class="row">
        <button class="pill" id="fwBtn" type="button">Launch fireworks</button>
        <button class="ghost" id="againLetter" type="button">Read the letter again</button>
        <button class="ghost" id="replay" type="button">Replay the film</button>
      </div>
    </div>
  </section>

  <div class="fade" id="fade"></div>
</div>

<script>
(function () {
  'use strict';
  var $ = function (id) { return document.getElementById(id); };
  var app = $('app'), cv = $('cv'), ctx = cv.getContext('2d');
  var au = document.createElement('canvas'), actx = au.getContext('2d');
  var RM = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  var TAU = 6.2832;

  function rnd(a, b) { return a + Math.random() * (b - a); }
  function pick(a) { return a[Math.floor(Math.random() * a.length)]; }
  function clamp(v, a, b) { return Math.max(a, Math.min(b, v)); }
  function lerp(a, b, t) { return a + (b - a) * t; }
  function easeOut(t) { return 1 - Math.pow(1 - t, 3); }
  function easeBack(t) { var c1 = 1.5, c3 = c1 + 1; return 1 + c3 * Math.pow(t - 1, 3) + c1 * Math.pow(t - 1, 2); }
  function hsla(h, s, l, a) { return 'hsla(' + h + ',' + s + '%,' + l + '%,' + (a == null ? 1 : a) + ')'; }
  function rgba(c, a) { return 'rgba(' + c[0] + ',' + c[1] + ',' + c[2] + ',' + a + ')'; }
  function mf(n) { return 440 * Math.pow(2, (n - 69) / 12); }

  /* ================= state ================= */
  var W = 0, H = 0, dpr = 1, maxH = 200, last = 0, frameN = 0;
  var scene = 'gate', sceneT0 = performance.now(), evs = {}, busy = false;
  var skyMix = 0, skyTarget = 0;
  var stars = [], shoots = [], lanterns = [], flowers = [], petals = [], flies = [], parts = [], bokeh = [], buildings = [];
  var fws = [], fparts = [], cons = null;
  var nextLan = 0, nextPetal = 0, nextShoot = 3000, nextFw = 0;
  var cake = { blowing: false, p: 0, lit: 1, out: false, outT: 0, snd: null };
  var BASE = 18, CAP = 90;

  /* ================= audio ================= */
  var ac = null, master = null, noiseBuf = null, aTimer = null, nextT = 0, astep = 0, level = 1, muted = false;
  function initAudio() {
    if (ac) return;
    var AC = window.AudioContext || window.webkitAudioContext;
    if (!AC) return;
    try {
      ac = new AC();
      master = ac.createGain(); master.gain.value = 0.8;
      var comp = ac.createDynamicsCompressor(); comp.threshold.value = -16; comp.ratio.value = 4;
      master.connect(comp); comp.connect(ac.destination);
      noiseBuf = ac.createBuffer(1, ac.sampleRate, ac.sampleRate);
      var d = noiseBuf.getChannelData(0);
      for (var i = 0; i < d.length; i++) d[i] = Math.random() * 2 - 1;
    } catch (e) { ac = null; }
  }
  function tone(t, type, freq, dur, vol, o) {
    o = o || {};
    var osc = ac.createOscillator(), g = ac.createGain(), f = ac.createBiquadFilter();
    f.type = 'lowpass'; f.frequency.setValueAtTime(o.cut || 3000, t);
    osc.type = type; osc.frequency.setValueAtTime(freq, t);
    if (o.glide) osc.frequency.exponentialRampToValueAtTime(o.glide, t + dur);
    g.gain.setValueAtTime(0.0001, t);
    g.gain.linearRampToValueAtTime(vol, t + (o.att || 0.01));
    g.gain.exponentialRampToValueAtTime(0.0001, t + dur);
    osc.connect(f); f.connect(g); g.connect(master);
    osc.start(t); osc.stop(t + dur + 0.05);
  }
  function bell(t, m, dur, vol) {
    var f = mf(m);
    tone(t, 'sine', f, dur, vol, { att: 0.004, cut: 7000 });
    tone(t, 'sine', f * 2.002, dur * 0.5, vol * 0.3, { att: 0.004, cut: 8000 });
    tone(t, 'triangle', f * 3.01, dur * 0.22, vol * 0.1, { att: 0.002, cut: 8000 });
  }
  function noiseHit(t, dur, type, freq, vol, q) {
    var src = ac.createBufferSource(); src.buffer = noiseBuf;
    var f = ac.createBiquadFilter(); f.type = type; f.frequency.value = freq; f.Q.value = q || 1;
    var g = ac.createGain();
    g.gain.setValueAtTime(vol, t); g.gain.exponentialRampToValueAtTime(0.0001, t + dur);
    src.connect(f); f.connect(g); g.connect(master);
    src.start(t, Math.random() * 0.5); src.stop(t + dur + 0.02);
  }
  function padAt(t, notes, dur, vol) {
    for (var i = 0; i < notes.length; i++) {
      for (var k = 0; k < 2; k++) {
        var o = ac.createOscillator(), g = ac.createGain(), f = ac.createBiquadFilter();
        o.type = 'triangle'; o.frequency.value = mf(notes[i]); o.detune.value = k ? 6 : -6;
        f.type = 'lowpass'; f.frequency.value = 1300;
        g.gain.setValueAtTime(0.0001, t);
        g.gain.linearRampToValueAtTime(vol, t + dur * 0.3);
        g.gain.linearRampToValueAtTime(0.0001, t + dur);
        o.connect(f); f.connect(g); g.connect(master); o.start(t); o.stop(t + dur + 0.05);
      }
    }
  }
  function kick(t, v) {
    var o = ac.createOscillator(), g = ac.createGain();
    o.type = 'sine'; o.frequency.setValueAtTime(150, t); o.frequency.exponentialRampToValueAtTime(48, t + 0.14);
    g.gain.setValueAtTime(v, t); g.gain.exponentialRampToValueAtTime(0.001, t + 0.36);
    o.connect(g); g.connect(master); o.start(t); o.stop(t + 0.4);
  }
  var CHORDS = [[53, 57, 60, 64], [55, 59, 62, 65], [52, 55, 59, 62], [57, 60, 64, 67]];
  var ROOTS = [41, 43, 40, 45], ARP = [0, 1, 2, 3, 2, 1, 3, 2];
  function sched() {
    if (!ac) return;
    var sd = 60 / 76 / 2;
    if (nextT < ac.currentTime - 0.1) nextT = ac.currentTime + 0.05;
    while (nextT < ac.currentTime + 0.3) {
      var bar = Math.floor(astep / 8) % 4, s = astep % 8, c = CHORDS[bar];
      if (level > 0) {
        if (s === 0) padAt(nextT, c, sd * 8, level >= 3 ? 0.05 : 0.035);
        if (level >= 2 || s % 2 === 0) bell(nextT, c[ARP[s]] + 12, sd * 5, level >= 2 ? 0.07 : 0.055);
        if (level >= 2 && s === 0) tone(nextT, 'sine', mf(ROOTS[bar]), sd * 6, 0.2, { cut: 700 });
        if (level >= 3) {
          if (s % 4 === 0) kick(nextT, 0.45);
          if (s % 2 === 1) noiseHit(nextT, 0.04, 'highpass', 8000, 0.03);
          if (s === 6) bell(nextT, c[3] + 24, sd * 3, 0.05);
        }
      }
      nextT += sd; astep++;
    }
  }
  var HB = [[67, 0.75], [67, 0.25], [69, 1], [67, 1], [72, 1], [71, 2], [67, 0.75], [67, 0.25], [69, 1], [67, 1], [74, 1], [72, 2],
            [67, 0.75], [67, 0.25], [79, 1], [76, 1], [72, 1], [71, 1], [69, 1], [77, 0.75], [77, 0.25], [76, 1], [72, 1], [74, 1], [72, 2]];
  var HBPAD = [[0, [48, 55, 60, 64], 4], [4, [43, 50, 55, 59], 6], [10, [48, 55, 60, 64], 6], [16, [43, 50, 55, 59], 2], [18, [41, 48, 53, 57], 4], [22, [48, 55, 60, 64], 4]];
  function playHB() {
    if (!ac) return;
    var t = ac.currentTime + 0.15, b = 0.56, pos = t, i;
    for (i = 0; i < HB.length; i++) { bell(pos, HB[i][0], 1.4, 0.11); pos += HB[i][1] * b; }
    for (i = 0; i < HBPAD.length; i++) padAt(t + HBPAD[i][0] * b, HBPAD[i][1], HBPAD[i][2] * b + 0.6, 0.03);
  }
  function sparkleSnd() {
    if (!ac) return;
    var n = [72, 76, 79, 84, 88, 91, 96], t = ac.currentTime + 0.02;
    for (var i = 0; i < n.length; i++) bell(t + i * 0.08, n[i], 1.6, 0.09);
    padAt(t, [60, 64, 67, 72], 2.5, 0.05);
  }
  function startBlowSnd() {
    if (!ac || cake.snd) return;
    var src = ac.createBufferSource(); src.buffer = noiseBuf; src.loop = true;
    var f = ac.createBiquadFilter(); f.type = 'bandpass'; f.frequency.value = 900; f.Q.value = 0.6;
    var g = ac.createGain(); g.gain.value = 0;
    src.connect(f); f.connect(g); g.connect(master); src.start();
    cake.snd = { src: src, g: g };
  }
  function stopBlowSnd() {
    if (!cake.snd) return;
    var s = cake.snd; cake.snd = null;
    try { s.g.gain.setTargetAtTime(0, ac.currentTime, 0.05); s.src.stop(ac.currentTime + 0.3); } catch (e) { /* already stopped */ }
  }
  function whistle() {
    if (!ac) return;
    var t = ac.currentTime, src = ac.createBufferSource(); src.buffer = noiseBuf;
    var f = ac.createBiquadFilter(); f.type = 'bandpass'; f.Q.value = 5;
    f.frequency.setValueAtTime(700, t); f.frequency.exponentialRampToValueAtTime(2800, t + 0.8);
    var g = ac.createGain(); g.gain.setValueAtTime(0.05, t); g.gain.exponentialRampToValueAtTime(0.0001, t + 0.85);
    src.connect(f); f.connect(g); g.connect(master); src.start(t); src.stop(t + 0.9);
  }
  function boom() {
    if (!ac) return;
    var t = ac.currentTime;
    var o = ac.createOscillator(), g = ac.createGain();
    o.type = 'sine'; o.frequency.setValueAtTime(130, t); o.frequency.exponentialRampToValueAtTime(38, t + 0.4);
    g.gain.setValueAtTime(0.55, t); g.gain.exponentialRampToValueAtTime(0.001, t + 0.5);
    o.connect(g); g.connect(master); o.start(t); o.stop(t + 0.55);
    noiseHit(t, 0.35, 'lowpass', 900, 0.3, 0.7);
    for (var i = 0; i < 7; i++) noiseHit(t + 0.15 + Math.random() * 0.5, 0.03, 'highpass', 5000, 0.05);
  }
  function setLevel(l) { level = l; }

  /* ================= scenery ================= */
  function groundY(x) { return H - 58 + Math.sin(x * 0.007 + 1) * 9 + Math.sin(x * 0.019) * 4; }
  function rr(x, y, w, h, r) {
    ctx.beginPath(); ctx.moveTo(x + r, y); ctx.lineTo(x + w - r, y); ctx.quadraticCurveTo(x + w, y, x + w, y + r);
    ctx.lineTo(x + w, y + h - r); ctx.quadraticCurveTo(x + w, y + h, x + w - r, y + h); ctx.lineTo(x + r, y + h);
    ctx.quadraticCurveTo(x, y + h, x, y + h - r); ctx.lineTo(x, y + r); ctx.quadraticCurveTo(x, y, x + r, y); ctx.closePath();
  }
  function ell(x, y, rx, ry) { ctx.beginPath(); ctx.ellipse(x, y, rx, ry, 0, 0, TAU); ctx.fill(); }
  function petal(len, wid, round) {
    var y2 = -len * (round ? 1.2 : 0.95), wx = wid * (round ? 1.1 : 0.8);
    ctx.beginPath(); ctx.moveTo(0, 0);
    ctx.bezierCurveTo(wid, -len * 0.25, wx, y2, 0, -len);
    ctx.bezierCurveTo(-wx, y2, -wid, -len * 0.25, 0, 0); ctx.closePath();
  }
  function spark(x, y, r) {
    var k = r * 0.12;
    ctx.beginPath(); ctx.moveTo(x, y - r);
    ctx.quadraticCurveTo(x + k, y - k, x + r, y); ctx.quadraticCurveTo(x + k, y + k, x, y + r);
    ctx.quadraticCurveTo(x - k, y + k, x - r, y); ctx.quadraticCurveTo(x - k, y - k, x, y - r); ctx.closePath();
  }
  function heartPath(x, y, s) {
    ctx.beginPath(); ctx.moveTo(x, y + s * 0.9);
    ctx.bezierCurveTo(x - s * 1.6, y - s * 0.2, x - s * 0.7, y - s * 1.1, x, y - s * 0.35);
    ctx.bezierCurveTo(x + s * 0.7, y - s * 1.1, x + s * 1.6, y - s * 0.2, x, y + s * 0.9); ctx.closePath();
  }

  var PAL = [[[3, 19, 25], [10, 59, 58], [18, 98, 79]], [[6, 34, 45], [20, 98, 90], [63, 191, 142]]];
  function mixc(a, b, m) { return 'rgb(' + Math.round(lerp(a[0], b[0], m)) + ',' + Math.round(lerp(a[1], b[1], m)) + ',' + Math.round(lerp(a[2], b[2], m)) + ')'; }

  function drawAurora(now) {
    var aw = au.width, ah = au.height, t = now / 1000 * (RM ? 0.25 : 1);
    if (frameN % 2 === 0) {
      actx.clearRect(0, 0, aw, ah);
      var hues = [150, 168, 128];
      for (var l = 0; l < 3; l++) {
        for (var x = 0; x < aw; x++) {
          var u = x / aw;
          var yc = ah * (0.42 + 0.1 * l) + Math.sin(u * 5 + t * 0.3 + l * 2) * ah * 0.12 + Math.sin(u * 11 - t * 0.22) * ah * 0.05;
          var hg = ah * (0.3 + 0.12 * Math.sin(u * 7 + t * 0.4 + l));
          var al = clamp(0.2 + 0.16 * Math.sin(u * 3 + t * 0.5 + l * 1.7), 0, 0.5);
          var g = actx.createLinearGradient(0, yc - hg, 0, yc + hg * 0.18);
          g.addColorStop(0, hsla(hues[l], 90, 60, 0));
          g.addColorStop(0.78, hsla(hues[l], 90, 62, al));
          g.addColorStop(1, hsla(hues[l], 90, 62, 0));
          actx.fillStyle = g; actx.fillRect(x, yc - hg, 1, hg * 1.18);
        }
      }
    }
    ctx.save();
    ctx.globalCompositeOperation = 'lighter'; ctx.globalAlpha = 0.85 + 0.15 * skyMix;
    ctx.imageSmoothingEnabled = true;
    ctx.drawImage(au, 0, 0, W, H * 0.62);
    ctx.restore();
  }

  function drawSky(now, dt) {
    skyMix += (skyTarget - skyMix) * Math.min(1, dt * 1.5);
    var g = ctx.createLinearGradient(0, 0, 0, H);
    g.addColorStop(0, mixc(PAL[0][0], PAL[1][0], skyMix));
    g.addColorStop(0.6, mixc(PAL[0][1], PAL[1][1], skyMix));
    g.addColorStop(1, mixc(PAL[0][2], PAL[1][2], skyMix));
    ctx.fillStyle = g; ctx.fillRect(0, 0, W, H);
    var i;
    for (i = 0; i < stars.length; i++) {
      var s = stars[i], a = RM ? 0.6 : 0.3 + 0.45 * Math.sin(now / 900 + s.ph);
      ctx.fillStyle = 'rgba(235,255,245,' + clamp(a, 0.1, 0.9) + ')';
      ctx.beginPath(); ctx.arc(s.fx * W, s.fy * H, s.r, 0, TAU); ctx.fill();
    }
    var mx = W * 0.87, my = H * 0.115, mr = clamp(W * 0.055, 22, 46);
    var mg = ctx.createRadialGradient(mx, my, mr * 0.6, mx, my, mr * 4);
    mg.addColorStop(0, 'rgba(255,244,180,0.45)'); mg.addColorStop(1, 'rgba(255,244,180,0)');
    ctx.fillStyle = mg; ctx.beginPath(); ctx.arc(mx, my, mr * 4, 0, TAU); ctx.fill();
    ctx.fillStyle = '#fff6cf'; ctx.beginPath(); ctx.arc(mx, my, mr, 0, TAU); ctx.fill();
    ctx.fillStyle = 'rgba(214,196,120,0.28)';
    ctx.beginPath(); ctx.arc(mx - mr * 0.3, my - mr * 0.2, mr * 0.22, 0, TAU); ctx.fill();
    ctx.beginPath(); ctx.arc(mx + mr * 0.3, my + mr * 0.3, mr * 0.16, 0, TAU); ctx.fill();
    drawAurora(now);
    if (!RM && now > nextShoot && (scene === 'intro' || scene === 'finale' || scene === 'gate')) {
      shoots.push({ x: rnd(W * 0.2, W * 0.9), y: rnd(0, H * 0.25), vx: -rnd(380, 560), vy: rnd(160, 260), life: 0, max: rnd(0.6, 0.9) });
      nextShoot = now + rnd(2500, 5500);
    }
    for (i = shoots.length - 1; i >= 0; i--) {
      var sh = shoots[i]; sh.life += dt; sh.x += sh.vx * dt; sh.y += sh.vy * dt;
      if (sh.life > sh.max) { shoots.splice(i, 1); continue; }
      var al = 1 - sh.life / sh.max;
      var sg = ctx.createLinearGradient(sh.x, sh.y, sh.x - sh.vx * 0.18, sh.y - sh.vy * 0.18);
      sg.addColorStop(0, 'rgba(255,255,255,' + al + ')'); sg.addColorStop(1, 'rgba(255,255,255,0)');
      ctx.strokeStyle = sg; ctx.lineWidth = 2.2; ctx.lineCap = 'round';
      ctx.beginPath(); ctx.moveTo(sh.x, sh.y); ctx.lineTo(sh.x - sh.vx * 0.18, sh.y - sh.vy * 0.18); ctx.stroke();
    }
  }

  function buildSkyline() {
    buildings = [];
    var x = -10;
    while (x < W + 20) {
      var w = rnd(26, 58), h = rnd(40, clamp(H * 0.2, 70, 160));
      var top = groundY(x + w / 2) - 10 - h, wins = [];
      var cols = Math.floor((w - 8) / 9), rows = Math.floor((h - 10) / 12);
      for (var r = 0; r < rows; r++) for (var c = 0; c < cols; c++) if (Math.random() < 0.3) wins.push([4 + c * 9, 8 + r * 12]);
      buildings.push({ x: x, w: w, top: top, h: h + 40, wins: wins });
      x += w + rnd(0, 4);
    }
  }
  function drawSkyline() {
    for (var i = 0; i < buildings.length; i++) {
      var b = buildings[i];
      ctx.fillStyle = '#0a3330'; ctx.fillRect(b.x, b.top, b.w, b.h);
      ctx.fillStyle = 'rgba(255,230,140,0.85)';
      for (var k = 0; k < b.wins.length; k++) ctx.fillRect(b.x + b.wins[k][0], b.top + b.wins[k][1], 5, 6);
    }
  }
  function hill(off, c1, c2) {
    var g = ctx.createLinearGradient(0, H - 120, 0, H);
    g.addColorStop(0, c1); g.addColorStop(1, c2);
    ctx.fillStyle = g; ctx.beginPath(); ctx.moveTo(0, H);
    for (var x = 0; x <= W + 12; x += 12) ctx.lineTo(x, groundY(x) + off);
    ctx.lineTo(W, H); ctx.closePath(); ctx.fill();
  }
  function drawGrass(now) {
    ctx.strokeStyle = '#0f4a3f'; ctx.lineWidth = 1.8; ctx.lineCap = 'round';
    for (var i = 0, x = 4; x < W; x += 13, i++) {
      var len = 9 + ((i * 37) % 9), sw = RM ? 0 : Math.sin(now / 900 + i) * 2.2, y = groundY(x) + 7;
      ctx.beginPath(); ctx.moveTo(x, y); ctx.quadraticCurveTo(x + sw * 0.4, y - len * 0.6, x + sw, y - len); ctx.stroke();
    }
  }
  function drawFlies(now) {
    for (var i = 0; i < flies.length; i++) {
      var f = flies[i];
      var x = f.fx * W + (RM ? 0 : Math.sin(now / 1700 + f.ph) * 18), y = f.fy * H + (RM ? 0 : Math.cos(now / 2100 + f.ph) * 14);
      var a = RM ? 0.6 : 0.3 + 0.7 * Math.max(0, Math.sin(now / 900 + f.ph * 3));
      var g = ctx.createRadialGradient(x, y, 0, x, y, 8);
      g.addColorStop(0, 'rgba(210,255,140,' + a + ')'); g.addColorStop(1, 'rgba(210,255,140,0)');
      ctx.fillStyle = g; ctx.beginPath(); ctx.arc(x, y, 8, 0, TAU); ctx.fill();
    }
  }

  /* ---------- lanterns ---------- */
  var LCOL = [[255, 200, 110], [255, 200, 110], [160, 255, 200], [255, 160, 200]];
  function addLantern(x, y, big) {
    lanterns.push({ x: x, y: y, vy: -rnd(18, 36), ph: rnd(0, 6.28), s: (big ? rnd(22, 34) : rnd(14, 26)), c: pick(LCOL), a: 0, life: 0 });
  }
  function drawLanterns(now, dt) {
    if (now > nextLan && (scene === 'gate' || scene === 'intro' || scene === 'finale') && lanterns.length < 22) {
      addLantern(rnd(0, W), H + 30, false); nextLan = now + (scene === 'finale' ? 900 : 1500);
    }
    for (var i = lanterns.length - 1; i >= 0; i--) {
      var l = lanterns[i]; l.life += dt; l.y += l.vy * dt; l.a = Math.min(1, l.life * 0.8);
      if (l.y < -70) { lanterns.splice(i, 1); continue; }
      var x = l.x + Math.sin(now / 1300 + l.ph) * 10, y = l.y, w = l.s, h = l.s * 1.3, c = l.c;
      var g = ctx.createRadialGradient(x, y, 0, x, y, w * 2.8);
      g.addColorStop(0, rgba(c, 0.38 * l.a)); g.addColorStop(1, rgba(c, 0));
      ctx.fillStyle = g; ctx.beginPath(); ctx.arc(x, y, w * 2.8, 0, TAU); ctx.fill();
      var bg = ctx.createLinearGradient(0, y - h / 2, 0, y + h / 2);
      bg.addColorStop(0, rgba([Math.min(255, c[0] + 20), Math.min(255, c[1] + 30), Math.min(255, c[2] + 40)], 0.95 * l.a));
      bg.addColorStop(1, rgba(c, 0.95 * l.a));
      ctx.fillStyle = bg; rr(x - w / 2, y - h / 2, w, h, w * 0.3); ctx.fill();
      ctx.fillStyle = 'rgba(255,255,230,' + 0.5 * l.a + ')'; ell(x, y + h * 0.05, w * 0.22, h * 0.3);
      ctx.strokeStyle = 'rgba(120,70,20,' + 0.35 * l.a + ')'; ctx.lineWidth = 1;
      ctx.beginPath(); ctx.moveTo(x - w * 0.17, y - h / 2); ctx.lineTo(x - w * 0.17, y + h / 2);
      ctx.moveTo(x + w * 0.17, y - h / 2); ctx.lineTo(x + w * 0.17, y + h / 2); ctx.stroke();
      ctx.fillStyle = 'rgba(60,35,10,' + l.a + ')'; ctx.fillRect(x - w * 0.5, y - h / 2 - 2, w, 3); ctx.fillRect(x - w * 0.5, y + h / 2 - 1, w, 3);
    }
  }

  /* ---------- petals ---------- */
  function addPetals(n, top) {
    for (var i = 0; i < n; i++) petals.push({
      x: rnd(0, W), y: top ? rnd(-160, -8) : rnd(0, H * 0.3), vy: rnd(40, 110), vx: rnd(-16, 16), rot: rnd(0, 6.28),
      vr: rnd(-1.6, 1.6), size: rnd(8, 15), hue: pick([150, 140, 160, 150, 335, 48]), ph: rnd(0, 6.28)
    });
  }
  function drawPetals(now, dt) {
    if (!RM && now > nextPetal && (scene === 'garden' || scene === 'letter' || scene === 'finale') && petals.length < 16) {
      addPetals(1, true); nextPetal = now + 1000;
    }
    for (var i = petals.length - 1; i >= 0; i--) {
      var p = petals[i];
      p.y += p.vy * dt; p.x += p.vx * dt + Math.sin(now / 700 + p.ph) * 0.4; p.rot += p.vr * dt;
      if (p.y > H + 20) { petals.splice(i, 1); continue; }
      ctx.save(); ctx.translate(p.x, p.y); ctx.rotate(p.rot);
      ctx.fillStyle = hsla(p.hue, 75, 84, 0.88); petal(p.size, p.size * 0.45, true); ctx.fill(); ctx.restore();
    }
  }

  /* ---------- flowers ---------- */
  var TYPES = ['tulip', 'rose', 'daisy', 'blossom', 'tulip', 'rose', 'blossom'];
  var LOOKS = {
    tulip: [[150, 62, 56], [140, 56, 62], [100, 62, 60], [168, 60, 56], [335, 85, 76]],
    rose: [[145, 52, 50], [160, 56, 54], [110, 48, 52], [338, 72, 72]],
    daisy: [[150, 40, 96], [90, 72, 72], [150, 40, 96]],
    blossom: [[150, 60, 86], [140, 50, 90], [335, 80, 88], [160, 55, 84]]
  };
  function addFlower(fx, hf, delay, t) {
    if (flowers.length >= CAP) flowers.splice(BASE, 1);
    var type = pick(TYPES), look = pick(LOOKS[type]);
    flowers.push({ fx: fx, hf: hf, type: type, hue: look[0], sat: look[1], light: look[2], delay: delay, t0: t, ph: rnd(0, 6.28), lean: rnd(-46, 46), rs: rnd(0.85, 1.15) });
  }
  function headTulip(f, s) {
    var sides = [-1, 1];
    for (var i = 0; i < 2; i++) {
      ctx.save(); ctx.rotate(sides[i] * 0.36);
      ctx.fillStyle = hsla(f.hue, f.sat, f.light - 7); petal(s * 1.3, s * 0.58, true); ctx.fill();
      ctx.strokeStyle = hsla(f.hue, f.sat, f.light - 32, 0.45); ctx.lineWidth = 1.2; ctx.stroke(); ctx.restore();
    }
    ctx.fillStyle = hsla(f.hue, f.sat, f.light + 4); petal(s * 1.38, s * 0.52, true); ctx.fill();
    ctx.strokeStyle = hsla(f.hue, f.sat, f.light - 32, 0.45); ctx.lineWidth = 1.2; ctx.stroke();
    ctx.fillStyle = hsla(f.hue, f.sat, f.light + 24, 0.4);
    ctx.save(); ctx.translate(-s * 0.1, 0); petal(s, s * 0.12, false); ctx.fill(); ctx.restore();
  }
  function headRose(f, s) {
    var counts = [7, 6, 5, 4];
    for (var i = 0; i < 4; i++) {
      var n = counts[i], len = s * (1.05 - i * 0.2), wid = s * (0.58 - i * 0.09);
      for (var k = 0; k < n; k++) {
        ctx.save(); ctx.rotate(k * TAU / n + i * 0.62);
        ctx.fillStyle = hsla(f.hue, f.sat, f.light - i * 6); petal(len, wid, true); ctx.fill();
        ctx.strokeStyle = hsla(f.hue, f.sat, f.light - 30, 0.4); ctx.lineWidth = 1.1; ctx.stroke(); ctx.restore();
      }
    }
    ctx.fillStyle = hsla(f.hue, f.sat, f.light - 26); ctx.beginPath(); ctx.arc(0, 0, s * 0.13, 0, TAU); ctx.fill();
  }
  function headDaisy(f, s) {
    for (var k = 0; k < 15; k++) {
      ctx.save(); ctx.rotate(k * TAU / 15);
      ctx.fillStyle = hsla(f.hue, f.sat, f.light); petal(s * 1.1, s * 0.17, false); ctx.fill();
      ctx.strokeStyle = hsla(f.hue, 45, 45, 0.35); ctx.lineWidth = 0.9; ctx.stroke(); ctx.restore();
    }
    ctx.fillStyle = 'hsl(45,100%,60%)'; ctx.beginPath(); ctx.arc(0, 0, s * 0.3, 0, TAU); ctx.fill();
    ctx.strokeStyle = 'hsl(32,80%,40%)'; ctx.lineWidth = 1.4; ctx.stroke();
  }
  function headBlossom(f, s) {
    for (var k = 0; k < 5; k++) {
      ctx.save(); ctx.rotate(k * TAU / 5);
      ctx.fillStyle = hsla(f.hue, f.sat, f.light); petal(s, s * 0.52, true); ctx.fill();
      ctx.strokeStyle = hsla(f.hue, f.sat, f.light - 30, 0.5); ctx.lineWidth = 1.1; ctx.stroke(); ctx.restore();
    }
    ctx.strokeStyle = 'hsla(45,90%,60%,0.9)'; ctx.lineWidth = 1.2; ctx.fillStyle = 'hsl(45,95%,62%)';
    for (var j = 0; j < 8; j++) {
      var a = j * TAU / 8, ex = Math.cos(a) * s * 0.32, ey = Math.sin(a) * s * 0.32;
      ctx.beginPath(); ctx.moveTo(0, 0); ctx.lineTo(ex, ey); ctx.stroke();
      ctx.beginPath(); ctx.arc(ex, ey, s * 0.05, 0, TAU); ctx.fill();
    }
    ctx.beginPath(); ctx.arc(0, 0, s * 0.12, 0, TAU); ctx.fill();
  }
  function drawFlower(f, now) {
    if (!RM && now - f.t0 < f.delay) return;
    var p = RM ? 1 : clamp((now - f.t0 - f.delay) / 2600, 0, 1);
    var x = f.fx * W, y = groundY(x) + 10, h = f.hf * maxH;
    var sp = easeOut(clamp(p / 0.62, 0, 1)), bp = clamp((p - 0.5) / 0.5, 0, 1), bs = bp > 0 ? easeBack(bp) : 0;
    var sway = RM ? 0 : Math.sin(now / 1100 + f.ph) * 5 * sp;
    var tx = x + f.lean * sp + sway, ty = y - h * sp, cx = x - f.lean * 0.25 * sp + sway * 0.3, cy = y - h * sp * 0.55;
    ctx.strokeStyle = 'hsl(168,48%,26%)'; ctx.lineWidth = 3.4; ctx.lineCap = 'round';
    ctx.beginPath(); ctx.moveTo(x, y); ctx.quadraticCurveTo(cx, cy, tx, ty); ctx.stroke();
    var ts = [0.22, 0.45];
    for (var li = 0; li < 2; li++) {
      var start = 0.25 + li * 0.15;
      if (sp <= start) continue;
      var lp = clamp((sp - start) / 0.4, 0, 1), t = ts[li], u = 1 - t;
      var bx = u * u * x + 2 * u * t * cx + t * t * tx, by = u * u * y + 2 * u * t * cy + t * t * ty;
      for (var d = -1; d <= 1; d += 2) {
        ctx.save(); ctx.translate(bx, by); ctx.rotate(d * (1.15 + li * 0.15));
        ctx.fillStyle = li ? 'hsl(158,48%,28%)' : 'hsl(162,50%,22%)';
        petal((li ? 34 : 28) * lp * f.rs, 9 * lp, false); ctx.fill(); ctx.restore();
      }
    }
    if (bs <= 0) return;
    var r = clamp(18 + f.hf * maxH * 0.1, 22, 44) * f.rs, s = r * bs;
    var ang = Math.atan2(tx - cx, -(ty - cy));
    ctx.save(); ctx.translate(tx, ty); ctx.rotate(ang * 0.7);
    var g = ctx.createRadialGradient(0, -s * 0.4, 0, 0, -s * 0.4, s * 1.9);
    g.addColorStop(0, hsla(f.hue, 90, 70, 0.3)); g.addColorStop(1, hsla(f.hue, 90, 70, 0));
    ctx.fillStyle = g; ctx.beginPath(); ctx.arc(0, -s * 0.4, s * 1.9, 0, TAU); ctx.fill();
    if (f.type === 'tulip') headTulip(f, s);
    else {
      ctx.translate(0, -s * 0.45);
      if (f.type === 'rose') headRose(f, s); else if (f.type === 'daisy') headDaisy(f, s); else headBlossom(f, s);
    }
    ctx.restore();
  }

  /* ---------- cake ---------- */
  var SPR = []; for (var q = 0; q < 16; q++) SPR.push([((q * 53) % 100) / 100, ((q * 29) % 100) / 100, q % 3]);
  function drawFlame(x, y, size, lean, now, lit) {
    if (lit < 0.03) return;
    var fl = Math.sin(now / 55 + x) * 0.5 + Math.sin(now / 31 + x * 2) * 0.5;
    var h = 26 * size * lit * (1 + fl * 0.12 - lean * 0.3), w = 9 * size * lit * (1 - lean * 0.25);
    ctx.save(); ctx.translate(x, y); ctx.rotate(lean * 1.1 + fl * 0.05 * (1 + lean * 4));
    var g = ctx.createLinearGradient(0, 0, 0, -h);
    g.addColorStop(0, 'rgba(255,140,40,0.95)'); g.addColorStop(0.55, 'rgba(255,200,70,0.97)'); g.addColorStop(1, 'rgba(255,245,170,0.9)');
    ctx.fillStyle = g; ctx.beginPath(); ctx.moveTo(0, 0);
    ctx.bezierCurveTo(w, -h * 0.3, w * 0.7, -h * 0.8, 0, -h); ctx.bezierCurveTo(-w * 0.7, -h * 0.8, -w, -h * 0.3, 0, 0); ctx.fill();
    ctx.fillStyle = 'rgba(255,255,255,0.9)'; ctx.beginPath(); ctx.moveTo(0, 0);
    ctx.bezierCurveTo(w * 0.4, -h * 0.15, w * 0.3, -h * 0.4, 0, -h * 0.5); ctx.bezierCurveTo(-w * 0.3, -h * 0.4, -w * 0.4, -h * 0.15, 0, 0); ctx.fill();
    ctx.restore();
  }
  function drawCake(now, t, dt) {
    var s = clamp(Math.min(W / 430, H / 800), 0.62, 1.35), cx = W / 2, ty = H * 0.8, i;
    ctx.globalCompositeOperation = 'lighter';
    for (i = 0; i < bokeh.length; i++) {
      var b = bokeh[i], bx = b.fx * W + (RM ? 0 : Math.sin(now / 3000 + b.ph) * 14), by = b.fy * H + (RM ? 0 : Math.cos(now / 3500 + b.ph) * 10);
      var bg = ctx.createRadialGradient(bx, by, 0, bx, by, b.r);
      bg.addColorStop(0, hsla(b.h, 80, 70, 0.22)); bg.addColorStop(1, hsla(b.h, 80, 70, 0));
      ctx.fillStyle = bg; ctx.beginPath(); ctx.arc(bx, by, b.r, 0, TAU); ctx.fill();
    }
    ctx.globalCompositeOperation = 'source-over';
    var tg = ctx.createLinearGradient(0, ty, 0, H); tg.addColorStop(0, '#0f3a36'); tg.addColorStop(1, '#071f1d');
    ctx.fillStyle = tg; ctx.fillRect(0, ty, W, H - ty);
    ctx.fillStyle = 'rgba(168,245,204,0.2)'; ctx.fillRect(0, ty, W, 2);
    ctx.fillStyle = '#9fd8bf'; ell(cx, ty + 2 * s, 180 * s, 16 * s);
    ctx.fillStyle = '#effff7'; ell(cx, ty - 2 * s, 172 * s, 13 * s);
    var b1w = 260 * s, b1h = 76 * s, b1x = cx - b1w / 2, b1y = ty - b1h - 6 * s;
    var g1 = ctx.createLinearGradient(0, b1y, 0, b1y + b1h); g1.addColorStop(0, '#bff5d6'); g1.addColorStop(1, '#6fd6a4');
    ctx.fillStyle = g1; rr(b1x, b1y, b1w, b1h, 14 * s); ctx.fill();
    ctx.fillStyle = '#e2fdee'; rr(b1x, b1y, b1w, 20 * s, 10 * s); ctx.fill();
    for (i = 0; i < 9; i++) {
      var dx = b1x + 16 * s + i * (b1w - 32 * s) / 8, dl = (8 + ((i * 7) % 4) * 6) * s;
      ctx.fillRect(dx - 6 * s, b1y + 12 * s, 12 * s, dl); ctx.beginPath(); ctx.arc(dx, b1y + 12 * s + dl, 6 * s, 0, TAU); ctx.fill();
    }
    var b2w = 180 * s, b2h = 62 * s, b2x = cx - b2w / 2, b2y = b1y - b2h + 4 * s;
    var g2 = ctx.createLinearGradient(0, b2y, 0, b2y + b2h); g2.addColorStop(0, '#ffe9f2'); g2.addColorStop(1, '#ffb9d4');
    ctx.fillStyle = g2; rr(b2x, b2y, b2w, b2h, 12 * s); ctx.fill();
    ctx.fillStyle = '#fff6fa'; rr(b2x, b2y, b2w, 18 * s, 9 * s); ctx.fill();
    for (i = 0; i < 7; i++) {
      var ex = b2x + 14 * s + i * (b2w - 28 * s) / 6, el = (7 + ((i * 5) % 3) * 6) * s;
      ctx.fillRect(ex - 5 * s, b2y + 10 * s, 10 * s, el); ctx.beginPath(); ctx.arc(ex, b2y + 10 * s + el, 5 * s, 0, TAU); ctx.fill();
    }
    var sc = ['#7ee8a8', '#fff', '#ffd86b'];
    for (i = 0; i < SPR.length; i++) { ctx.fillStyle = sc[SPR[i][2]]; ctx.fillRect(b2x + 12 * s + SPR[i][0] * (b2w - 24 * s), b2y + 30 * s + SPR[i][1] * (b2h - 40 * s), 4 * s, 4 * s); }
    var bxs = [-(b2w / 2 + 22 * s), -(b2w / 2 + 52 * s), (b2w / 2 + 22 * s), (b2w / 2 + 52 * s)];
    for (i = 0; i < 4; i++) {
      var sx = cx + bxs[i], sy = b1y + 2 * s;
      ctx.fillStyle = '#ff4f6d'; ctx.beginPath(); ctx.arc(sx, sy - 4 * s, 11 * s, 0, TAU); ctx.fill();
      ctx.fillStyle = '#2f9a74'; ctx.fillRect(sx - 7 * s, sy - 16 * s, 14 * s, 4 * s);
      ctx.fillStyle = '#ffd1d9'; ctx.fillRect(sx - 4 * s, sy - 5 * s, 2 * s, 2 * s); ctx.fillRect(sx + 3 * s, sy - 1 * s, 2 * s, 2 * s);
    }
    var fxs = [-96, 0, 96];
    for (i = 0; i < 3; i++) {
      ctx.save(); ctx.translate(cx + fxs[i] * s, b1y + 50 * s);
      ctx.fillStyle = '#ffb3d1'; for (var k = 0; k < 5; k++) { ctx.save(); ctx.rotate(k * TAU / 5); petal(11 * s, 6 * s, true); ctx.fill(); ctx.restore(); }
      ctx.fillStyle = '#ffd86b'; ctx.beginPath(); ctx.arc(0, 0, 3.2 * s, 0, TAU); ctx.fill(); ctx.restore();
    }
    var topY = b2y, x1 = cx - 38 * s, x8 = cx + 40 * s;
    ctx.fillStyle = '#6fe0a0'; rr(x1 - 9 * s, topY - 84 * s, 18 * s, 84 * s, 6 * s); ctx.fill();
    ctx.beginPath(); ctx.moveTo(x1 - 9 * s, topY - 84 * s); ctx.lineTo(x1 - 26 * s, topY - 68 * s); ctx.lineTo(x1 - 9 * s, topY - 60 * s); ctx.closePath(); ctx.fill();
    ctx.fillStyle = '#e9fff3'; for (i = 0; i < 4; i++) ctx.fillRect(x1 - 3 * s, topY - 74 * s + i * 18 * s, 6 * s, 5 * s);
    ctx.lineCap = 'round'; ctx.strokeStyle = '#ff9ec6'; ctx.lineWidth = 11 * s;
    ctx.beginPath(); ctx.arc(x8, topY - 62 * s, 15 * s, 0, TAU); ctx.stroke();
    ctx.beginPath(); ctx.arc(x8, topY - 24 * s, 21 * s, 0, TAU); ctx.stroke();
    ctx.strokeStyle = 'rgba(255,255,255,0.45)'; ctx.lineWidth = 3 * s;
    ctx.beginPath(); ctx.arc(x8, topY - 62 * s, 15 * s, 3.6, 5); ctx.stroke(); ctx.beginPath(); ctx.arc(x8, topY - 24 * s, 21 * s, 3.6, 5); ctx.stroke();
    ctx.strokeStyle = '#3a2a2a'; ctx.lineWidth = 2 * s;
    ctx.beginPath(); ctx.moveTo(x1, topY - 84 * s); ctx.lineTo(x1, topY - 91 * s); ctx.moveTo(x8, topY - 77 * s); ctx.lineTo(x8, topY - 91 * s); ctx.stroke();

    var lean = cake.p * 0.9;
    if (cake.lit > 0.03) {
      ctx.globalCompositeOperation = 'lighter';
      var fp = [x1, x8];
      for (i = 0; i < 2; i++) {
        var gg = ctx.createRadialGradient(fp[i], topY - 100 * s, 0, fp[i], topY - 100 * s, 230 * s);
        gg.addColorStop(0, 'rgba(255,190,90,' + (0.34 * cake.lit) + ')'); gg.addColorStop(1, 'rgba(255,190,90,0)');
        ctx.fillStyle = gg; ctx.beginPath(); ctx.arc(fp[i], topY - 100 * s, 230 * s, 0, TAU); ctx.fill();
      }
      ctx.globalCompositeOperation = 'source-over';
    }
    drawFlame(x1, topY - 91 * s, s, lean, now, cake.lit);
    drawFlame(x8, topY - 91 * s, s, lean, now, cake.lit);

    if (cake.out) {
      var since = (now - cake.outT) / 1000;
      var dark = 0.55 * (1 - cake.lit) * (1 - clamp(since / 4, 0, 1) * 0.85);
      if (dark > 0.01) { ctx.fillStyle = 'rgba(2,10,14,' + dark + ')'; ctx.fillRect(0, 0, W, H); }
    }
    cake.pos = [{ x: x1, y: topY - 94 * s }, { x: x8, y: topY - 94 * s }];
  }

  /* ---------- particles (confetti, sparks, smoke, glows) ---------- */
  var CONF = ['168,255,200', '201,255,107', '255,216,107', '255,143,192', '255,255,255', '90,230,170'];
  function confetti() {
    for (var i = 0; i < (RM ? 40 : 120); i++) parts.push({ k: 'c', x: rnd(0, W), y: rnd(-140, 0), vx: rnd(-40, 40), vy: rnd(160, 380), life: 0, max: rnd(2, 3.4), w: rnd(6, 12), hh: rnd(10, 18), rot: rnd(0, 6), vr: rnd(-8, 8), c: pick(CONF) });
  }
  function drawParts(dt) {
    for (var i = parts.length - 1; i >= 0; i--) {
      var p = parts[i]; p.life += dt;
      if (p.life < 0) continue;
      if (p.life >= p.max) { parts.splice(i, 1); continue; }
      p.x += (p.vx || 0) * dt; p.y += (p.vy || 0) * dt;
      var a = 1 - p.life / p.max;
      if (p.k === 'c') {
        p.rot += p.vr * dt; ctx.save(); ctx.translate(p.x, p.y); ctx.rotate(p.rot);
        ctx.fillStyle = 'rgba(' + p.c + ',' + Math.min(1, a * 2) + ')'; ctx.fillRect(-p.w / 2, -p.hh / 2, p.w, p.hh); ctx.restore();
      } else if (p.k === 'm') {
        var r = p.r + p.life * 22; ctx.fillStyle = 'rgba(210,225,220,' + (a * 0.22) + ')';
        ctx.beginPath(); ctx.arc(p.x + Math.sin(p.life * 3 + p.ph) * 5, p.y, r, 0, TAU); ctx.fill();
      } else if (p.k === 's') {
        ctx.fillStyle = 'rgba(' + p.c + ',' + a + ')'; spark(p.x, p.y, p.r * (0.4 + a * 0.8)); ctx.fill();
      } else if (p.k === 'g') {
        ctx.globalCompositeOperation = 'lighter';
        var gr = ctx.createRadialGradient(p.x, p.y, 0, p.x, p.y, p.r);
        gr.addColorStop(0, rgba(p.cc, 0.35 * a)); gr.addColorStop(1, rgba(p.cc, 0));
        ctx.fillStyle = gr; ctx.beginPath(); ctx.arc(p.x, p.y, p.r, 0, TAU); ctx.fill();
        ctx.globalCompositeOperation = 'source-over';
      }
    }
  }
  function smoke() {
    if (!cake.pos) return;
    for (var k = 0; k < cake.pos.length; k++) for (var i = 0; i < 8; i++)
      parts.push({ k: 'm', x: cake.pos[k].x + rnd(-3, 3), y: cake.pos[k].y, vx: rnd(-8, 8), vy: -rnd(28, 60), life: -i * 0.07, max: rnd(1.6, 2.6), r: rnd(3, 6), ph: rnd(0, 6) });
  }

  /* ---------- fireworks ---------- */
  var FWC = [[168, 255, 200], [201, 255, 107], [255, 216, 107], [255, 143, 192], [255, 255, 255], [90, 230, 170], [120, 220, 255]];
  function launch(tx, ty) {
    fws.push({ sx: tx + rnd(-70, 70), sy: H + 10, tx: tx, ty: ty, t: 0, dur: rnd(0.75, 1.05), c: pick(FWC), kind: pick(['peony', 'ring', 'heart', 'peony', 'willow']) });
    whistle();
  }
  function explode(f) {
    boom();
    parts.push({ k: 'g', x: f.tx, y: f.ty, r: 260, life: 0, max: 0.55, cc: f.c });
    var n, i, a, v, c2 = pick(FWC);
    if (f.kind === 'heart') {
      n = 64;
      for (i = 0; i < n; i++) {
        var u = i / n * TAU, hx = 16 * Math.pow(Math.sin(u), 3), hy = -(13 * Math.cos(u) - 5 * Math.cos(2 * u) - 2 * Math.cos(3 * u) - Math.cos(4 * u));
        fparts.push({ x: f.tx, y: f.ty, vx: hx * 8.5, vy: hy * 8.5, life: 0, max: rnd(1.3, 1.8), c: [255, 143, 192], g: 40, d: 0.985 });
      }
      return;
    }
    n = f.kind === 'ring' ? 54 : 72;
    for (i = 0; i < n; i++) {
      a = i / n * TAU + rnd(-0.05, 0.05);
      v = f.kind === 'ring' ? 150 + rnd(-8, 8) : rnd(40, 200);
      if (f.kind === 'willow') v = rnd(30, 150);
      fparts.push({ x: f.tx, y: f.ty, vx: Math.cos(a) * v, vy: Math.sin(a) * v, life: 0, max: f.kind === 'willow' ? rnd(1.8, 2.6) : rnd(1.1, 1.7), c: (i % 5 === 0) ? c2 : f.c, g: f.kind === 'willow' ? 90 : 60, d: 0.984 });
    }
  }
  function drawFireworks(dt) {
    var i;
    for (i = fws.length - 1; i >= 0; i--) {
      var f = fws[i]; f.t += dt; var p = f.t / f.dur;
      if (p >= 1) { explode(f); fws.splice(i, 1); continue; }
      var e = easeOut(p), x = lerp(f.sx, f.tx, e), y = lerp(f.sy, f.ty, e);
      ctx.fillStyle = 'rgba(255,240,200,0.95)'; ctx.beginPath(); ctx.arc(x, y, 2.4, 0, TAU); ctx.fill();
      parts.push({ k: 's', x: x + rnd(-2, 2), y: y + rnd(0, 6), vx: rnd(-8, 8), vy: rnd(10, 30), life: 0, max: 0.4, r: rnd(2, 4), c: '255,220,150' });
    }
    ctx.lineCap = 'round';
    for (i = fparts.length - 1; i >= 0; i--) {
      var q = fparts[i]; q.life += dt;
      if (q.life >= q.max) { fparts.splice(i, 1); continue; }
      var px = q.x, py = q.y;
      q.vx *= Math.pow(q.d, dt * 60); q.vy = q.vy * Math.pow(q.d, dt * 60) + q.g * dt;
      q.x += q.vx * dt; q.y += q.vy * dt;
      var a = 1 - q.life / q.max;
      ctx.strokeStyle = rgba(q.c, a); ctx.lineWidth = 2.2 * (0.5 + a * 0.6);
      ctx.beginPath(); ctx.moveTo(px, py); ctx.lineTo(q.x, q.y); ctx.stroke();
      ctx.fillStyle = rgba(q.c, a); ctx.beginPath(); ctx.arc(q.x, q.y, 1.6 * a + 0.6, 0, TAU); ctx.fill();
    }
  }

  /* ---------- the "18" constellation ---------- */
  function buildConst() {
    var fs = clamp(Math.min(W * 0.5, H * 0.26), 110, 300), oc = document.createElement('canvas');
    oc.width = Math.ceil(fs * 1.5); oc.height = Math.ceil(fs * 1.2);
    var o = oc.getContext('2d');
    o.font = '900 ' + fs + 'px "Arial Black", Impact, sans-serif'; o.textAlign = 'center'; o.textBaseline = 'middle'; o.fillStyle = '#fff';
    o.fillText('18', oc.width / 2, oc.height / 2);
    var d = o.getImageData(0, 0, oc.width, oc.height).data, g = Math.max(9, Math.round(fs / 13));
    function A(x, y) { if (x < 0 || y < 0 || x >= oc.width || y >= oc.height) return 0; return d[((y | 0) * oc.width + (x | 0)) * 4 + 3]; }
    var pts = [], ox = W / 2 - oc.width / 2, oy = H * 0.44 - oc.height / 2;
    for (var y = 0; y < oc.height; y += g) for (var x = 0; x < oc.width; x += g) {
      if (A(x, y) > 140 && (A(x - g, y) < 140 || A(x + g, y) < 140 || A(x, y - g) < 140 || A(x, y + g) < 140))
        pts.push({ tx: ox + x, ty: oy + y, sx: rnd(0, W), sy: rnd(0, H * 0.6), d: rnd(0, 1.2), ph: rnd(0, 6.28), big: Math.random() < 0.25 });
    }
    var edges = [];
    for (var i = 0; i < pts.length; i++) for (var j = i + 1; j < pts.length; j++) {
      var dx = pts[i].tx - pts[j].tx, dy = pts[i].ty - pts[j].ty;
      if (dx * dx + dy * dy < g * g * 2.2) edges.push([i, j]);
    }
    cons = { pts: pts, edges: edges };
  }
  function drawCons(now, t) {
    if (!cons) return;
    var lineA = clamp((t - 4.2) / 1.5, 0, 1), i;
    if (lineA > 0) {
      ctx.strokeStyle = 'rgba(168,245,204,' + (0.38 * lineA) + ')'; ctx.lineWidth = 1; ctx.beginPath();
      for (i = 0; i < cons.edges.length; i++) {
        var a = cons.pts[cons.edges[i][0]], b = cons.pts[cons.edges[i][1]];
        ctx.moveTo(a.tx, a.ty); ctx.lineTo(b.tx, b.ty);
      }
      ctx.stroke();
    }
    for (i = 0; i < cons.pts.length; i++) {
      var p = cons.pts[i], pr = clamp((t - 0.8 - p.d) / 2.2, 0, 1), e = easeOut(pr);
      if (pr <= 0) continue;
      var x = lerp(p.sx, p.tx, e), y = lerp(p.sy, p.ty, e), tw = RM ? 1 : 0.65 + 0.35 * Math.sin(now / 500 + p.ph), r = (p.big ? 6.5 : 4.2) * tw;
      var gl = ctx.createRadialGradient(x, y, 0, x, y, r * 3);
      gl.addColorStop(0, 'rgba(201,255,107,0.35)'); gl.addColorStop(1, 'rgba(201,255,107,0)');
      ctx.fillStyle = gl; ctx.beginPath(); ctx.arc(x, y, r * 3, 0, TAU); ctx.fill();
      ctx.fillStyle = '#f4fff8'; spark(x, y, r); ctx.fill();
    }
  }

  /* ================= scenes ================= */
  var SCN = ['gate', 'intro', 'cake', 'garden', 'letter', 'finale'];
  var SKY = { gate: 0, intro: 0, cake: 0, garden: 0.3, letter: 0.2, finale: 1 };
  var LVL = { gate: 1, intro: 1, cake: 0, garden: 2, letter: 2, finale: 3 };
  var fade = $('fade');

  function sub(text) {
    var el = $('sub'); el.textContent = text; el.classList.remove('pop'); void el.offsetWidth; if (text) el.classList.add('pop');
  }
  function enter(name) {
    scene = name; sceneT0 = performance.now(); evs = {};
    SCN.forEach(function (n) { $('s-' + n).classList.toggle('on', n === name); });
    $('hud').hidden = name === 'gate';
    var di = $('dots').children, idx = SCN.indexOf(name) - 1;
    for (var i = 0; i < di.length; i++) di[i].className = i <= idx ? 'on' : '';
    skyTarget = SKY[name]; setLevel(LVL[name]);
    fws.length = 0; fparts.length = 0; if (name !== 'finale') cons = null;
    if (name === 'intro') { sub(''); lanterns.length = 0; for (var k = 0; k < 6; k++) addLantern(rnd(0, W), rnd(H * 0.3, H), false); }
    if (name === 'cake') {
      cake.blowing = false; cake.p = 0; cake.lit = 1; cake.out = false; cake.pos = null; parts.length = 0; lanterns.length = 0;
      $('blow').style.display = ''; $('blow').style.setProperty('--p', '0%'); $('wishMsg').classList.remove('show'); $('skipCake').style.display = '';
    }
    if (name === 'garden') {
      flowers.length = 0; petals.length = 0; lanterns.length = 0; var order = [], t0 = performance.now();
      for (var m = 0; m < BASE; m++) order.push(m);
      order.sort(function () { return Math.random() - 0.5; });
      for (var n = 0; n < BASE; n++) addFlower((order[n] + 0.5) / BASE + rnd(-0.014, 0.014), rnd(0.4, 1), 300 + n * 190, t0);
      $('toLetter').classList.remove('show');
    }
    if (name === 'letter') showPage(0);
    if (name === 'finale') { buildConst(); lanterns.length = 0; for (var j = 0; j < 14; j++) addLantern(rnd(0, W), rnd(H * 0.4, H + 60), true); nextFw = performance.now() + 1500; }
  }
  function go(name) {
    if (busy) return; busy = true;
    fade.classList.add('on');
    setTimeout(function () {
      enter(name);
      requestAnimationFrame(function () { fade.classList.remove('on'); });
      setTimeout(function () { busy = false; }, 120);
    }, 750);
  }

  /* ---------- cake interaction ---------- */
  var blowBtn = $('blow');
  function startBlow() { if (cake.out || scene !== 'cake') return; cake.blowing = true; startBlowSnd(); }
  function endBlow() { cake.blowing = false; stopBlowSnd(); }
  blowBtn.addEventListener('pointerdown', function (e) { e.preventDefault(); startBlow(); });
  ['pointerup', 'pointerleave', 'pointercancel'].forEach(function (ev) { blowBtn.addEventListener(ev, endBlow); });
  blowBtn.addEventListener('keydown', function (e) { if ((e.key === ' ' || e.key === 'Enter') && !e.repeat) { e.preventDefault(); startBlow(); } });
  blowBtn.addEventListener('keyup', function (e) { if (e.key === ' ' || e.key === 'Enter') endBlow(); });
  blowBtn.addEventListener('contextmenu', function (e) { e.preventDefault(); });
  function extinguish() {
    cake.out = true; cake.outT = performance.now(); cake.blowing = false; stopBlowSnd();
    smoke();
    if (ac) noiseHit(ac.currentTime, 0.4, 'bandpass', 900, 0.22, 0.7);
    $('blow').style.display = 'none'; $('skipCake').style.display = 'none';
    setTimeout(function () {
      if (scene !== 'cake') return;
      confetti(); sparkleSnd(); $('wishMsg').classList.add('show');
      for (var i = 0; i < 12; i++) addLantern(W * 0.5 + rnd(-W * 0.35, W * 0.35), H * 0.78 + rnd(0, 60), true);
    }, 650);
    setTimeout(function () { if (scene === 'cake') go('garden'); }, 6200);
  }

  /* ---------- the letter ---------- */
  var PAGES = [
    [{ c: 'dear', t: 'Dear Ruweyda,' }, { c: 'cheer', t: 'HAPPY 18TH BIRTHDAYYY!! 🎂💗🌷' }],
    [{ c: 'p', t: 'I genuinely hope this new chapter of your life brings you so much happiness, peace, success, and beautiful memories. May Allah bless you with a life full of barakah, protect you from anything that isn’t meant for you, grant you everything your heart makes dua for, and guide you toward the best things in this dunya and the akhirah. Ameen. 🤍' }],
    [{ c: 'p', t: 'It’s honestly crazy to think you’re turning 18 already. You’re stepping into a whole new chapter of life, and I hope you know how much you deserve to experience all the good things life has to offer. I pray that you continue to grow into the person you want to become, achieve your dreams, and never feel like you’re falling behind in life. Everyone has their own timing, and I hope you always trust yours.' }],
    [{ c: 'p', t: 'I’m grateful for our friendship, and I hope we get to make so many more memories together. I hope that even as we grow older and life gets busier, we never lose the connection we’ve built. I hope we get to look back years from now and laugh about all the little things, remember the moments that meant something to us, and see how far we’ve both come. No matter where life takes us, I genuinely wish you nothing but the best. Happy birthday again, Ruweyda. May Allah make this year better than the last, fill your heart with contentment, and surprise you with blessings you never even knew to ask for. Ameen. 🫶🏽' },
     { c: 'with', t: 'With love,' }, { c: 'sig', t: 'Ramla Ali 💗' }]
  ];
  var segr = (window.Intl && Intl.Segmenter) ? new Intl.Segmenter(undefined, { granularity: 'grapheme' }) : null;
  function seg(s) { return segr ? Array.from(segr.segment(s), function (x) { return x.segment; }) : Array.from(s); }
  var pg = 0, blocks = [], total = 0, typed = 0, shown = -1, lt = $('lt');
  function showPage(i) {
    pg = i; lt.textContent = ''; blocks = []; total = 0;
    PAGES[i].forEach(function (b) {
      var p = document.createElement('p'); p.className = 'b-' + b.c; lt.appendChild(p);
      var sg = seg(b.t); blocks.push({ el: p, sg: sg }); total += sg.length;
    });
    typed = 0; shown = -1; lt.scrollTop = 0; renderTyped(); letterUI();
  }
  function renderTyped() {
    var n = Math.floor(typed);
    if (n === shown) return;
    shown = n; var rem = n;
    blocks.forEach(function (b) { b.el.textContent = b.sg.slice(0, clamp(rem, 0, b.sg.length)).join(''); rem -= b.sg.length; });
    lt.scrollTop = lt.scrollHeight;
  }
  function letterUI() {
    $('pg').textContent = (pg + 1) + ' / ' + PAGES.length;
    $('lnext').textContent = typed < total ? 'Skip typing' : (pg === PAGES.length - 1 ? 'Finish ›' : 'Continue ›');
  }
  function stepType(dt) {
    if (typed >= total) return;
    typed = Math.min(total, typed + dt * (pg === 0 ? 20 : 34));
    renderTyped();
    if (typed >= total) letterUI();
  }
  $('lnext').addEventListener('click', function () {
    if (typed < total) { typed = total; renderTyped(); letterUI(); return; }
    if (pg < PAGES.length - 1) showPage(pg + 1); else go('finale');
  });

  /* ---------- buttons ---------- */
  $('play').addEventListener('click', function () {
    initAudio();
    if (ac && ac.state === 'suspended') ac.resume();
    if (ac && !aTimer) { nextT = ac.currentTime + 0.1; astep = 0; aTimer = setInterval(sched, 40); }
    go('intro');
  });
  $('skipIntro').addEventListener('click', function () { go('cake'); });
  $('skipCake').addEventListener('click', function () { go('garden'); });
  $('toLetter').addEventListener('click', function () { go('letter'); });
  $('fwBtn').addEventListener('click', function () { launch(rnd(W * 0.15, W * 0.85), rnd(H * 0.12, H * 0.4)); });
  $('againLetter').addEventListener('click', function () { go('letter'); });
  $('replay').addEventListener('click', function () { go('intro'); });
  $('snd').addEventListener('click', function () {
    muted = !muted; this.setAttribute('aria-pressed', String(muted)); this.textContent = muted ? 'Sound off' : 'Sound on';
    if (master) master.gain.setTargetAtTime(muted ? 0 : 0.8, ac.currentTime, 0.05);
  });
  cv.addEventListener('pointerdown', function (e) {
    var r = cv.getBoundingClientRect(), x = e.clientX - r.left, y = e.clientY - r.top;
    if (scene === 'garden') addFlower(clamp(x / W, 0.01, 0.99), clamp((groundY(x) - y) / maxH, 0.3, 1), 0, performance.now());
    if (scene === 'finale' && y < H * 0.75) launch(x, y);
  });

  /* ================= main loop ================= */
  function frame(now) {
    if (!W || !H) resize();
    var dt = Math.min(0.05, (now - last) / 1000 || 0); last = now; frameN++;
    var t = (now - sceneT0) / 1000;
    ctx.clearRect(0, 0, W, H);
    drawSky(now, dt);
    if (scene === 'gate' || scene === 'intro' || scene === 'finale') drawSkyline();
    if (scene === 'cake') {
      if (!cake.out) {
        cake.p = clamp(cake.p + (cake.blowing ? dt / 1.2 : -dt / 0.7), 0, 1);
        blowBtn.style.setProperty('--p', Math.round(cake.p * 100) + '%');
        if (cake.snd) cake.snd.g.gain.value = 0.14 * cake.p;
        if (cake.p >= 1) extinguish();
      }
      var target = cake.out ? 0 : 1 - (cake.p > 0.85 ? (cake.p - 0.85) * 3 : 0);
      cake.lit += (target - cake.lit) * Math.min(1, dt * (cake.out ? 9 : 4));
      drawCake(now, t, dt);
    } else {
      hill(-10, '#1d6a55', '#0c2f2a');
      for (var i = 0; i < flowers.length; i++) drawFlower(flowers[i], now);
      hill(6, '#0c332d', '#071f1c');
      drawGrass(now); drawFlies(now);
    }
    drawLanterns(now, dt);
    drawPetals(now, dt);
    if (scene === 'finale') drawCons(now, t);
    drawFireworks(dt);
    drawParts(dt);

    if (scene === 'intro') {
      if (t > 2.6 && !evs.a) { evs.a = 1; sub('Every story has a turning point.'); }
      if (t > 5.6 && !evs.b) { evs.b = 1; sub('Tonight, yours turns eighteen.'); }
      if (t > 8.6 && !evs.c) { evs.c = 1; sub(''); }
      if (t > 9.4 && !evs.d) { evs.d = 1; go('cake'); }
    } else if (scene === 'cake') {
      if (t > 1.3 && !evs.a) { evs.a = 1; playHB(); }
    } else if (scene === 'garden') {
      if (t > 5.5 && !evs.a) { evs.a = 1; $('toLetter').classList.add('show'); }
    } else if (scene === 'letter') {
      stepType(dt);
    } else if (scene === 'finale') {
      if (now > nextFw && t > 1.2) { launch(rnd(W * 0.12, W * 0.88), rnd(H * 0.1, H * 0.42)); nextFw = now + (RM ? 3200 : rnd(1100, 2100)); }
    }
    requestAnimationFrame(frame);
  }

  /* ================= setup ================= */
  function resize() {
    dpr = Math.min(2, window.devicePixelRatio || 1);
    W = app.clientWidth || window.innerWidth; H = app.clientHeight || window.innerHeight;
    cv.width = Math.round(W * dpr); cv.height = Math.round(H * dpr);
    cv.style.width = W + 'px'; cv.style.height = H + 'px';
    ctx.setTransform(dpr, 0, 0, dpr, 0, 0);
    maxH = clamp(H * 0.36, 110, 330);
    au.width = Math.max(40, Math.ceil(W / 5)); au.height = Math.max(40, Math.ceil(H * 0.62 / 5));
    buildSkyline();
    if (scene === 'finale') buildConst();
  }
  var i0;
  for (i0 = 0; i0 < 90; i0++) stars.push({ fx: Math.random(), fy: Math.random() * 0.6, r: rnd(0.6, 1.6), ph: rnd(0, 6.28) });
  for (i0 = 0; i0 < 16; i0++) flies.push({ fx: Math.random(), fy: rnd(0.55, 0.88), ph: rnd(0, 6.28) });
  for (i0 = 0; i0 < 22; i0++) bokeh.push({ fx: Math.random(), fy: rnd(0.05, 0.85), r: rnd(20, 70), ph: rnd(0, 6.28), h: pick([150, 160, 45, 330, 170]) });
  resize();
  window.addEventListener('resize', resize);
  enter('gate');
  requestAnimationFrame(frame);
})();
</script>

</body>
</html>
