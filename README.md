<canvas id="sky"></canvas>

<div class="page">

  <header class="hero">
    <p class="eyebrow">✦ profile</p>
    <h1>Kanishka Naik</h1>
    <p class="role">Software Engineer &amp; Open-Source Maintainer</p>
    <p class="stack-line">JS/TS · Elixir · Go · Solidity</p>
    <p class="stack-line muted">Exploring payments, ledgers, and distributed systems</p>
    <p class="astro">Astrophile · Tech Blogger</p>

    <a class="site-link" href="https://kanishkanaik.dev/" target="_blank" rel="noopener">kanishkanaik.dev →</a>

    <nav class="social">
      <a href="https://www.linkedin.com/in/kanishka-naik-6b5180191/" target="_blank" rel="noopener">LinkedIn</a>
      <a href="https://github.com/iamkanishka" target="_blank" rel="noopener">GitHub</a>
      <a href="https://medium.com/@kanishkanaik97" target="_blank" rel="noopener">Medium</a>
      <a href="https://bsky.app/profile/kanishkanaik.dev" target="_blank" rel="noopener">Bluesky</a>
      <a href="https://x.com/NaikKanishk1831" target="_blank" rel="noopener">X</a>
      <a href="https://mastodon.social/@kanishkanaik" target="_blank" rel="noopener">Mastodon</a>
      <a href="https://www.npmjs.com/~atomlessmind" target="_blank" rel="noopener">NPM</a>
      <a href="https://hex.pm/users/kanishkanaik" target="_blank" rel="noopener">Hex</a>
    </nav>
  </header>

  <div class="divider">✦</div>

  <section>
    <h2>About</h2>
    <p>
      I'm a Full Stack Engineer with 5+ years of experience building production-grade
      systems designed to scale. My work sits at the intersection of backend performance,
      distributed architecture, and cloud-native infrastructure — with a growing focus on
      <strong>payments</strong>, <strong>financial ledgers</strong>, and <strong>blockchain systems</strong>.
    </p>
    <p>
      I care deeply about writing software that is not only functional, but maintainable,
      observable, and resilient under pressure. Beyond engineering, I contribute to
      open-source, write about distributed systems and infrastructure on my blog, and
      spend my nights thinking about the universe.
    </p>
  </section>

  <div class="divider">✦</div>

  <section>
    <h2>What I Work With</h2>

    <div class="stackgrid">
      <div class="stackcol">
        <h3>Languages</h3>
        <div class="pills">
          <span>TypeScript</span><span>JavaScript</span><span>Elixir</span><span>Go</span><span>Solidity</span>
        </div>
      </div>
      <div class="stackcol">
        <h3>Backend</h3>
        <div class="pills">
          <span>Node.js</span><span>NestJS</span><span>Express</span><span>Phoenix (Elixir)</span>
        </div>
      </div>
      <div class="stackcol">
        <h3>Frontend</h3>
        <div class="pills">
          <span>Angular</span><span>NgRx</span><span>NGXS</span><span>Sass</span><span>Material UI</span>
        </div>
      </div>
      <div class="stackcol">
        <h3>Databases &amp; Caching</h3>
        <div class="pills">
          <span>PostgreSQL</span><span>MySQL</span><span>MongoDB</span><span>Redis</span><span>Firebase</span>
        </div>
      </div>
      <div class="stackcol">
        <h3>Infrastructure &amp; DevOps</h3>
        <div class="pills">
          <span>Docker</span><span>Kubernetes</span><span>Kafka</span><span>AWS</span><span>GitHub Actions</span><span>CircleCI</span>
        </div>
      </div>
      <div class="stackcol">
        <h3>Architecture Patterns</h3>
        <div class="pills">
          <span>Microservices</span><span>Event-Driven Systems</span><span>Domain-Driven Design</span><span>Clean Architecture</span><span>Nx Monorepos</span>
        </div>
      </div>
    </div>
  </section>

  <div class="divider">✦</div>

  <section>
    <h2>Focus Areas</h2>
    <ul class="focus-list">
      <li><strong>Payments &amp; Ledgers</strong> — Designing reliable, audit-ready financial systems with strong consistency guarantees</li>
      <li><strong>Distributed Systems</strong> — Architecting services that scale horizontally and degrade gracefully under load</li>
      <li><strong>Open Source</strong> — Maintaining libraries and tooling that improve developer experience across the ecosystem</li>
      <li><strong>Blockchain &amp; Web3</strong> — Smart contract development in Solidity; exploring decentralised financial primitives</li>
      <li><strong>Technical Writing</strong> — Breaking down complex systems thinking into accessible, practical content</li>
    </ul>
  </section>

  <div class="divider">✦</div>

  <section>
    <h2>Engineering Principles</h2>
    <ul class="principles">
      <li>Design for scale from the start — retrofitting is expensive</li>
      <li>Build systems that fail gracefully, not catastrophically</li>
      <li>Observability is not optional in production</li>
      <li>Good architecture enables fast teams, not just fast software</li>
      <li>Write code for the engineer who maintains it next</li>
    </ul>
  </section>

  <div class="divider">✦</div>

  <section class="writing">
    <h2>Writing &amp; Open Source</h2>
    <p>
      I write about distributed systems, backend architecture, and engineering trade-offs.
      If you find something useful, a ⭐ on the repo goes a long way.
    </p>
    <p class="quote">Always building. Always learning. Always scaling.</p>
  </section>

  <footer>
    <a href="https://kanishkanaik.dev/" target="_blank" rel="noopener">kanishkanaik.dev</a>
    <span class="dot">·</span>
    <a href="https://github.com/iamkanishka" target="_blank" rel="noopener">@iamkanishka</a>
  </footer>

