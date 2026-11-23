<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Sarika Dhanshree · Brand Strategy Assignment</title>
<meta name="description" content="Instagram sunscreen strategy, sunscreen spray launch, Zomato annual brand plan, Minimalist and resources.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#fff8ee; --card:#ffffff; --ink:#1d2433; --muted:#5b6475; --line:#eadfcf;
  --sun:#ff9f1c; --coral:#f2603c; --navy:#1b2a49; --mint:#2ba58b; --sky:#d9ecff; --cream:#ffeccc;
  --radius:18px;
}
@media (prefers-color-scheme: dark){
  :root{--bg:#141a28;--card:#1c2436;--ink:#f3eee4;--muted:#a9b0c0;--line:#2c3650;--cream:#2a2a2a;--sky:#1f3350}
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.65 Inter,system-ui,sans-serif}
h1,h2,h3{font-family:Fraunces,Georgia,serif;line-height:1.15;margin:0 0 .5em}
h1{font-size:clamp(2.2rem,5.5vw,4rem);letter-spacing:-.02em}
h2{font-size:clamp(1.7rem,3.4vw,2.5rem)}
h3{font-size:1.25rem}
a{color:var(--coral)}
.wrap{max-width:1080px;margin:0 auto;padding:0 20px}
nav{position:sticky;top:0;z-index:20;background:color-mix(in srgb,var(--bg) 88%,transparent);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
nav .wrap{display:flex;gap:6px 18px;align-items:center;overflow-x:auto;padding-top:10px;padding-bottom:10px;white-space:nowrap}
nav b{font-family:Fraunces,serif;margin-right:auto}
nav a{text-decoration:none;color:var(--muted);font-size:.9rem;font-weight:500}
nav a:hover{color:var(--coral)}
.hero{padding:56px 0 30px}
.hero .grid{display:grid;grid-template-columns:1.1fr .9fr;gap:30px;align-items:center}
.tag{display:inline-block;background:var(--cream);color:var(--coral);font-weight:600;font-size:.8rem;padding:5px 12px;border-radius:99px;margin-bottom:14px}
.lead{font-size:1.15rem;color:var(--muted);max-width:56ch}
.meta{color:var(--muted);font-size:.92rem;margin-top:14px}
section{padding:54px 0;border-top:1px solid var(--line)}
.num{font-family:Fraunces,serif;color:var(--sun);font-size:1rem;font-weight:700;letter-spacing:.12em;text-transform:uppercase;display:block;margin-bottom:6px}
.card{background:var(--card);border:1px solid var(--line);border-radius:var(--radius);padding:22px}
.cols{display:grid;gap:18px}
.c2{grid-template-columns:repeat(2,1fr)} .c3{grid-template-columns:repeat(3,1fr)} .c4{grid-template-columns:repeat(4,1fr)}
.callout{background:var(--navy);color:#fff;border-radius:var(--radius);padding:28px 30px;margin:22px 0}
.callout p{margin:.3em 0}
.callout .big{font-family:Fraunces,serif;font-size:clamp(1.3rem,2.6vw,1.9rem);line-height:1.3}
.muted{color:var(--muted)}
.small{font-size:.88rem}
.pill{display:inline-block;padding:3px 10px;border-radius:99px;font-size:.78rem;font-weight:600;background:var(--sky);color:var(--navy);margin:2px 4px 2px 0}
@media (prefers-color-scheme: dark){.pill{color:#d9ecff}}
.tablewrap{overflow-x:auto;border:1px solid var(--line);border-radius:var(--radius);background:var(--card)}
table{border-collapse:collapse;width:100%;font-size:.9rem;min-width:720px}
th,td{padding:12px 14px;text-align:left;vertical-align:top;border-bottom:1px solid var(--line)}
th{background:var(--cream);font-size:.78rem;text-transform:uppercase;letter-spacing:.06em}
tr:last-child td{border-bottom:0}
td:first-child{font-weight:600}
.tabs{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0 12px}
.tabs button{border:1px solid var(--line);background:var(--card);color:var(--ink);padding:8px 14px;border-radius:99px;font:inherit;font-size:.88rem;cursor:pointer}
.tabs button[aria-selected=true]{background:var(--coral);border-color:var(--coral);color:#fff}
.kpi{display:none}.kpi.on{display:block}
.kpi dl{display:grid;grid-template-columns:150px 1fr;gap:8px 16px;margin:0}
.kpi dt{font-weight:600;color:var(--muted);font-size:.85rem}
.kpi dd{margin:0}
.bar{display:flex;align-items:center;gap:12px;margin:10px 0}
.bar .l{width:170px;font-weight:500;font-size:.92rem}
.bar .t{flex:1;background:var(--cream);border-radius:99px;height:16px;overflow:hidden}
.bar .t i{display:block;height:100%;background:linear-gradient(90deg,var(--sun),var(--coral));border-radius:99px}
.bar .v{width:44px;text-align:right;font-weight:600}
.tension{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin:18px 0}
.tension div{background:var(--card);border:1px solid var(--line);border-radius:var(--radius);padding:18px}
.tension small{display:block;color:var(--sun);font-weight:700;letter-spacing:.1em;text-transform:uppercase;margin-bottom:6px}
.timeline{display:grid;grid-template-columns:repeat(4,1fr);gap:12px}
.week{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:14px;font-size:.85rem}
.week h4{margin:0 0 2px;font-family:Fraunces,serif;font-size:1rem}
.week .d{color:var(--muted);font-size:.78rem;margin-bottom:8px;display:block}
.week p{margin:.4em 0}
.week b{font-size:.72rem;text-transform:uppercase;letter-spacing:.06em;color:var(--coral)}
.week.tease{border-top:5px solid var(--sky)} .week.launch{border-top:5px solid var(--coral)} .week.sustain{border-top:5px solid var(--mint)}
details{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:14px 18px;margin:10px 0}
summary{cursor:pointer;font-weight:600}
details p{margin:.6em 0 0}
.q{background:var(--cream);border-left:4px solid var(--sun);padding:10px 14px;border-radius:8px;font-size:.92rem}
.layers{counter-reset:l;display:grid;gap:12px}
.layer{display:grid;grid-template-columns:46px 1fr;gap:16px;background:var(--card);border:1px solid var(--line);border-radius:var(--radius);padding:18px}
.layer::before{counter-increment:l;content:counter(l);width:40px;height:40px;border-radius:50%;background:var(--navy);color:#fff;display:grid;place-items:center;font-family:Fraunces,serif;font-weight:700}
.layer h3{margin:0 0 4px}
.layer .out{margin-top:8px;font-size:.85rem;color:var(--mint);font-weight:600}
.slides{display:flex;flex-wrap:wrap;gap:8px}
.slides span{background:var(--card);border:1px solid var(--line);padding:4px 10px;border-radius:8px;font-size:.82rem}
.slides b{width:100%;font-family:Fraunces,serif;margin-top:8px}
figure{margin:0}
figcaption{font-size:.8rem;color:var(--muted);text-align:center;margin-top:6px}
footer{padding:40px 0;border-top:1px solid var(--line);color:var(--muted);font-size:.9rem;text-align:center}
@media (max-width:860px){
  .hero .grid,.c2,.c3,.c4,.tension{grid-template-columns:1fr}
  .timeline{grid-template-columns:1fr 1fr}
  .kpi dl{grid-template-columns:1fr}
  .bar .l{width:110px}
}
@media (max-width:520px){.timeline{grid-template-columns:1fr}}
</style>
</head>
<body>
<nav><div class="wrap">
  <b>Sarika Dhanshree</b>
  <a href="#s1">1 · Instagram</a><a href="#s2">2 · Spray launch</a><a href="#s3">3 · Zomato</a><a href="#s4">4 · Minimalist</a><a href="#s5">5 · Resources</a>
</div></nav>

<header class="hero"><div class="wrap grid">
  <div>
    <h1>Start from what people ask, doubt and do.</h1>
    <p class="lead">Strategic thinking, social media and brand building. Every answer begins with a consumer tension and ends with something a team could execute on Monday morning.</p>
    <p class="meta">Sarika Dhanshree · Delhi</p>
  </div>
  <figure>
    <!-- Hero illustration: sun, spray bottle, mist, day arc -->
    <svg viewBox="0 0 460 400" role="img" aria-label="Illustration of a sunscreen spray bottle misting under a sun, with a day arc of small moments">
      <circle cx="320" cy="110" r="62" fill="#ff9f1c"/>
      <g stroke="#ff9f1c" stroke-width="8" stroke-linecap="round">
        <path d="M320 18v-14M320 202v14M228 110h-14M426 110h14M254 44l-10-10M386 176l10 10M386 44l10-10M254 176l-10 10"/>
      </g>
      <path d="M30 330 Q230 120 430 330" fill="none" stroke="#1b2a49" stroke-width="3" stroke-dasharray="3 9" stroke-linecap="round"/>
      <circle cx="52" cy="318" r="14" fill="#2ba58b"/><circle cx="152" cy="212" r="14" fill="#f2603c"/>
      <circle cx="308" cy="212" r="14" fill="#f2603c"/><circle cx="408" cy="318" r="14" fill="#2ba58b"/>
      <g font-family="Inter,sans-serif" font-size="13" fill="#1b2a49" font-weight="600" text-anchor="middle">
        <text x="52" y="352">8 am</text><text x="152" y="246">commute</text><text x="308" y="246">2 pm lunch</text><text x="408" y="352">evening</text>
      </g>
      <!-- bottle -->
      <g transform="translate(150 150)">
        <rect x="46" y="0" width="34" height="22" rx="5" fill="#1b2a49"/>
        <rect x="80" y="6" width="26" height="8" rx="4" fill="#1b2a49"/>
        <rect x="26" y="22" width="74" height="150" rx="22" fill="#ffffff" stroke="#1b2a49" stroke-width="4"/>
        <rect x="26" y="70" width="74" height="60" fill="#f2603c"/>
        <text x="63" y="98" font-family="Fraunces,serif" font-size="17" font-weight="700" fill="#fff" text-anchor="middle">SPF</text>
        <text x="63" y="118" font-family="Fraunces,serif" font-size="17" font-weight="700" fill="#fff" text-anchor="middle">50</text>
      </g>
      <g fill="#d9ecff" stroke="#1b2a49" stroke-width="1.5" opacity=".95">
        <circle cx="285" cy="160" r="5"/><circle cx="302" cy="148" r="4"/><circle cx="296" cy="172" r="3.5"/>
        <circle cx="318" cy="162" r="4.5"/><circle cx="312" cy="184" r="3"/><circle cx="330" cy="176" r="3.5"/>
      </g>
      <path d="M258 160 L284 160" stroke="#1b2a49" stroke-width="3" stroke-linecap="round" stroke-dasharray="2 6"/>
    </svg>
  </figure>
</div></header>

<!-- ===================== 1 ===================== -->
<section id="s1"><div class="wrap">
  <span class="num">Section 1</span>
  <h2>Sunscreen brand: Instagram content strategy by KPI</h2>
  <p class="lead"><b>One post, one job.</b> Instagram is not one channel. Every piece of content is briefed against a single primary KPI, so the format, feature and CTA are chosen for that job. Sunscreen has an unusual problem: everyone agrees they should use it, but few feel like it. So content has to lower effort and doubt, not just advertise.</p>

  <div class="tabs" role="tablist" aria-label="KPI">
    <button role="tab" aria-selected="true" data-k="k0">Visibility</button>
    <button role="tab" aria-selected="false" data-k="k1">Deepening</button>
    <button role="tab" aria-selected="false" data-k="k2">Consideration</button>
    <button role="tab" aria-selected="false" data-k="k3">CTR</button>
    <button role="tab" aria-selected="false" data-k="k4">Conversion</button>
    <button role="tab" aria-selected="false" data-k="k5">Community</button>
    <button role="tab" aria-selected="false" data-k="k6">Retention</button>
  </div>
  <div class="card">
    <div class="kpi on" id="k0"><h3>Visibility (reach new people)</h3><dl>
      <dt>Format</dt><dd>Reels (main); Trial Reels shown to non-followers first</dd>
      <dt>Features</dt><dd>Collab posts, trending audio used sparingly, strong first-frame text hook</dd>
      <dt>Content idea</dt><dd>Relatable summer situations, sun myths in 15 seconds, UV-camera reveal</dd>
      <dt>CTA</dt><dd>“Send this to the friend who skips SPF” (a send is a high-intent share)</dd>
      <dt>Metrics</dt><dd>Non-follower reach, sends per reach, 3-second hold, views</dd></dl></div>
    <div class="kpi" id="k1"><h3>Visibility, deepening (saves and shares)</h3><dl>
      <dt>Format</dt><dd>Feed carousels</dd>
      <dt>Features</dt><dd>Question on the cover slide, recap on the last</dd>
      <dt>Content idea</dt><dd>SPF myths vs facts, SPF vs PA explained, how much is enough</dd>
      <dt>CTA</dt><dd>“Save this guide”</dd>
      <dt>Metrics</dt><dd>Saves, shares, swipe depth</dd></dl></div>
    <div class="kpi" id="k2"><h3>Consideration</h3><dl>
      <dt>Format</dt><dd>Reels and Stories</dd>
      <dt>Features</dt><dd>Collab posts; poll, quiz and question stickers</dd>
      <dt>Content idea</dt><dd>Product demo (texture, finish, how to apply); FAQs and comparisons</dd>
      <dt>CTA</dt><dd>“Explore the product” / “Ask us anything”</dd>
      <dt>Metrics</dt><dd>Profile visits, story replies, sticker taps, engagement rate</dd></dl></div>
    <div class="kpi" id="k3"><h3>CTR (move people to the product)</h3><dl>
      <dt>Format</dt><dd>Stories (main); product-tagged feed posts; Reels with a pinned comment</dd>
      <dt>Features</dt><dd>Link sticker, poll before the link, countdown sticker, product tags</dd>
      <dt>Content idea</dt><dd>Story sequence: problem poll, then proof clip, then link sticker</dd>
      <dt>CTA</dt><dd>“Tap to find your skin-type match” (a specific benefit beats “Shop now”)</dd>
      <dt>Metrics</dt><dd>Link taps, product page clicks, profile visits, CTR</dd></dl></div>
    <div class="kpi" id="k4"><h3>Conversion</h3><dl>
      <dt>Format</dt><dd>Stories, shop-tagged posts and Reels, DMs</dd>
      <dt>Features</dt><dd>Link stickers, product tags, comment-a-keyword DM automation, click-to-message ads, Highlights as a mini shop</dd>
      <dt>Content idea</dt><dd>Wear tests, dermatologist Q&amp;A, what’s in the box, UGC reviews, restock reminders</dd>
      <dt>CTA</dt><dd>“Comment SPF and we’ll DM your link and offer” (removes friction, gives a first-party lead)</dd>
      <dt>Metrics</dt><dd>Add-to-cart rate, orders, DM-to-order rate, conversion rate, CPA</dd></dl></div>
    <div class="kpi" id="k5"><h3>Community growth</h3><dl>
      <dt>Format</dt><dd>Reels, Stories, Broadcast Channel</dd>
      <dt>Features</dt><dd>Remix, Collab, Add Yours, Q&amp;A box, Close Friends early access</dd>
      <dt>Content idea</dt><dd>UGC and creator challenges, “Ask our skin expert”, a daily UV alert</dd>
      <dt>CTA</dt><dd>“Join our channel for the daily UV alert” (a reason to return, not just follow)</dd>
      <dt>Metrics</dt><dd>Follower growth rate, returning viewers, UGC volume, replies</dd></dl></div>
    <div class="kpi" id="k6"><h3>Retention and repeat use</h3><dl>
      <dt>Format</dt><dd>DMs, Broadcast Channel, Stories</dd>
      <dt>Features</dt><dd>Story replies, replenishment reminder</dd>
      <dt>Content idea</dt><dd>“Your bottle should last X weeks. If it lasts longer, you’re under-applying.”</dd>
      <dt>CTA</dt><dd>“Reply REFILL to reorder”</dd>
      <dt>Metrics</dt><dd>Repeat purchase, channel read rate</dd></dl></div>
  </div>

  <h3 style="margin-top:36px">Build a funnel loop</h3>
  <figure>
    <svg viewBox="0 0 900 190" role="img" aria-label="Funnel loop: Reel to Story sequence to DM or link to Broadcast Channel, looping back" style="width:100%;height:auto">
      <defs><marker id="ar" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="7" markerHeight="7" orient="auto"><path d="M0 0L10 5L0 10z" fill="#1b2a49"/></marker></defs>
      <g font-family="Inter,sans-serif" text-anchor="middle">
        <rect x="10" y="40" width="190" height="90" rx="18" fill="#ff9f1c"/>
        <text x="105" y="78" font-size="20" font-weight="700" fill="#1b2a49">Reel</text><text x="105" y="104" font-size="14" fill="#1b2a49">Discover</text>
        <rect x="245" y="40" width="190" height="90" rx="18" fill="#f2603c"/>
        <text x="340" y="78" font-size="20" font-weight="700" fill="#fff">Story sequence</text><text x="340" y="104" font-size="14" fill="#fff">Consider</text>
        <rect x="480" y="40" width="190" height="90" rx="18" fill="#1b2a49"/>
        <text x="575" y="78" font-size="20" font-weight="700" fill="#fff">DM or link</text><text x="575" y="104" font-size="14" fill="#fff">Convert</text>
        <rect x="715" y="40" width="175" height="90" rx="18" fill="#2ba58b"/>
        <text x="802" y="78" font-size="20" font-weight="700" fill="#fff">Broadcast Channel</text><text x="802" y="104" font-size="14" fill="#fff">Retain</text>
      </g>
      <g stroke="#1b2a49" stroke-width="3" fill="none" marker-end="url(#ar)">
        <path d="M202 85H240"/><path d="M437 85H475"/><path d="M672 85H710"/>
      </g>
      <path d="M802 135 C802 185 105 185 105 135" stroke="#1b2a49" stroke-width="2.5" stroke-dasharray="4 7" fill="none" marker-end="url(#ar)"/>
    </svg>
    <figcaption>Each step hands the person to the next.</figcaption>
  </figure>

  <div class="cols c3" style="margin-top:28px">
    <div class="card"><h3>Judge by the job</h3><p>High views do not mean purchase intent. A Reel is not a failure because it did not sell, and a Story is not a success because it got views. Judging everything on likes is the most common mistake.</p></div>
    <div class="card"><h3>Build the loop</h3><p>Reel (discover) → Story sequence (consider) → DM or link (convert) → Broadcast Channel (retain).</p></div>
    <div class="card"><h3>Weight by season</h3><p>In India, lean toward Visibility and Community in Jan–Feb, and toward CTR and Conversion from March as the heat builds.</p></div>
  </div>

  <h3 style="margin-top:36px">Suggested monthly organic mix</h3>
  <p class="muted small">A starting split, to be tested and adjusted on performance.</p>
  <div class="card">
    <div class="bar"><span class="l">Education</span><span class="t"><i style="width:25%"></i></span><span class="v">25%</span></div><p class="small muted" style="margin:-4px 0 8px 182px">Trust and correct usage (SPF, PA, reapplication)</p>
    <div class="bar"><span class="l">Entertainment</span><span class="t"><i style="width:25%"></i></span><span class="v">25%</span></div><p class="small muted" style="margin:-4px 0 8px 182px">Reach and shareability</p>
    <div class="bar"><span class="l">Product demonstration</span><span class="t"><i style="width:20%"></i></span><span class="v">20%</span></div><p class="small muted" style="margin:-4px 0 8px 182px">Consideration and objection handling</p>
    <div class="bar"><span class="l">Creators and UGC</span><span class="t"><i style="width:20%"></i></span><span class="v">20%</span></div><p class="small muted" style="margin:-4px 0 8px 182px">Social proof and community</p>
    <div class="bar"><span class="l">Offers and conversion</span><span class="t"><i style="width:10%"></i></span><span class="v">10%</span></div><p class="small muted" style="margin:-4px 0 0 182px">Direct sales, kept light so the feed does not feel promotional</p>
  </div>
  <div class="callout"><p class="big">Sunscreen is a functional product, so communication should connect to real routines (commutes, lunch breaks, travel) rather than repeating SPF claims.</p></div>
</div></section>

<!-- ===================== 2 ===================== -->
<section id="s2"><div class="wrap">
  <span class="num">Section 2</span>
  <h2>Sunscreen spray: research, insight and launch campaign</h2>

  <h3>A. Competitor snapshot</h3>
  <div class="tablewrap"><table>
    <tr><th>Brand and product</th><th>Leads with</th><th>Usage instruction</th><th>Consumer voice</th><th>Gap for a new spray</th></tr>
    <tr><td>Moha Sunscreen Spray, SPF 50 (170 g)</td><td>Rice bran oil, Ayurvedic heritage, 80-minute water resistance, sweatproof</td><td>Shake, hold about 12 inches away, apply generously</td><td>Cooling and travel-friendly; some find it oily or sticky, a few dislike the fragrance</td><td>Strong on hydration and sweat-proofing, but reapplication is a spec, not a habit</td></tr>
    <tr><td>Garnier Super UV Invisible Air Mist, SPF 50+ PA++++ (75 ml)</td><td>Air-Lock technology, no white cast, vitamin C, can go over makeup</td><td>Spray from 15 cm on face and neck; reapply every 2–3 hours</td><td>About 4.2 stars across 7.8K ratings on Smytten; some report white cast, greasiness or scent</td><td>Tells people to reapply but never shows the moment it happens</td></tr>
    <tr><td>Fixderma Shadow SPF 50+ Invisible Spray (50 ml)</td><td>Physical blockers plus chemical absorbers; UVA, UVB and blue light</td><td>Body spray</td><td>Few public reviews found</td><td>Technical, ingredient-led language that is hard to turn into everyday situations</td></tr>
    <tr><td>Lotus Professional Phyto-Rx Sunblock Mist, SPF 50 PA+++ (100 ml)</td><td>Anti-tan, ultra-light, sweat and water proof, botanicals</td><td>Last skincare step on cleansed face and neck</td><td>4.2 stars across 1,674 ratings on Nykaa</td><td>Framed as a morning skincare step, not something for the rest of the day</td></tr>
    <tr><td>RENEE Glowscreen SPF 50 Spray, PA++++ (50 ml)</td><td>Hyaluronic acid, vitamin C, dewy glow, “weightless, non-greasy”</td><td>Reapply every two hours and after sweating or swimming</td><td>Praised for easy reapplication; some note uneven spray, low output or oiliness</td><td>Closest to our space, but positioned on glow and beauty</td></tr>
  </table></div>
  <p class="small muted">I also scanned four adjacent sprays and mists (Asaya, 52 Sundaze, Inde Wild, Supergoop PLAY). Their usage instructions are effort-heavy and buried in fine print: one asks for 8–10 inches of distance and eyes shut for three seconds, another for 8–10 mists, and most say reapply every two hours. Sources: brand sites and marketplace listings (Nykaa, Tira, Purplle, Smytten, Flipkart), read in November 2026. Moha’s own pages list PA+++ and PA++++ in different places, so I would confirm the rating against pack before using it in any claim.</p>

  <h3 style="margin-top:36px">B. What the research shows</h3>
  <div class="cols c2">
    <div class="card"><h3>Formula claims are table stakes</h3><p>No white cast, invisible finish, works over makeup, vitamin C or hydration and SPF/PA numbers appear across the set. The rose-water “hydrating mist” lane is also getting crowded.</p></div>
    <div class="card"><h3>Reapplication is an instruction, not an idea</h3><p>Garnier says every 2–3 hours and RENEE every two hours, but both bury it in the how-to. Nobody makes it easy or visible.</p></div>
    <div class="card"><h3>Complaints repeat</h3><p>White cast, oily or sticky feel, strong scent, and uneven or insufficient spray.</p></div>
    <div class="card"><h3>Questions consumers ask</h3><p>Can I spray over makeup? Is it sweat and water resistant? Is it safe for oily, dry or sensitive skin? How much do I spray? Does it work in Indian heat and humidity?</p></div>
    <div class="card"><h3>Spray carries a usage risk</h3><p>Dermatology guidance advises generous application and rubbing in for even coverage, so convenience alone does not guarantee protection. The launch has to teach correct application, not only promote ease.</p></div>
    <div class="card"><h3>Honest data gap</h3><p>I could not verify specific influencer campaigns for these sprays from public sources, so the influencer layer is category-level. Before presenting, I would check the Instagram Ad Library, Reels search (#sunscreenspray, #sunscreenmist) and YouTube reviews.</p></div>
  </div>

  <h3 style="margin-top:36px">C. The insight</h3>
  <div class="callout">
    <p class="big">People don’t forget that sunscreen exists. They forget to carry the routine out of the house, and when they do spray, they can’t tell whether they did enough.</p>
  </div>
  <div class="tension">
    <div><small>People believe</small>A quick spritz means they’re protected.</div>
    <div><small>But in reality</small>Sprays are easy to under-apply, and you can’t see where you missed.</div>
    <div><small>So the tension is</small>“Did I reapply? And did I spray enough?”</div>
  </div>
  <p>Sunscreen goes on at 8 am. Then the day moves: a commute, lunch outside, an errand, a trip. Competitors sell the morning application; the problem is the afternoon. A spray’s real advantage is not the finish, it is that it fits the moments between. A spray wins the reapplication moment but loses the proof moment. Every competitor sells convenience; none sells confidence. That turns the spray’s biggest weakness (hard to measure) into the brand’s biggest story, and it is provable on camera.</p>
  <p class="small muted">This is my synthesis of category research, not a survey figure. Before launch I would validate it with social listening and short consumer interviews.</p>

  <h3 style="margin-top:36px">D. Launch campaign: SUNSCREEN. ON THE GO.</h3>
  <div class="cols c2" style="align-items:center">
    <div>
      <p class="lead" style="margin-top:0">The day doesn’t stop. Neither should your sun care.</p>
      <p><b>Campaign thought:</b> make protection feel like a natural, visible part of an ordinary day, not another task on the to-do list.</p>
      <p><span class="pill">Convenience</span> sun protection that fits into a busy day<br><span class="pill">Education</span> how to apply a spray correctly, and how much<br><span class="pill">Lifestyle</span> real Indian urban moments, not beach clichés<br><span class="pill">Community</span> people sharing the moments they remember to protect their skin</p>
    </div>
    <figure>
      <!-- Phone UV-camera illustration -->
      <svg viewBox="0 0 320 380" role="img" aria-label="Phone showing a UV-camera view of a face with covered and missed spots" style="width:100%;height:auto;max-width:340px;display:block;margin:auto">
        <rect x="70" y="10" width="180" height="360" rx="30" fill="#1b2a49"/>
        <rect x="82" y="34" width="156" height="312" rx="16" fill="#2a2150"/>
        <ellipse cx="160" cy="170" rx="58" ry="74" fill="#7c5cd6" opacity=".55"/>
        <ellipse cx="160" cy="170" rx="58" ry="74" fill="none" stroke="#c8b6ff" stroke-width="2"/>
        <g fill="#f4f0ff">
          <ellipse cx="138" cy="150" rx="22" ry="16" opacity=".9"/>
          <ellipse cx="184" cy="152" rx="20" ry="14" opacity=".9"/>
          <ellipse cx="160" cy="196" rx="16" ry="10" opacity=".9"/>
        </g>
        <g fill="#0f0a2a" opacity=".85">
          <ellipse cx="124" cy="196" rx="10" ry="12"/><ellipse cx="198" cy="190" rx="9" ry="11"/>
        </g>
        <circle cx="124" cy="196" r="17" fill="none" stroke="#ff9f1c" stroke-width="3" stroke-dasharray="4 4"/>
        <circle cx="198" cy="190" r="16" fill="none" stroke="#ff9f1c" stroke-width="3" stroke-dasharray="4 4"/>
        <rect x="96" y="284" width="128" height="34" rx="17" fill="#ff9f1c"/>
        <text x="160" y="306" font-family="Inter,sans-serif" font-size="14" font-weight="700" fill="#1b2a49" text-anchor="middle">Did you cover it?</text>
        <rect x="136" y="16" width="48" height="8" rx="4" fill="#0f0a2a"/>
      </svg>
      <figcaption>Concept visual: the UV-camera reveal that makes missed spots visible.</figcaption>
    </figure>
  </div>

  <div class="cols c2" style="margin-top:22px">
    <div class="card"><span class="pill">The IP</span><h3>The SPF Check</h3><p>Every week, creators and customers share one everyday moment when they remember to protect their skin: the 2 pm lunch break, the evening commute, the weekend market, the outdoor coffee date. It gives the brand a recurring format that outlasts the launch.</p><p class="small muted">Each SPF Check has two parts: a <b>time check</b> (did I reapply?) and a <b>spray check</b> (did I cover enough?).</p></div>
    <div class="card"><span class="pill">The proof mechanic</span><h3>Spray Count</h3><p>A UV-camera “did you cover it?” reveal and a clear guide on sprays per area, so protection becomes visible and countable.</p><p class="small muted">The exact number per area must come from our own pack instructions and testing, not from a competitor’s. I would not promise a coverage-detecting product feature.</p></div>
  </div>

  <h3 style="margin-top:30px">Influencer approach</h3>
  <div class="cols c4">
    <div class="card"><span class="pill">Build trust</span><h3>Dermatologists</h3><p class="small">SPF education, correct spray application, mythbusting</p></div>
    <div class="card"><span class="pill">Explain the product</span><h3>Skincare creators</h3><p class="small">Texture tests, over-makeup demos, UV-camera tests, finish on Indian skin tones</p></div>
    <div class="card"><span class="pill">Build relevance</span><h3>Lifestyle creators</h3><p class="small">Commute, travel, lunch-break and weekend routines</p></div>
    <div class="card"><span class="pill">Build community</span><h3>Micro-creators</h3><p class="small">Honest reviews, UGC, “what’s in my bag”</p></div>
  </div>

  <h3 style="margin-top:36px">E. Eight-week calendar</h3>
  <p class="muted">Assumed launch start: Monday 1 Feb 2027. Phases: Tease (weeks 1–2), Launch (weeks 3–5), Sustain (weeks 6–8). BAU is the always-on layer: weekly SPF education, ingredient explainers, myth-vs-fact posts, testimonials, FAQs and community replies.</p>
  <div class="timeline">
    <div class="week tease"><h4>Week 1 · Tease</h4><span class="d">1–7 Feb</span><p><b>Key</b><br>Reel teaser “Your day has plans. Does your SPF?”; Stories poll “How many sprays did you do today?”</p><p><b>BAU</b><br>FAQ Story: “Do I need sunscreen in winter?”</p><p><b>IP</b><br>Announce the format; wedding season</p><p><b>CTA</b><br>Share with someone who never reapplies; join the Broadcast Channel</p></div>
    <div class="week tease"><h4>Week 2 · Tease</h4><span class="d">8–14 Feb</span><p><b>Key</b><br>UV-camera mystery clips; creators receive a mystery product</p><p><b>BAU</b><br>Carousel: the forgotten part of your skincare routine</p><p><b>IP</b><br>Valentine’s Day (14 Feb): “Glow without the missed spot”</p><p><b>CTA</b><br>Send to the partner who skips SPF</p></div>
    <div class="week launch"><h4>Week 3 · Launch</h4><span class="d">15–21 Feb</span><p><b>Key</b><br>Product reveal and demo Reel, including the “2 sprays vs enough” film; dermatologist Q&amp;A (Live and Stories)</p><p><b>BAU</b><br>Proof Reel</p><p><b>IP</b><br>Episode 1: the 2 pm lunch break</p><p><b>CTA</b><br>Explore the spray; tap for the Spray Count guide</p></div>
    <div class="week launch"><h4>Week 4 · Launch</h4><span class="d">22–28 Feb</span><p><b>Key</b><br>“A day in my bag” creator Reels and a three-creator UV-test series</p><p><b>BAU</b><br>FAQ Q&amp;A on Stories</p><p><b>IP</b><br>Episode 2: the evening commute; bride-and-guest SPF</p><p><b>CTA</b><br>Comment SPF for the DM link</p></div>
    <div class="week launch"><h4>Week 5 · Launch</h4><span class="d">1–7 Mar</span><p><b>Key</b><br>Spray Count challenge opens (UGC Reel, Add Yours sticker)</p><p><b>BAU</b><br>Community reposts; customer questions answered</p><p><b>IP</b><br>Submissions open; reactive trigger on the first 35°C day in Delhi or Mumbai</p><p><b>CTA</b><br>Count your sprays, tag your sunscreen buddy</p></div>
    <div class="week sustain"><h4>Week 6 · Sustain</h4><span class="d">8–14 Mar</span><p><b>Key</b><br>How to apply a spray correctly: coverage guide carousel</p><p><b>BAU</b><br>Dermatologist cameo</p><p><b>IP</b><br>Women’s Day (8 Mar): “Protect on your commute”</p><p><b>CTA</b><br>Save this guide</p></div>
    <div class="week sustain"><h4>Week 7 · Sustain</h4><span class="d">15–21 Mar</span><p><b>Key</b><br>Reviews carousel; objection-handling Stories (over makeup, oily skin, sweat); launch offer with link sticker</p><p><b>BAU</b><br>How-to: reapplying over makeup</p><p><b>IP</b><br>Holi lead-up (around 22 Mar, confirm date): skin-prep angle</p><p><b>CTA</b><br>Shop now; comment HOLI for the guide</p></div>
    <div class="week sustain"><h4>Week 8 · Sustain</h4><span class="d">22–28 Mar</span><p><b>Key</b><br>Retention: “Your bottle should last X weeks”; reapplication reminder Reel</p><p><b>BAU</b><br>FAQ: travel and cabin size</p><p><b>IP</b><br>Episode 3: best community SPF Checks; IPL season start (check fixtures)</p><p><b>CTA</b><br>Reply REFILL to reorder</p></div>
  </div>
  <div class="cols c3" style="margin-top:22px">
    <div class="card"><h3>Feasibility</h3><p class="small">For a three-person team: each week needs one creator shoot and one UGC call-out. The dermatologist Q&amp;A needs scheduling in advance.</p></div>
    <div class="card"><h3>Claims guardrails</h3><p class="small">Limit claims to the SPF and PA ratings on pack. Avoid “all-day protection”, “sweatproof” or water-resistance wording unless the pack and testing support it, and always pair a spray demo with “apply generously and rub in” guidance.</p></div>
    <div class="card"><h3>Measurement</h3><p class="small">Visibility (non-follower reach, sends, views); Consideration (saves, shares, profile visits, engagement rate); Traffic (link taps, CTR, landing-page sessions); Conversion (add-to-cart, orders, conversion rate, CPA); Community (UGC count, channel joins). Review weekly and shift about 20% of effort toward what is working.</p></div>
  </div>

  <h3 style="margin-top:36px">F. AI prompts and responses</h3>
  <p class="muted">AI tool used: Claude (Anthropic). I ran the work in two passes and combined the results. The competitor research went into the prompts as context.</p>
  <details open><summary>Pass 1: research and insight</summary>
    <p class="q"><b>Prompt:</b> “I’m launching a sunscreen spray in India. Act as a category researcher. Analyse five competing sprays or mists. For each, list format and price, top three reasons-to-believe, CTAs and usage instructions, influencer or campaign approach, and the consumer questions the brand answers. Then summarise what every brand says and what none of them says. Flag anything you could not verify.”</p>
    <p class="q"><b>Prompt:</b> “From the research above, find ONE consumer insight that no competitor is addressing, in the format ‘People believe X. But in reality Y. So the tension is Z.’ Reject insights that are just product features. It must come from real behaviour, be provable on camera and be something a spray can uniquely own.”</p>
    <p><b>Response (summary):</b> every brand sells convenience, none sells confidence; sprays are easy to under-apply and nobody can see their protection. This gave the Spray Count mechanic.</p></details>
  <details><summary>Pass 2: territories and calendar</summary>
    <p class="q"><b>Prompt:</b> “Act as a senior brand strategist working on an Indian sunscreen spray launch. Insight: consumers understand the importance of sunscreen but struggle to maintain reapplication through the day. Competitor sprays all lead with formula claims. Develop three campaign territories, a central idea for each, Instagram formats, a distinctive recurring content IP and consumer participation ideas. Avoid summer and beach clichés. Prioritise Indian urban routines.”</p>
    <p><b>Response (summary):</b> three territories: SPF on the Move (IP: Bag Check), The SPF Check (IP: a weekly series of everyday protection moments) and Plans Change. SPF Stays. (IP: Plan B).</p>
    <p class="q"><b>Prompt:</b> “Using the territory The SPF Check for a sunscreen spray launch in India, create a four-week Instagram calendar with a key campaign layer, a BAU layer and the recurring IP. Keep claims accurate: do not promise protection beyond SPF and PA ratings on pack. Include content that teaches correct spray application.”</p>
    <p><b>Response (summary):</b> a layered calendar plus an accuracy note to avoid “all-day protection” or “sweatproof” wording without pack and test support.</p></details>
  <details><summary>My review of the output</summary>
    <p><b>Territory chosen: The SPF Check.</b> It can become a recurring brand property rather than a one-off campaign, and it ties directly to the insight. Territory 1 is close to existing “what’s in my bag” formats, and Territory 3 is easier to copy.</p>
    <p><b>Combining the passes:</b> I kept the SPF Check as the ownable ritual and added Spray Count as its proof layer, because the under-application insight makes the ritual teach something.</p>
    <p><b>Accuracy:</b> claims are limited to SPF and PA ratings; anything beyond needs pack and test support.</p>
    <p><b>Feasibility:</b> one creator shoot and one UGC call-out per week suits a small team.</p></details>
</div></section>

<!-- ===================== 3 ===================== -->
<section id="s3"><div class="wrap">
  <span class="num">Section 3</span>
  <h2>Zomato: how I would build the Annual Brand Plan</h2>
  <p class="muted">This answer is a process and a presentation index, not campaign ideas.</p>
  <div class="callout"><p class="big">Zomato already knows how to win on social, so the question is not “how do we get attention?” but “how do we stay culturally relevant when everyone already uses us?”</p>
  <p class="small" style="opacity:.85">The plan should keep Zomato distinctive as the category gets crowded, keep identity consistent across platforms, and connect social to business outcomes. I would start by agreeing with the client what winning means this year. One note: Zomato is now the consumer brand under the parent company Eternal, so the plan must define which brand voice we speak in and how it sits with sister brands.</p></div>

  <h3>The process stack (six layers)</h3>
  <div class="layers">
    <div class="layer"><div><h3>Listen</h3><p>Business and brand immersion (objectives, positioning, tone, guidelines, existing recurring properties). Audit 12–24 months of Zomato social by platform and format. Social listening on Reddit, X, Instagram comments and Google reviews. Review competitors and adjacent personality brands (Swiggy, Blinkit, Zepto). Interview the current social and community team.</p><div class="out">Output: business and brand audit, platform-wise performance audit, conversation map</div></div></div>
    <div class="layer"><div><h3>Diagnose</h3><p>Separate brand love from brand fatigue. Find which content earns real conversation versus polite likes. Map where Zomato wins (humour, notifications, wit) and where it is vulnerable (service frustration, delivery issues, price complaints). Separate what makes the tone work (habits the audience recognises) from what is only legacy, so the plan builds on the first and does not copy the second.</p><div class="out">Output: strengths, gaps and risks summary</div></div></div>
    <div class="layer"><div><h3>Define</h3><p>Agree the role of social (brand, community and customer care, not just campaigns). Set the cultural territory Zomato can credibly speak to. Set voice rules: what Zomato would say and what it never would.</p><div class="out">Output: strategic territory, voice guardrails</div></div></div>
    <div class="layer"><div><h3>Design</h3><p>Build content architecture, platform roles (Instagram for culture and moments, X for real-time wit, YouTube for long-form), cultural calendar, creator strategy and campaign architecture.</p><div class="out">Output: annual roadmap, platform roles, talent map</div></div></div>
    <div class="layer"><div><h3>Operationalise</h3><p>Team structure, approval flows with a fast lane for reactive content, brand-safety and crisis protocols, weekly sync, monthly review, quarterly reset.</p><div class="out">Output: workflow, SOPs, escalation tree</div></div></div>
    <div class="layer"><div><h3>Measure and evolve</h3><p>KPIs by layer, dashboards, and a quarterly review where we kill, keep or scale ideas. The plan is a living document, not a PDF.</p><div class="out">Output: KPI framework, review cadence</div></div></div>
  </div>

  <div class="card" style="margin-top:22px"><h3>Research and tools</h3><p>Primary research (interviews, surveys) combined with secondary research, rather than relying on social metrics alone.</p>
    <p><span class="pill">Listening</span> Brandwatch, Talkwalker, Meltwater <span class="pill">Competitor ads</span> Meta Ad Library <span class="pill">Analytics</span> Instagram Insights, YouTube Analytics <span class="pill">Search</span> Google Trends <span class="pill">Performance</span> GA4, UTM tracking, dashboards <span class="pill">Planning</span> Google Sheets, Slides, Notion <span class="pill">Creative</span> Figma, Canva</p></div>

  <h3 style="margin-top:36px">Content index</h3>
  <p class="muted small">How the plan is organised, not the ideas.</p>
  <div class="card">
    <div class="bar"><span class="l">Brand-defining moments</span><span class="t"><i style="width:20%"></i></span><span class="v">~20%</span></div><p class="small muted" style="margin:-4px 0 8px 182px">3–4 annual hero campaigns tied to cultural moments</p>
    <div class="bar"><span class="l">Always-on culture</span><span class="t"><i style="width:35%"></i></span><span class="v">~35%</span></div><p class="small muted" style="margin:-4px 0 8px 182px">Recurring formats that fans return for</p>
    <div class="bar"><span class="l">Real-time and reactive</span><span class="t"><i style="width:15%"></i></span><span class="v">~15%</span></div><p class="small muted" style="margin:-4px 0 8px 182px">Trend, news, sports and pop-culture response, with a pre-cleared approval lane</p>
    <div class="bar"><span class="l">Community and conversation</span><span class="t"><i style="width:15%"></i></span><span class="v">~15%</span></div><p class="small muted" style="margin:-4px 0 8px 182px">Replies, UGC, fan content, comment-led content</p>
    <div class="bar"><span class="l">Partnerships and creators</span><span class="t"><i style="width:10%"></i></span><span class="v">~10%</span></div><p class="small muted" style="margin:-4px 0 8px 182px">Collabs, creator-led food and city content, brand tie-ups</p>
    <div class="bar"><span class="l">Product and utility</span><span class="t"><i style="width:5%"></i></span><span class="v">~5%</span></div><p class="small muted" style="margin:-4px 0 0 182px">Features, offers and service moments in the brand’s voice</p>
  </div>

  <h3 style="margin-top:36px">Presentation index (20 slides)</h3>
  <div class="card"><div class="slides">
    <b>Understand (01–08)</b><span>01 Executive summary</span><span>02 Business context</span><span>03 Brand understanding</span><span>04 Category landscape</span><span>05 Consumer understanding</span><span>06 Brand audit</span><span>07 Social media audit</span><span>08 Strategic diagnosis</span>
    <b>Direct (09–11)</b><span>09 Annual brand strategy</span><span>10 Audience strategy</span><span>11 Content architecture</span>
    <b>Plan (12–16)</b><span>12 Campaign architecture</span><span>13 Cultural calendar</span><span>14 Creator strategy</span><span>15 Community strategy</span><span>16 Paid and organic integration</span>
    <b>Run (17–19)</b><span>17 Measurement framework</span><span>18 Execution roadmap</span><span>19 Governance</span>
    <b>Close (20)</b><span>20 Next steps</span>
  </div>
  <p class="small muted" style="margin-bottom:0">The deck opens with one slide of truth about the brand, then the diagnosis, the territory and the architecture, and ties every layer back to one question: <b>Why will people still care about Zomato next year?</b></p></div>

  <h3 style="margin-top:36px">How I would measure annual success</h3>
  <div class="tablewrap"><table style="min-width:520px">
    <tr><th>Dimension</th><th>Example metrics</th></tr>
    <tr><td>Cultural relevance</td><td>Share of conversation, organic mentions, sentiment, shares and sends</td></tr>
    <tr><td>Brand love</td><td>Comment quality, follower growth rate, returning-viewer rate</td></tr>
    <tr><td>Content effectiveness</td><td>Completion rate, engagement by format</td></tr>
    <tr><td>Business contribution</td><td>Referral traffic, app visits from social, attributed orders</td></tr>
    <tr><td>Health</td><td>Response time, brand-safety incidents, turnaround time</td></tr>
  </table></div>
  <div class="callout"><p class="big">An annual brand plan is not a calendar of festivals and posts. It explains why the brand should communicate, who with, where, how, and how success will be judged.</p></div>
</div></section>

<!-- ===================== 4 ===================== -->
<section id="s4"><div class="wrap">
  <span class="num">Section 4</span>
  <h2>A brand I admire for social media: Minimalist</h2>
  <div class="cols c2" style="align-items:center">
    <div>
      <p class="lead" style="margin-top:0">Minimalist built a loud brand in a quiet way. It competes in one of the noisiest categories in Indian D2C (skincare), and it didn’t win by being louder. It won by being clearer.</p>
    </div>
    <figure>
      <!-- Label illustration: the name is the message -->
      <svg viewBox="0 0 360 260" role="img" aria-label="Illustration of a plain dropper bottle label reading 10 percent niacinamide" style="width:100%;height:auto;max-width:360px;display:block;margin:auto">
        <rect x="120" y="14" width="40" height="34" rx="6" fill="#1b2a49"/><ellipse cx="140" cy="14" rx="14" ry="10" fill="#f2603c"/>
        <rect x="90" y="48" width="100" height="196" rx="14" fill="#ffffff" stroke="#1b2a49" stroke-width="4"/>
        <text x="140" y="100" font-family="Fraunces,serif" font-size="38" font-weight="700" fill="#1b2a49" text-anchor="middle">10%</text>
        <text x="140" y="128" font-family="Inter,sans-serif" font-size="14" font-weight="600" fill="#1b2a49" text-anchor="middle">Niacinamide</text>
        <line x1="108" y1="146" x2="172" y2="146" stroke="#eadfcf" stroke-width="3"/>
        <line x1="108" y1="162" x2="172" y2="162" stroke="#eadfcf" stroke-width="3"/>
        <line x1="108" y1="178" x2="150" y2="178" stroke="#eadfcf" stroke-width="3"/>
        <path d="M200 120 H236" stroke="#ff9f1c" stroke-width="3" stroke-linecap="round"/>
        <text x="244" y="116" font-family="Inter,sans-serif" font-size="13" font-weight="600" fill="#f2603c">The label</text>
        <text x="244" y="134" font-family="Inter,sans-serif" font-size="13" font-weight="600" fill="#f2603c">is the message</text>
      </svg>
      <figcaption>Illustration: product named by the active and its percentage.</figcaption>
    </figure>
  </div>

  <h3 style="margin-top:28px">What makes its approach distinct</h3>
  <div class="cols c2">
    <div class="card"><h3>The product name is the message</h3><p>Products are named by the active and its percentage (for example, 10% Niacinamide), and its sunscreen listing leads with “No White Cast” and “Multi-Vitamin”. The label does the job a tagline would, and social content teaches people to read it.</p></div>
    <div class="card"><h3>Education as the main creative format</h3><p>Where many competitors lead with celebrities, shades and sensorial storytelling, Minimalist leads with ingredient explainers, what a product does and doesn’t do, and honest guidance on who should not buy it. That honesty is the brand’s main asset.</p></div>
    <div class="card"><h3>Community as research</h3><p>Skincare communities (notably on Reddit and Instagram comments) shape what gets made and how it is explained. This is customer research turned into a growth engine.</p></div>
    <div class="card"><h3>Trust-led creators</h3><p>Dermatologists, educators and ingredient-literate creators rather than pure reach plays, so the endorsement carries information, not only visibility.</p></div>
    <div class="card"><h3>Consistency</h3><p>A recognisable visual and verbal system that doesn’t change with every trend, which makes the brand easy to spot in a crowded feed.</p></div>
    <div class="card"><h3>How it differs from competitors</h3><p>Dot &amp; Key leans into fun, flavours and celebrity summer campaigns (for example, Shanaya Kapoor for its Vitamin C + E sunscreen) to make SPF an everyday habit. Both routes are valid, but Minimalist is <b>explain-first</b> and Dot &amp; Key is <b>feel-first</b>. The market has plenty of the second and fewer credible examples of the first.</p></div>
  </div>

  <h3 style="margin-top:30px">What I would take from it</h3>
  <ul>
    <li>Start from one honest question: what does the customer need to understand before they trust us?</li>
    <li>Treat comments and community questions as research, not just engagement.</li>
    <li>Choose creators for the information they carry, not only their reach.</li>
    <li>Keep the visual and verbal system steady so every post builds on the last.</li>
    <li>Make ritual and proof work together: for our spray, The SPF Check gives people a reason to remember, and Spray Count gives them a reason to trust.</li>
  </ul>
</div></section>

<!-- ===================== 5 ===================== -->
<section id="s5"><div class="wrap">
  <span class="num">Section 5</span>
  <h2>Marketing publications and resources I follow</h2>
  <div class="tablewrap"><table style="min-width:520px">
    <tr><th>Resource</th><th>What I use it for</th></tr>
    <tr><td>afaqs!, Exchange4media</td><td>Indian campaign launches, category news and industry coverage</td></tr>
    <tr><td>Storyboard18, Campaign India</td><td>Brand and agency movement</td></tr>
    <tr><td>Social Samosa</td><td>Social, influencer and creator-economy coverage in India</td></tr>
    <tr><td>The Hard Copy</td><td>Indian startup, technology and business stories</td></tr>
    <tr><td>Marketing Brew, The Drum</td><td>Global marketing trends and creative campaigns</td></tr>
    <tr><td>Think with Google</td><td>Consumer behaviour and digital insights</td></tr>
    <tr><td>WARC</td><td>Marketing effectiveness and strategic case studies</td></tr>
    <tr><td>Mark Ritson, Ehrenberg-Bass Institute, Rory Sutherland</td><td>Rigorous strategy, evidence on how brands grow, behavioural thinking</td></tr>
    <tr><td>Lenny’s Newsletter</td><td>Product and growth thinking that connects to my interest in research</td></tr>
  </table></div>
  <div class="callout"><p><b>How I use them:</b> I read the trade press for what launched, and the strategy sources for why it worked or didn’t. When I find a campaign I like, I write down the consumer tension behind it before I look at the creative.</p></div>
</div></section>

<footer><div class="wrap">Sarika Dhanshree · Delhi</div></footer>

<script>
document.querySelectorAll('.tabs button').forEach(function(b){
  b.addEventListener('click',function(){
    document.querySelectorAll('.tabs button').forEach(function(x){x.setAttribute('aria-selected','false')});
    document.querySelectorAll('.kpi').forEach(function(x){x.classList.remove('on')});
    b.setAttribute('aria-selected','true');
    document.getElementById(b.dataset.k).classList.add('on');
  });
});
</script>
</body>
</html>

