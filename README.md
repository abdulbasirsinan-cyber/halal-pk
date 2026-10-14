
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#07130e">
<meta name="description" content="Discover Halal PK — a community-focused digital token project.">
<title>Halal PK | A New Digital Community</title>
<style>
:root{--bg:#07130e;--panel:#0e2118;--green:#39e58c;--muted:#a8b9ae;--white:#f4fff7;--line:#244432}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--white);font-family:Arial,Helvetica,sans-serif;line-height:1.6}
a{color:inherit;text-decoration:none}
nav{position:sticky;top:0;z-index:5;display:flex;justify-content:space-between;align-items:center;gap:16px;padding:18px 7%;background:#07130eeb;border-bottom:1px solid var(--line);backdrop-filter:blur(12px)}
.logo{font-size:22px;font-weight:900;letter-spacing:-1px}
.logo span{color:var(--green)}
.links{display:flex;gap:22px;font-size:13px;color:var(--muted)}
.links a:hover{color:var(--green)}
.btn{display:inline-block;padding:12px 19px;border-radius:9px;background:var(--green);color:#06140c;font-weight:800;font-size:14px}
.btn.outline{background:transparent;color:var(--green);border:1px solid var(--green)}
.hero{padding:90px 7% 75px;display:grid;grid-template-columns:1.15fr .85fr;gap:40px;align-items:center;background:radial-gradient(ellipse at 80% 35%,#16482a55,transparent 55%)}
.eyebrow{color:var(--green);font-size:12px;font-weight:800;letter-spacing:3px;text-transform:uppercase}
h1{font-size:clamp(46px,7vw,82px);line-height:1.02;letter-spacing:-4px;margin:20px 0}
h1 span{color:var(--green)}
p{color:var(--muted)}
.hero p{font-size:17px;max-width:540px}
.actions{display:flex;flex-wrap:wrap;gap:12px;margin-top:28px}
.coin-wrap{display:grid;place-items:center;min-height:300px}
.coin{width:min(270px,68vw);aspect-ratio:1;border-radius:50%;display:grid;place-items:center;background:radial-gradient(circle at 35% 25%,#8affbd,#19a85d 35%,#07552e 72%,#042b18);border:8px solid #4ef09a;box-shadow:0 0 35px #39e58c55,0 0 110px #1ac66b22,inset 0 0 28px #c0ffd455}
.coin strong{font-size:62px;color:#042b18;text-shadow:0 2px 0 #a5ffc9}
section{padding:75px 7%}
.section-title{text-align:center;max-width:700px;margin:0 auto 38px}
h2{font-size:clamp(30px,4vw,44px);line-height:1.15;margin:12px 0}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.card{padding:26px;border:1px solid var(--line);border-radius:17px;background:linear-gradient(145deg,#10251a,#0a1811)}
.card .icon{font-size:28px}
.card h3{margin:13px 0 7px}
.card p{font-size:14px;margin-bottom:0}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:30px}
.stat{padding:23px 12px;text-align:center;border:1px solid var(--line);border-radius:14px;background:#0c1c13}
.stat strong{display:block;font-size:clamp(20px,3vw,30px);color:var(--green)}
.stat span{font-size:12px;color:var(--muted)}
.roadmap{max-width:700px;margin:auto}
.step{display:flex;gap:18px;padding:20px 0;border-bottom:1px solid var(--line)}
.dot{flex-shrink:0;width:13px;height:13px;margin-top:8px;border-radius:50%;background:var(--green);box-shadow:0 0 14px #39e58c66}
.step h3{margin:0}
.step p{margin:4px 0 0;font-size:14px}
.banner{text-align:center;padding:48px 24px;border:1px solid #28623f;border-radius:22px;background:radial-gradient(ellipse at top,#1b573333,transparent 75%),#0b1c12}
footer{padding:30px 7%;border-top:1px solid var(--line);display:flex;justify-content:space-between;gap:18px;flex-wrap:wrap}
footer p{font-size:12px;margin:5px 0}
.notice{text-align:center;background:#18251b;color:#c9d9cd;padding:13px 7%;font-size:12px;border-top:1px solid var(--line)}
@media(max-width:760px){nav{padding:15px 5%}.links{gap:12px;font-size:12px}.links a:nth-child(2){display:none}.hero{grid-template-columns:1fr;text-align:center;padding:65px 6% 45px}h1{letter-spacing:-2px}.hero p{margin:auto}.actions{justify-content:center}.coin-wrap{min-height:230px}.coin{width:205px}.coin strong{font-size:48px}section{padding:55px 6%}.grid{grid-template-columns:1fr}.stats{grid-template-columns:1fr}.section-title{margin-bottom:26px}}
</style>
</head>
<body>
<nav>
  <a class="logo" href="#home">HALAL<span> PK</span></a>
  <div class="links">
    <a href="#about">About</a>
    <a href="#token">Token</a>
    <a href="#roadmap">Roadmap</a>
  </div>
  <a class="btn" href="#token">Explore HPK</a>
</nav>

<main>
<section class="hero" id="home">
  <div>
    <div class="eyebrow">A Community Token Project</div>
    <h1>Welcome to<br><span>Halal PK.</span></h1>
    <p>A digital token project with a community-first vision. Discover the idea, follow the progress, and join us as the project develops.</p>
    <div class="actions">
      <a class="btn" href="#about">Discover the Project ↗</a>
      <a class="btn outline" href="#roadmap">View Roadmap</a>
    </div>
  </div>
  <div class="coin-wrap">
    <div class="coin"><strong>HPK</strong></div>
  </div>
</section>

<section id="about">
  <div class="section-title">
    <div class="eyebrow">The Vision</div>
    <h2>Built around a <span style="color:var(--green)">community.</span></h2>
    <p>Halal PK is at an early development stage. Our first goal is to share clear information, build a community, and work transparently toward future milestones.</p>
  </div>
  <div class="grid">
    <article class="card">
      <div class="icon">🌱</div>
      <h3>Early beginnings</h3>
      <p>Starting with a clear concept and a website to share project updates.</p>
    </article>
    <article class="card">
      <div class="icon">🔎</div>
      <h3>Transparency</h3>
      <p>Project status and future developments should be communicated honestly.</p>
    </article>
    <article class="card">
      <div class="icon">🤝</div>
      <h3>Community first</h3>
      <p>A place to follow progress and learn about the project as it grows.</p>
    </article>
  </div>
</section>

<section id="token">
  <div class="section-title">
    <div class="eyebrow">Token Overview</div>
    <h2>Meet <span style="color:var(--green)">HPK.</span></h2>
    <p>Current project information. A test deployment is not a live public blockchain launch.</p>
  </div>
  <div class="stats">
    <div class="stat"><strong>HPK</strong><span>Token symbol</span></div>
    <div class="stat"><strong>1 Billion</strong><span>Planned token supply</span></div>
    <div class="stat"><strong>In Development</strong><span>Launch status</span></div>
  </div>
  <p style="text-align:center;font-size:13px;margin-top:22px">Blockchain: not yet launched publicly · Contract address: not available</p>
</section>

<section id="roadmap">
  <div class="section-title">
    <div class="eyebrow">The Journey</div>
    <h2>Project roadmap</h2>
    <p>These are goals, not completed promises. Timing may change as development progresses.</p>
  </div>
  <div class="roadmap">
    <div class="step"><div class="dot"></div><div><h3>01 — Project concept</h3><p>Define the name, initial token concept, and project direction.</p></div></div>
    <div class="step"><div class="dot"></div><div><h3>02 — Website launch</h3><p>Publish a home for project information and future updates.</p></div></div>
    <div class="step"><div class="dot"></div><div><h3>03 — Research and review</h3><p>Research network choices, contract safety, legal requirements, and costs.</p></div></div>
    <div class="step"><div class="dot"></div><div><h3>04 — Future blockchain launch</h3><p>Planned only. Requires further testing, funding, and a deliberate launch decision.</p></div></div>
  </div>
</section>

<section>
  <div class="banner">
    <div class="eyebrow">Follow the journey</div>
    <h2>Halal PK starts here.</h2>
    <p>Visit again for future project updates.</p>
    <a class="btn" href="#home">Back to Top ↑</a>
  </div>
</section>
</main>

<div class="notice">HPK is a project in development, not currently available for public trading. No investment return is promised.</div>
<footer>
  <div class="logo">HALAL<span style="color:var(--green)"> PK</span></div>
  <p>© 2026 Halal PK Project. All rights reserved.</p>
  <p>Built to share project information transparently.</p>
</footer>
</body>
</html>
