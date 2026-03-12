<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ratthaphon Khan — Portfolio</title>
  <meta name="description" content="Infrastructure · Full-Stack Engineer · AI Developer · KU SRC"/>
  <link rel="preconnect" href="https://fonts.googleapis.com"/>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
  <link href="https://fonts.googleapis.com/css2?family=Spectral:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Outfit:wght@200;300;400;500;600&display=swap" rel="stylesheet"/>
  <style>
    :root {
      --bg:        #141618;
      --bg2:       #1c1f23;
      --bg3:       #1f2329;
      --border:    #2a2e34;
      --accent:    #8fa8c8;
      --accent2:   #4a6a9a;
      --text:      #e8ecf0;
      --muted:     #a0aab8;
      --dim:       #5a6570;
      --faint:     #3a4550;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'Outfit', sans-serif;
      font-weight: 300;
      line-height: 1.6;
      overflow-x: hidden;
      cursor: none;
    }

    /* ── CUSTOM CURSOR ── */
    .cursor {
      width: 10px; height: 10px;
      background: var(--accent);
      border-radius: 50%;
      position: fixed;
      pointer-events: none;
      z-index: 9999;
      transition: transform 0.15s ease, opacity 0.15s;
      transform: translate(-50%, -50%);
    }
    .cursor-ring {
      width: 36px; height: 36px;
      border: 1px solid var(--accent);
      border-radius: 50%;
      position: fixed;
      pointer-events: none;
      z-index: 9998;
      transition: transform 0.35s ease, width 0.3s, height 0.3s, opacity 0.3s;
      transform: translate(-50%, -50%);
      opacity: 0.4;
    }
    body:hover .cursor { opacity: 1; }

    /* ── NOISE OVERLAY ── */
    body::before {
      content: '';
      position: fixed; inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      background-size: 200px;
      pointer-events: none;
      z-index: 0;
      opacity: 0.4;
    }

    /* ── GRID BG ── */
    body::after {
      content: '';
      position: fixed; inset: 0;
      background-image:
        linear-gradient(rgba(143,168,200,0.025) 1px, transparent 1px),
        linear-gradient(90deg, rgba(143,168,200,0.025) 1px, transparent 1px);
      background-size: 48px 48px;
      pointer-events: none;
      z-index: 0;
    }

    /* ── NAV ── */
    nav {
      position: fixed; top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 20px 48px;
      background: rgba(20,22,24,0.85);
      backdrop-filter: blur(16px);
      border-bottom: 1px solid var(--border);
      transition: padding 0.3s;
    }
    nav.scrolled { padding: 14px 48px; }
    .nav-logo {
      font-family: 'Spectral', serif;
      font-size: 18px;
      font-weight: 600;
      color: var(--accent);
      letter-spacing: 0.5px;
      font-style: italic;
    }
    .nav-links { display: flex; gap: 36px; list-style: none; }
    .nav-links a {
      color: var(--dim);
      text-decoration: none;
      font-size: 11px;
      letter-spacing: 3px;
      text-transform: uppercase;
      transition: color 0.2s;
      font-weight: 400;
    }
    .nav-links a:hover { color: var(--accent); }

    /* ── SECTIONS ── */
    section { position: relative; z-index: 1; }

    /* ── HERO ── */
    #hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      padding: 120px 48px 80px;
      position: relative;
      overflow: hidden;
    }

    .hero-accent-line {
      position: absolute;
      top: 0; left: 0; right: 0;
      height: 3px;
      background: linear-gradient(90deg, transparent, var(--accent), var(--accent2), transparent);
    }

    /* Decorative orbs */
    .orb {
      position: absolute;
      border-radius: 50%;
      filter: blur(80px);
      pointer-events: none;
    }
    .orb-1 {
      width: 500px; height: 500px;
      background: radial-gradient(circle, rgba(143,168,200,0.06) 0%, transparent 70%);
      top: -100px; right: -100px;
    }
    .orb-2 {
      width: 300px; height: 300px;
      background: radial-gradient(circle, rgba(74,106,154,0.08) 0%, transparent 70%);
      bottom: 0; left: 200px;
    }

    .hero-content { max-width: 700px; }

    .hero-eyebrow {
      font-size: 11px;
      letter-spacing: 5px;
      color: var(--accent);
      text-transform: uppercase;
      margin-bottom: 20px;
      opacity: 0;
      animation: fadeUp 0.8s ease 0.2s forwards;
    }

    .hero-name {
      font-family: 'Spectral', serif;
      font-size: clamp(48px, 7vw, 80px);
      font-weight: 300;
      line-height: 1.05;
      letter-spacing: -0.5px;
      color: var(--text);
      opacity: 0;
      animation: fadeUp 0.8s ease 0.35s forwards;
    }
    .hero-name em {
      font-style: italic;
      font-weight: 600;
      color: var(--accent);
    }

    .hero-roles {
      margin-top: 24px;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      opacity: 0;
      animation: fadeUp 0.8s ease 0.5s forwards;
    }
    .role-chip {
      border: 1px solid var(--border);
      color: var(--muted);
      padding: 6px 16px;
      font-size: 11px;
      letter-spacing: 2px;
      text-transform: uppercase;
      font-weight: 400;
      background: var(--bg2);
      transition: all 0.25s;
    }
    .role-chip:hover {
      border-color: var(--accent);
      color: var(--accent);
      background: rgba(143,168,200,0.05);
    }

    .hero-desc {
      margin-top: 28px;
      font-size: 15px;
      color: var(--dim);
      font-weight: 200;
      max-width: 480px;
      line-height: 1.8;
      opacity: 0;
      animation: fadeUp 0.8s ease 0.65s forwards;
    }

    .hero-cta {
      margin-top: 40px;
      display: flex;
      gap: 16px;
      opacity: 0;
      animation: fadeUp 0.8s ease 0.8s forwards;
    }
    .btn-primary {
      background: var(--accent);
      color: var(--bg);
      border: none;
      padding: 12px 28px;
      font-size: 11px;
      letter-spacing: 3px;
      text-transform: uppercase;
      font-weight: 600;
      text-decoration: none;
      font-family: 'Outfit';
      transition: all 0.25s;
      cursor: none;
    }
    .btn-primary:hover { background: #b0c8e8; transform: translateY(-2px); }
    .btn-ghost {
      border: 1px solid var(--border);
      color: var(--muted);
      padding: 12px 28px;
      font-size: 11px;
      letter-spacing: 3px;
      text-transform: uppercase;
      font-weight: 400;
      text-decoration: none;
      font-family: 'Outfit';
      transition: all 0.25s;
      cursor: none;
      background: transparent;
    }
    .btn-ghost:hover { border-color: var(--accent); color: var(--accent); transform: translateY(-2px); }

    /* Hero stats */
    .hero-stats {
      position: absolute;
      right: 48px;
      top: 50%;
      transform: translateY(-50%);
      display: flex;
      flex-direction: column;
      gap: 32px;
      opacity: 0;
      animation: fadeIn 1s ease 1s forwards;
    }
    .hero-stat {
      text-align: right;
      border-right: 2px solid var(--border);
      padding-right: 20px;
      transition: border-color 0.25s;
    }
    .hero-stat:hover { border-color: var(--accent); }
    .hero-stat-n {
      font-family: 'Spectral', serif;
      font-size: 38px;
      font-weight: 300;
      color: var(--accent);
      line-height: 1;
    }
    .hero-stat-l {
      font-size: 9px;
      color: var(--faint);
      letter-spacing: 3px;
      text-transform: uppercase;
      margin-top: 4px;
    }

    /* ── SECTION COMMON ── */
    .section-inner {
      max-width: 960px;
      margin: 0 auto;
      padding: 100px 48px;
    }
    .section-label {
      font-size: 10px;
      letter-spacing: 6px;
      color: var(--accent);
      text-transform: uppercase;
      margin-bottom: 48px;
      display: flex;
      align-items: center;
      gap: 16px;
    }
    .section-label::before {
      content: '';
      width: 32px; height: 1px;
      background: var(--accent);
    }
    .section-label::after {
      content: '';
      flex: 1; height: 1px;
      background: linear-gradient(90deg, var(--border), transparent);
    }

    /* ── ABOUT ── */
    #about { border-top: 1px solid var(--border); }
    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 64px;
      align-items: start;
    }
    .about-text h2 {
      font-family: 'Spectral', serif;
      font-size: 36px;
      font-weight: 300;
      color: var(--text);
      line-height: 1.25;
      margin-bottom: 24px;
    }
    .about-text h2 em { color: var(--accent); font-style: italic; }
    .about-text p {
      font-size: 14px;
      color: var(--dim);
      line-height: 1.9;
      font-weight: 200;
      margin-bottom: 16px;
    }
    .about-info {
      display: flex;
      flex-direction: column;
      gap: 0;
      border: 1px solid var(--border);
    }
    .info-row {
      display: flex;
      align-items: center;
      padding: 14px 20px;
      border-bottom: 1px solid var(--border);
      transition: background 0.2s;
    }
    .info-row:last-child { border-bottom: none; }
    .info-row:hover { background: var(--bg2); }
    .info-label {
      font-size: 9px;
      letter-spacing: 3px;
      text-transform: uppercase;
      color: var(--faint);
      width: 100px;
      flex-shrink: 0;
    }
    .info-value { font-size: 13px; color: var(--muted); font-weight: 300; }
    .info-value a { color: var(--accent); text-decoration: none; }
    .info-value a:hover { text-decoration: underline; }

    /* ── STACK ── */
    #stack { border-top: 1px solid var(--border); }
    .stack-groups {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 1px;
      background: var(--border);
      border: 1px solid var(--border);
    }
    .stack-group {
      background: var(--bg);
      padding: 28px 32px;
      transition: background 0.2s;
    }
    .stack-group:hover { background: var(--bg2); }
    .stack-group-title {
      font-size: 9px;
      letter-spacing: 3px;
      text-transform: uppercase;
      color: var(--accent);
      margin-bottom: 16px;
      font-weight: 400;
    }
    .stack-tags { display: flex; flex-wrap: wrap; gap: 8px; }
    .stack-tag {
      background: rgba(143,168,200,0.06);
      border: 1px solid rgba(143,168,200,0.15);
      color: var(--muted);
      padding: 4px 14px;
      font-size: 11px;
      letter-spacing: 1px;
      font-weight: 300;
      transition: all 0.2s;
    }
    .stack-tag:hover {
      border-color: var(--accent);
      color: var(--accent);
      background: rgba(143,168,200,0.08);
    }

    /* ── PROJECTS ── */
    #projects { border-top: 1px solid var(--border); }
    .projects-grid {
      display: flex;
      flex-direction: column;
      gap: 1px;
      background: var(--border);
      border: 1px solid var(--border);
    }
    .proj-card {
      background: var(--bg);
      padding: 32px 36px;
      display: grid;
      grid-template-columns: 1fr auto;
      gap: 24px;
      align-items: start;
      transition: background 0.25s;
      position: relative;
      overflow: hidden;
    }
    .proj-card::before {
      content: '';
      position: absolute;
      left: 0; top: 0; bottom: 0;
      width: 3px;
      background: transparent;
      transition: background 0.25s;
    }
    .proj-card:hover { background: var(--bg2); }
    .proj-card:hover::before { background: var(--accent); }

    .proj-number {
      font-family: 'Spectral', serif;
      font-size: 11px;
      color: rgba(143,168,200,0.2);
      letter-spacing: 2px;
      margin-bottom: 10px;
    }
    .proj-name {
      font-family: 'Spectral', serif;
      font-size: 20px;
      font-weight: 600;
      color: var(--text);
      margin-bottom: 8px;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .proj-desc {
      font-size: 13px;
      color: var(--dim);
      font-weight: 200;
      line-height: 1.7;
      max-width: 500px;
      margin-bottom: 16px;
    }
    .proj-modules {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-bottom: 14px;
    }
    .proj-module {
      background: var(--bg3);
      border: 1px solid var(--border);
      color: var(--faint);
      padding: 3px 12px;
      font-size: 10px;
      letter-spacing: 1px;
      font-weight: 300;
    }
    .proj-tags { display: flex; flex-wrap: wrap; gap: 8px; }
    .proj-tag {
      background: rgba(143,168,200,0.05);
      border: 1px solid rgba(143,168,200,0.15);
      color: var(--accent);
      padding: 3px 12px;
      font-size: 10px;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      font-weight: 400;
    }
    .proj-right { text-align: right; }
    .proj-status {
      display: inline-block;
      font-size: 9px;
      letter-spacing: 2px;
      text-transform: uppercase;
      padding: 6px 14px;
      border: 1px solid;
      font-weight: 400;
      margin-bottom: 12px;
    }
    .proj-link {
      display: block;
      font-size: 10px;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--faint);
      text-decoration: none;
      transition: color 0.2s;
      margin-top: 8px;
    }
    .proj-link:hover { color: var(--accent); }

    /* ── CONTACT ── */
    #contact { border-top: 1px solid var(--border); }
    .contact-inner {
      text-align: center;
      max-width: 560px;
      margin: 0 auto;
    }
    .contact-inner h2 {
      font-family: 'Spectral', serif;
      font-size: 42px;
      font-weight: 300;
      color: var(--text);
      line-height: 1.15;
      margin-bottom: 16px;
    }
    .contact-inner h2 em { color: var(--accent); font-style: italic; }
    .contact-inner p {
      font-size: 14px;
      color: var(--dim);
      font-weight: 200;
      line-height: 1.8;
      margin-bottom: 36px;
    }
    .contact-links {
      display: flex;
      justify-content: center;
      gap: 16px;
      flex-wrap: wrap;
    }
    .contact-link {
      border: 1px solid var(--border);
      color: var(--muted);
      padding: 12px 24px;
      font-size: 10px;
      letter-spacing: 3px;
      text-transform: uppercase;
      text-decoration: none;
      font-weight: 400;
      transition: all 0.25s;
      font-family: 'Outfit';
      display: flex;
      align-items: center;
      gap: 8px;
      background: var(--bg2);
    }
    .contact-link:hover {
      border-color: var(--accent);
      color: var(--accent);
      background: rgba(143,168,200,0.05);
      transform: translateY(-2px);
    }

    /* ── FOOTER ── */
    footer {
      border-top: 1px solid var(--border);
      padding: 24px 48px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: relative;
      z-index: 1;
    }
    .footer-left {
      font-family: 'Spectral', serif;
      font-size: 13px;
      color: var(--faint);
      font-style: italic;
    }
    .footer-right {
      font-size: 9px;
      letter-spacing: 3px;
      text-transform: uppercase;
      color: var(--faint);
    }
    .footer-bar {
      position: absolute;
      bottom: 0; left: 0; right: 0;
      height: 2px;
      background: linear-gradient(90deg, transparent, var(--accent), var(--accent2), transparent);
    }

    /* ── ANIMATIONS ── */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(20px); }
      to   { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to   { opacity: 1; }
    }
    .reveal {
      opacity: 0;
      transform: translateY(24px);
      transition: opacity 0.7s ease, transform 0.7s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: none;
    }

    /* ── SCROLLBAR ── */
    ::-webkit-scrollbar { width: 4px; }
    ::-webkit-scrollbar-track { background: var(--bg); }
    ::-webkit-scrollbar-thumb { background: var(--faint); border-radius: 2px; }
    ::-webkit-scrollbar-thumb:hover { background: var(--accent); }
  </style>
