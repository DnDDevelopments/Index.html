<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Buckner HomeBuilds | Houston Construction & Real Estate</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,700;1,400;1,500&family=Jost:wght@300;400;500;600&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --navy: #0f1c2e;
      --navy-mid: #162540;
      --navy-light: #1e3254;
      --slate: #3a4f6a;
      --steel: #6b8299;
      --cream: #f8f4ee;
      --warm-white: #fdfbf8;
      --amber: #c8893a;
      --amber-light: #e0a555;
      --tan: #d4bc96;
      --text-muted: #8a9db5;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'Jost', sans-serif;
      background: var(--warm-white);
      color: var(--navy);
      overflow-x: hidden;
    }

    /* ─── NAV ─── */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 200;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1.2rem 5vw;
      background: rgba(15, 28, 46, 0.97);
      backdrop-filter: blur(16px);
      border-bottom: 1px solid rgba(200,137,58,0.2);
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 0.75rem;
      text-decoration: none;
    }

    .logo-mark {
      width: 38px; height: 38px;
      background: var(--amber);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Playfair Display', serif;
      font-size: 1.1rem;
      font-weight: 700;
      color: var(--warm-white);
      clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
    }

    .logo-text {
      display: flex;
      flex-direction: column;
      line-height: 1;
    }

    .logo-name {
      font-family: 'Playfair Display', serif;
      font-size: 1.1rem;
      font-weight: 500;
      color: var(--warm-white);
      letter-spacing: 0.02em;
    }

    .logo-tag {
      font-size: 0.6rem;
      font-weight: 500;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: var(--amber);
      margin-top: 2px;
    }

    .nav-links {
      display: flex;
      gap: 2.2rem;
      list-style: none;
    }

    .nav-links a {
      font-size: 0.75rem;
      font-weight: 500;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      text-decoration: none;
      color: rgba(255,255,255,0.55);
      transition: color 0.2s;
    }

    .nav-links a:hover { color: var(--amber-light); }

    .nav-btn {
      background: var(--amber);
      color: var(--warm-white);
      padding: 0.6rem 1.6rem;
      font-size: 0.72rem;
      font-weight: 600;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      text-decoration: none;
      border-radius: 2px;
      transition: background 0.2s;
    }

    .nav-btn:hover { background: var(--amber-light); }

    /* ─── HERO ─── */
    .hero {
      min-height: 100vh;
      background: var(--navy);
      position: relative;
      display: flex;
      align-items: center;
      overflow: hidden;
    }

    /* blueprint grid background */
    .hero::before {
      content: '';
      position: absolute;
      inset: 0;
      background-image:
        linear-gradient(rgba(200,137,58,0.04) 1px, transparent 1px),
        linear-gradient(90deg, rgba(200,137,58,0.04) 1px, transparent 1px);
      background-size: 60px 60px;
      z-index: 0;
    }

    /* diagonal accent */
    .hero::after {
      content: '';
      position: absolute;
      right: -100px;
      top: -100px;
      width: 700px;
      height: 700px;
      background: radial-gradient(circle, rgba(200,137,58,0.12) 0%, transparent 65%);
      z-index: 0;
    }

    .hero-content {
      position: relative;
      z-index: 2;
      padding: 0 5vw;
      max-width: 700px;
      animation: fadeUp 1s ease both;
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .hero-label {
      display: inline-flex;
      align-items: center;
      gap: 0.8rem;
      font-size: 0.7rem;
      font-weight: 600;
      letter-spacing: 0.22em;
      text-transform: uppercase;
      color: var(--amber);
      margin-bottom: 2rem;
      animation: fadeUp 1s 0.1s ease both;
    }

    .hero-label::before, .hero-label::after {
      content: '';
      display: block;
      width: 28px;
      height: 1px;
      background: var(--amber);
      opacity: 0.6;
    }

    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(2.8rem, 6vw, 5.5rem);
      font-weight: 400;
      line-height: 1.08;
      color: var(--warm-white);
      margin-bottom: 1.8rem;
      animation: fadeUp 1s 0.2s ease both;
    }

    .hero h1 em {
      font-style: italic;
      color: var(--amber-light);
    }

    .hero-sub {
      font-size: 1.05rem;
      font-weight: 300;
      line-height: 1.8;
      color: rgba(255,255,255,0.5);
      max-width: 500px;
      margin-bottom: 3rem;
      animation: fadeUp 1s 0.3s ease both;
    }

    .hero-actions {
      display: flex;
      gap: 1rem;
      align-items: center;
      animation: fadeUp 1s 0.4s ease both;
    }

    .btn-primary {
      background: var(--amber);
      color: var(--warm-white);
      padding: 0.9rem 2.4rem;
      font-size: 0.75rem;
      font-weight: 600;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      text-decoration: none;
      border-radius: 2px;
      transition: background 0.2s, transform 0.2s;
    }

    .btn-primary:hover {
      background: var(--amber-light);
      transform: translateY(-2px);
    }

    .btn-outline {
      border: 1px solid rgba(255,255,255,0.2);
      color: rgba(255,255,255,0.65);
      padding: 0.9rem 2rem;
      font-size: 0.75rem;
      font-weight: 500;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      text-decoration: none;
      border-radius: 2px;
      transition: border-color 0.2s, color 0.2s;
    }

    .btn-outline:hover {
      border-color: var(--amber);
      color: var(--amber);
    }

    /* floating cards */
    .hero-cards {
      position: absolute;
      right: 5vw;
      bottom: 6rem;
      z-index: 2;
      display: flex;
      flex-direction: column;
      gap: 1rem;
      animation: fadeUp 1s 0.5s ease both;
    }

    .hero-card {
      background: rgba(255,255,255,0.04);
      border: 1px solid rgba(200,137,58,0.2);
      backdrop-filter: blur(8px);
      padding: 1.2rem 1.8rem;
      border-radius: 4px;
      display: flex;
      align-items: center;
      gap: 1rem;
      min-width: 220px;
    }

    .hero-card-icon {
      font-size: 1.5rem;
    }

    .hero-card-num {
      font-family: 'Playfair Display', serif;
      font-size: 1.6rem;
      font-weight: 500;
      color: var(--amber-light);
      line-height: 1;
    }

    .hero-card-label {
      font-size: 0.65rem;
      font-weight: 500;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.35);
      margin-top: 2px;
    }

    .hero-scroll {
      position: absolute;
      bottom: 2.5rem;
      left: 5vw;
      z-index: 2;
      display: flex;
      align-items: center;
      gap: 0.8rem;
      font-size: 0.65rem;
      font-weight: 500;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.25);
    }

    .scroll-line {
      width: 40px;
      height: 1px;
      background: rgba(255,255,255,0.15);
      position: relative;
      overflow: hidden;
    }

    .scroll-line::after {
      content: '';
      position: absolute;
      top: 0; left: -100%;
      width: 100%; height: 100%;
      background: var(--amber);
      animation: scrollAnim 2s ease infinite;
    }

    @keyframes scrollAnim {
      0%   { left: -100%; }
      100% { left: 100%; }
    }

    /* ─── STATS ─── */
    .stats {
      background: var(--amber);
      display: grid;
      grid-template-columns: repeat(4, 1fr);
    }

    .stat {
      padding: 2.5rem 2rem;
      text-align: center;
      border-right: 1px solid rgba(255,255,255,0.15);
    }

    .stat:last-child { border-right: none; }

    .stat-num {
      font-family: 'Playfair Display', serif;
      font-size: 2.6rem;
      font-weight: 700;
      color: var(--warm-white);
      line-height: 1;
      margin-bottom: 0.4rem;
    }

    .stat-label {
      font-size: 0.68rem;
      font-weight: 600;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.65);
    }

    /* ─── SERVICES ─── */
    .services {
      padding: 7rem 5vw;
      background: var(--warm-white);
    }

    .section-intro {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 4rem;
      align-items: flex-end;
      margin-bottom: 4rem;
    }

    .eyebrow {
      font-size: 0.7rem;
      font-weight: 600;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      color: var(--amber);
      margin-bottom: 1rem;
      display: flex;
      align-items: center;
      gap: 0.7rem;
    }

    .eyebrow::before {
      content: '';
      display: block;
      width: 20px;
      height: 2px;
      background: var(--amber);
    }

    .section-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(1.9rem, 3.5vw, 3rem);
      font-weight: 400;
      line-height: 1.15;
      color: var(--navy);
    }

    .section-title em { font-style: italic; color: var(--amber); }

    .section-desc {
      font-size: 0.95rem;
      font-weight: 300;
      line-height: 1.85;
      color: var(--slate);
      align-self: flex-end;
    }

    .services-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1.5rem;
    }

    .service-card {
      background: var(--cream);
      border-radius: 4px;
      padding: 2.8rem 2.2rem;
      position: relative;
      overflow: hidden;
      transition: box-shadow 0.3s, transform 0.3s;
      cursor: default;
      border-top: 3px solid transparent;
    }

    .service-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 20px 50px rgba(15,28,46,0.1);
      border-top-color: var(--amber);
    }

    .service-num {
      position: absolute;
      top: 1.5rem; right: 1.8rem;
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      font-weight: 700;
      color: rgba(15,28,46,0.04);
      line-height: 1;
    }

    .service-icon {
      font-size: 2.2rem;
      margin-bottom: 1.5rem;
      display: block;
    }

    .service-title {
      font-family: 'Playfair Display', serif;
      font-size: 1.4rem;
      font-weight: 500;
      color: var(--navy);
      margin-bottom: 0.9rem;
      line-height: 1.2;
    }

    .service-desc {
      font-size: 0.88rem;
      font-weight: 300;
      color: var(--slate);
      line-height: 1.8;
    }

    /* ─── ABOUT ─── */
    .about {
      padding: 7rem 5vw;
      background: var(--navy);
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 5rem;
      align-items: center;
    }

    .about-visual {
      position: relative;
    }

    .about-img-wrap {
      background: var(--navy-mid);
      border-radius: 4px;
      height: 480px;
      position: relative;
      overflow: hidden;
      border: 1px solid rgba(200,137,58,0.15);
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .about-pattern {
      position: absolute;
      inset: 0;
      background-image:
        linear-gradient(rgba(200,137,58,0.05) 1px, transparent 1px),
        linear-gradient(90deg, rgba(200,137,58,0.05) 1px, transparent 1px);
      background-size: 40px 40px;
    }

    .about-monogram {
      font-family: 'Playfair Display', serif;
      font-size: 14rem;
      font-weight: 700;
      color: rgba(200,137,58,0.06);
      line-height: 1;
      position: relative;
      z-index: 1;
      user-select: none;
    }

    .about-badge {
      position: absolute;
      bottom: -1.5rem;
      right: -1.5rem;
      background: var(--amber);
      padding: 1.8rem 2rem;
      border-radius: 4px;
      text-align: center;
      z-index: 2;
    }

    .badge-num {
      font-family: 'Playfair Display', serif;
      font-size: 2.2rem;
      font-weight: 700;
      color: var(--warm-white);
      line-height: 1;
    }

    .badge-label {
      font-size: 0.65rem;
      font-weight: 600;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.7);
      margin-top: 0.4rem;
    }

    .about-content .eyebrow { margin-bottom: 1rem; }

    .about-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(1.8rem, 3vw, 2.8rem);
      font-weight: 400;
      line-height: 1.15;
      color: var(--warm-white);
      margin-bottom: 1.5rem;
    }

    .about-title em { font-style: italic; color: var(--amber-light); }

    .about-desc {
      font-size: 0.92rem;
      font-weight: 300;
      line-height: 1.9;
      color: rgba(255,255,255,0.45);
      margin-bottom: 2.5rem;
    }

    .about-points {
      list-style: none;
      display: flex;
      flex-direction: column;
      gap: 1rem;
      margin-bottom: 2.5rem;
    }

    .about-points li {
      display: flex;
      align-items: center;
      gap: 1rem;
      font-size: 0.88rem;
      font-weight: 400;
      color: rgba(255,255,255,0.65);
    }

    .about-points li::before {
      content: '';
      display: block;
      width: 6px;
      height: 6px;
      background: var(--amber);
      border-radius: 50%;
      flex-shrink: 0;
    }

    /* ─── PROCESS ─── */
    .process {
      padding: 7rem 5vw;
      background: var(--cream);
    }

    .process-header {
      text-align: center;
      margin-bottom: 5rem;
    }

    .process-header .eyebrow {
      justify-content: center;
    }

    .process-header .eyebrow::before { display: none; }

    .process-steps {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 0;
      position: relative;
    }

    .process-steps::before {
      content: '';
      position: absolute;
      top: 2.2rem;
      left: 10%;
      right: 10%;
      height: 1px;
      background: linear-gradient(90deg, transparent, var(--amber), transparent);
      z-index: 0;
    }

    .process-step {
      text-align: center;
      padding: 0 1.5rem;
      position: relative;
      z-index: 1;
    }

    .step-num {
      width: 44px;
      height: 44px;
      background: var(--navy);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Playfair Display', serif;
      font-size: 1rem;
      font-weight: 700;
      color: var(--amber);
      margin: 0 auto 2rem;
      border: 2px solid var(--amber);
    }

    .step-title {
      font-family: 'Playfair Display', serif;
      font-size: 1.2rem;
      font-weight: 500;
      color: var(--navy);
      margin-bottom: 0.8rem;
    }

    .step-desc {
      font-size: 0.84rem;
      font-weight: 300;
      color: var(--slate);
      line-height: 1.75;
    }

    /* ─── CONTACT ─── */
    .contact {
      padding: 7rem 5vw;
      background: var(--navy);
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 6rem;
      align-items: start;
    }

    .contact-info .eyebrow { margin-bottom: 1rem; }

    .contact-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(1.8rem, 3vw, 2.8rem);
      font-weight: 400;
      color: var(--warm-white);
      margin-bottom: 1.5rem;
      line-height: 1.15;
    }

    .contact-title em { font-style: italic; color: var(--amber-light); }

    .contact-desc {
      font-size: 0.9rem;
      font-weight: 300;
      color: rgba(255,255,255,0.4);
      line-height: 1.85;
      margin-bottom: 3rem;
    }

    .contact-details {
      display: flex;
      flex-direction: column;
      gap: 1.2rem;
    }

    .contact-item {
      display: flex;
      align-items: center;
      gap: 1rem;
    }

    .contact-item-icon {
      width: 40px; height: 40px;
      background: rgba(200,137,58,0.1);
      border: 1px solid rgba(200,137,58,0.2);
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1rem;
      flex-shrink: 0;
    }

    .contact-item-text {
      font-size: 0.88rem;
      color: rgba(255,255,255,0.55);
    }

    .contact-item-label {
      font-size: 0.65rem;
      font-weight: 600;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--amber);
      margin-bottom: 0.2rem;
    }

    /* Form */
    .contact-form {
      background: rgba(255,255,255,0.03);
      border: 1px solid rgba(200,137,58,0.15);
      border-radius: 4px;
      padding: 2.5rem;
    }

    .form-title {
      font-family: 'Playfair Display', serif;
      font-size: 1.3rem;
      font-weight: 500;
      color: var(--warm-white);
      margin-bottom: 2rem;
    }

    .form-row {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1rem;
      margin-bottom: 1rem;
    }

    .form-group {
      display: flex;
      flex-direction: column;
      gap: 0.4rem;
      margin-bottom: 1rem;
    }

    .form-group label {
      font-size: 0.68rem;
      font-weight: 600;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.35);
    }

    .form-group input,
    .form-group select,
    .form-group textarea {
      background: rgba(255,255,255,0.05);
      border: 1px solid rgba(255,255,255,0.1);
      border-radius: 2px;
      padding: 0.75rem 1rem;
      font-family: 'Jost', sans-serif;
      font-size: 0.88rem;
      color: var(--warm-white);
      outline: none;
      transition: border-color 0.2s;
      width: 100%;
    }

    .form-group input::placeholder,
    .form-group textarea::placeholder {
      color: rgba(255,255,255,0.2);
    }

    .form-group select option { background: var(--navy); }

    .form-group input:focus,
    .form-group select:focus,
    .form-group textarea:focus {
      border-color: var(--amber);
    }

    .form-group textarea { resize: vertical; min-height: 100px; }

    .form-submit {
      width: 100%;
      background: var(--amber);
      color: var(--warm-white);
      border: none;
      padding: 0.95rem;
      font-family: 'Jost', sans-serif;
      font-size: 0.75rem;
      font-weight: 600;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      border-radius: 2px;
      cursor: pointer;
      transition: background 0.2s;
      margin-top: 0.5rem;
    }

    .form-submit:hover { background: var(--amber-light); }

    /* ─── FOOTER ─── */
    footer {
      background: #080f1a;
      padding: 3rem 5vw;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-top: 1px solid rgba(200,137,58,0.1);
    }

    .footer-brand {
      font-family: 'Playfair Display', serif;
      font-size: 1rem;
      font-weight: 500;
      color: rgba(255,255,255,0.35);
    }

    .footer-brand span { color: var(--amber); }

    .footer-copy {
      font-size: 0.72rem;
      color: rgba(255,255,255,0.2);
      letter-spacing: 0.05em;
    }

    .footer-links {
      display: flex;
      gap: 1.5rem;
      list-style: none;
    }

    .footer-links a {
      font-size: 0.7rem;
      font-weight: 500;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: rgba(255,255,255,0.25);
      text-decoration: none;
      transition: color 0.2s;
    }

    .footer-links a:hover { color: var(--amber); }
  </style>
