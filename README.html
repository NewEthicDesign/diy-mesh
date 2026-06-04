<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MESH — How It Works</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Bebas+Neue&family=IBM+Plex+Mono:ital,wght@0,400;0,600;1,400&display=swap');

  :root {
    --ink: #0a0a0a;
    --paper: #f0ebe0;
    --paper2: #e4dece;
    --red: #c0140a;
    --red2: #8a0e06;
    --yellow: #e8c832;
    --muted: #5a5040;
    --border: #1a1a1a;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--paper);
    color: var(--ink);
    font-family: 'IBM Plex Mono', monospace;
    font-size: 14px;
    line-height: 1.7;
    max-width: 720px;
    margin: 0 auto;
    padding: 40px 24px 80px;
  }

  /* NOISE OVERLAY */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 0;
    opacity: 0.5;
  }

  * { position: relative; z-index: 1; }

  /* MASTHEAD */
  .masthead {
    border: 3px solid var(--border);
    margin-bottom: 40px;
    overflow: hidden;
  }

  .masthead-top {
    background: var(--ink);
    padding: 28px 28px 20px;
    border-bottom: 3px solid var(--red);
  }

  .masthead-top h1 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 80px;
    color: var(--paper);
    letter-spacing: 10px;
    line-height: 0.9;
    text-shadow: 4px 4px 0 var(--red);
  }

  .masthead-top .subtitle {
    font-family: 'Share Tech Mono', monospace;
    font-size: 11px;
    letter-spacing: 3px;
    color: rgba(240,235,224,0.6);
    text-transform: uppercase;
    margin-top: 8px;
  }

  .masthead-bottom {
    background: var(--yellow);
    padding: 10px 28px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 8px;
  }

  .masthead-bottom span {
    font-family: 'Share Tech Mono', monospace;
    font-size: 10px;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: var(--ink);
  }

  /* INTRO PULL QUOTE */
  .pullquote {
    border-left: 5px solid var(--red);
    padding: 14px 20px;
    margin: 0 0 36px;
    background: var(--paper2);
  }

  .pullquote p {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 22px;
    letter-spacing: 1px;
    line-height: 1.3;
    color: var(--ink);
  }

  .pullquote small {
    display: block;
    font-family: 'Share Tech Mono', monospace;
    font-size: 10px;
    letter-spacing: 2px;
    color: var(--muted);
    margin-top: 6px;
    text-transform: uppercase;
  }

  /* SECTION HEADERS */
  .section {
    margin-bottom: 40px;
  }

  .section-header {
    display: flex;
    align-items: center;
    gap: 0;
    margin-bottom: 20px;
    border-bottom: 2px solid var(--border);
    padding-bottom: 10px;
  }

  .section-num {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 48px;
    color: var(--red);
    line-height: 1;
    margin-right: 14px;
    min-width: 40px;
  }

  .section-title-block h2 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 26px;
    letter-spacing: 3px;
    color: var(--ink);
    line-height: 1;
  }

  .section-title-block p {
    font-family: 'Share Tech Mono', monospace;
    font-size: 10px;
    letter-spacing: 1px;
    color: var(--muted);
    text-transform: uppercase;
    margin-top: 2px;
  }

  /* STEP BLOCKS */
  .step {
    display: flex;
    gap: 16px;
    margin-bottom: 20px;
    align-items: flex-start;
  }

  .step-num {
    background: var(--ink);
    color: var(--paper);
    font-family: 'Bebas Neue', sans-serif;
    font-size: 20px;
    min-width: 36px;
    height: 36px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    margin-top: 2px;
  }

  .step-content h3 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 18px;
    letter-spacing: 2px;
    margin-bottom: 4px;
  }

  .step-content p {
    font-size: 13px;
    color: var(--ink);
    line-height: 1.7;
  }

  .step-content p em {
    font-style: italic;
    color: var(--muted);
  }

  /* CALLOUT BOXES */
  .callout {
    border: 2px solid var(--border);
    padding: 14px 18px;
    margin: 16px 0;
    background: var(--paper2);
  }

  .callout.red {
    border-color: var(--red);
    border-left: 5px solid var(--red);
  }

  .callout.black {
    background: var(--ink);
    color: var(--paper);
  }

  .callout.yellow {
    background: var(--yellow);
    border-color: var(--border);
  }

  .callout-label {
    font-family: 'Share Tech Mono', monospace;
    font-size: 9px;
    letter-spacing: 3px;
    text-transform: uppercase;
    margin-bottom: 6px;
    opacity: 0.65;
  }

  .callout p {
    font-size: 13px;
    line-height: 1.6;
  }

  .callout.black p, .callout.black .callout-label { color: var(--paper); }
  .callout.black strong { color: var(--yellow); }

  /* CODE DISPLAY */
  .code-example {
    background: var(--ink);
    color: var(--yellow);
    font-family: 'Share Tech Mono', monospace;
    font-size: 12px;
    padding: 14px 16px;
    margin: 12px 0;
    word-break: break-all;
    border: 2px solid var(--border);
    line-height: 1.5;
  }

  /* FIELD TABLE */
  .field-table {
    width: 100%;
    border-collapse: collapse;
    margin: 12px 0;
    font-size: 12px;
  }

  .field-table th {
    background: var(--ink);
    color: var(--paper);
    font-family: 'Share Tech Mono', monospace;
    font-size: 10px;
    letter-spacing: 2px;
    text-transform: uppercase;
    text-align: left;
    padding: 8px 12px;
    border: 1px solid var(--border);
  }

  .field-table td {
    padding: 8px 12px;
    border: 1px solid #ccc;
    vertical-align: top;
    font-family: 'IBM Plex Mono', monospace;
  }

  .field-table tr:nth-child(even) td { background: var(--paper2); }

  .required {
    background: var(--red);
    color: white;
    font-family: 'Share Tech Mono', monospace;
    font-size: 8px;
    letter-spacing: 1px;
    padding: 2px 5px;
    text-transform: uppercase;
    vertical-align: middle;
    margin-left: 5px;
  }

  .optional {
    background: transparent;
    border: 1px solid #aaa;
    color: var(--muted);
    font-family: 'Share Tech Mono', monospace;
    font-size: 8px;
    letter-spacing: 1px;
    padding: 2px 5px;
    text-transform: uppercase;
    vertical-align: middle;
    margin-left: 5px;
  }

  /* DIAGRAM */
  .flow {
    display: flex;
    align-items: center;
    gap: 0;
    margin: 20px 0;
    flex-wrap: wrap;
    gap: 6px;
  }

  .flow-box {
    background: var(--ink);
    color: var(--paper);
    font-family: 'Share Tech Mono', monospace;
    font-size: 10px;
    letter-spacing: 1px;
    padding: 10px 14px;
    text-transform: uppercase;
    text-align: center;
    line-height: 1.4;
    min-width: 100px;
  }

  .flow-box.red { background: var(--red); }
  .flow-box.yellow { background: var(--yellow); color: var(--ink); }

  .flow-arrow {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 22px;
    color: var(--muted);
  }

  /* FAQ */
  .faq-item {
    border-top: 1px dashed #aaa;
    padding: 14px 0;
  }

  .faq-item:last-child { border-bottom: 1px dashed #aaa; }

  .faq-q {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 17px;
    letter-spacing: 1px;
    margin-bottom: 6px;
  }

  .faq-a {
    font-size: 13px;
    color: var(--ink);
    line-height: 1.7;
  }

  /* MANIFESTO */
  .manifesto {
    background: var(--ink);
    color: var(--paper);
    padding: 28px;
    margin-top: 40px;
    border-top: 5px solid var(--red);
  }

  .manifesto h2 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 28px;
    letter-spacing: 4px;
    color: var(--yellow);
    margin-bottom: 16px;
  }

  .manifesto p {
    font-family: 'Share Tech Mono', monospace;
    font-size: 11px;
    letter-spacing: 1px;
    line-height: 2;
    color: rgba(240,235,224,0.75);
  }

  .manifesto p strong { color: var(--paper); }

  .manifesto ul {
    list-style: none;
    margin: 12px 0;
  }

  .manifesto ul li::before {
    content: '★ ';
    color: var(--red);
  }

  .manifesto ul li {
    font-family: 'Share Tech Mono', monospace;
    font-size: 11px;
    letter-spacing: 1px;
    color: rgba(240,235,224,0.75);
    line-height: 2;
  }

  /* DIVIDER */
  .divider {
    border: none;
    border-top: 2px solid var(--border);
    margin: 32px 0;
    opacity: 0.15;
  }

  hr.thick {
    border: none;
    border-top: 3px solid var(--border);
    margin: 32px 0;
    opacity: 1;
  }

  /* PRINT STYLES */
  @media print {
    body::before { display: none; }
    body { background: white; }
    .masthead-top { background: #000 !important; -webkit-print-color-adjust: exact; }
    .callout.black { background: #000 !important; -webkit-print-color-adjust: exact; }
  }

  @media (max-width: 500px) {
    .masthead-top h1 { font-size: 56px; }
    .flow { flex-direction: column; align-items: flex-start; }
    .flow-arrow { transform: rotate(90deg); }
  }
</style>
</head>
<body>

<!-- MASTHEAD -->
<div class="masthead">
  <div class="masthead-top">
    <h1>DIY MESH</h1>
    <p class="subtitle">DIY Show Network // User Guide + README</p>
  </div>
  <div class="masthead-bottom">
    <span>No Ads &nbsp;★&nbsp; No Server &nbsp;★&nbsp; No Corporate Involvement</span>
    <span>Pass this around like a zine</span>
  </div>
</div>

<!-- INTRO -->
<div class="pullquote">
  <p>DIY Mesh is a punk show board that lives in a single HTML file. No app store. No account. No algorithm. No Ticketmaster. Just you, your browser, and your crew.</p>
  <small>Built for DIY punk / hardcore / metal / noise scenes</small>
</div>

<p style="font-size:13px; margin-bottom:32px; color:var(--muted)">This document explains how to use the <strong style="color:var(--ink)">diy-mesh-showboard.html</strong> file. Keep this readme alongside it or print it out and tape it to your bathroom wall.</p>

<hr class="thick">

<!-- SECTION 1: GETTING STARTED -->
<div class="section">
  <div class="section-header">
    <div class="section-num">1</div>
    <div class="section-title-block">
      <h2>Getting Started</h2>
      <p>Open the file, you're done</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">1</div>
    <div class="step-content">
      <h3>Get the file</h3>
      <p>Someone sent you <strong>diy-showboard.html</strong> — via email, USB stick, Discord, Signal, carrier pigeon, whatever. Save it somewhere on your computer you'll remember.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">2</div>
    <div class="step-content">
      <h3>Open it in your browser</h3>
      <p>Double-click the file, or drag it into any web browser (Chrome, Firefox, Safari, Edge — all work). You'll see the MESH show board load up. <em>No internet connection required once you have the file.</em></p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">3</div>
    <div class="step-content">
      <h3>That's it</h3>
      <p>Seriously. Everything saves locally in your browser. No login. No account. No one collecting your data. Your shows live on your machine.</p>
    </div>
  </div>

  <div class="callout red">
    <div class="callout-label">Important</div>
    <p>Always open the <strong>same file</strong> from the same location. If you move the file, your saved shows stay in the browser tied to the original file path. To transfer shows to a new location, use the Share Code system described below.</p>
  </div>
</div>

<!-- SECTION 2: POSTING A SHOW -->
<div class="section">
  <div class="section-header">
    <div class="section-num">2</div>
    <div class="section-title-block">
      <h2>Posting a Show</h2>
      <p>Get your show on the board</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">1</div>
    <div class="step-content">
      <h3>Hit "+ Post Show" in the top right</h3>
      <p>A form will slide open. Fill in what you know. Not everything is required but more info helps people out.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">2</div>
    <div class="step-content">
      <h3>Fill in the show details</h3>

      <table class="field-table">
        <thead>
          <tr>
            <th>Field</th>
            <th>What to put</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Bands / Artists</strong> <span class="required">Required</span></td>
            <td>List bands separated by / — e.g. <em>Ceremony / Harm's Way / No Warning</em></td>
          </tr>
          <tr>
            <td><strong>Date</strong> <span class="required">Required</span></td>
            <td>Pick from the date picker. Past shows won't display.</td>
          </tr>
          <tr>
            <td><strong>Time</strong> <span class="optional">Optional</span></td>
            <td>Doors time, set time — e.g. <em>7pm doors / 8pm</em></td>
          </tr>
          <tr>
            <td><strong>Venue</strong> <span class="required">Required</span></td>
            <td>Venue name, or <em>House show — DM for address</em></td>
          </tr>
          <tr>
            <td><strong>City</strong> <span class="required">Required</span></td>
            <td>City and state/region — e.g. <em>Cleveland, OH</em></td>
          </tr>
          <tr>
            <td><strong>Cost</strong> <span class="optional">Optional</span></td>
            <td><em>$5 / Donation / Free / PWYW</em></td>
          </tr>
          <tr>
            <td><strong>Genre</strong> <span class="optional">Optional</span></td>
            <td>Punk, Hardcore, Metal, Noise, or Other Underground</td>
          </tr>
          <tr>
            <td><strong>Ages</strong> <span class="optional">Optional</span></td>
            <td>All Ages, 18+, or 21+</td>
          </tr>
          <tr>
            <td><strong>Notes</strong> <span class="optional">Optional</span></td>
            <td>Anything else — contact info, BYOB, benefit info, safe space policy, etc.</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

  <div class="step">
    <div class="step-num">3</div>
    <div class="step-content">
      <h3>Click "Post Show"</h3>
      <p>Your show appears on the board immediately. It's saved to your browser's local storage — it'll still be there when you reopen the file tomorrow, next week, etc.</p>
    </div>
  </div>

  <div class="callout">
    <div class="callout-label">Tip</div>
    <p>For house shows or venues where you don't want the address public, put <strong>"House show — DM for address"</strong> in the Venue field, and put your contact info in the Notes field. People will figure it out.</p>
  </div>
</div>

<!-- SECTION 3: SHARING -->
<div class="section">
  <div class="section-header">
    <div class="section-num">3</div>
    <div class="section-title-block">
      <h2>Sharing Shows Across Cities</h2>
      <p>The core of how the mesh works</p>
    </div>
  </div>

  <p style="font-size:13px; margin-bottom:20px">This is the whole point. There's no central server — shows spread the same way a zine does. You make a copy, hand it to someone, they hand it to someone else.</p>

  <div class="flow">
    <div class="flow-box red">You post<br>a show</div>
    <div class="flow-arrow">→</div>
    <div class="flow-box">Click<br>"Share"</div>
    <div class="flow-arrow">→</div>
    <div class="flow-box yellow">Copy the<br>MESH:// code</div>
    <div class="flow-arrow">→</div>
    <div class="flow-box">Text it to<br>your friend</div>
    <div class="flow-arrow">→</div>
    <div class="flow-box red">They import<br>it. Done.</div>
  </div>

  <hr class="divider">

  <h3 style="font-family:'Bebas Neue',sans-serif; font-size:18px; letter-spacing:2px; margin-bottom:16px">TO SHARE A SHOW:</h3>

  <div class="step">
    <div class="step-num">1</div>
    <div class="step-content">
      <h3>Click "Share" on any show card</h3>
      <p>Either the small "Share" button on the card itself, or open the show's detail view and click "Share Code" in the bottom right.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">2</div>
    <div class="step-content">
      <h3>The code is copied to your clipboard</h3>
      <p>It looks like this — a wall of scrambled text starting with <strong>MESH://</strong></p>
      <div class="code-example">MESH://eyJpZCI6ImV4YW1wbGUwMSIsImJhbmRzIjoiRGlzY2hhcmdlIC8gU3ViaHVtYW5zIiwiZGF0ZSI6IjIwMjUtMDctMTUiLCJ0aW1lIjoiN3BtIGRvb3JzIiwidmVudWUiOiJUaGUgR3JvZyBTaG9wIiwiY2l0eSI6IkNsZXZlbGFuZCwgT0gifQ==</div>
      <p><em>The whole thing is just the show's info encoded in text. It contains no tracking, no IDs linked to you, nothing sketchy.</em></p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">3</div>
    <div class="step-content">
      <h3>Send it to your friend however you want</h3>
      <p>Text message, Signal, email, Discord, Mastodon, paste it in a note, write it on a flyer (kidding). Any channel works — it's just text.</p>
    </div>
  </div>

  <hr class="divider">

  <h3 style="font-family:'Bebas Neue',sans-serif; font-size:18px; letter-spacing:2px; margin-bottom:16px">TO IMPORT A SHOW (your friend sent you a code):</h3>

  <div class="step">
    <div class="step-num">1</div>
    <div class="step-content">
      <h3>Open MESH (diy-showboard.html) in your browser</h3>
      <p>Just double-click the file like normal.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">2</div>
    <div class="step-content">
      <h3>Click "Import Code" in the top right</h3>
      <p>A text box opens.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">3</div>
    <div class="step-content">
      <h3>Paste the MESH:// code and click Import</h3>
      <p>The show appears on your board instantly. If you already have that show, it'll tell you so you don't get duplicates.</p>
    </div>
  </div>

  <div class="callout black">
    <div class="callout-label">The network effect</div>
    <p>If you're plugged into scenes in multiple cities, you're the bridge. Import shows from your Cleveland friend, share them to your Detroit crew, import their Detroit shows, share those to Pittsburgh. <strong>That's the mesh.</strong> No algorithm. Just people passing information to people.</p>
  </div>
</div>

<!-- SECTION 4: SPREADING THE APP -->
<div class="section">
  <div class="section-header">
    <div class="section-num">4</div>
    <div class="section-title-block">
      <h2>Spreading the App Itself</h2>
      <p>Get your friends set up</p>
    </div>
  </div>

  <p style="font-size:13px; margin-bottom:16px">If someone in your city doesn't have the file yet, they can't receive show codes. Get them set up first:</p>

  <div class="step">
    <div class="step-num">1</div>
    <div class="step-content">
      <h3>Send them both files</h3>
      <p>Email <strong>diy-showboard.html</strong> and <strong>MESH-readme.html</strong> (this file) to your friend. Gmail, Outlook, ProtonMail — any email handles HTML file attachments. Or share via Signal, Discord, Google Drive, USB, etc.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">2</div>
    <div class="step-content">
      <h3>Tell them to save and open</h3>
      <p>They save <strong>diy-showboard.html</strong> to their computer and double-click it. That's all. They're set up.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">3</div>
    <div class="step-content">
      <h3>Now send them a show code</h3>
      <p>Generate a Share Code for any show on your board and send it to them so they have something right away. First code = first connection = the mesh grows.</p>
    </div>
  </div>

  <div class="callout yellow">
    <div class="callout-label">Think of it like a zine</div>
    <p>A zine doesn't have a server. You print it, hand it to someone, they hand it to someone. The file IS the publication. The codes ARE the content. It spreads as far as your network does.</p>
  </div>
</div>

<!-- SECTION 5: FINDING & FILTERING -->
<div class="section">
  <div class="section-header">
    <div class="section-num">5</div>
    <div class="section-title-block">
      <h2>Finding Shows</h2>
      <p>Search, filter, sort</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">—</div>
    <div class="step-content">
      <h3>Search bar</h3>
      <p>Type any part of a band name, venue, city, or show notes. Results filter as you type.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">—</div>
    <div class="step-content">
      <h3>Genre filter</h3>
      <p>Filter to Punk, Hardcore, Metal, Noise, or Other Underground only.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">—</div>
    <div class="step-content">
      <h3>City filter</h3>
      <p>Automatically populates with every city that has a show on your board. Good for when you're traveling.</p>
    </div>
  </div>

  <div class="step">
    <div class="step-num">—</div>
    <div class="step-content">
      <h3>Past shows</h3>
      <p>The board only shows upcoming shows. Once a show's date passes, it disappears from view automatically (it's still saved — it just gets filtered out). This keeps things clean.</p>
    </div>
  </div>
</div>

<!-- SECTION 6: FAQ -->
<div class="section">
  <div class="section-header">
    <div class="section-num">6</div>
    <div class="section-title-block">
      <h2>Questions</h2>
      <p>Stuff people ask</p>
    </div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Does this need the internet?</div>
    <div class="faq-a">Only to load the fonts the first time you open it (they come from Google Fonts). After that, it works fully offline. If you're somewhere with no internet and the fonts don't load, it'll fall back to a system monospace font and still work fine.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">What happens if I clear my browser history / cache?</div>
    <div class="faq-a">Your shows could get wiped — browser storage clears with certain privacy settings or "clear browsing data" actions. To protect against this: generate a Share Code for every show you want to keep and save those codes in a text file somewhere safe. You can reimport them any time.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Can I edit a show after posting it?</div>
    <div class="faq-a">Not yet — delete the old one (click the show, then "Delete" in the bottom left of the detail view) and repost with the corrected info. Then share a fresh code to anyone who had the old one.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Can multiple people post to the same board?</div>
    <div class="faq-a">Each person has their own board (it's local to their machine). The way you "share" a board is by trading codes. If you want to run a city-wide board, designate one person as the aggregator — they collect codes from everyone and can share a batch of codes for a whole scene's worth of shows.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Is this private? Can people see what I post?</div>
    <div class="faq-a">Your shows only go where you send the codes. Nothing is transmitted anywhere automatically. No one can see your board unless you share a code with them. The only "public" part is what you choose to share.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Can I use this on my phone?</div>
    <div class="faq-a">Yes — open it in your phone's browser. It's mobile-responsive. On iOS, save the HTML file to your Files app and open with Safari. On Android, save to Downloads and open with Chrome or Firefox.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">What if the file gets corrupted or I lose it?</div>
    <div class="faq-a">Get the file from whoever gave it to you originally, or ask anyone in your network who has it. The shows don't live in the file itself — they live in the browser storage on your machine. The file is just the interface. Your shows are in your browser tied to that file's location.</div>
  </div>

  <div class="faq-item">
    <div class="faq-q">Someone sent me a code but it won't import.</div>
    <div class="faq-a">Make sure you're copying the entire MESH:// code — it can be long. If it got cut off in a text message or email, ask them to resend it. If it still doesn't work, the code might have gotten corrupted in transit — ask for a fresh one.</div>
  </div>
</div>

<!-- MANIFESTO -->
<div class="manifesto">
  <h2>Why This Exists</h2>
  <p>
    Ticketmaster charges service fees that cost more than the ticket. LiveNation owns the venues. Spotify pays fractions of a penny. Facebook wants your data to sell ads. Instagram buries your posts unless you pay to boost them.
  </p>
  <p>&nbsp;</p>
  <p>
    The DIY scene doesn't need any of that. It never did. Shows get put on in basements, VFW halls, record stores, and living rooms. Word spreads through flyers, zines, word of mouth, and people who give a damn.
  </p>
  <p>&nbsp;</p>
  <p><strong>MESH is just that, but digital. Ground rules:</strong></p>
  <ul>
    <li>No ads, ever</li>
    <li>No data collection, ever</li>
    <li>No industry involvement, ever</li>
    <li>No central server that can be shut down or sold</li>
    <li>No algorithm deciding what shows you see</li>
    <li>No account required to participate</li>
  </ul>
  <p>&nbsp;</p>
  <p>The file is yours. Modify it. Redistribute it. Print this readme and tape it to a telephone pole. Do whatever you want with it. That's the point.</p>
  <p>&nbsp;</p>
  <p style="color:var(--yellow); font-weight:600">Keep it weird. Keep it local. Keep it loud.</p>
</div>

</body>
</html>