</head>
<body>

  <div class="cursor" id="cursor"></div>
  <div class="cursor-ring" id="cursorRing"></div>

  <!-- NAV -->
  <nav id="nav">
    <div class="nav-logo">RK</div>
    <ul class="nav-links">
      <li><a href="#about">About</a></li>
      <li><a href="#stack">Stack</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
      <li><a href="https://github.com/ratthaphon0" target="_blank">GitHub ↗</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section id="hero">
    <div class="hero-accent-line"></div>
    <div class="orb orb-1"></div>
    <div class="orb orb-2"></div>

    <div class="hero-content">
      <div class="hero-eyebrow">Software Engineer · Bangkok, TH</div>
      <h1 class="hero-name">Ratthaphon<br/><em>Khan</em></h1>
      <div class="hero-roles">
        <span class="role-chip">Infrastructure</span>
        <span class="role-chip">Full-Stack Dev</span>
        <span class="role-chip">AI Developer</span>
        <span class="role-chip">KU SRC</span>
      </div>
      <p class="hero-desc">
        Building intelligent systems and scalable applications. Student at Kasetsart University, passionate about AI, full-stack engineering, and collaborative development.
      </p>
      <div class="hero-cta">
        <a href="#projects" class="btn-primary">View Projects</a>
        <a href="https://github.com/ratthaphon0" target="_blank" class="btn-ghost">GitHub Profile</a>
      </div>
    </div>

    <div class="hero-stats">
      <div class="hero-stat">
        <div class="hero-stat-n">177</div>
        <div class="hero-stat-l">Contributions</div>
      </div>
      <div class="hero-stat">
        <div class="hero-stat-n">10</div>
        <div class="hero-stat-l">Repositories</div>
      </div>
      <div class="hero-stat">
        <div class="hero-stat-n">4+</div>
        <div class="hero-stat-l">Team Projects</div>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <div class="section-inner">
      <div class="section-label reveal">About</div>
      <div class="about-grid">
        <div class="about-text reveal">
          <h2>Engineer &amp;<br/><em>Problem Solver</em></h2>
          <p>I'm a software engineering student at Kasetsart University (KU SRC), specialising in infrastructure, full-stack development, and AI-driven systems.</p>
          <p>I enjoy working at the intersection of hardware, data, and intelligent software — building things that are both technically sound and genuinely useful.</p>
          <p>Currently developing several collaborative projects including underwater monitoring systems, smart IoT solutions, and e-commerce platforms.</p>
        </div>
        <div class="about-info reveal">
          <div class="info-row">
            <span class="info-label">Location</span>
            <span class="info-value">Chonburi, Thailand</span>
          </div>
          <div class="info-row">
            <span class="info-label">University</span>
            <span class="info-value">Kasetsart University (KU SRC)</span>
          </div>
          <div class="info-row">
            <span class="info-label">Role</span>
            <span class="info-value">Infrastructure · Full-Stack · AI</span>
          </div>
          <div class="info-row">
            <span class="info-label">GitHub</span>
            <span class="info-value"><a href="https://github.com/ratthaphon0" target="_blank">ratthaphon0 ↗</a></span>
          </div>
          <div class="info-row">
            <span class="info-label">Status</span>
            <span class="info-value" style="color:#7aaa70">● Open to collaboration</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- STACK -->
  <section id="stack">
    <div class="section-inner">
      <div class="section-label reveal">Stack</div>
      <div class="stack-groups reveal">
        <div class="stack-group">
          <div class="stack-group-title">Languages</div>
          <div class="stack-tags">
            <span class="stack-tag">Python</span>
            <span class="stack-tag">JavaScript</span>
            <span class="stack-tag">SQL</span>
            <span class="stack-tag">HTML / CSS</span>
          </div>
        </div>
        <div class="stack-group">
          <div class="stack-group-title">Frontend</div>
          <div class="stack-tags">
            <span class="stack-tag">React</span>
            <span class="stack-tag">HTML5</span>
            <span class="stack-tag">CSS3</span>
            <span class="stack-tag">Tailwind</span>
          </div>
        </div>
        <div class="stack-group">
          <div class="stack-group-title">Backend &amp; Data</div>
          <div class="stack-tags">
            <span class="stack-tag">Node.js</span>
            <span class="stack-tag">FastAPI</span>
            <span class="stack-tag">Pandas</span>
            <span class="stack-tag">scikit-learn</span>
            <span class="stack-tag">REST API</span>
          </div>
        </div>
        <div class="stack-group">
          <div class="stack-group-title">Tools &amp; Infrastructure</div>
          <div class="stack-tags">
            <span class="stack-tag">Git</span>
            <span class="stack-tag">GitHub</span>
            <span class="stack-tag">Docker</span>
            <span class="stack-tag">VS Code</span>
            <span class="stack-tag">IoT / RPi</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <div class="section-inner">
      <div class="section-label reveal">Projects</div>
      <div class="projects-grid">

        <!-- Underwater -->
        <div class="proj-card reveal">
          <div>
            <div class="proj-number">01</div>
            <div class="proj-name">🌊 Underwater Project Suite</div>
            <div class="proj-desc">Multi-module submarine underwater monitoring system — built collaboratively as a team.</div>
            <div class="proj-modules">
              <span class="proj-module">/ai</span>
              <span class="proj-module">/backend</span>
              <span class="proj-module">/frontend</span>
              <span class="proj-module">/datasci</span>
            </div>
            <div class="proj-tags">
              <span class="proj-tag">Python</span>
              <span class="proj-tag">React</span>
              <span class="proj-tag">AI / ML</span>
              <span class="proj-tag">FastAPI</span>
              <span class="proj-tag">Pandas</span>
            </div>
          </div>
          <div class="proj-right">
            <div class="proj-status" style="color:#8fa8c8;border-color:#8fa8c840">Team Collab</div>
            <a href="https://github.com/ratthaphon0/underwater-project-v1" target="_blank" class="proj-link">View on GitHub ↗</a>
          </div>
        </div>

        <!-- AsixfShop -->
        <div class="proj-card reveal">
          <div>
            <div class="proj-number">02</div>
            <div class="proj-name">🛒 AsixfShop</div>
            <div class="proj-desc">Full-featured e-commerce platform with product management, cart, and checkout flows.</div>
            <div class="proj-tags">
              <span class="proj-tag">JavaScript</span>
              <span class="proj-tag">React</span>
              <span class="proj-tag">Node.js</span>
            </div>
          </div>
          <div class="proj-right">
            <div class="proj-status" style="color:#7aaa70;border-color:#7aaa7040">In Progress</div>
            <a href="https://github.com/ratthaphon0/shopping-website" target="_blank" class="proj-link">View on GitHub ↗</a>
          </div>
        </div>

        <!-- SmartCanteen -->
        <div class="proj-card reveal">
          <div>
            <div class="proj-number">03</div>
            <div class="proj-name">🍱 SmartCanteen</div>
            <div class="proj-desc">IoT-integrated smart canteen management system with ordering and inventory tracking.</div>
            <div class="proj-tags">
              <span class="proj-tag">Python</span>
              <span class="proj-tag">IoT</span>
              <span class="proj-tag">Raspberry Pi</span>
            </div>
          </div>
          <div class="proj-right">
            <div class="proj-status" style="color:#8fa8c8;border-color:#8fa8c840">Team Collab</div>
            <a href="https://github.com/ratthaphon0/SmartCanteen" target="_blank" class="proj-link">View on GitHub ↗</a>
          </div>
        </div>



      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <div class="section-inner">
      <div class="section-label reveal">Contact</div>
      <div class="contact-inner reveal">
        <h2>Let's build<br/><em>something together</em></h2>
        <p>Open to collaborations, interesting projects, and new connections. Feel free to reach out anytime.</p>
        <div class="contact-links">
          <a href="https://github.com/ratthaphon0" target="_blank" class="contact-link">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0 1 12 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
            GitHub
          </a>
          <a href="/cdn-cgi/l/email-protection#82f0e3f6f6eae3f2eaedecb2c2e7fae3eff2eee7ace1edef" class="contact-link">
            <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
            Email
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-left">Ratthaphon Khan</div>
    <div class="footer-right">ratthaphon0 · Kasetsart University · Chonburi, TH</div>
    <div class="footer-bar"></div>
  </footer>

  <script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
    // Cursor
    const cursor = document.getElementById('cursor');
    const ring   = document.getElementById('cursorRing');
    let mx = 0, my = 0, rx = 0, ry = 0;
    document.addEventListener('mousemove', e => { mx = e.clientX; my = e.clientY; cursor.style.left = mx+'px'; cursor.style.top = my+'px'; });
    function animRing() {
      rx += (mx - rx) * 0.12;
      ry += (my - ry) * 0.12;
      ring.style.left = rx+'px'; ring.style.top = ry+'px';
      requestAnimationFrame(animRing);
    }
    animRing();
    document.querySelectorAll('a, button, .role-chip, .stack-tag').forEach(el => {
      el.addEventListener('mouseenter', () => { ring.style.width='56px'; ring.style.height='56px'; ring.style.opacity='0.7'; });
      el.addEventListener('mouseleave', () => { ring.style.width='36px'; ring.style.height='36px'; ring.style.opacity='0.4'; });
    });

    // Nav shrink on scroll
    const nav = document.getElementById('nav');
    window.addEventListener('scroll', () => {
      nav.classList.toggle('scrolled', window.scrollY > 60);
    });

    // Reveal on scroll
    const reveals = document.querySelectorAll('.reveal');
    const observer = new IntersectionObserver(entries => {
      entries.forEach((entry, i) => {
        if (entry.isIntersecting) {
          setTimeout(() => entry.target.classL
