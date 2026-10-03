# NEW<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#b9d3c2">
  <meta name="description" content="The wedding invitation of Alina Agha and Karim Ali Khan, November 2026.">
  <title>Alina &amp; Karim | Wedding Invitation</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@400;700&family=Cormorant+Garamond:wght@400;500;600;700&family=Great+Vibes&family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      color-scheme: light;
      --mint: #b9d3c2;
      --mint-deep: #7fa890;
      --emerald: #315d4c;
      --gold: #d4af37;
      --gold-deep: #8f6e1f;
      --cream: #fffdf9;
      --paper: #faf6f0;
      --blush: #f4ded8;
      --ink: #41392f;
      --muted: #786e61;
      --serif: "Cormorant Garamond", Georgia, serif;
      --sans: "Montserrat", sans-serif;
      --decorative: "Cinzel Decorative", Georgia, serif;
      --script: "Great Vibes", cursive;
    }

    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      min-width: 320px;
      color: var(--ink);
      background:
        radial-gradient(ellipse at 12% 14%, rgba(185, 211, 194, .44), transparent 34%),
        radial-gradient(ellipse at 88% 78%, rgba(244, 222, 216, .44), transparent 32%),
        #f5f0e8;
      font-family: var(--serif);
    }

    button, a { -webkit-tap-highlight-color: transparent; }
    button { font: inherit; }
    .invitation-shell {
      width: min(100%, 440px);
      min-height: 100vh;
      margin: 0 auto;
      overflow: hidden;
      background: var(--cream);
      box-shadow: 0 0 54px rgba(63, 54, 41, .18);
      position: relative;
    }

    .hero {
      padding: 56px 24px 40px;
      text-align: center;
      background: linear-gradient(180deg, #f4f0e8 0%, var(--cream) 100%);
      border-bottom: 1px solid rgba(143, 110, 31, .25);
    }
    .crest { color: var(--gold-deep); font-size: 27px; line-height: 1; }
    .bismillah {
      margin: 11px auto 18px;
      color: #716653;
      font-size: 15px;
      font-style: italic;
      line-height: 1.35;
    }
    .eyebrow, .section-kicker, .event-meta, .timer-label, .small-label {
      font-family: var(--sans);
      text-transform: uppercase;
      letter-spacing: .12em;
    }
    .eyebrow { color: var(--gold-deep); font-size: 9px; font-weight: 600; }
    .host-message {
      max-width: 340px;
      margin: 0 auto 20px;
      font-size: 19px;
      line-height: 1.38;
    }
    .host-message strong { font-weight: 700; }
    .bride-name, .groom-name {
      margin: 0;
      color: var(--emerald);
      font-family: var(--script);
      font-size: clamp(48px, 14vw, 66px);
      font-weight: 400;
      line-height: 1.08;
    }
    .parentage {
      margin: 3px 0 0;
      color: var(--muted);
      font-size: 15px;
      font-style: italic;
      line-height: 1.35;
    }
    .with-divider {
      display: flex;
      align-items: center;
      gap: 13px;
      width: min(100%, 250px);
      margin: 17px auto;
      color: var(--gold-deep);
      font-family: var(--script);
      font-size: 30px;
    }
    .with-divider::before, .with-divider::after {
      content: "";
      height: 1px;
      flex: 1;
      background: linear-gradient(90deg, transparent, var(--gold));
    }
    .with-divider::after { transform: scaleX(-1); }
    .footer-quote {
      max-width: 340px;
      margin: 25px auto 0;
      color: #685e51;
      font-size: 18px;
      font-style: italic;
      line-height: 1.35;
    }
    .gold-rule { width: 56px; height: 1px; margin: 24px auto; background: var(--gold); }

    .arch-card {
      position: relative;
      width: calc(100% - 26px);
      margin: 0 auto;
      padding: 14px;
      border: 1px solid var(--gold-deep);
      border-radius: 200px 200px 28px 28px;
      background: var(--paper);
      box-shadow: inset 0 0 0 4px var(--paper), inset 0 0 0 5px rgba(212, 175, 55, .75), 0 9px 22px rgba(71, 59, 42, .11);
    }
    .arch-inner {
      min-height: 650px;
      padding: 112px 19px 26px;
      border: 1px dashed rgba(143, 110, 31, .68);
      border-radius: 190px 190px 19px 19px;
      text-align: center;
    }
    .arch-inner .crest { margin-bottom: 12px; font-size: 31px; }
    .arch-inner .host-message { margin-top: 25px; font-size: 17px; }
    .arch-inner .bride-name, .arch-inner .groom-name { font-size: 55px; }
    .arch-inner .parentage { font-size: 14px; }
    .arch-inner .with-divider { margin: 17px auto; }
    .arch-inner .footer-quote { margin-top: 31px; font-size: 17px; }

    .content-section { padding: 35px 23px; text-align: center; }
    .section-kicker { margin: 0 0 7px; color: var(--gold-deep); font-size: 9px; font-weight: 600; }
    .section-title {
      margin: 0;
      color: var(--emerald);
      font-family: var(--decorative);
      font-size: 21px;
      font-weight: 400;
      line-height: 1.3;
    }
    .scratch-wrap {
      position: relative;
      height: 172px;
      margin: 20px auto 0;
      overflow: hidden;
      border: 1px solid var(--gold-deep);
      border-radius: 8px;
      background: linear-gradient(135deg, #fffaf0, #f7ead1);
      box-shadow: 0 6px 15px rgba(71, 59, 42, .09);
    }
    .scratch-reveal {
      display: grid;
      place-content: center;
      height: 100%;
      padding: 20px;
      color: var(--emerald);
    }
    .scratch-reveal strong { font-family: var(--decorative); font-size: 17px; font-weight: 400; }
    .scratch-reveal span { margin-top: 7px; font-size: 21px; font-style: italic; }
    .scratch-reveal small { margin-top: 5px; color: var(--muted); font-family: var(--sans); font-size: 10px; }
    #scratch-canvas {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      touch-action: none;
      cursor: crosshair;
      transition: opacity .5s ease;
    }
    #scratch-canvas.is-revealed { opacity: 0; pointer-events: none; }

    .countdown-section {
      padding-top: 27px;
      padding-bottom: 34px;
      background: linear-gradient(180deg, #f8f3eb, #fffdf9);
    }
    .countdown-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 8px; margin-top: 17px; }
    .timer-box {
      min-width: 0;
      padding: 12px 3px 10px;
      border: 1px solid rgba(143, 110, 31, .45);
      border-radius: 4px;
      background: rgba(255, 253, 249, .8);
    }
    .timer-value { display: block; color: var(--emerald); font-family: var(--decorative); font-size: 22px; line-height: 1.2; }
    .timer-label { display: block; margin-top: 4px; color: var(--muted); font-size: 8px; }
    .countdown-note { margin: 12px 0 0; color: var(--muted); font-family: var(--sans); font-size: 9px; }

    .events-section { padding-top: 35px; }
    .event-list { display: grid; gap: 13px; margin-top: 19px; text-align: left; }
    .event-card {
      padding: 17px 16px 15px;
      border: 1px solid rgba(143, 110, 31, .38);
      border-left: 3px solid var(--mint-deep);
      border-radius: 5px;
      background: #fffefa;
    }
    .event-meta { color: var(--gold-deep); font-size: 8px; font-weight: 600; line-height: 1.6; }
    .event-card h3 { margin: 5px 0 8px; color: var(--emerald); font-family: var(--decorative); font-size: 15px; font-weight: 400; line-height: 1.35; }
    .event-card p { margin: 4px 0; font-size: 16px; line-height: 1.35; }
    .event-card .venue { color: #51483e; font-weight: 600; }
    .event-actions { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 12px; }
    .event-link {
      display: inline-flex;
      min-height: 34px;
      align-items: center;
      justify-content: center;
      padding: 7px 10px;
      border: 1px solid var(--gold-deep);
      border-radius: 3px;
      color: var(--emerald);
      background: transparent;
      font-family: var(--sans);
      font-size: 9px;
      font-weight: 600;
      text-decoration: none;
      transition: color .2s ease, background .2s ease;
    }
    .event-link:hover, .event-link:focus-visible { color: white; background: var(--emerald); }
    .closing {
      padding: 28px 20px 36px;
      color: #665b4e;
      background: var(--mint);
      text-align: center;
    }
    .closing .couple-signature { margin: 0; color: var(--emerald); font-family: var(--script); font-size: 47px; }
    .closing p:last-child { margin: 5px 0 0; font-family: var(--sans); font-size: 9px; letter-spacing: .12em; text-transform: uppercase; }

    #curtain-wrapper {
      position: fixed;
      z-index: 20;
      inset: 0;
      overflow: hidden;
      background: #214b3c;
      transition: opacity .7s ease 1.05s;
    }
    #curtain-wrapper.is-open { opacity: 0; pointer-events: none; }
    .curtain-panel {
      position: absolute;
      z-index: 1;
      top: 0;
      bottom: 0;
      width: 52%;
      border-right: 2px solid rgba(212, 175, 55, .8);
      border-left: 1px solid rgba(212, 175, 55, .35);
      background:
        repeating-linear-gradient(90deg, rgba(248, 240, 201, .21) 0 2px, transparent 3px 12px, rgba(21, 71, 51, .32) 17px 24px),
        linear-gradient(90deg, #214f3d 0%, #67967a 13%, #a9c8b1 24%, #49795f 37%, #224d3b 49%, #79a487 65%, #2d624a 80%, #8caf96 93%, #294d3d 100%);
      box-shadow: inset -18px 0 24px rgba(16, 48, 35, .28), inset 10px 0 18px rgba(255, 255, 255, .1);
      transition: transform 1.25s cubic-bezier(.76, 0, .18, 1);
    }
    .curtain-panel.left { left: 0; transform-origin: left center; }
    .curtain-panel.right { right: 0; transform-origin: right center; transform: scaleX(-1); }
    #curtain-wrapper.is-open .curtain-panel.left { transform: translateX(-102%) scaleX(.58); }
    #curtain-wrapper.is-open .curtain-panel.right { transform: translateX(102%) scaleX(-.58); }
    .valance {
      position: absolute;
      z-index: 3;
      top: 0;
      left: 0;
      width: 100%;
      height: 112px;
      display: grid;
      place-items: center;
      padding-top: 17px;
      color: #fff4cf;
      background:
        radial-gradient(ellipse at 50% 5%, #edd78d 0%, #bf9a41 35%, transparent 36%) top / 100% 44px no-repeat,
        linear-gradient(180deg, #a78335, #d4af55 24%, #8f6e1f 29%, #d8bd73 35%, #87651d 100%);
      clip-path: polygon(0 0, 100% 0, 100% 75%, 91% 88%, 80% 76%, 68% 91%, 50% 77%, 32% 91%, 20% 76%, 9% 88%, 0 75%);
      box-shadow: 0 7px 18px rgba(21, 42, 31, .35);
      font-family: var(--decorative);
      font-size: 13px;
      letter-spacing: .15em;
      text-shadow: 0 1px 2px #604817;
      transition: transform .9s cubic-bezier(.7, 0, .2, 1);
    }
    #curtain-wrapper.is-open .valance { transform: translateY(-110%); }
    .seal-button {
      position: absolute;
      z-index: 5;
      top: 50%;
      left: 50%;
      display: grid;
      width: 132px;
      height: 132px;
      place-content: center;
      gap: 4px;
      transform: translate(-50%, -50%);
      border: 3px double #f2d886;
      border-radius: 50%;
      outline: 1px solid rgba(246, 224, 155, .65);
      outline-offset: 5px;
      color: #fff4dc;
      background: radial-gradient(circle at 32% 25%, #b97e68, #834b46 60%, #633c3b);
      box-shadow: 0 8px 26px rgba(10, 32, 23, .48), inset 0 0 0 5px rgba(255, 239, 199, .1);
      cursor: pointer;
      animation: seal-pulse 2.3s ease-in-out infinite;
    }
    .seal-monogram { font-family: var(--script); font-size: 51px; line-height: .92; }
    .seal-label { font-family: var(--sans); font-size: 8px; letter-spacing: .13em; text-transform: uppercase; }
    #curtain-wrapper.is-open .seal-button { opacity: 0; transition: opacity .25s ease; pointer-events: none; }
    @keyframes seal-pulse { 0%, 100% { box-shadow: 0 8px 26px rgba(10, 32, 23, .48), 0 0 0 0 rgba(244, 222, 216, .35); } 50% { box-shadow: 0 8px 26px rgba(10, 32, 23, .48), 0 0 0 11px rgba(244, 222, 216, 0); } }

    #petal-canvas { position: fixed; z-index: 8; inset: 0; width: 100%; height: 100%; pointer-events: none; }
    .audio-toggle {
      position: fixed;
      z-index: 10;
      right: max(16px, calc((100vw - 440px) / 2 + 16px));
      bottom: max(16px, env(safe-area-inset-bottom));
      display: grid;
      width: 46px;
      height: 46px;
      place-items: center;
      border: 1px solid #9d7924;
      border-radius: 50%;
      color: #fffdf5;
      background: var(--emerald);
      box-shadow: 0 4px 13px rgba(45, 64, 49, .22);
      font-size: 19px;
      cursor: pointer;
    }
    .audio-toggle:focus-visible, .seal-button:focus-visible { outline: 3px solid #f2d886; outline-offset: 4px; }
    #youtube-player { position: fixed; width: 200px; height: 200px; left: -220px; bottom: 0; overflow: hidden; opacity: 0; pointer-events: none; }

    @media (min-width: 600px) {
      .invitation-shell { margin: 28px auto; min-height: auto; }
      .hero { padding-top: 62px; }
    }
    @media (max-width: 360px) {
      .hero { padding-right: 17px; padding-left: 17px; }
      .content-section { padding-right: 16px; padding-left: 16px; }
      .arch-inner { padding-right: 14px; padding-left: 14px; }
      .timer-value { font-size: 19px; }
      .event-card { padding-right: 12px; padding-left: 12px; }
    }
    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after { scroll-behavior: auto !important; animation-duration: .01ms !important; animation-iteration-count: 1 !important; transition-duration: .01ms !important; }
    }
  </style>
</head>
<body>
  <main class="invitation-shell">
    <section class="hero" aria-labelledby="main-title">
      <div class="arch-card">
        <div class="arch-inner">
          <div class="crest" aria-hidden="true">❀</div>
          <p class="bismillah">In the name of Allah,<br>The Most Beneficent, The Most Merciful</p>
          <p class="eyebrow">Together with their families</p>
          <p class="host-message"><strong>Mrs. &amp; Mr. Muzaffar Nova Agha</strong> feels immense pleasure to have your kind presence at the Wedding Ceremony of their beloved daughter</p>
          <h1 class="bride-name" id="main-title">Alina Agha</h1>
          <p class="parentage">D/o. Mr. Muzaffar Nova Agha<br>and Mrs. Seema Muzaffar Agha</p>
          <div class="with-divider" aria-label="with">with</div>
          <p class="eyebrow">joyfully united with</p>
          <p class="groom-name">Karim Ali Khan</p>
          <p class="parentage">S/o. Mr. Nisar Khan<br>and Mrs. Fatima Bi. Khan</p>
          <div class="gold-rule"></div>
          <p class="footer-quote">Please grace us with your presence and keep us in your sincerest prayers. Your presence, prayers, and blessings will make our celebration truly complete.</p>
        </div>
      </div>
    </section>

    <section class="content-section" aria-labelledby="scratch-title">
      <p class="section-kicker">A little keepsake</p>
      <h2 class="section-title" id="scratch-title">A date to remember</h2>
      <div class="scratch-wrap">
        <div class="scratch-reveal" aria-live="polite">
          <strong>Save The Date</strong>
          <span>13th &amp; 15th November 2026</span>
          <small>Alina &amp; Karim's Wedding</small>
        </div>
        <canvas id="scratch-canvas" aria-label="Scratch the foil to reveal the wedding date"></canvas>
      </div>
    </section>

    <section class="content-section countdown-section" aria-labelledby="countdown-title">
      <p class="section-kicker">The first celebration</p>
      <h2 class="section-title" id="countdown-title">Until the Nikah</h2>
      <div class="countdown-grid" aria-live="off">
        <div class="timer-box"><span class="timer-value" id="days">---</span><span class="timer-label">Days</span></div>
        <div class="timer-box"><span class="timer-value" id="hours">--</span><span class="timer-label">Hours</span></div>
        <div class="timer-box"><span class="timer-value" id="minutes">--</span><span class="timer-label">Mins</span></div>
        <div class="timer-box"><span class="timer-value" id="seconds">--</span><span class="timer-label">Secs</span></div>
      </div>
      <p class="countdown-note">Friday, 13 November 2026 &middot; 8:00 AM</p>
    </section>

    <section class="content-section events-section" aria-labelledby="events-title">
      <p class="section-kicker">Three joyful gatherings</p>
      <h2 class="section-title" id="events-title">Wedding Celebrations</h2>
      <div class="event-list">
        <article class="event-card" data-title="Insha Allah Nikah" data-start="2026-11-13T08:00:00" data-end="2026-11-13T10:00:00" data-location="Nesai Masjid">
          <div class="event-meta">Friday &middot; 13 November 2026 &middot; 3rd Jamad-al-Sani 1448 AH</div>
          <h3>Insha Allah Nikah</h3>
          <p>8:00 AM</p>
          <p class="venue">Nesai Masjid</p>
          <div class="event-actions">
            <a class="event-link map-link" href="https://www.google.com/maps/search/?api=1&amp;query=Nesai+Masjid" target="_blank" rel="noopener">View on Google Maps</a>
            <a class="event-link calendar-link" href="#">Add to Google Calendar</a>
          </div>
        </article>
        <article class="event-card" data-title="Wedding Reception" data-start="2026-11-13T19:00:00" data-end="2026-11-13T23:00:00" data-location="Royal Paradise Hall, Mugali, Madgaon - Goa">
          <div class="event-meta">Friday &middot; 13 November 2026</div>
          <h3>Wedding Reception</h3>
          <p>7:00 PM onwards</p>
          <p class="venue">Royal Paradise Hall, Mugali, Madgaon - Goa</p>
          <div class="event-actions">
            <a class="event-link map-link" href="https://www.google.com/maps/search/?api=1&amp;query=Royal+Paradise+Hall%2C+Mugali%2C+Madgaon%2C+Goa" target="_blank" rel="noopener">View on Google Maps</a>
            <a class="event-link calendar-link" href="#">Add to Google Calendar</a>
          </div>
        </article>
        <article class="event-card" data-title="Walima Ceremony" data-start="2026-11-15T19:00:00" data-end="2026-11-15T23:00:00" data-location="Celebration Open Air, Dhavali Farmagudi Bypass, Opp. VRL Logistics, Ponda - Goa">
          <div class="event-meta">Sunday &middot; 15 November 2026 &middot; 5 Jamad-al-Sani 1448 AH</div>
          <h3>Walima Ceremony</h3>
          <p>7:00 PM onwards</p>
          <p class="venue">Celebration Open Air, Dhavali Farmagudi Bypass, Opp. VRL Logistics, Ponda - Goa</p>
          <div class="event-actions">
            <a class="event-link map-link" href="https://www.google.com/maps/search/?api=1&amp;query=Celebration+Open+Air%2C+Dhavali+Farmagudi+Bypass%2C+Ponda%2C+Goa" target="_blank" rel="noopener">View on Google Maps</a>
            <a class="event-link calendar-link" href="#">Add to Google Calendar</a>
          </div>
        </article>
      </div>
    </section>

    <footer class="closing">
      <p class="couple-signature">Alina &amp; Karim</p>
      <p>With love and gratitude</p>
    </footer>
  </main>

  <canvas id="petal-canvas" aria-hidden="true"></canvas>
  <div id="youtube-player" aria-hidden="true"></div>
  <button class="audio-toggle" id="audio-toggle" type="button" aria-label="Mute music" aria-pressed="false" title="Mute music">🔊</button>

  <div id="curtain-wrapper" role="dialog" aria-modal="true" aria-label="Open the wedding invitation">
    <div class="curtain-panel left" aria-hidden="true"></div>
    <div class="curtain-panel right" aria-hidden="true"></div>
    <div class="valance" aria-hidden="true">BISMILLAH</div>
    <button class="seal-button" id="open-seal" type="button" aria-label="Open the wedding invitation and play music">
      <span class="seal-monogram">AK</span>
      <span class="seal-label">Tap to Open</span>
    </button>
  </div>

  <script>
    (() => {
      const curtain = document.getElementById('curtain-wrapper');
      const openButton = document.getElementById('open-seal');
      const audioButton = document.getElementById('audio-toggle');
      const scratchCanvas = document.getElementById('scratch-canvas');
      const scratchContext = scratchCanvas.getContext('2d');
      const petalCanvas = document.getElementById('petal-canvas');
      const petalContext = petalCanvas.getContext('2d');
      const targetDate = new Date(2026, 10, 13, 8, 0, 0);
      let player;
      let playerReady = false;
      let apiRequested = false;
      let playbackRequested = false;
      let muted = false;

      function updateCountdown() {
        const remaining = Math.max(0, targetDate.getTime() - Date.now());
        const seconds = Math.floor(remaining / 1000);
        document.getElementById('days').textContent = String(Math.floor(seconds / 86400)).padStart(3, '0');
        document.getElementById('hours').textContent = String(Math.floor(seconds % 86400 / 3600)).padStart(2, '0');
        document.getElementById('minutes').textContent = String(Math.floor(seconds % 3600 / 60)).padStart(2, '0');
        document.getElementById('seconds').textContent = String(seconds % 60).padStart(2, '0');
      }
      updateCountdown();
      window.setInterval(updateCountdown, 1000);

      function calendarDate(value) {
        return new Date(value).toISOString().replace(/[-:]/g, '').replace(/\.\d{3}Z$/, 'Z');
      }
      document.querySelectorAll('.event-card').forEach((card) => {
        const title = card.dataset.title;
        const location = card.dataset.location;
        const start = new Date(card.dataset.start);
        const end = new Date(card.dataset.end);
        const calendarUrl = new URL('https://calendar.google.com/calendar/render');
        calendarUrl.search = new URLSearchParams({
          action: 'TEMPLATE',
          text: title,
          dates: `${calendarDate(start)}/${calendarDate(end)}`,
          details: 'Alina Agha and Karim Ali Khan\'s wedding celebration.',
          location
        });
        card.querySelector('.calendar-link').href = calendarUrl.toString();
        card.querySelector('.map-link').href = `https://www.google.com/maps/search/?api=1&query=${encodeURIComponent(location)}`;
      });

      function sizeScratchCanvas() {
        const bounds = scratchCanvas.getBoundingClientRect();
        const ratio = Math.min(window.devicePixelRatio || 1, 2);
        scratchCanvas.width = Math.round(bounds.width * ratio);
        scratchCanvas.height = Math.round(bounds.height * ratio);
        scratchContext.setTransform(ratio, 0, 0, ratio, 0, 0);
        const foil = scratchContext.createLinearGradient(0, 0, bounds.width, bounds.height);
        foil.addColorStop(0, '#719980');
        foil.addColorStop(.34, '#d8c27a');
        foil.addColorStop(.62, '#9bbda5');
        foil.addColorStop(1, '#b89443');
        scratchContext.fillStyle = foil;
        scratchContext.fillRect(0, 0, bounds.width, bounds.height);
        scratchContext.fillStyle = 'rgba(255, 253, 242, .94)';
        scratchContext.font = '600 10px Montserrat, sans-serif';
        scratchContext.textAlign = 'center';
        scratchContext.fillText('\u2728 SWIPE TO REVEAL \u2728', bounds.width / 2, bounds.height / 2 + 4);
      }
      sizeScratchCanvas();
      window.addEventListener('resize', sizeScratchCanvas);

      let scratching = false;
      let scratchedDistance = 0;
      let previousPoint = null;
      function scratchAt(event) {
        const bounds = scratchCanvas.getBoundingClientRect();
        const point = { x: event.clientX - bounds.left, y: event.clientY - bounds.top };
        if (previousPoint) scratchedDistance += Math.hypot(point.x - previousPoint.x, point.y - previousPoint.y);
        previousPoint = point;
        scratchContext.globalCompositeOperation = 'destination-out';
        scratchContext.lineCap = 'round';
        scratchContext.lineJoin = 'round';
        scratchContext.lineWidth = 38;
        scratchContext.beginPath();
        scratchContext.moveTo(point.x, point.y);
        scratchContext.lineTo(point.x + .1, point.y + .1);
        scratchContext.stroke();
        if (scratchedDistance > bounds.width * bounds.height * .12) {
          scratchCanvas.classList.add('is-revealed');
          scratchCanvas.setAttribute('aria-hidden', 'true');
        }
      }
      scratchCanvas.addEventListener('pointerdown', (event) => {
        scratching = true;
        previousPoint = null;
        scratchCanvas.setPointerCapture(event.pointerId);
        scratchAt(event);
      });
      scratchCanvas.addEventListener('pointermove', (event) => { if (scratching) scratchAt(event); });
      const stopScratching = () => { scratching = false; previousPoint = null; };
      scratchCanvas.addEventListener('pointerup', stopScratching);
      scratchCanvas.addEventListener('pointercancel', stopScratching);

      function resizePetalCanvas() {
        const ratio = Math.min(window.devicePixelRatio || 1, 2);
        petalCanvas.width = Math.round(window.innerWidth * ratio);
        petalCanvas.height = Math.round(window.innerHeight * ratio);
        petalContext.setTransform(ratio, 0, 0, ratio, 0, 0);
      }
      resizePetalCanvas();
      window.addEventListener('resize', resizePetalCanvas);
      const petals = [];
      let petalsRunning = false;
      function drawPetals() {
        if (!petalsRunning) return;
        const width = window.innerWidth;
        const height = window.innerHeight;
        petalContext.clearRect(0, 0, width, height);
        if (petals.length < 24 && Math.random() < .2) {
          petals.push({ x: Math.random() * width, y: -12, size: 4 + Math.random() * 5, speed: .55 + Math.random() * 1.15, drift: Math.random() * 1.2 - .6, phase: Math.random() * 6, rotation: Math.random() * Math.PI, spin: (Math.random() - .5) * .035 });
        }
        for (let index = petals.length - 1; index >= 0; index--) {
          const petal = petals[index];
          petal.y += petal.speed;
          petal.phase += .025;
          petal.x += petal.drift + Math.sin(petal.phase) * .55;
          petal.rotation += petal.spin;
          petalContext.save();
          petalContext.translate(petal.x, petal.y);
          petalContext.rotate(petal.rotation);
          petalContext.fillStyle = 'rgba(244, 190, 185, .68)';
          petalContext.beginPath();
          petalContext.ellipse(0, 0, petal.size * .65, petal.size, 0, 0, Math.PI * 2);
          petalContext.fill();
          petalContext.restore();
          if (petal.y > height + 15) petals.splice(index, 1);
        }
        window.requestAnimationFrame(drawPetals);
      }
      function startPetals() {
        if (petalsRunning) return;
        petalsRunning = true;
        drawPetals();
      }

      function loadYouTubePlayer() {
        if (apiRequested) return;
        apiRequested = true;
        window.onYouTubeIframeAPIReady = () => {
          player = new YT.Player('youtube-player', {
            videoId: 'wOtI4wvMwX0',
            playerVars: { autoplay: 1, controls: 0, playsinline: 1, loop: 1, playlist: 'wOtI4wvMwX0' },
            events: {
              onReady: (event) => {
                playerReady = true;
                if (muted) event.target.mute();
                if (playbackRequested) event.target.playVideo();
              }
            }
          });
        };
        const script = document.createElement('script');
        script.src = 'https://www.youtube.com/iframe_api';
        document.head.appendChild(script);
      }
      openButton.addEventListener('click', () => {
        curtain.classList.add('is-open');
        curtain.setAttribute('aria-hidden', 'true');
        playbackRequested = true;
        loadYouTubePlayer();
        if (playerReady) {
          if (muted) player.mute();
          player.playVideo();
        }
        startPetals();
        window.setTimeout(() => curtain.remove(), 1900);
      }, { once: true });
      audioButton.addEventListener('click', () => {
        muted = !muted;
        audioButton.textContent = muted ? '🔇' : '🔊';
        audioButton.setAttribute('aria-label', muted ? 'Unmute music' : 'Mute music');
        audioButton.setAttribute('title', muted ? 'Unmute music' : 'Mute music');
        audioButton.setAttribute('aria-pressed', String(muted));
        if (playerReady) muted ? player.mute() : player.unMute();
      });
    })();
  </script>
</body>
</html>