</div>

<style>
  :root{
    --void:#03050d;
    --deep:#080d1e;
    --mid:#131b33;
    --star:#eaf1ff;
    --text:#f4f7ff;
    --muted:#93a3d1;
    --faint:#5a6a9c;
    --link:#bcd4ff;
    --gold:#ffcf8a;
    --rule: rgba(188,212,255,0.18);
  }

  *{ box-sizing:border-box; }

  html,body{
    margin:0;
    padding:0;
    background:var(--void);
    color:var(--text);
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
    min-height:100%;
  }

  #sky{
    position:fixed;
    inset:0;
    width:100%;
    height:100%;
    z-index:0;
    background:
      radial-gradient(ellipse 120% 60% at 50% 0%, var(--mid) 0%, var(--deep) 45%, var(--void) 100%);
  }

  .page{
    position:relative;
    z-index:1;
    max-width:760px;
    margin:0 auto;
    padding:96px 28px 120px;
  }

  .hero{ text-align:center; padding-bottom:8px; }

  .eyebrow{
    font-family:"Courier New",monospace;
    letter-spacing:4px;
    font-size:12px;
    color:var(--faint);
    text-transform:uppercase;
    margin:0 0 18px;
  }

  h1{
    font-family:Georgia,"Iowan Old Style","Times New Roman",serif;
    font-weight:600;
    font-size:clamp(40px,7vw,64px);
    letter-spacing:2px;
    margin:0 0 14px;
    color:var(--text);
    text-shadow:0 0 40px rgba(188,212,255,0.15);
  }

  .role{
    font-family:"Courier New",monospace;
    font-size:17px;
    letter-spacing:1px;
    color:var(--text);
    margin:0 0 20px;
  }

  .stack-line{
    font-family:"Courier New",monospace;
    font-size:13.5px;
    letter-spacing:0.5px;
    color:var(--muted);
    margin:4px 0;
  }
  .stack-line.muted{ color:var(--faint); }

  .astro{
    font-family:"Courier New",monospace;
    font-style:italic;
    font-size:12.5px;
    color:var(--faint);
    margin:16px 0 28px;
  }

  .site-link{
    display:inline-block;
    color:var(--gold);
    text-decoration:none;
    font-family:"Courier New",monospace;
    font-size:14px;
    letter-spacing:0.5px;
    border-bottom:1px solid rgba(255,207,138,0.4);
    padding-bottom:2px;
    margin-bottom:32px;
    transition:opacity 0.2s ease, border-color 0.2s ease;
  }
  .site-link:hover{ opacity:0.8; border-color:var(--gold); }

  .social{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:6px 4px;
    margin-top:8px;
  }
  .social a{
    color:var(--link);
    text-decoration:none;
    font-family:"Courier New",monospace;
    font-size:12.5px;
    padding:7px 13px;
    border:1px solid var(--rule);
    border-radius:20px;
    transition:background 0.2s ease, color 0.2s ease, border-color 0.2s ease;
    background:rgba(19,27,51,0.4);
  }
  .social a:hover{
    color:var(--void);
    background:var(--link);
    border-color:var(--link);
  }

  .divider{
    text-align:center;
    color:var(--faint);
    font-size:14px;
    margin:56px 0;
    letter-spacing:8px;
  }

  section{ margin-bottom:8px; }

  h2{
    font-family:Georgia,"Iowan Old Style","Times New Roman",serif;
    font-weight:600;
    font-size:26px;
    letter-spacing:0.5px;
    color:var(--text);
    margin:0 0 20px;
  }

  h3{
    font-family:"Courier New",monospace;
    font-size:12px;
    letter-spacing:1.5px;
    text-transform:uppercase;
    color:var(--gold);
    margin:0 0 10px;
    font-weight:400;
  }

  p{
    font-size:15.5px;
    line-height:1.75;
    color:#dbe4fb;
    margin:0 0 16px;
  }

  strong{ color:var(--text); font-weight:600; }

  .stackgrid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:28px 32px;
  }
  @media (max-width:560px){
    .stackgrid{ grid-template-columns:1fr; }
  }

  .pills{
    display:flex;
    flex-wrap:wrap;
    gap:7px;
  }
  .pills span{
    font-family:"Courier New",monospace;
    font-size:12.5px;
    color:var(--muted);
    border:1px solid var(--rule);
    border-radius:5px;
    padding:5px 10px;
    background:rgba(19,27,51,0.4);
  }

  .focus-list, .principles{
    list-style:none;
    margin:0;
    padding:0;
  }
  .focus-list li, .principles li{
    position:relative;
    padding-left:24px;
    margin-bottom:16px;
    font-size:15.5px;
    line-height:1.7;
    color:#dbe4fb;
  }
  .focus-list li::before, .principles li::before{
    content:"✦";
    position:absolute;
    left:0;
    top:1px;
    color:var(--gold);
    font-size:12px;
  }

  .writing .quote{
    font-family:Georgia,"Iowan Old Style",serif;
    font-style:italic;
    font-size:18px;
    color:var(--text);
    text-align:center;
    margin-top:28px;
    letter-spacing:0.5px;
  }

  footer{
    text-align:center;
    margin-top:80px;
    font-family:"Courier New",monospace;
    font-size:13px;
    color:var(--faint);
  }
  footer a{
    color:var(--muted);
    text-decoration:none;
  }
  footer a:hover{ color:var(--gold); }
  footer .dot{ margin:0 10px; }

  @media (prefers-reduced-motion: reduce){
    #sky{ animation:none !important; }
  }
