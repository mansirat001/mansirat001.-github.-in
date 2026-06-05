<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mansirat Singh — Student & Lifelong Learner</title>
  <link rel="preconnect" href="https://fonts.googleapis.com"/>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet"/>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>

  <style>
    /* ============================================================
       CSS VARIABLES & RESET
    ============================================================ */
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg:       #070b14;
      --bg2:      #0d1423;
      --surface:  rgba(255,255,255,0.04);
      --border:   rgba(255,255,255,0.08);
      --gold:     #e8b94f;
      --gold2:    #f5d78e;
      --teal:     #3de8c8;
      --blue:     #4f8ef5;
      --text:     #e8eaf0;
      --muted:    #8892a4;
      --white:    #ffffff;
      --r:        16px;
      --ease:     cubic-bezier(.4,0,.2,1);
    }

    html { scroll-behavior: smooth; font-size: 16px; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'DM Sans', sans-serif;
      line-height: 1.65;
      overflow-x: hidden;
    }

    ::selection { background: var(--gold); color: #000; }

    /* ============================================================
       SCROLLBAR
    ============================================================ */
    ::-webkit-scrollbar { width: 5px; }
    ::-webkit-scrollbar-track { background: var(--bg); }
    ::-webkit-scrollbar-thumb { background: var(--gold); border-radius: 4px; }

    /* ============================================================
       LOADING SCREEN
    ============================================================ */
    #loader {
      position: fixed; inset: 0;
      background: var(--bg);
      z-index: 9999;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 24px;
      transition: opacity .6s var(--ease), visibility .6s;
    }
    #loader.hidden { opacity: 0; visibility: hidden; pointer-events: none; }

    .loader-logo {
      font-family: 'Syne', sans-serif;
      font-size: 2.4rem;
      font-weight: 800;
      background: linear-gradient(135deg, var(--gold), var(--teal));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      letter-spacing: -1px;
    }

    .loader-bar-wrap {
      width: 200px;
      height: 3px;
      background: var(--border);
      border-radius: 99px;
      overflow: hidden;
    }
    .loader-bar {
      height: 100%;
      width: 0%;
      background: linear-gradient(90deg, var(--gold), var(--teal));
      border-radius: 99px;
      animation: loadBar 1.8s var(--ease) forwards;
    }
    @keyframes loadBar { to { width: 100%; } }

    /* ============================================================
       NAVIGATION
    ============================================================ */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      padding: 18px 5%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      backdrop-filter: blur(18px);
      -webkit-backdrop-filter: blur(18px);
      background: rgba(7,11,20,.7);
      border-bottom: 1px solid var(--border);
      transition: padding .3s var(--ease);
    }
    nav.scrolled { padding: 12px 5%; }

    .nav-logo {
      font-family: 'Syne', sans-serif;
      font-size: 1.4rem;
      font-weight: 800;
      background: linear-gradient(135deg, var(--gold), var(--teal));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      letter-spacing: -0.5px;
      text-decoration: none;
    }

    .nav-links {
      display: flex;
      gap: 36px;
      list-style: none;
    }
    .nav-links a {
      color: var(--muted);
      text-decoration: none;
      font-size: .88rem;
      font-weight: 500;
      letter-spacing: .04em;
      text-transform: uppercase;
      transition: color .25s;
      position: relative;
    }
    .nav-links a::after {
      content: '';
      position: absolute;
      bottom: -4px; left: 0;
      width: 0; height: 1px;
      background: var(--gold);
      transition: width .3s var(--ease);
    }
    .nav-links a:hover { color: var(--gold); }
    .nav-links a:hover::after { width: 100%; }

    .nav-toggle {
      display: none;
      flex-direction: column;
      gap: 5px;
      cursor: pointer;
      padding: 4px;
    }
    .nav-toggle span {
      display: block;
      width: 24px; height: 2px;
      background: var(--text);
      border-radius: 2px;
      transition: transform .3s, opacity .3s;
    }

    /* ============================================================
       HERO SECTION
    ============================================================ */
    #hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      overflow: hidden;
      padding: 120px 5% 80px;
    }

    /* Animated mesh background */
    .hero-bg {
      position: absolute;
      inset: 0;
      background:
        radial-gradient(ellipse 60% 50% at 20% 30%, rgba(232,185,79,.12) 0%, transparent 70%),
        radial-gradient(ellipse 50% 60% at 80% 70%, rgba(61,232,200,.09) 0%, transparent 70%),
        radial-gradient(ellipse 40% 40% at 50% 50%, rgba(79,142,245,.07) 0%, transparent 60%);
      animation: meshPulse 8s ease-in-out infinite alternate;
    }
    @keyframes meshPulse {
      0%   { opacity: .7; transform: scale(1); }
      100% { opacity: 1;  transform: scale(1.04); }
    }

    /* Grid lines */
    .hero-grid {
      position: absolute;
      inset: 0;
      background-image:
        linear-gradient(rgba(255,255,255,.025) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,.025) 1px, transparent 1px);
      background-size: 60px 60px;
      mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black 40%, transparent 100%);
    }

    /* Floating orbs */
    .orb {
      position: absolute;
      border-radius: 50%;
      filter: blur(80px);
      pointer-events: none;
    }
    .orb-1 {
      width: 500px; height: 500px;
      background: radial-gradient(circle, rgba(232,185,79,.18), transparent 70%);
      top: -100px; left: -100px;
      animation: float1 12s ease-in-out infinite;
    }
    .orb-2 {
      width: 400px; height: 400px;
      background: radial-gradient(circle, rgba(61,232,200,.14), transparent 70%);
      bottom: -80px; right: -80px;
      animation: float2 10s ease-in-out infinite;
    }
    .orb-3 {
      width: 300px; height: 300px;
      background: radial-gradient(circle, rgba(79,142,245,.12), transparent 70%);
      top: 50%; left: 50%;
      transform: translate(-50%,-50%);
      animation: float3 14s ease-in-out infinite;
    }
    @keyframes float1 { 0%,100% { transform: translate(0,0); } 50% { transform: translate(40px,30px); } }
    @keyframes float2 { 0%,100% { transform: translate(0,0); } 50% { transform: translate(-30px,-40px); } }
    @keyframes float3 { 0%,100% { transform: translate(-50%,-50%); } 50% { transform: translate(-46%,-46%); } }

    /* Particles */
    #particles-canvas {
      position: absolute;
      inset: 0;
      pointer-events: none;
    }

    .hero-content {
      position: relative;
      z-index: 2;
      text-align: center;
      max-width: 820px;
    }

    .hero-badge {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 8px 18px;
      border: 1px solid rgba(232,185,79,.3);
      border-radius: 99px;
      font-size: .8rem;
      font-weight: 500;
      letter-spacing: .06em;
      text-transform: uppercase;
      color: var(--gold);
      background: rgba(232,185,79,.06);
      margin-bottom: 28px;
      backdrop-filter: blur(8px);
      animation: fadeUp .8s var(--ease) .3s both;
    }
    .hero-badge .dot {
      width: 7px; height: 7px;
      background: var(--gold);
      border-radius: 50%;
      animation: blink 1.6s ease-in-out infinite;
    }
    @keyframes blink { 0%,100% { opacity: 1; } 50% { opacity: .3; } }

    .hero-name {
      font-family: 'Syne', sans-serif;
      font-size: clamp(3rem, 8vw, 6.5rem);
      font-weight: 800;
      line-height: 1.05;
      letter-spacing: -2px;
      background: linear-gradient(135deg, var(--white) 0%, var(--gold2) 50%, var(--teal) 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      animation: fadeUp .9s var(--ease) .5s both;
      margin-bottom: 16px;
    }

    .hero-subtitle {
      font-size: clamp(1rem, 2.5vw, 1.25rem);
      color: var(--muted);
      font-weight: 300;
      letter-spacing: .02em;
      animation: fadeUp .9s var(--ease) .7s both;
      margin-bottom: 20px;
    }
    .hero-subtitle span { color: var(--teal); font-weight: 500; }

    .hero-tagline {
      font-family: 'Syne', sans-serif;
      font-size: clamp(1.1rem, 2.8vw, 1.5rem);
      font-weight: 600;
      color: var(--white);
      animation: fadeUp .9s var(--ease) .9s both;
      margin-bottom: 48px;
      position: relative;
      display: inline-block;
    }
    .hero-tagline::before, .hero-tagline::after {
      content: '"';
      color: var(--gold);
      font-size: 1.8em;
      line-height: 0;
      vertical-align: -0.3em;
    }
    .hero-tagline::before { margin-right: 6px; }
    .hero-tagline::after  { margin-left: 6px; }

    .hero-cta {
      display: flex;
      gap: 16px;
      justify-content: center;
      flex-wrap: wrap;
      animation: fadeUp .9s var(--ease) 1.1s both;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      padding: 14px 32px;
      border-radius: 99px;
      font-size: .95rem;
      font-weight: 500;
      cursor: pointer;
      text-decoration: none;
      transition: transform .25s var(--ease), box-shadow .25s var(--ease);
      border: none;
    }
    .btn:hover { transform: translateY(-3px); }

    .btn-primary {
      background: linear-gradient(135deg, var(--gold), #d4a03b);
      color: #000;
      box-shadow: 0 8px 30px rgba(232,185,79,.3);
    }
    .btn-primary:hover { box-shadow: 0 12px 40px rgba(232,185,79,.45); }

    .btn-outline {
      background: transparent;
      color: var(--text);
      border: 1px solid var(--border);
      backdrop-filter: blur(8px);
    }
    .btn-outline:hover { border-color: var(--gold); color: var(--gold); box-shadow: 0 8px 24px rgba(232,185,79,.1); }

    /* Scroll indicator */
    .scroll-hint {
      position: absolute;
      bottom: 36px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 8px;
      color: var(--muted);
      font-size: .78rem;
      letter-spacing: .08em;
      text-transform: uppercase;
      animation: fadeUp .9s var(--ease) 1.5s both;
    }
    .scroll-mouse {
      width: 24px; height: 40px;
      border: 1.5px solid var(--border);
      border-radius: 12px;
      position: relative;
    }
    .scroll-mouse::after {
      content: '';
      position: absolute;
      width: 4px; height: 8px;
      background: var(--gold);
      border-radius: 2px;
      top: 6px;
      left: 50%;
      transform: translateX(-50%);
      animation: scrollDot 1.8s ease-in-out infinite;
    }
    @keyframes scrollDot { 0%,100% { opacity: 1; top: 6px; } 100% { opacity: 0; top: 22px; } }

    /* ============================================================
       SECTION COMMON
    ============================================================ */
    section { padding: 100px 5%; }

    .section-label {
      display: inline-flex;
      align-items: center;
      gap: 10px;
      color: var(--gold);
      font-size: .78rem;
      font-weight: 600;
      letter-spacing: .14em;
      text-transform: uppercase;
      margin-bottom: 16px;
    }
    .section-label::before {
      content: '';
      width: 28px; height: 1px;
      background: var(--gold);
    }

    .section-title {
      font-family: 'Syne', sans-serif;
      font-size: clamp(2rem, 4.5vw, 3.2rem);
      font-weight: 800;
      letter-spacing: -1.5px;
      line-height: 1.1;
      color: var(--white);
      margin-bottom: 20px;
    }
    .section-title em {
      font-style: normal;
      background: linear-gradient(135deg, var(--gold), var(--teal));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .section-desc {
      color: var(--muted);
      font-size: 1.05rem;
      max-width: 560px;
      line-height: 1.75;
    }

    /* reveal animation */
    .reveal {
      opacity: 0;
      transform: translateY(40px);
      transition: opacity .75s var(--ease), transform .75s var(--ease);
    }
    .reveal.visible { opacity: 1; transform: none; }
    .reveal-delay-1 { transition-delay: .1s; }
    .reveal-delay-2 { transition-delay: .2s; }
    .reveal-delay-3 { transition-delay: .3s; }
    .reveal-delay-4 { transition-delay: .4s; }
    .reveal-delay-5 { transition-delay: .5s; }

    /* Glass card */
    .glass {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--r);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
    }

    /* ============================================================
       STATS BAR (between hero and about)
    ============================================================ */
    .stats-bar {
      padding: 0 5%;
      margin-top: -1px;
    }
    .stats-inner {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1px;
      background: var(--border);
      border: 1px solid var(--border);
      border-radius: var(--r);
      overflow: hidden;
    }
    .stat-item {
      padding: 32px 28px;
      background: var(--surface);
      text-align: center;
      transition: background .3s;
    }
    .stat-item:hover { background: rgba(232,185,79,.06); }
    .stat-number {
      font-family: 'Syne', sans-serif;
      font-size: 2.4rem;
      font-weight: 800;
      color: var(--gold);
      line-height: 1;
      margin-bottom: 6px;
    }
    .stat-label {
      font-size: .82rem;
      color: var(--muted);
      letter-spacing: .04em;
      text-transform: uppercase;
    }

    /* ============================================================
       ABOUT SECTION
    ============================================================ */
    #about {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 80px;
      align-items: center;
    }

    .about-visual {
      position: relative;
      aspect-ratio: 1;
      max-width: 420px;
    }
    .about-visual-card {
      width: 100%;
      height: 100%;
      border-radius: 24px;
      background: linear-gradient(135deg, rgba(232,185,79,.12), rgba(61,232,200,.08));
      border: 1px solid var(--border);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 20px;
      position: relative;
      overflow: hidden;
    }
    .about-visual-card::before {
      content: '';
      position: absolute;
      inset: 0;
      background: radial-gradient(circle at 30% 30%, rgba(232,185,79,.15), transparent 60%);
      pointer-events: none;
    }
    .about-avatar {
      width: 120px; height: 120px;
      border-radius: 50%;
      background: linear-gradient(135deg, var(--gold), var(--teal));
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Syne', sans-serif;
      font-size: 2.8rem;
      font-weight: 800;
      color: #000;
      position: relative;
      z-index: 1;
      box-shadow: 0 0 40px rgba(232,185,79,.3);
    }
    .about-avatar-name {
      font-family: 'Syne', sans-serif;
      font-size: 1.3rem;
      font-weight: 700;
      color: var(--white);
      position: relative;
      z-index: 1;
    }
    .about-avatar-role {
      font-size: .88rem;
      color: var(--teal);
      position: relative;
      z-index: 1;
    }

    /* floating tags */
    .float-tag {
      position: absolute;
      padding: 10px 16px;
      border-radius: 99px;
      font-size: .78rem;
      font-weight: 500;
      display: flex;
      align-items: center;
      gap: 7px;
      backdrop-filter: blur(12px);
    }
    .ft-1 {
      top: 20px; left: -30px;
      background: rgba(232,185,79,.12);
      border: 1px solid rgba(232,185,79,.25);
      color: var(--gold2);
      animation: tagFloat 4s ease-in-out infinite;
    }
    .ft-2 {
      bottom: 40px; right: -30px;
      background: rgba(61,232,200,.1);
      border: 1px solid rgba(61,232,200,.2);
      color: var(--teal);
      animation: tagFloat 5s ease-in-out infinite reverse;
    }
    .ft-3 {
      bottom: 10px; left: -10px;
      background: rgba(79,142,245,.1);
      border: 1px solid rgba(79,142,245,.2);
      color: var(--blue);
      animation: tagFloat 6s ease-in-out infinite 1s;
    }
    @keyframes tagFloat {
      0%,100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    .about-text .section-desc { max-width: 100%; }
    .about-highlights {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 28px;
    }
    .highlight-chip {
      padding: 8px 16px;
      border-radius: 99px;
      font-size: .82rem;
      font-weight: 500;
      background: var(--surface);
      border: 1px solid var(--border);
      color: var(--text);
      transition: border-color .25s, color .25s;
    }
    .highlight-chip:hover { border-color: var(--gold); color: var(--gold); }

    /* ============================================================
       EDUCATION SECTION
    ============================================================ */
    #education { background: var(--bg2); }
    #education .section-inner { max-width: 900px; margin: 0 auto; }

    .edu-header { margin-bottom: 56px; }

    .timeline {
      position: relative;
      padding-left: 40px;
    }
    .timeline::before {
      content: '';
      position: absolute;
      left: 15px; top: 0; bottom: 0;
      width: 1px;
      background: linear-gradient(to bottom, var(--gold), var(--teal), transparent);
    }

    .timeline-item {
      position: relative;
      margin-bottom: 48px;
    }
    .timeline-item:last-child { margin-bottom: 0; }

    .timeline-dot {
      position: absolute;
      left: -33px;
      top: 8px;
      width: 18px; height: 18px;
      border-radius: 50%;
      border: 2px solid var(--gold);
      background: var(--bg);
      display: flex;
      align-items: center;
      justify-content: center;
      transition: background .3s;
    }
    .timeline-dot::after {
      content: '';
      width: 7px; height: 7px;
      border-radius: 50%;
      background: var(--gold);
    }
    .timeline-item:hover .timeline-dot { background: var(--gold); }
    .timeline-item:hover .timeline-dot::after { background: #000; }

    .timeline-card {
      padding: 28px 32px;
      border-radius: var(--r);
      background: var(--surface);
      border: 1px solid var(--border);
      transition: border-color .3s, transform .3s, box-shadow .3s;
      cursor: default;
    }
    .timeline-card:hover {
      border-color: rgba(232,185,79,.3);
      transform: translateX(6px);
      box-shadow: 0 12px 40px rgba(0,0,0,.3);
    }

    .timeline-year {
      font-size: .78rem;
      font-weight: 600;
      letter-spacing: .1em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 8px;
    }
    .timeline-degree {
      font-family: 'Syne', sans-serif;
      font-size: 1.2rem;
      font-weight: 700;
      color: var(--white);
      margin-bottom: 4px;
    }
    .timeline-school {
      color: var(--muted);
      font-size: .92rem;
      margin-bottom: 12px;
    }
    .timeline-desc { color: var(--muted); font-size: .88rem; line-height: 1.7; }
    .timeline-badge {
      display: inline-block;
      margin-top: 14px;
      padding: 5px 14px;
      border-radius: 99px;
      font-size: .76rem;
      font-weight: 600;
      letter-spacing: .04em;
    }
    .badge-complete { background: rgba(61,232,200,.12); color: var(--teal); border: 1px solid rgba(61,232,200,.25); }
    .badge-ongoing  { background: rgba(232,185,79,.12); color: var(--gold); border: 1px solid rgba(232,185,79,.25); }
    .badge-future   { background: rgba(79,142,245,.12); color: var(--blue); border: 1px solid rgba(79,142,245,.25); }

    /* ============================================================
       SKILLS SECTION
    ============================================================ */
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 56px;
    }

    .skill-card {
      padding: 32px;
      border-radius: var(--r);
      background: var(--surface);
      border: 1px solid var(--border);
      position: relative;
      overflow: hidden;
      transition: transform .3s var(--ease), border-color .3s, box-shadow .3s;
      cursor: default;
    }
    .skill-card::before {
      content: '';
      position: absolute;
      inset: 0;
      opacity: 0;
      transition: opacity .4s;
    }
    .skill-card:hover { transform: translateY(-6px); border-color: rgba(232,185,79,.3); box-shadow: 0 20px 50px rgba(0,0,0,.35); }
    .skill-card:hover::before { opacity: 1; }

    .skill-icon {
      width: 52px; height: 52px;
      border-radius: 14px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.4rem;
      margin-bottom: 20px;
      position: relative;
      z-index: 1;
    }
    .si-gold  { background: rgba(232,185,79,.15); color: var(--gold); }
    .si-teal  { background: rgba(61,232,200,.12); color: var(--teal); }
    .si-blue  { background: rgba(79,142,245,.12); color: var(--blue); }
    .si-pink  { background: rgba(232,107,130,.12); color: #e86b82; }
    .si-green { background: rgba(74,222,128,.12); color: #4ade80; }

    .skill-name {
      font-family: 'Syne', sans-serif;
      font-size: 1.05rem;
      font-weight: 700;
      color: var(--white);
      margin-bottom: 8px;
      position: relative;
      z-index: 1;
    }
    .skill-desc {
      font-size: .86rem;
      color: var(--muted);
      line-height: 1.65;
      margin-bottom: 20px;
      position: relative;
      z-index: 1;
    }

    .skill-bar-wrap {
      height: 4px;
      background: var(--border);
      border-radius: 4px;
      overflow: hidden;
      position: relative;
      z-index: 1;
    }
    .skill-bar {
      height: 100%;
      border-radius: 4px;
      width: 0;
      transition: width 1.2s var(--ease);
    }
    .bar-gold  { background: linear-gradient(90deg, var(--gold), var(--gold2)); }
    .bar-teal  { background: linear-gradient(90deg, var(--teal), #7df5e3); }
    .bar-blue  { background: linear-gradient(90deg, var(--blue), #8bb8ff); }
    .bar-pink  { background: linear-gradient(90deg, #e86b82, #f5a3b0); }
    .bar-green { background: linear-gradient(90deg, #4ade80, #a0f0b8); }

    .skill-pct {
      position: absolute;
      right: 0; top: -22px;
      font-size: .76rem;
      font-weight: 600;
      color: var(--muted);
      position: relative;
      z-index: 1;
      text-align: right;
      margin-top: 6px;
    }

    /* ============================================================
       GOALS SECTION
    ============================================================ */
    #goals { background: var(--bg2); }

    .goals-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
      margin-top: 56px;
    }

    .goal-card {
      padding: 36px 28px;
      border-radius: var(--r);
      background: var(--surface);
      border: 1px solid var(--border);
      text-align: center;
      transition: transform .3s var(--ease), border-color .3s, box-shadow .3s;
      cursor: default;
      position: relative;
      overflow: hidden;
    }
    .goal-card::after {
      content: '';
      position: absolute;
      bottom: 0; left: 0; right: 0;
      height: 2px;
      background: linear-gradient(90deg, var(--gold), var(--teal));
      transform: scaleX(0);
      transition: transform .4s var(--ease);
    }
    .goal-card:hover { transform: translateY(-6px); border-color: rgba(232,185,79,.25); box-shadow: 0 16px 50px rgba(0,0,0,.3); }
    .goal-card:hover::after { transform: scaleX(1); }

    .goal-icon {
      width: 64px; height: 64px;
      border-radius: 50%;
      margin: 0 auto 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.6rem;
      background: linear-gradient(135deg, rgba(232,185,79,.15), rgba(61,232,200,.1));
      border: 1px solid rgba(232,185,79,.2);
    }
    .goal-title {
      font-family: 'Syne', sans-serif;
      font-size: 1.05rem;
      font-weight: 700;
      color: var(--white);
      margin-bottom: 10px;
    }
    .goal-text { font-size: .86rem; color: var(--muted); line-height: 1.65; }

    /* ============================================================
       QUOTE SECTION
    ============================================================ */
    #quotes {
      padding: 80px 5%;
      position: relative;
      overflow: hidden;
    }
    .quotes-bg {
      position: absolute;
      inset: 0;
      background:
        radial-gradient(ellipse 60% 80% at 30% 50%, rgba(232,185,79,.07) 0%, transparent 70%),
        radial-gradient(ellipse 50% 60% at 70% 50%, rgba(61,232,200,.05) 0%, transparent 70%);
    }
    .quotes-inner {
      position: relative;
      z-index: 2;
      max-width: 800px;
      margin: 0 auto;
      text-align: center;
    }
    .quote-carousel { position: relative; min-height: 160px; }

    .quote-slide {
      position: absolute;
      inset: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      opacity: 0;
      transform: translateY(20px);
      transition: opacity .6s var(--ease), transform .6s var(--ease);
      pointer-events: none;
    }
    .quote-slide.active { opacity: 1; transform: none; pointer-events: auto; }

    .quote-mark {
      font-family: 'Syne', sans-serif;
      font-size: 5rem;
      line-height: .6;
      color: var(--gold);
      opacity: .3;
      margin-bottom: 16px;
    }
    .quote-text {
      font-family: 'Syne', sans-serif;
      font-size: clamp(1.1rem, 2.5vw, 1.5rem);
      font-weight: 600;
      color: var(--white);
      line-height: 1.5;
      margin-bottom: 20px;
    }
    .quote-author {
      font-size: .88rem;
      color: var(--gold);
      letter-spacing: .04em;
    }

    .quote-dots {
      display: flex;
      gap: 8px;
      justify-content: center;
      margin-top: 32px;
    }
    .qdot {
      width: 8px; height: 8px;
      border-radius: 50%;
      background: var(--border);
      cursor: pointer;
      transition: background .3s, transform .3s;
    }
    .qdot.active { background: var(--gold); transform: scale(1.3); }

    /* ============================================================
       CONTACT SECTION
    ============================================================ */
    #contact { background: var(--bg2); }

    .contact-wrap {
      max-width: 700px;
      margin: 56px auto 0;
      text-align: center;
    }
    .contact-card {
      padding: 56px 40px;
      border-radius: 24px;
      background: var(--surface);
      border: 1px solid var(--border);
      position: relative;
      overflow: hidden;
    }
    .contact-card::before {
      content: '';
      position: absolute;
      inset: 0;
      background:
        radial-gradient(circle at 20% 20%, rgba(232,185,79,.08), transparent 50%),
        radial-gradient(circle at 80% 80%, rgba(61,232,200,.06), transparent 50%);
      pointer-events: none;
    }

    .contact-avatar {
      width: 88px; height: 88px;
      border-radius: 50%;
      background: linear-gradient(135deg, var(--gold), var(--teal));
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Syne', sans-serif;
      font-size: 2rem;
      font-weight: 800;
      color: #000;
      margin: 0 auto 24px;
      box-shadow: 0 0 30px rgba(232,185,79,.25);
      position: relative;
      z-index: 1;
    }

    .contact-name {
      font-family: 'Syne', sans-serif;
      font-size: 1.6rem;
      font-weight: 800;
      color: var(--white);
      margin-bottom: 8px;
      position: relative;
      z-index: 1;
    }
    .contact-role {
      color: var(--muted);
      font-size: .92rem;
      margin-bottom: 36px;
      position: relative;
      z-index: 1;
    }

    .contact-links {
      display: flex;
      flex-direction: column;
      gap: 14px;
      position: relative;
      z-index: 1;
    }
    .contact-link {
      display: flex;
      align-items: center;
      gap: 14px;
      padding: 16px 22px;
      border-radius: 12px;
      background: rgba(255,255,255,.03);
      border: 1px solid var(--border);
      text-decoration: none;
      color: var(--text);
      transition: border-color .3s, background .3s, transform .3s;
    }
    .contact-link:hover {
      border-color: rgba(232,185,79,.3);
      background: rgba(232,185,79,.06);
      transform: translateX(4px);
      color: var(--gold);
    }
    .cl-icon {
      width: 40px; height: 40px;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.1rem;
      flex-shrink: 0;
    }
    .cl-gold { background: rgba(232,185,79,.15); color: var(--gold); }

    .cl-text { text-align: left; }
    .cl-label { font-size: .76rem; color: var(--muted); letter-spacing: .04em; text-transform: uppercase; }
    .cl-value { font-weight: 500; font-size: .95rem; }

    /* ============================================================
       FOOTER
    ============================================================ */
    footer {
      padding: 40px 5%;
      border-top: 1px solid var(--border);
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 16px;
    }
    .footer-logo {
      font-family: 'Syne', sans-serif;
      font-size: 1.1rem;
      font-weight: 800;
      background: linear-gradient(135deg, var(--gold), var(--teal));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }
    .footer-copy { font-size: .82rem; color: var(--muted); }
    .footer-heart { color: #e86b82; }

    /* ============================================================
       ANIMATIONS
    ============================================================ */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to   { opacity: 1; transform: none; }
    }

    /* ============================================================
       CURSOR GLOW
    ============================================================ */
    .cursor-glow {
      position: fixed;
      width: 320px; height: 320px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(232,185,79,.07) 0%, transparent 70%);
      pointer-events: none;
      z-index: 0;
      transform: translate(-50%, -50%);
      transition: left .12s, top .12s;
    }

    /* ============================================================
       RESPONSIVE
    ============================================================ */
    @media (max-width: 900px) {
      #about {
        grid-template-columns: 1fr;
        gap: 48px;
      }
      .about-visual { max-width: 340px; margin: 0 auto; }
      .stats-inner { grid-template-columns: 1fr; }
    }

    @media (max-width: 768px) {
      .nav-links {
        position: fixed;
        inset: 0; top: 64px;
        background: rgba(7,11,20,.97);
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 32px;
        display: none;
      }
      .nav-links.open { display: flex; }
      .nav-links a { font-size: 1.1rem; }
      .nav-toggle { display: flex; }
      section { padding: 72px 6%; }
      .ft-1, .ft-2, .ft-3 { display: none; }
    }

    @media (max-width: 500px) {
      .hero-cta { flex-direction: column; align-items: center; }
      .contact-card { padding: 36px 20px; }
    }
  </style>
</head>
<body>

  <!-- Cursor glow -->
  <div class="cursor-glow" id="cursorGlow"></div>

  <!-- ========== LOADER ========== -->
  <div id="loader">
    <div class="loader-logo">MS</div>
    <div class="loader-bar-wrap">
      <div class="loader-bar"></div>
    </div>
    <p style="color:var(--muted);font-size:.8rem;letter-spacing:.1em;text-transform:uppercase;">Loading portfolio…</p>
  </div>

  <!-- ========== NAVIGATION ========== -->
  <nav id="navbar">
    <a class="nav-logo" href="#hero">Mansirat</a>
    <ul class="nav-links" id="navLinks">
      <li><a href="#about">About</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#goals">Goals</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <div class="nav-toggle" id="navToggle" aria-label="Toggle menu">
      <span></span><span></span><span></span>
    </div>
  </nav>

  <!-- ========== HERO ========== -->
  <section id="hero">
    <div class="hero-bg"></div>
    <div class="hero-grid"></div>
    <div class="orb orb-1"></div>
    <div class="orb orb-2"></div>
    <div class="orb orb-3"></div>
    <canvas id="particles-canvas"></canvas>

    <div class="hero-content">
      <div class="hero-badge">
        <div class="dot"></div>
        Student &amp; Lifelong Learner
      </div>

      <h1 class="hero-name">Mansirat Singh</h1>

      <p class="hero-subtitle">
        Studying at <span>NIELIT Ropar</span> &nbsp;·&nbsp; Future-Focused Technologist
      </p>

      <p class="hero-tagline">Learning Today, Building Tomorrow</p>

      <div class="hero-cta">
        <a href="#about" class="btn btn-primary">
          <i class="fas fa-user"></i> Discover My Story
        </a>
        <a href="#contact" class="btn btn-outline">
          <i class="fas fa-envelope"></i> Get In Touch
        </a>
      </div>
    </div>

    <div class="scroll-hint">
      <div class="scroll-mouse"></div>
      <span>Scroll</span>
    </div>
  </section>

  <!-- ========== STATS BAR ========== -->
  <div class="stats-bar">
    <div class="stats-inner">
      <div class="stat-item reveal">
        <div class="stat-number" data-count="12">0</div>
        <div class="stat-label">Years of Study</div>
      </div>
      <div class="stat-item reveal reveal-delay-2">
        <div class="stat-number" data-count="100">0<span>%</span></div>
        <div class="stat-label">Dedication</div>
      </div>
      <div class="stat-item reveal reveal-delay-3">
        <div class="stat-number">∞</div>
        <div class="stat-label">Will to Learn</div>
      </div>
    </div>
  </div>

  <!-- ========== ABOUT ========== -->
  <section id="about">
    <div class="about-visual reveal">
      <div class="about-visual-card">
        <div class="about-avatar">MS</div>
        <div class="about-avatar-name">Mansirat Singh</div>
        <div class="about-avatar-role">Student · Learner · Dreamer</div>
      </div>
      <div class="float-tag ft-1"><i class="fas fa-graduation-cap"></i> NIELIT Ropar</div>
      <div class="float-tag ft-2"><i class="fas fa-lightbulb"></i> Always Learning</div>
      <div class="float-tag ft-3"><i class="fas fa-star"></i> 12th Pass</div>
    </div>

    <div class="about-text">
      <p class="section-label reveal">About Me</p>
      <h2 class="section-title reveal reveal-delay-1">Passionate about <em>learning</em> &amp; growth</h2>
      <p class="section-desc reveal reveal-delay-2">
        Hi, I'm <strong style="color:var(--white)">Mansirat Singh</strong> — a dedicated and ambitious student currently enrolled at <strong style="color:var(--teal)">NIELIT Ropar</strong>. I believe that education is the most powerful tool for shaping a better future, and I bring that belief into everything I do.
      </p>
      <br>
      <p class="section-desc reveal reveal-delay-3">
        Having completed my 12th grade, I'm on an exciting journey of discovery — diving deeper into technology, building new skills every day, and setting my sights on a future filled with purpose and achievement. My philosophy is simple: <em style="color:var(--gold2)">never stop learning, never stop growing.</em>
      </p>

      <div class="about-highlights reveal reveal-delay-4">
        <span class="highlight-chip"><i class="fas fa-book" style="color:var(--gold);margin-right:6px"></i>Avid Reader</span>
        <span class="highlight-chip"><i class="fas fa-laptop-code" style="color:var(--teal);margin-right:6px"></i>Tech Enthusiast</span>
        <span class="highlight-chip"><i class="fas fa-bullseye" style="color:var(--blue);margin-right:6px"></i>Goal Oriented</span>
        <span class="highlight-chip"><i class="fas fa-clock" style="color:#e86b82;margin-right:6px"></i>Disciplined</span>
        <span class="highlight-chip"><i class="fas fa-seedling" style="color:#4ade80;margin-right:6px"></i>Always Growing</span>
      </div>
    </div>
  </section>

  <!-- ========== EDUCATION ========== -->
  <section id="education">
    <div class="section-inner">
      <div class="edu-header">
        <p class="section-label reveal">Education</p>
        <h2 class="section-title reveal reveal-delay-1">My <em>academic</em> journey</h2>
        <p class="section-desc reveal reveal-delay-2">Every chapter of my education has been a stepping stone toward a brighter, more capable version of myself.</p>
      </div>

      <div class="timeline">
        <div class="timeline-item reveal">
          <div class="timeline-dot"></div>
          <div class="timeline-card">
            <div class="timeline-year">Completed</div>
            <div class="timeline-degree">12th Grade (Senior Secondary)</div>
            <div class="timeline-school">Senior Secondary School</div>
            <div class="timeline-desc">
              Successfully completed my senior secondary education, building a strong academic foundation across core subjects and developing disciplined study habits that continue to guide me today.
            </div>
            <span class="timeline-badge badge-complete"><i class="fas fa-check-circle" style="margin-right:6px"></i>Completed</span>
          </div>
        </div>

        <div class="timeline-item reveal reveal-delay-2">
          <div class="timeline-dot" style="border-color:var(--gold)"></div>
          <div class="timeline-card">
            <div class="timeline-year" style="color:var(--gold)">Currently Enrolled</div>
            <div class="timeline-degree">Program at NIELIT Ropar</div>
            <div class="timeline-school">National Institute of Electronics &amp; Information Technology, Ropar</div>
            <div class="timeline-desc">
              Currently pursuing my studies at NIELIT Ropar — a premier government institute under the Ministry of Electronics &amp; IT. I'm gaining hands-on knowledge in technology, computers, and digital skills that are shaping my professional foundation.
            </div>
            <span class="timeline-badge badge-ongoing"><i class="fas fa-circle-notch fa-spin" style="margin-right:6px"></i>In Progress</span>
          </div>
        </div>

        <div class="timeline-item reveal reveal-delay-3">
          <div class="timeline-dot" style="border-color:var(--blue)"></div>
          <div class="timeline-card" style="border-color:rgba(79,142,245,.2)">
            <div class="timeline-year" style="color:var(--blue)">Future Goal</div>
            <div class="timeline-degree">Higher Education &amp; Continuous Learning</div>
            <div class="timeline-school">The Journey Continues…</div>
            <div class="timeline-desc">
              My aspirations reach far beyond today. I plan to pursue higher education, explore advanced technologies, and keep expanding my knowledge horizon — because true learning never ends.
            </div>
            <span class="timeline-badge badge-future"><i class="fas fa-rocket" style="margin-right:6px"></i>Future Aspiration</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== SKILLS ========== -->
  <section id="skills">
    <p class="section-label reveal">Skills</p>
    <h2 class="section-title reveal reveal-delay-1">What I <em>bring</em> to the table</h2>
    <p class="section-desc reveal reveal-delay-2">My strongest assets are not just technical — they're the core qualities that make me a reliable, driven, and capable individual.</p>

    <div class="skills-grid">
      <div class="skill-card reveal reveal-delay-1">
        <div class="skill-icon si-gold"><i class="fas fa-brain"></i></div>
        <div class="skill-name">Problem Solving</div>
        <div class="skill-desc">I approach every challenge with a calm, analytical mindset — breaking down complex problems into manageable, logical steps.</div>
        <div class="skill-bar-wrap"><div class="skill-bar bar-gold" data-width="88"></div></div>
        <div class="skill-pct">88%</div>
      </div>

      <div class="skill-card reveal reveal-delay-2">
        <div class="skill-icon si-teal"><i class="fas fa-bolt"></i></div>
        <div class="skill-name">Quick Learning</div>
        <div class="skill-desc">I absorb new concepts rapidly, whether it's a technical skill, a new subject, or a fresh perspective on life.</div>
        <div class="skill-bar-wrap"><div class="skill-bar bar-teal" data-width="92"></div></div>
        <div class="skill-pct">92%</div>
      </div>

      <div class="skill-card reveal reveal-delay-3">
        <div class="skill-icon si-blue"><i class="fas fa-desktop"></i></div>
        <div class="skill-name">Computer Fundamentals</div>
        <div class="skill-desc">Solid foundation in computer basics — hardware, software, operating systems, and digital tools used in modern environments.</div>
        <div class="skill-bar-wrap"><div class="skill-bar bar-blue" data-width="82"></div></div>
        <div class="skill-pct">82%</div>
      </div>

      <div class="skill-card reveal reveal-delay-4">
        <div class="skill-icon si-pink"><i class="fas fa-comments"></i></div>
        <div class="skill-name">Communication</div>
        <div class="skill-desc">Clear, respectful, and confident communication — whether speaking with peers, educators, or in team collaborations.</div>
        <div class="skill-bar-wrap"><div class="skill-bar bar-pink" data-width="80"></div></div>
        <div class="skill-pct">80%</div>
      </div>

      <div class="skill-card reveal reveal-delay-5">
        <div class="skill-icon si-green"><i class="fas fa-fire"></i></div>
        <div class="skill-name">Dedication to Studies</div>
        <div class="skill-desc">My single greatest strength. I show up every day, give my best effort, and maintain the discipline needed to achieve long-term goals.</div>
        <div class="skill-bar-wrap"><div class="skill-bar bar-green" data-width="96"></div></div>
        <div class="skill-pct">96%</div>
      </div>
    </div>
  </section>

  <!-- ========== GOALS ========== -->
  <section id="goals">
    <p class="section-label reveal">Goals &amp; Aspirations</p>
    <h2 class="section-title reveal reveal-delay-1">Where I'm <em>headed</em></h2>
    <p class="section-desc reveal reveal-delay-2">Every great journey starts with a clear destination. Here's what I'm working toward, every single day.</p>

    <div class="goals-grid">
      <div class="goal-card reveal reveal-delay-1">
        <div class="goal-icon"><i class="fas fa-university" style="color:var(--gold)"></i></div>
        <div class="goal-title">Higher Education</div>
        <div class="goal-text">Pursue advanced academic qualifications and earn degrees that open doors to remarkable opportunities.</div>
      </div>

      <div class="goal-card reveal reveal-delay-2">
        <div class="goal-icon"><i class="fas fa-microchip" style="color:var(--teal)"></i></div>
        <div class="goal-title">Advanced Technologies</div>
        <div class="goal-text">Master cutting-edge technologies — from AI and data science to cybersecurity and software development.</div>
      </div>

      <div class="goal-card reveal reveal-delay-3">
        <div class="goal-icon"><i class="fas fa-briefcase" style="color:var(--blue)"></i></div>
        <div class="goal-title">Successful Career</div>
        <div class="goal-text">Build a fulfilling career that makes a real difference, grounded in expertise, integrity, and continuous improvement.</div>
      </div>

      <div class="goal-card reveal reveal-delay-4">
        <div class="goal-icon"><i class="fas fa-infinity" style="color:#e86b82"></i></div>
        <div class="goal-title">Never Stop Learning</div>
        <div class="goal-text">Keep curiosity alive at every stage of life — because the moment you stop learning is the moment you stop growing.</div>
      </div>
    </div>
  </section>

  <!-- ========== QUOTES ========== -->
  <section id="quotes">
    <div class="quotes-bg"></div>
    <div class="quotes-inner">
      <p class="section-label" style="justify-content:center">Inspiration</p>
      <h2 class="section-title reveal" style="text-align:center">Words that <em>fuel</em> me</h2>

      <div class="quote-carousel" style="margin-top:48px">
        <div class="quote-slide active">
          <div class="quote-mark">"</div>
          <div class="quote-text">Education is the most powerful weapon which you can use to change the world.</div>
          <div class="quote-author">— Nelson Mandela</div>
        </div>
        <div class="quote-slide">
          <div class="quote-mark">"</div>
          <div class="quote-text">The roots of education are bitter, but the fruit is sweet.</div>
          <div class="quote-author">— Aristotle</div>
        </div>
        <div class="quote-slide">
          <div class="quote-mark">"</div>
          <div class="quote-text">Live as if you were to die tomorrow. Learn as if you were to live forever.</div>
          <div class="quote-author">— Mahatma Gandhi</div>
        </div>
        <div class="quote-slide">
          <div class="quote-mark">"</div>
          <div class="quote-text">The beautiful thing about learning is that no one can take it away from you.</div>
          <div class="quote-author">— B.B. King</div>
        </div>
        <div class="quote-slide">
          <div class="quote-mark">"</div>
          <div class="quote-text">An investment in knowledge pays the best interest.</div>
          <div class="quote-author">— Benjamin Franklin</div>
        </div>
      </div>

      <div class="quote-dots" id="quoteDots"></div>
    </div>
  </section>

  <!-- ========== CONTACT ========== -->
  <section id="contact">
    <p class="section-label reveal">Contact</p>
    <h2 class="section-title reveal reveal-delay-1">Let's <em>connect</em></h2>
    <p class="section-desc reveal reveal-delay-2">Whether you want to collaborate, share ideas, or simply say hello — I'd love to hear from you.</p>

    <div class="contact-wrap">
      <div class="contact-card reveal reveal-delay-3">
        <div class="contact-avatar">MS</div>
        <div class="contact-name">Mansirat Singh</div>
        <div class="contact-role">Student at NIELIT Ropar · Lifelong Learner</div>

        <div class="contact-links">
          <a href="mailto:mansiratsingh55@gmail.com" class="contact-link">
            <div class="cl-icon cl-gold"><i class="fas fa-envelope"></i></div>
            <div class="cl-text">
              <div class="cl-label">Email</div>
              <div class="cl-value">mansiratsingh55@gmail.com</div>
            </div>
            <i class="fas fa-arrow-right" style="margin-left:auto;color:var(--muted);font-size:.8rem"></i>
          </a>

          <a href="#" class="contact-link" style="cursor:default" onclick="return false">
            <div class="cl-icon" style="background:rgba(61,232,200,.12);color:var(--teal)"><i class="fas fa-map-marker-alt"></i></div>
            <div class="cl-text">
              <div class="cl-label">Location</div>
              <div class="cl-value">Punjab, India</div>
            </div>
          </a>

          <a href="#" class="contact-link" style="cursor:default" onclick="return false">
            <div class="cl-icon" style="background:rgba(79,142,245,.12);color:var(--blue)"><i class="fas fa-graduation-cap"></i></div>
            <div class="cl-text">
              <div class="cl-label">Institution</div>
              <div class="cl-value">NIELIT Ropar</div>
            </div>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== FOOTER ========== -->
  <footer>
    <div class="footer-logo">Mansirat Singh</div>
    <div class="footer-copy">
      Made with <span class="footer-heart">♥</span> &amp; a lot of ambition · 2024
    </div>
  </footer>

  <!-- ============================================================
       JAVASCRIPT
  ============================================================ -->
  <script>
    /* ---- Loader ---- */
    window.addEventListener('load', () => {
      setTimeout(() => {
        document.getElementById('loader').classList.add('hidden');
      }, 2000);
    });

    /* ---- Cursor glow ---- */
    const glow = document.getElementById('cursorGlow');
    document.addEventListener('mousemove', e => {
      glow.style.left = e.clientX + 'px';
      glow.style.top  = e.clientY + 'px';
    });

    /* ---- Navbar scroll ---- */
    const navbar = document.getElementById('navbar');
    window.addEventListener('scroll', () => {
      navbar.classList.toggle('scrolled', window.scrollY > 60);
    });

    /* ---- Mobile nav toggle ---- */
    const navToggle = document.getElementById('navToggle');
    const navLinks  = document.getElementById('navLinks');
    navToggle.addEventListener('click', () => {
      navLinks.classList.toggle('open');
    });
    navLinks.querySelectorAll('a').forEach(a => {
      a.addEventListener('click', () => navLinks.classList.remove('open'));
    });

    /* ---- Particles canvas ---- */
    (function () {
      const canvas = document.getElementById('particles-canvas');
      const ctx = canvas.getContext('2d');
      let W, H, particles = [];

      function resize() {
        W = canvas.width  = canvas.offsetWidth;
        H = canvas.height = canvas.offsetHeight;
      }
      resize();
      window.addEventListener('resize', resize);

      class Particle {
        constructor() { this.reset(); }
        reset() {
          this.x = Math.random() * W;
          this.y = Math.random() * H;
          this.r = Math.random() * 1.8 + .4;
          this.vx = (Math.random() - .5) * .3;
          this.vy = (Math.random() - .5) * .3;
          this.alpha = Math.random() * .5 + .1;
          this.color = Math.random() > .5 ? '232,185,79' : '61,232,200';
        }
        update() {
          this.x += this.vx;
          this.y += this.vy;
          if (this.x < 0 || this.x > W || this.y < 0 || this.y > H) this.reset();
        }
        draw() {
          ctx.beginPath();
          ctx.arc(this.x, this.y, this.r, 0, Math.PI * 2);
          ctx.fillStyle = `rgba(${this.color},${this.alpha})`;
          ctx.fill();
        }
      }

      for (let i = 0; i < 90; i++) particles.push(new Particle());

      function loop() {
        ctx.clearRect(0, 0, W, H);
        // draw connections
        for (let i = 0; i < particles.length; i++) {
          for (let j = i + 1; j < particles.length; j++) {
            const dx = particles[i].x - particles[j].x;
            const dy = particles[i].y - particles[j].y;
            const dist = Math.sqrt(dx*dx + dy*dy);
            if (dist < 100) {
              ctx.beginPath();
              ctx.moveTo(particles[i].x, particles[i].y);
              ctx.lineTo(particles[j].x, particles[j].y);
              ctx.strokeStyle = `rgba(232,185,79,${.06 * (1 - dist/100)})`;
              ctx.lineWidth = .6;
              ctx.stroke();
            }
          }
        }
        particles.forEach(p => { p.update(); p.draw(); });
        requestAnimationFrame(loop);
      }
      loop();
    })();

    /* ---- Scroll Reveal ---- */
    const reveals = document.querySelectorAll('.reveal');
    const revealObs = new IntersectionObserver((entries) => {
      entries.forEach(e => {
        if (e.isIntersecting) e.target.classList.add('visible');
      });
    }, { threshold: .12 });
    reveals.forEach(el => revealObs.observe(el));

    /* ---- Animated counters ---- */
    const counters = document.querySelectorAll('[data-count]');
    const counterObs = new IntersectionObserver((entries) => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          const el = e.target;
          const target = parseInt(el.dataset.count);
          const suffix = el.querySelector('span') ? el.querySelector('span').outerHTML : '';
          const innerText = el.innerText;
          let start = 0;
          const duration = 1800;
          const step = timestamp => {
            if (!start) start = timestamp;
            const progress = Math.min((timestamp - start) / duration, 1);
            const eased = 1 - Math.pow(1 - progress, 3);
            el.innerHTML = Math.floor(eased * target) + suffix;
            if (progress < 1) requestAnimationFrame(step);
          };
          requestAnimationFrame(step);
          counterObs.unobserve(el);
        }
      });
    }, { threshold: .5 });
    counters.forEach(el => counterObs.observe(el));

    /* ---- Skill bar animation ---- */
    const bars = document.querySelectorAll('.skill-bar');
    const barObs = new IntersectionObserver((entries) => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          e.target.style.width = e.target.dataset.width + '%';
          barObs.unobserve(e.target);
        }
      });
    }, { threshold: .3 });
    bars.forEach(b => barObs.observe(b));

    /* ---- Quote carousel ---- */
    const slides = document.querySelectorAll('.quote-slide');
    const dotsEl = document.getElementById('quoteDots');
    let currentQuote = 0;
    let quoteTimer;

    slides.forEach((_, i) => {
      const d = document.createElement('div');
      d.className = 'qdot' + (i === 0 ? ' active' : '');
      d.addEventListener('click', () => goToQuote(i));
      dotsEl.appendChild(d);
    });

    function goToQuote(n) {
      slides[currentQuote].classList.remove('active');
      dotsEl.children[currentQuote].classList.remove('active');
      currentQuote = (n + slides.length) % slides.length;
      slides[currentQuote].classList.add('active');
      dotsEl.children[currentQuote].classList.add('active');
    }

    function nextQuote() { goToQuote(currentQuote + 1); }
    quoteTimer = setInterval(nextQuote, 4500);
  </script>
</body>
</html>