</head>
<body>

  <!-- NAV -->
  <nav>
    <a href="#" class="logo">
      <div class="logo-mark">B</div>
      <div class="logo-text">
        <span class="logo-name">Buckner HomeBuilds</span>
        <span class="logo-tag">Houston, Texas</span>
      </div>
    </a>
    <ul class="nav-links">
      <li><a href="#services">Services</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#process">Process</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <a href="#contact" class="nav-btn">Get a Quote</a>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-content">
      <div class="hero-label">Houston's Premier Builder</div>
      <h1>Building Homes<br>That <em>Last</em> a<br>Lifetime</h1>
      <p class="hero-sub">
        From new construction and custom builds to residential development and renovation — Buckner HomeBuilds delivers quality craftsmanship rooted in Houston's community.
      </p>
      <div class="hero-actions">
        <a href="#contact" class="btn-primary">Start Your Project</a>
        <a href="#services" class="btn-outline">Our Services</a>
      </div>
    </div>

    <div class="hero-cards">
      <div class="hero-card">
        <div class="hero-card-icon">🏗️</div>
        <div>
          <div class="hero-card-num">Now</div>
          <div class="hero-card-label">Accepting New Clients</div>
        </div>
      </div>
      <div class="hero-card">
        <div class="hero-card-icon">⭐</div>
        <div>
          <div class="hero-card-num">5.0</div>
          <div class="hero-card-label">Client Rating</div>
        </div>
      </div>
      <div class="hero-card">
        <div class="hero-card-icon">📍</div>
        <div>
          <div class="hero-card-num">HTX</div>
          <div class="hero-card-label">Houston Based</div>
        </div>
      </div>
    </div>

    <div class="hero-scroll">
      <div class="scroll-line"></div>
      Scroll to explore
    </div>
  </section>

  <!-- STATS -->
  <div class="stats">
    <div class="stat">
      <div class="stat-num">New</div>
      <div class="stat-label">Accepting Projects</div>
    </div>
    <div class="stat">
      <div class="stat-num">100%</div>
      <div class="stat-label">Client Focused</div>
    </div>
    <div class="stat">
      <div class="stat-num">Free</div>
      <div class="stat-label">Consultations</div>
    </div>
    <div class="stat">
      <div class="stat-num">HTX</div>
      <div class="stat-label">Houston Proud</div>
    </div>
  </div>

  <!-- SERVICES -->
  <section class="services" id="services">
    <div class="section-intro">
      <div>
        <div class="eyebrow">What We Do</div>
        <h2 class="section-title">Full-Service <em>Construction</em><br>& Real Estate</h2>
      </div>
      <p class="section-desc">
        Whether you're breaking ground on a new build, redeveloping a lot, or renovating an existing property — we bring deep Houston expertise and hands-on project management to every job.
      </p>
    </div>

    <div class="services-grid">
      <div class="service-card">
        <span class="service-num">01</span>
        <span class="service-icon">🏠</span>
        <h3 class="service-title">New Home Construction</h3>
        <p class="service-desc">Custom and spec home builds from foundation to finish. We manage every phase — permits, subs, inspections, and delivery.</p>
      </div>
      <div class="service-card">
        <span class="service-num">02</span>
        <span class="service-icon">🏘️</span>
        <h3 class="service-title">Residential Development</h3>
        <p class="service-desc">Lot acquisition, land development, and multi-unit residential projects. We identify value, plan smart, and build to sell or hold.</p>
      </div>
      <div class="service-card">
        <span class="service-num">03</span>
        <span class="service-icon">🔨</span>
        <h3 class="service-title">Renovation & Remodeling</h3>
        <p class="service-desc">Full interior and exterior renovations. Kitchens, baths, additions, and full gut rehabs done right with quality materials.</p>
      </div>
      <div class="service-card">
        <span class="service-num">04</span>
        <span class="service-icon">🪣</span>
        <h3 class="service-title">Epoxy & Specialty Finishes</h3>
        <p class="service-desc">Professional epoxy flooring and specialty surface coatings for garages, warehouses, and residential spaces.</p>
      </div>
      <div class="service-card">
        <span class="service-num">05</span>
        <span class="service-icon">📋</span>
        <h3 class="service-title">Project Management</h3>
        <p class="service-desc">End-to-end oversight of your construction project. Scheduling, budgeting, subcontractor coordination, and quality control.</p>
      </div>
      <div class="service-card">
        <span class="service-num">06</span>
        <span class="service-icon">🏗️</span>
        <h3 class="service-title">Real Estate Consulting</h3>
        <p class="service-desc">Buy-side and sell-side advisory for investors and homeowners. Lot valuation, deal structuring, and builder partnerships.</p>
      </div>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="about" id="about">
    <div class="about-visual">
      <div class="about-img-wrap">
        <div class="about-pattern"></div>
        <div class="about-monogram">BH</div>
      </div>
      <div class="about-badge">
        <div class="badge-num">HTX</div>
        <div class="badge-label">Built Here</div>
      </div>
    </div>

    <div class="about-content">
      <div class="eyebrow">About Us</div>
      <h2 class="about-title">Rooted in Houston.<br><em>Built on Integrity.</em></h2>
      <p class="about-desc">
        Buckner HomeBuilds was founded with one goal: to bring honest, high-quality construction services to Houston homeowners, investors, and developers. We combine deep local market knowledge with hands-on craftsmanship — treating every project like it's our own property.
      </p>
      <ul class="about-points">
        <li>Licensed, insured, and Houston-based</li>
        <li>Transparent pricing — no hidden costs</li>
        <li>On-time delivery and clear communication</li>
        <li>Full project management from start to finish</li>
        <li>Experience in new builds, rehabs, and development</li>
      </ul>
      <a href="#contact" class="btn-primary">Work With Us</a>
    </div>
  </section>

  <!-- PROCESS -->
  <section class="process" id="process">
    <div class="process-header">
      <div class="eyebrow">How It Works</div>
      <h2 class="section-title">Our <em>Simple</em> Process</h2>
    </div>

    <div class="process-steps">
      <div class="process-step">
        <div class="step-num">1</div>
        <h3 class="step-title">Consultation</h3>
        <p class="step-desc">We start with a free conversation to understand your vision, budget, and timeline.</p>
      </div>
      <div class="process-step">
        <div class="step-num">2</div>
        <h3 class="step-title">Planning & Quote</h3>
        <p class="step-desc">We walk the site, assess the scope, and deliver a clear, itemized proposal.</p>
      </div>
      <div class="process-step">
        <div class="step-num">3</div>
        <h3 class="step-title">Build Phase</h3>
        <p class="step-desc">Construction begins with regular updates, milestone check-ins, and quality oversight.</p>
      </div>
      <div class="process-step">
        <div class="step-num">4</div>
        <h3 class="step-title">Delivery</h3>
        <p class="step-desc">Final walkthrough, punch list, and handoff — done right, on time, every time.</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section class="contact" id="contact">
    <div class="contact-info">
      <div class="eyebrow">Get In Touch</div>
      <h2 class="contact-title">Let's Build<br><em>Something Great</em></h2>
      <p class="contact-desc">
        Ready to start your project? Reach out for a free consultation. We serve the greater Houston area and surrounding communities.
      </p>
      <div class="contact-details">
        <div class="contact-item">
          <div class="contact-item-icon">📍</div>
          <div>
            <div class="contact-item-label">Location</div>
            <div class="contact-item-text">Houston, Texas 77009</div>
          </div>
        </div>
        <div class="contact-item">
          <div class="contact-item-icon">📞</div>
          <div>
            <div class="contact-item-label">Phone</div>
            <div class="contact-item-text">(682) 300-5569</div>
          </div>
        </div>
        <div class="contact-item">
          <div class="contact-item-icon">✉️</div>
          <div>
            <div class="contact-item-label">Email</div>
            <div class="contact-item-text"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="6e070008012e0c1b0d05000b1c0601030b0c1b07020a1d400d0103">[email&#160;protected]</a></div>
          </div>
        </div>
        <div class="contact-item">
          <div class="contact-item-icon">🕐</div>
          <div>
            <div class="contact-item-label">Hours</div>
            <div class="contact-item-text">Mon–Fri: 7am – 6pm</div>
          </div>
        </div>
      </div>
    </div>

    <div class="contact-form">
      <div class="form-title">Request a Free Quote</div>
      <div class="form-row">
        <div class="form-group">
          <label>First Name</label>
          <input type="text" placeholder="John" />
        </div>
        <div class="form-group">
          <label>Last Name</label>
          <input type="text" placeholder="Smith" />
        </div>
      </div>
      <div class="form-group">
        <label>Email Address</label>
        <input type="email" placeholder="john@email.com" />
      </div>
      <div class="form-group">
        <label>Phone Number</label>
        <input type="tel" placeholder="(713) 000-0000" />
      </div>
      <div class="form-group">
        <label>Project Type</label>
        <select>
          <option value="">Select a service...</option>
          <option>New Home Construction</option>
          <option>Residential Development</option>
          <option>Renovation & Remodeling</option>
          <option>Epoxy & Specialty Finishes</option>
          <option>Project Management</option>
          <option>Real Estate Consulting</option>
        </select>
      </div>
      <div class="form-group">
        <label>Tell Us About Your Project</label>
        <textarea placeholder="Describe your project, location, timeline, and budget..."></textarea>
      </div>
      <button class="form-submit">Send Message →</button>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-brand">Buckner <span>HomeBuilds</span></div>
    <div class="footer-copy">© 2025 Buckner HomeBuilds LLC. All rights reserved.</div>
    <ul class="footer-links">
      <li><a href="#services">Services</a></li