</style>

<script>
(function(){
  var canvas = document.getElementById('sky');
  var ctx = canvas.getContext('2d');
  var reduced = window.matchMedia && window.matchMedia('(prefers-reduced-motion: reduce)').matches;

  var w, h, dpr;
  function resize(){
    dpr = Math.min(window.devicePixelRatio || 1, 2);
    w = window.innerWidth;
    h = document.documentElement.scrollHeight;
    canvas.width = w * dpr;
    canvas.height = h * dpr;
    canvas.style.width = w + 'px';
    canvas.style.height = h + 'px';
    ctx.setTransform(dpr,0,0,dpr,0,0);
    buildStars();
  }

  var stars = [];
  function buildStars(){
    stars = [];
    var count = Math.floor((w*h) / 5200);
    for(var i=0;i<count;i++){
      stars.push({
        x: Math.random()*w,
        y: Math.random()*h,
        r: Math.random()*1.4 + 0.3,
        base: Math.random()*0.35 + 0.25,
        amp: Math.random()*0.45 + 0.25,
        speed: Math.random()*0.015 + 0.006,
        phase: Math.random()*Math.PI*2
      });
    }
  }

  var meteors = [];
  function spawnMeteor(){
    var cx = w/2, cy = h/2;
    var R = Math.hypot(w,h) * 0.62;
    var startAngle = Math.random()*Math.PI*2;
    var sx = cx + R*Math.cos(startAngle);
    var sy = cy + R*Math.sin(startAngle);
    var dirAngle = startAngle + Math.PI + (Math.random()-0.5)*1.6;
    var speed = Math.random()*3.5 + 3.5;
    var warm = Math.random() < 0.28;
    meteors.push({
      x:sx, y:sy,
      vx: Math.cos(dirAngle)*speed,
      vy: Math.sin(dirAngle)*speed,
      len: Math.random()*90 + 50,
      age:0,
      max: Math.random()*70 + 70,
      color: warm ? '255,214,163' : '255,255,255'
    });
  }

  var t = 0;
  var nextSpawn = 0;

  function frame(){
    t++;
    ctx.clearRect(0,0,w,h);

    for(var i=0;i<stars.length;i++){
      var s = stars[i];
      var op = reduced ? s.base + s.amp*0.5 : s.base + Math.sin(t*s.speed + s.phase) * s.amp;
      ctx.beginPath();
      ctx.fillStyle = 'rgba(234,241,255,'+Math.max(0,Math.min(1,op))+')';
      ctx.arc(s.x, s.y, s.r, 0, Math.PI*2);
      ctx.fill();
    }

    if(!reduced){
      if(t > nextSpawn && meteors.length < 7){
        spawnMeteor();
        nextSpawn = t + Math.random()*70 + 30;
      }

      for(var j=meteors.length-1;j>=0;j--){
        var m = meteors[j];
        m.x += m.vx;
        m.y += m.vy;
        m.age++;

        var op2 = 1;
        if(m.age < 12) op2 = m.age/12;
        else if(m.age > m.max-18) op2 = Math.max(0,(m.max-m.age)/18);

        var speedMag = Math.hypot(m.vx,m.vy);
        var tx = m.x - (m.vx/speedMag)*m.len;
        var ty = m.y - (m.vy/speedMag)*m.len;

        var grad = ctx.createLinearGradient(m.x,m.y,tx,ty);
        grad.addColorStop(0, 'rgba('+m.color+','+op2+')');
        grad.addColorStop(1, 'rgba('+m.color+',0)');

        ctx.strokeStyle = grad;
        ctx.lineWidth = 1.4;
        ctx.lineCap = 'round';
        ctx.beginPath();
        ctx.moveTo(m.x,m.y);
        ctx.lineTo(tx,ty);
        ctx.stroke();

        ctx.beginPath();
        ctx.fillStyle = 'rgba('+m.color+','+op2+')';
        ctx.arc(m.x,m.y,1.3,0,Math.PI*2);
        ctx.fill();

        if(m.age > m.max || m.x < -300 || m.x > w+300 || m.y < -300 || m.y > h+300){
          meteors.splice(j,1);
        }
      }
    }

    requestAnimationFrame(frame);
  }

  window.addEventListener('resize', resize);
  resize();
  requestAnimationFrame(frame);
})();
</script>
