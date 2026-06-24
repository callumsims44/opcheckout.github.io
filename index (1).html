<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Op Checkout — Retail Crime Intelligence for England & Wales</title>
<meta name="description" content="Op Checkout is the record management system built for retail staff in England and Wales. Log incidents, capture evidence, build intelligence, and share alerts with neighbouring stores.">
<style>
  /* ── Reset & base ─────────────────────────────────────────────────── */
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --navy:    #0D1F4C;
    --navy-m:  #1A3A7A;
    --navy-l:  #E6ECF8;
    --grey:    #7A8499;
    --grey-l:  #F4F5F7;
    --border:  #DDE0E8;
    --white:   #FFFFFF;
    --text:    #1A1D2E;
    --muted:   #6B7280;
    --red:     #D0312D;
    --green:   #1A6E3C;
    --green-l: #E6F4ED;
    --amber:   #C47A00;
    --r: 10px;
  }
  html { scroll-behavior: smooth; }
  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Inter', sans-serif;
    color: var(--text);
    background: var(--white);
    font-size: 16px;
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
  }
  img { max-width: 100%; display: block; }
  a { color: inherit; text-decoration: none; }

  /* ── Typography ───────────────────────────────────────────────────── */
  h1 { font-size: clamp(2rem, 5vw, 3.2rem); font-weight: 800; line-height: 1.1; letter-spacing: -0.03em; }
  h2 { font-size: clamp(1.6rem, 3.5vw, 2.4rem); font-weight: 700; line-height: 1.2; letter-spacing: -0.02em; }
  h3 { font-size: 1.1rem; font-weight: 700; }
  p  { color: var(--muted); }

  /* ── Layout helpers ───────────────────────────────────────────────── */
  .container { max-width: 1100px; margin: 0 auto; padding: 0 24px; }
  .section    { padding: 88px 0; }
  .section-sm { padding: 56px 0; }
  .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; align-items: center; }
  .grid-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: 24px; }
  .grid-4 { display: grid; grid-template-columns: repeat(4, 1fr); gap: 20px; }
  .text-center { text-align: center; }
  .mt-4  { margin-top: 4px; }
  .mt-8  { margin-top: 8px; }
  .mt-16 { margin-top: 16px; }
  .mt-24 { margin-top: 24px; }
  .mt-40 { margin-top: 40px; }
  .mt-56 { margin-top: 56px; }

  /* ── Buttons ──────────────────────────────────────────────────────── */
  .btn {
    display: inline-flex; align-items: center; gap: 8px;
    padding: 13px 24px; border-radius: 8px;
    font-size: 15px; font-weight: 700;
    cursor: pointer; border: none; transition: all 0.18s;
    white-space: nowrap;
  }
  .btn-primary { background: var(--navy); color: var(--white); }
  .btn-primary:hover { background: var(--navy-m); transform: translateY(-1px); box-shadow: 0 4px 16px rgba(13,31,76,0.25); }
  .btn-outline { background: transparent; color: var(--navy); border: 2px solid var(--border); }
  .btn-outline:hover { border-color: var(--navy); background: var(--navy-l); }
  .btn-white { background: var(--white); color: var(--navy); }
  .btn-white:hover { background: var(--navy-l); transform: translateY(-1px); }
  .btn-lg { padding: 16px 32px; font-size: 16px; border-radius: 10px; }

  /* ── Navigation ───────────────────────────────────────────────────── */
  .nav {
    position: sticky; top: 0; z-index: 100;
    background: rgba(255,255,255,0.95);
    backdrop-filter: blur(10px);
    border-bottom: 1px solid var(--border);
  }
  .nav-inner {
    display: flex; align-items: center; justify-content: space-between;
    height: 64px;
  }
  .nav-logo { display: flex; align-items: center; gap: 10px; }
  .nav-logo-icon {
    width: 36px; height: 36px;
    background: var(--navy); border-radius: 9px;
    display: flex; align-items: center; justify-content: center;
  }
  .nav-logo-icon svg { width: 22px; height: 22px; }
  .nav-brand { font-size: 16px; font-weight: 800; color: var(--navy); letter-spacing: -0.02em; }
  .nav-links { display: flex; align-items: center; gap: 32px; }
  .nav-links a { font-size: 14px; font-weight: 600; color: var(--muted); transition: color 0.15s; }
  .nav-links a:hover { color: var(--navy); }
  .nav-cta { display: flex; align-items: center; gap: 12px; }

  /* ── Hero ─────────────────────────────────────────────────────────── */
  .hero {
    background: var(--navy);
    padding: 100px 0 80px;
    position: relative;
    overflow: hidden;
  }
  .hero::before {
    content: '';
    position: absolute; inset: 0;
    background: radial-gradient(ellipse at 70% 50%, rgba(26,58,122,0.6) 0%, transparent 70%);
  }
  .hero-inner { position: relative; z-index: 1; }
  .hero-eyebrow {
    display: inline-flex; align-items: center; gap: 8px;
    background: rgba(255,255,255,0.1);
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 100px;
    padding: 6px 14px;
    font-size: 13px; font-weight: 600; color: rgba(255,255,255,0.85);
    margin-bottom: 24px;
  }
  .hero-eyebrow-dot { width: 7px; height: 7px; background: #4ADE80; border-radius: 50%; animation: pulse 2s infinite; }
  @keyframes pulse { 0%,100% { opacity: 1; } 50% { opacity: 0.4; } }
  .hero h1 { color: var(--white); max-width: 720px; }
  .hero h1 span { color: #7CB9FF; }
  .hero-sub { font-size: 1.1rem; color: rgba(255,255,255,0.65); max-width: 560px; margin-top: 20px; line-height: 1.7; }
  .hero-actions { display: flex; align-items: center; gap: 14px; margin-top: 36px; flex-wrap: wrap; }
  .hero-stats {
    display: flex; gap: 48px; margin-top: 64px;
    padding-top: 40px; border-top: 1px solid rgba(255,255,255,0.1);
    flex-wrap: wrap;
  }
  .hero-stat-val { font-size: 2rem; font-weight: 800; color: var(--white); line-height: 1; }
  .hero-stat-label { font-size: 13px; color: rgba(255,255,255,0.5); margin-top: 4px; }

  /* ── Problem strip ────────────────────────────────────────────────── */
  .problem-strip { background: var(--grey-l); border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); }
  .problem-inner { display: flex; align-items: center; gap: 0; }
  .problem-item {
    flex: 1; padding: 28px 24px;
    border-right: 1px solid var(--border);
    text-align: center;
  }
  .problem-item:last-child { border-right: none; }
  .problem-num { font-size: 1.8rem; font-weight: 800; color: var(--red); line-height: 1; }
  .problem-label { font-size: 13px; color: var(--muted); margin-top: 4px; }

  /* ── Section label ────────────────────────────────────────────────── */
  .section-label {
    display: inline-block;
    font-size: 12px; font-weight: 700; letter-spacing: 0.08em; text-transform: uppercase;
    color: var(--navy); background: var(--navy-l);
    padding: 5px 12px; border-radius: 100px;
    margin-bottom: 16px;
  }

  /* ── Feature cards ────────────────────────────────────────────────── */
  .feature-card {
    background: var(--white);
    border: 1px solid var(--border);
    border-radius: var(--r);
    padding: 28px;
    transition: box-shadow 0.2s, transform 0.2s;
  }
  .feature-card:hover { box-shadow: 0 8px 32px rgba(13,31,76,0.1); transform: translateY(-2px); }
  .feature-icon {
    width: 44px; height: 44px;
    background: var(--navy-l); border-radius: 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 20px; margin-bottom: 16px;
  }
  .feature-card h3 { color: var(--navy); margin-bottom: 8px; }
  .feature-card p { font-size: 14px; line-height: 1.6; }

  /* ── How it works ─────────────────────────────────────────────────── */
  .how-bg { background: var(--grey-l); }
  .step-num {
    width: 36px; height: 36px;
    background: var(--navy); color: var(--white);
    border-radius: 50%; display: flex; align-items: center; justify-content: center;
    font-size: 14px; font-weight: 800; flex-shrink: 0;
  }
  .step { display: flex; gap: 20px; align-items: flex-start; }
  .step-content h3 { color: var(--navy); margin-bottom: 6px; }
  .step-content p { font-size: 14px; }
  .steps-list { display: flex; flex-direction: column; gap: 28px; }
  .step-connector { width: 1px; height: 20px; background: var(--border); margin-left: 18px; }

  /* ── Network section ──────────────────────────────────────────────── */
  .network-card {
    background: var(--navy);
    border-radius: var(--r);
    padding: 32px;
    color: var(--white);
  }
  .network-card h3 { color: var(--white); margin-bottom: 8px; }
  .network-card p { color: rgba(255,255,255,0.6); font-size: 14px; }
  .bolo-preview {
    background: var(--white);
    border-radius: 8px;
    overflow: hidden;
    margin-top: 20px;
    border: 2px solid var(--red);
  }
  .bolo-header { background: var(--red); padding: 8px 14px; font-size: 12px; font-weight: 700; color: var(--white); display: flex; justify-content: space-between; }
  .bolo-body { padding: 14px; display: flex; gap: 12px; }
  .bolo-avatar { width: 48px; height: 48px; background: var(--grey-l); border-radius: 8px; display: flex; align-items: center; justify-content: center; font-size: 22px; flex-shrink: 0; }
  .bolo-info h4 { font-size: 13px; font-weight: 700; color: var(--text); margin-bottom: 2px; }
  .bolo-info p { font-size: 12px; color: var(--muted); }
  .bolo-tag { display: inline-block; padding: 2px 8px; border-radius: 12px; font-size: 10px; font-weight: 700; background: #FDECEA; color: var(--red); margin-top: 6px; margin-right: 4px; }

  /* ── Alert preview ────────────────────────────────────────────────── */
  .alert-preview {
    background: var(--white);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 14px;
    margin-top: 12px;
    display: flex; gap: 12px; align-items: flex-start;
  }
  .alert-dot { width: 10px; height: 10px; border-radius: 50%; flex-shrink: 0; margin-top: 4px; }
  .alert-dot.red { background: var(--red); }
  .alert-dot.amber { background: var(--amber); }
  .alert-dot.green { background: var(--green); }
  .alert-title { font-size: 13px; font-weight: 700; color: var(--text); }
  .alert-sub { font-size: 12px; color: var(--muted); margin-top: 2px; }

  /* ── Pricing ──────────────────────────────────────────────────────── */
  .price-card {
    background: var(--white);
    border: 1px solid var(--border);
    border-radius: var(--r);
    padding: 32px;
    transition: box-shadow 0.2s;
  }
  .price-card.featured { border: 2px solid var(--navy); }
  .price-badge { font-size: 11px; font-weight: 700; padding: 4px 10px; border-radius: 100px; display: inline-block; margin-bottom: 16px; }
  .price-badge.blue { background: var(--navy-l); color: var(--navy); }
  .price-badge.popular { background: var(--navy); color: var(--white); }
  .price-name { font-size: 18px; font-weight: 700; color: var(--navy); }
  .price-amount { font-size: 2.4rem; font-weight: 800; color: var(--text); line-height: 1; margin: 12px 0 4px; }
  .price-amount span { font-size: 16px; font-weight: 400; color: var(--muted); }
  .price-desc { font-size: 13px; color: var(--muted); margin-bottom: 24px; padding-bottom: 24px; border-bottom: 1px solid var(--border); }
  .price-feature { display: flex; align-items: center; gap: 10px; font-size: 14px; color: var(--text); padding: 7px 0; }
  .price-feature::before { content: '✓'; width: 20px; height: 20px; background: var(--green-l); color: var(--green); border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 11px; font-weight: 700; flex-shrink: 0; }

  /* ── Compliance strip ─────────────────────────────────────────────── */
  .compliance { background: var(--navy-l); border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); }
  .compliance-inner { display: flex; align-items: center; gap: 0; }
  .compliance-item { flex: 1; padding: 24px; border-right: 1px solid var(--border); display: flex; align-items: center; gap: 12px; }
  .compliance-item:last-child { border-right: none; }
  .compliance-icon { font-size: 22px; flex-shrink: 0; }
  .compliance-text { font-size: 13px; font-weight: 600; color: var(--navy); }
  .compliance-sub { font-size: 12px; color: var(--muted); margin-top: 2px; }

  /* ── CTA ──────────────────────────────────────────────────────────── */
  .cta-section { background: var(--navy); padding: 96px 0; text-align: center; }
  .cta-section h2 { color: var(--white); }
  .cta-section p { color: rgba(255,255,255,0.6); max-width: 520px; margin: 16px auto 0; font-size: 1rem; }
  .cta-actions { display: flex; align-items: center; justify-content: center; gap: 14px; margin-top: 36px; flex-wrap: wrap; }

  /* ── Footer ───────────────────────────────────────────────────────── */
  .footer { padding: 48px 0 32px; border-top: 1px solid var(--border); }
  .footer-inner { display: flex; align-items: flex-start; justify-content: space-between; gap: 40px; flex-wrap: wrap; }
  .footer-brand p { font-size: 13px; color: var(--muted); margin-top: 12px; max-width: 280px; }
  .footer-col h4 { font-size: 13px; font-weight: 700; color: var(--navy); margin-bottom: 12px; }
  .footer-col a { display: block; font-size: 13px; color: var(--muted); padding: 3px 0; transition: color 0.15s; }
  .footer-col a:hover { color: var(--navy); }
  .footer-bottom { margin-top: 40px; padding-top: 24px; border-top: 1px solid var(--border); display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 12px; }
  .footer-bottom p { font-size: 12px; color: var(--muted); }
  .gdpr-badge { display: inline-flex; align-items: center; gap: 6px; background: var(--green-l); color: var(--green); font-size: 11px; font-weight: 700; padding: 4px 10px; border-radius: 100px; }

  /* ── Responsive ───────────────────────────────────────────────────── */
  @media (max-width: 768px) {
    .grid-2, .grid-3, .grid-4 { grid-template-columns: 1fr; }
    .nav-links, .nav-cta .btn-outline { display: none; }
    .problem-inner, .compliance-inner { flex-direction: column; }
    .problem-item, .compliance-item { border-right: none; border-bottom: 1px solid var(--border); }
    .problem-item:last-child, .compliance-item:last-child { border-bottom: none; }
    .hero-stats { gap: 28px; }
    .footer-inner { flex-direction: column; }
  }
  @media (prefers-reduced-motion: reduce) { *, *::before, *::after { animation: none !important; transition: none !important; } }
</style>
</head>
<body>

<!-- ══ NAV ══ -->
<nav class="nav">
  <div class="container nav-inner">
    <a href="#" class="nav-logo">
      <div class="nav-logo-icon">
        <svg viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M11 2L3.5 6.5V11C3.5 15.14 6.86 18.97 11 20C15.14 18.97 18.5 15.14 18.5 11V6.5L11 2Z" fill="white" opacity="0.15"/>
          <path d="M11 2L3.5 6.5V11C3.5 15.14 6.86 18.97 11 20C15.14 18.97 18.5 15.14 18.5 11V6.5L11 2Z" stroke="white" stroke-width="1.5" stroke-linejoin="round"/>
          <path d="M7.5 11L9.5 13L14.5 8.5" stroke="white" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
      </div>
      <span class="nav-brand">Op Checkout</span>
    </a>
    <div class="nav-links">
      <a href="#features">Features</a>
      <a href="#how-it-works">How it works</a>
      <a href="#network">Network</a>
      <a href="#pricing">Pricing</a>
      <a href="#about">About</a>
    </div>
    <div class="nav-cta">
      <a href="#" class="btn btn-outline" style="padding:9px 18px;font-size:14px">Sign in</a>
      <a href="#pricing" class="btn btn-primary" style="padding:9px 18px;font-size:14px">Start free trial</a>
    </div>
  </div>
</nav>

<!-- ══ HERO ══ -->
<section class="hero">
  <div class="container hero-inner">
    <div class="hero-eyebrow">
      <div class="hero-eyebrow-dot"></div>
      Built for England & Wales
    </div>
    <h1>Retail crime stops<br>at the <span>checkout</span>.</h1>
    <p class="hero-sub">Op Checkout is the record management system built for retail staff. Log incidents, capture court-ready evidence, build intelligence on repeat offenders, and share alerts with every store in your area — in minutes.</p>
    <div class="hero-actions">
      <a href="#pricing" class="btn btn-white btn-lg">Start free trial</a>
      <a href="#how-it-works" class="btn btn-outline btn-lg" style="border-color:rgba(255,255,255,0.3);color:rgba(255,255,255,0.85)">See how it works</a>
    </div>
    <div class="hero-stats">
      <div>
        <div class="hero-stat-val">530k+</div>
        <div class="hero-stat-label">Shoplifting offences recorded in England & Wales (2024/25)</div>
      </div>
      <div>
        <div class="hero-stat-val">2%</div>
        <div class="hero-stat-label">Of retail crime incidents that result in a conviction</div>
      </div>
      <div>
        <div class="hero-stat-val">£4.2bn</div>
        <div class="hero-stat-label">Annual cost of retail crime to UK businesses</div>
      </div>
      <div>
        <div class="hero-stat-val">300k+</div>
        <div class="hero-stat-label">Retail sites in England & Wales with no crime intelligence tool</div>
      </div>
    </div>
  </div>
</section>

<!-- ══ PROBLEM STRIP ══ -->
<div class="problem-strip section-sm">
  <div class="container">
    <div class="problem-inner">
      <div class="problem-item">
        <div class="problem-num">10%</div>
        <div class="problem-label">of incidents result in police attendance</div>
      </div>
      <div class="problem-item">
        <div class="problem-num">70%</div>
        <div class="problem-label">of crime is committed by just 10% of offenders</div>
      </div>
      <div class="problem-item">
        <div class="problem-num">95%</div>
        <div class="problem-label">of retail crime is never formally reported</div>
      </div>
      <div class="problem-item">
        <div class="problem-num">55,000</div>
        <div class="problem-label">retail thefts happen every single day</div>
      </div>
    </div>
  </div>
</div>

<!-- ══ FEATURES ══ -->
<section class="section" id="features">
  <div class="container">
    <div class="text-center">
      <div class="section-label">Features</div>
      <h2>Everything you need.<br>Nothing you don't.</h2>
      <p style="max-width:520px;margin:16px auto 0">Designed for the shop floor — not a head office. Simple enough for any member of staff to use. Powerful enough to build real intelligence.</p>
    </div>
    <div class="grid-3 mt-40">
      <div class="feature-card">
        <div class="feature-icon">📋</div>
        <h3>Incident recording</h3>
        <p>Log crime in under five minutes with our guided 5-step wizard. Crime type, time, location, description — structured so every record is consistent and usable.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">📎</div>
        <h3>Evidence capture</h3>
        <p>Upload photos, CCTV stills, and video directly from your phone. Every file is encrypted and stored securely on UK servers the moment you hit upload.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">📝</div>
        <h3>Witness statements</h3>
        <p>Our guided statement wizard walks staff through exactly what to say — producing court-ready witness statements that actually stand up when it matters.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">👤</div>
        <h3>Person of interest profiles</h3>
        <p>Build intelligence profiles on repeat offenders. Link incidents, track methods of offending, and see when the same person has been flagged by other stores near you.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">📡</div>
        <h3>Network alerts</h3>
        <p>When a nearby store logs an incident, you hear about it immediately. Real-time alerts within your chosen radius — so your staff are always one step ahead.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">📊</div>
        <h3>Analytics & insights</h3>
        <p>See your crime trends, peak times, hotspot days, and total losses at a glance. Use real data to make smarter decisions about staffing and security.</p>
      </div>
    </div>
  </div>
</section>

<!-- ══ HOW IT WORKS ══ -->
<section class="section how-bg" id="how-it-works">
  <div class="container">
    <div class="grid-2">
      <div>
        <div class="section-label">How it works</div>
        <h2>From incident to intelligence in five steps.</h2>
        <p class="mt-16" style="margin-bottom:36px">Designed so that any member of staff — with zero training — can produce a record that is genuinely useful to your team, your network, and the police.</p>
        <div class="steps-list">
          <div class="step">
            <div class="step-num">1</div>
            <div class="step-content">
              <h3>Log the incident</h3>
              <p>Crime type, date, time, location, and description. Structured fields mean nothing gets missed.</p>
            </div>
          </div>
          <div class="step-connector"></div>
          <div class="step">
            <div class="step-num">2</div>
            <div class="step-content">
              <h3>Upload your evidence</h3>
              <p>Photos, CCTV stills, video. Encrypted and stored securely in the UK the moment you upload.</p>
            </div>
          </div>
          <div class="step-connector"></div>
          <div class="step">
            <div class="step-num">3</div>
            <div class="step-content">
              <h3>Describe the suspect</h3>
              <p>Structured suspect description — appearance, clothing, vehicle, method of offending.</p>
            </div>
          </div>
          <div class="step-connector"></div>
          <div class="step">
            <div class="step-num">4</div>
            <div class="step-content">
              <h3>Capture a witness statement</h3>
              <p>Our guided wizard produces a CPS-aligned statement that is ready to hand to police.</p>
            </div>
          </div>
          <div class="step-connector"></div>
          <div class="step">
            <div class="step-num">5</div>
            <div class="step-content">
              <h3>Share to your network</h3>
              <p>One tap sends an alert to every Op Checkout store within your radius. Everyone stays informed.</p>
            </div>
          </div>
        </div>
      </div>
      <!-- Mock screen preview -->
      <div style="background:var(--navy);border-radius:16px;padding:24px;box-shadow:0 24px 64px rgba(13,31,76,0.3)">
        <div style="background:#0A1838;border-radius:10px;padding:14px;margin-bottom:12px">
          <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:12px">
            <span style="color:white;font-size:13px;font-weight:700">Log Incident</span>
            <span style="background:rgba(255,255,255,0.1);color:rgba(255,255,255,0.6);font-size:11px;padding:3px 8px;border-radius:4px">Step 1 of 5</span>
          </div>
          <div style="display:flex;gap:6px;margin-bottom:16px">
            <div style="flex:1;height:3px;background:#7CB9FF;border-radius:2px"></div>
            <div style="flex:1;height:3px;background:rgba(255,255,255,0.15);border-radius:2px"></div>
            <div style="flex:1;height:3px;background:rgba(255,255,255,0.15);border-radius:2px"></div>
            <div style="flex:1;height:3px;background:rgba(255,255,255,0.15);border-radius:2px"></div>
            <div style="flex:1;height:3px;background:rgba(255,255,255,0.15);border-radius:2px"></div>
          </div>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px">
            <div>
              <div style="font-size:10px;color:rgba(255,255,255,0.4);margin-bottom:4px">Crime type</div>
              <div style="background:rgba(255,255,255,0.08);border-radius:6px;padding:8px 10px;font-size:12px;color:white">Shoplifting</div>
            </div>
            <div>
              <div style="font-size:10px;color:rgba(255,255,255,0.4);margin-bottom:4px">Date</div>
              <div style="background:rgba(255,255,255,0.08);border-radius:6px;padding:8px 10px;font-size:12px;color:white">24 Jun 2026</div>
            </div>
            <div>
              <div style="font-size:10px;color:rgba(255,255,255,0.4);margin-bottom:4px">Time</div>
              <div style="background:rgba(255,255,255,0.08);border-radius:6px;padding:8px 10px;font-size:12px;color:white">14:22</div>
            </div>
            <div>
              <div style="font-size:10px;color:rgba(255,255,255,0.4);margin-bottom:4px">Location</div>
              <div style="background:rgba(255,255,255,0.08);border-radius:6px;padding:8px 10px;font-size:12px;color:white">Shop floor</div>
            </div>
          </div>
          <div style="margin-top:8px">
            <div style="font-size:10px;color:rgba(255,255,255,0.4);margin-bottom:4px">Value lost</div>
            <div style="background:rgba(255,255,255,0.08);border-radius:6px;padding:8px 10px;font-size:12px;color:white">£48.00</div>
          </div>
        </div>
        <div style="background:#D0312D;border-radius:8px;padding:10px 14px;margin-bottom:10px">
          <div style="font-size:11px;font-weight:700;color:white;letter-spacing:0.05em">🔴 NETWORK ALERT — 0.4 MILES</div>
          <div style="font-size:11px;color:rgba(255,255,255,0.8);margin-top:2px">Co-op Ringwood · Shoplifting · Male, 30s, navy jacket</div>
        </div>
        <div style="display:grid;grid-template-columns:1fr 1fr 1fr 1fr;gap:8px">
          <div style="background:rgba(255,255,255,0.06);border-radius:6px;padding:10px;text-align:center">
            <div style="font-size:18px;font-weight:800;color:white">3</div>
            <div style="font-size:9px;color:rgba(255,255,255,0.4);margin-top:2px">Open</div>
          </div>
          <div style="background:rgba(255,255,255,0.06);border-radius:6px;padding:10px;text-align:center">
            <div style="font-size:18px;font-weight:800;color:#7CB9FF">£840</div>
            <div style="font-size:9px;color:rgba(255,255,255,0.4);margin-top:2px">Lost</div>
          </div>
          <div style="background:rgba(255,255,255,0.06);border-radius:6px;padding:10px;text-align:center">
            <div style="font-size:18px;font-weight:800;color:#FCD34D">5</div>
            <div style="font-size:9px;color:rgba(255,255,255,0.4);margin-top:2px">Alerts</div>
          </div>
          <div style="background:rgba(255,255,255,0.06);border-radius:6px;padding:10px;text-align:center">
            <div style="font-size:18px;font-weight:800;color:#4ADE80">7</div>
            <div style="font-size:9px;color:rgba(255,255,255,0.4);margin-top:2px">POIs</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ══ NETWORK ══ -->
<section class="section" id="network">
  <div class="container">
    <div class="grid-2">
      <div>
        <div class="network-card">
          <div class="section-label" style="background:rgba(255,255,255,0.1);color:rgba(255,255,255,0.8)">Network intelligence</div>
          <h3 style="font-size:1.3rem;margin-top:8px">Real-time alerts from every store in your area.</h3>
          <p>When a neighbouring store logs an incident, you know about it immediately. Issue BOLOs, share suspect descriptions, and build a community intelligence network that protects everyone.</p>
          <div class="alert-preview" style="margin-top:20px">
            <div class="alert-dot red"></div>
            <div><div class="alert-title">BOLO — prolific offender active</div><div class="alert-sub">7 incidents · 3 stores · Do not confront</div></div>
          </div>
          <div class="alert-preview">
            <div class="alert-dot amber"></div>
            <div><div class="alert-title">Network alert — Co-op Ringwood</div><div class="alert-sub">Theft of spirits · Male 30s · 0.4 miles · 11:32</div></div>
          </div>
          <div class="alert-preview">
            <div class="alert-dot green"></div>
            <div><div class="alert-title">POI cross-match found</div><div class="alert-sub">OC-0881 suspect linked to 2 other stores</div></div>
          </div>
        </div>
      </div>
      <div>
        <div class="section-label">Why it matters</div>
        <h2>The top 10% of offenders cause 70% of retail crime.</h2>
        <p class="mt-16">These people are known. They hit the same streets, the same store types, the same products — week after week. The intelligence exists. It just isn't connected.</p>
        <p class="mt-16">Op Checkout connects it. Every store that joins makes the network stronger for everyone around them. When Store A logs a suspect, Store B — two streets away — knows about it before they walk through the door.</p>
        <div class="grid-2 mt-40" style="gap:16px">
          <div style="padding:20px;background:var(--grey-l);border-radius:var(--r);border:1px solid var(--border)">
            <div style="font-size:1.6rem;font-weight:800;color:var(--navy)">1 mile</div>
            <div style="font-size:13px;color:var(--muted);margin-top:4px">Default alert radius — configurable up to 10 miles</div>
          </div>
          <div style="padding:20px;background:var(--grey-l);border-radius:var(--r);border:1px solid var(--border)">
            <div style="font-size:1.6rem;font-weight:800;color:var(--navy)">30 days</div>
            <div style="font-size:13px;color:var(--muted);margin-top:4px">BOLO auto-expiry — GDPR compliant by design</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ══ COMPLIANCE ══ -->
<div class="compliance section-sm">
  <div class="container">
    <div class="compliance-inner">
      <div class="compliance-item">
        <div class="compliance-icon">🔒</div>
        <div>
          <div class="compliance-text">UK GDPR compliant</div>
          <div class="compliance-sub">Built to DPA 2018 standards from day one</div>
        </div>
      </div>
      <div class="compliance-item">
        <div class="compliance-icon">🇬🇧</div>
        <div>
          <div class="compliance-text">UK servers only</div>
          <div class="compliance-sub">Your data never leaves England & Wales</div>
        </div>
      </div>
      <div class="compliance-item">
        <div class="compliance-icon">🔐</div>
        <div>
          <div class="compliance-text">End-to-end encrypted</div>
          <div class="compliance-sub">AES-256 at rest · TLS 1.3 in transit</div>
        </div>
      </div>
      <div class="compliance-item">
        <div class="compliance-icon">📋</div>
        <div>
          <div class="compliance-text">CPS-aligned evidence</div>
          <div class="compliance-sub">Statements and records built for court</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ══ PRICING ══ -->
<section class="section" id="pricing">
  <div class="container">
    <div class="text-center">
      <div class="section-label">Pricing</div>
      <h2>Simple, transparent pricing.</h2>
      <p style="max-width:480px;margin:16px auto 0">Every tier includes the full Op Checkout feature set. No hidden costs. No long-term contracts. Start with a free 3-month pilot.</p>
    </div>
    <div class="grid-3 mt-40">
      <div class="price-card">
        <div class="price-badge blue">Starter</div>
        <div class="price-name">Independent stores</div>
        <div class="price-amount">£29 <span>/ site / month</span></div>
        <div class="price-desc">Perfect for independent convenience stores, off-licences, and single-site retailers.</div>
        <div class="price-feature">Incident recording & evidence upload</div>
        <div class="price-feature">5-step guided statement wizard</div>
        <div class="price-feature">Basic POI profiling</div>
        <div class="price-feature">Geo-radius network alerts</div>
        <div class="price-feature">1 manager account</div>
        <div class="price-feature">UK encrypted data storage</div>
        <a href="#" class="btn btn-outline" style="width:100%;justify-content:center;margin-top:24px">Start free trial</a>
      </div>
      <div class="price-card featured">
        <div class="price-badge popular">Most popular</div>
        <div class="price-name">Pro</div>
        <div class="price-amount">£49 <span>/ site / month</span></div>
        <div class="price-desc">For small chains and multi-site retailers who need cross-store intelligence.</div>
        <div class="price-feature">Everything in Starter</div>
        <div class="price-feature">Cross-store intelligence sharing</div>
        <div class="price-feature">BOLO notices</div>
        <div class="price-feature">Analytics dashboard</div>
        <div class="price-feature">Up to 10 user accounts</div>
        <div class="price-feature">Priority support</div>
        <a href="#" class="btn btn-primary" style="width:100%;justify-content:center;margin-top:24px">Start free trial</a>
      </div>
      <div class="price-card">
        <div class="price-badge blue">Business</div>
        <div class="price-name">50+ sites</div>
        <div class="price-amount">£39 <span>/ site / month</span></div>
        <div class="price-desc">Volume pricing for mid-size chains. Everything included, with dedicated onboarding.</div>
        <div class="price-feature">Everything in Pro</div>
        <div class="price-feature">Volume discount pricing</div>
        <div class="price-feature">Dedicated onboarding support</div>
        <div class="price-feature">Unlimited user accounts</div>
        <div class="price-feature">API access</div>
        <div class="price-feature">Advanced analytics</div>
        <a href="#" class="btn btn-outline" style="width:100%;justify-content:center;margin-top:24px">Contact us</a>
      </div>
    </div>
    <p style="text-align:center;font-size:13px;color:var(--muted);margin-top:24px">All plans include a free 3-month pilot. No credit card required. Cancel any time.</p>
  </div>
</section>

<!-- ══ ABOUT ══ -->
<section class="section how-bg" id="about">
  <div class="container">
    <div class="grid-2">
      <div>
        <div class="section-label">Our story</div>
        <h2>Built by someone who knows the problem.</h2>
        <p class="mt-16">Op Checkout was founded because I saw a gap that nobody was filling. Retail crime in England and Wales is at record levels — and the vast majority of retailers, particularly independent stores and small chains, have no proper tools to record it, share intelligence, or take action.</p>
        <p class="mt-16">The intelligence to catch prolific offenders exists. It just lives in fragments — a CCTV still in one store, a description written on a Post-it in another. Op Checkout connects those fragments into something that actually works.</p>
        <p class="mt-16">We are building this platform for the high street, not the boardroom. If you run a store in England or Wales and retail crime is a problem for you — Op Checkout is built for you.</p>
        <div style="margin-top:28px;padding:20px;background:var(--white);border-radius:var(--r);border:1px solid var(--border)">
          <div style="font-size:15px;font-weight:700;color:var(--navy)">Callum Lynch</div>
          <div style="font-size:13px;color:var(--muted);margin-top:2px">Founder & Director · Operation Checkout Ltd</div>
          <div style="font-size:13px;color:var(--muted);margin-top:8px;font-style:italic">"Every store that joins Op Checkout makes the network stronger for everyone around them."</div>
        </div>
      </div>
      <div style="display:flex;flex-direction:column;gap:16px">
        <div style="background:var(--white);border-radius:var(--r);border:1px solid var(--border);padding:24px">
          <div style="font-size:2rem;font-weight:800;color:var(--navy)">300,000+</div>
          <div style="font-size:14px;color:var(--muted);margin-top:4px">Retail sites in England & Wales we are building this for</div>
        </div>
        <div style="background:var(--white);border-radius:var(--r);border:1px solid var(--border);padding:24px">
          <div style="font-size:2rem;font-weight:800;color:var(--navy)">England & Wales</div>
          <div style="font-size:14px;color:var(--muted);margin-top:4px">The only retail crime platform built first for our legal system, our police, and our high street</div>
        </div>
        <div style="background:var(--white);border-radius:var(--r);border:1px solid var(--border);padding:24px">
          <div style="font-size:2rem;font-weight:800;color:var(--navy)">Phase 1</div>
          <div style="font-size:14px;color:var(--muted);margin-top:4px">Currently in pilot — accepting applications from early adopter retailers</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ══ CTA ══ -->
<section class="cta-section">
  <div class="container">
    <div class="section-label" style="background:rgba(255,255,255,0.1);color:rgba(255,255,255,0.8)">Get started</div>
    <h2>Ready to take back control?</h2>
    <p>Join Op Checkout and give your store the intelligence tools it deserves. Free 3-month pilot. No contract. No credit card.</p>
    <div class="cta-actions">
      <a href="#" class="btn btn-white btn-lg">Start your free trial</a>
      <a href="mailto:hello@opcheckout.co.uk" class="btn btn-outline btn-lg" style="border-color:rgba(255,255,255,0.3);color:rgba(255,255,255,0.85)">Get in touch</a>
    </div>
  </div>
</section>

<!-- ══ FOOTER ══ -->
<footer class="footer">
  <div class="container">
    <div class="footer-inner">
      <div class="footer-brand">
        <a href="#" class="nav-logo">
          <div class="nav-logo-icon">
            <svg viewBox="0 0 22 22" fill="none">
              <path d="M11 2L3.5 6.5V11C3.5 15.14 6.86 18.97 11 20C15.14 18.97 18.5 15.14 18.5 11V6.5L11 2Z" fill="white" opacity="0.15"/>
              <path d="M11 2L3.5 6.5V11C3.5 15.14 6.86 18.97 11 20C15.14 18.97 18.5 15.14 18.5 11V6.5L11 2Z" stroke="white" stroke-width="1.5" stroke-linejoin="round"/>
              <path d="M7.5 11L9.5 13L14.5 8.5" stroke="white" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
          </div>
          <span class="nav-brand">Op Checkout</span>
        </a>
        <p>England & Wales' leading retail crime intelligence platform. Built for the high street, not the boardroom.</p>
      </div>
      <div class="footer-col">
        <h4>Product</h4>
        <a href="#features">Features</a>
        <a href="#how-it-works">How it works</a>
        <a href="#network">Network</a>
        <a href="#pricing">Pricing</a>
      </div>
      <div class="footer-col">
        <h4>Company</h4>
        <a href="#about">About</a>
        <a href="mailto:hello@opcheckout.co.uk">Contact</a>
        <a href="#">Blog</a>
        <a href="#">Partners</a>
      </div>
      <div class="footer-col">
        <h4>Legal</h4>
        <a href="#">Privacy policy</a>
        <a href="#">Terms of service</a>
        <a href="#">Data processing agreement</a>
        <a href="#">Cookie policy</a>
      </div>
    </div>
    <div class="footer-bottom">
      <p>© 2026 Operation Checkout Ltd. Registered in England & Wales.</p>
      <div style="display:flex;gap:12px;align-items:center;flex-wrap:wrap">
        <span class="gdpr-badge">🔒 UK GDPR Compliant</span>
        <span class="gdpr-badge" style="background:var(--navy-l);color:var(--navy)">🇬🇧 UK Data Only</span>
      </div>
    </div>
  </div>
</footer>

</body>
</html>
