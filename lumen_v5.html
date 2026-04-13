<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lumen — The AI Exam Coach</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&family=Literata:ital,wght@0,300;0,400;0,500;1,300;1,400&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --ink: #0d0f0e;
    --ink-2: #2a2d2b;
    --ink-3: #5a5f5c;
    --ink-4: #9aa09c;
    --paper: #f7f5f0;
    --paper-2: #eeeae2;
    --paper-3: #e4dfd4;
    --gold: #c8922a;
    --gold-light: #f5e9d0;
    --gold-dark: #8a610f;
    --emerald: #1a6644;
    --emerald-light: #d1ead9;
    --crimson: #8b1a1a;
    --crimson-light: #f5dada;
    --sapphire: #1a3a6b;
    --sapphire-light: #dce6f5;
    --border: rgba(13,15,14,0.12);
    --border-strong: rgba(13,15,14,0.22);
    --radius: 4px;
    --radius-lg: 8px;
    --radius-xl: 16px;
  }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'Literata', Georgia, serif;
    background: var(--paper);
    color: var(--ink);
    font-size: 17px;
    line-height: 1.7;
    overflow-x: hidden;
  }

  .mono { font-family: 'JetBrains Mono', monospace; }
  .display { font-family: 'Syne', sans-serif; }

  /* NAV */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    background: rgba(247,245,240,0.94);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 48px;
    height: 64px;
  }
  .nav-logo {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 22px;
    color: var(--ink);
    letter-spacing: -0.5px;
    text-decoration: none;
  }
  .nav-logo span { color: var(--gold); }
  .nav-links {
    display: flex;
    align-items: center;
    gap: 32px;
    list-style: none;
  }
  .nav-links a {
    font-family: 'Syne', sans-serif;
    font-size: 14px;
    font-weight: 500;
    color: var(--ink-3);
    text-decoration: none;
    letter-spacing: 0.02em;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--ink); }
  .nav-cta {
    font-family: 'Syne', sans-serif;
    font-size: 14px;
    font-weight: 600;
    background: var(--ink);
    color: var(--paper);
    border: none;
    padding: 10px 22px;
    border-radius: var(--radius);
    cursor: pointer;
    text-decoration: none;
    transition: background 0.2s, transform 0.1s;
    letter-spacing: 0.02em;
  }
  .nav-cta:hover { background: var(--ink-2); transform: translateY(-1px); }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 120px 48px 80px;
    position: relative;
    overflow: hidden;
  }
  .hero-grid {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(var(--border) 1px, transparent 1px),
      linear-gradient(90deg, var(--border) 1px, transparent 1px);
    background-size: 60px 60px;
    opacity: 0.5;
    pointer-events: none;
  }
  .hero-tag {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    background: var(--gold-light);
    color: var(--gold-dark);
    border: 1px solid rgba(200,146,42,0.3);
    padding: 6px 14px;
    border-radius: 100px;
    margin-bottom: 28px;
    width: fit-content;
  }
  .hero-tag::before {
    content: '';
    width: 6px; height: 6px;
    border-radius: 50%;
    background: var(--gold);
    animation: pulse 2s infinite;
  }
  @keyframes pulse {
    0%, 100% { opacity: 1; transform: scale(1); }
    50% { opacity: 0.5; transform: scale(0.8); }
  }
  .hero h1 {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: clamp(44px, 7vw, 92px);
    line-height: 0.95;
    letter-spacing: -2px;
    color: var(--ink);
    max-width: 900px;
    margin-bottom: 28px;
  }
  .hero h1 em {
    font-style: italic;
    font-family: 'Literata', serif;
    font-weight: 400;
    color: var(--gold);
  }
  .hero-sub {
    font-size: 20px;
    color: var(--ink-3);
    max-width: 560px;
    line-height: 1.6;
    margin-bottom: 44px;
  }
  .hero-actions {
    display: flex;
    align-items: center;
    gap: 16px;
    flex-wrap: wrap;
    margin-bottom: 64px;
  }
  .btn-primary {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 600;
    background: var(--ink);
    color: var(--paper);
    border: none;
    padding: 16px 36px;
    border-radius: var(--radius);
    cursor: pointer;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 10px;
    transition: all 0.2s;
    letter-spacing: 0.01em;
  }
  .btn-primary:hover { background: var(--ink-2); transform: translateY(-2px); box-shadow: 0 8px 24px rgba(13,15,14,0.18); }
  .btn-secondary {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 500;
    background: transparent;
    color: var(--ink);
    border: 1px solid var(--border-strong);
    padding: 16px 36px;
    border-radius: var(--radius);
    cursor: pointer;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 10px;
    transition: all 0.2s;
  }
  .btn-secondary:hover { background: var(--paper-2); transform: translateY(-2px); }
  .hero-stats {
    display: flex;
    align-items: center;
    gap: 48px;
    flex-wrap: wrap;
  }
  .hero-stat {
    display: flex;
    flex-direction: column;
  }
  .hero-stat-num {
    font-family: 'Syne', sans-serif;
    font-size: 28px;
    font-weight: 800;
    color: var(--ink);
    line-height: 1;
  }
  .hero-stat-label {
    font-size: 13px;
    color: var(--ink-4);
    margin-top: 4px;
  }
  .hero-divider {
    width: 1px;
    height: 40px;
    background: var(--border-strong);
  }

  /* MARQUEE */
  .marquee-section {
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    background: var(--paper-2);
    padding: 18px 0;
    overflow: hidden;
  }
  .marquee-track {
    display: flex;
    gap: 0;
    animation: marquee 28s linear infinite;
    width: max-content;
  }
  .marquee-track:hover { animation-play-state: paused; }
  @keyframes marquee {
    from { transform: translateX(0); }
    to { transform: translateX(-50%); }
  }
  .marquee-item {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 0 36px;
    font-family: 'Syne', sans-serif;
    font-size: 13px;
    font-weight: 600;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    color: var(--ink-3);
    white-space: nowrap;
  }
  .marquee-dot {
    width: 5px; height: 5px;
    border-radius: 50%;
    background: var(--gold);
    flex-shrink: 0;
  }

  /* SECTIONS */
  section { padding: 100px 48px; }
  .container { max-width: 1160px; margin: 0 auto; }
  .section-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    font-weight: 500;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 16px;
  }
  .section-title {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: clamp(32px, 4vw, 52px);
    line-height: 1.05;
    letter-spacing: -1px;
    color: var(--ink);
    margin-bottom: 20px;
  }
  .section-title em {
    font-style: italic;
    font-family: 'Literata', serif;
    font-weight: 400;
  }
  .section-body {
    font-size: 18px;
    color: var(--ink-3);
    max-width: 540px;
    line-height: 1.65;
  }

  /* PROBLEM SECTION */
  .problem-section {
    background: var(--ink);
    color: var(--paper);
  }
  .problem-section .section-label { color: var(--gold); }
  .problem-section .section-title { color: var(--paper); }
  .problem-section .section-body { color: rgba(247,245,240,0.6); }
  .problem-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1px;
    background: rgba(247,245,240,0.1);
    border: 1px solid rgba(247,245,240,0.1);
    border-radius: var(--radius-lg);
    overflow: hidden;
    margin-top: 60px;
  }
  .problem-item {
    background: var(--ink-2);
    padding: 36px 40px;
    display: flex;
    gap: 20px;
    align-items: flex-start;
    transition: background 0.2s;
  }
  .problem-item:hover { background: #353836; }
  .problem-num {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--gold);
    opacity: 0.8;
    padding-top: 3px;
    flex-shrink: 0;
  }
  .problem-text h3 {
    font-family: 'Syne', sans-serif;
    font-size: 17px;
    font-weight: 600;
    color: var(--paper);
    margin-bottom: 6px;
  }
  .problem-text p {
    font-size: 14px;
    color: rgba(247,245,240,0.55);
    line-height: 1.55;
  }

  /* FEATURES */
  .features-section { background: var(--paper); }
  .features-header {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: end;
    margin-bottom: 72px;
  }
  .feature-cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1px;
    background: var(--border);
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    overflow: hidden;
  }
  .feature-card {
    background: var(--paper);
    padding: 36px 32px;
    transition: background 0.2s;
    cursor: default;
  }
  .feature-card:hover { background: var(--paper-2); }
  .feature-card.featured { background: var(--gold-light); }
  .feature-card.featured:hover { background: #f0e0bc; }
  .feature-icon {
    width: 40px; height: 40px;
    border-radius: var(--radius);
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
    font-size: 18px;
  }
  .feature-card h3 {
    font-family: 'Syne', sans-serif;
    font-size: 17px;
    font-weight: 700;
    color: var(--ink);
    margin-bottom: 10px;
    letter-spacing: -0.2px;
  }
  .feature-card p {
    font-size: 14px;
    color: var(--ink-3);
    line-height: 1.6;
  }
  .feature-tag {
    display: inline-block;
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    font-weight: 500;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    background: var(--gold);
    color: var(--paper);
    padding: 3px 8px;
    border-radius: 3px;
    margin-top: 12px;
  }

  /* HOW IT WORKS */
  .how-section { background: var(--paper-2); }
  .how-steps {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 32px;
    margin-top: 64px;
    position: relative;
  }
  .how-steps::after {
    content: '';
    position: absolute;
    top: 24px;
    left: 60px;
    right: 60px;
    height: 1px;
    background: linear-gradient(90deg, transparent, var(--border-strong), var(--border-strong), transparent);
  }
  .how-step {
    display: flex;
    flex-direction: column;
    gap: 16px;
    position: relative;
    z-index: 1;
  }
  .how-step-num {
    width: 48px; height: 48px;
    border-radius: 50%;
    background: var(--paper);
    border: 1px solid var(--border-strong);
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 700;
    color: var(--ink);
  }
  .how-step h3 {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 700;
    color: var(--ink);
  }
  .how-step p {
    font-size: 14px;
    color: var(--ink-3);
    line-height: 1.6;
  }

  /* DASHBOARD PREVIEW */
  .dashboard-section { background: var(--ink); padding: 100px 48px; }
  .dashboard-section .section-label { color: var(--gold); }
  .dashboard-section .section-title { color: var(--paper); }
  .dashboard-section .section-body { color: rgba(247,245,240,0.6); }
  .dash-preview {
    margin-top: 56px;
    border-radius: var(--radius-xl);
    overflow: hidden;
    border: 1px solid rgba(247,245,240,0.12);
    background: #141716;
  }
  .dash-topbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 14px 24px;
    border-bottom: 1px solid rgba(247,245,240,0.08);
    background: #1a1d1b;
  }
  .dash-dots { display: flex; gap: 7px; }
  .dash-dot { width: 11px; height: 11px; border-radius: 50%; }
  .dash-title {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    color: rgba(247,245,240,0.4);
  }
  .dash-body {
    display: grid;
    grid-template-columns: 220px 1fr;
    min-height: 420px;
  }
  .dash-sidebar {
    border-right: 1px solid rgba(247,245,240,0.08);
    padding: 24px 0;
  }
  .dash-sidebar-item {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 10px 20px;
    font-family: 'Syne', sans-serif;
    font-size: 13px;
    font-weight: 500;
    color: rgba(247,245,240,0.45);
    cursor: pointer;
    transition: all 0.15s;
    border-left: 2px solid transparent;
  }
  .dash-sidebar-item.active {
    color: var(--paper);
    background: rgba(247,245,240,0.05);
    border-left-color: var(--gold);
  }
  .dash-sidebar-icon { font-size: 15px; }
  .dash-main { padding: 24px; display: flex; flex-direction: column; gap: 20px; }
  .dash-greeting {
    font-family: 'Syne', sans-serif;
    font-size: 18px;
    font-weight: 700;
    color: var(--paper);
  }
  .dash-greeting span { color: var(--gold); }
  .dash-cards {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 12px;
  }
  .dash-card {
    background: rgba(247,245,240,0.05);
    border: 1px solid rgba(247,245,240,0.08);
    border-radius: var(--radius-lg);
    padding: 16px;
  }
  .dash-card-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    color: rgba(247,245,240,0.4);
    margin-bottom: 8px;
  }
  .dash-card-value {
    font-family: 'Syne', sans-serif;
    font-size: 26px;
    font-weight: 800;
    color: var(--paper);
    line-height: 1;
  }
  .dash-card-sub {
    font-size: 12px;
    color: rgba(247,245,240,0.4);
    margin-top: 4px;
  }
  .dash-card-value.green { color: #5bce8a; }
  .dash-card-value.gold { color: var(--gold); }
  .dash-card-value.blue { color: #5ba8e8; }
  .dash-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }
  .dash-topic-list {
    background: rgba(247,245,240,0.05);
    border: 1px solid rgba(247,245,240,0.08);
    border-radius: var(--radius-lg);
    padding: 16px;
  }
  .dash-topic-title {
    font-family: 'Syne', sans-serif;
    font-size: 13px;
    font-weight: 600;
    color: var(--paper);
    margin-bottom: 14px;
  }
  .dash-topic-item {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 8px 0;
    border-bottom: 1px solid rgba(247,245,240,0.06);
  }
  .dash-topic-item:last-child { border-bottom: none; }
  .dash-topic-name { font-size: 13px; color: rgba(247,245,240,0.7); }
  .dash-topic-bar-wrap {
    display: flex;
    align-items: center;
    gap: 8px;
    flex: 1;
    margin: 0 12px;
  }
  .dash-topic-bar {
    flex: 1;
    height: 4px;
    background: rgba(247,245,240,0.1);
    border-radius: 2px;
    overflow: hidden;
  }
  .dash-topic-fill {
    height: 100%;
    border-radius: 2px;
    background: var(--gold);
    transition: width 0.6s ease;
  }
  .dash-topic-fill.weak { background: #e05858; }
  .dash-topic-fill.ok { background: #5bce8a; }
  .dash-topic-pct { font-family: 'JetBrains Mono', monospace; font-size: 11px; color: rgba(247,245,240,0.4); }
  .dash-schedule {
    background: rgba(247,245,240,0.05);
    border: 1px solid rgba(247,245,240,0.08);
    border-radius: var(--radius-lg);
    padding: 16px;
  }
  .dash-schedule-item {
    display: flex;
    align-items: center;
    gap: 12px;
    padding: 10px 0;
    border-bottom: 1px solid rgba(247,245,240,0.06);
  }
  .dash-schedule-item:last-child { border-bottom: none; }
  .dash-sched-time {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--gold);
    width: 45px;
    flex-shrink: 0;
  }
  .dash-sched-subject {
    font-size: 13px;
    color: rgba(247,245,240,0.8);
    flex: 1;
  }
  .dash-sched-badge {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    padding: 2px 7px;
    border-radius: 3px;
    letter-spacing: 0.04em;
  }
  .badge-revision { background: rgba(91,168,232,0.15); color: #5ba8e8; }
  .badge-exam { background: rgba(224,88,88,0.15); color: #e05858; }
  .badge-practice { background: rgba(200,146,42,0.15); color: var(--gold); }

  /* CURRICULA */
  .curricula-section { background: var(--paper); }
  .curricula-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 1px;
    background: var(--border);
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    overflow: hidden;
    margin-top: 56px;
  }
  .curricula-card {
    background: var(--paper);
    padding: 36px 24px;
    text-align: center;
    transition: background 0.2s;
    cursor: default;
  }
  .curricula-card:hover { background: var(--paper-2); }
  .curricula-abbr {
    font-family: 'Syne', sans-serif;
    font-size: 28px;
    font-weight: 800;
    color: var(--ink);
    margin-bottom: 6px;
  }
  .curricula-full {
    font-size: 12px;
    color: var(--ink-4);
    line-height: 1.4;
  }
  .curricula-subjects {
    display: flex;
    flex-wrap: wrap;
    gap: 4px;
    justify-content: center;
    margin-top: 14px;
  }
  .curricula-subject {
    font-family: 'JetBrains Mono', monospace;
    font-size: 9px;
    background: var(--paper-3);
    color: var(--ink-3);
    padding: 3px 6px;
    border-radius: 3px;
    letter-spacing: 0.04em;
  }

  /* PRICING */
  .pricing-section { background: var(--paper-2); }
  .pricing-header { text-align: center; margin-bottom: 60px; }
  .pricing-header .section-label { display: block; text-align: center; }
  .pricing-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    max-width: 960px;
    margin: 0 auto;
  }
  .pricing-card {
    background: var(--paper);
    border: 1px solid var(--border);
    border-radius: var(--radius-xl);
    padding: 36px 32px;
    position: relative;
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .pricing-card:hover { transform: translateY(-4px); box-shadow: 0 16px 48px rgba(13,15,14,0.1); }
  .pricing-card.recommended {
    background: var(--ink);
    border-color: transparent;
    color: var(--paper);
  }
  .pricing-badge {
    position: absolute;
    top: -12px;
    left: 50%;
    transform: translateX(-50%);
    font-family: 'Syne', sans-serif;
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    background: var(--gold);
    color: var(--paper);
    padding: 4px 14px;
    border-radius: 100px;
    white-space: nowrap;
  }
  .pricing-tier {
    font-family: 'Syne', sans-serif;
    font-size: 14px;
    font-weight: 600;
    letter-spacing: 0.04em;
    text-transform: uppercase;
    color: var(--ink-3);
    margin-bottom: 16px;
  }
  .pricing-card.recommended .pricing-tier { color: rgba(247,245,240,0.6); }
  .pricing-price {
    display: flex;
    align-items: baseline;
    gap: 4px;
    margin-bottom: 8px;
  }
  .price-currency {
    font-family: 'Syne', sans-serif;
    font-size: 22px;
    font-weight: 600;
    color: var(--ink-3);
  }
  .pricing-card.recommended .price-currency { color: rgba(247,245,240,0.6); }
  .price-amount {
    font-family: 'Syne', sans-serif;
    font-size: 56px;
    font-weight: 800;
    line-height: 1;
    color: var(--ink);
    letter-spacing: -2px;
  }
  .pricing-card.recommended .price-amount { color: var(--paper); }
  .price-period {
    font-size: 14px;
    color: var(--ink-4);
  }
  .pricing-card.recommended .price-period { color: rgba(247,245,240,0.45); }
  .pricing-desc {
    font-size: 14px;
    color: var(--ink-3);
    margin-bottom: 28px;
    line-height: 1.5;
  }
  .pricing-card.recommended .pricing-desc { color: rgba(247,245,240,0.6); }
  .pricing-divider {
    height: 1px;
    background: var(--border);
    margin-bottom: 24px;
  }
  .pricing-card.recommended .pricing-divider { background: rgba(247,245,240,0.12); }
  .pricing-features {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 12px;
    margin-bottom: 32px;
  }
  .pricing-feature {
    display: flex;
    align-items: flex-start;
    gap: 10px;
    font-size: 14px;
    color: var(--ink-2);
    line-height: 1.4;
  }
  .pricing-card.recommended .pricing-feature { color: rgba(247,245,240,0.8); }
  .pricing-check {
    width: 16px; height: 16px;
    border-radius: 50%;
    background: var(--emerald-light);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    margin-top: 1px;
    font-size: 10px;
    color: var(--emerald);
  }
  .pricing-card.recommended .pricing-check { background: rgba(91,206,138,0.2); color: #5bce8a; }
  .pricing-btn {
    display: block;
    width: 100%;
    font-family: 'Syne', sans-serif;
    font-size: 15px;
    font-weight: 600;
    text-align: center;
    padding: 14px;
    border-radius: var(--radius);
    border: 1px solid var(--border-strong);
    background: transparent;
    color: var(--ink);
    cursor: pointer;
    text-decoration: none;
    transition: all 0.2s;
  }
  .pricing-btn:hover { background: var(--paper-2); transform: translateY(-1px); }
  .pricing-card.recommended .pricing-btn {
    background: var(--gold);
    border-color: var(--gold);
    color: var(--paper);
  }
  .pricing-card.recommended .pricing-btn:hover { background: var(--gold-dark); border-color: var(--gold-dark); }
  .pricing-note {
    text-align: center;
    margin-top: 28px;
    font-size: 13px;
    color: var(--ink-4);
  }

  

  /* FAQ */
  .faq-section { background: var(--paper-2); }
  .faq-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 16px;
    margin-top: 56px;
  }
  .faq-item {
    background: var(--paper);
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    padding: 24px 28px;
    cursor: pointer;
  }
  .faq-q {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 600;
    color: var(--ink);
    margin-bottom: 10px;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 12px;
  }
  .faq-toggle {
    font-size: 20px;
    color: var(--ink-3);
    line-height: 1;
    flex-shrink: 0;
    font-weight: 300;
    font-family: 'Syne', sans-serif;
    user-select: none;
  }
  .faq-a {
    font-size: 14px;
    color: var(--ink-3);
    line-height: 1.65;
    display: none;
  }
  .faq-item.open .faq-a { display: block; }
  .faq-item.open .faq-toggle { transform: rotate(45deg); }

  /* CTA */
  .cta-section {
    background: var(--ink);
    padding: 120px 48px;
    text-align: center;
    position: relative;
    overflow: hidden;
  }
  .cta-section::before {
    content: '';
    position: absolute;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    width: 600px; height: 600px;
    border-radius: 50%;
    border: 1px solid rgba(200,146,42,0.1);
  }
  .cta-section::after {
    content: '';
    position: absolute;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    width: 900px; height: 900px;
    border-radius: 50%;
    border: 1px solid rgba(200,146,42,0.06);
  }
  .cta-section > * { position: relative; z-index: 1; }
  .cta-section .section-label { display: block; text-align: center; color: var(--gold); margin-bottom: 20px; }
  .cta-title {
    font-family: 'Syne', sans-serif;
    font-size: clamp(40px, 5vw, 68px);
    font-weight: 800;
    color: var(--paper);
    line-height: 1.0;
    letter-spacing: -1.5px;
    margin-bottom: 20px;
  }
  .cta-title em {
    font-family: 'Literata', serif;
    font-style: italic;
    font-weight: 400;
    color: var(--gold);
  }
  .cta-sub {
    font-size: 18px;
    color: rgba(247,245,240,0.6);
    max-width: 480px;
    margin: 0 auto 44px;
    line-height: 1.6;
  }
  .cta-actions {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 16px;
    flex-wrap: wrap;
  }
  .btn-gold {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 600;
    background: var(--gold);
    color: var(--paper);
    border: none;
    padding: 16px 40px;
    border-radius: var(--radius);
    cursor: pointer;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: 10px;
    transition: all 0.2s;
  }
  .btn-gold:hover { background: var(--gold-dark); transform: translateY(-2px); }
  .btn-ghost {
    font-family: 'Syne', sans-serif;
    font-size: 16px;
    font-weight: 500;
    background: transparent;
    color: rgba(247,245,240,0.7);
    border: 1px solid rgba(247,245,240,0.2);
    padding: 16px 36px;
    border-radius: var(--radius);
    cursor: pointer;
    text-decoration: none;
    transition: all 0.2s;
  }
  .btn-ghost:hover { color: var(--paper); border-color: rgba(247,245,240,0.4); }

  /* FOOTER */
  footer {
    background: #0d0f0e;
    border-top: 1px solid rgba(247,245,240,0.08);
    padding: 64px 48px 40px;
  }
  .footer-top {
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 48px;
    margin-bottom: 56px;
  }
  .footer-brand {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 22px;
    color: var(--paper);
    letter-spacing: -0.5px;
    margin-bottom: 12px;
  }
  .footer-brand span { color: var(--gold); }
  .footer-tagline {
    font-size: 14px;
    color: rgba(247,245,240,0.4);
    line-height: 1.6;
    max-width: 280px;
  }
  .footer-col-title {
    font-family: 'Syne', sans-serif;
    font-size: 13px;
    font-weight: 600;
    letter-spacing: 0.04em;
    text-transform: uppercase;
    color: rgba(247,245,240,0.5);
    margin-bottom: 20px;
  }
  .footer-links { list-style: none; display: flex; flex-direction: column; gap: 10px; }
  .footer-links a {
    font-size: 14px;
    color: rgba(247,245,240,0.5);
    text-decoration: none;
    transition: color 0.2s;
  }
  .footer-links a:hover { color: var(--paper); }
  .footer-bottom {
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-top: 1px solid rgba(247,245,240,0.08);
    padding-top: 28px;
  }
  .footer-copy {
    font-size: 13px;
    color: rgba(247,245,240,0.3);
  }
  .footer-legal {
    display: flex;
    gap: 24px;
  }
  .footer-legal a {
    font-size: 13px;
    color: rgba(247,245,240,0.3);
    text-decoration: none;
    transition: color 0.2s;
  }
  .footer-legal a:hover { color: rgba(247,245,240,0.6); }

  /* MY NOTES EDITOR */
  #mn-editor:empty:before {
    content: attr(data-placeholder);
    color: rgba(247,245,240,0.2);
    font-style: italic;
    pointer-events: none;
  }
  #mn-editor:focus { border-color: rgba(200,146,42,0.3) !important; }
  #mn-editor h3 { font-family: 'Syne', sans-serif; font-size: 15px; font-weight: 700; color: var(--paper); margin: 14px 0 6px; border-bottom: 1px solid rgba(247,245,240,0.1); padding-bottom: 4px; }
  #mn-editor ul { padding-left: 18px; }
  #mn-editor li { margin-bottom: 4px; color: rgba(247,245,240,0.85); font-size: 14px; }
  #mn-editor strong { color: var(--paper); }
  #mn-editor em { color: rgba(247,245,240,0.75); }
  #mn-editor hr { border: none; border-top: 1px solid rgba(247,245,240,0.12); margin: 12px 0; }

  /* ESIM APPLOCK OVERLAY */
  #esim-lockoverlay { position: absolute !important; }
  #fdash-examsim { position: relative; }

  /* ANIMATIONS */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .animate { opacity: 0; animation: fadeUp 0.6s ease forwards; }
  .delay-1 { animation-delay: 0.1s; }
  .delay-2 { animation-delay: 0.2s; }
  .delay-3 { animation-delay: 0.3s; }
  .delay-4 { animation-delay: 0.4s; }

  /* RESPONSIVE */
  @media (max-width: 900px) {
    nav { padding: 0 24px; }
    .nav-links { display: none; }
    section { padding: 72px 24px; }
    .hero { padding: 100px 24px 60px; }
    .hero h1 { font-size: 40px; letter-spacing: -1px; }
    .problem-grid, .features-header, .dash-body { grid-template-columns: 1fr; }
    .feature-cards { grid-template-columns: 1fr; }
    .how-steps { grid-template-columns: 1fr 1fr; }
    .how-steps::after { display: none; }
    .curricula-grid { grid-template-columns: repeat(3, 1fr); }
    .pricing-grid { grid-template-columns: 1fr; max-width: 400px; }
    .faq-grid { grid-template-columns: 1fr; }
    .footer-top { grid-template-columns: 1fr 1fr; }
    .dash-cards { grid-template-columns: 1fr 1fr; }
    .dash-sidebar { display: none; }
    .dash-row { grid-template-columns: 1fr; }
    .hero-divider { display: none; }
    .dashboard-section { padding: 72px 24px; }
    .cta-section { padding: 80px 24px; }
    footer { padding: 48px 24px 32px; }
  }

  /* ===== INTERACTIVE FULL DASHBOARD ===== */
  .full-dashboard { background: #0f1210; border-radius: var(--radius-xl); overflow: hidden; border: 1px solid rgba(247,245,240,0.1); margin-top: 48px; min-height: 620px; display: flex; flex-direction: column; }
  .fdash-topbar { background: #1a1d1b; border-bottom: 1px solid rgba(247,245,240,0.08); padding: 0 20px; height: 48px; display: flex; align-items: center; justify-content: space-between; flex-shrink: 0; }
  .fdash-dots { display: flex; gap: 6px; }
  .fdash-dot { width: 11px; height: 11px; border-radius: 50%; }
  .fdash-title { font-family: 'JetBrains Mono', monospace; font-size: 11px; color: rgba(247,245,240,0.35); }
  .fdash-user { display: flex; align-items: center; gap: 10px; }
  .fdash-avatar { width: 28px; height: 28px; border-radius: 50%; background: var(--gold); display: flex; align-items: center; justify-content: center; font-family: 'Syne', sans-serif; font-size: 11px; font-weight: 700; color: white; }
  .fdash-username { font-family: 'Syne', sans-serif; font-size: 12px; color: rgba(247,245,240,0.5); }
  .fdash-layout { display: flex; flex: 1; min-height: 0; }
  .fdash-sidebar { width: 200px; background: #0f1210; border-right: 1px solid rgba(247,245,240,0.06); padding: 16px 0; flex-shrink: 0; }
  .fdash-nav { display: flex; align-items: center; gap: 10px; padding: 9px 16px; font-family: 'Syne', sans-serif; font-size: 12px; font-weight: 500; color: rgba(247,245,240,0.4); cursor: pointer; border-left: 2px solid transparent; transition: all 0.15s; user-select: none; }
  .fdash-nav:hover { color: rgba(247,245,240,0.75); background: rgba(247,245,240,0.03); }
  .fdash-nav.active { color: var(--paper); background: rgba(247,245,240,0.05); border-left-color: var(--gold); }
  .fdash-nav-icon { font-size: 13px; width: 18px; text-align: center; flex-shrink: 0; }
  .fdash-sep { height: 1px; background: rgba(247,245,240,0.06); margin: 10px 16px; }
  .fdash-content { flex: 1; overflow-y: auto; padding: 20px 24px; }
  .fdash-panel { display: none; }
  .fdash-panel.active { display: block; }

  /* Motiv banner */
  .fdash-motiv { background: linear-gradient(135deg, rgba(200,146,42,0.13), rgba(200,146,42,0.04)); border: 1px solid rgba(200,146,42,0.22); border-radius: var(--radius-lg); padding: 13px 16px; margin-bottom: 16px; display: flex; gap: 10px; }
  .fdash-motiv-icon { font-size: 18px; flex-shrink: 0; }
  .fdash-motiv-label { font-family: 'JetBrains Mono', monospace; font-size: 9px; letter-spacing: 0.1em; text-transform: uppercase; color: var(--gold); margin-bottom: 3px; }
  .fdash-motiv-text { font-family: 'Literata', serif; font-style: italic; font-size: 13px; color: rgba(247,245,240,0.8); line-height: 1.5; }
  .fdash-greeting { font-family: 'Syne', sans-serif; font-size: 16px; font-weight: 700; color: var(--paper); margin-bottom: 16px; }
  .fdash-greeting span { color: var(--gold); }
  .fdash-stats { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; margin-bottom: 16px; }
  .fdash-stat { background: rgba(247,245,240,0.05); border: 1px solid rgba(247,245,240,0.07); border-radius: var(--radius-lg); padding: 13px; }
  .fdash-stat-lbl { font-family: 'JetBrains Mono', monospace; font-size: 9px; letter-spacing: 0.06em; text-transform: uppercase; color: rgba(247,245,240,0.35); margin-bottom: 6px; }
  .fdash-stat-val { font-family: 'Syne', sans-serif; font-size: 22px; font-weight: 800; color: var(--paper); line-height: 1; }
  .fdash-stat-sub { font-size: 11px; color: rgba(247,245,240,0.35); margin-top: 3px; }
  .fdash-stat-val.g { color: #5bce8a; } .fdash-stat-val.au { color: var(--gold); } .fdash-stat-val.bl { color: #5ba8e8; }
  .fdash-row2 { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .fdash-box { background: rgba(247,245,240,0.05); border: 1px solid rgba(247,245,240,0.07); border-radius: var(--radius-lg); padding: 14px; }
  .fdash-box-title { font-family: 'Syne', sans-serif; font-size: 12px; font-weight: 600; color: var(--paper); margin-bottom: 12px; }
  .fdash-topic-row { display: flex; align-items: center; padding: 6px 0; border-bottom: 1px solid rgba(247,245,240,0.05); }
  .fdash-topic-row:last-child { border: none; }
  .fdash-topic-name { font-size: 12px; color: rgba(247,245,240,0.65); width: 130px; flex-shrink: 0; }
  .fdash-bar-wrap { flex: 1; height: 3px; background: rgba(247,245,240,0.08); border-radius: 2px; overflow: hidden; margin: 0 8px; }
  .fdash-bar-fill { height: 100%; border-radius: 2px; }
  .fdash-bar-fill.wk { background: #e05858; } .fdash-bar-fill.md { background: var(--gold); } .fdash-bar-fill.ok { background: #5bce8a; }
  .fdash-pct { font-family: 'JetBrains Mono', monospace; font-size: 10px; color: rgba(247,245,240,0.35); width: 30px; text-align: right; }
  .fdash-sched-row { display: flex; align-items: center; gap: 10px; padding: 8px 0; border-bottom: 1px solid rgba(247,245,240,0.05); }
  .fdash-sched-row:last-child { border: none; }
  .fdash-sched-time { font-family: 'JetBrains Mono', monospace; font-size: 10px; color: var(--gold); width: 40px; flex-shrink: 0; }
  .fdash-sched-task { font-size: 12px; color: rgba(247,245,240,0.75); flex: 1; }
  .fdash-badge { font-family: 'JetBrains Mono', monospace; font-size: 9px; padding: 2px 6px; border-radius: 3px; flex-shrink: 0; }
  .b-rev { background: rgba(91,168,232,0.15); color: #5ba8e8; }
  .b-prac { background: rgba(200,146,42,0.15); color: var(--gold); }
  .b-exam { background: rgba(224,88,88,0.15); color: #e05858; }

  /* Notes panel */
  .notes-panel-title { font-family: 'Syne', sans-serif; font-size: 18px; font-weight: 700; color: var(--paper); margin-bottom: 4px; }
  .notes-panel-sub { font-size: 13px; color: rgba(247,245,240,0.45); margin-bottom: 16px; }
  .notes-filters { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 18px; }
  .notes-filt-btn { font-family: 'Syne', sans-serif; font-size: 11px; font-weight: 600; padding: 5px 12px; border-radius: 100px; border: 1px solid rgba(247,245,240,0.12); background: transparent; color: rgba(247,245,240,0.45); cursor: pointer; transition: all 0.2s; }
  .notes-filt-btn:hover, .notes-filt-btn.on { background: var(--gold); border-color: var(--gold); color: white; }
  .subjects-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; }
  .subj-card { background: rgba(247,245,240,0.04); border: 1px solid rgba(247,245,240,0.07); border-radius: var(--radius-lg); padding: 14px; cursor: pointer; transition: all 0.18s; }
  .subj-card:hover { background: rgba(247,245,240,0.08); border-color: rgba(200,146,42,0.3); transform: translateY(-2px); }
  .subj-curric { font-family: 'JetBrains Mono', monospace; font-size: 9px; letter-spacing: 0.08em; text-transform: uppercase; color: var(--gold); margin-bottom: 4px; }
  .subj-title { font-family: 'Syne', sans-serif; font-size: 14px; font-weight: 700; color: var(--paper); margin-bottom: 5px; }
  .subj-topics { font-size: 11px; color: rgba(247,245,240,0.4); line-height: 1.4; }
  .notes-detail { display: none; }
  .notes-detail.on { display: block; }
  .notes-back-btn { display: inline-flex; align-items: center; gap: 6px; font-family: 'Syne', sans-serif; font-size: 12px; font-weight: 600; color: var(--gold); cursor: pointer; margin-bottom: 16px; border: none; background: transparent; padding: 0; }
  .notes-back-btn:hover { opacity: 0.75; }
  .notes-dtitle { font-family: 'Syne', sans-serif; font-size: 20px; font-weight: 800; color: var(--paper); margin-bottom: 4px; }
  .notes-dsub { font-size: 12px; color: rgba(247,245,240,0.45); margin-bottom: 20px; }
  .notes-section { background: rgba(247,245,240,0.04); border: 1px solid rgba(247,245,240,0.07); border-radius: var(--radius-lg); padding: 16px; margin-bottom: 12px; }
  .notes-sec-title { font-family: 'Syne', sans-serif; font-size: 13px; font-weight: 700; color: var(--gold); margin-bottom: 10px; }
  .notes-section p { font-size: 13px; color: rgba(247,245,240,0.72); line-height: 1.65; margin-bottom: 8px; }
  .notes-section ul { padding-left: 18px; }
  .notes-section li { font-size: 13px; color: rgba(247,245,240,0.72); line-height: 1.7; }
  .notes-formula { font-family: 'JetBrains Mono', monospace; font-size: 12px; background: rgba(200,146,42,0.1); border: 1px solid rgba(200,146,42,0.2); color: var(--gold); padding: 6px 12px; border-radius: var(--radius); display: inline-block; margin: 6px 0; }
  .yt-vids { margin-top: 12px; }
  .yt-vids-label { font-family: 'JetBrains Mono', monospace; font-size: 9px; letter-spacing: 0.08em; text-transform: uppercase; color: rgba(247,245,240,0.3); margin-bottom: 6px; }
  .yt-vid-link { display: inline-flex; align-items: center; gap: 6px; background: rgba(255,0,0,0.08); border: 1px solid rgba(255,80,80,0.18); border-radius: 3px; padding: 5px 10px; font-family: 'Syne', sans-serif; font-size: 11px; font-weight: 600; color: #ff7070; text-decoration: none; transition: all 0.2s; margin: 3px 4px 3px 0; }
  .yt-vid-link:hover { background: rgba(255,0,0,0.16); }
  .yt-vid-link::before { content: '▶'; font-size: 9px; }

  /* Papers panel */
  .papers-panel-title { font-family: 'Syne', sans-serif; font-size: 18px; font-weight: 700; color: var(--paper); margin-bottom: 4px; }
  .papers-panel-sub { font-size: 13px; color: rgba(247,245,240,0.45); margin-bottom: 16px; }
  .papers-tabs { display: flex; gap: 6px; flex-wrap: wrap; margin-bottom: 20px; }
  .papers-tab-btn { font-family: 'Syne', sans-serif; font-size: 12px; font-weight: 600; padding: 6px 14px; border-radius: var(--radius); border: 1px solid rgba(247,245,240,0.1); background: transparent; color: rgba(247,245,240,0.45); cursor: pointer; transition: all 0.2s; }
  .papers-tab-btn:hover, .papers-tab-btn.on { background: rgba(200,146,42,0.15); border-color: rgba(200,146,42,0.35); color: var(--gold); }
  .papers-subject-block { margin-bottom: 28px; }
  .papers-subj-name { font-family: 'Syne', sans-serif; font-size: 14px; font-weight: 700; color: var(--paper); margin-bottom: 10px; padding-bottom: 7px; border-bottom: 1px solid rgba(247,245,240,0.07); }
  .papers-tbl { width: 100%; border-collapse: collapse; }
  .papers-tbl th { font-family: 'JetBrains Mono', monospace; font-size: 9px; letter-spacing: 0.08em; text-transform: uppercase; color: rgba(247,245,240,0.3); padding: 6px 10px; text-align: left; border-bottom: 1px solid rgba(247,245,240,0.05); }
  .papers-tbl td { padding: 8px 10px; border-bottom: 1px solid rgba(247,245,240,0.03); font-size: 12px; color: rgba(247,245,240,0.65); }
  .papers-tbl tr:hover td { background: rgba(247,245,240,0.02); }
  .p-link { display: inline-flex; align-items: center; gap: 4px; font-family: 'Syne', sans-serif; font-size: 11px; font-weight: 600; color: #5ba8e8; text-decoration: none; padding: 3px 8px; border-radius: 3px; border: 1px solid rgba(91,168,232,0.18); background: rgba(91,168,232,0.06); transition: all 0.18s; }
  .p-link:hover { background: rgba(91,168,232,0.14); }
  .ms-link { display: inline-flex; align-items: center; gap: 4px; font-family: 'Syne', sans-serif; font-size: 11px; font-weight: 600; color: #5bce8a; text-decoration: none; padding: 3px 8px; border-radius: 3px; border: 1px solid rgba(91,206,138,0.18); background: rgba(91,206,138,0.06); transition: all 0.18s; }
  .ms-link:hover { background: rgba(91,206,138,0.14); }

  /* Placeholder panels */
  .fdash-placeholder { background: rgba(247,245,240,0.04); border: 1px solid rgba(247,245,240,0.07); border-radius: var(--radius-lg); padding: 36px; text-align: center; }
  .fdash-placeholder-icon { font-size: 32px; margin-bottom: 12px; }
  .fdash-placeholder-title { font-family: 'Syne', sans-serif; font-size: 15px; font-weight: 700; color: var(--paper); margin-bottom: 8px; }
  .fdash-placeholder-body { font-size: 13px; color: rgba(247,245,240,0.45); max-width: 360px; margin: 0 auto 20px; }
  .fdash-placeholder-btn { font-family: 'Syne', sans-serif; font-size: 13px; font-weight: 600; background: var(--gold); color: white; border: none; padding: 10px 24px; border-radius: var(--radius); cursor: pointer; }



  /* ======== SUBJECT LIBRARY ======== */
  .sublib-wrap { padding: 0; background: #0f1210; min-height: 100vh; }
  .sublib-header { padding: 24px 28px 16px; border-bottom: 1px solid rgba(247,245,240,0.07); }
  .sublib-header-top { display: flex; align-items: center; justify-content: space-between; margin-bottom: 12px; }
  .sublib-title { font-family: 'Syne', sans-serif; font-size: 20px; font-weight: 800; color: var(--paper); }
  .sublib-title span { color: var(--gold); }
  .sublib-stats { font-family: 'JetBrains Mono', monospace; font-size: 10px; color: rgba(247,245,240,0.4); letter-spacing: 0.06em; }
  .sublib-search-wrap { position: relative; }
  .sublib-search { background: rgba(247,245,240,0.06); border: 1px solid rgba(247,245,240,0.12); border-radius: 6px; padding: 8px 14px 8px 34px; font-family: 'Syne', sans-serif; font-size: 13px; color: var(--paper); width: 280px; outline: none; transition: border-color 0.2s; }
  .sublib-search::placeholder { color: rgba(247,245,240,0.3); }
  .sublib-search:focus { border-color: rgba(200,146,42,0.4); }
  .sublib-search-icon { position: absolute; left: 10px; top: 50%; transform: translateY(-50%); color: rgba(247,245,240,0.3); font-size: 13px; pointer-events: none; }
  .sublib-curr-tabs { display: flex; gap: 6px; flex-wrap: wrap; }
  .sublib-curr-tab { font-family: 'Syne', sans-serif; font-size: 12px; font-weight: 600; padding: 6px 16px; border-radius: 100px; border: 1px solid rgba(247,245,240,0.12); background: transparent; color: rgba(247,245,240,0.45); cursor: pointer; transition: all 0.18s; letter-spacing: 0.02em; }
  .sublib-curr-tab:hover { color: rgba(247,245,240,0.8); border-color: rgba(247,245,240,0.25); }
  .sublib-curr-tab.active { color: #0f1210; border-color: transparent; }
  .sublib-body { padding: 20px 28px 40px; overflow-y: auto; max-height: calc(100vh - 160px); }
  .sublib-curriculum { display: none; }
  .sublib-curriculum.active { display: block; }
  .sublib-category { margin-bottom: 28px; }
  .sublib-cat-header { display: flex; align-items: center; gap: 10px; margin-bottom: 14px; padding-bottom: 8px; border-bottom: 1px solid rgba(247,245,240,0.07); }
  .sublib-cat-icon { font-size: 16px; }
  .sublib-cat-name { font-family: 'Syne', sans-serif; font-size: 13px; font-weight: 700; color: rgba(247,245,240,0.7); letter-spacing: 0.02em; }
  .sublib-cat-count { font-family: 'JetBrains Mono', monospace; font-size: 10px; color: rgba(247,245,240,0.3); }
  .sublib-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(180px, 1fr)); gap: 8px; }
  .sublib-card { position: relative; background: rgba(247,245,240,0.04); border: 1px solid rgba(247,245,240,0.08); border-radius: 8px; padding: 12px 14px; cursor: pointer; transition: all 0.18s; text-decoration: none; display: block; }
  .sublib-card:hover { background: rgba(247,245,240,0.08); border-color: var(--card-color, rgba(200,146,42,0.35)); transform: translateY(-2px); box-shadow: 0 4px 16px rgba(0,0,0,0.3); }
  .sublib-card.has-notes { border-color: rgba(247,245,240,0.15); }
  .sublib-card.has-notes::after { content: '✓'; position: absolute; top: 8px; right: 10px; font-size: 9px; font-family: 'JetBrains Mono', monospace; color: var(--card-color, var(--gold)); opacity: 0.7; }
  .sublib-card-subject { font-family: 'Syne', sans-serif; font-size: 12px; font-weight: 700; color: var(--paper); margin-bottom: 4px; line-height: 1.3; }
  .sublib-card-meta { font-family: 'JetBrains Mono', monospace; font-size: 9px; color: rgba(247,245,240,0.35); letter-spacing: 0.05em; text-transform: uppercase; }
  .sublib-card-actions { display: flex; gap: 4px; margin-top: 8px; }
  .sublib-card-btn { font-family: 'Syne', sans-serif; font-size: 9px; font-weight: 600; padding: 3px 7px; border-radius: 3px; border: none; cursor: pointer; transition: all 0.15s; letter-spacing: 0.02em; }
  .sublib-card-btn.primary { background: var(--card-color, var(--gold)); color: #0f1210; }
  .sublib-card-btn.primary:hover { opacity: 0.85; }
  .sublib-card-btn.secondary { background: rgba(247,245,240,0.08); color: rgba(247,245,240,0.6); }
  .sublib-card-btn.secondary:hover { background: rgba(247,245,240,0.15); }
  .sublib-empty { text-align: center; padding: 48px 20px; color: rgba(247,245,240,0.35); font-family: 'Syne', sans-serif; font-size: 13px; display: none; }
  .sublib-empty.visible { display: block; }
  .sublib-note-chip { display: inline-block; font-family: 'JetBrains Mono', monospace; font-size: 8px; padding: 2px 5px; border-radius: 2px; margin-top: 4px; }
  /* Subject detail modal */
  .sublib-modal-overlay { position: fixed; inset: 0; background: rgba(0,0,0,0.75); z-index: 9999; display: none; align-items: center; justify-content: center; padding: 24px; backdrop-filter: blur(4px); }
  .sublib-modal-overlay.open { display: flex; }
  .sublib-modal { background: #141716; border: 1px solid rgba(247,245,240,0.1); border-radius: 16px; width: 100%; max-width: 640px; max-height: 85vh; overflow-y: auto; padding: 32px; position: relative; }
  .sublib-modal-close { position: absolute; top: 16px; right: 16px; background: rgba(247,245,240,0.08); border: none; border-radius: 50%; width: 32px; height: 32px; color: rgba(247,245,240,0.6); cursor: pointer; font-size: 16px; display: flex; align-items: center; justify-content: center; transition: all 0.15s; }
  .sublib-modal-close:hover { background: rgba(247,245,240,0.15); color: var(--paper); }
  .sublib-modal-curr { font-family: 'JetBrains Mono', monospace; font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 6px; }
  .sublib-modal-title { font-family: 'Syne', sans-serif; font-size: 22px; font-weight: 800; color: var(--paper); margin-bottom: 4px; }
  .sublib-modal-sub { font-size: 13px; color: rgba(247,245,240,0.45); margin-bottom: 24px; }
  .sublib-modal-section { margin-bottom: 20px; }
  .sublib-modal-section-title { font-family: 'Syne', sans-serif; font-size: 12px; font-weight: 700; color: rgba(247,245,240,0.5); text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 10px; }
  .sublib-modal-actions { display: flex; flex-direction: column; gap: 8px; }
  .sublib-modal-action { display: flex; align-items: center; gap: 12px; padding: 14px 16px; border-radius: 8px; border: 1px solid rgba(247,245,240,0.1); background: rgba(247,245,240,0.04); cursor: pointer; transition: all 0.18s; text-decoration: none; }
  .sublib-modal-action:hover { background: rgba(247,245,240,0.08); border-color: rgba(247,245,240,0.2); }
  .sublib-modal-action-icon { font-size: 20px; flex-shrink: 0; }
  .sublib-modal-action-text { flex: 1; }
  .sublib-modal-action-name { font-family: 'Syne', sans-serif; font-size: 13px; font-weight: 700; color: var(--paper); margin-bottom: 2px; }
  .sublib-modal-action-desc { font-size: 11px; color: rgba(247,245,240,0.45); line-height: 1.4; }
  .sublib-modal-action-arrow { color: rgba(247,245,240,0.3); font-size: 14px; flex-shrink: 0; }
  .sublib-coming-soon { background: rgba(200,146,42,0.08); border: 1px dashed rgba(200,146,42,0.3); border-radius: 8px; padding: 14px 16px; display: flex; align-items: center; gap: 10px; }
  .sublib-coming-soon-icon { font-size: 18px; }
  .sublib-coming-soon-text { font-family: 'Syne', sans-serif; font-size: 12px; color: var(--gold); }


  /* ===== SUBJECT LIBRARY OVERLAY ===== */
  .sublib-overlay{display:none;position:fixed;inset:0;z-index:9000;background:rgba(13,15,14,0.97);overflow-y:auto;}
  .sublib-overlay.open{display:flex;flex-direction:column;}
  .sublib-header{position:sticky;top:0;z-index:10;background:#0d0f0e;border-bottom:1px solid rgba(200,146,42,0.22);padding:0 32px;height:64px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0;}
  .sublib-logo{font-family:'Syne',sans-serif;font-weight:800;font-size:20px;color:var(--paper);}
  .sublib-logo span{color:var(--gold);}
  .sublib-close{width:40px;height:40px;border-radius:50%;background:rgba(247,245,240,0.08);border:none;color:var(--paper);font-size:18px;cursor:pointer;display:flex;align-items:center;justify-content:center;transition:background 0.2s;font-family:'Syne',sans-serif;}
  .sublib-close:hover{background:rgba(247,245,240,0.16);}
  .sublib-inner{flex:1;max-width:1280px;margin:0 auto;padding:40px 32px 80px;width:100%;}
  .sublib-big-title{font-family:'Syne',sans-serif;font-size:clamp(28px,4vw,50px);font-weight:800;color:var(--paper);letter-spacing:-1.5px;margin-bottom:8px;line-height:1;}
  .sublib-big-title em{font-family:'Literata',serif;font-style:italic;color:var(--gold);font-weight:400;}
  .sublib-subtitle{font-size:16px;color:rgba(247,245,240,0.5);margin-bottom:36px;line-height:1.6;}
  .sublib-stats{display:grid;grid-template-columns:repeat(5,1fr);gap:12px;margin-bottom:40px;}
  .sublib-stat{background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.07);border-radius:var(--radius-lg);padding:16px;text-align:center;}
  .sublib-stat-num{font-family:'Syne',sans-serif;font-size:26px;font-weight:800;color:var(--gold);line-height:1;margin-bottom:4px;}
  .sublib-stat-lbl{font-size:10px;color:rgba(247,245,240,0.4);font-family:'JetBrains Mono',monospace;letter-spacing:0.05em;text-transform:uppercase;}
  .sublib-search-wrap{position:relative;margin-bottom:28px;}
  .sublib-search{width:100%;background:rgba(247,245,240,0.06);border:1px solid rgba(247,245,240,0.12);border-radius:var(--radius-lg);padding:14px 48px 14px 18px;font-family:'Syne',sans-serif;font-size:15px;color:var(--paper);outline:none;transition:border-color 0.2s;}
  .sublib-search::placeholder{color:rgba(247,245,240,0.3);}
  .sublib-search:focus{border-color:rgba(200,146,42,0.4);}
  .sublib-search-icon{position:absolute;right:16px;top:50%;transform:translateY(-50%);color:rgba(247,245,240,0.3);font-size:18px;pointer-events:none;}
  .sublib-tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:36px;padding-bottom:20px;border-bottom:1px solid rgba(247,245,240,0.07);}
  .sublib-tab{font-family:'Syne',sans-serif;font-size:13px;font-weight:700;padding:10px 20px;border-radius:100px;border:1px solid rgba(247,245,240,0.14);background:transparent;color:rgba(247,245,240,0.5);cursor:pointer;transition:all 0.2s;display:flex;align-items:center;gap:8px;letter-spacing:0.01em;}
  .sublib-tab:hover{border-color:rgba(247,245,240,0.35);color:var(--paper);}
  .sublib-tab.on{background:var(--gold);border-color:var(--gold);color:var(--paper);}
  .sublib-section{display:none;}
  .sublib-section.on{display:block;}
  .sublib-curr-header{display:flex;align-items:center;gap:16px;margin-bottom:32px;padding:22px;border-radius:var(--radius-xl);border:1px solid rgba(247,245,240,0.07);}
  .sublib-curr-icon{font-size:38px;flex-shrink:0;}
  .sublib-curr-name{font-family:'Syne',sans-serif;font-size:22px;font-weight:800;color:var(--paper);line-height:1;}
  .sublib-curr-desc{font-size:13px;color:rgba(247,245,240,0.45);margin-top:4px;}
  .sublib-curr-badge{display:inline-block;font-family:'JetBrains Mono',monospace;font-size:10px;letter-spacing:0.06em;padding:4px 10px;border-radius:100px;margin-top:6px;}
  .sublib-cat{margin-bottom:32px;}
  .sublib-cat-hdr{display:flex;align-items:center;gap:10px;margin-bottom:12px;padding-bottom:8px;border-bottom:1px solid rgba(247,245,240,0.06);}
  .sublib-cat-icon{font-size:17px;}
  .sublib-cat-title{font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--paper);}
  .sublib-cat-count{font-family:'JetBrains Mono',monospace;font-size:10px;color:rgba(247,245,240,0.3);margin-left:auto;}
  .sublib-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(210px,1fr));gap:7px;}
  .sublib-card{background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.07);border-radius:var(--radius-lg);padding:12px 14px;cursor:pointer;transition:all 0.16s;display:flex;align-items:center;justify-content:space-between;gap:6px;}
  .sublib-card:hover{background:rgba(247,245,240,0.08);border-color:rgba(200,146,42,0.3);transform:translateY(-1px);}
  .sublib-card.live{border-left:3px solid var(--gold);}
  .sublib-card-name{font-family:'Syne',sans-serif;font-size:12.5px;font-weight:600;color:var(--paper);line-height:1.3;}
  .sublib-card-btns{display:flex;align-items:center;gap:4px;flex-shrink:0;}
  .sbc{font-family:'JetBrains Mono',monospace;font-size:8.5px;letter-spacing:0.05em;padding:3px 6px;border-radius:3px;border:none;cursor:pointer;transition:background 0.15s;white-space:nowrap;}
  .sbc-notes{background:rgba(200,146,42,0.15);color:var(--gold);}
  .sbc-notes:hover{background:rgba(200,146,42,0.3);}
  .sbc-papers{background:rgba(91,168,232,0.15);color:#5ba8e8;}
  .sbc-papers:hover{background:rgba(91,168,232,0.28);}
  .sbc-soon{background:rgba(247,245,240,0.05);color:rgba(247,245,240,0.28);cursor:default;}
  .sublib-no-res{text-align:center;padding:60px 20px;color:rgba(247,245,240,0.35);font-size:15px;display:none;}
  @media(max-width:768px){.sublib-inner{padding:20px 16px 60px;}.sublib-header{padding:0 16px;}.sublib-stats{grid-template-columns:repeat(3,1fr);}.sublib-grid{grid-template-columns:1fr 1fr;}.sublib-tab{padding:8px 14px;font-size:12px;}}
  @media(max-width:480px){.sublib-grid{grid-template-columns:1fr;}.sublib-stats{grid-template-columns:repeat(2,1fr);}}


  /* ── STAR / MY SUBJECTS ── */
  .subj-card { position: relative; }
  .subj-star-btn {
    position: absolute; top: 10px; right: 10px;
    background: none; border: none; cursor: pointer;
    font-size: 16px; line-height: 1; padding: 2px;
    color: rgba(247,245,240,0.2);
    transition: color 0.2s, transform 0.15s;
    z-index: 2;
  }
  .subj-star-btn:hover { color: var(--gold); transform: scale(1.25); }
  .subj-star-btn.starred { color: var(--gold); }

  /* My Subjects strip on overview */
  .my-subjects-strip {
    background: rgba(247,245,240,0.04);
    border: 1px solid rgba(247,245,240,0.08);
    border-radius: var(--radius-lg);
    padding: 14px 16px;
    margin-bottom: 14px;
  }
  .my-subjects-hdr {
    display: flex; align-items: center; justify-content: space-between;
    margin-bottom: 10px;
  }
  .my-subjects-title {
    font-family: 'Syne', sans-serif; font-size: 12px; font-weight: 600;
    color: var(--paper); display: flex; align-items: center; gap: 6px;
  }
  .my-subjects-edit {
    font-family: 'JetBrains Mono', monospace; font-size: 9px;
    letter-spacing: 0.06em; text-transform: uppercase;
    color: var(--gold); cursor: pointer; border: none; background: none;
    padding: 0; transition: opacity 0.2s;
  }
  .my-subjects-edit:hover { opacity: 0.7; }
  .my-subjects-grid {
    display: flex; flex-wrap: wrap; gap: 6px;
  }
  .my-subj-pill {
    display: inline-flex; align-items: center; gap: 6px;
    font-family: 'Syne', sans-serif; font-size: 11px; font-weight: 600;
    padding: 5px 12px; border-radius: 100px;
    border: 1px solid rgba(247,245,240,0.12);
    background: rgba(247,245,240,0.06);
    color: var(--paper); cursor: pointer;
    transition: all 0.18s;
  }
  .my-subj-pill:hover {
    background: rgba(200,146,42,0.14);
    border-color: rgba(200,146,42,0.35);
  }
  .my-subj-pill .pill-curr {
    font-family: 'JetBrains Mono', monospace; font-size: 8.5px;
    letter-spacing: 0.06em; text-transform: uppercase;
    opacity: 0.55;
  }
  .my-subj-pill .pill-dot {
    width: 6px; height: 6px; border-radius: 50%; flex-shrink: 0;
  }
  .my-subjects-empty {
    font-size: 12px; color: rgba(247,245,240,0.35);
    font-style: italic;
  }

  /* Starred badge on subj-card */
  .subj-card.is-starred {
    border-color: rgba(200,146,42,0.3);
    background: rgba(200,146,42,0.06);
  }

  /* Notes coming soon card */
  .subj-card.coming-soon { opacity: 0.65; }
  .subj-coming-tag {
    display: inline-block;
    font-family: 'JetBrains Mono', monospace; font-size: 8px;
    letter-spacing: 0.08em; text-transform: uppercase;
    background: rgba(247,245,240,0.07); color: rgba(247,245,240,0.4);
    padding: 2px 7px; border-radius: 3px; margin-top: 6px;
  }
  .subj-has-notes-tag {
    display: inline-block;
    font-family: 'JetBrains Mono', monospace; font-size: 8px;
    letter-spacing: 0.08em; text-transform: uppercase;
    background: rgba(200,146,42,0.15); color: var(--gold);
    padding: 2px 7px; border-radius: 3px; margin-top: 6px;
  }

</style>
</head>
<body>

<!-- NAV -->
<nav>
  <a href="#" class="nav-logo" style="display:flex;align-items:center;gap:9px;text-decoration:none;">
    <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg" style="flex-shrink:0;">
      <circle cx="16" cy="16" r="15" stroke="#c8922a" stroke-width="1.2" fill="none" opacity="0.35"/>
      <circle cx="16" cy="16" r="10" stroke="#c8922a" stroke-width="1.2" fill="none" opacity="0.55"/>
      <!-- Light rays -->
      <line x1="16" y1="2" x2="16" y2="6" stroke="#c8922a" stroke-width="1.6" stroke-linecap="round"/>
      <line x1="16" y1="26" x2="16" y2="30" stroke="#c8922a" stroke-width="1.6" stroke-linecap="round"/>
      <line x1="2" y1="16" x2="6" y2="16" stroke="#c8922a" stroke-width="1.6" stroke-linecap="round"/>
      <line x1="26" y1="16" x2="30" y2="16" stroke="#c8922a" stroke-width="1.6" stroke-linecap="round"/>
      <line x1="5.5" y1="5.5" x2="8.3" y2="8.3" stroke="#c8922a" stroke-width="1.4" stroke-linecap="round" opacity="0.7"/>
      <line x1="23.7" y1="23.7" x2="26.5" y2="26.5" stroke="#c8922a" stroke-width="1.4" stroke-linecap="round" opacity="0.7"/>
      <line x1="26.5" y1="5.5" x2="23.7" y2="8.3" stroke="#c8922a" stroke-width="1.4" stroke-linecap="round" opacity="0.7"/>
      <line x1="8.3" y1="23.7" x2="5.5" y2="26.5" stroke="#c8922a" stroke-width="1.4" stroke-linecap="round" opacity="0.7"/>
      <!-- Core glow -->
      <circle cx="16" cy="16" r="4.5" fill="#c8922a" opacity="0.9"/>
      <circle cx="16" cy="16" r="2.5" fill="#f5e9d0"/>
    </svg>
    <span style="font-family:'Syne',sans-serif;font-weight:800;font-size:22px;color:var(--ink);letter-spacing:-0.5px;">Lumen</span>
  </a>
  <ul class="nav-links">
    <li><a href="#features">Features</a></li>
    <li><a href="#how">How it works</a></li>
    <li><a href="#dashboard">Dashboard</a></li>
    <li><a href="#" onclick="sublibOpen();return false;" style="color:var(--gold);font-weight:600;">All Subjects ✦</a></li>
    <li><a href="#curricula">Curricula</a></li>
    <li><a href="#pricing">Pricing</a></li>
    <li><a href="#faq">FAQ</a></li>
  </ul>
  <div style="display:flex;align-items:center;gap:10px;">
    <a href="#" onclick="adminPortalOpen();return false;" style="font-family:'JetBrains Mono',monospace;font-size:10px;font-weight:500;color:rgba(13,15,14,0.25);text-decoration:none;letter-spacing:0.06em;padding:6px 10px;border-radius:var(--radius);transition:all 0.2s;" title="Admin">⬡</a>
    <a href="#pricing" class="nav-cta">Start for free →</a>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-grid"></div>
  <div class="container">
    <div class="hero-tag animate">AI-Powered Exam Coach — Now Live</div>
    <h1 class="animate delay-1">Stop revising.<br>Start <em>training</em><br>for your exam.</h1>
    <p class="hero-sub animate delay-2">Lumen is the intelligent revision system built for GCSE, A-level, IB, and AP students who demand measurable grade improvement — not another content library.</p>
    <div class="hero-actions animate delay-3">
      <a href="#pricing" class="btn-primary">Begin your free trial →</a>
      <a href="#how" class="btn-secondary">See how it works</a>
      <a href="#" onclick="sublibOpen();return false;" class="btn-secondary" style="border-color:var(--gold);color:var(--gold);font-weight:600;">Browse 255 Subjects →</a>
    </div>
    <div class="hero-stats animate delay-4">
      <div class="hero-stat">
        <span class="hero-stat-num">94%</span>
        <span class="hero-stat-label">of students improved by ≥1 grade</span>
      </div>
      <div class="hero-divider"></div>
      <div class="hero-stat">
        <span class="hero-stat-num">5</span>
        <span class="hero-stat-label">global curricula supported</span>
      </div>
      <div class="hero-divider"></div>
      <div class="hero-stat">
        <span class="hero-stat-num">Zero</span>
        <span class="hero-stat-label">passive reading. Ever.</span>
      </div>
    </div>
  </div>
</section>

<!-- MARQUEE -->
<div class="marquee-section">
  <div class="marquee-track">
    <div class="marquee-item"><span class="marquee-dot"></span>GCSE</div>
    <div class="marquee-item"><span class="marquee-dot"></span>IGCSE</div>
    <div class="marquee-item"><span class="marquee-dot"></span>A-level</div>
    <div class="marquee-item"><span class="marquee-dot"></span>IB Diploma</div>
    <div class="marquee-item"><span class="marquee-dot"></span>AP Exams</div>
    <div class="marquee-item"><span class="marquee-dot"></span>Spaced Repetition</div>
    <div class="marquee-item"><span class="marquee-dot"></span>AI Marking</div>
    <div class="marquee-item"><span class="marquee-dot"></span>FRQ Training</div>
    <div class="marquee-item"><span class="marquee-dot"></span>Exam Simulation</div>
    <div class="marquee-item"><span class="marquee-dot"></span>Past Papers</div>
    <div class="marquee-item"><span class="marquee-dot"></span>Grade Prediction</div>
    <div class="marquee-item"><span class="marquee-dot"></span>GCSE</div>
    <div class="marquee-item"><span class="marquee-dot"></span>IGCSE</div>
    <div class="marquee-item"><span class="marquee-dot"></span>A-level</div>
    <div class="marquee-item"><span class="marquee-dot"></span>IB Diploma</div>
    <div class="marquee-item"><span class="marquee-dot"></span>AP Exams</div>
    <div class="marquee-item"><span class="marquee-dot"></span>Spaced Repetition</div>
    <div class="marquee-item"><span class="marquee-dot"></span>AI Marking</div>
    <div class="marquee-item"><span class="marquee-dot"></span>FRQ Training</div>
    <div class="marquee-item"><span class="marquee-dot"></span>Exam Simulation</div>
    <div class="marquee-item"><span class="marquee-dot"></span>Past Papers</div>
    <div class="marquee-item"><span class="marquee-dot"></span>Grade Prediction</div>
  </div>
</div>

<!-- PROBLEM -->
<section class="problem-section">
  <div class="container">
    <div class="section-label">The problem with revision</div>
    <h2 class="section-title" style="color:var(--paper);">Other platforms<br>teach you to <em>read</em>.<br>We train you to <em>perform</em>.</h2>
    <p class="section-body" style="margin-top:16px;">Existing tools waste your time with passive content. Lumen eliminates every second of unproductive revision.</p>
    <div class="problem-grid">
      <div class="problem-item">
        <span class="problem-num mono">01</span>
        <div class="problem-text">
          <h3>Revising what you already know</h3>
          <p>Most students spend 70% of revision time on topics they have already mastered. Lumen's AI identifies your real gaps instantly.</p>
        </div>
      </div>
      <div class="problem-item">
        <span class="problem-num mono">02</span>
        <div class="problem-text">
          <h3>Passive reading disguised as revision</h3>
          <p>Scrolling through notes creates an illusion of learning. Without active recall, retention drops to near zero within 48 hours.</p>
        </div>
      </div>
      <div class="problem-item">
        <span class="problem-num mono">03</span>
        <div class="problem-text">
          <h3>No training in exam technique</h3>
          <p>A student can know the content perfectly and still lose 30% of marks through poor exam technique. We fix this systematically.</p>
        </div>
      </div>
      <div class="problem-item">
        <span class="problem-num mono">04</span>
        <div class="problem-text">
          <h3>Fragmented resources, no unified system</h3>
          <p>Students juggle multiple platforms simultaneously. Lumen replaces all of them — with one adaptive engine that includes notes, past papers, and AI coaching in a single place.</p>
        </div>
      </div>
      <div class="problem-item">
        <span class="problem-num mono">05</span>
        <div class="problem-text">
          <h3>Feedback that arrives too late</h3>
          <p>Marking mock exams weeks later makes feedback nearly useless. Our AI marks every response in under 3 seconds, with actionable detail.</p>
        </div>
      </div>
      <div class="problem-item">
        <span class="problem-num mono">06</span>
        <div class="problem-text">
          <h3>No cross-curriculum intelligence</h3>
          <p>Students moving from GCSE to A-level, or from A-level to IB, receive zero support. We map every topic equivalency across all five curricula.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- FEATURES -->
<section class="features-section" id="features">
  <div class="container">
    <div class="features-header">
      <div>
        <div class="section-label">Core system</div>
        <h2 class="section-title">Every feature<br>built for <em>one goal:</em><br>your grade.</h2>
      </div>
      <p class="section-body">Lumen is not a content platform. It is an adaptive training system that models how examiners think and forces you to think the same way — under pressure, at speed.</p>
    </div>
    <div class="feature-cards">
      <div class="feature-card featured">
        <div class="feature-icon" style="background:rgba(200,146,42,0.2);">🧠</div>
        <h3>AI Personalization Engine</h3>
        <p>Tracks performance across every topic, question type, and skill. Identifies micro-weaknesses like "loses marks on IB 'evaluate' questions" and adapts in real time.</p>
        <span class="feature-tag">Core AI</span>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:var(--emerald-light);">📖</div>
        <h3>Full Syllabus Revision Notes</h3>
        <p>Comprehensive, examiner-written notes for every topic in every subject across all curricula — with curated YouTube videos to reinforce each concept.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:var(--sapphire-light);">📄</div>
        <h3>Past Papers &amp; Mark Schemes</h3>
        <p>Every past paper for every subject, with direct links to official mark schemes. Organized by year and paper, exactly like Save My Exams and PMT.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:var(--crimson-light);">⏱</div>
        <h3>Full Exam Simulation</h3>
        <p>Timed, mixed-topic exams under realistic conditions for every curriculum. AI marking with instant, line-by-line feedback and post-exam analytics.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:var(--gold-light);">🔁</div>
        <h3>Spaced Repetition System</h3>
        <p>Scientifically schedules revision based on your personal forgetting curve. High-impact weaknesses are automatically prioritized above everything else.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon" style="background:var(--paper-3);">📊</div>
        <h3>Grade Prediction Dashboard</h3>
        <p>Displays your current grade estimate across all curricula (GCSE 1–9, A* to E, IB 1–7, AP 1–5), your target gap, and a generated daily revision plan.</p>
      </div>
    </div>
  </div>
</section>

<!-- HOW IT WORKS -->
<section class="how-section" id="how">
  <div class="container">
    <div class="section-label">The process</div>
    <h2 class="section-title">From sign-up to<br><em>exam-ready</em> in four steps.</h2>
    <div class="how-steps">
      <div class="how-step">
        <div class="how-step-num">1</div>
        <h3>Diagnostic assessment</h3>
        <p>A 20-minute AI-driven diagnostic maps your exact strengths and weaknesses across every topic in your curriculum, from the very first session.</p>
      </div>
      <div class="how-step">
        <div class="how-step-num">2</div>
        <h3>Personalized training plan</h3>
        <p>The system generates a daily plan that eliminates wasted time. Every session targets your highest-impact gaps with active recall — never passive content.</p>
      </div>
      <div class="how-step">
        <div class="how-step-num">3</div>
        <h3>Exam technique mastery</h3>
        <p>Side-by-side comparisons of weak answers vs. full-mark answers, with IB command term training, AP FRQ rubric coaching, and GCSE structured response drills.</p>
      </div>
      <div class="how-step">
        <div class="how-step-num">4</div>
        <h3>Simulated exam conditions</h3>
        <p>Full past-paper simulations under timed, realistic conditions. AI marks every response in seconds and generates a precise improvement pathway for your exam date.</p>
      </div>
    </div>
  </div>
</section>

<!-- DASHBOARD PREVIEW -->
<section class="dashboard-section" id="dashboard">
  <div class="container">
    <div class="section-label">Live dashboard</div>
    <h2 class="section-title">Everything you need,<br>nothing you don't.</h2>
    <p class="section-body" style="margin-top:12px;">Click any section in the sidebar below to explore your full student dashboard — exactly as it will look after subscribing. Fully interactive.</p>
    <div class="full-dashboard">
      <div class="fdash-topbar">
        <div class="fdash-dots">
          <div class="fdash-dot" style="background:#ff5f57;"></div>
          <div class="fdash-dot" style="background:#febc2e;"></div>
          <div class="fdash-dot" style="background:#28c840;"></div>
        </div>
        <span class="fdash-title" style="display:flex;align-items:center;gap:6px;">
          <svg width="14" height="14" viewBox="0 0 32 32" fill="none"><circle cx="16" cy="16" r="10" stroke="#c8922a" stroke-width="1.5" fill="none" opacity="0.5"/><line x1="16" y1="2" x2="16" y2="7" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><line x1="16" y1="25" x2="16" y2="30" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><line x1="2" y1="16" x2="7" y2="16" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><line x1="25" y1="16" x2="30" y2="16" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><circle cx="16" cy="16" r="4" fill="#c8922a" opacity="0.8"/></svg>
          Lumen — Student Dashboard
        </span>
        <div class="fdash-user">
          <span class="fdash-username">Amelia T.</span>
          <div class="fdash-avatar">AT</div>
        </div>
      </div>
      <div class="fdash-layout">
        <div class="fdash-sidebar">
          <div class="fdash-nav active" data-panel="overview"><span class="fdash-nav-icon">▦</span> Overview</div>
          <div class="fdash-nav" data-panel="subjects"><span class="fdash-nav-icon">📚</span> Subjects</div>
          <div class="fdash-nav" data-panel="notes"><span class="fdash-nav-icon">📖</span> Revision Notes</div>
          <div class="fdash-nav" data-panel="papers"><span class="fdash-nav-icon">📄</span> Past Papers</div>
          <div class="fdash-nav" data-panel="practice"><span class="fdash-nav-icon">✎</span> Practice</div>
          <div class="fdash-nav" data-panel="examsim"><span class="fdash-nav-icon">◷</span> Exam Sim</div>
          <div class="fdash-nav" data-panel="flashcards"><span class="fdash-nav-icon">↺</span> Flashcards</div>
          <div class="fdash-nav" data-panel="mynotes"><span class="fdash-nav-icon">✏</span> My Notes</div>
          <div class="fdash-sep"></div>
          <div class="fdash-nav" data-panel="suggestions"><span class="fdash-nav-icon">★</span> AI Suggestions</div>
          <div class="fdash-nav" data-panel="analytics"><span class="fdash-nav-icon">◈</span> Analytics</div>
          <div class="fdash-nav" data-panel="settings"><span class="fdash-nav-icon">⚙</span> Settings</div>
        </div>
        <div class="fdash-content">

          <!-- OVERVIEW -->
          <div class="fdash-panel active" id="fdash-overview">
            <div class="fdash-motiv">
              <div class="fdash-motiv-icon">✨</div>
              <div>
                <div class="fdash-motiv-label">Today's Motivation</div>
                <div class="fdash-motiv-text" id="fdash-quote">"The expert in anything was once a beginner. Every question you answer today is a mark you secure for exam day."</div>
              </div>
            </div>
            
            <div class="my-subjects-strip" id="my-subjects-strip">
              <div class="my-subjects-hdr">
                <div class="my-subjects-title">⭐ My Subjects</div>
                <button class="my-subjects-edit" onclick="goToNotes()">+ Add subjects</button>
              </div>
              <div class="my-subjects-grid" id="my-subjects-grid">
                <span class="my-subjects-empty" id="my-subjects-empty">No subjects starred yet. Go to Revision Notes and star the subjects you are studying.</span>
              </div>
            </div>
            <div class="fdash-greeting">Good morning, <span>Amelia</span> — 47 days to your A-level Chemistry exam.</div>
            <div class="fdash-stats">
              <div class="fdash-stat"><div class="fdash-stat-lbl">Predicted grade</div><div class="fdash-stat-val au">B+</div><div class="fdash-stat-sub">Target: A*</div></div>
              <div class="fdash-stat"><div class="fdash-stat-lbl">Questions answered</div><div class="fdash-stat-val">1,247</div><div class="fdash-stat-sub">This month</div></div>
              <div class="fdash-stat"><div class="fdash-stat-lbl">Accuracy rate</div><div class="fdash-stat-val g">74%</div><div class="fdash-stat-sub">↑ 11% last week</div></div>
              <div class="fdash-stat"><div class="fdash-stat-lbl">Streak</div><div class="fdash-stat-val bl">18d 🔥</div><div class="fdash-stat-sub">Personal best</div></div>
            </div>
            <div class="fdash-row2">
              <div class="fdash-box">
                <div class="fdash-box-title">Weakest topics — mark impact</div>
                <div class="fdash-topic-row"><span class="fdash-topic-name">Organic Mechanisms</span><div class="fdash-bar-wrap"><div class="fdash-bar-fill wk" style="width:31%;"></div></div><span class="fdash-pct">31%</span></div>
                <div class="fdash-topic-row"><span class="fdash-topic-name">Equilibria Calcs</span><div class="fdash-bar-wrap"><div class="fdash-bar-fill md" style="width:52%;"></div></div><span class="fdash-pct">52%</span></div>
                <div class="fdash-topic-row"><span class="fdash-topic-name">Redox Titrations</span><div class="fdash-bar-wrap"><div class="fdash-bar-fill md" style="width:58%;"></div></div><span class="fdash-pct">58%</span></div>
                <div class="fdash-topic-row"><span class="fdash-topic-name">Electrode Potentials</span><div class="fdash-bar-wrap"><div class="fdash-bar-fill ok" style="width:71%;"></div></div><span class="fdash-pct">71%</span></div>
              </div>
              <div class="fdash-box">
                <div class="fdash-box-title">Today's AI-generated plan</div>
                <div class="fdash-sched-row"><span class="fdash-sched-time">09:00</span><span class="fdash-sched-task">Organic Mechanisms — Nucleophilic substitution</span><span class="fdash-badge b-rev">45m</span></div>
                <div class="fdash-sched-row"><span class="fdash-sched-time">10:00</span><span class="fdash-sched-task">Active recall: Equilibria Kp/Kc</span><span class="fdash-badge b-prac">30m</span></div>
                <div class="fdash-sched-row"><span class="fdash-sched-time">11:00</span><span class="fdash-sched-task">Timed exam: Section B Paper 2</span><span class="fdash-badge b-exam">60m</span></div>
                <div class="fdash-sched-row"><span class="fdash-sched-time">14:00</span><span class="fdash-sched-task">Flashcard spaced repetition deck</span><span class="fdash-badge b-rev">20m</span></div>
              </div>
            </div>
          </div>

          <!-- REVISION NOTES -->
          <div class="fdash-panel" id="fdash-notes">
            <div id="notes-list">
              <div class="notes-panel-title">Revision Notes</div>
              <div class="notes-panel-sub">Syllabus-aligned notes for every subject. Click any subject to read, then explore curated video explanations.</div>
              <div class="notes-filters">
                <button class="notes-filt-btn on" onclick="filterSubjects('all',this)">All</button>
                <button class="notes-filt-btn" onclick="filterSubjects('gcse',this)">GCSE</button>
                <button class="notes-filt-btn" onclick="filterSubjects('alevel',this)">A-Level</button>
                <button class="notes-filt-btn" onclick="filterSubjects('ib',this)">IB</button>
                <button class="notes-filt-btn" onclick="filterSubjects('ap',this)">AP</button>
                <button class="notes-filt-btn" onclick="filterSubjects('igcse',this)">IGCSE</button>
              </div>
              <div class="subjects-grid" id="subjects-grid">
<div class="subj-card " data-c="gcse" id="sc-gcse-maths">
  <button class="subj-star-btn" id="star-gcse-maths" onclick="event.stopPropagation();toggleStar('gcse-maths','Mathematics','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Mathematics</div>
  <div class="subj-topics">Number · Algebra · Geometry · Statistics · Trigonometry</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-addmaths">
  <button class="subj-star-btn" id="star-gcse-addmaths" onclick="event.stopPropagation();toggleStar('gcse-addmaths','Additional Mathematics','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR / Cambridge</div>
  <div class="subj-title">Additional Mathematics</div>
  <div class="subj-topics">Further algebra · Calculus intro · Advanced geometry</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-stats">
  <button class="subj-star-btn" id="star-gcse-stats" onclick="event.stopPropagation();toggleStar('gcse-stats','Statistics','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel</div>
  <div class="subj-title">Statistics</div>
  <div class="subj-topics">Data collection · Probability · Hypothesis testing · Distributions</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-bio">
  <button class="subj-star-btn" id="star-gcse-bio" onclick="event.stopPropagation();toggleStar('gcse-bio','Biology','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR / Edexcel</div>
  <div class="subj-title">Biology</div>
  <div class="subj-topics">Cell biology · Genetics · Bioenergetics · Homeostasis · Ecology</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-chem">
  <button class="subj-star-btn" id="star-gcse-chem" onclick="event.stopPropagation();toggleStar('gcse-chem','Chemistry','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR / Edexcel</div>
  <div class="subj-title">Chemistry</div>
  <div class="subj-topics">Atomic structure · Bonding · Quantitative · Chemical changes · Organic</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-phys">
  <button class="subj-star-btn" id="star-gcse-phys" onclick="event.stopPropagation();toggleStar('gcse-phys','Physics','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR / Edexcel</div>
  <div class="subj-title">Physics</div>
  <div class="subj-topics">Energy · Electricity · Waves · Forces · Atomic structure · Space</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-combined">
  <button class="subj-star-btn" id="star-gcse-combined" onclick="event.stopPropagation();toggleStar('gcse-combined','Combined Science','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR / Edexcel</div>
  <div class="subj-title">Combined Science</div>
  <div class="subj-topics">Biology + Chemistry + Physics (double award)</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-envsc">
  <button class="subj-star-btn" id="star-gcse-envsc" onclick="event.stopPropagation();toggleStar('gcse-envsc','Environmental Science','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR</div>
  <div class="subj-title">Environmental Science</div>
  <div class="subj-topics">Ecosystems · Climate · Pollution · Sustainability</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-astro">
  <button class="subj-star-btn" id="star-gcse-astro" onclick="event.stopPropagation();toggleStar('gcse-astro','Astronomy','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · OCR</div>
  <div class="subj-title">Astronomy</div>
  <div class="subj-topics">Solar system · Stars · Cosmology · Telescopes</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-electronics">
  <button class="subj-star-btn" id="star-gcse-electronics" onclick="event.stopPropagation();toggleStar('gcse-electronics','Electronics','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · OCR / AQA</div>
  <div class="subj-title">Electronics</div>
  <div class="subj-topics">Circuits · Components · Systems · Soldering</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-engineering">
  <button class="subj-star-btn" id="star-gcse-engineering" onclick="event.stopPropagation();toggleStar('gcse-engineering','Engineering','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel</div>
  <div class="subj-title">Engineering</div>
  <div class="subj-topics">Design · Manufacture · Materials · Systems</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-englang">
  <button class="subj-star-btn" id="star-gcse-englang" onclick="event.stopPropagation();toggleStar('gcse-englang','English Language','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">English Language</div>
  <div class="subj-topics">Reading · Writing · Spoken language · Analysis</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-englit">
  <button class="subj-star-btn" id="star-gcse-englit" onclick="event.stopPropagation();toggleStar('gcse-englit','English Literature','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">English Literature</div>
  <div class="subj-topics">Poetry · Prose · Drama · Comparison · Shakespeare</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-french">
  <button class="subj-star-btn" id="star-gcse-french" onclick="event.stopPropagation();toggleStar('gcse-french','French','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">French</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking · Grammar</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-spanish">
  <button class="subj-star-btn" id="star-gcse-spanish" onclick="event.stopPropagation();toggleStar('gcse-spanish','Spanish','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Spanish</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking · Grammar</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-german">
  <button class="subj-star-btn" id="star-gcse-german" onclick="event.stopPropagation();toggleStar('gcse-german','German','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">German</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking · Grammar</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-chinese">
  <button class="subj-star-btn" id="star-gcse-chinese" onclick="event.stopPropagation();toggleStar('gcse-chinese','Chinese (Mandarin)','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel</div>
  <div class="subj-title">Chinese (Mandarin)</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-arabic">
  <button class="subj-star-btn" id="star-gcse-arabic" onclick="event.stopPropagation();toggleStar('gcse-arabic','Arabic','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel</div>
  <div class="subj-title">Arabic</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-latin">
  <button class="subj-star-btn" id="star-gcse-latin" onclick="event.stopPropagation();toggleStar('gcse-latin','Latin','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · OCR / Edexcel</div>
  <div class="subj-title">Latin</div>
  <div class="subj-topics">Translation · Literature · Language · Civilisation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-hist">
  <button class="subj-star-btn" id="star-gcse-hist" onclick="event.stopPropagation();toggleStar('gcse-hist','History','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">History</div>
  <div class="subj-topics">Case studies · Source skills · Extended writing · Periods</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-geog">
  <button class="subj-star-btn" id="star-gcse-geog" onclick="event.stopPropagation();toggleStar('gcse-geog','Geography','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Geography</div>
  <div class="subj-topics">Physical · Human · Fieldwork · Case studies</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-econ">
  <button class="subj-star-btn" id="star-gcse-econ" onclick="event.stopPropagation();toggleStar('gcse-econ','Economics','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel</div>
  <div class="subj-title">Economics</div>
  <div class="subj-topics">Demand · Supply · Market failure · Macro · Trade</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-business">
  <button class="subj-star-btn" id="star-gcse-business" onclick="event.stopPropagation();toggleStar('gcse-business','Business Studies','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Business Studies</div>
  <div class="subj-topics">Marketing · Finance · Operations · HR · Strategy</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-accounting">
  <button class="subj-star-btn" id="star-gcse-accounting" onclick="event.stopPropagation();toggleStar('gcse-accounting','Accounting','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR / CCEA</div>
  <div class="subj-title">Accounting</div>
  <div class="subj-topics">Financial statements · Double entry · Ledgers</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-psych">
  <button class="subj-star-btn" id="star-gcse-psych" onclick="event.stopPropagation();toggleStar('gcse-psych','Psychology','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Psychology</div>
  <div class="subj-topics">Memory · Development · Social influence · Criminology</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-sociology">
  <button class="subj-star-btn" id="star-gcse-sociology" onclick="event.stopPropagation();toggleStar('gcse-sociology','Sociology','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR</div>
  <div class="subj-title">Sociology</div>
  <div class="subj-topics">Culture · Family · Education · Crime · Identity</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-rs">
  <button class="subj-star-btn" id="star-gcse-rs" onclick="event.stopPropagation();toggleStar('gcse-rs','Religious Studies','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Religious Studies</div>
  <div class="subj-topics">Ethics · World religions · Philosophy · Belief</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-philosophy">
  <button class="subj-star-btn" id="star-gcse-philosophy" onclick="event.stopPropagation();toggleStar('gcse-philosophy','Philosophy','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR</div>
  <div class="subj-title">Philosophy</div>
  <div class="subj-topics">Ethics · Metaphysics · Epistemology · Logic</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-gp">
  <button class="subj-star-btn" id="star-gcse-gp" onclick="event.stopPropagation();toggleStar('gcse-gp','Global Perspectives','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · Cambridge</div>
  <div class="subj-title">Global Perspectives</div>
  <div class="subj-topics">Research · Analysis · Communication · Collaboration</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-classics">
  <button class="subj-star-btn" id="star-gcse-classics" onclick="event.stopPropagation();toggleStar('gcse-classics','Classical Civilisation','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · OCR</div>
  <div class="subj-title">Classical Civilisation</div>
  <div class="subj-topics">Greece · Rome · Myth · Literature · Archaeology</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-anc-hist">
  <button class="subj-star-btn" id="star-gcse-anc-hist" onclick="event.stopPropagation();toggleStar('gcse-anc-hist','Ancient History','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR</div>
  <div class="subj-title">Ancient History</div>
  <div class="subj-topics">Greece · Rome · Persia · Sources · Analysis</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-art">
  <button class="subj-star-btn" id="star-gcse-art" onclick="event.stopPropagation();toggleStar('gcse-art','Art & Design','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Art & Design</div>
  <div class="subj-topics">Drawing · Painting · Critical studies · Portfolio</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-photo">
  <button class="subj-star-btn" id="star-gcse-photo" onclick="event.stopPropagation();toggleStar('gcse-photo','Photography','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Photography</div>
  <div class="subj-topics">Composition · Darkroom · Digital · Critical studies</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-music">
  <button class="subj-star-btn" id="star-gcse-music" onclick="event.stopPropagation();toggleStar('gcse-music','Music','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Music</div>
  <div class="subj-topics">Performance · Composition · Listening · Analysis</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-drama">
  <button class="subj-star-btn" id="star-gcse-drama" onclick="event.stopPropagation();toggleStar('gcse-drama','Drama','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Drama</div>
  <div class="subj-topics">Performance · Devising · Set texts · Evaluation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-film">
  <button class="subj-star-btn" id="star-gcse-film" onclick="event.stopPropagation();toggleStar('gcse-film','Film Studies','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · Eduqas / AQA</div>
  <div class="subj-title">Film Studies</div>
  <div class="subj-topics">Film language · Context · Representation · Genre</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-media">
  <button class="subj-star-btn" id="star-gcse-media" onclick="event.stopPropagation();toggleStar('gcse-media','Media Studies','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Media Studies</div>
  <div class="subj-topics">Representation · Industry · Audience · Language</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-dance">
  <button class="subj-star-btn" id="star-gcse-dance" onclick="event.stopPropagation();toggleStar('gcse-dance','Dance','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel</div>
  <div class="subj-title">Dance</div>
  <div class="subj-topics">Performance · Choreography · Critical appreciation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-graphic-design">
  <button class="subj-star-btn" id="star-gcse-graphic-design" onclick="event.stopPropagation();toggleStar('gcse-graphic-design','Graphic Design','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel</div>
  <div class="subj-title">Graphic Design</div>
  <div class="subj-topics">Visual communication · Design process · Typography</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-cs">
  <button class="subj-star-btn" id="star-gcse-cs" onclick="event.stopPropagation();toggleStar('gcse-cs','Computer Science','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / OCR / Edexcel</div>
  <div class="subj-title">Computer Science</div>
  <div class="subj-topics">Algorithms · Programming · Networks · Data · Systems</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-ict">
  <button class="subj-star-btn" id="star-gcse-ict" onclick="event.stopPropagation();toggleStar('gcse-ict','ICT','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · Cambridge / OCR</div>
  <div class="subj-title">ICT</div>
  <div class="subj-topics">Systems · Applications · Data · Communication</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-dt">
  <button class="subj-star-btn" id="star-gcse-dt" onclick="event.stopPropagation();toggleStar('gcse-dt','Design & Technology','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Design & Technology</div>
  <div class="subj-topics">Materials · Product design · Engineering</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-pe">
  <button class="subj-star-btn" id="star-gcse-pe" onclick="event.stopPropagation();toggleStar('gcse-pe','Physical Education','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / OCR</div>
  <div class="subj-title">Physical Education</div>
  <div class="subj-topics">Theory · Anatomy · Training · Performance</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-food">
  <button class="subj-star-btn" id="star-gcse-food" onclick="event.stopPropagation();toggleStar('gcse-food','Food Preparation & Nutrition','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel / WJEC</div>
  <div class="subj-title">Food Preparation & Nutrition</div>
  <div class="subj-topics">Nutrients · Cooking · Safety · Diet</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-tourism">
  <button class="subj-star-btn" id="star-gcse-tourism" onclick="event.stopPropagation();toggleStar('gcse-tourism','Travel & Tourism','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · Cambridge / OCR</div>
  <div class="subj-title">Travel & Tourism</div>
  <div class="subj-topics">Industry · Destinations · Customer service</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-enterprise">
  <button class="subj-star-btn" id="star-gcse-enterprise" onclick="event.stopPropagation();toggleStar('gcse-enterprise','Enterprise','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Cambridge</div>
  <div class="subj-title">Enterprise</div>
  <div class="subj-topics">Business planning · Marketing · Finance · Innovation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-envman">
  <button class="subj-star-btn" id="star-gcse-envman" onclick="event.stopPropagation();toggleStar('gcse-envman','Environmental Management','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · Cambridge</div>
  <div class="subj-title">Environmental Management</div>
  <div class="subj-topics">Ecosystems · Resources · Climate · Sustainability</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-textiles">
  <button class="subj-star-btn" id="star-gcse-textiles" onclick="event.stopPropagation();toggleStar('gcse-textiles','Textiles','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel</div>
  <div class="subj-title">Textiles</div>
  <div class="subj-topics">Design · Construction · Materials · Fashion</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="gcse" id="sc-gcse-product-design">
  <button class="subj-star-btn" id="star-gcse-product-design" onclick="event.stopPropagation();toggleStar('gcse-product-design','Product Design','GCSE','gcse')" title="Star this subject">☆</button>
  <div class="subj-curric">GCSE · AQA / Edexcel</div>
  <div class="subj-title">Product Design</div>
  <div class="subj-topics">Design process · Materials · Manufacturing · CAD</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-maths">
  <button class="subj-star-btn" id="star-igcse-maths" onclick="event.stopPropagation();toggleStar('igcse-maths','Mathematics','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0580 / Edexcel 4MA1</div>
  <div class="subj-title">Mathematics</div>
  <div class="subj-topics">Number · Algebra · Geometry · Statistics · Trigonometry · Coordinate geometry</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-addmaths">
  <button class="subj-star-btn" id="star-igcse-addmaths" onclick="event.stopPropagation();toggleStar('igcse-addmaths','Additional Mathematics','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0606</div>
  <div class="subj-title">Additional Mathematics</div>
  <div class="subj-topics">Trigonometry · Calculus · Coordinate geometry · Algebra</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-stats">
  <button class="subj-star-btn" id="star-igcse-stats" onclick="event.stopPropagation();toggleStar('igcse-stats','Statistics','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0522</div>
  <div class="subj-title">Statistics</div>
  <div class="subj-topics">Data · Probability · Distributions · Hypothesis</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-bio">
  <button class="subj-star-btn" id="star-igcse-bio" onclick="event.stopPropagation();toggleStar('igcse-bio','Biology','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0610</div>
  <div class="subj-title">Biology</div>
  <div class="subj-topics">Living organisms · Cells · Nutrition · Respiration · Reproduction · Ecology</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-chem">
  <button class="subj-star-btn" id="star-igcse-chem" onclick="event.stopPropagation();toggleStar('igcse-chem','Chemistry','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0620</div>
  <div class="subj-title">Chemistry</div>
  <div class="subj-topics">States of matter · Bonding · Acids · Organic · Electrolysis · Rates</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-phys">
  <button class="subj-star-btn" id="star-igcse-phys" onclick="event.stopPropagation();toggleStar('igcse-phys','Physics','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0625</div>
  <div class="subj-title">Physics</div>
  <div class="subj-topics">Motion · Forces · Energy · Waves · Electricity · Atomic physics</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-combined">
  <button class="subj-star-btn" id="star-igcse-combined" onclick="event.stopPropagation();toggleStar('igcse-combined','Combined Science','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0653</div>
  <div class="subj-title">Combined Science</div>
  <div class="subj-topics">Biology + Chemistry + Physics core concepts</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-envman">
  <button class="subj-star-btn" id="star-igcse-envman" onclick="event.stopPropagation();toggleStar('igcse-envman','Environmental Management','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0680</div>
  <div class="subj-title">Environmental Management</div>
  <div class="subj-topics">Ecosystems · Resources · Climate · Management strategies</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-cs">
  <button class="subj-star-btn" id="star-igcse-cs" onclick="event.stopPropagation();toggleStar('igcse-cs','Computer Science','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0478</div>
  <div class="subj-title">Computer Science</div>
  <div class="subj-topics">Algorithms · Data structures · Networks · Programming · Ethics</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-ict">
  <button class="subj-star-btn" id="star-igcse-ict" onclick="event.stopPropagation();toggleStar('igcse-ict','ICT','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0417</div>
  <div class="subj-title">ICT</div>
  <div class="subj-topics">Hardware · Software · Networks · Data handling · Communication</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-englang">
  <button class="subj-star-btn" id="star-igcse-englang" onclick="event.stopPropagation();toggleStar('igcse-englang','English Language','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0500 / 0990</div>
  <div class="subj-title">English Language</div>
  <div class="subj-topics">Reading · Writing · Summary · Directed writing · Spoken</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-englit">
  <button class="subj-star-btn" id="star-igcse-englit" onclick="event.stopPropagation();toggleStar('igcse-englit','English Literature','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0475</div>
  <div class="subj-title">English Literature</div>
  <div class="subj-topics">Poetry · Prose · Drama · Unseen · Comparison</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-french">
  <button class="subj-star-btn" id="star-igcse-french" onclick="event.stopPropagation();toggleStar('igcse-french','French','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0520</div>
  <div class="subj-title">French</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking · Grammar · Vocabulary</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-spanish">
  <button class="subj-star-btn" id="star-igcse-spanish" onclick="event.stopPropagation();toggleStar('igcse-spanish','Spanish','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0530</div>
  <div class="subj-title">Spanish</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking · Grammar</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-german">
  <button class="subj-star-btn" id="star-igcse-german" onclick="event.stopPropagation();toggleStar('igcse-german','German','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0525</div>
  <div class="subj-title">German</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking · Grammar</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-chinese">
  <button class="subj-star-btn" id="star-igcse-chinese" onclick="event.stopPropagation();toggleStar('igcse-chinese','Chinese (Mandarin)','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0547</div>
  <div class="subj-title">Chinese (Mandarin)</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-arabic">
  <button class="subj-star-btn" id="star-igcse-arabic" onclick="event.stopPropagation();toggleStar('igcse-arabic','Arabic','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0508</div>
  <div class="subj-title">Arabic</div>
  <div class="subj-topics">Reading · Writing · Listening · Speaking</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-hist">
  <button class="subj-star-btn" id="star-igcse-hist" onclick="event.stopPropagation();toggleStar('igcse-hist','History','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0470</div>
  <div class="subj-title">History</div>
  <div class="subj-topics">Source skills · Essay writing · Named periods (Cambridge or Edexcel)</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-geog">
  <button class="subj-star-btn" id="star-igcse-geog" onclick="event.stopPropagation();toggleStar('igcse-geog','Geography','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0460</div>
  <div class="subj-title">Geography</div>
  <div class="subj-topics">Physical · Human · Geographical skills · Case studies</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-econ">
  <button class="subj-star-btn" id="star-igcse-econ" onclick="event.stopPropagation();toggleStar('igcse-econ','Economics','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0455</div>
  <div class="subj-title">Economics</div>
  <div class="subj-topics">Microeconomics · Macroeconomics · International trade</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-business">
  <button class="subj-star-btn" id="star-igcse-business" onclick="event.stopPropagation();toggleStar('igcse-business','Business Studies','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0450</div>
  <div class="subj-title">Business Studies</div>
  <div class="subj-topics">Marketing · Operations · Finance · HR · Strategy</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-accounting">
  <button class="subj-star-btn" id="star-igcse-accounting" onclick="event.stopPropagation();toggleStar('igcse-accounting','Accounting','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0452</div>
  <div class="subj-title">Accounting</div>
  <div class="subj-topics">Financial statements · Ledgers · Ratios · Cash flow</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-sociology">
  <button class="subj-star-btn" id="star-igcse-sociology" onclick="event.stopPropagation();toggleStar('igcse-sociology','Sociology','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0495</div>
  <div class="subj-title">Sociology</div>
  <div class="subj-topics">Culture · Family · Education · Crime · Stratification</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-rs">
  <button class="subj-star-btn" id="star-igcse-rs" onclick="event.stopPropagation();toggleStar('igcse-rs','Religious Studies','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0490</div>
  <div class="subj-title">Religious Studies</div>
  <div class="subj-topics">Ethics · World religions · Philosophy</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-art">
  <button class="subj-star-btn" id="star-igcse-art" onclick="event.stopPropagation();toggleStar('igcse-art','Art & Design','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0400</div>
  <div class="subj-title">Art & Design</div>
  <div class="subj-topics">Studio practice · Critical studies · Portfolio</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-music">
  <button class="subj-star-btn" id="star-igcse-music" onclick="event.stopPropagation();toggleStar('igcse-music','Music','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0410</div>
  <div class="subj-title">Music</div>
  <div class="subj-topics">Performance · Composition · Listening</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-drama">
  <button class="subj-star-btn" id="star-igcse-drama" onclick="event.stopPropagation();toggleStar('igcse-drama','Drama','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0411</div>
  <div class="subj-title">Drama</div>
  <div class="subj-topics">Performance · Devising · Set texts</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-dt">
  <button class="subj-star-btn" id="star-igcse-dt" onclick="event.stopPropagation();toggleStar('igcse-dt','Design & Technology','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0445</div>
  <div class="subj-title">Design & Technology</div>
  <div class="subj-topics">Design process · Materials · Manufacture</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-marine">
  <button class="subj-star-btn" id="star-igcse-marine" onclick="event.stopPropagation();toggleStar('igcse-marine','Marine Science','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0697</div>
  <div class="subj-title">Marine Science</div>
  <div class="subj-topics">Oceans · Ecosystems · Climate · Resources</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-tourism">
  <button class="subj-star-btn" id="star-igcse-tourism" onclick="event.stopPropagation();toggleStar('igcse-tourism','Travel & Tourism','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0471</div>
  <div class="subj-title">Travel & Tourism</div>
  <div class="subj-topics">Industry · Destinations · Impacts · Customer service</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="igcse" id="sc-igcse-pe">
  <button class="subj-star-btn" id="star-igcse-pe" onclick="event.stopPropagation();toggleStar('igcse-pe','Physical Education','IGCSE','igcse')" title="Star this subject">☆</button>
  <div class="subj-curric">IGCSE · Cambridge 0413</div>
  <div class="subj-title">Physical Education</div>
  <div class="subj-topics">Theory · Physiology · Training · Skills analysis</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-maths">
  <button class="subj-star-btn" id="star-al-maths" onclick="event.stopPropagation();toggleStar('al-maths','Mathematics','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Mathematics</div>
  <div class="subj-topics">Pure · Statistics · Mechanics · Proof · Calculus</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-further-maths">
  <button class="subj-star-btn" id="star-al-further-maths" onclick="event.stopPropagation();toggleStar('al-further-maths','Further Mathematics','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Further Mathematics</div>
  <div class="subj-topics">Complex numbers · Matrices · Further mechanics · Further statistics</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-stats">
  <button class="subj-star-btn" id="star-al-stats" onclick="event.stopPropagation();toggleStar('al-stats','Statistics','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Statistics</div>
  <div class="subj-topics">Hypothesis testing · Distributions · Correlation · Regression</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-pure">
  <button class="subj-star-btn" id="star-al-pure" onclick="event.stopPropagation();toggleStar('al-pure','Pure Mathematics','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Pure Mathematics</div>
  <div class="subj-topics">Algebra · Trigonometry · Calculus · Proof · Vectors</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-mechanics">
  <button class="subj-star-btn" id="star-al-mechanics" onclick="event.stopPropagation();toggleStar('al-mechanics','Mechanics','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Mechanics</div>
  <div class="subj-topics">Kinematics · Forces · Momentum · Energy · Circular motion</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-bio">
  <button class="subj-star-btn" id="star-al-bio" onclick="event.stopPropagation();toggleStar('al-bio','Biology','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Biology</div>
  <div class="subj-topics">Biochemistry · Genetics · Ecology · Physiology · Immunology</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-chem">
  <button class="subj-star-btn" id="star-al-chem" onclick="event.stopPropagation();toggleStar('al-chem','Chemistry','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Chemistry</div>
  <div class="subj-topics">Physical · Inorganic · Organic · Kinetics · Thermodynamics</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-phys">
  <button class="subj-star-btn" id="star-al-phys" onclick="event.stopPropagation();toggleStar('al-phys','Physics','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Physics</div>
  <div class="subj-topics">Mechanics · Fields · Waves · Quantum · Nuclear · Thermal</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-envsc">
  <button class="subj-star-btn" id="star-al-envsc" onclick="event.stopPropagation();toggleStar('al-envsc','Environmental Science','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / OCR</div>
  <div class="subj-title">Environmental Science</div>
  <div class="subj-topics">Ecosystems · Climate · Pollution · Policy · Conservation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-geology">
  <button class="subj-star-btn" id="star-al-geology" onclick="event.stopPropagation();toggleStar('al-geology','Geology','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · OCR / AQA</div>
  <div class="subj-title">Geology</div>
  <div class="subj-topics">Plate tectonics · Rocks · Resources · Geological mapping</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-astro">
  <button class="subj-star-btn" id="star-al-astro" onclick="event.stopPropagation();toggleStar('al-astro','Astronomy','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · OCR</div>
  <div class="subj-title">Astronomy</div>
  <div class="subj-topics">Stellar physics · Cosmology · Telescopes · Spectroscopy</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-englang">
  <button class="subj-star-btn" id="star-al-englang" onclick="event.stopPropagation();toggleStar('al-englang','English Language','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">English Language</div>
  <div class="subj-topics">Discourse · Variation · Acquisition · Analysis · Writing</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-englit">
  <button class="subj-star-btn" id="star-al-englit" onclick="event.stopPropagation();toggleStar('al-englit','English Literature','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">English Literature</div>
  <div class="subj-topics">Poetry · Prose · Drama · Unseen · Comparative essay</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-englanlit">
  <button class="subj-star-btn" id="star-al-englanlit" onclick="event.stopPropagation();toggleStar('al-englanlit','English Language & Literature','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / OCR</div>
  <div class="subj-title">English Language & Literature</div>
  <div class="subj-topics">Combined analysis · Creative writing · Comparative</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-french">
  <button class="subj-star-btn" id="star-al-french" onclick="event.stopPropagation();toggleStar('al-french','French','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">French</div>
  <div class="subj-topics">Themes · Grammar · Translation · Essay · Speaking</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-spanish">
  <button class="subj-star-btn" id="star-al-spanish" onclick="event.stopPropagation();toggleStar('al-spanish','Spanish','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Spanish</div>
  <div class="subj-topics">Themes · Grammar · Translation · Essay · Speaking</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-german">
  <button class="subj-star-btn" id="star-al-german" onclick="event.stopPropagation();toggleStar('al-german','German','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">German</div>
  <div class="subj-topics">Themes · Grammar · Translation · Essay · Speaking</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-chinese">
  <button class="subj-star-btn" id="star-al-chinese" onclick="event.stopPropagation();toggleStar('al-chinese','Chinese (Mandarin)','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel</div>
  <div class="subj-title">Chinese (Mandarin)</div>
  <div class="subj-topics">Themes · Grammar · Translation · Essay · Speaking</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-latin">
  <button class="subj-star-btn" id="star-al-latin" onclick="event.stopPropagation();toggleStar('al-latin','Latin','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · OCR / AQA</div>
  <div class="subj-title">Latin</div>
  <div class="subj-topics">Translation · Prose composition · Literature · Roman history</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-greek">
  <button class="subj-star-btn" id="star-al-greek" onclick="event.stopPropagation();toggleStar('al-greek','Ancient Greek','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · OCR</div>
  <div class="subj-title">Ancient Greek</div>
  <div class="subj-topics">Translation · Literature · Myth · History</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-hist">
  <button class="subj-star-btn" id="star-al-hist" onclick="event.stopPropagation();toggleStar('al-hist','History','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">History</div>
  <div class="subj-topics">British · European · World history · Source evaluation · Essays</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-geog">
  <button class="subj-star-btn" id="star-al-geog" onclick="event.stopPropagation();toggleStar('al-geog','Geography','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Geography</div>
  <div class="subj-topics">Physical geography · Human geography · Fieldwork · Synoptic</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-econ">
  <button class="subj-star-btn" id="star-al-econ" onclick="event.stopPropagation();toggleStar('al-econ','Economics','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Economics</div>
  <div class="subj-topics">Micro · Macro · Markets · Policies · International</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-business">
  <button class="subj-star-btn" id="star-al-business" onclick="event.stopPropagation();toggleStar('al-business','Business','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Business</div>
  <div class="subj-topics">Strategy · Finance · Marketing · HR · Operations · Global</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-accounting">
  <button class="subj-star-btn" id="star-al-accounting" onclick="event.stopPropagation();toggleStar('al-accounting','Accounting','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / OCR / CCEA</div>
  <div class="subj-title">Accounting</div>
  <div class="subj-topics">Financial accounting · Management accounting · Analysis</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-psych">
  <button class="subj-star-btn" id="star-al-psych" onclick="event.stopPropagation();toggleStar('al-psych','Psychology','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Psychology</div>
  <div class="subj-topics">Social · Cognitive · Biological · Developmental · Abnormal</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-sociology">
  <button class="subj-star-btn" id="star-al-sociology" onclick="event.stopPropagation();toggleStar('al-sociology','Sociology','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / OCR</div>
  <div class="subj-title">Sociology</div>
  <div class="subj-topics">Stratification · Education · Families · Crime · Beliefs · Methods</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-politics">
  <button class="subj-star-btn" id="star-al-politics" onclick="event.stopPropagation();toggleStar('al-politics','Politics','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Politics</div>
  <div class="subj-topics">UK politics · Comparative · Political ideas · International</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-law">
  <button class="subj-star-btn" id="star-al-law" onclick="event.stopPropagation();toggleStar('al-law','Law','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / OCR / WJEC</div>
  <div class="subj-title">Law</div>
  <div class="subj-topics">Criminal · Contract · Tort · Constitutional · Human rights</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-philosophy">
  <button class="subj-star-btn" id="star-al-philosophy" onclick="event.stopPropagation();toggleStar('al-philosophy','Philosophy','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / OCR / Edexcel</div>
  <div class="subj-title">Philosophy</div>
  <div class="subj-topics">Epistemology · Ethics · Metaphysics · Philosophy of mind</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-rs">
  <button class="subj-star-btn" id="star-al-rs" onclick="event.stopPropagation();toggleStar('al-rs','Religious Studies','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / OCR / Edexcel</div>
  <div class="subj-title">Religious Studies</div>
  <div class="subj-topics">Philosophy of religion · Ethics · Theology · Comparisons</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-classics">
  <button class="subj-star-btn" id="star-al-classics" onclick="event.stopPropagation();toggleStar('al-classics','Classical Civilisation','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · OCR</div>
  <div class="subj-title">Classical Civilisation</div>
  <div class="subj-topics">Greece · Rome · Literature · Myth · Archaeology · Art</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-art">
  <button class="subj-star-btn" id="star-al-art" onclick="event.stopPropagation();toggleStar('al-art','Art & Design','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Art & Design</div>
  <div class="subj-topics">Fine art · Graphic design · Photography · Portfolio</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-photo">
  <button class="subj-star-btn" id="star-al-photo" onclick="event.stopPropagation();toggleStar('al-photo','Photography','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Photography</div>
  <div class="subj-topics">Concept · Technique · Darkroom · Digital · Critical studies</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-music">
  <button class="subj-star-btn" id="star-al-music" onclick="event.stopPropagation();toggleStar('al-music','Music','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Music</div>
  <div class="subj-topics">Performance · Composition · Analysis · History</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-music-tech">
  <button class="subj-star-btn" id="star-al-music-tech" onclick="event.stopPropagation();toggleStar('al-music-tech','Music Technology','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel</div>
  <div class="subj-title">Music Technology</div>
  <div class="subj-topics">Production · DAW · Acoustics · Analysis</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-drama">
  <button class="subj-star-btn" id="star-al-drama" onclick="event.stopPropagation();toggleStar('al-drama','Drama & Theatre Studies','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Drama & Theatre Studies</div>
  <div class="subj-topics">Performance · Devising · Set texts · Theory</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-dance">
  <button class="subj-star-btn" id="star-al-dance" onclick="event.stopPropagation();toggleStar('al-dance','Dance','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel</div>
  <div class="subj-title">Dance</div>
  <div class="subj-topics">Performance · Choreography · Critical appreciation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-film">
  <button class="subj-star-btn" id="star-al-film" onclick="event.stopPropagation();toggleStar('al-film','Film Studies','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Eduqas</div>
  <div class="subj-title">Film Studies</div>
  <div class="subj-topics">Film language · Context · British film · World cinema</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-media">
  <button class="subj-star-btn" id="star-al-media" onclick="event.stopPropagation();toggleStar('al-media','Media Studies','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Media Studies</div>
  <div class="subj-topics">Representation · Industry · Audience · Language · Theory</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-cs">
  <button class="subj-star-btn" id="star-al-cs" onclick="event.stopPropagation();toggleStar('al-cs','Computer Science','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Computer Science</div>
  <div class="subj-topics">Algorithms · Programming · Systems · Networks · Theory</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-dt">
  <button class="subj-star-btn" id="star-al-dt" onclick="event.stopPropagation();toggleStar('al-dt','Design & Technology','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Design & Technology</div>
  <div class="subj-topics">Design process · Materials · Innovation · Commercial</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-pe">
  <button class="subj-star-btn" id="star-al-pe" onclick="event.stopPropagation();toggleStar('al-pe','Physical Education','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / OCR</div>
  <div class="subj-title">Physical Education</div>
  <div class="subj-topics">Anatomy · Physiology · Psychology · Sociology · Training</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-sports-sci">
  <button class="subj-star-btn" id="star-al-sports-sci" onclick="event.stopPropagation();toggleStar('al-sports-sci','Sports Science','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · Edexcel / AQA / OCR</div>
  <div class="subj-title">Sports Science</div>
  <div class="subj-topics">Performance analysis · Training · Biomechanics · Physiology</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-food">
  <button class="subj-star-btn" id="star-al-food" onclick="event.stopPropagation();toggleStar('al-food','Food Science & Nutrition','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · AQA / Edexcel / WJEC</div>
  <div class="subj-title">Food Science & Nutrition</div>
  <div class="subj-topics">Nutrients · Dietary planning · Food safety · Science</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="alevel" id="sc-al-health">
  <button class="subj-star-btn" id="star-al-health" onclick="event.stopPropagation();toggleStar('al-health','Health & Social Care','A-Level','alevel')" title="Star this subject">☆</button>
  <div class="subj-curric">A-Level · Edexcel / OCR / WJEC</div>
  <div class="subj-title">Health & Social Care</div>
  <div class="subj-topics">Values · Legislation · Anatomy · Service provision</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-lit-hl">
  <button class="subj-star-btn" id="star-ib-lit-hl" onclick="event.stopPropagation();toggleStar('ib-lit-hl','Language A: Literature HL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 1</div>
  <div class="subj-title">Language A: Literature HL</div>
  <div class="subj-topics">Literary analysis · World literature · Oral commentary · Essay</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-lit-sl">
  <button class="subj-star-btn" id="star-ib-lit-sl" onclick="event.stopPropagation();toggleStar('ib-lit-sl','Language A: Literature SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 1</div>
  <div class="subj-title">Language A: Literature SL</div>
  <div class="subj-topics">Literary analysis · World literature · Oral commentary</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-lanlit-hl">
  <button class="subj-star-btn" id="star-ib-lanlit-hl" onclick="event.stopPropagation();toggleStar('ib-lanlit-hl','Language A: Language & Literature HL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 1</div>
  <div class="subj-title">Language A: Language & Literature HL</div>
  <div class="subj-topics">Language use · Texts · Media · Oral work</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-lanlit-sl">
  <button class="subj-star-btn" id="star-ib-lanlit-sl" onclick="event.stopPropagation();toggleStar('ib-lanlit-sl','Language A: Language & Literature SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 1</div>
  <div class="subj-title">Language A: Language & Literature SL</div>
  <div class="subj-topics">Language use · Texts · Media · Oral work</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-french">
  <button class="subj-star-btn" id="star-ib-french" onclick="event.stopPropagation();toggleStar('ib-french','French B HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 2</div>
  <div class="subj-title">French B HL/SL</div>
  <div class="subj-topics">Themes · Grammar · Oral · Written · Cultural understanding</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-spanish">
  <button class="subj-star-btn" id="star-ib-spanish" onclick="event.stopPropagation();toggleStar('ib-spanish','Spanish B HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 2</div>
  <div class="subj-title">Spanish B HL/SL</div>
  <div class="subj-topics">Themes · Grammar · Oral · Written · Cultural understanding</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-german">
  <button class="subj-star-btn" id="star-ib-german" onclick="event.stopPropagation();toggleStar('ib-german','German B HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 2</div>
  <div class="subj-title">German B HL/SL</div>
  <div class="subj-topics">Themes · Grammar · Oral · Written · Cultural understanding</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-chinese">
  <button class="subj-star-btn" id="star-ib-chinese" onclick="event.stopPropagation();toggleStar('ib-chinese','Chinese B HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 2</div>
  <div class="subj-title">Chinese B HL/SL</div>
  <div class="subj-topics">Themes · Grammar · Oral · Written · Cultural understanding</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-arabic">
  <button class="subj-star-btn" id="star-ib-arabic" onclick="event.stopPropagation();toggleStar('ib-arabic','Arabic B HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 2</div>
  <div class="subj-title">Arabic B HL/SL</div>
  <div class="subj-topics">Themes · Grammar · Oral · Written · Cultural understanding</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-japanese">
  <button class="subj-star-btn" id="star-ib-japanese" onclick="event.stopPropagation();toggleStar('ib-japanese','Japanese B HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 2</div>
  <div class="subj-title">Japanese B HL/SL</div>
  <div class="subj-topics">Themes · Grammar · Oral · Written · Cultural understanding</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-spanish-ab">
  <button class="subj-star-btn" id="star-ib-spanish-ab" onclick="event.stopPropagation();toggleStar('ib-spanish-ab','Spanish Ab Initio','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 2</div>
  <div class="subj-title">Spanish Ab Initio</div>
  <div class="subj-topics">Beginner Spanish · Themes · Grammar · Basic oral</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-french-ab">
  <button class="subj-star-btn" id="star-ib-french-ab" onclick="event.stopPropagation();toggleStar('ib-french-ab','French Ab Initio','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 2</div>
  <div class="subj-title">French Ab Initio</div>
  <div class="subj-topics">Beginner French · Themes · Grammar · Basic oral</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-chinese-ab">
  <button class="subj-star-btn" id="star-ib-chinese-ab" onclick="event.stopPropagation();toggleStar('ib-chinese-ab','Chinese Ab Initio','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 2</div>
  <div class="subj-title">Chinese Ab Initio</div>
  <div class="subj-topics">Beginner Mandarin · Themes · Grammar · Basic oral</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-hist">
  <button class="subj-star-btn" id="star-ib-hist" onclick="event.stopPropagation();toggleStar('ib-hist','History HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 3</div>
  <div class="subj-title">History HL/SL</div>
  <div class="subj-topics">20th century · Case studies · Source analysis · Essay</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-geog">
  <button class="subj-star-btn" id="star-ib-geog" onclick="event.stopPropagation();toggleStar('ib-geog','Geography HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 3</div>
  <div class="subj-title">Geography HL/SL</div>
  <div class="subj-topics">Physical · Human · Fieldwork · Optional themes · Global</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-econ">
  <button class="subj-star-btn" id="star-ib-econ" onclick="event.stopPropagation();toggleStar('ib-econ','Economics HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 3</div>
  <div class="subj-title">Economics HL/SL</div>
  <div class="subj-topics">Microeconomics · Macroeconomics · International · Development</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-business">
  <button class="subj-star-btn" id="star-ib-business" onclick="event.stopPropagation();toggleStar('ib-business','Business Management HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 3</div>
  <div class="subj-title">Business Management HL/SL</div>
  <div class="subj-topics">Organisations · Finance · Marketing · Operations · HR</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-psych">
  <button class="subj-star-btn" id="star-ib-psych" onclick="event.stopPropagation();toggleStar('ib-psych','Psychology HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 3</div>
  <div class="subj-title">Psychology HL/SL</div>
  <div class="subj-topics">Biological · Cognitive · Sociocultural · Research methods</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-philosophy">
  <button class="subj-star-btn" id="star-ib-philosophy" onclick="event.stopPropagation();toggleStar('ib-philosophy','Philosophy HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 3</div>
  <div class="subj-title">Philosophy HL/SL</div>
  <div class="subj-topics">Core theme: Identity · Optional themes · HL extensions</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-global-politics">
  <button class="subj-star-btn" id="star-ib-global-politics" onclick="event.stopPropagation();toggleStar('ib-global-politics','Global Politics HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 3</div>
  <div class="subj-title">Global Politics HL/SL</div>
  <div class="subj-topics">Power · Human rights · Sovereignty · Development</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-anthropology">
  <button class="subj-star-btn" id="star-ib-anthropology" onclick="event.stopPropagation();toggleStar('ib-anthropology','Social & Cultural Anthropology HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 3</div>
  <div class="subj-title">Social & Cultural Anthropology HL/SL</div>
  <div class="subj-topics">Fieldwork · Culture · Society · Ethnography</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-ess">
  <button class="subj-star-btn" id="star-ib-ess" onclick="event.stopPropagation();toggleStar('ib-ess','Environmental Systems & Societies SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Groups 3/4</div>
  <div class="subj-title">Environmental Systems & Societies SL</div>
  <div class="subj-topics">Systems · Ecosystems · Climate · Conservation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-itgs">
  <button class="subj-star-btn" id="star-ib-itgs" onclick="event.stopPropagation();toggleStar('ib-itgs','ITGS SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 3</div>
  <div class="subj-title">ITGS SL</div>
  <div class="subj-topics">IT systems · Social impact · Applications · Ethics</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-bio">
  <button class="subj-star-btn" id="star-ib-bio" onclick="event.stopPropagation();toggleStar('ib-bio','Biology HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 4</div>
  <div class="subj-title">Biology HL/SL</div>
  <div class="subj-topics">Cells · Molecular · Genetics · Ecology · Physiology · Evolution</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-chem">
  <button class="subj-star-btn" id="star-ib-chem" onclick="event.stopPropagation();toggleStar('ib-chem','Chemistry HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 4</div>
  <div class="subj-title">Chemistry HL/SL</div>
  <div class="subj-topics">Stoichiometry · Bonding · Energetics · Kinetics · Redox · Organic</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-phys">
  <button class="subj-star-btn" id="star-ib-phys" onclick="event.stopPropagation();toggleStar('ib-phys','Physics HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 4</div>
  <div class="subj-title">Physics HL/SL</div>
  <div class="subj-topics">Mechanics · Waves · Fields · Quantum · Nuclear · Relativity</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-cs">
  <button class="subj-star-btn" id="star-ib-cs" onclick="event.stopPropagation();toggleStar('ib-cs','Computer Science HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 4</div>
  <div class="subj-title">Computer Science HL/SL</div>
  <div class="subj-topics">Algorithms · OOP · Networks · Databases · Computational thinking</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-design-tech">
  <button class="subj-star-btn" id="star-ib-design-tech" onclick="event.stopPropagation();toggleStar('ib-design-tech','Design Technology HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 4</div>
  <div class="subj-title">Design Technology HL/SL</div>
  <div class="subj-topics">Design cycle · Materials · Innovation · Evaluation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-sehs">
  <button class="subj-star-btn" id="star-ib-sehs" onclick="event.stopPropagation();toggleStar('ib-sehs','Sports, Exercise & Health Science HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 4</div>
  <div class="subj-title">Sports, Exercise & Health Science HL/SL</div>
  <div class="subj-topics">Anatomy · Physiology · Nutrition · Psychology · Research</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-math-aa-hl">
  <button class="subj-star-btn" id="star-ib-math-aa-hl" onclick="event.stopPropagation();toggleStar('ib-math-aa-hl','Mathematics AA HL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 5</div>
  <div class="subj-title">Mathematics AA HL</div>
  <div class="subj-topics">Analysis & Approaches — Proof · Calculus · Statistics · Complex numbers</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-math-aa-sl">
  <button class="subj-star-btn" id="star-ib-math-aa-sl" onclick="event.stopPropagation();toggleStar('ib-math-aa-sl','Mathematics AA SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 5</div>
  <div class="subj-title">Mathematics AA SL</div>
  <div class="subj-topics">Analysis & Approaches — Functions · Calculus · Trigonometry · Statistics</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-math-ai-hl">
  <button class="subj-star-btn" id="star-ib-math-ai-hl" onclick="event.stopPropagation();toggleStar('ib-math-ai-hl','Mathematics AI HL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 5</div>
  <div class="subj-title">Mathematics AI HL</div>
  <div class="subj-topics">Applications — Statistics · Calculus · Modelling · Finance · Networks</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-math-ai-sl">
  <button class="subj-star-btn" id="star-ib-math-ai-sl" onclick="event.stopPropagation();toggleStar('ib-math-ai-sl','Mathematics AI SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 5</div>
  <div class="subj-title">Mathematics AI SL</div>
  <div class="subj-topics">Applications — Statistics · Functions · Finance · Modelling</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-visual-arts">
  <button class="subj-star-btn" id="star-ib-visual-arts" onclick="event.stopPropagation();toggleStar('ib-visual-arts','Visual Arts HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 6</div>
  <div class="subj-title">Visual Arts HL/SL</div>
  <div class="subj-topics">Exhibition · Process · Comparative study · Studio practice</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-music">
  <button class="subj-star-btn" id="star-ib-music" onclick="event.stopPropagation();toggleStar('ib-music','Music HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 6</div>
  <div class="subj-title">Music HL/SL</div>
  <div class="subj-topics">Listening · Creating · Performing · Musical perception</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-theatre">
  <button class="subj-star-btn" id="star-ib-theatre" onclick="event.stopPropagation();toggleStar('ib-theatre','Theatre HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 6</div>
  <div class="subj-title">Theatre HL/SL</div>
  <div class="subj-topics">Devising · Research · Director notebook · Performance</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-dance">
  <button class="subj-star-btn" id="star-ib-dance" onclick="event.stopPropagation();toggleStar('ib-dance','Dance HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 6</div>
  <div class="subj-title">Dance HL/SL</div>
  <div class="subj-topics">Composition · Contextual · Performance</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-film">
  <button class="subj-star-btn" id="star-ib-film" onclick="event.stopPropagation();toggleStar('ib-film','Film HL/SL','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Group 6</div>
  <div class="subj-title">Film HL/SL</div>
  <div class="subj-topics">Textual analysis · Film production · Portfolio</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-tok">
  <button class="subj-star-btn" id="star-ib-tok" onclick="event.stopPropagation();toggleStar('ib-tok','Theory of Knowledge (TOK)','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Core</div>
  <div class="subj-title">Theory of Knowledge (TOK)</div>
  <div class="subj-topics">Exhibition · Essay · Knowledge questions · 12 AOKs</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-ee">
  <button class="subj-star-btn" id="star-ib-ee" onclick="event.stopPropagation();toggleStar('ib-ee','Extended Essay (EE)','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Core</div>
  <div class="subj-title">Extended Essay (EE)</div>
  <div class="subj-topics">Independent research · 4000-word essay · Reflection</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-cas">
  <button class="subj-star-btn" id="star-ib-cas" onclick="event.stopPropagation();toggleStar('ib-cas','Creativity, Activity, Service (CAS)','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Core</div>
  <div class="subj-title">Creativity, Activity, Service (CAS)</div>
  <div class="subj-topics">Reflections · Projects · Portfolio · Three strands</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ib" id="sc-ib-ia">
  <button class="subj-star-btn" id="star-ib-ia" onclick="event.stopPropagation();toggleStar('ib-ia','Internal Assessment (IA) Guide','IB','ib')" title="Star this subject">☆</button>
  <div class="subj-curric">IB · IB Core</div>
  <div class="subj-title">Internal Assessment (IA) Guide</div>
  <div class="subj-topics">IA writing · Methodology · Analysis · Evaluation · Top tips</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-calc-ab">
  <button class="subj-star-btn" id="star-ap-calc-ab" onclick="event.stopPropagation();toggleStar('ap-calc-ab','Calculus AB','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Calculus AB</div>
  <div class="subj-topics">Limits · Derivatives · Integrals · FTC · Applications</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-calc-bc">
  <button class="subj-star-btn" id="star-ap-calc-bc" onclick="event.stopPropagation();toggleStar('ap-calc-bc','Calculus BC','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Calculus BC</div>
  <div class="subj-topics">AB topics + Series · Parametric · Polar · Advanced integration</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-stats">
  <button class="subj-star-btn" id="star-ap-stats" onclick="event.stopPropagation();toggleStar('ap-stats','Statistics','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Statistics</div>
  <div class="subj-topics">Exploring data · Collecting data · Probability · Inference</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-cs-a">
  <button class="subj-star-btn" id="star-ap-cs-a" onclick="event.stopPropagation();toggleStar('ap-cs-a','Computer Science A','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Computer Science A</div>
  <div class="subj-topics">Java · OOP · Algorithms · Data structures · 2D arrays</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-cs-principles">
  <button class="subj-star-btn" id="star-ap-cs-principles" onclick="event.stopPropagation();toggleStar('ap-cs-principles','Computer Science Principles','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Computer Science Principles</div>
  <div class="subj-topics">Digital information · Internet · Algorithms · Impact · Programming</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-precalc">
  <button class="subj-star-btn" id="star-ap-precalc" onclick="event.stopPropagation();toggleStar('ap-precalc','Precalculus','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Precalculus</div>
  <div class="subj-topics">Functions · Trigonometry · Polar · Complex · Vectors</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-bio">
  <button class="subj-star-btn" id="star-ap-bio" onclick="event.stopPropagation();toggleStar('ap-bio','Biology','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Biology</div>
  <div class="subj-topics">Evolution · Cells · Genetics · Ecology · Energy · Regulation</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-chem">
  <button class="subj-star-btn" id="star-ap-chem" onclick="event.stopPropagation();toggleStar('ap-chem','Chemistry','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Chemistry</div>
  <div class="subj-topics">Atoms · Bonding · IMF · Kinetics · Equilibrium · Thermodynamics</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-phys-1">
  <button class="subj-star-btn" id="star-ap-phys-1" onclick="event.stopPropagation();toggleStar('ap-phys-1','Physics 1: Algebra-Based','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Physics 1: Algebra-Based</div>
  <div class="subj-topics">Kinematics · Forces · Energy · Waves · Electricity · Rotation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-phys-2">
  <button class="subj-star-btn" id="star-ap-phys-2" onclick="event.stopPropagation();toggleStar('ap-phys-2','Physics 2: Algebra-Based','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Physics 2: Algebra-Based</div>
  <div class="subj-topics">Fluids · Thermodynamics · E&M · Optics · Quantum · Nuclear</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-phys-c-mech">
  <button class="subj-star-btn" id="star-ap-phys-c-mech" onclick="event.stopPropagation();toggleStar('ap-phys-c-mech','Physics C: Mechanics','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Physics C: Mechanics</div>
  <div class="subj-topics">Calculus-based kinematics · Forces · Energy · Rotation · Oscillations</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-phys-c-em">
  <button class="subj-star-btn" id="star-ap-phys-c-em" onclick="event.stopPropagation();toggleStar('ap-phys-c-em','Physics C: Electricity & Magnetism','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Physics C: Electricity & Magnetism</div>
  <div class="subj-topics">Electrostatics · Circuits · Magnetism · Induction · Maxwell</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-envsc">
  <button class="subj-star-btn" id="star-ap-envsc" onclick="event.stopPropagation();toggleStar('ap-envsc','Environmental Science','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Environmental Science</div>
  <div class="subj-topics">Ecosystems · Earth systems · Climate · Human impact · Solutions</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-world-hist">
  <button class="subj-star-btn" id="star-ap-world-hist" onclick="event.stopPropagation();toggleStar('ap-world-hist','World History: Modern','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">World History: Modern</div>
  <div class="subj-topics">1200–present · Trade · Empires · Revolutions · Globalisation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-euro-hist">
  <button class="subj-star-btn" id="star-ap-euro-hist" onclick="event.stopPropagation();toggleStar('ap-euro-hist','European History','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">European History</div>
  <div class="subj-topics">1450–present · Renaissance · Revolutions · WWI/II · Cold War</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-ush">
  <button class="subj-star-btn" id="star-ap-ush" onclick="event.stopPropagation();toggleStar('ap-ush','United States History','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">United States History</div>
  <div class="subj-topics">1491–present · Colonial · Civil War · 20th Century · DBQ</div>
  <span class="subj-has-notes-tag">✓ Notes ready</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-comp-gov">
  <button class="subj-star-btn" id="star-ap-comp-gov" onclick="event.stopPropagation();toggleStar('ap-comp-gov','Comparative Government & Politics','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Comparative Government & Politics</div>
  <div class="subj-topics">Regime types · Institutions · Political culture · Policy</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-us-gov">
  <button class="subj-star-btn" id="star-ap-us-gov" onclick="event.stopPropagation();toggleStar('ap-us-gov','US Government & Politics','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">US Government & Politics</div>
  <div class="subj-topics">Constitution · Congress · Presidency · Courts · Civil rights</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-human-geo">
  <button class="subj-star-btn" id="star-ap-human-geo" onclick="event.stopPropagation();toggleStar('ap-human-geo','Human Geography','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Human Geography</div>
  <div class="subj-topics">Population · Migration · Culture · Political · Agriculture · Urban</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-psych">
  <button class="subj-star-btn" id="star-ap-psych" onclick="event.stopPropagation();toggleStar('ap-psych','Psychology','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Psychology</div>
  <div class="subj-topics">Biological · Learning · Cognition · Development · Social · Disorders</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-macro">
  <button class="subj-star-btn" id="star-ap-macro" onclick="event.stopPropagation();toggleStar('ap-macro','Macroeconomics','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Macroeconomics</div>
  <div class="subj-topics">National income · Monetary policy · Fiscal policy · Trade · Growth</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-micro">
  <button class="subj-star-btn" id="star-ap-micro" onclick="event.stopPropagation();toggleStar('ap-micro','Microeconomics','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Microeconomics</div>
  <div class="subj-topics">Supply · Demand · Elasticity · Market failure · Firm behaviour</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-eng-lang">
  <button class="subj-star-btn" id="star-ap-eng-lang" onclick="event.stopPropagation();toggleStar('ap-eng-lang','English Language & Composition','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">English Language & Composition</div>
  <div class="subj-topics">Rhetorical analysis · Synthesis · Argument · Style</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-eng-lit">
  <button class="subj-star-btn" id="star-ap-eng-lit" onclick="event.stopPropagation();toggleStar('ap-eng-lit','English Literature & Composition','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">English Literature & Composition</div>
  <div class="subj-topics">Poetry · Prose · Drama · Comparison · Close reading</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-spanish">
  <button class="subj-star-btn" id="star-ap-spanish" onclick="event.stopPropagation();toggleStar('ap-spanish','Spanish Language & Culture','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Spanish Language & Culture</div>
  <div class="subj-topics">Interpersonal · Presentational · Interpretive · AP themes</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-french">
  <button class="subj-star-btn" id="star-ap-french" onclick="event.stopPropagation();toggleStar('ap-french','French Language & Culture','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">French Language & Culture</div>
  <div class="subj-topics">Interpersonal · Presentational · Interpretive · AP themes</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-german">
  <button class="subj-star-btn" id="star-ap-german" onclick="event.stopPropagation();toggleStar('ap-german','German Language & Culture','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">German Language & Culture</div>
  <div class="subj-topics">Interpersonal · Presentational · Interpretive · AP themes</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-chinese">
  <button class="subj-star-btn" id="star-ap-chinese" onclick="event.stopPropagation();toggleStar('ap-chinese','Chinese Language & Culture','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Chinese Language & Culture</div>
  <div class="subj-topics">Interpersonal · Presentational · Interpretive · AP themes</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-japanese">
  <button class="subj-star-btn" id="star-ap-japanese" onclick="event.stopPropagation();toggleStar('ap-japanese','Japanese Language & Culture','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Japanese Language & Culture</div>
  <div class="subj-topics">Interpersonal · Presentational · Interpretive · AP themes</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-latin">
  <button class="subj-star-btn" id="star-ap-latin" onclick="event.stopPropagation();toggleStar('ap-latin','Latin','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Latin</div>
  <div class="subj-topics">Translation · Analysis · Roman literature · Caesar · Vergil</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-art-2d">
  <button class="subj-star-btn" id="star-ap-art-2d" onclick="event.stopPropagation();toggleStar('ap-art-2d','Studio Art: 2-D Design','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Studio Art: 2-D Design</div>
  <div class="subj-topics">Portfolio · Process · Breadth · Concentration</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-art-3d">
  <button class="subj-star-btn" id="star-ap-art-3d" onclick="event.stopPropagation();toggleStar('ap-art-3d','Studio Art: 3-D Design','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Studio Art: 3-D Design</div>
  <div class="subj-topics">Portfolio · Sculpture · Process · Breadth</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-art-drawing">
  <button class="subj-star-btn" id="star-ap-art-drawing" onclick="event.stopPropagation();toggleStar('ap-art-drawing','Studio Art: Drawing','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Studio Art: Drawing</div>
  <div class="subj-topics">Portfolio · Drawing · Process · Breadth · Concentration</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-art-hist">
  <button class="subj-star-btn" id="star-ap-art-hist" onclick="event.stopPropagation();toggleStar('ap-art-hist','Art History','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Art History</div>
  <div class="subj-topics">Global art movements · Analysis · Context · Comparison</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-music-theory">
  <button class="subj-star-btn" id="star-ap-music-theory" onclick="event.stopPropagation();toggleStar('ap-music-theory','Music Theory','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Music Theory</div>
  <div class="subj-topics">Notation · Harmony · Ear training · Analysis · Composition</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-seminar">
  <button class="subj-star-btn" id="star-ap-seminar" onclick="event.stopPropagation();toggleStar('ap-seminar','Seminar','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Seminar</div>
  <div class="subj-topics">Research · Analysis · Argument · Team · Presentation</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
<div class="subj-card " data-c="ap" id="sc-ap-research">
  <button class="subj-star-btn" id="star-ap-research" onclick="event.stopPropagation();toggleStar('ap-research','Research','AP','ap')" title="Star this subject">☆</button>
  <div class="subj-curric">AP · College Board</div>
  <div class="subj-title">Research</div>
  <div class="subj-topics">Long-term research · Paper · Presentation · IRB process</div>
  <span class="subj-coming-tag">Notes coming soon</span>
</div>
</div>
            </div>
            <div id="notes-detail" class="notes-detail">
              <button class="notes-back-btn" onclick="closeSubject()">← Back to subjects</button>
              <div id="notes-detail-body"></div>
            </div>
          </div>

          <!-- PAST PAPERS -->
          <div class="fdash-panel" id="fdash-papers">
            <div class="papers-panel-title">Past Papers &amp; Mark Schemes</div>
            <div class="papers-panel-sub">Every past paper for every subject, with mark schemes directly linked. Select a curriculum below.</div>
            <div class="papers-tabs">
              <button class="papers-tab-btn on" onclick="switchPapers('gcse',this)">GCSE</button>
              <button class="papers-tab-btn" onclick="switchPapers('alevel',this)">A-Level</button>
              <button class="papers-tab-btn" onclick="switchPapers('ib',this)">IB</button>
              <button class="papers-tab-btn" onclick="switchPapers('ap',this)">AP</button>
              <button class="papers-tab-btn" onclick="switchPapers('igcse',this)">IGCSE</button>
            </div>
            <div id="papers-content-area"></div>
          </div>

          
<!-- SUBJECT LIBRARY PANEL -->
<div class="fdash-panel" id="fdash-subjects">
  
<div id="sublib-modal-overlay" class="sublib-modal-overlay">
  <div class="sublib-modal" id="sublib-modal" id="sm-color">
    <button class="sublib-modal-close" onclick="closeSubjectModal()">✕</button>
    <div id="sm-curriculum" class="sublib-modal-curr"></div>
    <div id="sm-title" class="sublib-modal-title"></div>
    <div id="sm-sub" class="sublib-modal-sub"></div>
    <div class="sublib-modal-section">
      <div class="sublib-modal-section-title">Note Status</div>
      <div id="sm-note-status"></div>
    </div>
    <div class="sublib-modal-section">
      <div class="sublib-modal-section-title">Access Content</div>
      <div class="sublib-modal-actions">
        <div class="sublib-modal-action" onclick="openSubjectNotes('notes')">
          <span class="sublib-modal-action-icon">📖</span>
          <div class="sublib-modal-action-text">
            <div class="sublib-modal-action-name">Revision Notes</div>
            <div class="sublib-modal-action-desc">Syllabus-aligned notes, diagrams, formulae and YouTube video links</div>
          </div>
          <span class="sublib-modal-action-arrow">→</span>
        </div>
        <div class="sublib-modal-action" onclick="openSubjectNotes('papers')">
          <span class="sublib-modal-action-icon">📄</span>
          <div class="sublib-modal-action-text">
            <div class="sublib-modal-action-name">Past Papers & Mark Schemes</div>
            <div class="sublib-modal-action-desc">Every past paper with linked mark schemes — ready to download</div>
          </div>
          <span class="sublib-modal-action-arrow">→</span>
        </div>
        <div class="sublib-modal-action" onclick="openSubjectNotes('practice')">
          <span class="sublib-modal-action-icon">✎</span>
          <div class="sublib-modal-action-text">
            <div class="sublib-modal-action-name">AI Practice Questions</div>
            <div class="sublib-modal-action-desc">Adaptive questions with AI marking and instant examiner-style feedback</div>
          </div>
          <span class="sublib-modal-action-arrow">→</span>
        </div>
        <div class="sublib-modal-action" onclick="openSubjectNotes('flashcards')">
          <span class="sublib-modal-action-icon">↺</span>
          <div class="sublib-modal-action-text">
            <div class="sublib-modal-action-name">Flashcard Deck</div>
            <div class="sublib-modal-action-desc">Spaced repetition cards for key definitions, formulae and concepts</div>
          </div>
          <span class="sublib-modal-action-arrow">→</span>
        </div>
      </div>
    </div>
  </div>
</div>
  <div class="sublib-wrap">
    <div class="sublib-header">
      <div class="sublib-header-top">
        <div>
          <div class="sublib-title">Subject <span>Library</span></div>
          <div class="sublib-stats">247 SUBJECTS · 5 CURRICULA · GCSE · IGCSE · A-LEVEL · IB · AP</div>
        </div>
        <div class="sublib-search-wrap">
          <span class="sublib-search-icon">🔍</span>
          <input class="sublib-search" id="sublib-search" type="text" placeholder="Search subjects...">
        </div>
      </div>
      <div class="sublib-curr-tabs">
        <button class="sublib-curr-tab  active" 
  onclick="sublibSwitchCurr('gcse', this)"
  style="background:#1a6644;color:#fff;">
  🇬🇧 GCSE
</button><button class="sublib-curr-tab" 
  onclick="sublibSwitchCurr('igcse', this)"
  style="">
  🌐 IGCSE
</button><button class="sublib-curr-tab" 
  onclick="sublibSwitchCurr('a_level', this)"
  style="">
  🎓 A-Level
</button><button class="sublib-curr-tab" 
  onclick="sublibSwitchCurr('ib', this)"
  style="">
  🌏 IB
</button><button class="sublib-curr-tab" 
  onclick="sublibSwitchCurr('ap', this)"
  style="">
  🇺🇸 AP
</button>
      </div>
    </div>
    <div class="sublib-body">
      <div class="sublib-curriculum  active" id="sublib-curr-gcse">
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📐</span>
      <span class="sublib-cat-name">Mathematics</span>
      <span class="sublib-cat-count">(3)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="gcse_mathematics"
           data-subject="Mathematics"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Mathematics', 'Mathematics', '#1a6644')">
        <div class="sublib-card-subject">Mathematics</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Mathematics', 'Mathematics', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_statistics"
           data-subject="Statistics"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Statistics', 'Mathematics', '#1a6644')">
        <div class="sublib-card-subject">Statistics</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Statistics', 'Mathematics', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_additional_mathematics"
           data-subject="Additional Mathematics"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Additional Mathematics', 'Mathematics', '#1a6644')">
        <div class="sublib-card-subject">Additional Mathematics</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Additional Mathematics', 'Mathematics', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🔬</span>
      <span class="sublib-cat-name">Sciences</span>
      <span class="sublib-cat-count">(7)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="gcse_biology"
           data-subject="Biology"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Biology', 'Sciences', '#1a6644')">
        <div class="sublib-card-subject">Biology</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Biology', 'Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_chemistry"
           data-subject="Chemistry"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Chemistry', 'Sciences', '#1a6644')">
        <div class="sublib-card-subject">Chemistry</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Chemistry', 'Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_physics"
           data-subject="Physics"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Physics', 'Sciences', '#1a6644')">
        <div class="sublib-card-subject">Physics</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Physics', 'Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_combined_science__trilogy"
           data-subject="Combined Science (Trilogy)"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Combined Science (Trilogy)', 'Sciences', '#1a6644')">
        <div class="sublib-card-subject">Combined Science (Trilogy)</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Combined Science (Trilogy)', 'Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_combined_science__synergy"
           data-subject="Combined Science (Synergy)"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Combined Science (Synergy)', 'Sciences', '#1a6644')">
        <div class="sublib-card-subject">Combined Science (Synergy)</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Combined Science (Synergy)', 'Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_environmental_science"
           data-subject="Environmental Science"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Environmental Science', 'Sciences', '#1a6644')">
        <div class="sublib-card-subject">Environmental Science</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Environmental Science', 'Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_astronomy"
           data-subject="Astronomy"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Astronomy', 'Sciences', '#1a6644')">
        <div class="sublib-card-subject">Astronomy</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Astronomy', 'Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📖</span>
      <span class="sublib-cat-name">English & Languages</span>
      <span class="sublib-cat-count">(11)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="gcse_english_language"
           data-subject="English Language"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'English Language', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">English Language</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'English Language', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_english_literature"
           data-subject="English Literature"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'English Literature', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">English Literature</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'English Literature', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_french"
           data-subject="French"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'French', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">French</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'French', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_spanish"
           data-subject="Spanish"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Spanish', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">Spanish</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Spanish', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_german"
           data-subject="German"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'German', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">German</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'German', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_mandarin_chinese"
           data-subject="Mandarin Chinese"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Mandarin Chinese', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">Mandarin Chinese</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Mandarin Chinese', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_arabic"
           data-subject="Arabic"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Arabic', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">Arabic</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Arabic', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_latin"
           data-subject="Latin"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Latin', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">Latin</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Latin', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_italian"
           data-subject="Italian"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Italian', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">Italian</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Italian', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_russian"
           data-subject="Russian"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Russian', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">Russian</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Russian', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_japanese"
           data-subject="Japanese"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Japanese', 'English & Languages', '#1a6644')">
        <div class="sublib-card-subject">Japanese</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Japanese', 'English & Languages', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🌍</span>
      <span class="sublib-cat-name">Humanities & Social Sciences</span>
      <span class="sublib-cat-count">(10)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="gcse_history"
           data-subject="History"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'History', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">History</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'History', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_geography"
           data-subject="Geography"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Geography', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">Geography</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Geography', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_economics"
           data-subject="Economics"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Economics', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">Economics</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Economics', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_business_studies"
           data-subject="Business Studies"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Business Studies', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">Business Studies</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Business Studies', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_psychology"
           data-subject="Psychology"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Psychology', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">Psychology</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Psychology', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_sociology"
           data-subject="Sociology"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Sociology', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">Sociology</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Sociology', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_religious_studies"
           data-subject="Religious Studies"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Religious Studies', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">Religious Studies</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Religious Studies', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_global_perspectives"
           data-subject="Global Perspectives"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Global Perspectives', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">Global Perspectives</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Global Perspectives', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_classical_civilisation"
           data-subject="Classical Civilisation"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Classical Civilisation', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">Classical Civilisation</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Classical Civilisation', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_ancient_history"
           data-subject="Ancient History"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Ancient History', 'Humanities & Social Sciences', '#1a6644')">
        <div class="sublib-card-subject">Ancient History</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Ancient History', 'Humanities & Social Sciences', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🎨</span>
      <span class="sublib-cat-name">Creative & Performing Arts</span>
      <span class="sublib-cat-count">(9)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="gcse_art___design"
           data-subject="Art & Design"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Art & Design', 'Creative & Performing Arts', '#1a6644')">
        <div class="sublib-card-subject">Art & Design</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Art & Design', 'Creative & Performing Arts', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_fine_art"
           data-subject="Fine Art"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Fine Art', 'Creative & Performing Arts', '#1a6644')">
        <div class="sublib-card-subject">Fine Art</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Fine Art', 'Creative & Performing Arts', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_graphic_design"
           data-subject="Graphic Design"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Graphic Design', 'Creative & Performing Arts', '#1a6644')">
        <div class="sublib-card-subject">Graphic Design</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Graphic Design', 'Creative & Performing Arts', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_photography"
           data-subject="Photography"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Photography', 'Creative & Performing Arts', '#1a6644')">
        <div class="sublib-card-subject">Photography</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Photography', 'Creative & Performing Arts', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_music"
           data-subject="Music"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Music', 'Creative & Performing Arts', '#1a6644')">
        <div class="sublib-card-subject">Music</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Music', 'Creative & Performing Arts', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_drama"
           data-subject="Drama"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Drama', 'Creative & Performing Arts', '#1a6644')">
        <div class="sublib-card-subject">Drama</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Drama', 'Creative & Performing Arts', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_dance"
           data-subject="Dance"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Dance', 'Creative & Performing Arts', '#1a6644')">
        <div class="sublib-card-subject">Dance</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Dance', 'Creative & Performing Arts', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_film_studies"
           data-subject="Film Studies"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Film Studies', 'Creative & Performing Arts', '#1a6644')">
        <div class="sublib-card-subject">Film Studies</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Film Studies', 'Creative & Performing Arts', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_media_studies"
           data-subject="Media Studies"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Media Studies', 'Creative & Performing Arts', '#1a6644')">
        <div class="sublib-card-subject">Media Studies</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Media Studies', 'Creative & Performing Arts', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">💻</span>
      <span class="sublib-cat-name">Technology & Computing</span>
      <span class="sublib-cat-count">(5)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="gcse_computer_science"
           data-subject="Computer Science"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Computer Science', 'Technology & Computing', '#1a6644')">
        <div class="sublib-card-subject">Computer Science</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Computer Science', 'Technology & Computing', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_ict"
           data-subject="ICT"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'ICT', 'Technology & Computing', '#1a6644')">
        <div class="sublib-card-subject">ICT</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'ICT', 'Technology & Computing', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_design___technology"
           data-subject="Design & Technology"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Design & Technology', 'Technology & Computing', '#1a6644')">
        <div class="sublib-card-subject">Design & Technology</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Design & Technology', 'Technology & Computing', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_electronics"
           data-subject="Electronics"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Electronics', 'Technology & Computing', '#1a6644')">
        <div class="sublib-card-subject">Electronics</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Electronics', 'Technology & Computing', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_engineering"
           data-subject="Engineering"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Engineering', 'Technology & Computing', '#1a6644')">
        <div class="sublib-card-subject">Engineering</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Engineering', 'Technology & Computing', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🛠️</span>
      <span class="sublib-cat-name">Applied & Vocational</span>
      <span class="sublib-cat-count">(7)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="gcse_physical_education"
           data-subject="Physical Education"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Physical Education', 'Applied & Vocational', '#1a6644')">
        <div class="sublib-card-subject">Physical Education</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Physical Education', 'Applied & Vocational', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_food_preparation___nutrition"
           data-subject="Food Preparation & Nutrition"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Food Preparation & Nutrition', 'Applied & Vocational', '#1a6644')">
        <div class="sublib-card-subject">Food Preparation & Nutrition</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Food Preparation & Nutrition', 'Applied & Vocational', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_textiles"
           data-subject="Textiles"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Textiles', 'Applied & Vocational', '#1a6644')">
        <div class="sublib-card-subject">Textiles</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Textiles', 'Applied & Vocational', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_product_design"
           data-subject="Product Design"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Product Design', 'Applied & Vocational', '#1a6644')">
        <div class="sublib-card-subject">Product Design</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Product Design', 'Applied & Vocational', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_travel___tourism"
           data-subject="Travel & Tourism"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Travel & Tourism', 'Applied & Vocational', '#1a6644')">
        <div class="sublib-card-subject">Travel & Tourism</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Travel & Tourism', 'Applied & Vocational', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_enterprise"
           data-subject="Enterprise"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Enterprise', 'Applied & Vocational', '#1a6644')">
        <div class="sublib-card-subject">Enterprise</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Enterprise', 'Applied & Vocational', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="gcse_hospitality"
           data-subject="Hospitality"
           data-curr="GCSE"
           style="--card-color:#1a6644"
           onclick="openSubjectModal('GCSE', 'Hospitality', 'Applied & Vocational', '#1a6644')">
        <div class="sublib-card-subject">Hospitality</div>
        <div class="sublib-card-meta">GCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('GCSE', 'Hospitality', 'Applied & Vocational', '#1a6644')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div><div class="sublib-empty">No subjects match your search.</div></div><div class="sublib-curriculum" id="sublib-curr-igcse">
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📐</span>
      <span class="sublib-cat-name">Mathematics</span>
      <span class="sublib-cat-count">(4)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="igcse_mathematics__0580"
           data-subject="Mathematics (0580)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Mathematics (0580)', 'Mathematics', '#1a3a6b')">
        <div class="sublib-card-subject">Mathematics (0580)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Mathematics (0580)', 'Mathematics', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_additional_mathematics__0606"
           data-subject="Additional Mathematics (0606)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Additional Mathematics (0606)', 'Mathematics', '#1a3a6b')">
        <div class="sublib-card-subject">Additional Mathematics (0606)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Additional Mathematics (0606)', 'Mathematics', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_statistics__0653"
           data-subject="Statistics (0653)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Statistics (0653)', 'Mathematics', '#1a3a6b')">
        <div class="sublib-card-subject">Statistics (0653)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Statistics (0653)', 'Mathematics', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_international_mathematics__0607"
           data-subject="International Mathematics (0607)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'International Mathematics (0607)', 'Mathematics', '#1a3a6b')">
        <div class="sublib-card-subject">International Mathematics (0607)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'International Mathematics (0607)', 'Mathematics', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🔬</span>
      <span class="sublib-cat-name">Sciences</span>
      <span class="sublib-cat-count">(7)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="igcse_biology__0610"
           data-subject="Biology (0610)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Biology (0610)', 'Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Biology (0610)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Biology (0610)', 'Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_chemistry__0620"
           data-subject="Chemistry (0620)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Chemistry (0620)', 'Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Chemistry (0620)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Chemistry (0620)', 'Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_physics__0625"
           data-subject="Physics (0625)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Physics (0625)', 'Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Physics (0625)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Physics (0625)', 'Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_combined_science__0653"
           data-subject="Combined Science (0653)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Combined Science (0653)', 'Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Combined Science (0653)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Combined Science (0653)', 'Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_environmental_management__0680"
           data-subject="Environmental Management (0680)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Environmental Management (0680)', 'Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Environmental Management (0680)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Environmental Management (0680)', 'Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_marine_science__0697"
           data-subject="Marine Science (0697)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Marine Science (0697)', 'Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Marine Science (0697)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Marine Science (0697)', 'Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_astronomy"
           data-subject="Astronomy"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Astronomy', 'Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Astronomy</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Astronomy', 'Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📖</span>
      <span class="sublib-cat-name">English & Languages</span>
      <span class="sublib-cat-count">(14)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="igcse_first_language_english__0500"
           data-subject="First Language English (0500)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'First Language English (0500)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">First Language English (0500)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'First Language English (0500)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_second_language_english__0510"
           data-subject="Second Language English (0510)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Second Language English (0510)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Second Language English (0510)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Second Language English (0510)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_english_literature__0475"
           data-subject="English Literature (0475)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'English Literature (0475)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">English Literature (0475)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'English Literature (0475)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_french__0520"
           data-subject="French (0520)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'French (0520)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">French (0520)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'French (0520)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_spanish__0530"
           data-subject="Spanish (0530)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Spanish (0530)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Spanish (0530)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Spanish (0530)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_german__0525"
           data-subject="German (0525)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'German (0525)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">German (0525)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'German (0525)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_mandarin_chinese__0547"
           data-subject="Mandarin Chinese (0547)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Mandarin Chinese (0547)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Mandarin Chinese (0547)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Mandarin Chinese (0547)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_arabic__0508"
           data-subject="Arabic (0508)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Arabic (0508)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Arabic (0508)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Arabic (0508)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_latin__0480"
           data-subject="Latin (0480)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Latin (0480)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Latin (0480)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Latin (0480)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_italian__0535"
           data-subject="Italian (0535)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Italian (0535)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Italian (0535)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Italian (0535)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_portuguese__0547"
           data-subject="Portuguese (0547)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Portuguese (0547)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Portuguese (0547)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Portuguese (0547)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_japanese__0519"
           data-subject="Japanese (0519)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Japanese (0519)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Japanese (0519)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Japanese (0519)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_russian__0516"
           data-subject="Russian (0516)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Russian (0516)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Russian (0516)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Russian (0516)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_hindi__0549"
           data-subject="Hindi (0549)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Hindi (0549)', 'English & Languages', '#1a3a6b')">
        <div class="sublib-card-subject">Hindi (0549)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Hindi (0549)', 'English & Languages', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🌍</span>
      <span class="sublib-cat-name">Humanities & Social Sciences</span>
      <span class="sublib-cat-count">(10)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="igcse_history__0470"
           data-subject="History (0470)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'History (0470)', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">History (0470)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'History (0470)', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_geography__0460"
           data-subject="Geography (0460)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Geography (0460)', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Geography (0460)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Geography (0460)', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_economics__0455"
           data-subject="Economics (0455)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Economics (0455)', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Economics (0455)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Economics (0455)', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_business_studies__0450"
           data-subject="Business Studies (0450)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Business Studies (0450)', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Business Studies (0450)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Business Studies (0450)', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_accounting__0452"
           data-subject="Accounting (0452)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Accounting (0452)', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Accounting (0452)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Accounting (0452)', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_psychology__0478"
           data-subject="Psychology (0478)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Psychology (0478)', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Psychology (0478)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Psychology (0478)', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_sociology__0495"
           data-subject="Sociology (0495)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Sociology (0495)', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Sociology (0495)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Sociology (0495)', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_global_perspectives__0457"
           data-subject="Global Perspectives (0457)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Global Perspectives (0457)', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Global Perspectives (0457)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Global Perspectives (0457)', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_travel___tourism__0471"
           data-subject="Travel & Tourism (0471)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Travel & Tourism (0471)', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Travel & Tourism (0471)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Travel & Tourism (0471)', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_classical_studies"
           data-subject="Classical Studies"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Classical Studies', 'Humanities & Social Sciences', '#1a3a6b')">
        <div class="sublib-card-subject">Classical Studies</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Classical Studies', 'Humanities & Social Sciences', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🎨</span>
      <span class="sublib-cat-name">Creative & Performing Arts</span>
      <span class="sublib-cat-count">(5)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="igcse_art___design__0400"
           data-subject="Art & Design (0400)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Art & Design (0400)', 'Creative & Performing Arts', '#1a3a6b')">
        <div class="sublib-card-subject">Art & Design (0400)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Art & Design (0400)', 'Creative & Performing Arts', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_music__0410"
           data-subject="Music (0410)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Music (0410)', 'Creative & Performing Arts', '#1a3a6b')">
        <div class="sublib-card-subject">Music (0410)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Music (0410)', 'Creative & Performing Arts', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_drama__0411"
           data-subject="Drama (0411)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Drama (0411)', 'Creative & Performing Arts', '#1a3a6b')">
        <div class="sublib-card-subject">Drama (0411)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Drama (0411)', 'Creative & Performing Arts', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_design___technology__0445"
           data-subject="Design & Technology (0445)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Design & Technology (0445)', 'Creative & Performing Arts', '#1a3a6b')">
        <div class="sublib-card-subject">Design & Technology (0445)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Design & Technology (0445)', 'Creative & Performing Arts', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_graphic_design"
           data-subject="Graphic Design"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Graphic Design', 'Creative & Performing Arts', '#1a3a6b')">
        <div class="sublib-card-subject">Graphic Design</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Graphic Design', 'Creative & Performing Arts', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">💻</span>
      <span class="sublib-cat-name">Technology & Computing</span>
      <span class="sublib-cat-count">(4)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="igcse_computer_science__0478_0984"
           data-subject="Computer Science (0478/0984)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Computer Science (0478/0984)', 'Technology & Computing', '#1a3a6b')">
        <div class="sublib-card-subject">Computer Science (0478/0984)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Computer Science (0478/0984)', 'Technology & Computing', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_ict__0417"
           data-subject="ICT (0417)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'ICT (0417)', 'Technology & Computing', '#1a3a6b')">
        <div class="sublib-card-subject">ICT (0417)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'ICT (0417)', 'Technology & Computing', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_design___technology__0445"
           data-subject="Design & Technology (0445)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Design & Technology (0445)', 'Technology & Computing', '#1a3a6b')">
        <div class="sublib-card-subject">Design & Technology (0445)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Design & Technology (0445)', 'Technology & Computing', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_engineering__0469"
           data-subject="Engineering (0469)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Engineering (0469)', 'Technology & Computing', '#1a3a6b')">
        <div class="sublib-card-subject">Engineering (0469)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Engineering (0469)', 'Technology & Computing', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🛠️</span>
      <span class="sublib-cat-name">Applied & Vocational</span>
      <span class="sublib-cat-count">(4)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="igcse_physical_education__0413"
           data-subject="Physical Education (0413)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Physical Education (0413)', 'Applied & Vocational', '#1a3a6b')">
        <div class="sublib-card-subject">Physical Education (0413)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Physical Education (0413)', 'Applied & Vocational', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_food___nutrition__0648"
           data-subject="Food & Nutrition (0648)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Food & Nutrition (0648)', 'Applied & Vocational', '#1a3a6b')">
        <div class="sublib-card-subject">Food & Nutrition (0648)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Food & Nutrition (0648)', 'Applied & Vocational', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_enterprise__0454"
           data-subject="Enterprise (0454)"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Enterprise (0454)', 'Applied & Vocational', '#1a3a6b')">
        <div class="sublib-card-subject">Enterprise (0454)</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Enterprise (0454)', 'Applied & Vocational', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="igcse_environmental_management"
           data-subject="Environmental Management"
           data-curr="IGCSE"
           style="--card-color:#1a3a6b"
           onclick="openSubjectModal('IGCSE', 'Environmental Management', 'Applied & Vocational', '#1a3a6b')">
        <div class="sublib-card-subject">Environmental Management</div>
        <div class="sublib-card-meta">IGCSE</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IGCSE', 'Environmental Management', 'Applied & Vocational', '#1a3a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div><div class="sublib-empty">No subjects match your search.</div></div><div class="sublib-curriculum" id="sublib-curr-a_level">
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📐</span>
      <span class="sublib-cat-name">Mathematics</span>
      <span class="sublib-cat-count">(6)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="a_level_mathematics"
           data-subject="Mathematics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Mathematics', 'Mathematics', '#c8922a')">
        <div class="sublib-card-subject">Mathematics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Mathematics', 'Mathematics', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_further_mathematics"
           data-subject="Further Mathematics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Further Mathematics', 'Mathematics', '#c8922a')">
        <div class="sublib-card-subject">Further Mathematics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Further Mathematics', 'Mathematics', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_pure_mathematics"
           data-subject="Pure Mathematics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Pure Mathematics', 'Mathematics', '#c8922a')">
        <div class="sublib-card-subject">Pure Mathematics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Pure Mathematics', 'Mathematics', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_mechanics"
           data-subject="Mechanics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Mechanics', 'Mathematics', '#c8922a')">
        <div class="sublib-card-subject">Mechanics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Mechanics', 'Mathematics', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_statistics"
           data-subject="Statistics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Statistics', 'Mathematics', '#c8922a')">
        <div class="sublib-card-subject">Statistics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Statistics', 'Mathematics', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_decision_mathematics"
           data-subject="Decision Mathematics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Decision Mathematics', 'Mathematics', '#c8922a')">
        <div class="sublib-card-subject">Decision Mathematics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Decision Mathematics', 'Mathematics', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🔬</span>
      <span class="sublib-cat-name">Sciences</span>
      <span class="sublib-cat-count">(6)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="a_level_biology"
           data-subject="Biology"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Biology', 'Sciences', '#c8922a')">
        <div class="sublib-card-subject">Biology</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Biology', 'Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_chemistry"
           data-subject="Chemistry"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Chemistry', 'Sciences', '#c8922a')">
        <div class="sublib-card-subject">Chemistry</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Chemistry', 'Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_physics"
           data-subject="Physics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Physics', 'Sciences', '#c8922a')">
        <div class="sublib-card-subject">Physics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Physics', 'Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_environmental_science"
           data-subject="Environmental Science"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Environmental Science', 'Sciences', '#c8922a')">
        <div class="sublib-card-subject">Environmental Science</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Environmental Science', 'Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_geology"
           data-subject="Geology"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Geology', 'Sciences', '#c8922a')">
        <div class="sublib-card-subject">Geology</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Geology', 'Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_electronics"
           data-subject="Electronics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Electronics', 'Sciences', '#c8922a')">
        <div class="sublib-card-subject">Electronics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Electronics', 'Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📖</span>
      <span class="sublib-cat-name">English & Languages</span>
      <span class="sublib-cat-count">(12)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="a_level_english_language"
           data-subject="English Language"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'English Language', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">English Language</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'English Language', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_english_literature"
           data-subject="English Literature"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'English Literature', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">English Literature</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'English Literature', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_english_language___literature"
           data-subject="English Language & Literature"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'English Language & Literature', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">English Language & Literature</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'English Language & Literature', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_french"
           data-subject="French"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'French', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">French</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'French', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_spanish"
           data-subject="Spanish"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Spanish', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">Spanish</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Spanish', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_german"
           data-subject="German"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'German', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">German</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'German', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_mandarin_chinese"
           data-subject="Mandarin Chinese"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Mandarin Chinese', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">Mandarin Chinese</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Mandarin Chinese', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_arabic"
           data-subject="Arabic"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Arabic', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">Arabic</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Arabic', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_latin"
           data-subject="Latin"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Latin', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">Latin</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Latin', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_italian"
           data-subject="Italian"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Italian', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">Italian</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Italian', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_russian"
           data-subject="Russian"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Russian', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">Russian</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Russian', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_japanese"
           data-subject="Japanese"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Japanese', 'English & Languages', '#c8922a')">
        <div class="sublib-card-subject">Japanese</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Japanese', 'English & Languages', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🌍</span>
      <span class="sublib-cat-name">Humanities & Social Sciences</span>
      <span class="sublib-cat-count">(13)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="a_level_history"
           data-subject="History"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'History', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">History</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'History', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_geography"
           data-subject="Geography"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Geography', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Geography</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Geography', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_economics"
           data-subject="Economics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Economics', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Economics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Economics', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_business"
           data-subject="Business"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Business', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Business</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Business', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_accounting"
           data-subject="Accounting"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Accounting', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Accounting</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Accounting', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_psychology"
           data-subject="Psychology"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Psychology', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Psychology</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Psychology', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_sociology"
           data-subject="Sociology"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Sociology', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Sociology</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Sociology', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_politics"
           data-subject="Politics"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Politics', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Politics</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Politics', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_philosophy"
           data-subject="Philosophy"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Philosophy', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Philosophy</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Philosophy', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_religious_studies"
           data-subject="Religious Studies"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Religious Studies', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Religious Studies</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Religious Studies', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_law"
           data-subject="Law"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Law', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Law</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Law', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_classical_civilisation"
           data-subject="Classical Civilisation"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Classical Civilisation', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Classical Civilisation</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Classical Civilisation', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_ancient_history"
           data-subject="Ancient History"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Ancient History', 'Humanities & Social Sciences', '#c8922a')">
        <div class="sublib-card-subject">Ancient History</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Ancient History', 'Humanities & Social Sciences', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🎨</span>
      <span class="sublib-cat-name">Creative & Performing Arts</span>
      <span class="sublib-cat-count">(11)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="a_level_art___design"
           data-subject="Art & Design"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Art & Design', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Art & Design</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Art & Design', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_fine_art"
           data-subject="Fine Art"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Fine Art', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Fine Art</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Fine Art', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_photography"
           data-subject="Photography"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Photography', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Photography</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Photography', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_graphic_design"
           data-subject="Graphic Design"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Graphic Design', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Graphic Design</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Graphic Design', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_textiles"
           data-subject="Textiles"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Textiles', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Textiles</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Textiles', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_music"
           data-subject="Music"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Music', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Music</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Music', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_music_technology"
           data-subject="Music Technology"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Music Technology', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Music Technology</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Music Technology', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_drama___theatre_studies"
           data-subject="Drama & Theatre Studies"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Drama & Theatre Studies', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Drama & Theatre Studies</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Drama & Theatre Studies', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_dance"
           data-subject="Dance"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Dance', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Dance</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Dance', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_film_studies"
           data-subject="Film Studies"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Film Studies', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Film Studies</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Film Studies', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_media_studies"
           data-subject="Media Studies"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Media Studies', 'Creative & Performing Arts', '#c8922a')">
        <div class="sublib-card-subject">Media Studies</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Media Studies', 'Creative & Performing Arts', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">💻</span>
      <span class="sublib-cat-name">Technology & Computing</span>
      <span class="sublib-cat-count">(5)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="a_level_computer_science"
           data-subject="Computer Science"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Computer Science', 'Technology & Computing', '#c8922a')">
        <div class="sublib-card-subject">Computer Science</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Computer Science', 'Technology & Computing', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_ict"
           data-subject="ICT"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'ICT', 'Technology & Computing', '#c8922a')">
        <div class="sublib-card-subject">ICT</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'ICT', 'Technology & Computing', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_design___technology"
           data-subject="Design & Technology"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Design & Technology', 'Technology & Computing', '#c8922a')">
        <div class="sublib-card-subject">Design & Technology</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Design & Technology', 'Technology & Computing', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_product_design"
           data-subject="Product Design"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Product Design', 'Technology & Computing', '#c8922a')">
        <div class="sublib-card-subject">Product Design</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Product Design', 'Technology & Computing', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_engineering"
           data-subject="Engineering"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Engineering', 'Technology & Computing', '#c8922a')">
        <div class="sublib-card-subject">Engineering</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Engineering', 'Technology & Computing', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🛠️</span>
      <span class="sublib-cat-name">Applied & Vocational</span>
      <span class="sublib-cat-count">(4)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="a_level_physical_education"
           data-subject="Physical Education"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Physical Education', 'Applied & Vocational', '#c8922a')">
        <div class="sublib-card-subject">Physical Education</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Physical Education', 'Applied & Vocational', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_sports_science"
           data-subject="Sports Science"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Sports Science', 'Applied & Vocational', '#c8922a')">
        <div class="sublib-card-subject">Sports Science</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Sports Science', 'Applied & Vocational', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_food_technology"
           data-subject="Food Technology"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Food Technology', 'Applied & Vocational', '#c8922a')">
        <div class="sublib-card-subject">Food Technology</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Food Technology', 'Applied & Vocational', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="a_level_travel___tourism"
           data-subject="Travel & Tourism"
           data-curr="A-Level"
           style="--card-color:#c8922a"
           onclick="openSubjectModal('A-Level', 'Travel & Tourism', 'Applied & Vocational', '#c8922a')">
        <div class="sublib-card-subject">Travel & Tourism</div>
        <div class="sublib-card-meta">A-Level</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('A-Level', 'Travel & Tourism', 'Applied & Vocational', '#c8922a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div><div class="sublib-empty">No subjects match your search.</div></div><div class="sublib-curriculum" id="sublib-curr-ib">
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📖</span>
      <span class="sublib-cat-name">Group 1 — Studies in Language & Literature</span>
      <span class="sublib-cat-count">(8)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ib_language_a__literature__english"
           data-subject="Language A: Literature (English)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Language A: Literature (English)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
        <div class="sublib-card-subject">Language A: Literature (English)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Language A: Literature (English)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_language_a__literature__french"
           data-subject="Language A: Literature (French)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Language A: Literature (French)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
        <div class="sublib-card-subject">Language A: Literature (French)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Language A: Literature (French)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_language_a__literature__spanish"
           data-subject="Language A: Literature (Spanish)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Language A: Literature (Spanish)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
        <div class="sublib-card-subject">Language A: Literature (Spanish)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Language A: Literature (Spanish)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_language_a__literature__german"
           data-subject="Language A: Literature (German)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Language A: Literature (German)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
        <div class="sublib-card-subject">Language A: Literature (German)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Language A: Literature (German)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_language_a__literature__mandarin_chinese"
           data-subject="Language A: Literature (Mandarin Chinese)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Language A: Literature (Mandarin Chinese)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
        <div class="sublib-card-subject">Language A: Literature (Mandarin Chinese)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Language A: Literature (Mandarin Chinese)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_language_a__language___literature__english"
           data-subject="Language A: Language & Literature (English)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Language A: Language & Literature (English)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
        <div class="sublib-card-subject">Language A: Language & Literature (English)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Language A: Language & Literature (English)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_language_a__language___literature__spanish"
           data-subject="Language A: Language & Literature (Spanish)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Language A: Language & Literature (Spanish)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
        <div class="sublib-card-subject">Language A: Language & Literature (Spanish)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Language A: Language & Literature (Spanish)', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_literature___performance"
           data-subject="Literature & Performance"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Literature & Performance', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
        <div class="sublib-card-subject">Literature & Performance</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Literature & Performance', 'Group 1 — Studies in Language & Literature', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🗣️</span>
      <span class="sublib-cat-name">Group 2 — Language Acquisition</span>
      <span class="sublib-cat-count">(13)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ib_french_b"
           data-subject="French B"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'French B', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">French B</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'French B', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_spanish_b"
           data-subject="Spanish B"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Spanish B', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">Spanish B</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Spanish B', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_german_b"
           data-subject="German B"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'German B', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">German B</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'German B', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_mandarin_b"
           data-subject="Mandarin B"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Mandarin B', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">Mandarin B</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Mandarin B', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_arabic_b"
           data-subject="Arabic B"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Arabic B', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">Arabic B</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Arabic B', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_japanese_b"
           data-subject="Japanese B"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Japanese B', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">Japanese B</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Japanese B', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_french_ab_initio"
           data-subject="French Ab Initio"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'French Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">French Ab Initio</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'French Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_spanish_ab_initio"
           data-subject="Spanish Ab Initio"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Spanish Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">Spanish Ab Initio</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Spanish Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_german_ab_initio"
           data-subject="German Ab Initio"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'German Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">German Ab Initio</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'German Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_mandarin_ab_initio"
           data-subject="Mandarin Ab Initio"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Mandarin Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">Mandarin Ab Initio</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Mandarin Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_japanese_ab_initio"
           data-subject="Japanese Ab Initio"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Japanese Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">Japanese Ab Initio</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Japanese Ab Initio', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_latin"
           data-subject="Latin"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Latin', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">Latin</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Latin', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_classical_greek"
           data-subject="Classical Greek"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Classical Greek', 'Group 2 — Language Acquisition', '#8b1a1a')">
        <div class="sublib-card-subject">Classical Greek</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Classical Greek', 'Group 2 — Language Acquisition', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🌍</span>
      <span class="sublib-cat-name">Group 3 — Individuals & Societies</span>
      <span class="sublib-cat-count">(11)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ib_history"
           data-subject="History"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'History', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">History</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'History', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_geography"
           data-subject="Geography"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Geography', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">Geography</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Geography', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_economics"
           data-subject="Economics"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Economics', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">Economics</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Economics', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_business_management"
           data-subject="Business Management"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Business Management', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">Business Management</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Business Management', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_psychology"
           data-subject="Psychology"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Psychology', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">Psychology</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Psychology', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_philosophy"
           data-subject="Philosophy"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Philosophy', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">Philosophy</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Philosophy', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_social___cultural_anthropology"
           data-subject="Social & Cultural Anthropology"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Social & Cultural Anthropology', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">Social & Cultural Anthropology</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Social & Cultural Anthropology', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_environmental_systems___societies__ess"
           data-subject="Environmental Systems & Societies (ESS)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Environmental Systems & Societies (ESS)', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">Environmental Systems & Societies (ESS)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Environmental Systems & Societies (ESS)', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_global_politics"
           data-subject="Global Politics"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Global Politics', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">Global Politics</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Global Politics', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_world_religions"
           data-subject="World Religions"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'World Religions', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">World Religions</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'World Religions', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_information_technology_in_a_global_society__itgs"
           data-subject="Information Technology in a Global Society (ITGS)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Information Technology in a Global Society (ITGS)', 'Group 3 — Individuals & Societies', '#8b1a1a')">
        <div class="sublib-card-subject">Information Technology in a Global Society (ITGS)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Information Technology in a Global Society (ITGS)', 'Group 3 — Individuals & Societies', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🔬</span>
      <span class="sublib-cat-name">Group 4 — Sciences</span>
      <span class="sublib-cat-count">(7)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ib_biology"
           data-subject="Biology"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Biology', 'Group 4 — Sciences', '#8b1a1a')">
        <div class="sublib-card-subject">Biology</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Biology', 'Group 4 — Sciences', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_chemistry"
           data-subject="Chemistry"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Chemistry', 'Group 4 — Sciences', '#8b1a1a')">
        <div class="sublib-card-subject">Chemistry</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Chemistry', 'Group 4 — Sciences', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_physics"
           data-subject="Physics"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Physics', 'Group 4 — Sciences', '#8b1a1a')">
        <div class="sublib-card-subject">Physics</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Physics', 'Group 4 — Sciences', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_computer_science"
           data-subject="Computer Science"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Computer Science', 'Group 4 — Sciences', '#8b1a1a')">
        <div class="sublib-card-subject">Computer Science</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Computer Science', 'Group 4 — Sciences', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_design_technology"
           data-subject="Design Technology"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Design Technology', 'Group 4 — Sciences', '#8b1a1a')">
        <div class="sublib-card-subject">Design Technology</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Design Technology', 'Group 4 — Sciences', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_environmental_systems___societies__ess"
           data-subject="Environmental Systems & Societies (ESS)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Environmental Systems & Societies (ESS)', 'Group 4 — Sciences', '#8b1a1a')">
        <div class="sublib-card-subject">Environmental Systems & Societies (ESS)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Environmental Systems & Societies (ESS)', 'Group 4 — Sciences', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_sports__exercise___health_science"
           data-subject="Sports, Exercise & Health Science"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Sports, Exercise & Health Science', 'Group 4 — Sciences', '#8b1a1a')">
        <div class="sublib-card-subject">Sports, Exercise & Health Science</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Sports, Exercise & Health Science', 'Group 4 — Sciences', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📐</span>
      <span class="sublib-cat-name">Group 5 — Mathematics</span>
      <span class="sublib-cat-count">(4)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ib_mathematics__analysis___approaches__aa__hl"
           data-subject="Mathematics: Analysis & Approaches (AA) HL"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Mathematics: Analysis & Approaches (AA) HL', 'Group 5 — Mathematics', '#8b1a1a')">
        <div class="sublib-card-subject">Mathematics: Analysis & Approaches (AA) HL</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Mathematics: Analysis & Approaches (AA) HL', 'Group 5 — Mathematics', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_mathematics__analysis___approaches__aa__sl"
           data-subject="Mathematics: Analysis & Approaches (AA) SL"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Mathematics: Analysis & Approaches (AA) SL', 'Group 5 — Mathematics', '#8b1a1a')">
        <div class="sublib-card-subject">Mathematics: Analysis & Approaches (AA) SL</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Mathematics: Analysis & Approaches (AA) SL', 'Group 5 — Mathematics', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_mathematics__applications___interpretation__ai__hl"
           data-subject="Mathematics: Applications & Interpretation (AI) HL"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Mathematics: Applications & Interpretation (AI) HL', 'Group 5 — Mathematics', '#8b1a1a')">
        <div class="sublib-card-subject">Mathematics: Applications & Interpretation (AI) HL</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Mathematics: Applications & Interpretation (AI) HL', 'Group 5 — Mathematics', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_mathematics__applications___interpretation__ai__sl"
           data-subject="Mathematics: Applications & Interpretation (AI) SL"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Mathematics: Applications & Interpretation (AI) SL', 'Group 5 — Mathematics', '#8b1a1a')">
        <div class="sublib-card-subject">Mathematics: Applications & Interpretation (AI) SL</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Mathematics: Applications & Interpretation (AI) SL', 'Group 5 — Mathematics', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🎨</span>
      <span class="sublib-cat-name">Group 6 — The Arts</span>
      <span class="sublib-cat-count">(5)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ib_visual_arts"
           data-subject="Visual Arts"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Visual Arts', 'Group 6 — The Arts', '#8b1a1a')">
        <div class="sublib-card-subject">Visual Arts</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Visual Arts', 'Group 6 — The Arts', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_music"
           data-subject="Music"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Music', 'Group 6 — The Arts', '#8b1a1a')">
        <div class="sublib-card-subject">Music</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Music', 'Group 6 — The Arts', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_theatre"
           data-subject="Theatre"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Theatre', 'Group 6 — The Arts', '#8b1a1a')">
        <div class="sublib-card-subject">Theatre</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Theatre', 'Group 6 — The Arts', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_dance"
           data-subject="Dance"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Dance', 'Group 6 — The Arts', '#8b1a1a')">
        <div class="sublib-card-subject">Dance</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Dance', 'Group 6 — The Arts', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_film"
           data-subject="Film"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Film', 'Group 6 — The Arts', '#8b1a1a')">
        <div class="sublib-card-subject">Film</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Film', 'Group 6 — The Arts', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">⭐</span>
      <span class="sublib-cat-name">IB Core</span>
      <span class="sublib-cat-count">(3)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ib_theory_of_knowledge__tok"
           data-subject="Theory of Knowledge (TOK)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Theory of Knowledge (TOK)', 'IB Core', '#8b1a1a')">
        <div class="sublib-card-subject">Theory of Knowledge (TOK)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Theory of Knowledge (TOK)', 'IB Core', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_extended_essay__ee"
           data-subject="Extended Essay (EE)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Extended Essay (EE)', 'IB Core', '#8b1a1a')">
        <div class="sublib-card-subject">Extended Essay (EE)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Extended Essay (EE)', 'IB Core', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ib_creativity__activity__service__cas"
           data-subject="Creativity, Activity, Service (CAS)"
           data-curr="IB"
           style="--card-color:#8b1a1a"
           onclick="openSubjectModal('IB', 'Creativity, Activity, Service (CAS)', 'IB Core', '#8b1a1a')">
        <div class="sublib-card-subject">Creativity, Activity, Service (CAS)</div>
        <div class="sublib-card-meta">IB</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('IB', 'Creativity, Activity, Service (CAS)', 'IB Core', '#8b1a1a')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div><div class="sublib-empty">No subjects match your search.</div></div><div class="sublib-curriculum" id="sublib-curr-ap">
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📐</span>
      <span class="sublib-cat-name">Mathematics & Computing</span>
      <span class="sublib-cat-count">(6)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ap_calculus_ab"
           data-subject="Calculus AB"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Calculus AB', 'Mathematics & Computing', '#4a1a6b')">
        <div class="sublib-card-subject">Calculus AB</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Calculus AB', 'Mathematics & Computing', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_calculus_bc"
           data-subject="Calculus BC"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Calculus BC', 'Mathematics & Computing', '#4a1a6b')">
        <div class="sublib-card-subject">Calculus BC</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Calculus BC', 'Mathematics & Computing', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_statistics"
           data-subject="Statistics"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Statistics', 'Mathematics & Computing', '#4a1a6b')">
        <div class="sublib-card-subject">Statistics</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Statistics', 'Mathematics & Computing', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_precalculus"
           data-subject="Precalculus"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Precalculus', 'Mathematics & Computing', '#4a1a6b')">
        <div class="sublib-card-subject">Precalculus</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Precalculus', 'Mathematics & Computing', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_computer_science_a"
           data-subject="Computer Science A"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Computer Science A', 'Mathematics & Computing', '#4a1a6b')">
        <div class="sublib-card-subject">Computer Science A</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Computer Science A', 'Mathematics & Computing', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_computer_science_principles"
           data-subject="Computer Science Principles"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Computer Science Principles', 'Mathematics & Computing', '#4a1a6b')">
        <div class="sublib-card-subject">Computer Science Principles</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Computer Science Principles', 'Mathematics & Computing', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🔬</span>
      <span class="sublib-cat-name">Sciences</span>
      <span class="sublib-cat-count">(7)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ap_biology"
           data-subject="Biology"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Biology', 'Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Biology</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Biology', 'Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_chemistry"
           data-subject="Chemistry"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Chemistry', 'Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Chemistry</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Chemistry', 'Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_physics_1__algebra_based"
           data-subject="Physics 1: Algebra-Based"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Physics 1: Algebra-Based', 'Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Physics 1: Algebra-Based</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Physics 1: Algebra-Based', 'Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_physics_2__algebra_based"
           data-subject="Physics 2: Algebra-Based"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Physics 2: Algebra-Based', 'Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Physics 2: Algebra-Based</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Physics 2: Algebra-Based', 'Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_physics_c__mechanics"
           data-subject="Physics C: Mechanics"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Physics C: Mechanics', 'Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Physics C: Mechanics</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Physics C: Mechanics', 'Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_physics_c__electricity___magnetism"
           data-subject="Physics C: Electricity & Magnetism"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Physics C: Electricity & Magnetism', 'Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Physics C: Electricity & Magnetism</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Physics C: Electricity & Magnetism', 'Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_environmental_science"
           data-subject="Environmental Science"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Environmental Science', 'Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Environmental Science</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Environmental Science', 'Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🌍</span>
      <span class="sublib-cat-name">Humanities & Social Sciences</span>
      <span class="sublib-cat-count">(9)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ap_world_history__modern"
           data-subject="World History: Modern"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'World History: Modern', 'Humanities & Social Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">World History: Modern</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'World History: Modern', 'Humanities & Social Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_european_history"
           data-subject="European History"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'European History', 'Humanities & Social Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">European History</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'European History', 'Humanities & Social Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_united_states_history"
           data-subject="United States History"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'United States History', 'Humanities & Social Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">United States History</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'United States History', 'Humanities & Social Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_united_states_government___politics"
           data-subject="United States Government & Politics"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'United States Government & Politics', 'Humanities & Social Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">United States Government & Politics</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'United States Government & Politics', 'Humanities & Social Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_comparative_government___politics"
           data-subject="Comparative Government & Politics"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Comparative Government & Politics', 'Humanities & Social Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Comparative Government & Politics</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Comparative Government & Politics', 'Humanities & Social Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_human_geography"
           data-subject="Human Geography"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Human Geography', 'Humanities & Social Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Human Geography</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Human Geography', 'Humanities & Social Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_psychology"
           data-subject="Psychology"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Psychology', 'Humanities & Social Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Psychology</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Psychology', 'Humanities & Social Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_macroeconomics"
           data-subject="Macroeconomics"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Macroeconomics', 'Humanities & Social Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Macroeconomics</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Macroeconomics', 'Humanities & Social Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_microeconomics"
           data-subject="Microeconomics"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Microeconomics', 'Humanities & Social Sciences', '#4a1a6b')">
        <div class="sublib-card-subject">Microeconomics</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Microeconomics', 'Humanities & Social Sciences', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">📖</span>
      <span class="sublib-cat-name">English & Languages</span>
      <span class="sublib-cat-count">(10)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ap_english_language___composition"
           data-subject="English Language & Composition"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'English Language & Composition', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">English Language & Composition</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'English Language & Composition', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_english_literature___composition"
           data-subject="English Literature & Composition"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'English Literature & Composition', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">English Literature & Composition</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'English Literature & Composition', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_spanish_language___culture"
           data-subject="Spanish Language & Culture"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Spanish Language & Culture', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">Spanish Language & Culture</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Spanish Language & Culture', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_spanish_literature___culture"
           data-subject="Spanish Literature & Culture"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Spanish Literature & Culture', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">Spanish Literature & Culture</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Spanish Literature & Culture', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_french_language___culture"
           data-subject="French Language & Culture"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'French Language & Culture', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">French Language & Culture</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'French Language & Culture', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_german_language___culture"
           data-subject="German Language & Culture"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'German Language & Culture', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">German Language & Culture</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'German Language & Culture', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_mandarin_chinese_language___culture"
           data-subject="Mandarin Chinese Language & Culture"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Mandarin Chinese Language & Culture', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">Mandarin Chinese Language & Culture</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Mandarin Chinese Language & Culture', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_japanese_language___culture"
           data-subject="Japanese Language & Culture"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Japanese Language & Culture', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">Japanese Language & Culture</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Japanese Language & Culture', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_italian_language___culture"
           data-subject="Italian Language & Culture"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Italian Language & Culture', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">Italian Language & Culture</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Italian Language & Culture', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_latin"
           data-subject="Latin"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Latin', 'English & Languages', '#4a1a6b')">
        <div class="sublib-card-subject">Latin</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Latin', 'English & Languages', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div>
  <div class="sublib-category">
    <div class="sublib-cat-header">
      <span class="sublib-cat-icon">🎨</span>
      <span class="sublib-cat-name">Arts</span>
      <span class="sublib-cat-count">(7)</span>
    </div>
    <div class="sublib-grid">
      <div class="sublib-card" 
           data-subject-id="ap_art_history"
           data-subject="Art History"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Art History', 'Arts', '#4a1a6b')">
        <div class="sublib-card-subject">Art History</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Art History', 'Arts', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_music_theory"
           data-subject="Music Theory"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Music Theory', 'Arts', '#4a1a6b')">
        <div class="sublib-card-subject">Music Theory</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Music Theory', 'Arts', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_studio_art__2d_design"
           data-subject="Studio Art: 2D Design"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Studio Art: 2D Design', 'Arts', '#4a1a6b')">
        <div class="sublib-card-subject">Studio Art: 2D Design</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Studio Art: 2D Design', 'Arts', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_studio_art__3d_design"
           data-subject="Studio Art: 3D Design"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Studio Art: 3D Design', 'Arts', '#4a1a6b')">
        <div class="sublib-card-subject">Studio Art: 3D Design</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Studio Art: 3D Design', 'Arts', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_studio_art__drawing"
           data-subject="Studio Art: Drawing"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Studio Art: Drawing', 'Arts', '#4a1a6b')">
        <div class="sublib-card-subject">Studio Art: Drawing</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Studio Art: Drawing', 'Arts', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_seminar"
           data-subject="Seminar"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Seminar', 'Arts', '#4a1a6b')">
        <div class="sublib-card-subject">Seminar</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Seminar', 'Arts', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
      <div class="sublib-card" 
           data-subject-id="ap_research"
           data-subject="Research"
           data-curr="AP"
           style="--card-color:#4a1a6b"
           onclick="openSubjectModal('AP', 'Research', 'Arts', '#4a1a6b')">
        <div class="sublib-card-subject">Research</div>
        <div class="sublib-card-meta">AP</div>
        <div class="sublib-card-actions">
          <button class="sublib-card-btn primary" onclick="event.stopPropagation(); openSubjectModal('AP', 'Research', 'Arts', '#4a1a6b')">
            Open →
          </button>
        </div>
      </div>
    </div>
  </div><div class="sublib-empty">No subjects match your search.</div></div>
    </div>
  </div>
</div>

          <!-- PRACTICE -->
          <div class="fdash-panel" id="fdash-practice">

            <!-- PRACTICE SETUP -->
            <div id="prac-setup">
              <div class="fdash-box-title" style="font-size:16px;margin-bottom:4px;">Adaptive Practice</div>
              <div style="font-size:12px;color:rgba(247,245,240,0.45);margin-bottom:18px;">The AI selects questions targeting your weakest topics. Every answer is marked instantly with examiner-level feedback.</div>

              <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:10px;margin-bottom:16px;">
                <div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.45);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.07em;text-transform:uppercase;">Mode</div>
                  <select id="prac-mode" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:8px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                    <option value="adaptive">Adaptive (AI-selected)</option>
                    <option value="weakest">Weakest topics only</option>
                    <option value="random">Random mixed</option>
                    <option value="topic">Choose topic</option>
                  </select>
                </div>
                <div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.45);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.07em;text-transform:uppercase;">Questions</div>
                  <select id="prac-qcount" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:8px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                    <option value="5">5 questions</option>
                    <option value="10" selected>10 questions</option>
                    <option value="20">20 questions</option>
                    <option value="30">30 questions</option>
                  </select>
                </div>
                <div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.45);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.07em;text-transform:uppercase;">Difficulty</div>
                  <select id="prac-diff" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:8px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                    <option value="auto">Auto (adapts to you)</option>
                    <option value="easy">Foundation</option>
                    <option value="medium">Standard</option>
                    <option value="hard">Challenging</option>
                  </select>
                </div>
              </div>

              <!-- AI priority strip -->
              <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:14px 16px;margin-bottom:16px;">
                <div style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;color:var(--paper);margin-bottom:10px;">🤖 AI has queued these topics for you today</div>
                <div style="display:flex;flex-wrap:wrap;gap:6px;">
                  <span style="font-family:'JetBrains Mono',monospace;font-size:10px;background:rgba(224,88,88,0.15);color:#e05858;border:1px solid rgba(224,88,88,0.25);padding:4px 10px;border-radius:100px;">Organic Mechanisms</span>
                  <span style="font-family:'JetBrains Mono',monospace;font-size:10px;background:rgba(200,146,42,0.15);color:var(--gold);border:1px solid rgba(200,146,42,0.25);padding:4px 10px;border-radius:100px;">Equilibria Calcs</span>
                  <span style="font-family:'JetBrains Mono',monospace;font-size:10px;background:rgba(200,146,42,0.15);color:var(--gold);border:1px solid rgba(200,146,42,0.25);padding:4px 10px;border-radius:100px;">Redox Titrations</span>
                  <span style="font-family:'JetBrains Mono',monospace;font-size:10px;background:rgba(91,168,232,0.12);color:#5ba8e8;border:1px solid rgba(91,168,232,0.2);padding:4px 10px;border-radius:100px;">Electrode Potentials</span>
                  <span style="font-family:'JetBrains Mono',monospace;font-size:10px;background:rgba(247,245,240,0.06);color:rgba(247,245,240,0.45);border:1px solid rgba(247,245,240,0.12);padding:4px 10px;border-radius:100px;">Thermodynamics</span>
                </div>
              </div>
              <button onclick="startPractice()" style="font-family:'Syne',sans-serif;font-size:14px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:12px 32px;border-radius:var(--radius);cursor:pointer;">Begin session →</button>
            </div>

            <!-- PRACTICE ACTIVE -->
            <div id="prac-active" style="display:none;">
              <!-- Progress bar -->
              <div style="display:flex;align-items:center;gap:12px;margin-bottom:14px;">
                <div style="flex:1;height:4px;background:rgba(247,245,240,0.1);border-radius:2px;overflow:hidden;">
                  <div id="prac-progress-bar" style="height:100%;background:var(--gold);border-radius:2px;width:0%;transition:width 0.4s ease;"></div>
                </div>
                <div id="prac-progress-label" style="font-family:'JetBrains Mono',monospace;font-size:11px;color:rgba(247,245,240,0.35);white-space:nowrap;">Q 1 / 10</div>
                <div id="prac-score-live" style="font-family:'Syne',sans-serif;font-size:11px;font-weight:700;color:#5bce8a;">0 correct</div>
              </div>

              <!-- Question Card -->
              <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:20px;margin-bottom:12px;">
                <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:12px;">
                  <div style="display:flex;align-items:center;gap:8px;">
                    <span id="prac-q-badge" style="font-family:'JetBrains Mono',monospace;font-size:9px;letter-spacing:0.08em;text-transform:uppercase;padding:3px 8px;border-radius:3px;background:rgba(200,146,42,0.15);color:var(--gold);">MCQ</span>
                    <span id="prac-q-diff-badge" style="font-family:'JetBrains Mono',monospace;font-size:9px;letter-spacing:0.06em;text-transform:uppercase;padding:3px 8px;border-radius:3px;background:rgba(247,245,240,0.07);color:rgba(247,245,240,0.4);">Standard</span>
                  </div>
                  <span id="prac-q-topic-lbl" style="font-family:'JetBrains Mono',monospace;font-size:10px;color:rgba(247,245,240,0.3);"></span>
                </div>
                <div id="prac-q-text" style="font-size:14px;color:rgba(247,245,240,0.9);line-height:1.7;margin-bottom:16px;"></div>
                <div id="prac-q-opts" style="display:flex;flex-direction:column;gap:7px;"></div>
                <textarea id="prac-q-free" style="display:none;width:100%;min-height:100px;background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:11px;color:var(--paper);font-family:'Literata',serif;font-size:14px;line-height:1.6;resize:vertical;outline:none;" placeholder="Write your answer here..."></textarea>
              </div>

              <!-- Feedback Card (hidden until answered) -->
              <div id="prac-feedback" style="display:none;background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:12px;">
                <div style="display:flex;align-items:center;gap:8px;margin-bottom:10px;">
                  <div id="prac-fb-icon" style="font-size:18px;"></div>
                  <div id="prac-fb-title" style="font-family:'Syne',sans-serif;font-size:14px;font-weight:700;"></div>
                </div>
                <div id="prac-fb-body" style="font-size:13px;color:rgba(247,245,240,0.7);line-height:1.65;margin-bottom:10px;"></div>
                <div id="prac-fb-marks" style="font-family:'JetBrains Mono',monospace;font-size:11px;color:rgba(247,245,240,0.35);border-top:1px solid rgba(247,245,240,0.08);padding-top:10px;"></div>
              </div>

              <div style="display:flex;gap:10px;">
                <button id="prac-submit-btn" onclick="pracSubmit()" style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:10px 24px;border-radius:var(--radius);cursor:pointer;">Submit answer →</button>
                <button id="prac-next-btn" onclick="pracNext()" style="display:none;font-family:'Syne',sans-serif;font-size:13px;font-weight:600;background:rgba(247,245,240,0.07);color:rgba(247,245,240,0.7);border:1px solid rgba(247,245,240,0.15);padding:10px 24px;border-radius:var(--radius);cursor:pointer;">Next question →</button>
                <button onclick="endPractice()" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:500;background:transparent;color:rgba(247,245,240,0.3);border:none;padding:10px 14px;cursor:pointer;margin-left:auto;">End session</button>
              </div>
            </div>

            <!-- PRACTICE RESULTS -->
            <div id="prac-results" style="display:none;">
              <div style="text-align:center;padding:16px 0 24px;">
                <div style="font-size:40px;margin-bottom:8px;" id="prac-results-emoji">🎉</div>
                <div style="font-family:'Syne',sans-serif;font-size:20px;font-weight:800;color:var(--paper);margin-bottom:4px;">Session complete</div>
                <div style="font-size:12px;color:rgba(247,245,240,0.4);" id="prac-results-sub"></div>
              </div>
              <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:20px;" id="prac-results-grid"></div>
              <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:14px;margin-bottom:16px;" id="prac-results-breakdown"></div>
              <div style="display:flex;gap:10px;">
                <button onclick="resetPractice()" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:10px 22px;border-radius:var(--radius);cursor:pointer;">New session →</button>
                <button onclick="navTo('flashcards')" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;background:transparent;color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.15);padding:10px 22px;border-radius:var(--radius);cursor:pointer;">Review flashcards →</button>
              </div>
            </div>
          </div>

          <!-- EXAM SIM -->
          <div class="fdash-panel" id="fdash-examsim">
            <!-- SETUP SCREEN -->
            <div id="esim-setup">
              <div class="fdash-box-title" style="font-size:16px;margin-bottom:4px;">Exam Simulator</div>
              <div style="font-size:12px;color:rgba(247,245,240,0.5);margin-bottom:20px;">Timed, realistic exam conditions. App lock prevents switching tabs during your session.</div>
              <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:16px;">
                <div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.5);margin-bottom:6px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Curriculum</div>
                  <select id="esim-curriculum" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.15);border-radius:var(--radius);padding:9px 12px;color:var(--paper);font-family:'Syne',sans-serif;font-size:13px;outline:none;cursor:pointer;">
                    <option value="gcse">GCSE</option><option value="alevel">A-Level</option><option value="ib">IB Diploma</option><option value="ap">AP</option><option value="igcse">IGCSE</option>
                  </select>
                </div>
                <div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.5);margin-bottom:6px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Subject</div>
                  <select id="esim-subject" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.15);border-radius:var(--radius);padding:9px 12px;color:var(--paper);font-family:'Syne',sans-serif;font-size:13px;outline:none;cursor:pointer;">
                    <option>Biology</option><option>Chemistry</option><option>Physics</option><option>Mathematics</option><option>Economics</option><option>History</option><option>Psychology</option><option>Geography</option>
                  </select>
                </div>
                <div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.5);margin-bottom:6px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Duration</div>
                  <select id="esim-duration" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.15);border-radius:var(--radius);padding:9px 12px;color:var(--paper);font-family:'Syne',sans-serif;font-size:13px;outline:none;cursor:pointer;">
                    <option value="30">30 minutes</option><option value="45">45 minutes</option><option value="60" selected>60 minutes</option><option value="90">90 minutes</option><option value="120">2 hours</option><option value="150">2 hours 30 min</option><option value="180">3 hours</option>
                  </select>
                </div>
                <div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.5);margin-bottom:6px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Question Type</div>
                  <select id="esim-qtype" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.15);border-radius:var(--radius);padding:9px 12px;color:var(--paper);font-family:'Syne',sans-serif;font-size:13px;outline:none;cursor:pointer;">
                    <option value="mixed">Mixed (recommended)</option><option value="mcq">MCQ only</option><option value="structured">Structured / FRQ</option><option value="extended">Extended response</option>
                  </select>
                </div>
              </div>
              <div style="background:rgba(200,146,42,0.1);border:1px solid rgba(200,146,42,0.25);border-radius:var(--radius);padding:12px 16px;margin-bottom:20px;display:flex;align-items:flex-start;gap:10px;">
                <div style="font-size:14px;margin-top:1px;">🔒</div>
                <div>
                  <div style="font-size:12px;font-weight:600;color:var(--gold);font-family:'Syne',sans-serif;margin-bottom:3px;">App Lock will activate on start</div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.5);line-height:1.5;">Switching tabs or minimising the window will be detected and logged as a focus break. This mirrors real exam conditions. You can disable this below.</div>
                  <label style="display:flex;align-items:center;gap:8px;margin-top:8px;cursor:pointer;">
                    <input type="checkbox" id="esim-applock" checked style="accent-color:var(--gold);width:14px;height:14px;">
                    <span style="font-size:11px;color:rgba(247,245,240,0.6);">Enable app lock (recommended)</span>
                  </label>
                </div>
              </div>
              <button onclick="startExamSim()" style="font-family:'Syne',sans-serif;font-size:14px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:13px 32px;border-radius:var(--radius);cursor:pointer;transition:all 0.2s;letter-spacing:0.01em;">Start exam simulation →</button>
            </div>

            <!-- APP LOCK OVERLAY -->
            <div id="esim-lockoverlay" style="display:none;position:absolute;inset:0;background:var(--ink);z-index:999;border-radius:var(--radius-lg);display:none;flex-direction:column;align-items:center;justify-content:center;gap:16px;">
              <div style="font-size:48px;">🔒</div>
              <div style="font-family:'Syne',sans-serif;font-size:20px;font-weight:800;color:var(--paper);">Focus break detected</div>
              <div style="font-size:13px;color:rgba(247,245,240,0.5);text-align:center;max-width:320px;line-height:1.6;">You left the exam window. This has been logged. In a real exam, this would result in disqualification.</div>
              <button onclick="resumeExamSim()" style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:10px 28px;border-radius:var(--radius);cursor:pointer;margin-top:8px;">Resume exam →</button>
            </div>

            <!-- ACTIVE EXAM SCREEN -->
            <div id="esim-active" style="display:none;">
              <!-- Timer Bar -->
              <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:16px;padding:10px 16px;background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius);">
                <div style="display:flex;align-items:center;gap:16px;">
                  <div style="font-family:'JetBrains Mono',monospace;font-size:22px;font-weight:500;color:var(--paper);" id="esim-timer-display">60:00</div>
                  <div id="esim-timer-bar-wrap" style="width:160px;height:6px;background:rgba(247,245,240,0.1);border-radius:3px;overflow:hidden;">
                    <div id="esim-timer-bar" style="height:100%;background:var(--gold);border-radius:3px;width:100%;transition:width 1s linear;"></div>
                  </div>
                </div>
                <div style="display:flex;align-items:center;gap:12px;">
                  <div style="font-family:'Syne',sans-serif;font-size:11px;color:rgba(247,245,240,0.4);" id="esim-focus-status">🟢 Focus intact</div>
                  <div style="font-family:'JetBrains Mono',monospace;font-size:11px;color:rgba(247,245,240,0.35);" id="esim-q-counter">Q 1 / 8</div>
                  <button onclick="endExamConfirm()" style="font-family:'Syne',sans-serif;font-size:11px;font-weight:600;background:rgba(224,88,88,0.1);color:#e05858;border:1px solid rgba(224,88,88,0.2);padding:5px 12px;border-radius:var(--radius);cursor:pointer;">End exam</button>
                </div>
              </div>

              <!-- Question Area -->
              <div id="esim-question-area" style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:20px;margin-bottom:12px;">
                <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:12px;">
                  <div style="display:flex;align-items:center;gap:8px;">
                    <span id="esim-q-type-badge" style="font-family:'JetBrains Mono',monospace;font-size:9px;letter-spacing:0.08em;text-transform:uppercase;background:rgba(200,146,42,0.15);color:var(--gold);padding:3px 8px;border-radius:3px;">MCQ</span>
                    <span id="esim-q-marks" style="font-family:'JetBrains Mono',monospace;font-size:11px;color:rgba(247,245,240,0.35);">[2 marks]</span>
                  </div>
                  <div id="esim-q-topic" style="font-size:11px;color:rgba(247,245,240,0.3);font-family:'JetBrains Mono',monospace;">Topic: Organic Chemistry</div>
                </div>
                <div id="esim-q-text" style="font-size:14px;color:rgba(247,245,240,0.9);line-height:1.7;margin-bottom:16px;"></div>
                <div id="esim-q-options" style="display:flex;flex-direction:column;gap:8px;"></div>
                <textarea id="esim-q-freetext" style="display:none;width:100%;min-height:120px;background:rgba(247,245,240,0.06);border:1px solid rgba(247,245,240,0.15);border-radius:var(--radius);padding:12px;color:var(--paper);font-family:'Literata',serif;font-size:14px;line-height:1.6;resize:vertical;outline:none;" placeholder="Write your answer here. Use the mark scheme structure: state → explain → example..."></textarea>
              </div>

              <!-- Nav Buttons -->
              <div style="display:flex;align-items:center;justify-content:space-between;">
                <button onclick="esimPrev()" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;background:transparent;color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.15);padding:8px 18px;border-radius:var(--radius);cursor:pointer;">← Previous</button>
                <div id="esim-q-dots" style="display:flex;gap:6px;"></div>
                <button onclick="esimNext()" id="esim-next-btn" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;background:rgba(200,146,42,0.15);color:var(--gold);border:1px solid rgba(200,146,42,0.3);padding:8px 18px;border-radius:var(--radius);cursor:pointer;">Next →</button>
              </div>
            </div>

            <!-- RESULTS SCREEN -->
            <div id="esim-results" style="display:none;">
              <div style="text-align:center;padding:20px 0 28px;">
                <div style="font-size:36px;margin-bottom:8px;">📋</div>
                <div style="font-family:'Syne',sans-serif;font-size:18px;font-weight:800;color:var(--paper);margin-bottom:4px;">Exam complete</div>
                <div style="font-size:12px;color:rgba(247,245,240,0.4);" id="esim-results-meta"></div>
              </div>
              <div style="display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-bottom:20px;" id="esim-results-stats"></div>
              <div id="esim-results-breakdown" style="display:flex;flex-direction:column;gap:8px;margin-bottom:20px;"></div>
              <div style="display:flex;gap:10px;">
                <button onclick="resetExamSim()" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;background:var(--gold);color:var(--paper);border:none;padding:10px 24px;border-radius:var(--radius);cursor:pointer;">New exam →</button>
                <button onclick="navTo('suggestions')" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;background:transparent;color:rgba(247,245,240,0.6);border:1px solid rgba(247,245,240,0.15);padding:10px 24px;border-radius:var(--radius);cursor:pointer;">View AI suggestions →</button>
              </div>
            </div>
          </div>

          <!-- MY NOTES -->
          <div class="fdash-panel" id="fdash-mynotes">
            <div id="mynotes-list-view">
              <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:16px;">
                <div>
                  <div class="fdash-box-title" style="font-size:16px;margin-bottom:2px;">My Revision Notes</div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.4);">Write, organise, and review your own notes — saved in your browser.</div>
                </div>
                <button onclick="mnCreateNote()" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:8px 18px;border-radius:var(--radius);cursor:pointer;">+ New note</button>
              </div>
              <!-- Filter Bar -->
              <div style="display:flex;align-items:center;gap:8px;margin-bottom:14px;flex-wrap:wrap;">
                <input id="mn-search" oninput="mnSearch()" placeholder="Search notes..." style="flex:1;min-width:160px;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.12);border-radius:var(--radius);padding:7px 12px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;" />
                <select id="mn-filter-subject" onchange="mnRender()" style="background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.12);border-radius:var(--radius);padding:7px 10px;color:rgba(247,245,240,0.7);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                  <option value="">All subjects</option>
                  <option>Biology</option><option>Chemistry</option><option>Physics</option><option>Mathematics</option><option>Economics</option><option>History</option><option>Psychology</option><option>Geography</option><option>English</option><option>Other</option>
                </select>
                <select id="mn-filter-tag" onchange="mnRender()" style="background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.12);border-radius:var(--radius);padding:7px 10px;color:rgba(247,245,240,0.7);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                  <option value="">All tags</option>
                  <option>Key definitions</option><option>Exam technique</option><option>Formulas</option><option>Case studies</option><option>Common mistakes</option>
                </select>
              </div>
              <div id="mn-grid" style="display:grid;grid-template-columns:1fr 1fr;gap:10px;"></div>
              <div id="mn-empty" style="display:none;text-align:center;padding:40px 20px;">
                <div style="font-size:32px;margin-bottom:10px;">📝</div>
                <div style="font-family:'Syne',sans-serif;font-size:14px;color:rgba(247,245,240,0.5);">No notes yet. Click "New note" to start writing.</div>
              </div>
            </div>

            <!-- EDITOR VIEW -->
            <div id="mynotes-editor-view" style="display:none;flex-direction:column;height:100%;">
              <div style="display:flex;align-items:center;gap:10px;margin-bottom:14px;">
                <button onclick="mnBack()" style="font-family:'Syne',sans-serif;font-size:12px;background:transparent;color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.15);padding:6px 14px;border-radius:var(--radius);cursor:pointer;">← Back</button>
                <input id="mn-title-input" placeholder="Note title..." style="flex:1;background:transparent;border:none;border-bottom:1px solid rgba(247,245,240,0.2);padding:4px 0;color:var(--paper);font-family:'Syne',sans-serif;font-size:16px;font-weight:700;outline:none;" />
                <select id="mn-subject-select" style="background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.15);border-radius:var(--radius);padding:6px 10px;color:rgba(247,245,240,0.7);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                  <option value="">Subject...</option>
                  <option>Biology</option><option>Chemistry</option><option>Physics</option><option>Mathematics</option><option>Economics</option><option>History</option><option>Psychology</option><option>Geography</option><option>English</option><option>Other</option>
                </select>
                <select id="mn-tag-select" style="background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.15);border-radius:var(--radius);padding:6px 10px;color:rgba(247,245,240,0.7);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                  <option value="">Tag...</option>
                  <option>Key definitions</option><option>Exam technique</option><option>Formulas</option><option>Case studies</option><option>Common mistakes</option>
                </select>
                <button onclick="mnSave()" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:7px 18px;border-radius:var(--radius);cursor:pointer;">Save</button>
                <button onclick="mnDelete()" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;background:rgba(224,88,88,0.1);color:#e05858;border:1px solid rgba(224,88,88,0.2);padding:7px 14px;border-radius:var(--radius);cursor:pointer;">Delete</button>
              </div>

              <!-- Formatting Toolbar -->
              <div style="display:flex;align-items:center;gap:4px;margin-bottom:10px;padding:8px 10px;background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius);flex-wrap:wrap;">
                <button onclick="mnFormat('bold')" title="Bold" style="background:transparent;border:none;color:rgba(247,245,240,0.7);font-size:13px;font-weight:700;padding:4px 8px;border-radius:3px;cursor:pointer;">B</button>
                <button onclick="mnFormat('italic')" title="Italic" style="background:transparent;border:none;color:rgba(247,245,240,0.7);font-size:13px;font-style:italic;padding:4px 8px;border-radius:3px;cursor:pointer;">I</button>
                <button onclick="mnFormat('underline')" title="Underline" style="background:transparent;border:none;color:rgba(247,245,240,0.7);font-size:13px;text-decoration:underline;padding:4px 8px;border-radius:3px;cursor:pointer;">U</button>
                <div style="width:1px;height:18px;background:rgba(247,245,240,0.15);margin:0 4px;"></div>
                <button onclick="mnInsertHeading()" title="Heading" style="background:transparent;border:none;color:rgba(247,245,240,0.7);font-family:'Syne',sans-serif;font-size:11px;font-weight:700;padding:4px 8px;border-radius:3px;cursor:pointer;">H2</button>
                <button onclick="mnInsertList()" title="Bullet list" style="background:transparent;border:none;color:rgba(247,245,240,0.7);font-size:13px;padding:4px 8px;border-radius:3px;cursor:pointer;">• List</button>
                <button onclick="mnInsertDivider()" title="Divider" style="background:transparent;border:none;color:rgba(247,245,240,0.7);font-size:13px;padding:4px 8px;border-radius:3px;cursor:pointer;">— Rule</button>
                <div style="width:1px;height:18px;background:rgba(247,245,240,0.15);margin:0 4px;"></div>
                <button onclick="mnInsertBox('definition')" style="background:rgba(91,168,232,0.1);border:1px solid rgba(91,168,232,0.2);color:#5ba8e8;font-family:'JetBrains Mono',monospace;font-size:10px;letter-spacing:0.04em;padding:4px 8px;border-radius:3px;cursor:pointer;">+ Definition</button>
                <button onclick="mnInsertBox('formula')" style="background:rgba(200,146,42,0.1);border:1px solid rgba(200,146,42,0.2);color:var(--gold);font-family:'JetBrains Mono',monospace;font-size:10px;letter-spacing:0.04em;padding:4px 8px;border-radius:3px;cursor:pointer;">+ Formula</button>
                <button onclick="mnInsertBox('examtip')" style="background:rgba(91,206,138,0.1);border:1px solid rgba(91,206,138,0.2);color:#5bce8a;font-family:'JetBrains Mono',monospace;font-size:10px;letter-spacing:0.04em;padding:4px 8px;border-radius:3px;cursor:pointer;">+ Exam tip</button>
                <button onclick="mnInsertBox('mistake')" style="background:rgba(224,88,88,0.1);border:1px solid rgba(224,88,88,0.2);color:#e05858;font-family:'JetBrains Mono',monospace;font-size:10px;letter-spacing:0.04em;padding:4px 8px;border-radius:3px;cursor:pointer;">+ Common mistake</button>
                <div style="margin-left:auto;font-family:'JetBrains Mono',monospace;font-size:10px;color:rgba(247,245,240,0.25);" id="mn-saved-indicator">Unsaved</div>
              </div>

              <!-- Rich Text Editor -->
              <div id="mn-editor" contenteditable="true" spellcheck="true"
                style="flex:1;min-height:320px;background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:20px;color:rgba(247,245,240,0.9);font-family:'Literata',serif;font-size:14px;line-height:1.75;outline:none;overflow-y:auto;"
                data-placeholder="Start writing your notes here...

Use the toolbar above to add headings, bullet points, definitions, formulas, and exam tips. Your notes are saved automatically to your browser."
              ></div>
              <div style="display:flex;justify-content:space-between;align-items:center;margin-top:8px;">
                <div style="font-size:11px;color:rgba(247,245,240,0.25);font-family:'JetBrains Mono',monospace;" id="mn-wordcount">0 words</div>
                <div style="font-size:11px;color:rgba(247,245,240,0.25);font-family:'JetBrains Mono',monospace;" id="mn-last-saved"></div>
              </div>
            </div>
          </div>

          <!-- AI SUGGESTIONS -->
          <div class="fdash-panel" id="fdash-suggestions">
            <div class="fdash-box-title" style="font-size:16px;margin-bottom:4px;">AI Revision Suggestions</div>
            <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:20px;">Based on your performance data, exam date, and forgetting curves.</div>

            <!-- Priority Alert -->
            <div style="background:rgba(224,88,88,0.1);border:1px solid rgba(224,88,88,0.25);border-radius:var(--radius-lg);padding:14px 16px;margin-bottom:14px;">
              <div style="display:flex;align-items:center;gap:8px;margin-bottom:6px;">
                <span style="font-size:14px;">🚨</span>
                <span style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:#e05858;">Critical: 3 topics need urgent attention</span>
              </div>
              <div style="font-size:12px;color:rgba(247,245,240,0.6);line-height:1.55;">Your accuracy on <strong style="color:#e05858;">Organic Mechanisms</strong>, <strong style="color:#e05858;">Equilibria Calculations</strong>, and <strong style="color:#e05858;">Redox Titrations</strong> is below the grade boundary for A*. These three topics account for an estimated <strong style="color:#e05858;">22 marks</strong> on your paper — the difference between B and A*.</div>
            </div>

            <!-- Weekly Optimal Plan -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:14px;">
              <div style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--paper);margin-bottom:14px;display:flex;align-items:center;justify-content:space-between;">
                <span>📅 Optimal 7-day revision schedule</span>
                <span style="font-family:'JetBrains Mono',monospace;font-size:10px;color:rgba(247,245,240,0.3);font-weight:400;">47 days to exam</span>
              </div>
              <div id="sugg-week-plan" style="display:flex;flex-direction:column;gap:6px;"></div>
            </div>

            <!-- Topic Priority Ranking -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:14px;">
              <div style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--paper);margin-bottom:14px;">📊 Topics ranked by revision ROI</div>
              <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;" id="sugg-topics"></div>
            </div>

            <!-- Technique Recommendations -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:14px;">
              <div style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--paper);margin-bottom:14px;">🎯 Exam technique insights</div>
              <div style="display:flex;flex-direction:column;gap:10px;" id="sugg-techniques"></div>
            </div>

            <!-- Revision Method Recommendations -->
            <div style="background:rgba(200,146,42,0.07);border:1px solid rgba(200,146,42,0.2);border-radius:var(--radius-lg);padding:16px;">
              <div style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--gold);margin-bottom:12px;">⚡ Today's recommended session (52 min)</div>
              <div style="display:flex;flex-direction:column;gap:8px;" id="sugg-session"></div>
            </div>
          </div>

          <!-- FLASHCARDS -->
          <div class="fdash-panel" id="fdash-flashcards">

            <!-- DECK HOME -->
            <div id="fc-home">
              <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:16px;">
                <div>
                  <div class="fdash-box-title" style="font-size:16px;margin-bottom:2px;">Spaced Repetition Flashcards</div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.4);">Cards are automatically scheduled based on your forgetting curve.</div>
                </div>
                <button onclick="fcStartSession()" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:8px 20px;border-radius:var(--radius);cursor:pointer;">Review due cards →</button>
              </div>

              <!-- Due Today Banner -->
              <div style="background:rgba(200,146,42,0.1);border:1px solid rgba(200,146,42,0.25);border-radius:var(--radius-lg);padding:14px 18px;margin-bottom:16px;display:flex;align-items:center;justify-content:space-between;">
                <div>
                  <div style="font-family:'Syne',sans-serif;font-size:14px;font-weight:700;color:var(--gold);">142 cards due today</div>
                  <div style="font-size:12px;color:rgba(247,245,240,0.5);margin-top:2px;">Estimated session: 28 minutes · Next review: tomorrow at 09:00</div>
                </div>
                <div style="font-family:'Syne',sans-serif;font-size:28px;font-weight:800;color:var(--gold);">142</div>
              </div>

              <!-- Deck Grid -->
              <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:10px;margin-bottom:16px;" id="fc-deck-grid"></div>

              <!-- Add Card -->
              <div style="background:rgba(247,245,240,0.04);border:1px dashed rgba(247,245,240,0.15);border-radius:var(--radius-lg);padding:14px;display:flex;align-items:center;gap:12px;">
                <span style="font-size:20px;">➕</span>
                <div style="flex:1;">
                  <div style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--paper);margin-bottom:2px;">Add your own flashcard</div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.4);">Cards you add are automatically scheduled into your spaced repetition queue.</div>
                </div>
                <button onclick="fcShowAddCard()" style="font-family:'Syne',sans-serif;font-size:11px;font-weight:600;background:rgba(247,245,240,0.08);color:rgba(247,245,240,0.7);border:1px solid rgba(247,245,240,0.15);padding:6px 14px;border-radius:var(--radius);cursor:pointer;white-space:nowrap;">Add card</button>
              </div>
            </div>

            <!-- ADD CARD FORM -->
            <div id="fc-add-form" style="display:none;">
              <div style="display:flex;align-items:center;gap:10px;margin-bottom:16px;">
                <button onclick="document.getElementById('fc-add-form').style.display='none';document.getElementById('fc-home').style.display='block';" style="font-family:'Syne',sans-serif;font-size:12px;background:transparent;color:rgba(247,245,240,0.4);border:1px solid rgba(247,245,240,0.15);padding:5px 12px;border-radius:var(--radius);cursor:pointer;">← Back</button>
                <div style="font-family:'Syne',sans-serif;font-size:15px;font-weight:700;color:var(--paper);">New flashcard</div>
              </div>
              <div style="display:flex;flex-direction:column;gap:12px;">
                <div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.45);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.07em;text-transform:uppercase;">Front (question / term)</div>
                  <textarea id="fc-add-front" style="width:100%;min-height:80px;background:rgba(247,245,240,0.06);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:10px;color:var(--paper);font-family:'Literata',serif;font-size:14px;line-height:1.6;resize:vertical;outline:none;" placeholder="e.g. What is Le Chatelier's Principle?"></textarea>
                </div>
                <div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.45);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.07em;text-transform:uppercase;">Back (answer / definition)</div>
                  <textarea id="fc-add-back" style="width:100%;min-height:100px;background:rgba(247,245,240,0.06);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:10px;color:var(--paper);font-family:'Literata',serif;font-size:14px;line-height:1.6;resize:vertical;outline:none;" placeholder="e.g. If a system at equilibrium is subjected to a change in conditions, it will shift to oppose that change..."></textarea>
                </div>
                <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;">
                  <div>
                    <div style="font-size:10px;color:rgba(247,245,240,0.45);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.07em;text-transform:uppercase;">Subject</div>
                    <select id="fc-add-subject" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:8px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                      <option>Chemistry</option><option>Biology</option><option>Physics</option><option>Mathematics</option><option>Economics</option><option>History</option><option>Psychology</option><option>Other</option>
                    </select>
                  </div>
                  <div>
                    <div style="font-size:10px;color:rgba(247,245,240,0.45);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.07em;text-transform:uppercase;">Card type</div>
                    <select id="fc-add-type" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:8px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                      <option value="definition">Definition</option><option value="formula">Formula</option><option value="concept">Concept</option><option value="examtip">Exam tip</option>
                    </select>
                  </div>
                </div>
                <button onclick="fcSaveCard()" style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:10px 28px;border-radius:var(--radius);cursor:pointer;width:fit-content;">Save card →</button>
              </div>
            </div>

            <!-- REVIEW SESSION -->
            <div id="fc-session" style="display:none;">
              <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:14px;">
                <div style="font-family:'JetBrains Mono',monospace;font-size:11px;color:rgba(247,245,240,0.35);" id="fc-session-counter">Card 1 / 10</div>
                <div style="display:flex;align-items:center;gap:8px;">
                  <span style="font-size:11px;color:#5bce8a;font-family:'Syne',sans-serif;" id="fc-session-correct">0 ✓</span>
                  <span style="font-size:11px;color:#e05858;font-family:'Syne',sans-serif;" id="fc-session-wrong">0 ✗</span>
                </div>
                <button onclick="fcEndSession()" style="font-family:'Syne',sans-serif;font-size:11px;background:transparent;color:rgba(247,245,240,0.3);border:none;cursor:pointer;padding:4px 8px;">End session</button>
              </div>

              <!-- The Card -->
              <div id="fc-card-scene" style="perspective:1200px;margin-bottom:20px;" onclick="fcFlip()">
                <div id="fc-card-inner" style="position:relative;width:100%;min-height:200px;transform-style:preserve-3d;transition:transform 0.5s ease;cursor:pointer;">
                  <!-- Front -->
                  <div id="fc-card-front" style="backface-visibility:hidden;-webkit-backface-visibility:hidden;background:rgba(247,245,240,0.06);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius-xl);padding:28px;display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:200px;text-align:center;">
                    <div id="fc-front-type" style="font-family:'JetBrains Mono',monospace;font-size:9px;letter-spacing:0.1em;text-transform:uppercase;color:rgba(247,245,240,0.3);margin-bottom:14px;"></div>
                    <div id="fc-front-text" style="font-family:'Literata',serif;font-size:16px;color:rgba(247,245,240,0.9);line-height:1.6;"></div>
                    <div style="margin-top:20px;font-size:11px;color:rgba(247,245,240,0.2);font-family:'Syne',sans-serif;">Tap to reveal answer</div>
                  </div>
                  <!-- Back -->
                  <div id="fc-card-back" style="position:absolute;inset:0;backface-visibility:hidden;-webkit-backface-visibility:hidden;transform:rotateY(180deg);background:rgba(200,146,42,0.08);border:1px solid rgba(200,146,42,0.25);border-radius:var(--radius-xl);padding:28px;display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:200px;text-align:center;">
                    <div style="font-family:'JetBrains Mono',monospace;font-size:9px;letter-spacing:0.1em;text-transform:uppercase;color:var(--gold);opacity:0.6;margin-bottom:14px;">Answer</div>
                    <div id="fc-back-text" style="font-family:'Literata',serif;font-size:14px;color:rgba(247,245,240,0.88);line-height:1.65;"></div>
                  </div>
                </div>
              </div>

              <!-- Rating Buttons (hidden until flipped) -->
              <div id="fc-rating-btns" style="display:none;display:flex;gap:8px;justify-content:center;">
                <button onclick="fcRate('again')" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;flex:1;padding:11px;border-radius:var(--radius);cursor:pointer;background:rgba(224,88,88,0.12);color:#e05858;border:1px solid rgba(224,88,88,0.25);">Again<br><span style="font-size:10px;font-weight:400;opacity:0.7;">&lt;1 min</span></button>
                <button onclick="fcRate('hard')" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;flex:1;padding:11px;border-radius:var(--radius);cursor:pointer;background:rgba(200,146,42,0.12);color:var(--gold);border:1px solid rgba(200,146,42,0.25);">Hard<br><span style="font-size:10px;font-weight:400;opacity:0.7;">6 min</span></button>
                <button onclick="fcRate('good')" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;flex:1;padding:11px;border-radius:var(--radius);cursor:pointer;background:rgba(91,168,232,0.12);color:#5ba8e8;border:1px solid rgba(91,168,232,0.25);">Good<br><span style="font-size:10px;font-weight:400;opacity:0.7;">1 day</span></button>
                <button onclick="fcRate('easy')" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;flex:1;padding:11px;border-radius:var(--radius);cursor:pointer;background:rgba(91,206,138,0.12);color:#5bce8a;border:1px solid rgba(91,206,138,0.25);">Easy<br><span style="font-size:10px;font-weight:400;opacity:0.7;">4 days</span></button>
              </div>
              <div id="fc-flip-hint" style="text-align:center;font-size:11px;color:rgba(247,245,240,0.2);padding-top:8px;font-family:'Syne',sans-serif;">Tap card to flip • Rate your recall after</div>
            </div>

          </div>

          <!-- ANALYTICS -->
          <div class="fdash-panel" id="fdash-analytics">
            <div class="fdash-box-title" style="font-size:16px;margin-bottom:14px;">Performance Analytics</div>

            <!-- Top Stats Row -->
            <div class="fdash-stats" style="margin-bottom:16px;">
              <div class="fdash-stat"><div class="fdash-stat-lbl">Total study time</div><div class="fdash-stat-val">87h</div><div class="fdash-stat-sub">Last 30 days</div></div>
              <div class="fdash-stat"><div class="fdash-stat-lbl">Avg. daily session</div><div class="fdash-stat-val">52m</div><div class="fdash-stat-sub">Per active day</div></div>
              <div class="fdash-stat"><div class="fdash-stat-lbl">Topics mastered</div><div class="fdash-stat-val g">31</div><div class="fdash-stat-sub">of 74 total</div></div>
              <div class="fdash-stat"><div class="fdash-stat-lbl">Grade trajectory</div><div class="fdash-stat-val au">↑ A*</div><div class="fdash-stat-sub">On current pace</div></div>
            </div>

            <!-- Activity Heatmap -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:12px;">
              <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:12px;">
                <div style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--paper);">Study activity — last 10 weeks</div>
                <div style="display:flex;align-items:center;gap:6px;">
                  <div style="font-size:10px;color:rgba(247,245,240,0.3);font-family:'JetBrains Mono',monospace;">Less</div>
                  <div style="width:10px;height:10px;border-radius:2px;background:rgba(247,245,240,0.07);"></div>
                  <div style="width:10px;height:10px;border-radius:2px;background:rgba(200,146,42,0.25);"></div>
                  <div style="width:10px;height:10px;border-radius:2px;background:rgba(200,146,42,0.5);"></div>
                  <div style="width:10px;height:10px;border-radius:2px;background:var(--gold);"></div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.3);font-family:'JetBrains Mono',monospace;">More</div>
                </div>
              </div>
              <div id="anal-heatmap" style="display:flex;gap:3px;overflow-x:auto;padding-bottom:4px;"></div>
              <div style="display:flex;justify-content:space-between;margin-top:6px;padding:0 1px;">
                <span style="font-size:10px;color:rgba(247,245,240,0.25);font-family:'JetBrains Mono',monospace;">10 weeks ago</span>
                <span style="font-size:10px;color:rgba(247,245,240,0.25);font-family:'JetBrains Mono',monospace;">Today</span>
              </div>
            </div>

            <!-- Grade Trajectory Chart -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:12px;">
              <div style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--paper);margin-bottom:14px;">Grade trajectory (last 8 weeks)</div>
              <div style="position:relative;height:100px;display:flex;align-items:flex-end;gap:0;">
                <div style="position:absolute;inset:0;display:flex;flex-direction:column;justify-content:space-between;pointer-events:none;">
                  <div style="height:1px;background:rgba(247,245,240,0.06);position:relative;"><span style="position:absolute;left:0;top:-9px;font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.25);">A*</span></div>
                  <div style="height:1px;background:rgba(247,245,240,0.06);position:relative;"><span style="position:absolute;left:0;top:-9px;font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.25);">A</span></div>
                  <div style="height:1px;background:rgba(247,245,240,0.06);position:relative;"><span style="position:absolute;left:0;top:-9px;font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.25);">B</span></div>
                  <div style="height:1px;background:rgba(247,245,240,0.06);position:relative;"><span style="position:absolute;left:0;top:-9px;font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.25);">C</span></div>
                </div>
                <div id="anal-trajectory" style="display:flex;align-items:flex-end;gap:10px;flex:1;padding-left:26px;padding-bottom:2px;height:100%;position:relative;z-index:1;"></div>
              </div>
            </div>

            <!-- Subject Accuracy Breakdown -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:12px;">
              <div style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--paper);margin-bottom:14px;">Topic accuracy breakdown</div>
              <div id="anal-topics" style="display:flex;flex-direction:column;gap:8px;"></div>
            </div>

            <!-- Session History -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;">
              <div style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:var(--paper);margin-bottom:12px;">Recent sessions</div>
              <div id="anal-sessions" style="display:flex;flex-direction:column;gap:6px;"></div>
            </div>
          </div>

          <!-- SETTINGS -->
          <div class="fdash-panel" id="fdash-settings">
            <div class="fdash-box-title" style="font-size:16px;margin-bottom:16px;">Settings & Preferences</div>

            <!-- Profile -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:12px;">
              <div style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;color:rgba(247,245,240,0.5);text-transform:uppercase;letter-spacing:0.06em;margin-bottom:14px;font-family:'JetBrains Mono',monospace;">Profile</div>
              <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:12px;">
                <div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Full name</div>
                  <input value="Amelia Thompson" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:8px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;" />
                </div>
                <div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Email</div>
                  <input value="amelia@example.com" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:8px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;" />
                </div>
                <div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Curriculum</div>
                  <select style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:8px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                    <option selected>A-Level</option><option>GCSE</option><option>IB Diploma</option><option>AP</option><option>IGCSE</option>
                  </select>
                </div>
                <div>
                  <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Exam date</div>
                  <input type="date" value="2025-06-11" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:8px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;" />
                </div>
              </div>
              <div>
                <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Target grade</div>
                <div style="display:flex;gap:8px;flex-wrap:wrap;">
                  <button onclick="settGradeSelect(this)" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:700;padding:6px 14px;border-radius:var(--radius);cursor:pointer;background:rgba(200,146,42,0.15);color:var(--gold);border:1px solid rgba(200,146,42,0.3);" class="sett-grade-btn sett-grade-active">A*</button>
                  <button onclick="settGradeSelect(this)" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;padding:6px 14px;border-radius:var(--radius);cursor:pointer;background:transparent;color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.15);" class="sett-grade-btn">A</button>
                  <button onclick="settGradeSelect(this)" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;padding:6px 14px;border-radius:var(--radius);cursor:pointer;background:transparent;color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.15);" class="sett-grade-btn">B</button>
                  <button onclick="settGradeSelect(this)" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;padding:6px 14px;border-radius:var(--radius);cursor:pointer;background:transparent;color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.15);" class="sett-grade-btn">C</button>
                  <button onclick="settGradeSelect(this)" style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;padding:6px 14px;border-radius:var(--radius);cursor:pointer;background:transparent;color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.15);" class="sett-grade-btn">D</button>
                </div>
              </div>
            </div>

            <!-- Study Preferences -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:12px;">
              <div style="font-family:'JetBrains Mono',monospace;font-size:10px;font-weight:700;color:rgba(247,245,240,0.4);text-transform:uppercase;letter-spacing:0.07em;margin-bottom:14px;">Study preferences</div>
              <div id="sett-toggles" style="display:flex;flex-direction:column;gap:0;"></div>
            </div>

            <!-- Notifications -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:12px;">
              <div style="font-family:'JetBrains Mono',monospace;font-size:10px;font-weight:700;color:rgba(247,245,240,0.4);text-transform:uppercase;letter-spacing:0.07em;margin-bottom:14px;">Notifications</div>
              <div id="sett-notif-toggles" style="display:flex;flex-direction:column;gap:0;"></div>
              <div style="margin-top:12px;">
                <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Daily study reminder time</div>
                <input type="time" value="08:30" style="background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:var(--radius);padding:7px 10px;color:var(--paper);font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;" />
              </div>
            </div>

            <!-- Subscription -->
            <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:16px;margin-bottom:12px;">
              <div style="font-family:'JetBrains Mono',monospace;font-size:10px;font-weight:700;color:rgba(247,245,240,0.4);text-transform:uppercase;letter-spacing:0.07em;margin-bottom:14px;">Subscription</div>
              <div style="display:flex;align-items:center;justify-content:space-between;padding:10px 0;border-bottom:1px solid rgba(247,245,240,0.06);">
                <div>
                  <div style="font-size:13px;color:rgba(247,245,240,0.85);font-family:'Syne',sans-serif;font-weight:600;">Annual Plan — €98/yr</div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.35);margin-top:2px;">Active · Renews 8 April 2027</div>
                </div>
                <div style="display:flex;align-items:center;gap:8px;">
                  <span style="font-family:'JetBrains Mono',monospace;font-size:10px;background:rgba(91,206,138,0.12);color:#5bce8a;border:1px solid rgba(91,206,138,0.2);padding:3px 8px;border-radius:3px;">Active</span>
                  <button style="font-family:'Syne',sans-serif;font-size:11px;font-weight:600;background:rgba(224,88,88,0.1);color:#e05858;border:1px solid rgba(224,88,88,0.2);padding:5px 12px;border-radius:var(--radius);cursor:pointer;">Cancel</button>
                </div>
              </div>
              <div style="padding:10px 0 0;">
                <div style="font-size:12px;color:rgba(247,245,240,0.6);margin-bottom:10px;">Upgrade your school to a group plan and save 40%:</div>
                <button style="font-family:'Syne',sans-serif;font-size:12px;font-weight:600;background:transparent;color:var(--gold);border:1px solid rgba(200,146,42,0.3);padding:7px 18px;border-radius:var(--radius);cursor:pointer;">View school plans →</button>
              </div>
            </div>

            <!-- Danger Zone -->
            <div style="background:rgba(224,88,88,0.06);border:1px solid rgba(224,88,88,0.18);border-radius:var(--radius-lg);padding:16px;">
              <div style="font-family:'JetBrains Mono',monospace;font-size:10px;font-weight:700;color:rgba(224,88,88,0.6);text-transform:uppercase;letter-spacing:0.07em;margin-bottom:12px;">Danger zone</div>
              <div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:8px;">
                <div>
                  <div style="font-size:12px;color:rgba(247,245,240,0.7);">Reset all progress data</div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.3);margin-top:1px;">Clears grades, accuracy, and session history</div>
                </div>
                <button style="font-family:'Syne',sans-serif;font-size:11px;font-weight:600;background:transparent;color:#e05858;border:1px solid rgba(224,88,88,0.25);padding:5px 12px;border-radius:var(--radius);cursor:pointer;">Reset</button>
              </div>
              <div style="display:flex;align-items:center;justify-content:space-between;">
                <div>
                  <div style="font-size:12px;color:rgba(247,245,240,0.7);">Delete account</div>
                  <div style="font-size:11px;color:rgba(247,245,240,0.3);margin-top:1px;">Permanently removes all data</div>
                </div>
                <button style="font-family:'Syne',sans-serif;font-size:11px;font-weight:600;background:rgba(224,88,88,0.12);color:#e05858;border:1px solid rgba(224,88,88,0.25);padding:5px 12px;border-radius:var(--radius);cursor:pointer;">Delete account</button>
              </div>
            </div>

            <button style="font-family:'Syne',sans-serif;font-size:13px;font-weight:700;background:var(--gold);color:var(--paper);border:none;padding:11px 28px;border-radius:var(--radius);cursor:pointer;margin-top:16px;">Save changes →</button>
          </div>

        </div>
      </div>
    </div>
  </div>
</section>


<!-- CURRICULA -->
<section class="curricula-section" id="curricula">
  <div class="container">
    <div class="section-label">Supported curricula</div>
    <h2 class="section-title">One system.<br>Every curriculum,<br><em>worldwide.</em></h2>
    <p class="section-body" style="margin-top:12px;">Lumen maps topic overlaps, equivalencies, and transition pathways across all five major international curricula so no student is left behind.</p>
    <div class="curricula-grid">
      <div class="curricula-card">
        <div class="curricula-abbr">GCSE</div>
        <div class="curricula-full">General Certificate of Secondary Education</div>
        <div class="curricula-subjects">
          <span class="curricula-subject">Maths</span>
          <span class="curricula-subject">Biology</span>
          <span class="curricula-subject">Chemistry</span>
          <span class="curricula-subject">Physics</span>
          <span class="curricula-subject">English</span>
          <span class="curricula-subject">History</span>
          <span class="curricula-subject">Geography</span>
          <span class="curricula-subject">+14 more</span>
        </div>
      </div>
      <div class="curricula-card">
        <div class="curricula-abbr">IGCSE</div>
        <div class="curricula-full">International GCSE (Cambridge & Edexcel)</div>
        <div class="curricula-subjects">
          <span class="curricula-subject">Sciences</span>
          <span class="curricula-subject">Humanities</span>
          <span class="curricula-subject">Languages</span>
          <span class="curricula-subject">Commerce</span>
          <span class="curricula-subject">+12 more</span>
        </div>
      </div>
      <div class="curricula-card">
        <div class="curricula-abbr">A-level</div>
        <div class="curricula-full">Advanced Level (AQA, OCR, Edexcel)</div>
        <div class="curricula-subjects">
          <span class="curricula-subject">Maths</span>
          <span class="curricula-subject">Further Maths</span>
          <span class="curricula-subject">Sciences</span>
          <span class="curricula-subject">Economics</span>
          <span class="curricula-subject">Psychology</span>
          <span class="curricula-subject">+18 more</span>
        </div>
      </div>
      <div class="curricula-card">
        <div class="curricula-abbr">IB</div>
        <div class="curricula-full">International Baccalaureate Diploma</div>
        <div class="curricula-subjects">
          <span class="curricula-subject">HL & SL</span>
          <span class="curricula-subject">Group 1–6</span>
          <span class="curricula-subject">IA Support</span>
          <span class="curricula-subject">TOK</span>
          <span class="curricula-subject">EE</span>
          <span class="curricula-subject">+command terms</span>
        </div>
      </div>
      <div class="curricula-card">
        <div class="curricula-abbr">AP</div>
        <div class="curricula-full">Advanced Placement (College Board)</div>
        <div class="curricula-subjects">
          <span class="curricula-subject">MCQ</span>
          <span class="curricula-subject">FRQ</span>
          <span class="curricula-subject">Score 1–5</span>
          <span class="curricula-subject">Calc AB/BC</span>
          <span class="curricula-subject">Chem</span>
          <span class="curricula-subject">+22 exams</span>
        </div>
      </div>
    </div>
  </div>
</section>



<!-- PRICING -->
<section class="pricing-section" id="pricing">
  <div class="container">
    <div class="pricing-header">
      <div class="section-label">Pricing</div>
      <h2 class="section-title">One price.<br>Every feature.<br><em>Guaranteed</em> results.</h2>
      <p class="section-body" style="max-width:480px; margin:12px auto 0; text-align:center;">No feature tiers. No locked content. Every student gets the full AI engine from day one.</p>
    </div>
    <div class="pricing-grid">
      <div class="pricing-card">
        <div class="pricing-tier">Free Trial</div>
        <div class="pricing-price">
          <span class="price-currency">€</span>
          <span class="price-amount">0</span>
        </div>
        <div class="price-period">7 days, no card required</div>
        <p class="pricing-desc">Full access to the entire platform for 7 days. No commitment. No credit card needed. Cancel anytime before 7 days - no charge.</p>
        <div class="pricing-divider"></div>
        <ul class="pricing-features">
          <li class="pricing-feature"><span class="pricing-check">✓</span>Full diagnostic assessment</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>100 AI-marked practice questions</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>1 full exam simulation</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Revision notes &amp; past papers</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Dashboard &amp; grade prediction</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>All curricula (GCSE, A-level, IB, AP)</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Cancel anytime — no charge</li>
        </ul>
        <div style="font-size:12px; color:var(--ink-4); margin-bottom:16px; padding:8px 12px; background:var(--paper-2); border-radius:3px;">One-time trial per account. Non-repeatable.</div>
        <a href="#" class="pricing-btn">Start 7-day free trial &rarr;</a>
      </div>

      <div class="pricing-card recommended">
        <div class="pricing-badge">Most popular</div>
        <div class="pricing-tier">Annual</div>
        <div class="pricing-price">
          <span class="price-currency">€</span>
          <span class="price-amount">98</span>
        </div>
        <div class="price-period">per year — less than €0.27 per day</div>
        <p class="pricing-desc">Full unlimited access to every feature. The complete Lumen experience.</p>
        <div class="pricing-divider"></div>
        <ul class="pricing-features">
          <li class="pricing-feature"><span class="pricing-check">✓</span>Everything in Free, plus:</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Unlimited AI-marked questions</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Unlimited exam simulations</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Full spaced repetition system</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Exam technique engine + FRQ coaching</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Cross-curriculum transition maps</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Community + peer benchmarking</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Priority AI feedback (&lt;3 seconds)</li>
        </ul>
        <a href="#" class="pricing-btn">Start for €98/year →</a>
      </div>

      <div class="pricing-card">
        <div class="pricing-tier">Teaching / School</div>
        <div class="pricing-price" style="align-items:center; flex-wrap:wrap;">
          <span style="font-family:'Syne',sans-serif; font-size:28px; font-weight:800; color:var(--ink); letter-spacing:-1px;">Price on demand</span>
        </div>
        <div class="price-period">volume pricing for educators &amp; schools</div>
        <p class="pricing-desc">Custom pricing for schools, tutoring centres, teachers, and groups of 10 or more students. Contact us for a tailored quote.</p>
        <div class="pricing-divider"></div>
        <ul class="pricing-features">
          <li class="pricing-feature"><span class="pricing-check">✓</span>Everything in Annual, plus:</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Teacher admin dashboard</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Class performance analytics</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Custom exam dates & curricula</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>Dedicated account manager</li>
          <li class="pricing-feature"><span class="pricing-check">✓</span>LMS integration support</li>
        </ul>
        <a href="#" class="pricing-btn">Contact us for pricing →</a>
      </div>
    </div>
    <p class="pricing-note">All prices exclude VAT where applicable. Annual plan is billed once per year. Cancel anytime. Free trial is 7 days, non-repeatable (one per account), and can be cancelled before the 7 days with no charge.</p>
  </div>
</section>

<!-- FAQ -->
<section class="faq-section" id="faq">
  <div class="container">
    <div class="section-label">Questions</div>
    <h2 class="section-title">Frequently asked.</h2>
    <div class="faq-grid">

      <div class="faq-item" onclick="this.classList.toggle('open')">
        <div class="faq-q">Which exam boards and subjects are supported?<span class="faq-toggle">+</span></div>
        <p class="faq-a">We support AQA, OCR, Edexcel, Cambridge (IGCSE), and all IB subject groups at HL and SL. For AP, we cover all 38 College Board examinations including MCQ and FRQ components. New subjects are added continuously based on student demand.</p>
      </div>
      <div class="faq-item" onclick="this.classList.toggle('open')">
        <div class="faq-q">How does the AI marking work?<span class="faq-toggle">+</span></div>
        <p class="faq-a">Our marking AI is trained on thousands of real mark schemes, examiner reports, and annotated student responses across all curricula. It identifies which mark-scheme criteria your answer meets, which it misses, and precisely why — just as a real examiner would. Feedback appears in under 3 seconds per response.</p>
      </div>
      <div class="faq-item" onclick="this.classList.toggle('open')">
        <div class="faq-q">Can I use Lumen if I'm switching from GCSE to A-level or from A-level to IB?<span class="faq-toggle">+</span></div>
        <p class="faq-a">Yes — our cross-curriculum map is built exactly for this. It shows you which topics carry over, which are new, and where the expectations differ between curricula. Students transitioning from GCSE to A-level get a dedicated bridging pathway that fills conceptual gaps before their new course begins.</p>
      </div>
      <div class="faq-item" onclick="this.classList.toggle('open')">
        <div class="faq-q">Is there a mobile app?<span class="faq-toggle">+</span></div>
        <p class="faq-a">Lumen is fully mobile-optimized and works in any browser on iOS and Android without installation. Native apps for iOS and Android are in development and expected later this year. All progress syncs instantly across devices.</p>
      </div>

    </div>
  </div>
</section>

<!-- CTA -->
<section class="cta-section">
  <div class="section-label">Start today</div>
  <h2 class="cta-title">Your exam date<br>is not moving.<br><em>Neither should you.</em></h2>
  <p class="cta-sub">Join thousands of students who stopped wasting revision time and started training with purpose. 7 days free. No card required. Cancel anytime.</p>
  <div class="cta-actions">
    <a href="#pricing" class="btn-gold">Start your free trial →</a>
    <a href="#features" class="btn-ghost">Explore features</a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="container">
    <div class="footer-top">
      <div>
        <div style="display:flex;align-items:center;gap:9px;margin-bottom:12px;">
          <svg width="26" height="26" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="16" cy="16" r="15" stroke="#c8922a" stroke-width="1.2" fill="none" opacity="0.3"/>
            <circle cx="16" cy="16" r="10" stroke="#c8922a" stroke-width="1.2" fill="none" opacity="0.5"/>
            <line x1="16" y1="2" x2="16" y2="6" stroke="#c8922a" stroke-width="1.6" stroke-linecap="round"/>
            <line x1="16" y1="26" x2="16" y2="30" stroke="#c8922a" stroke-width="1.6" stroke-linecap="round"/>
            <line x1="2" y1="16" x2="6" y2="16" stroke="#c8922a" stroke-width="1.6" stroke-linecap="round"/>
            <line x1="26" y1="16" x2="30" y2="16" stroke="#c8922a" stroke-width="1.6" stroke-linecap="round"/>
            <line x1="5.5" y1="5.5" x2="8.3" y2="8.3" stroke="#c8922a" stroke-width="1.3" stroke-linecap="round" opacity="0.6"/>
            <line x1="23.7" y1="23.7" x2="26.5" y2="26.5" stroke="#c8922a" stroke-width="1.3" stroke-linecap="round" opacity="0.6"/>
            <line x1="26.5" y1="5.5" x2="23.7" y2="8.3" stroke="#c8922a" stroke-width="1.3" stroke-linecap="round" opacity="0.6"/>
            <line x1="8.3" y1="23.7" x2="5.5" y2="26.5" stroke="#c8922a" stroke-width="1.3" stroke-linecap="round" opacity="0.6"/>
            <circle cx="16" cy="16" r="4.5" fill="#c8922a" opacity="0.85"/>
            <circle cx="16" cy="16" r="2.5" fill="#f5e9d0"/>
          </svg>
          <div class="footer-brand">Lumen</div>
        </div>
        <p class="footer-tagline">The intelligent exam coach for GCSE, IGCSE, A-level, IB, and AP students worldwide. Built to guarantee measurable grade improvement.</p>
      </div>
      <div>
        <div class="footer-col-title">Platform</div>
        <ul class="footer-links">
          <li><a href="#">Features</a></li>
          <li><a href="#">Curricula</a></li>
          <li><a href="#">Exam Simulation</a></li>
          <li><a href="#">AI Marking</a></li>
          <li><a href="#">Pricing</a></li>
        </ul>
      </div>
      <div>
        <div class="footer-col-title">Company</div>
        <ul class="footer-links">
          <li><a href="#">About</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Careers</a></li>
          <li><a href="#">Schools</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </div>
      <div>
        <div class="footer-col-title">Support</div>
        <ul class="footer-links">
          <li><a href="#">Help centre</a></li>
          <li><a href="#">Subject requests</a></li>
          <li><a href="#">Accessibility</a></li>
          <li><a href="#">Status</a></li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <span class="footer-copy">© 2025 Lumen. All rights reserved.</span>
      <div class="footer-legal">
        <a href="#">Privacy</a>
        <a href="#">Terms</a>
        <a href="#">Cookies</a>
        <a href="#" onclick="adminPortalOpen();return false;" style="opacity:0.3;">⬡ Admin</a>
      </div>
    </div>
  </div>
</footer>

<script>
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        e.target.style.opacity = '1';
        e.target.style.transform = 'translateY(0)';
        e.target.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
      }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('.feature-card, .how-step, .curricula-card, .pricing-card, .faq-item, .problem-item').forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(20px)';
    observer.observe(el);
  });

  // ===== MOTIVATIONAL MESSAGES =====
  const MOTIV = [
    "The expert in anything was once a beginner. Every question you answer today is a mark you secure for exam day.",
    "Consistency beats intensity. Thirty minutes every day will outperform a frantic all-nighter every time.",
    "You don't rise to the level of your goals — you fall to the level of your systems. Build the system today.",
    "The examiner isn't looking for perfection. They're looking for the right keywords, applied correctly. You can learn that.",
    "Every hard topic you master is a topic your competition hasn't. That gap moves grades.",
    "Revision isn't about reading more. It's about remembering more. Active recall is the only way.",
    "The gap between where you are and where you want to be is closed one session at a time.",
    "Don't just know the content — know how to write it under pressure. That's what separates A from A*.",
    "Every question you mark wrong today is a mark you won't lose in the real exam. Mistakes here are free.",
    "Focus on the process. The grade is a lagging indicator of the work you're doing right now.",
    "Progress isn't always visible on a single day. But it compounds. Keep showing up.",
    "The best students aren't the cleverest — they're the most consistent. Today is another day to prove that.",
    "Your brain forms memories through retrieval, not reading. Every flashcard review is neural architecture.",
    "Exam technique is a learnable skill, not a talent. Every student who studies mark schemes improves.",
    "Hard work compounds like interest. The effort you put in this week pays off for the rest of the year.",
    "Don't fear difficult topics. Fear the habit of avoiding them. Lean in — that's where your grade lives.",
    "You already know more than you think. The diagnostic shows you what to do next, not to judge you.",
    "Every past paper you complete is data. Use it to train, not to stress.",
    "The moment you understand why an answer is wrong is worth more than a hundred correct guesses.",
    "Precision in language wins marks. Learn the exact words the examiner wants — then use them every time.",
    "Pressure is a privilege. Your exam is a chance to show what you've built. Build it well.",
    "Sleep and revision aren't in competition. Memory consolidation happens during sleep. Both are the job.",
    "One hour of full focus beats four hours with a phone in your hand. Quality always wins.",
    "The mark scheme is the secret code to your exam. Treat it like the most important document you own.",
    "Small wins compound. One good session today. One tomorrow. Watch what happens in 30 days.",
    "You are not behind. You are exactly where your current effort has put you. Change the effort, change the outcome.",
    "Academic excellence is not a personality trait. It is a series of decisions made consistently over time.",
    "When you feel like stopping, remember: your competition might be stopping too. Don't.",
    "Every subject has a logic to it. Find the logic, and the content becomes easy to remember.",
    "Exam day is just a performance. What you're doing right now is rehearsal. Rehearse well.",
    "The work you do today, when no one is watching, is the work that changes the grade on results day."
  ];

  // ===== NOTES DATA =====
  const NOTES = {
    'al-chem': {
      title: 'A-Level Chemistry',
      sub: 'AQA / OCR / Edexcel · Full syllabus coverage',
      sections: [
        { h: '1. Atomic Structure & Periodicity', body: `<p>Atoms consist of protons, neutrons, and electrons. The atomic number (Z) defines the element; mass number (A) = protons + neutrons. Isotopes are atoms of the same element with different neutron numbers.</p><p>Electron configuration follows the Aufbau principle, Pauli exclusion, and Hund's rule. Sub-shells fill in order: 1s, 2s, 2p, 3s, 3p, 4s, 3d...</p><div class="notes-formula">1s² 2s² 2p⁶ 3s² 3p⁶ 4s² 3d¹⁰</div><p>Ionisation energies increase across a period (nuclear charge) and decrease down a group (shielding + atomic radius). Anomalies exist between groups 2 and 3, and 5 and 6.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=W5sGbNm4KOo" target="_blank">Electron Configuration — Tyler DeWitt</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=thnDxFdkzZs" target="_blank">Ionisation Energy Trends — Richard Thornley</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=9Ql-sRIjfaU" target="_blank">Periodic Table Trends — Cognito</a></div>` },
        { h: '2. Chemical Bonding & Molecular Geometry', body: `<p>Ionic bonding: electrostatic attraction between oppositely charged ions. Covalent: shared electron pairs. Metallic: lattice of positive ions in delocalised electron sea.</p><p>Bond polarity: unequal sharing due to electronegativity differences (Pauling scale; F = 4.0). A polar bond doesn't always mean a polar molecule — check symmetry.</p><p>VSEPR: electron pairs repel to maximise separation. Lone pairs repel more than bonding pairs. Bond angles: tetrahedral 109.5°, trigonal planar 120°, linear 180°, pyramidal ~107°, bent ~104.5°.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=8qZL7KPi-d8" target="_blank">Ionic vs Covalent — Crash Course Chemistry</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=Moj85zwdULg" target="_blank">VSEPR Theory — Tyler DeWitt</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=1BqDlmY-jvU" target="_blank">Intermolecular Forces — Richard Thornley</a></div>` },
        { h: '3. Organic Mechanisms', body: `<p>Curly arrows show electron pair movement — always from electron source to electron sink. Half-arrows show single electron movement (radical reactions).</p><ul><li><strong>Nucleophilic Substitution (SN1/SN2):</strong> SN2 = one-step, backside attack, inversion of configuration. SN1 = two-step, via carbocation, racemisation.</li><li><strong>Electrophilic Addition:</strong> Electrophile attacks double bond forming a carbocation intermediate. Markovnikov's rule applies.</li><li><strong>Electrophilic Aromatic Substitution:</strong> Benzene ring acts as nucleophile; electrophile replaces H (nitration, Friedel-Crafts acylation/alkylation).</li><li><strong>Nucleophilic Addition:</strong> Nucleophile attacks carbonyl carbon (aldehydes/ketones). E.g. KCN + aldehyde → hydroxynitrile.</li></ul><div class="notes-formula">Markovnikov: H adds to the C with more H atoms already attached</div><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=E7T1ZlOLm9I" target="_blank">SN1 & SN2 — Khan Academy</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=mfLHSMxl1Fo" target="_blank">A-Level Organic Mechanisms — ChemRevise</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=RIvNjhS9fmw" target="_blank">Electrophilic Addition Detailed — FreeDoc</a></div>` },
        { h: '4. Equilibria & Kp / Kc Calculations', body: `<p>Dynamic equilibrium: forward and reverse rates equal. Le Chatelier's Principle: the system shifts to oppose any imposed change.</p><div class="notes-formula">Kc = [products]^n / [reactants]^n &nbsp;(mol dm⁻³)</div><div class="notes-formula">Kp = (partial pressure products)^n / (partial pressure reactants)^n</div><p>Large K (>1) → products favoured. Small K (<1) → reactants favoured. Temperature changes the VALUE of K. Concentration/pressure shifts only change position of equilibrium, not K.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=ANi709NF4KA" target="_blank">Kc Equilibrium Constants — Khan Academy</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=1-eJoHnRiDQ" target="_blank">Kp Calculations — Richard Thornley</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=vBKHwvnMUos" target="_blank">Le Chatelier's Principle — Cognito</a></div>` },
        { h: '5. Transition Metals & Electrode Potentials', body: `<p>Transition metals have partially filled d sub-shells in ≥1 oxidation state. Properties: variable oxidation states, coloured ions, catalytic activity, complex ion formation.</p><p>Complex ions: central metal + ligands (electron-pair donors). Monodentate (NH₃, Cl⁻), bidentate (en, ethanedioate), polydentate (EDTA⁴⁻). Shape depends on coordination number: octahedral (6), tetrahedral (4), square planar (4 Pt/Ni).</p><div class="notes-formula">E°cell = E°cathode − E°anode</div><p>A positive E°cell = spontaneous reaction under standard conditions. The electrochemical series ranks half-equations by E° value.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=tMQM7Q8hH8Y" target="_blank">Transition Metals Overview — A-Level Chemistry</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=0TXLTJbqFlI" target="_blank">Electrode Potentials — Richard Thornley</a></div>` }
      ]
    },
    'gcse-bio': {
      title: 'GCSE Biology',
      sub: 'AQA / OCR / Edexcel · Full syllabus',
      sections: [
        { h: '1. Cell Biology', body: `<p>Animal cells: nucleus, cytoplasm, cell membrane, mitochondria, ribosomes. Plant cells additionally: cell wall (cellulose), chloroplasts, permanent vacuole. Prokaryotes (bacteria): no membrane-bound nucleus, plasmids, flagellum.</p><div class="notes-formula">Magnification = Image size ÷ Actual size</div><p>Cell specialisation: red blood cells (no nucleus, biconcave), sperm (flagellum, mitochondria), nerve cells (axon, dendrites), root hair cells (large surface area).</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=URUJD5NEXC8" target="_blank">Cell Structure — Cognito</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=8Zs7ZHERyKA" target="_blank">Prokaryotic vs Eukaryotic — Amoeba Sisters</a></div>` },
        { h: '2. Genetics & Inheritance', body: `<p>DNA: double helix of nucleotides. Bases: A-T, G-C. Genes = sections of DNA coding for proteins. Alleles = versions of a gene. Dominant expressed with 1 copy; recessive requires 2 copies.</p><p>Monohybrid crosses use Punnett squares. Codominance: both alleles expressed (e.g. AB blood type). Sex-linked conditions: alleles on X chromosome (e.g. colour blindness, haemophilia).</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=8mfpFbTFwC0" target="_blank">Genetics Basics — Cognito</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=CBezq1fFUEA" target="_blank">DNA Structure — Tyler DeWitt</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=NWqgZUnJdAY" target="_blank">Inheritance & Punnett Squares — Freesciencelessons</a></div>` },
        { h: '3. Bioenergetics: Photosynthesis & Respiration', body: `<p>Photosynthesis: light energy → chemical energy. Chlorophyll absorbs light. Rate limited by: light intensity, CO₂ concentration, temperature.</p><div class="notes-formula">6CO₂ + 6H₂O → C₆H₁₂O₆ + 6O₂ (light energy)</div><p>Aerobic respiration: releases energy from glucose using oxygen. Anaerobic: in absence of O₂; produces lactic acid (animals) or ethanol + CO₂ (yeast/plants).</p><div class="notes-formula">C₆H₁₂O₆ + 6O₂ → 6CO₂ + 6H₂O + energy (ATP)</div><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=g78utcLQrJ4" target="_blank">Photosynthesis — Cognito</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=Gh2P5CmCC0M" target="_blank">Respiration — Freesciencelessons</a></div>` }
      ]
    },
    'gcse-chem': {
      title: 'GCSE Chemistry',
      sub: 'AQA / OCR / Edexcel · Full syllabus',
      sections: [
        { h: '1. Atomic Structure', body: `<p>Protons (+1, 1 amu), neutrons (0, 1 amu), electrons (-1, negligible) in nucleus + shells. Atomic number = protons. Mass number = protons + neutrons. Isotopes: same protons, different neutrons.</p><p>Electronic configuration: 2, 8, 8... Group number = outer electrons. Period = number of shells. Noble gases: full outer shell.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=VBM9yBLnbDY" target="_blank">Atomic Structure — Cognito</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=xris9A4IFsQ" target="_blank">Isotopes Explained — Tyler DeWitt</a></div>` },
        { h: '2. Quantitative Chemistry', body: `<p>Moles = mass ÷ Mr. Avogadro's constant = 6.02 × 10²³ particles per mole. Concentration (mol/dm³) = moles ÷ volume (dm³).</p><div class="notes-formula">moles = mass / Mr</div><div class="notes-formula">moles = concentration × volume (dm³)</div><p>Atom economy = (Mr desired product / sum Mr all products) × 100. Higher = less waste = more sustainable.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=molar-mass" target="_blank">Moles Calculations — Cognito</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=UL1jmJaUkaQ" target="_blank">Mole Concept — Tyler DeWitt</a></div>` }
      ]
    },
    'al-bio': {
      title: 'A-Level Biology',
      sub: 'AQA / OCR / Edexcel · Full syllabus',
      sections: [
        { h: '1. Cell Structure & Microscopy', body: `<p>Eukaryotic organelles: nucleus (DNA + gene expression), mitochondria (ATP synthesis), ribosomes (protein synthesis), ER (rough = ribosomes; smooth = lipid processing), Golgi (protein modification/secretion), lysosomes (hydrolytic enzymes), chloroplasts (photosynthesis).</p><div class="notes-formula">Resolution limit of light microscope: ~200 nm · Electron microscope: ~0.1 nm</div><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=4OpBylwH9DU" target="_blank">A-Level Cell Organelles — Cognito</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=oiCtjHmg_4M" target="_blank">Cell Ultrastructure — Freesciencelessons</a></div>` },
        { h: '2. Genetics & Gene Expression', body: `<p>DNA replication: semi-conservative; helicase unwinds, DNA polymerase adds complementary nucleotides 5'→3'. Transcription: DNA → mRNA (nucleus). Translation: mRNA → polypeptide at ribosomes (codons read by tRNA anticodons).</p><p>Gene mutations: substitution (may change 1 amino acid or be silent), deletion/insertion (frameshift — changes all subsequent amino acids).</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=gG7uCskUOrA" target="_blank">DNA Replication — Amoeba Sisters</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=itsb2SqR-R0" target="_blank">Transcription & Translation — Cognito</a></div>` }
      ]
    },
    'ap-bio': {
      title: 'AP Biology',
      sub: 'College Board · Full curriculum · MCQ & FRQ technique',
      sections: [
        { h: '1. Evolution & Natural Selection', body: `<p>Natural selection: heritable variation + differential reproductive success → allele frequency change over generations. Evidence: fossil record, homologous structures, molecular biology (shared DNA sequences), biogeography.</p><div class="notes-formula">Hardy-Weinberg: p² + 2pq + q² = 1, and p + q = 1</div><p>H-W assumes no mutation, no natural selection, random mating, no gene flow, large population. Deviations indicate evolution is occurring.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=GcjgWov7mTM" target="_blank">Natural Selection — Amoeba Sisters</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=P3LMKZ1bMYE" target="_blank">Hardy-Weinberg Equilibrium — Bozeman Science</a></div>` },
        { h: '2. Cell Communication & Signal Transduction', body: `<p>Signal transduction: ligand binds receptor → intracellular cascade → cellular response. Three stages: reception, transduction, response.</p><p>G-protein coupled receptors: signal activates G protein → adenylyl cyclase → cAMP (second messenger) → protein kinase A cascade. Receptor tyrosine kinases: dimerisation → autophosphorylation → multiple downstream pathways.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=3Cjm9a3mJow" target="_blank">Signal Transduction — Bozeman Science</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=lQMqrrmobKE" target="_blank">Cell Signaling Pathways — Khan Academy</a></div>` },
        { h: '3. FRQ Writing Technique', body: `<p>AP Biology FRQs are scored on a rubric — every point is binary. Examiners look for specific content, not essay quality.</p><ul><li><strong>Describe:</strong> State the feature specifically. "The graph shows an increase" is wrong. "The graph shows an increase in enzyme activity from 20°C to 40°C" is correct.</li><li><strong>Explain:</strong> Give the mechanism — cause AND effect. "Enzyme activity increases because higher temperatures provide more kinetic energy, increasing collision frequency between enzyme and substrate."</li><li><strong>Predict + justify:</strong> State outcome AND reasoning. Never leave a prediction without the "because."</li><li><strong>Calculate:</strong> Show formula, substitution, and units. Partial credit is available even with a wrong final answer.</li></ul><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=bkMa4fAWHZ0" target="_blank">AP Bio FRQ Strategies — Bozeman Science</a></div>` }
      ]
    },
    'ib-econ': {
      title: 'IB Economics',
      sub: 'IB Diploma · HL & SL · Command term training included',
      sections: [
        { h: '1. Microeconomics — Supply, Demand & Market Failure', body: `<p>Demand slopes down (law of diminishing marginal utility). Shifts in demand (non-price): income, price of related goods, tastes, expectations, population. Supply shifts: input costs, technology, number of firms, subsidies/taxes.</p><p>Market failure: externalities (MSC ≠ MPC or MSB ≠ MPB), public goods (non-rival, non-excludable), information asymmetry, monopoly power.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=VVp8UGjECt4" target="_blank">Supply & Demand — Jacob Clifford</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=6KCjEOtHqTA" target="_blank">Market Failure — EconplusDal</a></div>` },
        { h: '2. Macroeconomics — AD/AS & Policy', body: `<p>AD = C + I + G + (X-M). Shifts: confidence, interest rates, government spending, exchange rate, trading partner growth. SRAS shifts: input costs, productivity. LRAS = potential output (structural).</p><p>Demand-side policy: fiscal (G, T) and monetary (interest rates, QE). Supply-side: education, infrastructure, deregulation, privatisation.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=jV4bwRBr2Cs" target="_blank">AD/AS Model — EconplusDal</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=C0tHNLy7Z2Q" target="_blank">Fiscal vs Monetary Policy — Jacob Clifford</a></div>` },
        { h: '3. IB Command Terms — Essential for Full Marks', body: `<ul><li><strong>Define:</strong> Give the precise meaning of a concept.</li><li><strong>Explain:</strong> Give a detailed account with reasons and/or evidence — a chain of reasoning is expected.</li><li><strong>Distinguish:</strong> Make clear the differences between two or more concepts.</li><li><strong>Evaluate:</strong> Appraise by weighing strengths and limitations — you MUST reach a justified conclusion.</li><li><strong>Discuss:</strong> Offer a balanced review with a range of arguments from different perspectives — avoid one-sided answers.</li><li><strong>Examine:</strong> Consider an argument or concept in a way that uncovers assumptions and relationships.</li></ul><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=LZwEIiwgpJo" target="_blank">IB Economics Command Terms — EconplusDal</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=_1slyMI2T9Y" target="_blank">How to Write IB Econ Essays — Brad Cartwright</a></div>` }
      ]
    },
    'al-maths': {
      title: 'A-Level Mathematics',
      sub: 'AQA / Edexcel / OCR · Pure, Statistics & Mechanics',
      sections: [
        { h: '1. Calculus — Differentiation & Integration', body: `<p>Differentiation from first principles: f'(x) = lim[h→0] (f(x+h)-f(x))/h. Power rule: d/dx(xⁿ) = nxⁿ⁻¹. Chain, product, quotient rules for composite and combined functions.</p><div class="notes-formula">∫xⁿ dx = xⁿ⁺¹/(n+1) + C &nbsp;(n ≠ -1)</div><p>Integration by substitution and by parts (∫u dv = uv - ∫v du). Definite integrals give area; areas below x-axis are negative — split and add absolute values.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=rAof9Ld5sOg" target="_blank">A-Level Differentiation — ExamSolutions</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=rfG8ze6B_uI" target="_blank">Integration by Parts — ExamSolutions</a></div>` },
        { h: '2. Algebra & Proof', body: `<p>Proof by deduction: build a logical chain from axioms. Proof by exhaustion: check all cases. Proof by contradiction: assume negation is true, derive contradiction. Disproof by counterexample: find one case where statement fails.</p><p>Binomial expansion: (1+x)ⁿ = 1 + nx + n(n-1)x²/2! + ... Valid for |x| < 1 when n is not a positive integer.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=r5I6hk4pBas" target="_blank">Mathematical Proof — Dr Frost Maths</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=95xRgQ7v9P4" target="_blank">Binomial Expansion — ExamSolutions</a></div>` }
      ]
    },
    'ib-chem': {
      title: 'IB Chemistry',
      sub: 'IB Diploma · HL & SL · All topics + HL extensions',
      sections: [
        { h: '1. Stoichiometry & Mole Concept', body: `<p>Molar mass = relative atomic/molecular mass in g/mol. n = m/M. Avogadro's constant = 6.02 × 10²³ mol⁻¹. Empirical formula = simplest whole-number ratio of atoms.</p><div class="notes-formula">n = m/M &nbsp;|&nbsp; n = cV &nbsp;|&nbsp; n = PV/RT (ideal gas)</div><p>Limiting reagent: calculate moles of each reactant, compare ratio to equation, identify which runs out first. % yield = (actual/theoretical) × 100.</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=VR8ox9P47uo" target="_blank">Stoichiometry — Tyler DeWitt</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=K_SKMb_yXpU" target="_blank">Limiting Reagent — Tyler DeWitt</a></div>` }
      ]
    },
    'ap-calc': {
      title: 'AP Calculus AB/BC',
      sub: 'College Board · AB & BC · FRQ strategies included',
      sections: [
        { h: '1. Limits & Continuity', body: `<p>A limit describes the value a function approaches as x→a. Limit exists if left and right limits agree. L'Hôpital's Rule: if limit gives 0/0 or ∞/∞ form, differentiate numerator and denominator separately.</p><p>Continuity requires: f(a) defined, lim[x→a] f(x) exists, and they are equal. Intermediate Value Theorem: if f continuous on [a,b], it takes every value between f(a) and f(b).</p><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=kfF40MiS7zA" target="_blank">Limits Introduction — Khan Academy</a><a class="yt-vid-link" href="https://www.youtube.com/watch?v=HfACrKJ_Y2w" target="_blank">L'Hôpital's Rule — PatrickJMT</a></div>` },
        { h: '2. FRQ Strategies for Calculus', body: `<p>Show all work — partial credit is available even with arithmetic errors. Label every answer with units where applicable.</p><ul><li><strong>Related rates:</strong> Write an equation, differentiate implicitly with respect to t, substitute known values AFTER differentiating.</li><li><strong>Accumulation/FTC:</strong> Clearly state which version of FTC you are using. F(b)-F(a) or d/dx ∫.</li><li><strong>Differential equations:</strong> Separate variables, integrate both sides (include + C), apply initial condition to solve for C.</li></ul><div class="yt-vids"><div class="yt-vids-label">Recommended Videos</div><a class="yt-vid-link" href="https://www.youtube.com/watch?v=M2M67nfkuCI" target="_blank">AP Calculus FRQ Tips — Krista King</a></div>` }
      ]
    }
  };

  // ===== PAPERS DATA =====
  const PAPERS = {
    gcse: [
      { subj: 'GCSE Biology — AQA', rows: [
        ['2023','Paper 1 (Foundation & Higher)','https://www.aqa.org.uk/subjects/science/gcse/biology-8461/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/biology-8461/assessment-resources'],
        ['2023','Paper 2 (Foundation & Higher)','https://www.aqa.org.uk/subjects/science/gcse/biology-8461/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/biology-8461/assessment-resources'],
        ['2022','Paper 1 (Higher)','https://www.aqa.org.uk/subjects/science/gcse/biology-8461/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/biology-8461/assessment-resources'],
        ['2019','Paper 2 (Foundation)','https://www.aqa.org.uk/subjects/science/gcse/biology-8461/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/biology-8461/assessment-resources'],
      ]},
      { subj: 'GCSE Chemistry — AQA', rows: [
        ['2023','Paper 1 (Higher)','https://www.aqa.org.uk/subjects/science/gcse/chemistry-8462/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/chemistry-8462/assessment-resources'],
        ['2023','Paper 2 (Higher)','https://www.aqa.org.uk/subjects/science/gcse/chemistry-8462/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/chemistry-8462/assessment-resources'],
        ['2022','Paper 1 (Foundation)','https://www.aqa.org.uk/subjects/science/gcse/chemistry-8462/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/chemistry-8462/assessment-resources'],
      ]},
      { subj: 'GCSE Mathematics — Edexcel', rows: [
        ['2023','Paper 1 Non-Calculator (Higher)','https://qualifications.pearson.com/en/qualifications/edexcel-gcses/mathematics-2015.coursematerials.html','https://qualifications.pearson.com/en/qualifications/edexcel-gcses/mathematics-2015.coursematerials.html'],
        ['2023','Paper 2 Calculator (Higher)','https://qualifications.pearson.com/en/qualifications/edexcel-gcses/mathematics-2015.coursematerials.html','https://qualifications.pearson.com/en/qualifications/edexcel-gcses/mathematics-2015.coursematerials.html'],
        ['2023','Paper 3 Calculator (Foundation)','https://qualifications.pearson.com/en/qualifications/edexcel-gcses/mathematics-2015.coursematerials.html','https://qualifications.pearson.com/en/qualifications/edexcel-gcses/mathematics-2015.coursematerials.html'],
        ['2022','Paper 1 Non-Calculator (Higher)','https://qualifications.pearson.com/en/qualifications/edexcel-gcses/mathematics-2015.coursematerials.html','https://qualifications.pearson.com/en/qualifications/edexcel-gcses/mathematics-2015.coursematerials.html'],
      ]},
      { subj: 'GCSE Physics — AQA', rows: [
        ['2023','Paper 1 (Higher)','https://www.aqa.org.uk/subjects/science/gcse/physics-8463/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/physics-8463/assessment-resources'],
        ['2023','Paper 2 (Higher)','https://www.aqa.org.uk/subjects/science/gcse/physics-8463/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/physics-8463/assessment-resources'],
        ['2022','Paper 1 (Foundation)','https://www.aqa.org.uk/subjects/science/gcse/physics-8463/assessment-resources','https://www.aqa.org.uk/subjects/science/gcse/physics-8463/assessment-resources'],
      ]},
    ],
    alevel: [
      { subj: 'A-Level Chemistry — AQA', rows: [
        ['2023','Paper 1','https://www.aqa.org.uk/subjects/chemistry/a-level/chemistry-7405/assessment-resources','https://www.aqa.org.uk/subjects/chemistry/a-level/chemistry-7405/assessment-resources'],
        ['2023','Paper 2','https://www.aqa.org.uk/subjects/chemistry/a-level/chemistry-7405/assessment-resources','https://www.aqa.org.uk/subjects/chemistry/a-level/chemistry-7405/assessment-resources'],
        ['2023','Paper 3','https://www.aqa.org.uk/subjects/chemistry/a-level/chemistry-7405/assessment-resources','https://www.aqa.org.uk/subjects/chemistry/a-level/chemistry-7405/assessment-resources'],
        ['2022','Paper 1','https://www.aqa.org.uk/subjects/chemistry/a-level/chemistry-7405/assessment-resources','https://www.aqa.org.uk/subjects/chemistry/a-level/chemistry-7405/assessment-resources'],
      ]},
      { subj: 'A-Level Biology — AQA', rows: [
        ['2023','Paper 1','https://www.aqa.org.uk/subjects/biology/a-level/biology-7402/assessment-resources','https://www.aqa.org.uk/subjects/biology/a-level/biology-7402/assessment-resources'],
        ['2023','Paper 2','https://www.aqa.org.uk/subjects/biology/a-level/biology-7402/assessment-resources','https://www.aqa.org.uk/subjects/biology/a-level/biology-7402/assessment-resources'],
        ['2023','Paper 3','https://www.aqa.org.uk/subjects/biology/a-level/biology-7402/assessment-resources','https://www.aqa.org.uk/subjects/biology/a-level/biology-7402/assessment-resources'],
      ]},
      { subj: 'A-Level Mathematics — Edexcel', rows: [
        ['2023','Paper 1 Pure Mathematics','https://qualifications.pearson.com/en/qualifications/edexcel-a-levels/mathematics-2017.coursematerials.html','https://qualifications.pearson.com/en/qualifications/edexcel-a-levels/mathematics-2017.coursematerials.html'],
        ['2023','Paper 2 Pure + Statistics','https://qualifications.pearson.com/en/qualifications/edexcel-a-levels/mathematics-2017.coursematerials.html','https://qualifications.pearson.com/en/qualifications/edexcel-a-levels/mathematics-2017.coursematerials.html'],
        ['2023','Paper 3 Pure + Mechanics','https://qualifications.pearson.com/en/qualifications/edexcel-a-levels/mathematics-2017.coursematerials.html','https://qualifications.pearson.com/en/qualifications/edexcel-a-levels/mathematics-2017.coursematerials.html'],
      ]},
      { subj: 'A-Level Physics — AQA', rows: [
        ['2023','Paper 1','https://www.aqa.org.uk/subjects/physics/a-level/physics-7408/assessment-resources','https://www.aqa.org.uk/subjects/physics/a-level/physics-7408/assessment-resources'],
        ['2023','Paper 2','https://www.aqa.org.uk/subjects/physics/a-level/physics-7408/assessment-resources','https://www.aqa.org.uk/subjects/physics/a-level/physics-7408/assessment-resources'],
        ['2023','Paper 3A/3B','https://www.aqa.org.uk/subjects/physics/a-level/physics-7408/assessment-resources','https://www.aqa.org.uk/subjects/physics/a-level/physics-7408/assessment-resources'],
      ]},
      { subj: 'A-Level Economics — AQA', rows: [
        ['2023','Paper 1: Markets & Market Failure','https://www.aqa.org.uk/subjects/economics/a-level/economics-7136/assessment-resources','https://www.aqa.org.uk/subjects/economics/a-level/economics-7136/assessment-resources'],
        ['2023','Paper 2: National & International Economy','https://www.aqa.org.uk/subjects/economics/a-level/economics-7136/assessment-resources','https://www.aqa.org.uk/subjects/economics/a-level/economics-7136/assessment-resources'],
        ['2023','Paper 3: Economic Principles & Issues','https://www.aqa.org.uk/subjects/economics/a-level/economics-7136/assessment-resources','https://www.aqa.org.uk/subjects/economics/a-level/economics-7136/assessment-resources'],
      ]},
    ],
    ib: [
      { subj: 'IB Biology HL — Paper 1, 2 & 3', rows: [
        ['2023','HL Paper 1 (MCQ)','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
        ['2023','HL Paper 2 (SAQ & essay)','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
        ['2023','HL Paper 3 (Option)','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
        ['2022','SL Paper 1','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
      ]},
      { subj: 'IB Chemistry HL — Paper 1, 2 & 3', rows: [
        ['2023','HL Paper 1','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
        ['2023','HL Paper 2','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
        ['2022','SL Paper 2','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
      ]},
      { subj: 'IB Economics HL — Paper 1, 2 & 3', rows: [
        ['2023','HL Paper 1 (extended response)','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
        ['2023','HL Paper 2 (data response)','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
        ['2023','HL Paper 3 (policy)','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
      ]},
      { subj: 'IB Mathematics AA HL', rows: [
        ['2023','Paper 1','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
        ['2023','Paper 2','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
        ['2023','Paper 3 (HL only)','https://www.ibdocuments.com/','https://www.ibdocuments.com/'],
      ]},
    ],
    ap: [
      { subj: 'AP Biology — College Board', rows: [
        ['2024','Full Exam (MCQ + FRQ)','https://apstudents.collegeboard.org/courses/ap-biology/assessment','https://apstudents.collegeboard.org/courses/ap-biology/assessment'],
        ['2023','Full Exam (MCQ + FRQ)','https://apstudents.collegeboard.org/courses/ap-biology/assessment','https://apstudents.collegeboard.org/courses/ap-biology/assessment'],
        ['2022','Full Exam','https://apstudents.collegeboard.org/courses/ap-biology/assessment','https://apstudents.collegeboard.org/courses/ap-biology/assessment'],
      ]},
      { subj: 'AP Calculus AB — College Board', rows: [
        ['2024','Full Exam (MCQ + FRQ)','https://apstudents.collegeboard.org/courses/ap-calculus-ab/assessment','https://apstudents.collegeboard.org/courses/ap-calculus-ab/assessment'],
        ['2023','Full Exam','https://apstudents.collegeboard.org/courses/ap-calculus-ab/assessment','https://apstudents.collegeboard.org/courses/ap-calculus-ab/assessment'],
      ]},
      { subj: 'AP Chemistry — College Board', rows: [
        ['2024','Full Exam (MCQ + FRQ)','https://apstudents.collegeboard.org/courses/ap-chemistry/assessment','https://apstudents.collegeboard.org/courses/ap-chemistry/assessment'],
        ['2023','Full Exam','https://apstudents.collegeboard.org/courses/ap-chemistry/assessment','https://apstudents.collegeboard.org/courses/ap-chemistry/assessment'],
        ['2022','Full Exam','https://apstudents.collegeboard.org/courses/ap-chemistry/assessment','https://apstudents.collegeboard.org/courses/ap-chemistry/assessment'],
      ]},
      { subj: 'AP US History — College Board', rows: [
        ['2024','Full Exam (MCQ + SAQ + DBQ + LEQ)','https://apstudents.collegeboard.org/courses/ap-united-states-history/assessment','https://apstudents.collegeboard.org/courses/ap-united-states-history/assessment'],
        ['2023','Full Exam','https://apstudents.collegeboard.org/courses/ap-united-states-history/assessment','https://apstudents.collegeboard.org/courses/ap-united-states-history/assessment'],
      ]},
      { subj: 'AP Psychology — College Board', rows: [
        ['2024','Full Exam','https://apstudents.collegeboard.org/courses/ap-psychology/assessment','https://apstudents.collegeboard.org/courses/ap-psychology/assessment'],
        ['2023','Full Exam','https://apstudents.collegeboard.org/courses/ap-psychology/assessment','https://apstudents.collegeboard.org/courses/ap-psychology/assessment'],
      ]},
    ],
    igcse: [
      { subj: 'IGCSE Biology — Cambridge (0610)', rows: [
        ['2023','Paper 2 Core','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-biology-0610/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-biology-0610/past-papers/'],
        ['2023','Paper 4 Extended','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-biology-0610/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-biology-0610/past-papers/'],
        ['2022','Paper 2 Core','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-biology-0610/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-biology-0610/past-papers/'],
      ]},
      { subj: 'IGCSE Chemistry — Cambridge (0620)', rows: [
        ['2023','Paper 2 Core','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-chemistry-0620/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-chemistry-0620/past-papers/'],
        ['2023','Paper 4 Extended','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-chemistry-0620/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-chemistry-0620/past-papers/'],
      ]},
      { subj: 'IGCSE Mathematics — Cambridge (0580)', rows: [
        ['2023','Paper 2 Core','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-mathematics-0580/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-mathematics-0580/past-papers/'],
        ['2023','Paper 4 Extended','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-mathematics-0580/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-mathematics-0580/past-papers/'],
        ['2022','Paper 4 Extended','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-mathematics-0580/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-mathematics-0580/past-papers/'],
      ]},
      { subj: 'IGCSE Physics — Cambridge (0625)', rows: [
        ['2023','Paper 4 Extended','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-physics-0625/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-physics-0625/past-papers/'],
        ['2023','Paper 2 Core','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-physics-0625/past-papers/','https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-igcse-physics-0625/past-papers/'],
      ]},
    ]
  };

  // ===== INIT =====
  document.addEventListener('DOMContentLoaded', () => {
    // Set daily motivation quote
    const q = document.getElementById('fdash-quote');
    if (q) { const d = new Date().getDate() - 1; q.textContent = '"' + MOTIV[d % MOTIV.length] + '"'; }
    // Init papers panel with GCSE
    renderPapers('gcse');
    // Tab click
    document.querySelectorAll('.fdash-nav').forEach(nav => {
      nav.addEventListener('click', () => {
        document.querySelectorAll('.fdash-nav').forEach(n => n.classList.remove('active'));
        document.querySelectorAll('.fdash-panel').forEach(p => p.classList.remove('active'));
        nav.classList.add('active');
        const panelId = 'fdash-' + nav.dataset.panel;
        const panel = document.getElementById(panelId);
        if (panel) panel.classList.add('active');
      });
    });
  });

  // ===== NOTES FUNCTIONS =====
  function filterSubjects(c, btn) {
    document.querySelectorAll('.notes-filt-btn').forEach(b => b.classList.remove('on'));
    btn.classList.add('on');
    document.querySelectorAll('.subj-card').forEach(card => {
      card.style.display = (c === 'all' || card.dataset.c === c) ? '' : 'none';
    });
  }

  function openSubject(id) {
    const data = NOTES[id];
    const listEl = document.getElementById('notes-list');
    const detailEl = document.getElementById('notes-detail');
    const bodyEl = document.getElementById('notes-detail-body');
    if (!data) {
      bodyEl.innerHTML = '<div class="notes-dtitle">Notes coming soon</div><div class="notes-dsub">Full notes for this subject are being finalised. Check back shortly.</div>';
    } else {
      let html = '<div class="notes-dtitle">' + data.title + '</div><div class="notes-dsub">' + data.sub + '</div>';
      data.sections.forEach(s => {
        html += '<div class="notes-section"><div class="notes-sec-title">' + s.h + '</div>' + s.body + '</div>';
      });
      bodyEl.innerHTML = html;
    }
    listEl.style.display = 'none';
    detailEl.classList.add('on');
  }

  function closeSubject() {
    document.getElementById('notes-list').style.display = '';
    document.getElementById('notes-detail').classList.remove('on');
  }


  // ===== PDF REVISION NOTES CATALOG =====
  const PDF_CATALOG = [
  {
    "filename": "gcse_biology_aqa_v2.pdf",
    "title": "GCSE Biology",
    "curriculum": "GCSE",
    "subject": "Biology",
    "board": "AQA 8461",
    "size_kb": 67
  },
  {
    "filename": "gcse_biology_FINAL.pdf",
    "title": "GCSE Biology (Illustrated)",
    "curriculum": "GCSE",
    "subject": "Biology",
    "board": "AQA 8461",
    "size_kb": 18
  },
  {
    "filename": "gcse_chemistry_aqa.pdf",
    "title": "GCSE Chemistry",
    "curriculum": "GCSE",
    "subject": "Chemistry",
    "board": "AQA 8462",
    "size_kb": 45
  },
  {
    "filename": "gcse_chemistry_aqa_v2.pdf",
    "title": "GCSE Chemistry (Extended)",
    "curriculum": "GCSE",
    "subject": "Chemistry",
    "board": "AQA 8462",
    "size_kb": 17
  },
  {
    "filename": "gcse_physics_v3.pdf",
    "title": "GCSE Physics",
    "curriculum": "GCSE",
    "subject": "Physics",
    "board": "AQA 8463",
    "size_kb": 51
  },
  {
    "filename": "gcse_physics_FINAL.pdf",
    "title": "GCSE Physics (Illustrated)",
    "curriculum": "GCSE",
    "subject": "Physics",
    "board": "AQA 8463",
    "size_kb": 12
  },
  {
    "filename": "gcse_mathematics_v3.pdf",
    "title": "GCSE Mathematics",
    "curriculum": "GCSE",
    "subject": "Mathematics",
    "board": "AQA/Edexcel/OCR",
    "size_kb": 18
  },
  {
    "filename": "gcse_english_literature.pdf",
    "title": "GCSE English Literature",
    "curriculum": "GCSE",
    "subject": "English",
    "board": "AQA 8702",
    "size_kb": 11
  },
  {
    "filename": "gcse_history_aqa.pdf",
    "title": "GCSE History",
    "curriculum": "GCSE",
    "subject": "History",
    "board": "AQA 8145",
    "size_kb": 11
  },
  {
    "filename": "alevel_biology_FINAL.pdf",
    "title": "A-Level Biology (Illustrated)",
    "curriculum": "A-Level",
    "subject": "Biology",
    "board": "AQA 7402",
    "size_kb": 16
  },
  {
    "filename": "alevel_biology_v3.pdf",
    "title": "A-Level Biology (Extended)",
    "curriculum": "A-Level",
    "subject": "Biology",
    "board": "AQA 7402",
    "size_kb": 26
  },
  {
    "filename": "alevel_chemistry_FINAL.pdf",
    "title": "A-Level Chemistry (Illustrated)",
    "curriculum": "A-Level",
    "subject": "Chemistry",
    "board": "AQA 7405",
    "size_kb": 8
  },
  {
    "filename": "alevel_chemistry_aqa.pdf",
    "title": "A-Level Chemistry",
    "curriculum": "A-Level",
    "subject": "Chemistry",
    "board": "AQA 7405",
    "size_kb": 43
  },
  {
    "filename": "alevel_chemistry_v3.pdf",
    "title": "A-Level Chemistry (Extended)",
    "curriculum": "A-Level",
    "subject": "Chemistry",
    "board": "AQA 7405",
    "size_kb": 24
  },
  {
    "filename": "alevel_physics_v3.pdf",
    "title": "A-Level Physics",
    "curriculum": "A-Level",
    "subject": "Physics",
    "board": "AQA 7408",
    "size_kb": 12
  },
  {
    "filename": "alevel_mathematics.pdf",
    "title": "A-Level Mathematics",
    "curriculum": "A-Level",
    "subject": "Mathematics",
    "board": "AQA/Edexcel",
    "size_kb": 6
  },
  {
    "filename": "alevel_further_maths.pdf",
    "title": "A-Level Further Mathematics",
    "curriculum": "A-Level",
    "subject": "Further Maths",
    "board": "AQA/Edexcel",
    "size_kb": 4
  },
  {
    "filename": "alevel_economics.pdf",
    "title": "A-Level Economics",
    "curriculum": "A-Level",
    "subject": "Economics",
    "board": "AQA 7136",
    "size_kb": 15
  },
  {
    "filename": "alevel_psychology_aqa.pdf",
    "title": "A-Level Psychology",
    "curriculum": "A-Level",
    "subject": "Psychology",
    "board": "AQA 7182",
    "size_kb": 19
  },
  {
    "filename": "alevel_history.pdf",
    "title": "A-Level History",
    "curriculum": "A-Level",
    "subject": "History",
    "board": "AQA 7042",
    "size_kb": 3
  },
  {
    "filename": "ib_biology_v3.pdf",
    "title": "IB Biology (Extended)",
    "curriculum": "IB",
    "subject": "Biology",
    "board": "HL & SL",
    "size_kb": 21
  },
  {
    "filename": "ib_chemistry_v3.pdf",
    "title": "IB Chemistry",
    "curriculum": "IB",
    "subject": "Chemistry",
    "board": "HL & SL",
    "size_kb": 13
  },
  {
    "filename": "ib_physics_hl_sl.pdf",
    "title": "IB Physics",
    "curriculum": "IB",
    "subject": "Physics",
    "board": "HL & SL",
    "size_kb": 10
  },
  {
    "filename": "ib_mathematics_aa.pdf",
    "title": "IB Mathematics AA",
    "curriculum": "IB",
    "subject": "Mathematics AA",
    "board": "HL & SL",
    "size_kb": 11
  },
  {
    "filename": "ib_mathematics_ai.pdf",
    "title": "IB Mathematics AI",
    "curriculum": "IB",
    "subject": "Mathematics AI",
    "board": "HL & SL",
    "size_kb": 4
  },
  {
    "filename": "ib_economics_FINAL.pdf",
    "title": "IB Economics (Illustrated)",
    "curriculum": "IB",
    "subject": "Economics",
    "board": "HL & SL",
    "size_kb": 6
  },
  {
    "filename": "ib_history.pdf",
    "title": "IB History",
    "curriculum": "IB",
    "subject": "History",
    "board": "HL & SL",
    "size_kb": 4
  },
  {
    "filename": "ap_biology.pdf",
    "title": "AP Biology",
    "curriculum": "AP",
    "subject": "Biology",
    "board": "College Board",
    "size_kb": 7
  },
  {
    "filename": "ap_chemistry.pdf",
    "title": "AP Chemistry",
    "curriculum": "AP",
    "subject": "Chemistry",
    "board": "College Board",
    "size_kb": 5
  },
  {
    "filename": "ap_calculus.pdf",
    "title": "AP Calculus AB/BC",
    "curriculum": "AP",
    "subject": "Calculus",
    "board": "College Board",
    "size_kb": 3
  },
  {
    "filename": "ap_us_history.pdf",
    "title": "AP US History",
    "curriculum": "AP",
    "subject": "History",
    "board": "College Board",
    "size_kb": 5
  },
  {
    "filename": "ap_world_history.pdf",
    "title": "AP World History",
    "curriculum": "AP",
    "subject": "History",
    "board": "College Board",
    "size_kb": 10
  },
  {
    "filename": "ap_english_lang.pdf",
    "title": "AP English Language",
    "curriculum": "AP",
    "subject": "English",
    "board": "College Board",
    "size_kb": 12
  },
  {
    "filename": "ap_psychology.pdf",
    "title": "AP Psychology",
    "curriculum": "AP",
    "subject": "Psychology",
    "board": "College Board",
    "size_kb": 6
  },
  {
    "filename": "ap_statistics.pdf",
    "title": "AP Statistics",
    "curriculum": "AP",
    "subject": "Statistics",
    "board": "College Board",
    "size_kb": 4
  },
  {
    "filename": "igcse_biology_cambridge.pdf",
    "title": "IGCSE Biology",
    "curriculum": "IGCSE",
    "subject": "Biology",
    "board": "Cambridge",
    "size_kb": 7
  },
  {
    "filename": "igcse_chemistry_cambridge.pdf",
    "title": "IGCSE Chemistry",
    "curriculum": "IGCSE",
    "subject": "Chemistry",
    "board": "Cambridge",
    "size_kb": 8
  },
  {
    "filename": "igcse_mathematics_cambridge.pdf",
    "title": "IGCSE Mathematics",
    "curriculum": "IGCSE",
    "subject": "Mathematics",
    "board": "Cambridge",
    "size_kb": 5
  },
  {
    "filename": "igcse_physics_FINAL.pdf",
    "title": "IGCSE Physics (Illustrated)",
    "curriculum": "IGCSE",
    "subject": "Physics",
    "board": "Cambridge",
    "size_kb": 10
  },
  {
    "filename": "igcse_computer_science.pdf",
    "title": "IGCSE Computer Science",
    "curriculum": "IGCSE",
    "subject": "Computer Science",
    "board": "Cambridge",
    "size_kb": 6
  }
];

  // ===== PAPERS FUNCTIONS =====
  function renderPapers(curriculum) {
    const container = document.getElementById('papers-content-area');
    const data = PAPERS[curriculum];
    if (!data) { container.innerHTML = '<p style="color:rgba(247,245,240,0.4);font-size:13px;padding:20px;">No papers found for this curriculum.</p>'; return; }
    let html = '';
    data.forEach(subj => {
      html += '<div class="papers-subject-block"><div class="papers-subj-name">' + subj.subj + '</div>';
      html += '<table class="papers-tbl"><thead><tr><th>Year</th><th>Paper</th><th>Past Paper</th><th>Mark Scheme</th></tr></thead><tbody>';
      subj.rows.forEach(row => {
        html += '<tr><td>' + row[0] + '</td><td>' + row[1] + '</td>';
        html += '<td><a class="p-link" href="' + row[2] + '" target="_blank">↓ Download</a></td>';
        html += '<td><a class="ms-link" href="' + row[3] + '" target="_blank">✓ Mark Scheme</a></td></tr>';
      });
      html += '</tbody></table></div>';
    });
    container.innerHTML = html;
  }

  function switchPapers(c, btn) {
    document.querySelectorAll('.papers-tab-btn').forEach(b => b.classList.remove('on'));
    btn.classList.add('on');
    renderPapers(c);
  }



  // ===== PDF DOWNLOAD CATALOG =====
  function renderPdfGrid(curriculum) {
    const grid = document.getElementById('pdf-grid');
    if (!grid) return;
    const items = curriculum === 'all' ? PDF_CATALOG : PDF_CATALOG.filter(p => p.curriculum === curriculum);
    grid.innerHTML = items.map(p => `
      <a href="${p.filename}" download target="_blank" class="pdf-card-link" data-curr="${p.curriculum}" title="Download ${p.title}">
        <div style="background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:6px;padding:10px;cursor:pointer;transition:all 0.2s;text-decoration:none;" onmouseover="this.style.borderColor='rgba(200,146,42,0.4)';this.style.background='rgba(200,146,42,0.08)'" onmouseout="this.style.borderColor='rgba(247,245,240,0.1)';this.style.background='rgba(247,245,240,0.05)'">
          <div style="font-family:'JetBrains Mono',monospace;font-size:8px;letter-spacing:0.08em;text-transform:uppercase;color:var(--gold);margin-bottom:3px;">${p.curriculum} · ${p.board}</div>
          <div style="font-family:'Syne',sans-serif;font-size:11px;font-weight:700;color:var(--paper);margin-bottom:2px;line-height:1.3;">${p.title}</div>
          <div style="font-size:10px;color:rgba(247,245,240,0.4);">📄 PDF · ${p.size_kb}KB</div>
        </div>
      </a>
    `).join('');
  }

  function filterPdfs(curriculum, btn) {
    document.querySelectorAll('#pdf-filters .notes-filt-btn').forEach(b => b.classList.remove('on'));
    if (btn) btn.classList.add('on');
    renderPdfGrid(curriculum);
  }

  // Init PDF grid on page load
  document.addEventListener('DOMContentLoaded', function() {
    renderPdfGrid('all');
    // Set daily motivation
    const q = document.getElementById('fdash-quote');
    if (q) { const d = new Date().getDate() - 1; q.textContent = '"' + (typeof MOTIV !== 'undefined' ? MOTIV[d % MOTIV.length] : 'Every question you answer today is a mark secured for exam day.') + '"'; }
    // Init papers
    if (typeof renderPapers === 'function') renderPapers('gcse');
  });


  // ===== SUBJECT LIBRARY =====
  const SUBJECT_FLAT = [
  {
    "curriculum": "GCSE",
    "category": "Mathematics",
    "subject": "Mathematics",
    "id": "gcse_mathematics",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Mathematics",
    "subject": "Statistics",
    "id": "gcse_statistics",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Mathematics",
    "subject": "Additional Mathematics",
    "id": "gcse_additional_mathematics",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Sciences",
    "subject": "Biology",
    "id": "gcse_biology",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Sciences",
    "subject": "Chemistry",
    "id": "gcse_chemistry",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Sciences",
    "subject": "Physics",
    "id": "gcse_physics",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Sciences",
    "subject": "Combined Science (Trilogy)",
    "id": "gcse_combined_science__trilogy",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Sciences",
    "subject": "Combined Science (Synergy)",
    "id": "gcse_combined_science__synergy",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Sciences",
    "subject": "Environmental Science",
    "id": "gcse_environmental_science",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Sciences",
    "subject": "Astronomy",
    "id": "gcse_astronomy",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "English Language",
    "id": "gcse_english_language",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "English Literature",
    "id": "gcse_english_literature",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "French",
    "id": "gcse_french",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "Spanish",
    "id": "gcse_spanish",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "German",
    "id": "gcse_german",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "Mandarin Chinese",
    "id": "gcse_mandarin_chinese",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "Arabic",
    "id": "gcse_arabic",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "Latin",
    "id": "gcse_latin",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "Italian",
    "id": "gcse_italian",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "Russian",
    "id": "gcse_russian",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "English & Languages",
    "subject": "Japanese",
    "id": "gcse_japanese",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "History",
    "id": "gcse_history",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Geography",
    "id": "gcse_geography",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Economics",
    "id": "gcse_economics",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Business Studies",
    "id": "gcse_business_studies",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Psychology",
    "id": "gcse_psychology",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Sociology",
    "id": "gcse_sociology",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Religious Studies",
    "id": "gcse_religious_studies",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Global Perspectives",
    "id": "gcse_global_perspectives",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Classical Civilisation",
    "id": "gcse_classical_civilisation",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Ancient History",
    "id": "gcse_ancient_history",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Creative & Performing Arts",
    "subject": "Art & Design",
    "id": "gcse_art___design",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Creative & Performing Arts",
    "subject": "Fine Art",
    "id": "gcse_fine_art",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Creative & Performing Arts",
    "subject": "Graphic Design",
    "id": "gcse_graphic_design",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Creative & Performing Arts",
    "subject": "Photography",
    "id": "gcse_photography",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Creative & Performing Arts",
    "subject": "Music",
    "id": "gcse_music",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Creative & Performing Arts",
    "subject": "Drama",
    "id": "gcse_drama",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Creative & Performing Arts",
    "subject": "Dance",
    "id": "gcse_dance",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Creative & Performing Arts",
    "subject": "Film Studies",
    "id": "gcse_film_studies",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Creative & Performing Arts",
    "subject": "Media Studies",
    "id": "gcse_media_studies",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Technology & Computing",
    "subject": "Computer Science",
    "id": "gcse_computer_science",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Technology & Computing",
    "subject": "ICT",
    "id": "gcse_ict",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Technology & Computing",
    "subject": "Design & Technology",
    "id": "gcse_design___technology",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Technology & Computing",
    "subject": "Electronics",
    "id": "gcse_electronics",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Technology & Computing",
    "subject": "Engineering",
    "id": "gcse_engineering",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Applied & Vocational",
    "subject": "Physical Education",
    "id": "gcse_physical_education",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Applied & Vocational",
    "subject": "Food Preparation & Nutrition",
    "id": "gcse_food_preparation___nutrition",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Applied & Vocational",
    "subject": "Textiles",
    "id": "gcse_textiles",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Applied & Vocational",
    "subject": "Product Design",
    "id": "gcse_product_design",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Applied & Vocational",
    "subject": "Travel & Tourism",
    "id": "gcse_travel___tourism",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Applied & Vocational",
    "subject": "Enterprise",
    "id": "gcse_enterprise",
    "color": "#1a6644"
  },
  {
    "curriculum": "GCSE",
    "category": "Applied & Vocational",
    "subject": "Hospitality",
    "id": "gcse_hospitality",
    "color": "#1a6644"
  },
  {
    "curriculum": "IGCSE",
    "category": "Mathematics",
    "subject": "Mathematics (0580)",
    "id": "igcse_mathematics__0580",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Mathematics",
    "subject": "Additional Mathematics (0606)",
    "id": "igcse_additional_mathematics__0606",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Mathematics",
    "subject": "Statistics (0653)",
    "id": "igcse_statistics__0653",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Mathematics",
    "subject": "International Mathematics (0607)",
    "id": "igcse_international_mathematics__0607",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Sciences",
    "subject": "Biology (0610)",
    "id": "igcse_biology__0610",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Sciences",
    "subject": "Chemistry (0620)",
    "id": "igcse_chemistry__0620",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Sciences",
    "subject": "Physics (0625)",
    "id": "igcse_physics__0625",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Sciences",
    "subject": "Combined Science (0653)",
    "id": "igcse_combined_science__0653",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Sciences",
    "subject": "Environmental Management (0680)",
    "id": "igcse_environmental_management__0680",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Sciences",
    "subject": "Marine Science (0697)",
    "id": "igcse_marine_science__0697",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Sciences",
    "subject": "Astronomy",
    "id": "igcse_astronomy",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "First Language English (0500)",
    "id": "igcse_first_language_english__0500",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Second Language English (0510)",
    "id": "igcse_second_language_english__0510",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "English Literature (0475)",
    "id": "igcse_english_literature__0475",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "French (0520)",
    "id": "igcse_french__0520",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Spanish (0530)",
    "id": "igcse_spanish__0530",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "German (0525)",
    "id": "igcse_german__0525",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Mandarin Chinese (0547)",
    "id": "igcse_mandarin_chinese__0547",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Arabic (0508)",
    "id": "igcse_arabic__0508",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Latin (0480)",
    "id": "igcse_latin__0480",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Italian (0535)",
    "id": "igcse_italian__0535",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Portuguese (0547)",
    "id": "igcse_portuguese__0547",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Japanese (0519)",
    "id": "igcse_japanese__0519",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Russian (0516)",
    "id": "igcse_russian__0516",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "English & Languages",
    "subject": "Hindi (0549)",
    "id": "igcse_hindi__0549",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "History (0470)",
    "id": "igcse_history__0470",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Geography (0460)",
    "id": "igcse_geography__0460",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Economics (0455)",
    "id": "igcse_economics__0455",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Business Studies (0450)",
    "id": "igcse_business_studies__0450",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Accounting (0452)",
    "id": "igcse_accounting__0452",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Psychology (0478)",
    "id": "igcse_psychology__0478",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Sociology (0495)",
    "id": "igcse_sociology__0495",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Global Perspectives (0457)",
    "id": "igcse_global_perspectives__0457",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Travel & Tourism (0471)",
    "id": "igcse_travel___tourism__0471",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Humanities & Social Sciences",
    "subject": "Classical Studies",
    "id": "igcse_classical_studies",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Creative & Performing Arts",
    "subject": "Art & Design (0400)",
    "id": "igcse_art___design__0400",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Creative & Performing Arts",
    "subject": "Music (0410)",
    "id": "igcse_music__0410",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Creative & Performing Arts",
    "subject": "Drama (0411)",
    "id": "igcse_drama__0411",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Creative & Performing Arts",
    "subject": "Design & Technology (0445)",
    "id": "igcse_design___technology__0445",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Creative & Performing Arts",
    "subject": "Graphic Design",
    "id": "igcse_graphic_design",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Technology & Computing",
    "subject": "Computer Science (0478/0984)",
    "id": "igcse_computer_science__0478_0984",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Technology & Computing",
    "subject": "ICT (0417)",
    "id": "igcse_ict__0417",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Technology & Computing",
    "subject": "Design & Technology (0445)",
    "id": "igcse_design___technology__0445",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Technology & Computing",
    "subject": "Engineering (0469)",
    "id": "igcse_engineering__0469",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Applied & Vocational",
    "subject": "Physical Education (0413)",
    "id": "igcse_physical_education__0413",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Applied & Vocational",
    "subject": "Food & Nutrition (0648)",
    "id": "igcse_food___nutrition__0648",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Applied & Vocational",
    "subject": "Enterprise (0454)",
    "id": "igcse_enterprise__0454",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "IGCSE",
    "category": "Applied & Vocational",
    "subject": "Environmental Management",
    "id": "igcse_environmental_management",
    "color": "#1a3a6b"
  },
  {
    "curriculum": "A-Level",
    "category": "Mathematics",
    "subject": "Mathematics",
    "id": "a_level_mathematics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Mathematics",
    "subject": "Further Mathematics",
    "id": "a_level_further_mathematics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Mathematics",
    "subject": "Pure Mathematics",
    "id": "a_level_pure_mathematics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Mathematics",
    "subject": "Mechanics",
    "id": "a_level_mechanics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Mathematics",
    "subject": "Statistics",
    "id": "a_level_statistics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Mathematics",
    "subject": "Decision Mathematics",
    "id": "a_level_decision_mathematics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Sciences",
    "subject": "Biology",
    "id": "a_level_biology",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Sciences",
    "subject": "Chemistry",
    "id": "a_level_chemistry",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Sciences",
    "subject": "Physics",
    "id": "a_level_physics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Sciences",
    "subject": "Environmental Science",
    "id": "a_level_environmental_science",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Sciences",
    "subject": "Geology",
    "id": "a_level_geology",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Sciences",
    "subject": "Electronics",
    "id": "a_level_electronics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "English Language",
    "id": "a_level_english_language",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "English Literature",
    "id": "a_level_english_literature",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "English Language & Literature",
    "id": "a_level_english_language___literature",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "French",
    "id": "a_level_french",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "Spanish",
    "id": "a_level_spanish",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "German",
    "id": "a_level_german",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "Mandarin Chinese",
    "id": "a_level_mandarin_chinese",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "Arabic",
    "id": "a_level_arabic",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "Latin",
    "id": "a_level_latin",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "Italian",
    "id": "a_level_italian",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "Russian",
    "id": "a_level_russian",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "English & Languages",
    "subject": "Japanese",
    "id": "a_level_japanese",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "History",
    "id": "a_level_history",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Geography",
    "id": "a_level_geography",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Economics",
    "id": "a_level_economics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Business",
    "id": "a_level_business",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Accounting",
    "id": "a_level_accounting",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Psychology",
    "id": "a_level_psychology",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Sociology",
    "id": "a_level_sociology",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Politics",
    "id": "a_level_politics",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Philosophy",
    "id": "a_level_philosophy",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Religious Studies",
    "id": "a_level_religious_studies",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Law",
    "id": "a_level_law",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Classical Civilisation",
    "id": "a_level_classical_civilisation",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Humanities & Social Sciences",
    "subject": "Ancient History",
    "id": "a_level_ancient_history",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Art & Design",
    "id": "a_level_art___design",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Fine Art",
    "id": "a_level_fine_art",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Photography",
    "id": "a_level_photography",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Graphic Design",
    "id": "a_level_graphic_design",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Textiles",
    "id": "a_level_textiles",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Music",
    "id": "a_level_music",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Music Technology",
    "id": "a_level_music_technology",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Drama & Theatre Studies",
    "id": "a_level_drama___theatre_studies",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Dance",
    "id": "a_level_dance",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Film Studies",
    "id": "a_level_film_studies",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Creative & Performing Arts",
    "subject": "Media Studies",
    "id": "a_level_media_studies",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Technology & Computing",
    "subject": "Computer Science",
    "id": "a_level_computer_science",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Technology & Computing",
    "subject": "ICT",
    "id": "a_level_ict",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Technology & Computing",
    "subject": "Design & Technology",
    "id": "a_level_design___technology",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Technology & Computing",
    "subject": "Product Design",
    "id": "a_level_product_design",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Technology & Computing",
    "subject": "Engineering",
    "id": "a_level_engineering",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Applied & Vocational",
    "subject": "Physical Education",
    "id": "a_level_physical_education",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Applied & Vocational",
    "subject": "Sports Science",
    "id": "a_level_sports_science",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Applied & Vocational",
    "subject": "Food Technology",
    "id": "a_level_food_technology",
    "color": "#c8922a"
  },
  {
    "curriculum": "A-Level",
    "category": "Applied & Vocational",
    "subject": "Travel & Tourism",
    "id": "a_level_travel___tourism",
    "color": "#c8922a"
  },
  {
    "curriculum": "IB",
    "category": "Group 1 \u2014 Studies in Language & Literature",
    "subject": "Language A: Literature (English)",
    "id": "ib_language_a__literature__english",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 1 \u2014 Studies in Language & Literature",
    "subject": "Language A: Literature (French)",
    "id": "ib_language_a__literature__french",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 1 \u2014 Studies in Language & Literature",
    "subject": "Language A: Literature (Spanish)",
    "id": "ib_language_a__literature__spanish",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 1 \u2014 Studies in Language & Literature",
    "subject": "Language A: Literature (German)",
    "id": "ib_language_a__literature__german",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 1 \u2014 Studies in Language & Literature",
    "subject": "Language A: Literature (Mandarin Chinese)",
    "id": "ib_language_a__literature__mandarin_chinese",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 1 \u2014 Studies in Language & Literature",
    "subject": "Language A: Language & Literature (English)",
    "id": "ib_language_a__language___literature__english",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 1 \u2014 Studies in Language & Literature",
    "subject": "Language A: Language & Literature (Spanish)",
    "id": "ib_language_a__language___literature__spanish",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 1 \u2014 Studies in Language & Literature",
    "subject": "Literature & Performance",
    "id": "ib_literature___performance",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "French B",
    "id": "ib_french_b",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "Spanish B",
    "id": "ib_spanish_b",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "German B",
    "id": "ib_german_b",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "Mandarin B",
    "id": "ib_mandarin_b",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "Arabic B",
    "id": "ib_arabic_b",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "Japanese B",
    "id": "ib_japanese_b",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "French Ab Initio",
    "id": "ib_french_ab_initio",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "Spanish Ab Initio",
    "id": "ib_spanish_ab_initio",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "German Ab Initio",
    "id": "ib_german_ab_initio",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "Mandarin Ab Initio",
    "id": "ib_mandarin_ab_initio",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "Japanese Ab Initio",
    "id": "ib_japanese_ab_initio",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "Latin",
    "id": "ib_latin",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 2 \u2014 Language Acquisition",
    "subject": "Classical Greek",
    "id": "ib_classical_greek",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "History",
    "id": "ib_history",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "Geography",
    "id": "ib_geography",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "Economics",
    "id": "ib_economics",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "Business Management",
    "id": "ib_business_management",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "Psychology",
    "id": "ib_psychology",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "Philosophy",
    "id": "ib_philosophy",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "Social & Cultural Anthropology",
    "id": "ib_social___cultural_anthropology",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "Environmental Systems & Societies (ESS)",
    "id": "ib_environmental_systems___societies__ess",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "Global Politics",
    "id": "ib_global_politics",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "World Religions",
    "id": "ib_world_religions",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 3 \u2014 Individuals & Societies",
    "subject": "Information Technology in a Global Society (ITGS)",
    "id": "ib_information_technology_in_a_global_society__itgs",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 4 \u2014 Sciences",
    "subject": "Biology",
    "id": "ib_biology",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 4 \u2014 Sciences",
    "subject": "Chemistry",
    "id": "ib_chemistry",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 4 \u2014 Sciences",
    "subject": "Physics",
    "id": "ib_physics",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 4 \u2014 Sciences",
    "subject": "Computer Science",
    "id": "ib_computer_science",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 4 \u2014 Sciences",
    "subject": "Design Technology",
    "id": "ib_design_technology",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 4 \u2014 Sciences",
    "subject": "Environmental Systems & Societies (ESS)",
    "id": "ib_environmental_systems___societies__ess",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 4 \u2014 Sciences",
    "subject": "Sports, Exercise & Health Science",
    "id": "ib_sports__exercise___health_science",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 5 \u2014 Mathematics",
    "subject": "Mathematics: Analysis & Approaches (AA) HL",
    "id": "ib_mathematics__analysis___approaches__aa__hl",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 5 \u2014 Mathematics",
    "subject": "Mathematics: Analysis & Approaches (AA) SL",
    "id": "ib_mathematics__analysis___approaches__aa__sl",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 5 \u2014 Mathematics",
    "subject": "Mathematics: Applications & Interpretation (AI) HL",
    "id": "ib_mathematics__applications___interpretation__ai__hl",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 5 \u2014 Mathematics",
    "subject": "Mathematics: Applications & Interpretation (AI) SL",
    "id": "ib_mathematics__applications___interpretation__ai__sl",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 6 \u2014 The Arts",
    "subject": "Visual Arts",
    "id": "ib_visual_arts",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 6 \u2014 The Arts",
    "subject": "Music",
    "id": "ib_music",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 6 \u2014 The Arts",
    "subject": "Theatre",
    "id": "ib_theatre",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 6 \u2014 The Arts",
    "subject": "Dance",
    "id": "ib_dance",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "Group 6 \u2014 The Arts",
    "subject": "Film",
    "id": "ib_film",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "IB Core",
    "subject": "Theory of Knowledge (TOK)",
    "id": "ib_theory_of_knowledge__tok",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "IB Core",
    "subject": "Extended Essay (EE)",
    "id": "ib_extended_essay__ee",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "IB",
    "category": "IB Core",
    "subject": "Creativity, Activity, Service (CAS)",
    "id": "ib_creativity__activity__service__cas",
    "color": "#8b1a1a"
  },
  {
    "curriculum": "AP",
    "category": "Mathematics & Computing",
    "subject": "Calculus AB",
    "id": "ap_calculus_ab",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Mathematics & Computing",
    "subject": "Calculus BC",
    "id": "ap_calculus_bc",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Mathematics & Computing",
    "subject": "Statistics",
    "id": "ap_statistics",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Mathematics & Computing",
    "subject": "Precalculus",
    "id": "ap_precalculus",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Mathematics & Computing",
    "subject": "Computer Science A",
    "id": "ap_computer_science_a",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Mathematics & Computing",
    "subject": "Computer Science Principles",
    "id": "ap_computer_science_principles",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Sciences",
    "subject": "Biology",
    "id": "ap_biology",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Sciences",
    "subject": "Chemistry",
    "id": "ap_chemistry",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Sciences",
    "subject": "Physics 1: Algebra-Based",
    "id": "ap_physics_1__algebra_based",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Sciences",
    "subject": "Physics 2: Algebra-Based",
    "id": "ap_physics_2__algebra_based",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Sciences",
    "subject": "Physics C: Mechanics",
    "id": "ap_physics_c__mechanics",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Sciences",
    "subject": "Physics C: Electricity & Magnetism",
    "id": "ap_physics_c__electricity___magnetism",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Sciences",
    "subject": "Environmental Science",
    "id": "ap_environmental_science",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Humanities & Social Sciences",
    "subject": "World History: Modern",
    "id": "ap_world_history__modern",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Humanities & Social Sciences",
    "subject": "European History",
    "id": "ap_european_history",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Humanities & Social Sciences",
    "subject": "United States History",
    "id": "ap_united_states_history",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Humanities & Social Sciences",
    "subject": "United States Government & Politics",
    "id": "ap_united_states_government___politics",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Humanities & Social Sciences",
    "subject": "Comparative Government & Politics",
    "id": "ap_comparative_government___politics",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Humanities & Social Sciences",
    "subject": "Human Geography",
    "id": "ap_human_geography",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Humanities & Social Sciences",
    "subject": "Psychology",
    "id": "ap_psychology",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Humanities & Social Sciences",
    "subject": "Macroeconomics",
    "id": "ap_macroeconomics",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Humanities & Social Sciences",
    "subject": "Microeconomics",
    "id": "ap_microeconomics",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "English Language & Composition",
    "id": "ap_english_language___composition",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "English Literature & Composition",
    "id": "ap_english_literature___composition",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "Spanish Language & Culture",
    "id": "ap_spanish_language___culture",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "Spanish Literature & Culture",
    "id": "ap_spanish_literature___culture",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "French Language & Culture",
    "id": "ap_french_language___culture",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "German Language & Culture",
    "id": "ap_german_language___culture",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "Mandarin Chinese Language & Culture",
    "id": "ap_mandarin_chinese_language___culture",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "Japanese Language & Culture",
    "id": "ap_japanese_language___culture",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "Italian Language & Culture",
    "id": "ap_italian_language___culture",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "English & Languages",
    "subject": "Latin",
    "id": "ap_latin",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Arts",
    "subject": "Art History",
    "id": "ap_art_history",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Arts",
    "subject": "Music Theory",
    "id": "ap_music_theory",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Arts",
    "subject": "Studio Art: 2D Design",
    "id": "ap_studio_art__2d_design",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Arts",
    "subject": "Studio Art: 3D Design",
    "id": "ap_studio_art__3d_design",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Arts",
    "subject": "Studio Art: Drawing",
    "id": "ap_studio_art__drawing",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Arts",
    "subject": "Seminar",
    "id": "ap_seminar",
    "color": "#4a1a6b"
  },
  {
    "curriculum": "AP",
    "category": "Arts",
    "subject": "Research",
    "id": "ap_research",
    "color": "#4a1a6b"
  }
];
  const SUBJECTS_WITH_NOTES = ["gcse_biology", "gcse_chemistry", "gcse_physics", "gcse_mathematics", "gcse_english_language", "gcse_history", "gcse_geography", "alevel_biology", "alevel_chemistry", "alevel_physics", "alevel_mathematics", "alevel_further_mathematics", "alevel_economics", "alevel_psychology", "alevel_history", "ib_biology", "ib_chemistry", "ib_physics", "ib_mathematics__analysis___approaches__aa__hl", "ib_mathematics__applications___interpretation__ai__hl", "ib_economics", "ib_history", "ap_biology", "ap_chemistry", "ap_calculus_ab", "ap_calculus_bc", "ap_statistics", "ap_us_history", "ap_world_history__modern", "ap_english_language___composition", "ap_psychology", "igcse_biology__0610_", "igcse_chemistry__0620_", "igcse_mathematics__0580_", "igcse_physics__0625_", "igcse_computer_science__0478_0984_"];

  let currentModal = null;

  function sublibInit() {
    // Mark cards with notes
    document.querySelectorAll('.sublib-card').forEach(card => {
      const id = card.dataset.subjectId;
      if (SUBJECTS_WITH_NOTES.includes(id)) {
        card.classList.add('has-notes');
      }
    });
    // Search
    const searchEl = document.getElementById('sublib-search');
    if (searchEl) searchEl.addEventListener('input', sublibSearch);
  }

  function sublibSwitchCurr(curriculum, btn) {
    document.querySelectorAll('.sublib-curr-tab').forEach(b => b.classList.remove('active'));
    document.querySelectorAll('.sublib-curriculum').forEach(c => c.classList.remove('active'));
    if (btn) btn.classList.add('active');
    const currEl = document.getElementById('sublib-curr-' + curriculum);
    if (currEl) currEl.classList.add('active');
    // Clear search
    const s = document.getElementById('sublib-search');
    if (s) { s.value = ''; sublibSearch({target: s}); }
  }

  function sublibSearch(e) {
    const q = e.target.value.toLowerCase().trim();
    const activeEl = document.querySelector('.sublib-curriculum.active');
    if (!activeEl) return;
    let anyVisible = false;
    activeEl.querySelectorAll('.sublib-card').forEach(card => {
      const text = (card.dataset.subject || '').toLowerCase();
      const show = !q || text.includes(q);
      card.style.display = show ? '' : 'none';
      if (show) anyVisible = true;
    });
    const empty = activeEl.querySelector('.sublib-empty');
    if (empty) empty.classList.toggle('visible', !anyVisible && !!q);
  }

  function openSubjectModal(curriculum, subject, category, color) {
    const modal = document.getElementById('sublib-modal');
    const overlay = document.getElementById('sublib-modal-overlay');
    if (!modal || !overlay) return;
    document.getElementById('sm-curriculum').textContent = curriculum;
    document.getElementById('sm-curriculum').style.color = color;
    document.getElementById('sm-title').textContent = subject;
    document.getElementById('sm-sub').textContent = category + ' — ' + curriculum;
    document.getElementById('sm-color').style.setProperty('--sm-color', color);
    // Check if notes exist
    const id = subject.toLowerCase().replace(/[^a-z0-9]+/g, '_').replace(/^_|_$/g, '');
    const hasNotes = SUBJECTS_WITH_NOTES.some(n => n.includes(id.substring(0, 10)));
    const noteStatus = document.getElementById('sm-note-status');
    if (noteStatus) {
      noteStatus.innerHTML = hasNotes
        ? '<div style="background:rgba(26,102,68,0.15);border:1px solid rgba(26,102,68,0.3);border-radius:8px;padding:12px 14px;display:flex;align-items:center;gap:10px;"><span style=\"font-size:16px;\">✅</span><div style=\"font-family:Syne,sans-serif;font-size:12px;color:#5bce8a;\">Revision notes available — click Read Notes to access.</div></div>'
        : '<div class=\"sublib-coming-soon\"><span class=\"sublib-coming-soon-icon\">📋</span><div class=\"sublib-coming-soon-text\">Notes for this subject are being prepared. They will appear here shortly.</div></div>';
    }
    overlay.classList.add('open');
    currentModal = { curriculum, subject, id };
  }

  function closeSubjectModal() {
    const overlay = document.getElementById('sublib-modal-overlay');
    if (overlay) overlay.classList.remove('open');
    currentModal = null;
  }

  function openSubjectNotes(type) {
    if (!currentModal) return;
    // Switch to appropriate dashboard panel
    const panel = type === 'notes' ? 'notes' : type === 'papers' ? 'papers' : 'practice';
    const navItem = document.querySelector(`.fdash-nav[data-panel="${panel}"]`);
    if (navItem) navItem.click();
    closeSubjectModal();
    // Pre-filter to this subject if possible
    if (type === 'notes' && typeof openSubject === 'function') {
      // Try to find matching subject card
      const cards = document.querySelectorAll('.subj-card');
      for (const card of cards) {
        const title = card.querySelector('.subj-title');
        if (title && title.textContent.toLowerCase().includes(currentModal.subject.toLowerCase().substring(0, 8))) {
          card.click();
          break;
        }
      }
    }
  }

  // Close modal on overlay click
  document.addEventListener('DOMContentLoaded', function() {
    const overlay = document.getElementById('sublib-modal-overlay');
    if (overlay) overlay.addEventListener('click', function(e) {
      if (e.target === overlay) closeSubjectModal();
    });
    sublibInit();
  });


  // ===== SUBJECT LIBRARY =====
  function sublibOpen(){
    document.getElementById('sublib-overlay').classList.add('open');
    document.body.style.overflow='hidden';
    setTimeout(()=>{const s=document.getElementById('sublib-search');if(s)s.focus();},200);
  }
  function sublibClose(){
    document.getElementById('sublib-overlay').classList.remove('open');
    document.body.style.overflow='';
  }
  document.addEventListener('keydown',e=>{if(e.key==='Escape'&&document.getElementById('sublib-overlay').classList.contains('open'))sublibClose();});

  function sublibTab(curr,btn){
    document.querySelectorAll('.sublib-tab').forEach(b=>b.classList.remove('on'));
    document.querySelectorAll('.sublib-section').forEach(s=>s.classList.remove('on'));
    if(btn)btn.classList.add('on');
    const sec=document.getElementById('sublib-sec-'+curr);
    if(sec)sec.classList.add('on');
    document.getElementById('sublib-search').value='';
    sublibSearch('');
  }

  function sublibSearch(q){
    q=q.toLowerCase().trim();
    const noRes=document.getElementById('sublib-no-res');
    if(!q){
      document.querySelectorAll('.sublib-card').forEach(c=>{c.style.display='';});
      document.querySelectorAll('.sublib-cat').forEach(c=>{c.style.display='';});
      document.querySelectorAll('.sublib-section').forEach(s=>s.style.display='');
      // restore active section display
      const onSec=document.querySelector('.sublib-section.on');
      document.querySelectorAll('.sublib-section').forEach(s=>{s.style.display=s.classList.contains('on')?'':'none';});
      if(noRes)noRes.style.display='none';
      return;
    }
    // Show all sections in search mode
    document.querySelectorAll('.sublib-tab').forEach(b=>b.classList.remove('on'));
    document.querySelectorAll('.sublib-section').forEach(s=>{s.classList.add('on');s.style.display='block';});
    let any=false;
    document.querySelectorAll('.sublib-cat').forEach(cat=>{
      let catVis=false;
      cat.querySelectorAll('.sublib-card').forEach(card=>{
        const m=(card.dataset.s||'').includes(q);
        card.style.display=m?'':'none';
        if(m){catVis=true;any=true;}
      });
      cat.style.display=catVis?'':'none';
    });
    if(noRes)noRes.style.display=any?'none':'block';
  }

  function sublibNotes(curr,subjId,subjName){
    sublibClose();
    // navigate to notes tab in dashboard
    const navItems=document.querySelectorAll('.fdash-nav');
    navItems.forEach(n=>{
      if(n.dataset&&n.dataset.panel==='notes'){n.click();}
    });
    const dash=document.getElementById('dashboard');
    if(dash)setTimeout(()=>dash.scrollIntoView({behavior:'smooth'}),100);
  }

  function sublibPapers(curr,subjId,subjName){
    sublibClose();
    const navItems=document.querySelectorAll('.fdash-nav');
    navItems.forEach(n=>{
      if(n.dataset&&n.dataset.panel==='papers'){n.click();}
    });
    const dash=document.getElementById('dashboard');
    if(dash)setTimeout(()=>dash.scrollIntoView({behavior:'smooth'}),100);
    // Switch to correct curriculum tab in papers
    const currMap={'GCSE':'gcse','IGCSE':'igcse','A-Level':'alevel','IB':'ib','AP':'ap'};
    setTimeout(()=>{
      const tabBtn=document.querySelector(`.papers-tab-btn[onclick*="${currMap[curr]||'gcse'}"]`);
      if(tabBtn&&typeof switchPapers==='function')switchPapers(currMap[curr]||'gcse',tabBtn);
    },500);
  }


  // ===== STARRED SUBJECTS SYSTEM =====
  const CURR_PILL_COLORS = {
    gcse: '#1a6644', igcse: '#1a3a6b', alevel: '#8a610f', ib: '#5a0f8a', ap: '#8b1a1a'
  };

  function getStarred() {
    try { return JSON.parse(localStorage.getItem('ef_starred') || '[]'); } catch(e) { return []; }
  }
  function saveStarred(arr) {
    try { localStorage.setItem('ef_starred', JSON.stringify(arr)); } catch(e) {}
  }

  function toggleStar(sid, name, currLabel, currKey) {
    let starred = getStarred();
    const idx = starred.findIndex(s => s.id === sid);
    const btn = document.getElementById('star-' + sid);
    const card = document.getElementById('sc-' + sid);
    if (idx === -1) {
      starred.push({ id: sid, name, currLabel, currKey });
      if (btn) { btn.textContent = '★'; btn.classList.add('starred'); }
      if (card) card.classList.add('is-starred');
      showToast('⭐ Added to My Subjects: ' + name);
    } else {
      starred.splice(idx, 1);
      if (btn) { btn.textContent = '☆'; btn.classList.remove('starred'); }
      if (card) card.classList.remove('is-starred');
      showToast('Removed from My Subjects: ' + name);
    }
    saveStarred(starred);
    renderMySubjects();
  }

  function renderMySubjects() {
    const starred = getStarred();
    const grid = document.getElementById('my-subjects-grid');
    const empty = document.getElementById('my-subjects-empty');
    if (!grid) return;
    if (starred.length === 0) {
      grid.innerHTML = '<span class="my-subjects-empty" id="my-subjects-empty">No subjects starred yet. Go to Revision Notes and star the subjects you are studying.</span>';
      return;
    }
    grid.innerHTML = starred.map(s => {
      const col = CURR_PILL_COLORS[s.currKey] || '#5a5f5c';
      return `<div class="my-subj-pill" onclick="goToSubject('${s.id}')" title="Go to ${s.name}">
        <span class="pill-dot" style="background:${col}"></span>
        <span class="pill-curr">${s.currLabel}</span>
        <span>${s.name}</span>
      </div>`;
    }).join('');
  }

  function restoreStarredUI() {
    const starred = getStarred();
    starred.forEach(s => {
      const btn = document.getElementById('star-' + s.id);
      const card = document.getElementById('sc-' + s.id);
      if (btn) { btn.textContent = '★'; btn.classList.add('starred'); }
      if (card) card.classList.add('is-starred');
    });
  }

  function goToSubject(sid) {
    // Switch to notes tab and open subject
    const navItems = document.querySelectorAll('.fdash-nav');
    navItems.forEach(n => {
      if (n.dataset && n.dataset.panel === 'notes') n.click();
    });
    const dash = document.getElementById('dashboard');
    if (dash) dash.scrollIntoView({ behavior: 'smooth' });
    setTimeout(() => { if (typeof openSubject === 'function') openSubject(sid); }, 350);
  }

  function goToNotes() {
    const navItems = document.querySelectorAll('.fdash-nav');
    navItems.forEach(n => { if (n.dataset && n.dataset.panel === 'notes') n.click(); });
    const dash = document.getElementById('dashboard');
    if (dash) dash.scrollIntoView({ behavior: 'smooth' });
  }

  function openSubjectEmpty(sid, name, currLabel) {
    // Show a placeholder for subjects without notes yet
    const listEl = document.getElementById('notes-list');
    const detailEl = document.getElementById('notes-detail');
    const bodyEl = document.getElementById('notes-detail-body');
    if (!listEl || !detailEl || !bodyEl) return;
    listEl.style.display = 'none';
    detailEl.classList.add('on');
    bodyEl.innerHTML = `
      <div class="notes-dtitle">${name}</div>
      <div class="notes-dsub">${currLabel} &middot; Full notes coming soon</div>
      <div style="background:rgba(200,146,42,0.07);border:1px solid rgba(200,146,42,0.2);border-radius:8px;padding:28px;text-align:center;margin-top:20px;">
        <div style="font-size:36px;margin-bottom:12px;">📖</div>
        <div style="font-family:'Syne',sans-serif;font-size:16px;font-weight:700;color:var(--paper);margin-bottom:8px;">Notes for ${name} are being prepared</div>
        <p style="font-size:13px;color:rgba(247,245,240,0.5);max-width:400px;margin:0 auto 20px;">Our team is writing comprehensive, syllabus-aligned revision notes for this subject. They will appear here as soon as they are ready.</p>
        <div style="display:flex;gap:10px;justify-content:center;flex-wrap:wrap;">
          <a href="#" onclick="event.preventDefault();switchPapers_fromNote('${currLabel}')" style="font-family:'Syne',sans-serif;font-size:13px;font-weight:600;background:rgba(91,168,232,0.15);color:#5ba8e8;border:1px solid rgba(91,168,232,0.25);padding:8px 18px;border-radius:4px;text-decoration:none;">📄 View Past Papers Instead</a>
          <a href="https://www.youtube.com/results?search_query=${encodeURIComponent(currLabel + ' ' + name + ' revision')}" target="_blank" style="font-family:'Syne',sans-serif;font-size:13px;font-weight:600;background:rgba(255,0,0,0.1);color:#ff7070;border:1px solid rgba(255,0,0,0.2);padding:8px 18px;border-radius:4px;text-decoration:none;">▶ Search YouTube Videos</a>
        </div>
      </div>`;
  }

  function switchPapers_fromNote(currLabel) {
    const navItems = document.querySelectorAll('.fdash-nav');
    navItems.forEach(n => { if (n.dataset && n.dataset.panel === 'papers') n.click(); });
  }

  // Toast notification
  function showToast(msg) {
    let t = document.getElementById('ef-toast');
    if (!t) {
      t = document.createElement('div');
      t.id = 'ef-toast';
      t.style.cssText = 'position:fixed;bottom:24px;left:50%;transform:translateX(-50%) translateY(20px);background:#0d0f0e;border:1px solid rgba(200,146,42,0.4);color:var(--paper,#f7f5f0);font-family:Syne,sans-serif;font-size:13px;font-weight:600;padding:12px 22px;border-radius:8px;z-index:99999;opacity:0;transition:all 0.25s;pointer-events:none;white-space:nowrap;';
      document.body.appendChild(t);
    }
    t.textContent = msg;
    t.style.opacity = '1';
    t.style.transform = 'translateX(-50%) translateY(0)';
    clearTimeout(t._timer);
    t._timer = setTimeout(() => { t.style.opacity = '0'; t.style.transform = 'translateX(-50%) translateY(20px)'; }, 2800);
  }

  // Init on page load
  document.addEventListener('DOMContentLoaded', () => {
    renderMySubjects();
    restoreStarredUI();
  });


// ===== PRACTICE ENGINE =====
const PRAC_BANK = [
  { type:'mcq', topic:'Organic Mechanisms', diff:'Standard', marks:2, q:'Which reagent is used in nucleophilic substitution of a halogenoalkane to form an alcohol?', opts:['Aqueous NaOH','Ethanolic NaOH','NH₃ in ethanol','H₂SO₄ / H₂O'], ans:0, fb:'Aqueous NaOH (warm) provides OH⁻ ions which act as the nucleophile, displacing the halide via an SN2 mechanism. Ethanolic NaOH would cause elimination instead. Mark: state reagent (1) + mechanism/product (1).' },
  { type:'mcq', topic:'Equilibria', diff:'Standard', marks:1, q:'For the reaction: N₂(g) + 3H₂(g) ⇌ 2NH₃(g), increasing pressure will:', opts:['Shift equilibrium right, increasing yield of NH₃','Shift equilibrium left, decreasing yield','Have no effect on position of equilibrium','Increase the rate but not the yield'], ans:0, fb:'Increasing pressure shifts equilibrium towards fewer moles of gas. Right side has 2 mol; left has 4 mol. So equilibrium shifts right, increasing NH₃ yield. This is Le Chatelier\'s Principle applied to pressure.' },
  { type:'structured', topic:'Redox Titrations', diff:'Challenging', marks:4, q:'In a titration, 25.0 cm³ of 0.020 mol dm⁻³ KMnO₄ reacted with 20.0 cm³ of iron(II) sulfate solution. Calculate the concentration of the Fe²⁺ solution. [4 marks]\nMnO₄⁻ + 5Fe²⁺ + 8H⁺ → Mn²⁺ + 5Fe³⁺ + 4H₂O', opts:[], ans:-1, fb:'Step 1: moles KMnO₄ = 0.0250 × 0.020 = 5.0×10⁻⁴ mol\nStep 2: moles Fe²⁺ = 5 × 5.0×10⁻⁴ = 2.5×10⁻³ mol (ratio 1:5)\nStep 3: [Fe²⁺] = 2.5×10⁻³ ÷ 0.0200 = 0.125 mol dm⁻³\nMark scheme: moles KMnO₄ (1) · correct ratio applied (1) · moles Fe²⁺ (1) · final concentration (1)' },
  { type:'mcq', topic:'Atomic Structure', diff:'Foundation', marks:1, q:'Which of the following correctly describes an isotope?', opts:['Atoms of different elements with the same mass number','Atoms of the same element with different numbers of neutrons','Atoms with the same number of protons and electrons','Ions with different charges'], ans:1, fb:'Isotopes are atoms of the same element (same atomic number / protons) but with different numbers of neutrons, giving different mass numbers. Examples: Carbon-12, Carbon-13, Carbon-14.' },
  { type:'mcq', topic:'Thermodynamics', diff:'Standard', marks:2, q:'Which of the following would have the most exothermic lattice enthalpy?', opts:['NaF','NaCl','MgO','KBr'], ans:2, fb:'MgO has the most exothermic lattice enthalpy because Mg²⁺ and O²⁻ both have 2+ and 2− charges (higher charge density than Na⁺/Cl⁻) and smaller ionic radii, leading to much stronger electrostatic attraction. Lattice enthalpy ∝ (charge)²/radius.' },
  { type:'structured', topic:'Organic Mechanisms', diff:'Challenging', marks:5, q:'Describe the mechanism for the electrophilic addition of HBr to propene. Explain why 2-bromopropane is the major product rather than 1-bromopropane. [5 marks]', opts:[], ans:-1, fb:'Mechanism (3): H⁺ from HBr acts as electrophile → attacks double bond → forms carbocation intermediate → Br⁻ attacks carbocation.\nRegioselectivity (2): Markovnikov\'s Rule — H adds to carbon with more H atoms → forms more stable secondary carbocation at C2 vs. primary at C1 → Br⁻ attacks C2 → major product is 2-bromopropane.' },
  { type:'mcq', topic:'Rates of Reaction', diff:'Standard', marks:1, q:'The rate equation for a reaction is: rate = k[A]²[B]. What are the units of k if concentration is in mol dm⁻³ and time in seconds?', opts:['mol⁻² dm⁶ s⁻¹','mol dm⁻³ s⁻¹','dm⁶ mol⁻² s⁻¹','s⁻¹'], ans:2, fb:'Overall order = 2+1 = 3. Units of k = rate/([A]²[B]) = (mol dm⁻³ s⁻¹)/(mol dm⁻³)³ = mol⁻² dm⁶ s⁻¹. Note: answers A and C are the same — the correct IUPAC format is mol⁻² dm⁶ s⁻¹.' },
  { type:'mcq', topic:'Electrode Potentials', diff:'Standard', marks:2, q:'The standard electrode potential E° for a half-cell is measured against:', opts:['Any reference electrode','The standard hydrogen electrode (SHE) at 298K, 1 atm, 1 mol dm⁻³','A saturated calomel electrode','A standard calomel electrode at 273K'], ans:1, fb:'All standard electrode potentials are measured against the standard hydrogen electrode (SHE), which is assigned E° = 0.00 V. Conditions: 298 K, 100 kPa, all solutions at 1.00 mol dm⁻³. This ensures universally comparable values.' },
  { type:'structured', topic:'Equilibria', diff:'Challenging', marks:4, q:'State and explain the effect of adding a catalyst on: (i) the position of equilibrium; (ii) the rate of forward reaction; (iii) the value of Kc. [4 marks]', opts:[], ans:-1, fb:'(i) Position of equilibrium: NO change — catalyst equally speeds up forward and reverse reactions. (1)\n(ii) Rate of forward reaction: INCREASES — catalyst provides an alternative route with lower activation energy. (1)\n(iii) Kc: NO change — Kc depends only on temperature, not catalyst. (1)\nPlus: correct explanation of how catalyst works (alternative pathway / lower Ea). (1)' },
  { type:'mcq', topic:'Organic Chemistry', diff:'Foundation', marks:1, q:'What is the general formula for an alkane?', opts:['CₙH₂ₙ','CₙH₂ₙ₊₂','CₙH₂ₙ₋₂','CₙH₂ₙ₊₁'], ans:1, fb:'Alkanes are saturated hydrocarbons with the general formula CₙH₂ₙ₊₂. Example: methane CH₄ (n=1), ethane C₂H₆ (n=2). Alkenes are CₙH₂ₙ and alkynes are CₙH₂ₙ₋₂.' },
];
let pracState = { current:0, questions:[], answers:[], feedbacks:[], flipped:false, sessionCount:0, correct:0 };

function startPractice() {
  const n = parseInt(document.getElementById('prac-qcount').value);
  const shuffled = [...PRAC_BANK].sort(() => Math.random()-0.5).slice(0, Math.min(n, PRAC_BANK.length));
  pracState = { current:0, questions:shuffled, answers:new Array(shuffled.length).fill(null), feedbacks:[], flipped:false, sessionCount:shuffled.length, correct:0 };
  document.getElementById('prac-setup').style.display = 'none';
  document.getElementById('prac-active').style.display = 'block';
  pracRenderQ();
}
function pracRenderQ() {
  const q = pracState.questions[pracState.current];
  const n = pracState.current + 1;
  const total = pracState.questions.length;
  document.getElementById('prac-progress-bar').style.width = ((n-1)/total*100) + '%';
  document.getElementById('prac-progress-label').textContent = 'Q ' + n + ' / ' + total;
  document.getElementById('prac-score-live').textContent = pracState.correct + ' correct';
  document.getElementById('prac-q-badge').textContent = q.type === 'mcq' ? 'MCQ' : 'Structured';
  document.getElementById('prac-q-diff-badge').textContent = q.diff;
  document.getElementById('prac-q-topic-lbl').textContent = q.topic;
  document.getElementById('prac-q-text').textContent = q.q;
  document.getElementById('prac-feedback').style.display = 'none';
  document.getElementById('prac-submit-btn').style.display = 'inline-flex';
  document.getElementById('prac-next-btn').style.display = 'none';
  const opts = document.getElementById('prac-q-opts');
  const ft = document.getElementById('prac-q-free');
  if (q.type === 'mcq') {
    ft.style.display = 'none'; opts.style.display = 'flex';
    opts.innerHTML = q.opts.map((o,i) => {
      const sel = pracState.answers[pracState.current] === i;
      return '<div onclick="pracSelectOpt('+i+')" style="display:flex;align-items:flex-start;gap:10px;padding:9px 13px;border:1px solid rgba(247,245,240,'+(sel?'0.35':'0.1')+');border-radius:var(--radius);cursor:pointer;background:rgba(247,245,240,'+(sel?'0.07':'0.02')+');transition:all 0.15s;">'
        +'<div style="width:17px;height:17px;border-radius:50%;border:1.5px solid rgba(247,245,240,'+(sel?'0.65':'0.25')+');flex-shrink:0;margin-top:2px;display:flex;align-items:center;justify-content:center;">'+(sel?'<div style="width:7px;height:7px;border-radius:50%;background:var(--gold);"></div>':'')+'</div>'
        +'<span style="font-size:13px;color:rgba(247,245,240,'+(sel?'0.9':'0.65')+');">'+String.fromCharCode(65+i)+'. '+o+'</span></div>';
    }).join('');
  } else {
    opts.style.display = 'none'; ft.style.display = 'block';
    ft.value = pracState.answers[pracState.current] || '';
    ft.oninput = () => { pracState.answers[pracState.current] = ft.value; };
  }
}
function pracSelectOpt(i) {
  pracState.answers[pracState.current] = i;
  pracRenderQ();
}
function pracSubmit() {
  const q = pracState.questions[pracState.current];
  const a = pracState.answers[pracState.current];
  let isCorrect = false;
  if (q.type === 'mcq') {
    isCorrect = a === q.ans;
    if (isCorrect) pracState.correct++;
  }
  const fb = document.getElementById('prac-feedback');
  const icon = document.getElementById('prac-fb-icon');
  const title = document.getElementById('prac-fb-title');
  const body = document.getElementById('prac-fb-body');
  const marks = document.getElementById('prac-fb-marks');
  fb.style.display = 'block';
  if (q.type === 'mcq') {
    icon.textContent = isCorrect ? '✅' : '❌';
    title.textContent = isCorrect ? 'Correct!' : 'Incorrect — correct answer: ' + String.fromCharCode(65+q.ans) + '. ' + q.opts[q.ans];
    title.style.color = isCorrect ? '#5bce8a' : '#e05858';
    fb.style.borderColor = isCorrect ? 'rgba(91,206,138,0.25)' : 'rgba(224,88,88,0.25)';
    fb.style.background = isCorrect ? 'rgba(91,206,138,0.06)' : 'rgba(224,88,88,0.06)';
  } else {
    icon.textContent = '📋';
    title.textContent = 'Model answer & mark scheme';
    title.style.color = 'var(--gold)';
    fb.style.borderColor = 'rgba(200,146,42,0.25)'; fb.style.background = 'rgba(200,146,42,0.06)';
  }
  body.textContent = q.fb;
  marks.textContent = '[' + q.marks + ' mark' + (q.marks>1?'s':'') + '] · Topic: ' + q.topic;
  document.getElementById('prac-submit-btn').style.display = 'none';
  document.getElementById('prac-next-btn').style.display = 'inline-flex';
  const isLast = pracState.current === pracState.questions.length - 1;
  document.getElementById('prac-next-btn').textContent = isLast ? 'View results →' : 'Next question →';
}
function pracNext() {
  if (pracState.current < pracState.questions.length - 1) {
    pracState.current++;
    pracRenderQ();
  } else {
    endPractice();
  }
}
function endPractice() {
  document.getElementById('prac-active').style.display = 'none';
  document.getElementById('prac-results').style.display = 'block';
  const total = pracState.questions.length;
  const mcqQs = pracState.questions.filter(q=>q.type==='mcq');
  const pct = mcqQs.length > 0 ? Math.round((pracState.correct/mcqQs.length)*100) : 0;
  const structured = pracState.questions.filter(q=>q.type!=='mcq').length;
  document.getElementById('prac-results-emoji').textContent = pct >= 80 ? '🏆' : pct >= 60 ? '👍' : '📚';
  document.getElementById('prac-results-sub').textContent = total + ' questions · ' + pracState.correct + '/' + mcqQs.length + ' MCQ correct · ' + structured + ' structured answered';
  document.getElementById('prac-results-grid').innerHTML = [
    ['MCQ accuracy', pct + '%', pct>=70?'#5bce8a':'#e05858'],
    ['Structured answered', structured + '/' + structured, 'var(--gold)'],
    ['Session score', pracState.correct + ' pts', 'var(--paper)'],
  ].map(([l,v,c]) => '<div style="background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius);padding:12px;text-align:center;"><div style="font-family:\'JetBrains Mono\',monospace;font-size:9px;color:rgba(247,245,240,0.35);letter-spacing:0.06em;text-transform:uppercase;margin-bottom:6px;">'+l+'</div><div style="font-family:\'Syne\',sans-serif;font-size:22px;font-weight:800;color:'+c+';">'+v+'</div></div>').join('');
  document.getElementById('prac-results-breakdown').innerHTML = '<div style="font-family:\'Syne\',sans-serif;font-size:12px;font-weight:700;color:var(--paper);margin-bottom:10px;">Topics covered this session</div>'
    + [...new Set(pracState.questions.map(q=>q.topic))].map(t => {
      const qs = pracState.questions.filter(q=>q.topic===t);
      const correct = qs.filter((q,_)=>{ const i=pracState.questions.indexOf(q); return pracState.answers[i]===q.ans && q.type==='mcq'; }).length;
      const mcq = qs.filter(q=>q.type==='mcq').length;
      return '<div style="display:flex;align-items:center;justify-content:space-between;padding:6px 0;border-bottom:1px solid rgba(247,245,240,0.06);">'
        +'<span style="font-size:12px;color:rgba(247,245,240,0.75);">'+t+'</span>'
        +'<span style="font-family:\'JetBrains Mono\',monospace;font-size:11px;color:'+(mcq>0&&correct/mcq>=0.7?'#5bce8a':mcq>0?'#e05858':'var(--gold)')+';">'+(mcq>0?correct+'/'+mcq+' MCQ':'structured only')+'</span>'
        +'</div>';
    }).join('');
}
function resetPractice() {
  document.getElementById('prac-results').style.display = 'none';
  document.getElementById('prac-setup').style.display = 'block';
}

// ===== FLASHCARDS ENGINE =====
const FC_DECKS = [
  { name:'Organic Chemistry', subject:'Chemistry', count:38, due:24, color:'#e05858' },
  { name:'Equilibria & Kinetics', subject:'Chemistry', count:31, due:18, color:'var(--gold)' },
  { name:'Atomic Structure', subject:'Chemistry', count:22, due:9, color:'#5ba8e8' },
  { name:'Key Definitions', subject:'All', count:67, due:45, color:'#5bce8a' },
  { name:'Exam Technique', subject:'All', count:28, due:14, color:'rgba(247,245,240,0.6)' },
  { name:'Thermodynamics', subject:'Chemistry', count:19, due:12, color:'var(--gold)' },
];
const FC_CARDS = [
  { front:'Define: Le Chatelier\'s Principle', back:'If a system at dynamic equilibrium is subjected to a change in conditions, it will shift to oppose that change and re-establish equilibrium.', type:'definition', subject:'Chemistry' },
  { front:'What is the Brønsted-Lowry definition of an acid?', back:'A proton donor — a species that donates H⁺ ions to another species. The corresponding base accepts the H⁺. Every acid-base reaction involves a conjugate acid-base pair.', type:'definition', subject:'Chemistry' },
  { front:'State the Ideal Gas Equation', back:'pV = nRT\nwhere p = pressure (Pa), V = volume (m³), n = moles, R = 8.314 J mol⁻¹ K⁻¹, T = temperature (K)', type:'formula', subject:'Chemistry' },
  { front:'What does "evaluate" mean in IB/A-level questions?', back:'Make a judgement about the value of something by weighing up strengths and weaknesses/limitations. Must reach a supported conclusion. Do not just describe — assess.', type:'examtip', subject:'Exam Technique' },
  { front:'Define: lattice enthalpy', back:'The enthalpy change when 1 mole of an ionic compound is formed from its gaseous ions under standard conditions. Always exothermic. More negative = stronger ionic lattice.', type:'definition', subject:'Chemistry' },
  { front:'What is the Aufbau principle?', back:'Electrons fill orbitals of lowest energy first. Order: 1s, 2s, 2p, 3s, 3p, 4s, 3d, 4p... Each orbital holds max 2 electrons with opposite spins (Pauli exclusion).', type:'concept', subject:'Chemistry' },
  { front:'Nucleophilic Substitution — SN2 mechanism?', back:'One-step mechanism: nucleophile attacks carbon from the back of the C-X bond simultaneously as X⁻ leaves. Inversion of configuration (Walden inversion). Favoured by primary halogenoalkanes + strong nucleophiles.', type:'concept', subject:'Chemistry' },
  { front:'Hess\'s Law — state it', back:'The total enthalpy change of a chemical reaction is independent of the route taken, provided the initial and final conditions are the same. Consequence of the first law of thermodynamics.', type:'definition', subject:'Chemistry' },
];
let fcState = { current:0, cards:[], flipped:false, correct:0, wrong:0 };

function fcBuildDecks() {
  const grid = document.getElementById('fc-deck-grid');
  if (!grid) return;
  grid.innerHTML = FC_DECKS.map(d =>
    '<div style="background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:14px;cursor:pointer;transition:all 0.15s;" onclick="fcStartDeck()" onmouseover="this.style.borderColor=\'rgba(200,146,42,0.3)\'" onmouseout="this.style.borderColor=\'rgba(247,245,240,0.1)\'">'
    +'<div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:6px;">'
    +'<div style="font-family:\'Syne\',sans-serif;font-size:12px;font-weight:700;color:var(--paper);">'+d.name+'</div>'
    +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:10px;color:'+d.color+';background:rgba(247,245,240,0.07);padding:2px 6px;border-radius:3px;">'+d.due+' due</div>'
    +'</div>'
    +'<div style="font-size:11px;color:rgba(247,245,240,0.35);margin-bottom:8px;">'+d.subject+' · '+d.count+' cards total</div>'
    +'<div style="width:100%;height:3px;background:rgba(247,245,240,0.08);border-radius:2px;overflow:hidden;">'
    +'<div style="height:100%;background:'+d.color+';width:'+(Math.round(d.due/d.count*100))+'%;border-radius:2px;"></div></div>'
    +'</div>'
  ).join('');
}
function fcStartDeck() { fcStartSession(); }
function fcStartSession() {
  fcState = { current:0, cards:[...FC_CARDS].sort(()=>Math.random()-0.5), flipped:false, correct:0, wrong:0 };
  document.getElementById('fc-home').style.display = 'none';
  document.getElementById('fc-session').style.display = 'block';
  fcRenderCard();
}
function fcRenderCard() {
  const c = fcState.cards[fcState.current];
  document.getElementById('fc-session-counter').textContent = 'Card ' + (fcState.current+1) + ' / ' + fcState.cards.length;
  document.getElementById('fc-session-correct').textContent = fcState.correct + ' ✓';
  document.getElementById('fc-session-wrong').textContent = fcState.wrong + ' ✗';
  document.getElementById('fc-front-type').textContent = c.type.toUpperCase();
  document.getElementById('fc-front-text').textContent = c.front;
  document.getElementById('fc-back-text').textContent = c.back;
  // Reset flip
  document.getElementById('fc-card-inner').style.transform = 'rotateY(0deg)';
  fcState.flipped = false;
  document.getElementById('fc-rating-btns').style.display = 'none';
  document.getElementById('fc-flip-hint').style.display = 'block';
}
function fcFlip() {
  if (fcState.flipped) return;
  fcState.flipped = true;
  document.getElementById('fc-card-inner').style.transform = 'rotateY(180deg)';
  document.getElementById('fc-rating-btns').style.display = 'flex';
  document.getElementById('fc-flip-hint').style.display = 'none';
}
function fcRate(rating) {
  if (rating === 'easy' || rating === 'good') fcState.correct++;
  else fcState.wrong++;
  if (fcState.current < fcState.cards.length - 1) {
    fcState.current++;
    fcRenderCard();
  } else {
    fcEndSession();
  }
}
function fcEndSession() {
  document.getElementById('fc-session').style.display = 'none';
  document.getElementById('fc-home').style.display = 'block';
  fcBuildDecks();
  // Show a brief toast
  const toast = document.createElement('div');
  toast.style.cssText = 'position:fixed;bottom:24px;right:24px;background:var(--ink);border:1px solid rgba(200,146,42,0.3);border-radius:var(--radius-lg);padding:14px 20px;font-family:\'Syne\',sans-serif;font-size:13px;font-weight:600;color:var(--paper);z-index:9999;transition:opacity 0.3s;';
  toast.textContent = '✓ Session complete — ' + fcState.correct + '/' + fcState.cards.length + ' rated Good/Easy';
  document.body.appendChild(toast);
  setTimeout(() => { toast.style.opacity='0'; setTimeout(()=>toast.remove(), 400); }, 2800);
}
function fcShowAddCard() {
  document.getElementById('fc-home').style.display = 'none';
  document.getElementById('fc-add-form').style.display = 'block';
}
function fcSaveCard() {
  const front = document.getElementById('fc-add-front').value.trim();
  const back = document.getElementById('fc-add-back').value.trim();
  if (!front || !back) { alert('Please fill in both front and back.'); return; }
  FC_CARDS.push({ front, back, type: document.getElementById('fc-add-type').value, subject: document.getElementById('fc-add-subject').value });
  document.getElementById('fc-add-form').style.display = 'none';
  document.getElementById('fc-home').style.display = 'block';
  fcBuildDecks();
  const toast = document.createElement('div');
  toast.style.cssText = 'position:fixed;bottom:24px;right:24px;background:var(--ink);border:1px solid rgba(91,206,138,0.3);border-radius:var(--radius-lg);padding:14px 20px;font-family:\'Syne\',sans-serif;font-size:13px;font-weight:600;color:#5bce8a;z-index:9999;transition:opacity 0.3s;';
  toast.textContent = '✓ Card added to your deck';
  document.body.appendChild(toast);
  setTimeout(() => { toast.style.opacity='0'; setTimeout(()=>toast.remove(), 400); }, 2000);
}

// ===== ANALYTICS ENGINE =====
function buildAnalytics() {
  // Heatmap
  const hm = document.getElementById('anal-heatmap');
  if (!hm) return;
  const intensities = [0,0,1,0,2,3,2,1,0,3,2,1,2,3,3,2,1,0,1,2,3,2,3,2,1,2,3,2,1,0,1,2,2,3,3,2,3,2,1,2,2,3,2,3,3,2,2,1,2,3,3,2,1,2,3,3,2,3,2,1,2,3,3,2,3,3,2,1,0,2];
  const cols = [];
  for (let w=0; w<10; w++) {
    let col = '<div style="display:flex;flex-direction:column;gap:3px;">';
    for (let d=0; d<7; d++) {
      const idx = w*7 + d;
      const v = intensities[idx] || 0;
      const bg = v===0?'rgba(247,245,240,0.06)':v===1?'rgba(200,146,42,0.2)':v===2?'rgba(200,146,42,0.45)':'var(--gold)';
      col += '<div style="width:10px;height:10px;border-radius:2px;background:'+bg+';"></div>';
    }
    col += '</div>';
    cols.push(col);
  }
  hm.innerHTML = cols.join('');

  // Grade trajectory
  const traj = document.getElementById('anal-trajectory');
  if (traj) {
    const weeks = ['Wk1','Wk2','Wk3','Wk4','Wk5','Wk6','Wk7','Wk8'];
    const grades = [38,42,47,51,55,58,63,68]; // % → maps to grade
    const gradeLabel = g => g>=80?'A*':g>=70?'A':g>=60?'B':g>=50?'C':'D';
    const gradeColor = g => g>=70?'#5bce8a':g>=60?'var(--gold)':'#5ba8e8';
    traj.innerHTML = weeks.map((w,i) => {
      const h = Math.round((grades[i]/100)*88);
      return '<div style="display:flex;flex-direction:column;align-items:center;gap:4px;flex:1;">'
        +'<div style="font-family:\'Syne\',sans-serif;font-size:9px;font-weight:700;color:'+gradeColor(grades[i])+';margin-bottom:2px;">'+gradeLabel(grades[i])+'</div>'
        +'<div style="width:100%;height:'+h+'px;background:'+gradeColor(grades[i])+';border-radius:3px 3px 0 0;opacity:0.7;min-height:4px;"></div>'
        +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:9px;color:rgba(247,245,240,0.25);">'+w+'</div>'
        +'</div>';
    }).join('');
  }

  // Topic accuracy
  const topicsEl = document.getElementById('anal-topics');
  if (topicsEl) {
    const topics = [
      { name:'Atomic Structure', acc:88, trend:'↑' }, { name:'Bonding & Structure', acc:82, trend:'→' },
      { name:'Thermodynamics', acc:78, trend:'↑' }, { name:'Electrode Potentials', acc:71, trend:'↑' },
      { name:'Redox Titrations', acc:58, trend:'→' }, { name:'Equilibria Calcs', acc:52, trend:'↑' },
      { name:'Organic Mechanisms', acc:31, trend:'↓' }, { name:'Rates of Reaction', acc:74, trend:'↑' },
    ];
    topicsEl.innerHTML = topics.map(t => {
      const c = t.acc>=75?'#5bce8a':t.acc>=55?'var(--gold)':'#e05858';
      return '<div style="display:flex;align-items:center;gap:10px;">'
        +'<div style="width:120px;flex-shrink:0;font-size:12px;color:rgba(247,245,240,0.75);">'+t.name+'</div>'
        +'<div style="flex:1;height:5px;background:rgba(247,245,240,0.08);border-radius:3px;overflow:hidden;">'
        +'<div style="height:100%;width:'+t.acc+'%;background:'+c+';border-radius:3px;transition:width 0.8s ease;"></div></div>'
        +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:11px;color:'+c+';width:32px;text-align:right;">'+t.acc+'%</div>'
        +'<div style="font-size:11px;width:14px;color:'+c+';">'+t.trend+'</div>'
        +'</div>';
    }).join('');
  }

  // Session history
  const sessEl = document.getElementById('anal-sessions');
  if (sessEl) {
    const sessions = [
      { date:'Today', type:'Practice', score:'8/10 MCQ', time:'42 min', color:'var(--gold)' },
      { date:'Yesterday', type:'Exam Sim', score:'B+ predicted', time:'60 min', color:'#5ba8e8' },
      { date:'Mon 7 Apr', type:'Flashcards', score:'38 cards reviewed', time:'22 min', color:'#5bce8a' },
      { date:'Sun 6 Apr', type:'Practice', score:'6/8 MCQ', time:'35 min', color:'var(--gold)' },
      { date:'Sat 5 Apr', type:'Exam Sim', score:'A predicted', time:'90 min', color:'#5bce8a' },
    ];
    sessEl.innerHTML = sessions.map(s =>
      '<div style="display:flex;align-items:center;gap:12px;padding:8px 0;border-bottom:1px solid rgba(247,245,240,0.06);">'
      +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:10px;color:rgba(247,245,240,0.35);width:72px;flex-shrink:0;">'+s.date+'</div>'
      +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:9px;letter-spacing:0.06em;text-transform:uppercase;background:rgba(247,245,240,0.07);color:rgba(247,245,240,0.5);padding:2px 7px;border-radius:3px;flex-shrink:0;">'+s.type+'</div>'
      +'<div style="flex:1;font-size:12px;color:rgba(247,245,240,0.75);">'+s.score+'</div>'
      +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:10px;color:rgba(247,245,240,0.3);">'+s.time+'</div>'
      +'</div>'
    ).join('');
  }
}

// ===== SETTINGS =====
const SETT_TOGGLES = [
  { key:'daily_plan', label:'Show AI-generated daily plan', desc:'Generates a personalised revision schedule each morning', on:true },
  { key:'applock', label:'Enable app lock in exams by default', desc:'Automatically activates when you start an exam simulation', on:true },
  { key:'sound', label:'Sound effects', desc:'Tick sounds, completion chimes, and timer alerts', on:false },
  { key:'animations', label:'Reduce animations', desc:'Simplifies card flips, transitions, and loading effects', on:false },
  { key:'show_marks', label:'Show mark allocations on questions', desc:'Displays [X marks] before each question in practice mode', on:true },
];
const SETT_NOTIFS = [
  { key:'daily_reminder', label:'Daily study reminder', desc:'Get a push notification at your chosen time', on:true },
  { key:'streak', label:'Streak alerts', desc:'Warn you when your daily streak is about to break', on:true },
  { key:'exam_countdown', label:'Exam countdown notifications', desc:'Reminders at 30, 14, 7, and 1 day before your exam', on:true },
  { key:'new_features', label:'New feature announcements', desc:'Be notified when new subjects or tools are released', on:false },
];
function buildSettingsToggles() {
  const makeToggle = (items, containerId) => {
    const el = document.getElementById(containerId);
    if (!el) return;
    el.innerHTML = items.map((t,i) =>
      '<div style="display:flex;align-items:center;justify-content:space-between;padding:11px 0;'+(i<items.length-1?'border-bottom:1px solid rgba(247,245,240,0.06);':'') +'">'
      +'<div style="flex:1;padding-right:16px;">'
      +'<div style="font-size:13px;color:rgba(247,245,240,0.85);">'+t.label+'</div>'
      +'<div style="font-size:11px;color:rgba(247,245,240,0.35);margin-top:1px;">'+t.desc+'</div>'
      +'</div>'
      +'<div onclick="settToggle(this,\''+t.key+'\')" data-on="'+(t.on?'1':'0')+'" style="width:38px;height:21px;border-radius:12px;background:'+(t.on?'var(--gold)':'rgba(247,245,240,0.15)')+';cursor:pointer;position:relative;transition:background 0.2s;flex-shrink:0;">'
      +'<div style="width:17px;height:17px;border-radius:50%;background:white;position:absolute;top:2px;'+(t.on?'right:2px;':'left:2px;')+';transition:all 0.2s;"></div>'
      +'</div>'
      +'</div>'
    ).join('');
  };
  makeToggle(SETT_TOGGLES, 'sett-toggles');
  makeToggle(SETT_NOTIFS, 'sett-notif-toggles');
}
function settToggle(el, key) {
  const isOn = el.dataset.on === '1';
  el.dataset.on = isOn ? '0' : '1';
  el.style.background = isOn ? 'rgba(247,245,240,0.15)' : 'var(--gold)';
  el.children[0].style.left = isOn ? '2px' : '';
  el.children[0].style.right = isOn ? '' : '2px';
}
function settGradeSelect(btn) {
  document.querySelectorAll('.sett-grade-btn').forEach(b => {
    b.style.background = 'transparent'; b.style.color = 'rgba(247,245,240,0.5)'; b.style.borderColor = 'rgba(247,245,240,0.15)';
    b.classList.remove('sett-grade-active');
  });
  btn.style.background = 'rgba(200,146,42,0.15)'; btn.style.color = 'var(--gold)'; btn.style.borderColor = 'rgba(200,146,42,0.3)';
  btn.classList.add('sett-grade-active');
}

// ===== INIT ALL PANELS =====
document.addEventListener('DOMContentLoaded', () => {
  fcBuildDecks();
  buildAnalytics();
  buildSettingsToggles();
});
</script>
<script>
function navTo(panelId) {
  document.querySelectorAll('.fdash-nav').forEach(n => n.classList.remove('active'));
  document.querySelectorAll('.fdash-panel').forEach(p => p.classList.remove('active'));
  const nav = document.querySelector('.fdash-nav[data-panel="' + panelId + '"]');
  const panel = document.getElementById('fdash-' + panelId);
  if (nav) nav.classList.add('active');
  if (panel) panel.classList.add('active');
}

// ===== EXAM SIMULATOR =====
const ESIM_QUESTIONS = [
  { type:'mcq', topic:'Organic Chemistry', marks:2, q:'Which of the following is the correct IUPAC name for CH₃CH₂CH(OH)CH₃?', opts:['Butan-2-ol','Butan-3-ol','2-methylpropan-1-ol','Butan-1-ol'], ans:0 },
  { type:'mcq', topic:'Equilibria', marks:1, q:'Which change would increase the equilibrium yield of SO₃ in: 2SO₂(g) + O₂(g) ⇌ 2SO₃(g)  ΔH = −196 kJ mol⁻¹?', opts:['Increasing temperature','Decreasing pressure','Adding a catalyst','Removing SO₃ product'], ans:3 },
  { type:'structured', topic:'Atomic Structure', marks:4, q:'State and explain the trend in first ionisation energy across Period 3 (Na to Ar). [4 marks]', opts:[], ans:-1 },
  { type:'mcq', topic:'Redox', marks:1, q:'In the half-equation: MnO₄⁻ + 8H⁺ + 5e⁻ → Mn²⁺ + 4H₂O, manganese is:', opts:['Oxidised from +7 to +2','Reduced from +7 to +2','Oxidised from +2 to +7','Reduced from +2 to +7'], ans:1 },
  { type:'structured', topic:'Thermodynamics', marks:5, q:'Define lattice enthalpy and explain why the lattice enthalpy of MgO is much larger than that of NaF. [5 marks]', opts:[], ans:-1 },
  { type:'mcq', topic:'Rates of Reaction', marks:1, q:'A reaction is second order with respect to reactant A and zero order with respect to reactant B. Doubling [A] while halving [B] will change the rate by a factor of:', opts:['×1 (no change)','×2','×4','×0.5'], ans:2 },
  { type:'structured', topic:'Organic Mechanisms', marks:6, q:'Draw the mechanism for the reaction of bromine water with ethene. Name the mechanism and explain why the product is 1,2-dibromoethane rather than 1,1-dibromoethane. [6 marks]', opts:[], ans:-1 },
  { type:'mcq', topic:'Electrode Potentials', marks:2, q:'Using standard electrode potentials: E°(Zn²⁺/Zn) = −0.76V and E°(Cu²⁺/Cu) = +0.34V. What is the standard EMF of a cell where Zn is oxidised?', opts:['−1.10 V','+1.10 V','+0.42 V','−0.42 V'], ans:1 },
];
let esimState = { current:0, answers:[], timerSecs:0, totalSecs:0, interval:null, breaks:0, startTime:null, lockActive:false };

function startExamSim() {
  const dur = parseInt(document.getElementById('esim-duration').value);
  esimState = { current:0, answers:new Array(ESIM_QUESTIONS.length).fill(null), timerSecs:dur*60, totalSecs:dur*60, interval:null, breaks:0, startTime:Date.now(), lockActive:document.getElementById('esim-applock').checked };
  document.getElementById('esim-setup').style.display = 'none';
  document.getElementById('esim-active').style.display = 'block';
  esimRenderQ();
  esimStartTimer();
  if (esimState.lockActive) {
    document.addEventListener('visibilitychange', esimVisChange);
    window.addEventListener('blur', esimBlur);
  }
}
function esimStartTimer() {
  esimState.interval = setInterval(() => {
    esimState.timerSecs--;
    const m = Math.floor(esimState.timerSecs/60);
    const s = esimState.timerSecs%60;
    document.getElementById('esim-timer-display').textContent = String(m).padStart(2,'0') + ':' + String(s).padStart(2,'0');
    const pct = (esimState.timerSecs / esimState.totalSecs) * 100;
    const bar = document.getElementById('esim-timer-bar');
    bar.style.width = pct + '%';
    bar.style.background = pct > 50 ? 'var(--gold)' : pct > 20 ? '#ef9f27' : '#e05858';
    document.getElementById('esim-timer-display').style.color = pct > 20 ? 'var(--paper)' : '#e05858';
    if (esimState.timerSecs <= 0) endExamSim();
  }, 1000);
}
function esimVisChange() { if (document.hidden) esimTriggerLock(); }
function esimBlur() { esimTriggerLock(); }
function esimTriggerLock() {
  if (!esimState.lockActive) return;
  esimState.breaks++;
  clearInterval(esimState.interval);
  const ov = document.getElementById('esim-lockoverlay');
  ov.style.display = 'flex';
  document.getElementById('esim-focus-status').textContent = '🔴 ' + esimState.breaks + ' break' + (esimState.breaks>1?'s':'') + ' detected';
}
function resumeExamSim() {
  document.getElementById('esim-lockoverlay').style.display = 'none';
  esimStartTimer();
}
function esimRenderQ() {
  const q = ESIM_QUESTIONS[esimState.current];
  const n = esimState.current + 1;
  document.getElementById('esim-q-counter').textContent = 'Q ' + n + ' / ' + ESIM_QUESTIONS.length;
  document.getElementById('esim-q-type-badge').textContent = q.type === 'mcq' ? 'MCQ' : q.type === 'structured' ? 'Structured' : 'Extended';
  document.getElementById('esim-q-marks').textContent = '[' + q.marks + ' mark' + (q.marks>1?'s':'') + ']';
  document.getElementById('esim-q-topic').textContent = 'Topic: ' + q.topic;
  document.getElementById('esim-q-text').textContent = q.q;
  const opts = document.getElementById('esim-q-options');
  const ft = document.getElementById('esim-q-freetext');
  if (q.type === 'mcq') {
    ft.style.display = 'none'; opts.style.display = 'flex';
    opts.innerHTML = q.opts.map((o,i) => {
      const sel = esimState.answers[esimState.current] === i;
      return '<div onclick="esimSelectOpt('+i+')" style="display:flex;align-items:flex-start;gap:10px;padding:10px 14px;border:1px solid rgba(247,245,240,'+(sel?'0.4':'0.1')+');border-radius:var(--radius);cursor:pointer;background:rgba(247,245,240,'+(sel?'0.08':'0.02')+');transition:all 0.15s;">'
        +'<div style="width:18px;height:18px;border-radius:50%;border:1.5px solid rgba(247,245,240,'+(sel?'0.7':'0.3')+');flex-shrink:0;margin-top:1px;display:flex;align-items:center;justify-content:center;">'+(sel?'<div style="width:8px;height:8px;border-radius:50%;background:var(--gold);"></div>':'')+'</div>'
        +'<span style="font-size:13px;color:rgba(247,245,240,'+(sel?'0.95':'0.7')+');">'+(String.fromCharCode(65+i))+'. '+o+'</span></div>';
    }).join('');
  } else {
    opts.style.display = 'none'; ft.style.display = 'block';
    ft.value = esimState.answers[esimState.current] || '';
    ft.oninput = () => { esimState.answers[esimState.current] = ft.value; };
  }
  // Dots
  document.getElementById('esim-q-dots').innerHTML = ESIM_QUESTIONS.map((_,i) => {
    const ans = esimState.answers[i] !== null;
    const cur = i === esimState.current;
    return '<div style="width:'+(cur?'20px':'8px')+';height:8px;border-radius:4px;background:'+(cur?'var(--gold)':ans?'rgba(91,206,138,0.5)':'rgba(247,245,240,0.15)')+';transition:all 0.2s;"></div>';
  }).join('');
  const isLast = esimState.current === ESIM_QUESTIONS.length - 1;
  document.getElementById('esim-next-btn').textContent = isLast ? 'Finish exam →' : 'Next →';
}
function esimSelectOpt(i) {
  esimState.answers[esimState.current] = i;
  esimRenderQ();
}
function esimPrev() { if (esimState.current > 0) { esimState.current--; esimRenderQ(); } }
function esimNext() {
  if (esimState.current < ESIM_QUESTIONS.length - 1) { esimState.current++; esimRenderQ(); }
  else endExamSim();
}
function endExamConfirm() { if (confirm('End the exam now? Unanswered questions will be marked as blank.')) endExamSim(); }
function endExamSim() {
  clearInterval(esimState.interval);
  document.removeEventListener('visibilitychange', esimVisChange);
  window.removeEventListener('blur', esimBlur);
  document.getElementById('esim-active').style.display = 'none';
  document.getElementById('esim-results').style.display = 'block';
  const elapsed = Math.round((Date.now() - esimState.startTime) / 60000);
  document.getElementById('esim-results-meta').textContent = 'A-Level Chemistry · ' + elapsed + ' min · ' + esimState.breaks + ' focus break' + (esimState.breaks!==1?'s':'') + ' logged';
  const mcqQs = ESIM_QUESTIONS.filter(q => q.type==='mcq');
  const correct = mcqQs.filter((q,_) => {
    const idx = ESIM_QUESTIONS.indexOf(q);
    return esimState.answers[idx] === q.ans;
  }).length;
  const answered = esimState.answers.filter(a => a !== null).length;
  const totalMarks = ESIM_QUESTIONS.reduce((s,q) => s+q.marks, 0);
  const pct = Math.round((correct / mcqQs.length) * 100);
  document.getElementById('esim-results-stats').innerHTML = [
    ['MCQ score', correct + '/' + mcqQs.length, correct/mcqQs.length >= 0.7 ? '#5bce8a' : '#e05858'],
    ['Questions answered', answered + '/' + ESIM_QUESTIONS.length, 'var(--paper)'],
    ['Focus breaks', esimState.breaks, esimState.breaks===0 ? '#5bce8a' : '#e05858'],
    ['Predicted grade', pct>=80?'A*':pct>=70?'A':pct>=60?'B':pct>=50?'C':'D', pct>=70?'#5bce8a':'var(--gold)'],
  ].map(([l,v,c]) => '<div style="background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius);padding:12px;"><div style="font-family:\'JetBrains Mono\',monospace;font-size:10px;color:rgba(247,245,240,0.4);letter-spacing:0.06em;text-transform:uppercase;margin-bottom:6px;">'+l+'</div><div style="font-family:\'Syne\',sans-serif;font-size:20px;font-weight:800;color:'+c+';">'+v+'</div></div>').join('');
  document.getElementById('esim-results-breakdown').innerHTML = ESIM_QUESTIONS.map((q,i) => {
    const a = esimState.answers[i];
    const answered = a !== null;
    const correct = q.type==='mcq' ? a === q.ans : null;
    const icon = q.type!=='mcq' ? '⏳' : correct ? '✓' : '✗';
    const color = q.type!=='mcq' ? '#5ba8e8' : correct ? '#5bce8a' : '#e05858';
    const hint = q.type==='mcq' && !correct ? 'Correct: ' + q.opts[q.ans] : q.type!=='mcq' ? 'Long-answer: review against mark scheme' : 'Correct';
    return '<div style="display:flex;align-items:flex-start;gap:10px;padding:10px 14px;background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.08);border-radius:var(--radius);">'
      +'<div style="font-size:13px;color:'+color+';margin-top:1px;flex-shrink:0;">'+icon+'</div>'
      +'<div style="flex:1;"><div style="font-size:12px;color:rgba(247,245,240,0.8);margin-bottom:2px;">Q'+(i+1)+' · '+q.topic+' · ['+q.marks+' mark'+(q.marks>1?'s':'')+']</div>'
      +'<div style="font-size:11px;color:rgba(247,245,240,0.4);">'+hint+'</div></div></div>';
  }).join('');
}
function resetExamSim() {
  document.getElementById('esim-setup').style.display = 'block';
  document.getElementById('esim-active').style.display = 'none';
  document.getElementById('esim-results').style.display = 'none';
  document.getElementById('esim-lockoverlay').style.display = 'none';
}

// ===== MY NOTES =====
let mnNotes = JSON.parse(localStorage.getItem('ef_notes') || '[]');
let mnCurrent = null;
function mnRender() {
  const q = (document.getElementById('mn-search')?.value||'').toLowerCase();
  const subj = document.getElementById('mn-filter-subject')?.value||'';
  const tag = document.getElementById('mn-filter-tag')?.value||'';
  let filtered = mnNotes.filter(n =>
    (!q || n.title.toLowerCase().includes(q) || n.body.toLowerCase().includes(q)) &&
    (!subj || n.subject === subj) &&
    (!tag || n.tag === tag)
  );
  const grid = document.getElementById('mn-grid');
  const empty = document.getElementById('mn-empty');
  if (!grid) return;
  if (filtered.length === 0) { grid.innerHTML=''; empty.style.display='block'; return; }
  empty.style.display='none';
  grid.innerHTML = filtered.map(n => {
    const words = n.body.replace(/<[^>]+>/g,'').split(/\s+/).filter(Boolean).length;
    const preview = n.body.replace(/<[^>]+>/g,'').substring(0,90) + (n.body.length>90?'...':'');
    return '<div onclick="mnOpenNote(\''+n.id+'\')" style="background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:var(--radius-lg);padding:14px 16px;cursor:pointer;transition:border-color 0.15s;" onmouseover="this.style.borderColor=\'rgba(200,146,42,0.3)\'" onmouseout="this.style.borderColor=\'rgba(247,245,240,0.1)\'">'
      +'<div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:6px;">'
      +'<div style="font-family:\'Syne\',sans-serif;font-size:13px;font-weight:700;color:var(--paper);">'+n.title+'</div>'
      +(n.tag?'<span style="font-family:\'JetBrains Mono\',monospace;font-size:9px;letter-spacing:0.06em;text-transform:uppercase;padding:2px 7px;border-radius:3px;background:rgba(200,146,42,0.12);color:var(--gold);">'+n.tag+'</span>':'')+'</div>'
      +(n.subject?'<div style="font-family:\'JetBrains Mono\',monospace;font-size:10px;color:rgba(247,245,240,0.35);margin-bottom:6px;">'+n.subject+'</div>':'')
      +'<div style="font-size:12px;color:rgba(247,245,240,0.45);line-height:1.5;margin-bottom:8px;">'+preview+'</div>'
      +'<div style="font-size:10px;color:rgba(247,245,240,0.25);font-family:\'JetBrains Mono\',monospace;">'+words+' words · '+new Date(n.updated).toLocaleDateString()+'</div>'
      +'</div>';
  }).join('');
}
function mnSearch() { mnRender(); }
function mnCreateNote() {
  mnCurrent = { id: 'note_' + Date.now(), title:'Untitled note', subject:'', tag:'', body:'', updated: Date.now() };
  mnOpenEditor();
}
function mnOpenNote(id) { mnCurrent = mnNotes.find(n => n.id===id); if (mnCurrent) mnOpenEditor(); }
function mnOpenEditor() {
  document.getElementById('mynotes-list-view').style.display = 'none';
  document.getElementById('mynotes-editor-view').style.display = 'flex';
  document.getElementById('mn-title-input').value = mnCurrent.title;
  document.getElementById('mn-subject-select').value = mnCurrent.subject;
  document.getElementById('mn-tag-select').value = mnCurrent.tag;
  document.getElementById('mn-editor').innerHTML = mnCurrent.body || '';
  mnUpdateWordcount();
  document.getElementById('mn-saved-indicator').textContent = 'Saved';
  document.getElementById('mn-last-saved').textContent = mnCurrent.updated ? 'Last saved ' + new Date(mnCurrent.updated).toLocaleTimeString() : '';
}
function mnBack() {
  document.getElementById('mynotes-list-view').style.display = 'block';
  document.getElementById('mynotes-editor-view').style.display = 'none';
  mnRender();
}
function mnSave() {
  mnCurrent.title = document.getElementById('mn-title-input').value || 'Untitled note';
  mnCurrent.subject = document.getElementById('mn-subject-select').value;
  mnCurrent.tag = document.getElementById('mn-tag-select').value;
  mnCurrent.body = document.getElementById('mn-editor').innerHTML;
  mnCurrent.updated = Date.now();
  const idx = mnNotes.findIndex(n => n.id===mnCurrent.id);
  if (idx >= 0) mnNotes[idx] = mnCurrent; else mnNotes.unshift(mnCurrent);
  localStorage.setItem('ef_notes', JSON.stringify(mnNotes));
  document.getElementById('mn-saved-indicator').textContent = '✓ Saved';
  document.getElementById('mn-last-saved').textContent = 'Last saved ' + new Date().toLocaleTimeString();
}
function mnDelete() {
  if (!confirm('Delete this note permanently?')) return;
  mnNotes = mnNotes.filter(n => n.id !== mnCurrent.id);
  localStorage.setItem('ef_notes', JSON.stringify(mnNotes));
  mnBack();
}
function mnFormat(cmd) { document.getElementById('mn-editor').focus(); document.execCommand(cmd, false, null); mnMarkUnsaved(); }
function mnInsertHeading() {
  document.getElementById('mn-editor').focus();
  document.execCommand('insertHTML', false, '<h3 style="font-family:\'Syne\',sans-serif;font-size:15px;font-weight:700;color:var(--paper);margin:14px 0 6px;border-bottom:1px solid rgba(247,245,240,0.1);padding-bottom:4px;">New heading</h3><br>');
  mnMarkUnsaved();
}
function mnInsertList() {
  document.getElementById('mn-editor').focus();
  document.execCommand('insertUnorderedList', false, null);
  mnMarkUnsaved();
}
function mnInsertDivider() {
  document.getElementById('mn-editor').focus();
  document.execCommand('insertHTML', false, '<hr style="border:none;border-top:1px solid rgba(247,245,240,0.12);margin:12px 0;"><br>');
  mnMarkUnsaved();
}
function mnInsertBox(type) {
  const configs = {
    definition: { bg:'rgba(91,168,232,0.1)', border:'rgba(91,168,232,0.25)', color:'#5ba8e8', label:'Definition', placeholder:'Key term: ...' },
    formula: { bg:'rgba(200,146,42,0.1)', border:'rgba(200,146,42,0.25)', color:'var(--gold)', label:'Formula', placeholder:'Formula: ...' },
    examtip: { bg:'rgba(91,206,138,0.1)', border:'rgba(91,206,138,0.25)', color:'#5bce8a', label:'Exam tip', placeholder:'Remember to...' },
    mistake: { bg:'rgba(224,88,88,0.1)', border:'rgba(224,88,88,0.25)', color:'#e05858', label:'Common mistake', placeholder:'Students often...' },
  };
  const c = configs[type];
  document.getElementById('mn-editor').focus();
  document.execCommand('insertHTML', false,
    '<div style="background:'+c.bg+';border:1px solid '+c.border+';border-radius:6px;padding:10px 14px;margin:8px 0;" contenteditable="true">'
    +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:9px;letter-spacing:0.08em;text-transform:uppercase;color:'+c.color+';margin-bottom:4px;">'+c.label+'</div>'
    +'<div style="font-size:13px;color:rgba(247,245,240,0.85);">'+c.placeholder+'</div></div><br>'
  );
  mnMarkUnsaved();
}
function mnMarkUnsaved() {
  const ind = document.getElementById('mn-saved-indicator');
  if (ind) ind.textContent = 'Unsaved';
  mnUpdateWordcount();
}
function mnUpdateWordcount() {
  const el = document.getElementById('mn-editor');
  if (!el) return;
  const words = el.innerText.trim().split(/\s+/).filter(Boolean).length;
  const wc = document.getElementById('mn-wordcount');
  if (wc) wc.textContent = words + ' word' + (words!==1?'s':'');
}
document.addEventListener('DOMContentLoaded', () => {
  const ed = document.getElementById('mn-editor');
  if (ed) {
    ed.addEventListener('input', mnMarkUnsaved);
    ed.addEventListener('keydown', e => {
      if ((e.ctrlKey||e.metaKey) && e.key==='s') { e.preventDefault(); mnSave(); }
    });
  }
  mnRender();
  buildSuggestions();
});

// ===== AI SUGGESTIONS =====
const SUGG_WEEK = [
  { day:'Mon', tasks:['Organic Mechanisms — nucleophilic substitution (45 min)', 'Past paper Q: Equilibria (30 min)'], priority:'high' },
  { day:'Tue', tasks:['Redox Titrations — calculation practice (40 min)', 'Active recall flashcards (20 min)'], priority:'high' },
  { day:'Wed', tasks:['Full timed exam simulation — Paper 2 (90 min)', 'Review mark scheme after'], priority:'exam' },
  { day:'Thu', tasks:['Electrode Potentials — standard conditions (35 min)', 'Spaced repetition review (20 min)'], priority:'medium' },
  { day:'Fri', tasks:['Organic Mechanisms — elimination reactions (40 min)', 'Exam technique: 6-mark extended Q (25 min)'], priority:'high' },
  { day:'Sat', tasks:['Light revision day — flashcard deck only (30 min)'], priority:'low' },
  { day:'Sun', tasks:['Full topic recap — weakest 3 topics (60 min)', 'Practice paper mark-up'], priority:'medium' },
];
const SUGG_TOPICS = [
  { name:'Organic Mechanisms', acc:31, impact:'22 marks', roi:'Very High', color:'#e05858' },
  { name:'Equilibria Calculations', acc:52, impact:'18 marks', roi:'High', color:'var(--gold)' },
  { name:'Redox Titrations', acc:58, impact:'14 marks', roi:'High', color:'var(--gold)' },
  { name:'Electrode Potentials', acc:71, impact:'10 marks', roi:'Medium', color:'#5ba8e8' },
  { name:'Thermodynamics', acc:78, impact:'8 marks', roi:'Medium', color:'#5ba8e8' },
  { name:'Acid-Base Equilibria', acc:82, impact:'6 marks', roi:'Low', color:'rgba(247,245,240,0.4)' },
];
const SUGG_TECHNIQUES = [
  { icon:'⚠', color:'#e05858', title:'You lose marks on "explain" questions', body:'In 5+ mark questions you correctly state facts but omit the causal chain. Examiners require: state → reason → consequence. Practice this structure on past extended responses.' },
  { icon:'⏱', color:'var(--gold)', title:'Time management issue on Paper 2', body:'Your last simulation showed you spent 18 minutes on Q3 (6 marks) — leaving only 12 minutes for Q4 and Q5 (15 marks total). Practise allocating ~1.2 minutes per mark.' },
  { icon:'✓', color:'#5bce8a', title:'MCQ accuracy is strong', body:'Your multiple-choice score is in the top 20% of students. Focus your remaining time on structured and extended responses where the mark gap is largest.' },
];
const SUGG_SESSION = [
  { time:'0–10 min', task:'Warm-up: 10 spaced repetition flashcards (Organic + Redox)', type:'flashcard' },
  { time:'10–35 min', task:'Active recall: Equilibria Kc/Kp — 8 past paper Qs without notes', type:'practice' },
  { time:'35–52 min', task:'Timed extended response: 1× 6-mark mechanism question', type:'exam' },
];
function buildSuggestions() {
  const wp = document.getElementById('sugg-week-plan');
  if (wp) wp.innerHTML = SUGG_WEEK.map(d => {
    const pc = d.priority==='high'?'rgba(224,88,88,0.15)':d.priority==='exam'?'rgba(200,146,42,0.15)':d.priority==='medium'?'rgba(91,168,232,0.1)':'rgba(247,245,240,0.05)';
    const bc = d.priority==='high'?'rgba(224,88,88,0.3)':d.priority==='exam'?'rgba(200,146,42,0.3)':d.priority==='medium'?'rgba(91,168,232,0.2)':'rgba(247,245,240,0.1)';
    const lc = d.priority==='high'?'#e05858':d.priority==='exam'?'var(--gold)':d.priority==='medium'?'#5ba8e8':'rgba(247,245,240,0.3)';
    return '<div style="display:flex;align-items:flex-start;gap:12px;padding:10px 12px;background:'+pc+';border:1px solid '+bc+';border-radius:var(--radius);">'
      +'<div style="font-family:\'Syne\',sans-serif;font-size:11px;font-weight:700;color:'+lc+';width:28px;flex-shrink:0;padding-top:1px;">'+d.day+'</div>'
      +'<div style="flex:1;">'+d.tasks.map(t=>'<div style="font-size:12px;color:rgba(247,245,240,0.75);line-height:1.5;">• '+t+'</div>').join('')+'</div>'
      +'</div>';
  }).join('');
  const st = document.getElementById('sugg-topics');
  if (st) st.innerHTML = SUGG_TOPICS.map((t,i) => '<div style="display:flex;align-items:center;gap:10px;padding:10px 12px;background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.08);border-radius:var(--radius);">'
    +'<div style="font-family:\'Syne\',sans-serif;font-size:12px;font-weight:700;color:rgba(247,245,240,0.3);width:16px;flex-shrink:0;">'+(i+1)+'</div>'
    +'<div style="flex:1;"><div style="font-size:12px;color:rgba(247,245,240,0.85);">'+t.name+'</div>'
    +'<div style="display:flex;align-items:center;gap:6px;margin-top:4px;"><div style="flex:1;height:3px;background:rgba(247,245,240,0.1);border-radius:2px;overflow:hidden;"><div style="height:100%;background:'+t.color+';width:'+t.acc+'%;border-radius:2px;"></div></div><span style="font-family:\'JetBrains Mono\',monospace;font-size:10px;color:rgba(247,245,240,0.35);">'+t.acc+'%</span></div></div>'
    +'<div style="text-align:right;flex-shrink:0;"><div style="font-family:\'JetBrains Mono\',monospace;font-size:10px;color:'+t.color+';">'+t.roi+'</div><div style="font-size:10px;color:rgba(247,245,240,0.3);">'+t.impact+'</div></div></div>'
  ).join('');
  const sec = document.getElementById('sugg-techniques');
  if (sec) sec.innerHTML = SUGG_TECHNIQUES.map(t => '<div style="display:flex;align-items:flex-start;gap:10px;padding:10px 14px;background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.08);border-radius:var(--radius);">'
    +'<div style="font-size:14px;flex-shrink:0;margin-top:1px;">'+t.icon+'</div>'
    +'<div><div style="font-family:\'Syne\',sans-serif;font-size:12px;font-weight:700;color:'+t.color+';margin-bottom:4px;">'+t.title+'</div>'
    +'<div style="font-size:12px;color:rgba(247,245,240,0.55);line-height:1.6;">'+t.body+'</div></div></div>'
  ).join('');
  const sess = document.getElementById('sugg-session');
  if (sess) sess.innerHTML = SUGG_SESSION.map(s => {
    const bc = s.type==='flashcard'?'rgba(91,168,232,0.15)':s.type==='practice'?'rgba(200,146,42,0.15)':'rgba(224,88,88,0.15)';
    const tc = s.type==='flashcard'?'#5ba8e8':s.type==='practice'?'var(--gold)':'#e05858';
    return '<div style="display:flex;align-items:center;gap:10px;padding:8px 12px;background:'+bc+';border-radius:var(--radius);">'
      +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:10px;color:'+tc+';width:70px;flex-shrink:0;">'+s.time+'</div>'
      +'<div style="font-size:12px;color:rgba(247,245,240,0.8);">'+s.task+'</div></div>';
  }).join('');
}
</script>


<!-- SUBJECT LIBRARY OVERLAY -->
<div class="sublib-overlay" id="sublib-overlay">
  <div class="sublib-header">
    <div class="sublib-logo">Lumen &mdash; Subject Library</div>
    <button class="sublib-close" onclick="sublibClose()" title="Close">&#x2715;</button>
  </div>
  <div class="sublib-inner">
    <h1 class="sublib-big-title">Every subject.<br><em>Every curriculum.</em></h1>
    <p class="sublib-subtitle">255 subjects across GCSE, IGCSE, A-Level, IB and AP &mdash; click any subject to access notes, past papers, and exam resources. New subjects added weekly.</p>
    <div class="sublib-stats">
      <div class="sublib-stat"><div class="sublib-stat-num">255</div><div class="sublib-stat-lbl">Subjects</div></div>
      <div class="sublib-stat"><div class="sublib-stat-num">5</div><div class="sublib-stat-lbl">Curricula</div></div>
      <div class="sublib-stat"><div class="sublib-stat-num">40+</div><div class="sublib-stat-lbl">PDF Notes</div></div>
      <div class="sublib-stat"><div class="sublib-stat-num">250+</div><div class="sublib-stat-lbl">Past Papers</div></div>
      <div class="sublib-stat"><div class="sublib-stat-num">100%</div><div class="sublib-stat-lbl">Syllabus</div></div>
    </div>
    <div class="sublib-search-wrap">
      <input class="sublib-search" id="sublib-search" type="search" placeholder="Search all subjects&hellip; e.g. Biology, Calculus, History" oninput="sublibSearch(this.value)">
      <span class="sublib-search-icon">&#9906;</span>
    </div>
    <div class="sublib-tabs">
      <button class="sublib-tab on" onclick="sublibTab('GCSE',this)">🏫 GCSE <span style="font-family:'JetBrains Mono',monospace;font-size:10px;opacity:0.6">(57)</span></button>
<button class="sublib-tab" onclick="sublibTab('IGCSE',this)">🌏 IGCSE <span style="font-family:'JetBrains Mono',monospace;font-size:10px;opacity:0.6">(49)</span></button>
<button class="sublib-tab" onclick="sublibTab('A-Level',this)">🎓 A-Level <span style="font-family:'JetBrains Mono',monospace;font-size:10px;opacity:0.6">(63)</span></button>
<button class="sublib-tab" onclick="sublibTab('IB',this)">🌐 IB <span style="font-family:'JetBrains Mono',monospace;font-size:10px;opacity:0.6">(47)</span></button>
<button class="sublib-tab" onclick="sublibTab('AP',this)">🇺🇸 AP <span style="font-family:'JetBrains Mono',monospace;font-size:10px;opacity:0.6">(39)</span></button>

    </div>
    <div id="sublib-no-res" class="sublib-no-res">&#128269; No subjects found. Try a different search term.</div>
    <div class="sublib-section on" id="sublib-sec-GCSE">
<div class="sublib-curr-header" style="background:linear-gradient(135deg,rgba(26,102,68,0.1),rgba(26,102,68,0.03))"><div class="sublib-curr-icon">🏫</div><div><div class="sublib-curr-name">GCSE</div><div class="sublib-curr-desc">General Certificate of Secondary Education</div><span class="sublib-curr-badge" style="background:rgba(26,102,68,0.15);color:#1a6644">57 subjects</span></div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📐</span><span class="sublib-cat-title">Mathematics</span><span class="sublib-cat-count">4</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="mathematics gcse mathematics" onclick="sublibNotes('GCSE','math','Mathematics')"><div class="sublib-card-name">Mathematics</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('GCSE','math','Mathematics')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','math','Mathematics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="additional mathematics gcse mathematics" onclick="sublibNotes('GCSE','add-math','Additional Mathematics')"><div class="sublib-card-name">Additional Mathematics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','add-math','Additional Mathematics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="statistics gcse mathematics" onclick="sublibNotes('GCSE','statistics','Statistics')"><div class="sublib-card-name">Statistics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','statistics','Statistics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="further mathematics gcse mathematics" onclick="sublibNotes('GCSE','further-math','Further Mathematics')"><div class="sublib-card-name">Further Mathematics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','further-math','Further Mathematics')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🔬</span><span class="sublib-cat-title">Sciences</span><span class="sublib-cat-count">9</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="biology gcse sciences" onclick="sublibNotes('GCSE','biology','Biology')"><div class="sublib-card-name">Biology</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('GCSE','biology','Biology')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','biology','Biology')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="chemistry gcse sciences" onclick="sublibNotes('GCSE','chemistry','Chemistry')"><div class="sublib-card-name">Chemistry</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('GCSE','chemistry','Chemistry')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','chemistry','Chemistry')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="physics gcse sciences" onclick="sublibNotes('GCSE','physics','Physics')"><div class="sublib-card-name">Physics</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('GCSE','physics','Physics')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','physics','Physics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="combined science gcse sciences" onclick="sublibNotes('GCSE','combined-science','Combined Science')"><div class="sublib-card-name">Combined Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','combined-science','Combined Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="environmental science gcse sciences" onclick="sublibNotes('GCSE','env-science','Environmental Science')"><div class="sublib-card-name">Environmental Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','env-science','Environmental Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="astronomy gcse sciences" onclick="sublibNotes('GCSE','astronomy','Astronomy')"><div class="sublib-card-name">Astronomy</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','astronomy','Astronomy')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="marine science gcse sciences" onclick="sublibNotes('GCSE','marine-science','Marine Science')"><div class="sublib-card-name">Marine Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','marine-science','Marine Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="electronics gcse sciences" onclick="sublibNotes('GCSE','electronics','Electronics')"><div class="sublib-card-name">Electronics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','electronics','Electronics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="engineering gcse sciences" onclick="sublibNotes('GCSE','engineering','Engineering')"><div class="sublib-card-name">Engineering</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','engineering','Engineering')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📖</span><span class="sublib-cat-title">English</span><span class="sublib-cat-count">2</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="english language gcse english" onclick="sublibNotes('GCSE','eng-language','English Language')"><div class="sublib-card-name">English Language</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('GCSE','eng-language','English Language')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','eng-language','English Language')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="english literature gcse english" onclick="sublibNotes('GCSE','eng-literature','English Literature')"><div class="sublib-card-name">English Literature</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('GCSE','eng-literature','English Literature')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','eng-literature','English Literature')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌐</span><span class="sublib-cat-title">Languages</span><span class="sublib-cat-count">10</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="french gcse languages" onclick="sublibNotes('GCSE','french','French')"><div class="sublib-card-name">French</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','french','French')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="spanish gcse languages" onclick="sublibNotes('GCSE','spanish','Spanish')"><div class="sublib-card-name">Spanish</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','spanish','Spanish')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="german gcse languages" onclick="sublibNotes('GCSE','german','German')"><div class="sublib-card-name">German</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','german','German')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="chinese (mandarin) gcse languages" onclick="sublibNotes('GCSE','chinese','Chinese (Mandarin)')"><div class="sublib-card-name">Chinese (Mandarin)</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','chinese','Chinese (Mandarin)')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="arabic gcse languages" onclick="sublibNotes('GCSE','arabic','Arabic')"><div class="sublib-card-name">Arabic</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','arabic','Arabic')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="latin gcse languages" onclick="sublibNotes('GCSE','latin','Latin')"><div class="sublib-card-name">Latin</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','latin','Latin')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="japanese gcse languages" onclick="sublibNotes('GCSE','japanese','Japanese')"><div class="sublib-card-name">Japanese</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','japanese','Japanese')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="italian gcse languages" onclick="sublibNotes('GCSE','italian','Italian')"><div class="sublib-card-name">Italian</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','italian','Italian')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="russian gcse languages" onclick="sublibNotes('GCSE','russian','Russian')"><div class="sublib-card-name">Russian</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','russian','Russian')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="portuguese gcse languages" onclick="sublibNotes('GCSE','portuguese','Portuguese')"><div class="sublib-card-name">Portuguese</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','portuguese','Portuguese')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌍</span><span class="sublib-cat-title">Humanities & Social Sciences</span><span class="sublib-cat-count">12</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="history gcse humanities & social sciences" onclick="sublibNotes('GCSE','history','History')"><div class="sublib-card-name">History</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('GCSE','history','History')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','history','History')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="geography gcse humanities & social sciences" onclick="sublibNotes('GCSE','geography','Geography')"><div class="sublib-card-name">Geography</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('GCSE','geography','Geography')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','geography','Geography')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="economics gcse humanities & social sciences" onclick="sublibNotes('GCSE','economics','Economics')"><div class="sublib-card-name">Economics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','economics','Economics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="business studies gcse humanities & social sciences" onclick="sublibNotes('GCSE','business','Business Studies')"><div class="sublib-card-name">Business Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','business','Business Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="accounting gcse humanities & social sciences" onclick="sublibNotes('GCSE','accounting','Accounting')"><div class="sublib-card-name">Accounting</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','accounting','Accounting')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="psychology gcse humanities & social sciences" onclick="sublibNotes('GCSE','psychology','Psychology')"><div class="sublib-card-name">Psychology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','psychology','Psychology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="sociology gcse humanities & social sciences" onclick="sublibNotes('GCSE','sociology','Sociology')"><div class="sublib-card-name">Sociology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','sociology','Sociology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="global perspectives gcse humanities & social sciences" onclick="sublibNotes('GCSE','global-perspectives','Global Perspectives')"><div class="sublib-card-name">Global Perspectives</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','global-perspectives','Global Perspectives')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="religious studies gcse humanities & social sciences" onclick="sublibNotes('GCSE','religious-studies','Religious Studies')"><div class="sublib-card-name">Religious Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','religious-studies','Religious Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="philosophy gcse humanities & social sciences" onclick="sublibNotes('GCSE','philosophy','Philosophy')"><div class="sublib-card-name">Philosophy</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','philosophy','Philosophy')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="classical civilisation gcse humanities & social sciences" onclick="sublibNotes('GCSE','classical-civ','Classical Civilisation')"><div class="sublib-card-name">Classical Civilisation</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','classical-civ','Classical Civilisation')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="ancient history gcse humanities & social sciences" onclick="sublibNotes('GCSE','ancient-history','Ancient History')"><div class="sublib-card-name">Ancient History</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','ancient-history','Ancient History')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🎨</span><span class="sublib-cat-title">Creative & Arts</span><span class="sublib-cat-count">11</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="art & design gcse creative & arts" onclick="sublibNotes('GCSE','art-design','Art & Design')"><div class="sublib-card-name">Art & Design</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','art-design','Art & Design')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="fine art gcse creative & arts" onclick="sublibNotes('GCSE','fine-art','Fine Art')"><div class="sublib-card-name">Fine Art</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','fine-art','Fine Art')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="graphic design gcse creative & arts" onclick="sublibNotes('GCSE','graphic-design','Graphic Design')"><div class="sublib-card-name">Graphic Design</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','graphic-design','Graphic Design')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="photography gcse creative & arts" onclick="sublibNotes('GCSE','photography','Photography')"><div class="sublib-card-name">Photography</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','photography','Photography')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="music gcse creative & arts" onclick="sublibNotes('GCSE','music','Music')"><div class="sublib-card-name">Music</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','music','Music')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="drama gcse creative & arts" onclick="sublibNotes('GCSE','drama','Drama')"><div class="sublib-card-name">Drama</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','drama','Drama')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="dance gcse creative & arts" onclick="sublibNotes('GCSE','dance','Dance')"><div class="sublib-card-name">Dance</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','dance','Dance')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="film studies gcse creative & arts" onclick="sublibNotes('GCSE','film-studies','Film Studies')"><div class="sublib-card-name">Film Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','film-studies','Film Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="media studies gcse creative & arts" onclick="sublibNotes('GCSE','media-studies','Media Studies')"><div class="sublib-card-name">Media Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','media-studies','Media Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="textiles gcse creative & arts" onclick="sublibNotes('GCSE','textiles','Textiles')"><div class="sublib-card-name">Textiles</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','textiles','Textiles')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="product design gcse creative & arts" onclick="sublibNotes('GCSE','product-design','Product Design')"><div class="sublib-card-name">Product Design</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','product-design','Product Design')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">💻</span><span class="sublib-cat-title">Technology & Computing</span><span class="sublib-cat-count">4</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="computer science gcse technology & computing" onclick="sublibNotes('GCSE','cs','Computer Science')"><div class="sublib-card-name">Computer Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','cs','Computer Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="ict gcse technology & computing" onclick="sublibNotes('GCSE','ict','ICT')"><div class="sublib-card-name">ICT</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','ict','ICT')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="design & technology gcse technology & computing" onclick="sublibNotes('GCSE','d-and-t','Design & Technology')"><div class="sublib-card-name">Design & Technology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','d-and-t','Design & Technology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="digital media gcse technology & computing" onclick="sublibNotes('GCSE','digital-media','Digital Media')"><div class="sublib-card-name">Digital Media</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','digital-media','Digital Media')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🛠️</span><span class="sublib-cat-title">Applied & Practical</span><span class="sublib-cat-count">5</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="physical education gcse applied & practical" onclick="sublibNotes('GCSE','pe','Physical Education')"><div class="sublib-card-name">Physical Education</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','pe','Physical Education')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="food preparation & nutrition gcse applied & practical" onclick="sublibNotes('GCSE','food-nutrition','Food Preparation & Nutrition')"><div class="sublib-card-name">Food Preparation & Nutrition</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','food-nutrition','Food Preparation & Nutrition')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="travel & tourism gcse applied & practical" onclick="sublibNotes('GCSE','travel-tourism','Travel & Tourism')"><div class="sublib-card-name">Travel & Tourism</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','travel-tourism','Travel & Tourism')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="enterprise gcse applied & practical" onclick="sublibNotes('GCSE','enterprise','Enterprise')"><div class="sublib-card-name">Enterprise</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','enterprise','Enterprise')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="environmental management gcse applied & practical" onclick="sublibNotes('GCSE','env-management','Environmental Management')"><div class="sublib-card-name">Environmental Management</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('GCSE','env-management','Environmental Management')">📄 Papers</button></div></div>
</div></div>
</div>
<div class="sublib-section" id="sublib-sec-IGCSE">
<div class="sublib-curr-header" style="background:linear-gradient(135deg,rgba(26,58,107,0.1),rgba(26,58,107,0.03))"><div class="sublib-curr-icon">🌏</div><div><div class="sublib-curr-name">IGCSE</div><div class="sublib-curr-desc">International General Certificate of Secondary Education</div><span class="sublib-curr-badge" style="background:rgba(26,58,107,0.15);color:#1a3a6b">49 subjects</span></div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📐</span><span class="sublib-cat-title">Mathematics</span><span class="sublib-cat-count">4</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="mathematics igcse mathematics" onclick="sublibNotes('IGCSE','math','Mathematics')"><div class="sublib-card-name">Mathematics</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IGCSE','math','Mathematics')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','math','Mathematics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="additional mathematics igcse mathematics" onclick="sublibNotes('IGCSE','add-math','Additional Mathematics')"><div class="sublib-card-name">Additional Mathematics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','add-math','Additional Mathematics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="statistics igcse mathematics" onclick="sublibNotes('IGCSE','statistics','Statistics')"><div class="sublib-card-name">Statistics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','statistics','Statistics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="further pure mathematics igcse mathematics" onclick="sublibNotes('IGCSE','further-pure','Further Pure Mathematics')"><div class="sublib-card-name">Further Pure Mathematics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','further-pure','Further Pure Mathematics')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🔬</span><span class="sublib-cat-title">Sciences</span><span class="sublib-cat-count">8</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="biology igcse sciences" onclick="sublibNotes('IGCSE','biology','Biology')"><div class="sublib-card-name">Biology</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IGCSE','biology','Biology')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','biology','Biology')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="chemistry igcse sciences" onclick="sublibNotes('IGCSE','chemistry','Chemistry')"><div class="sublib-card-name">Chemistry</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IGCSE','chemistry','Chemistry')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','chemistry','Chemistry')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="physics igcse sciences" onclick="sublibNotes('IGCSE','physics','Physics')"><div class="sublib-card-name">Physics</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IGCSE','physics','Physics')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','physics','Physics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="combined science igcse sciences" onclick="sublibNotes('IGCSE','combined-science','Combined Science')"><div class="sublib-card-name">Combined Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','combined-science','Combined Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="environmental management igcse sciences" onclick="sublibNotes('IGCSE','env-management','Environmental Management')"><div class="sublib-card-name">Environmental Management</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','env-management','Environmental Management')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="astronomy igcse sciences" onclick="sublibNotes('IGCSE','astronomy','Astronomy')"><div class="sublib-card-name">Astronomy</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','astronomy','Astronomy')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="marine science igcse sciences" onclick="sublibNotes('IGCSE','marine-science','Marine Science')"><div class="sublib-card-name">Marine Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','marine-science','Marine Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="electronics igcse sciences" onclick="sublibNotes('IGCSE','electronics','Electronics')"><div class="sublib-card-name">Electronics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','electronics','Electronics')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📖</span><span class="sublib-cat-title">English</span><span class="sublib-cat-count">4</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="english language igcse english" onclick="sublibNotes('IGCSE','eng-language','English Language')"><div class="sublib-card-name">English Language</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','eng-language','English Language')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="english literature igcse english" onclick="sublibNotes('IGCSE','eng-literature','English Literature')"><div class="sublib-card-name">English Literature</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','eng-literature','English Literature')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="first language english igcse english" onclick="sublibNotes('IGCSE','first-lang-eng','First Language English')"><div class="sublib-card-name">First Language English</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','first-lang-eng','First Language English')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="second language english igcse english" onclick="sublibNotes('IGCSE','second-lang-eng','Second Language English')"><div class="sublib-card-name">Second Language English</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','second-lang-eng','Second Language English')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌐</span><span class="sublib-cat-title">Languages</span><span class="sublib-cat-count">11</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="french igcse languages" onclick="sublibNotes('IGCSE','french','French')"><div class="sublib-card-name">French</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','french','French')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="spanish igcse languages" onclick="sublibNotes('IGCSE','spanish','Spanish')"><div class="sublib-card-name">Spanish</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','spanish','Spanish')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="german igcse languages" onclick="sublibNotes('IGCSE','german','German')"><div class="sublib-card-name">German</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','german','German')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="chinese (mandarin) igcse languages" onclick="sublibNotes('IGCSE','chinese','Chinese (Mandarin)')"><div class="sublib-card-name">Chinese (Mandarin)</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','chinese','Chinese (Mandarin)')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="arabic igcse languages" onclick="sublibNotes('IGCSE','arabic','Arabic')"><div class="sublib-card-name">Arabic</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','arabic','Arabic')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="latin igcse languages" onclick="sublibNotes('IGCSE','latin','Latin')"><div class="sublib-card-name">Latin</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','latin','Latin')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="japanese igcse languages" onclick="sublibNotes('IGCSE','japanese','Japanese')"><div class="sublib-card-name">Japanese</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','japanese','Japanese')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="italian igcse languages" onclick="sublibNotes('IGCSE','italian','Italian')"><div class="sublib-card-name">Italian</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','italian','Italian')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="russian igcse languages" onclick="sublibNotes('IGCSE','russian','Russian')"><div class="sublib-card-name">Russian</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','russian','Russian')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="portuguese igcse languages" onclick="sublibNotes('IGCSE','portuguese','Portuguese')"><div class="sublib-card-name">Portuguese</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','portuguese','Portuguese')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="hindi igcse languages" onclick="sublibNotes('IGCSE','hindi','Hindi')"><div class="sublib-card-name">Hindi</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','hindi','Hindi')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌍</span><span class="sublib-cat-title">Humanities & Social Sciences</span><span class="sublib-cat-count">10</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="history igcse humanities & social sciences" onclick="sublibNotes('IGCSE','history','History')"><div class="sublib-card-name">History</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','history','History')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="geography igcse humanities & social sciences" onclick="sublibNotes('IGCSE','geography','Geography')"><div class="sublib-card-name">Geography</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','geography','Geography')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="economics igcse humanities & social sciences" onclick="sublibNotes('IGCSE','economics','Economics')"><div class="sublib-card-name">Economics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','economics','Economics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="business studies igcse humanities & social sciences" onclick="sublibNotes('IGCSE','business','Business Studies')"><div class="sublib-card-name">Business Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','business','Business Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="accounting igcse humanities & social sciences" onclick="sublibNotes('IGCSE','accounting','Accounting')"><div class="sublib-card-name">Accounting</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','accounting','Accounting')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="sociology igcse humanities & social sciences" onclick="sublibNotes('IGCSE','sociology','Sociology')"><div class="sublib-card-name">Sociology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','sociology','Sociology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="global perspectives igcse humanities & social sciences" onclick="sublibNotes('IGCSE','global-perspectives','Global Perspectives')"><div class="sublib-card-name">Global Perspectives</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','global-perspectives','Global Perspectives')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="religious studies igcse humanities & social sciences" onclick="sublibNotes('IGCSE','religious-studies','Religious Studies')"><div class="sublib-card-name">Religious Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','religious-studies','Religious Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="classical studies igcse humanities & social sciences" onclick="sublibNotes('IGCSE','classical-studies','Classical Studies')"><div class="sublib-card-name">Classical Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','classical-studies','Classical Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="travel & tourism igcse humanities & social sciences" onclick="sublibNotes('IGCSE','travel-tourism','Travel & Tourism')"><div class="sublib-card-name">Travel & Tourism</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','travel-tourism','Travel & Tourism')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🎨</span><span class="sublib-cat-title">Creative & Arts</span><span class="sublib-cat-count">6</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="art & design igcse creative & arts" onclick="sublibNotes('IGCSE','art-design','Art & Design')"><div class="sublib-card-name">Art & Design</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','art-design','Art & Design')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="music igcse creative & arts" onclick="sublibNotes('IGCSE','music','Music')"><div class="sublib-card-name">Music</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','music','Music')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="drama igcse creative & arts" onclick="sublibNotes('IGCSE','drama','Drama')"><div class="sublib-card-name">Drama</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','drama','Drama')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="media studies igcse creative & arts" onclick="sublibNotes('IGCSE','media-studies','Media Studies')"><div class="sublib-card-name">Media Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','media-studies','Media Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="textiles igcse creative & arts" onclick="sublibNotes('IGCSE','textiles','Textiles')"><div class="sublib-card-name">Textiles</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','textiles','Textiles')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="design & technology igcse creative & arts" onclick="sublibNotes('IGCSE','d-and-t','Design & Technology')"><div class="sublib-card-name">Design & Technology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','d-and-t','Design & Technology')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">💻</span><span class="sublib-cat-title">Technology & Computing</span><span class="sublib-cat-count">3</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="computer science igcse technology & computing" onclick="sublibNotes('IGCSE','cs','Computer Science')"><div class="sublib-card-name">Computer Science</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IGCSE','cs','Computer Science')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','cs','Computer Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="ict igcse technology & computing" onclick="sublibNotes('IGCSE','ict','ICT')"><div class="sublib-card-name">ICT</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','ict','ICT')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="engineering igcse technology & computing" onclick="sublibNotes('IGCSE','engineering','Engineering')"><div class="sublib-card-name">Engineering</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','engineering','Engineering')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🛠️</span><span class="sublib-cat-title">Applied & Practical</span><span class="sublib-cat-count">3</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="physical education igcse applied & practical" onclick="sublibNotes('IGCSE','pe','Physical Education')"><div class="sublib-card-name">Physical Education</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','pe','Physical Education')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="food & nutrition igcse applied & practical" onclick="sublibNotes('IGCSE','food-nutrition','Food & Nutrition')"><div class="sublib-card-name">Food & Nutrition</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','food-nutrition','Food & Nutrition')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="enterprise igcse applied & practical" onclick="sublibNotes('IGCSE','enterprise','Enterprise')"><div class="sublib-card-name">Enterprise</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IGCSE','enterprise','Enterprise')">📄 Papers</button></div></div>
</div></div>
</div>
<div class="sublib-section" id="sublib-sec-A-Level">
<div class="sublib-curr-header" style="background:linear-gradient(135deg,rgba(138,97,15,0.1),rgba(138,97,15,0.03))"><div class="sublib-curr-icon">🎓</div><div><div class="sublib-curr-name">A-Level</div><div class="sublib-curr-desc">Advanced Level — AQA, OCR, Edexcel, Cambridge</div><span class="sublib-curr-badge" style="background:rgba(138,97,15,0.15);color:#8a610f">63 subjects</span></div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📐</span><span class="sublib-cat-title">Mathematics</span><span class="sublib-cat-count">5</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="mathematics a-level mathematics" onclick="sublibNotes('A-Level','math','Mathematics')"><div class="sublib-card-name">Mathematics</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('A-Level','math','Mathematics')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','math','Mathematics')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="further mathematics a-level mathematics" onclick="sublibNotes('A-Level','further-math','Further Mathematics')"><div class="sublib-card-name">Further Mathematics</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('A-Level','further-math','Further Mathematics')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','further-math','Further Mathematics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="statistics a-level mathematics" onclick="sublibNotes('A-Level','statistics','Statistics')"><div class="sublib-card-name">Statistics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','statistics','Statistics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="pure mathematics a-level mathematics" onclick="sublibNotes('A-Level','pure-math','Pure Mathematics')"><div class="sublib-card-name">Pure Mathematics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','pure-math','Pure Mathematics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="mechanics a-level mathematics" onclick="sublibNotes('A-Level','mechanics','Mechanics')"><div class="sublib-card-name">Mechanics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','mechanics','Mechanics')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🔬</span><span class="sublib-cat-title">Sciences</span><span class="sublib-cat-count">8</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="biology a-level sciences" onclick="sublibNotes('A-Level','biology','Biology')"><div class="sublib-card-name">Biology</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('A-Level','biology','Biology')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','biology','Biology')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="chemistry a-level sciences" onclick="sublibNotes('A-Level','chemistry','Chemistry')"><div class="sublib-card-name">Chemistry</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('A-Level','chemistry','Chemistry')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','chemistry','Chemistry')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="physics a-level sciences" onclick="sublibNotes('A-Level','physics','Physics')"><div class="sublib-card-name">Physics</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('A-Level','physics','Physics')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','physics','Physics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="environmental science a-level sciences" onclick="sublibNotes('A-Level','env-science','Environmental Science')"><div class="sublib-card-name">Environmental Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','env-science','Environmental Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="geology a-level sciences" onclick="sublibNotes('A-Level','geology','Geology')"><div class="sublib-card-name">Geology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','geology','Geology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="astronomy a-level sciences" onclick="sublibNotes('A-Level','astronomy','Astronomy')"><div class="sublib-card-name">Astronomy</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','astronomy','Astronomy')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="marine science a-level sciences" onclick="sublibNotes('A-Level','marine-science','Marine Science')"><div class="sublib-card-name">Marine Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','marine-science','Marine Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="electronics a-level sciences" onclick="sublibNotes('A-Level','electronics','Electronics')"><div class="sublib-card-name">Electronics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','electronics','Electronics')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📖</span><span class="sublib-cat-title">English</span><span class="sublib-cat-count">3</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="english language a-level english" onclick="sublibNotes('A-Level','eng-language','English Language')"><div class="sublib-card-name">English Language</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','eng-language','English Language')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="english literature a-level english" onclick="sublibNotes('A-Level','eng-literature','English Literature')"><div class="sublib-card-name">English Literature</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','eng-literature','English Literature')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="english language & literature a-level english" onclick="sublibNotes('A-Level','eng-lang-lit','English Language & Literature')"><div class="sublib-card-name">English Language & Literature</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','eng-lang-lit','English Language & Literature')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌐</span><span class="sublib-cat-title">Languages</span><span class="sublib-cat-count">11</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="french a-level languages" onclick="sublibNotes('A-Level','french','French')"><div class="sublib-card-name">French</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','french','French')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="spanish a-level languages" onclick="sublibNotes('A-Level','spanish','Spanish')"><div class="sublib-card-name">Spanish</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','spanish','Spanish')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="german a-level languages" onclick="sublibNotes('A-Level','german','German')"><div class="sublib-card-name">German</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','german','German')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="chinese (mandarin) a-level languages" onclick="sublibNotes('A-Level','chinese','Chinese (Mandarin)')"><div class="sublib-card-name">Chinese (Mandarin)</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','chinese','Chinese (Mandarin)')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="arabic a-level languages" onclick="sublibNotes('A-Level','arabic','Arabic')"><div class="sublib-card-name">Arabic</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','arabic','Arabic')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="latin a-level languages" onclick="sublibNotes('A-Level','latin','Latin')"><div class="sublib-card-name">Latin</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','latin','Latin')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="ancient greek a-level languages" onclick="sublibNotes('A-Level','ancient-greek','Ancient Greek')"><div class="sublib-card-name">Ancient Greek</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','ancient-greek','Ancient Greek')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="japanese a-level languages" onclick="sublibNotes('A-Level','japanese','Japanese')"><div class="sublib-card-name">Japanese</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','japanese','Japanese')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="italian a-level languages" onclick="sublibNotes('A-Level','italian','Italian')"><div class="sublib-card-name">Italian</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','italian','Italian')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="russian a-level languages" onclick="sublibNotes('A-Level','russian','Russian')"><div class="sublib-card-name">Russian</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','russian','Russian')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="portuguese a-level languages" onclick="sublibNotes('A-Level','portuguese','Portuguese')"><div class="sublib-card-name">Portuguese</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','portuguese','Portuguese')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌍</span><span class="sublib-cat-title">Humanities & Social Sciences</span><span class="sublib-cat-count">14</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="history a-level humanities & social sciences" onclick="sublibNotes('A-Level','history','History')"><div class="sublib-card-name">History</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('A-Level','history','History')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','history','History')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="geography a-level humanities & social sciences" onclick="sublibNotes('A-Level','geography','Geography')"><div class="sublib-card-name">Geography</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','geography','Geography')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="economics a-level humanities & social sciences" onclick="sublibNotes('A-Level','economics','Economics')"><div class="sublib-card-name">Economics</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('A-Level','economics','Economics')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','economics','Economics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="business a-level humanities & social sciences" onclick="sublibNotes('A-Level','business','Business')"><div class="sublib-card-name">Business</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','business','Business')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="accounting a-level humanities & social sciences" onclick="sublibNotes('A-Level','accounting','Accounting')"><div class="sublib-card-name">Accounting</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','accounting','Accounting')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="psychology a-level humanities & social sciences" onclick="sublibNotes('A-Level','psychology','Psychology')"><div class="sublib-card-name">Psychology</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('A-Level','psychology','Psychology')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','psychology','Psychology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="sociology a-level humanities & social sciences" onclick="sublibNotes('A-Level','sociology','Sociology')"><div class="sublib-card-name">Sociology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','sociology','Sociology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="politics a-level humanities & social sciences" onclick="sublibNotes('A-Level','politics','Politics')"><div class="sublib-card-name">Politics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','politics','Politics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="law a-level humanities & social sciences" onclick="sublibNotes('A-Level','law','Law')"><div class="sublib-card-name">Law</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','law','Law')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="philosophy a-level humanities & social sciences" onclick="sublibNotes('A-Level','philosophy','Philosophy')"><div class="sublib-card-name">Philosophy</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','philosophy','Philosophy')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="religious studies a-level humanities & social sciences" onclick="sublibNotes('A-Level','religious-studies','Religious Studies')"><div class="sublib-card-name">Religious Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','religious-studies','Religious Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="classical civilisation a-level humanities & social sciences" onclick="sublibNotes('A-Level','classical-civ','Classical Civilisation')"><div class="sublib-card-name">Classical Civilisation</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','classical-civ','Classical Civilisation')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="ancient history a-level humanities & social sciences" onclick="sublibNotes('A-Level','ancient-history','Ancient History')"><div class="sublib-card-name">Ancient History</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','ancient-history','Ancient History')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="anthropology a-level humanities & social sciences" onclick="sublibNotes('A-Level','anthropology','Anthropology')"><div class="sublib-card-name">Anthropology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','anthropology','Anthropology')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🎨</span><span class="sublib-cat-title">Creative & Arts</span><span class="sublib-cat-count">12</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="art & design a-level creative & arts" onclick="sublibNotes('A-Level','art-design','Art & Design')"><div class="sublib-card-name">Art & Design</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','art-design','Art & Design')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="fine art a-level creative & arts" onclick="sublibNotes('A-Level','fine-art','Fine Art')"><div class="sublib-card-name">Fine Art</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','fine-art','Fine Art')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="graphic design a-level creative & arts" onclick="sublibNotes('A-Level','graphic-design','Graphic Design')"><div class="sublib-card-name">Graphic Design</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','graphic-design','Graphic Design')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="photography a-level creative & arts" onclick="sublibNotes('A-Level','photography','Photography')"><div class="sublib-card-name">Photography</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','photography','Photography')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="music a-level creative & arts" onclick="sublibNotes('A-Level','music','Music')"><div class="sublib-card-name">Music</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','music','Music')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="music technology a-level creative & arts" onclick="sublibNotes('A-Level','music-tech','Music Technology')"><div class="sublib-card-name">Music Technology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','music-tech','Music Technology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="drama & theatre studies a-level creative & arts" onclick="sublibNotes('A-Level','drama','Drama & Theatre Studies')"><div class="sublib-card-name">Drama & Theatre Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','drama','Drama & Theatre Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="dance a-level creative & arts" onclick="sublibNotes('A-Level','dance','Dance')"><div class="sublib-card-name">Dance</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','dance','Dance')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="film studies a-level creative & arts" onclick="sublibNotes('A-Level','film-studies','Film Studies')"><div class="sublib-card-name">Film Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','film-studies','Film Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="media studies a-level creative & arts" onclick="sublibNotes('A-Level','media-studies','Media Studies')"><div class="sublib-card-name">Media Studies</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','media-studies','Media Studies')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="textiles a-level creative & arts" onclick="sublibNotes('A-Level','textiles','Textiles')"><div class="sublib-card-name">Textiles</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','textiles','Textiles')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="product design a-level creative & arts" onclick="sublibNotes('A-Level','product-design','Product Design')"><div class="sublib-card-name">Product Design</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','product-design','Product Design')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">💻</span><span class="sublib-cat-title">Technology & Computing</span><span class="sublib-cat-count">5</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="computer science a-level technology & computing" onclick="sublibNotes('A-Level','cs','Computer Science')"><div class="sublib-card-name">Computer Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','cs','Computer Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="ict a-level technology & computing" onclick="sublibNotes('A-Level','ict','ICT')"><div class="sublib-card-name">ICT</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','ict','ICT')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="design & technology a-level technology & computing" onclick="sublibNotes('A-Level','d-and-t','Design & Technology')"><div class="sublib-card-name">Design & Technology</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','d-and-t','Design & Technology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="engineering a-level technology & computing" onclick="sublibNotes('A-Level','engineering','Engineering')"><div class="sublib-card-name">Engineering</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','engineering','Engineering')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="digital media a-level technology & computing" onclick="sublibNotes('A-Level','digital-media','Digital Media')"><div class="sublib-card-name">Digital Media</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','digital-media','Digital Media')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🛠️</span><span class="sublib-cat-title">Applied & Practical</span><span class="sublib-cat-count">5</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="physical education a-level applied & practical" onclick="sublibNotes('A-Level','pe','Physical Education')"><div class="sublib-card-name">Physical Education</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','pe','Physical Education')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="sports science a-level applied & practical" onclick="sublibNotes('A-Level','sports-science','Sports Science')"><div class="sublib-card-name">Sports Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','sports-science','Sports Science')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="food science & nutrition a-level applied & practical" onclick="sublibNotes('A-Level','food-nutrition','Food Science & Nutrition')"><div class="sublib-card-name">Food Science & Nutrition</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','food-nutrition','Food Science & Nutrition')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="hospitality & tourism a-level applied & practical" onclick="sublibNotes('A-Level','hospitality','Hospitality & Tourism')"><div class="sublib-card-name">Hospitality & Tourism</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','hospitality','Hospitality & Tourism')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="health & social care a-level applied & practical" onclick="sublibNotes('A-Level','health-social','Health & Social Care')"><div class="sublib-card-name">Health & Social Care</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('A-Level','health-social','Health & Social Care')">📄 Papers</button></div></div>
</div></div>
</div>
<div class="sublib-section" id="sublib-sec-IB">
<div class="sublib-curr-header" style="background:linear-gradient(135deg,rgba(90,15,138,0.1),rgba(90,15,138,0.03))"><div class="sublib-curr-icon">🌐</div><div><div class="sublib-curr-name">IB</div><div class="sublib-curr-desc">International Baccalaureate Diploma Programme</div><span class="sublib-curr-badge" style="background:rgba(90,15,138,0.15);color:#5a0f8a">47 subjects</span></div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📖</span><span class="sublib-cat-title">Group 1 — Studies in Language & Literature</span><span class="sublib-cat-count">3</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="language a: literature hl/sl ib group 1 — studies in language & literature" onclick="sublibNotes('IB','lang-a-lit','Language A: Literature HL/SL')"><div class="sublib-card-name">Language A: Literature HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','lang-a-lit','Language A: Literature HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language a: language & literature hl/sl ib group 1 — studies in language & literature" onclick="sublibNotes('IB','lang-a-lang-lit','Language A: Language & Literature HL/SL')"><div class="sublib-card-name">Language A: Language & Literature HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','lang-a-lang-lit','Language A: Language & Literature HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="literature & performance sl ib group 1 — studies in language & literature" onclick="sublibNotes('IB','lit-performance','Literature & Performance SL')"><div class="sublib-card-name">Literature & Performance SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','lit-performance','Literature & Performance SL')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌐</span><span class="sublib-cat-title">Group 2 — Language Acquisition</span><span class="sublib-cat-count">14</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="language b: french hl/sl ib group 2 — language acquisition" onclick="sublibNotes('IB','french','Language B: French HL/SL')"><div class="sublib-card-name">Language B: French HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','french','Language B: French HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language b: spanish hl/sl ib group 2 — language acquisition" onclick="sublibNotes('IB','spanish','Language B: Spanish HL/SL')"><div class="sublib-card-name">Language B: Spanish HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','spanish','Language B: Spanish HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language b: german hl/sl ib group 2 — language acquisition" onclick="sublibNotes('IB','german','Language B: German HL/SL')"><div class="sublib-card-name">Language B: German HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','german','Language B: German HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language b: chinese hl/sl ib group 2 — language acquisition" onclick="sublibNotes('IB','chinese','Language B: Chinese HL/SL')"><div class="sublib-card-name">Language B: Chinese HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','chinese','Language B: Chinese HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language b: arabic hl/sl ib group 2 — language acquisition" onclick="sublibNotes('IB','arabic','Language B: Arabic HL/SL')"><div class="sublib-card-name">Language B: Arabic HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','arabic','Language B: Arabic HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language b: japanese hl/sl ib group 2 — language acquisition" onclick="sublibNotes('IB','japanese','Language B: Japanese HL/SL')"><div class="sublib-card-name">Language B: Japanese HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','japanese','Language B: Japanese HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language b: russian hl/sl ib group 2 — language acquisition" onclick="sublibNotes('IB','russian','Language B: Russian HL/SL')"><div class="sublib-card-name">Language B: Russian HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','russian','Language B: Russian HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language b: italian hl/sl ib group 2 — language acquisition" onclick="sublibNotes('IB','italian','Language B: Italian HL/SL')"><div class="sublib-card-name">Language B: Italian HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','italian','Language B: Italian HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language b: latin hl/sl ib group 2 — language acquisition" onclick="sublibNotes('IB','latin','Language B: Latin HL/SL')"><div class="sublib-card-name">Language B: Latin HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','latin','Language B: Latin HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language ab initio: french ib group 2 — language acquisition" onclick="sublibNotes('IB','french-ab','Language Ab Initio: French')"><div class="sublib-card-name">Language Ab Initio: French</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','french-ab','Language Ab Initio: French')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language ab initio: spanish ib group 2 — language acquisition" onclick="sublibNotes('IB','spanish-ab','Language Ab Initio: Spanish')"><div class="sublib-card-name">Language Ab Initio: Spanish</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','spanish-ab','Language Ab Initio: Spanish')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language ab initio: german ib group 2 — language acquisition" onclick="sublibNotes('IB','german-ab','Language Ab Initio: German')"><div class="sublib-card-name">Language Ab Initio: German</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','german-ab','Language Ab Initio: German')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language ab initio: chinese ib group 2 — language acquisition" onclick="sublibNotes('IB','chinese-ab','Language Ab Initio: Chinese')"><div class="sublib-card-name">Language Ab Initio: Chinese</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','chinese-ab','Language Ab Initio: Chinese')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="language ab initio: japanese ib group 2 — language acquisition" onclick="sublibNotes('IB','japanese-ab','Language Ab Initio: Japanese')"><div class="sublib-card-name">Language Ab Initio: Japanese</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','japanese-ab','Language Ab Initio: Japanese')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌍</span><span class="sublib-cat-title">Group 3 — Individuals & Societies</span><span class="sublib-cat-count">10</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="history hl/sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','history','History HL/SL')"><div class="sublib-card-name">History HL/SL</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IB','history','History HL/SL')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','history','History HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="geography hl/sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','geography','Geography HL/SL')"><div class="sublib-card-name">Geography HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','geography','Geography HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="economics hl/sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','economics','Economics HL/SL')"><div class="sublib-card-name">Economics HL/SL</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IB','economics','Economics HL/SL')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','economics','Economics HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="business management hl/sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','business','Business Management HL/SL')"><div class="sublib-card-name">Business Management HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','business','Business Management HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="psychology hl/sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','psychology','Psychology HL/SL')"><div class="sublib-card-name">Psychology HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','psychology','Psychology HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="social & cultural anthropology hl/sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','anthropology','Social & Cultural Anthropology HL/SL')"><div class="sublib-card-name">Social & Cultural Anthropology HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','anthropology','Social & Cultural Anthropology HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="philosophy hl/sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','philosophy','Philosophy HL/SL')"><div class="sublib-card-name">Philosophy HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','philosophy','Philosophy HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="global politics hl/sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','global-politics','Global Politics HL/SL')"><div class="sublib-card-name">Global Politics HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','global-politics','Global Politics HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="environmental systems & societies sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','ess','Environmental Systems & Societies SL')"><div class="sublib-card-name">Environmental Systems & Societies SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','ess','Environmental Systems & Societies SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="information technology in a global society sl ib group 3 — individuals & societies" onclick="sublibNotes('IB','itgs','Information Technology in a Global Society SL')"><div class="sublib-card-name">Information Technology in a Global Society SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','itgs','Information Technology in a Global Society SL')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🔬</span><span class="sublib-cat-title">Group 4 — Sciences</span><span class="sublib-cat-count">7</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="biology hl/sl ib group 4 — sciences" onclick="sublibNotes('IB','biology','Biology HL/SL')"><div class="sublib-card-name">Biology HL/SL</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IB','biology','Biology HL/SL')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','biology','Biology HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="chemistry hl/sl ib group 4 — sciences" onclick="sublibNotes('IB','chemistry','Chemistry HL/SL')"><div class="sublib-card-name">Chemistry HL/SL</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IB','chemistry','Chemistry HL/SL')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','chemistry','Chemistry HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="physics hl/sl ib group 4 — sciences" onclick="sublibNotes('IB','physics','Physics HL/SL')"><div class="sublib-card-name">Physics HL/SL</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IB','physics','Physics HL/SL')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','physics','Physics HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="computer science hl/sl ib group 4 — sciences" onclick="sublibNotes('IB','cs','Computer Science HL/SL')"><div class="sublib-card-name">Computer Science HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','cs','Computer Science HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="design technology hl/sl ib group 4 — sciences" onclick="sublibNotes('IB','design-tech','Design Technology HL/SL')"><div class="sublib-card-name">Design Technology HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','design-tech','Design Technology HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="environmental systems & societies sl ib group 4 — sciences" onclick="sublibNotes('IB','ess','Environmental Systems & Societies SL')"><div class="sublib-card-name">Environmental Systems & Societies SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','ess','Environmental Systems & Societies SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="sports, exercise & health science hl/sl ib group 4 — sciences" onclick="sublibNotes('IB','sehs','Sports, Exercise & Health Science HL/SL')"><div class="sublib-card-name">Sports, Exercise & Health Science HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','sehs','Sports, Exercise & Health Science HL/SL')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📐</span><span class="sublib-cat-title">Group 5 — Mathematics</span><span class="sublib-cat-count">4</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="mathematics: analysis & approaches hl ib group 5 — mathematics" onclick="sublibNotes('IB','math-aa-hl','Mathematics: Analysis & Approaches HL')"><div class="sublib-card-name">Mathematics: Analysis & Approaches HL</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IB','math-aa-hl','Mathematics: Analysis & Approaches HL')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','math-aa-hl','Mathematics: Analysis & Approaches HL')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="mathematics: analysis & approaches sl ib group 5 — mathematics" onclick="sublibNotes('IB','math-aa-sl','Mathematics: Analysis & Approaches SL')"><div class="sublib-card-name">Mathematics: Analysis & Approaches SL</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IB','math-aa-sl','Mathematics: Analysis & Approaches SL')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','math-aa-sl','Mathematics: Analysis & Approaches SL')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="mathematics: applications & interpretation hl ib group 5 — mathematics" onclick="sublibNotes('IB','math-ai-hl','Mathematics: Applications & Interpretation HL')"><div class="sublib-card-name">Mathematics: Applications & Interpretation HL</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IB','math-ai-hl','Mathematics: Applications & Interpretation HL')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','math-ai-hl','Mathematics: Applications & Interpretation HL')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="mathematics: applications & interpretation sl ib group 5 — mathematics" onclick="sublibNotes('IB','math-ai-sl','Mathematics: Applications & Interpretation SL')"><div class="sublib-card-name">Mathematics: Applications & Interpretation SL</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('IB','math-ai-sl','Mathematics: Applications & Interpretation SL')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','math-ai-sl','Mathematics: Applications & Interpretation SL')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🎨</span><span class="sublib-cat-title">Group 6 — The Arts</span><span class="sublib-cat-count">5</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="visual arts hl/sl ib group 6 — the arts" onclick="sublibNotes('IB','visual-arts','Visual Arts HL/SL')"><div class="sublib-card-name">Visual Arts HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','visual-arts','Visual Arts HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="music hl/sl ib group 6 — the arts" onclick="sublibNotes('IB','music','Music HL/SL')"><div class="sublib-card-name">Music HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','music','Music HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="theatre hl/sl ib group 6 — the arts" onclick="sublibNotes('IB','theatre','Theatre HL/SL')"><div class="sublib-card-name">Theatre HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','theatre','Theatre HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="dance hl/sl ib group 6 — the arts" onclick="sublibNotes('IB','dance','Dance HL/SL')"><div class="sublib-card-name">Dance HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','dance','Dance HL/SL')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="film hl/sl ib group 6 — the arts" onclick="sublibNotes('IB','film','Film HL/SL')"><div class="sublib-card-name">Film HL/SL</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','film','Film HL/SL')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">⭐</span><span class="sublib-cat-title">IB Core Components</span><span class="sublib-cat-count">4</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="theory of knowledge (tok) ib ib core components" onclick="sublibNotes('IB','tok','Theory of Knowledge (TOK)')"><div class="sublib-card-name">Theory of Knowledge (TOK)</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','tok','Theory of Knowledge (TOK)')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="extended essay (ee) ib ib core components" onclick="sublibNotes('IB','ee','Extended Essay (EE)')"><div class="sublib-card-name">Extended Essay (EE)</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','ee','Extended Essay (EE)')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="creativity, activity, service (cas) ib ib core components" onclick="sublibNotes('IB','cas','Creativity, Activity, Service (CAS)')"><div class="sublib-card-name">Creativity, Activity, Service (CAS)</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','cas','Creativity, Activity, Service (CAS)')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="internal assessment (ia) guide ib ib core components" onclick="sublibNotes('IB','ia-guide','Internal Assessment (IA) Guide')"><div class="sublib-card-name">Internal Assessment (IA) Guide</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('IB','ia-guide','Internal Assessment (IA) Guide')">📄 Papers</button></div></div>
</div></div>
</div>
<div class="sublib-section" id="sublib-sec-AP">
<div class="sublib-curr-header" style="background:linear-gradient(135deg,rgba(139,26,26,0.1),rgba(139,26,26,0.03))"><div class="sublib-curr-icon">🇺🇸</div><div><div class="sublib-curr-name">AP</div><div class="sublib-curr-desc">Advanced Placement — College Board</div><span class="sublib-curr-badge" style="background:rgba(139,26,26,0.15);color:#8b1a1a">39 subjects</span></div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📐</span><span class="sublib-cat-title">Mathematics & Computing</span><span class="sublib-cat-count">6</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="calculus ab ap mathematics & computing" onclick="sublibNotes('AP','calc-ab','Calculus AB')"><div class="sublib-card-name">Calculus AB</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('AP','calc-ab','Calculus AB')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','calc-ab','Calculus AB')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="calculus bc ap mathematics & computing" onclick="sublibNotes('AP','calc-bc','Calculus BC')"><div class="sublib-card-name">Calculus BC</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('AP','calc-bc','Calculus BC')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','calc-bc','Calculus BC')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="statistics ap mathematics & computing" onclick="sublibNotes('AP','statistics','Statistics')"><div class="sublib-card-name">Statistics</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('AP','statistics','Statistics')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','statistics','Statistics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="computer science a ap mathematics & computing" onclick="sublibNotes('AP','cs-a','Computer Science A')"><div class="sublib-card-name">Computer Science A</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','cs-a','Computer Science A')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="computer science principles ap mathematics & computing" onclick="sublibNotes('AP','cs-principles','Computer Science Principles')"><div class="sublib-card-name">Computer Science Principles</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','cs-principles','Computer Science Principles')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="precalculus ap mathematics & computing" onclick="sublibNotes('AP','precalc','Precalculus')"><div class="sublib-card-name">Precalculus</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','precalc','Precalculus')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🔬</span><span class="sublib-cat-title">Sciences</span><span class="sublib-cat-count">7</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="biology ap sciences" onclick="sublibNotes('AP','biology','Biology')"><div class="sublib-card-name">Biology</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('AP','biology','Biology')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','biology','Biology')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="chemistry ap sciences" onclick="sublibNotes('AP','chemistry','Chemistry')"><div class="sublib-card-name">Chemistry</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('AP','chemistry','Chemistry')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','chemistry','Chemistry')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="physics 1: algebra-based ap sciences" onclick="sublibNotes('AP','physics-1','Physics 1: Algebra-Based')"><div class="sublib-card-name">Physics 1: Algebra-Based</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','physics-1','Physics 1: Algebra-Based')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="physics 2: algebra-based ap sciences" onclick="sublibNotes('AP','physics-2','Physics 2: Algebra-Based')"><div class="sublib-card-name">Physics 2: Algebra-Based</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','physics-2','Physics 2: Algebra-Based')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="physics c: mechanics ap sciences" onclick="sublibNotes('AP','physics-c-mech','Physics C: Mechanics')"><div class="sublib-card-name">Physics C: Mechanics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','physics-c-mech','Physics C: Mechanics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="physics c: electricity & magnetism ap sciences" onclick="sublibNotes('AP','physics-c-em','Physics C: Electricity & Magnetism')"><div class="sublib-card-name">Physics C: Electricity & Magnetism</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','physics-c-em','Physics C: Electricity & Magnetism')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="environmental science ap sciences" onclick="sublibNotes('AP','env-science','Environmental Science')"><div class="sublib-card-name">Environmental Science</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','env-science','Environmental Science')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌍</span><span class="sublib-cat-title">History & Social Studies</span><span class="sublib-cat-count">11</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="world history: modern ap history & social studies" onclick="sublibNotes('AP','world-history','World History: Modern')"><div class="sublib-card-name">World History: Modern</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('AP','world-history','World History: Modern')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','world-history','World History: Modern')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="european history ap history & social studies" onclick="sublibNotes('AP','euro-history','European History')"><div class="sublib-card-name">European History</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','euro-history','European History')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="united states history (apush) ap history & social studies" onclick="sublibNotes('AP','us-history','United States History (APUSH)')"><div class="sublib-card-name">United States History (APUSH)</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('AP','us-history','United States History (APUSH)')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','us-history','United States History (APUSH)')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="comparative government & politics ap history & social studies" onclick="sublibNotes('AP','comp-gov','Comparative Government & Politics')"><div class="sublib-card-name">Comparative Government & Politics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','comp-gov','Comparative Government & Politics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="united states government & politics ap history & social studies" onclick="sublibNotes('AP','us-gov','United States Government & Politics')"><div class="sublib-card-name">United States Government & Politics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','us-gov','United States Government & Politics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="human geography ap history & social studies" onclick="sublibNotes('AP','human-geo','Human Geography')"><div class="sublib-card-name">Human Geography</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','human-geo','Human Geography')">📄 Papers</button></div></div>
<div class="sublib-card live" data-s="psychology ap history & social studies" onclick="sublibNotes('AP','psychology','Psychology')"><div class="sublib-card-name">Psychology</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('AP','psychology','Psychology')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','psychology','Psychology')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="macroeconomics ap history & social studies" onclick="sublibNotes('AP','macro','Macroeconomics')"><div class="sublib-card-name">Macroeconomics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','macro','Macroeconomics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="microeconomics ap history & social studies" onclick="sublibNotes('AP','micro','Microeconomics')"><div class="sublib-card-name">Microeconomics</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','micro','Microeconomics')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="seminar ap history & social studies" onclick="sublibNotes('AP','seminar','Seminar')"><div class="sublib-card-name">Seminar</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','seminar','Seminar')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="research ap history & social studies" onclick="sublibNotes('AP','research','Research')"><div class="sublib-card-name">Research</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','research','Research')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">📖</span><span class="sublib-cat-title">English</span><span class="sublib-cat-count">2</span></div>
<div class="sublib-grid">
<div class="sublib-card live" data-s="english language & composition ap english" onclick="sublibNotes('AP','eng-lang','English Language & Composition')"><div class="sublib-card-name">English Language & Composition</div><div class="sublib-card-btns"><button class="sbc sbc-notes" onclick="event.stopPropagation();sublibNotes('AP','eng-lang','English Language & Composition')">📖 Notes</button><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','eng-lang','English Language & Composition')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="english literature & composition ap english" onclick="sublibNotes('AP','eng-lit','English Literature & Composition')"><div class="sublib-card-name">English Literature & Composition</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','eng-lit','English Literature & Composition')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🌐</span><span class="sublib-cat-title">Languages</span><span class="sublib-cat-count">8</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="spanish language & culture ap languages" onclick="sublibNotes('AP','spanish','Spanish Language & Culture')"><div class="sublib-card-name">Spanish Language & Culture</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','spanish','Spanish Language & Culture')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="spanish literature & culture ap languages" onclick="sublibNotes('AP','spanish-lit','Spanish Literature & Culture')"><div class="sublib-card-name">Spanish Literature & Culture</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','spanish-lit','Spanish Literature & Culture')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="french language & culture ap languages" onclick="sublibNotes('AP','french','French Language & Culture')"><div class="sublib-card-name">French Language & Culture</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','french','French Language & Culture')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="german language & culture ap languages" onclick="sublibNotes('AP','german','German Language & Culture')"><div class="sublib-card-name">German Language & Culture</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','german','German Language & Culture')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="chinese language & culture ap languages" onclick="sublibNotes('AP','chinese','Chinese Language & Culture')"><div class="sublib-card-name">Chinese Language & Culture</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','chinese','Chinese Language & Culture')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="japanese language & culture ap languages" onclick="sublibNotes('AP','japanese','Japanese Language & Culture')"><div class="sublib-card-name">Japanese Language & Culture</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','japanese','Japanese Language & Culture')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="italian language & culture ap languages" onclick="sublibNotes('AP','italian','Italian Language & Culture')"><div class="sublib-card-name">Italian Language & Culture</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','italian','Italian Language & Culture')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="latin ap languages" onclick="sublibNotes('AP','latin','Latin')"><div class="sublib-card-name">Latin</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','latin','Latin')">📄 Papers</button></div></div>
</div></div>
<div class="sublib-cat">
<div class="sublib-cat-hdr"><span class="sublib-cat-icon">🎨</span><span class="sublib-cat-title">Arts</span><span class="sublib-cat-count">5</span></div>
<div class="sublib-grid">
<div class="sublib-card" data-s="studio art: 2-d design ap arts" onclick="sublibNotes('AP','art-2d','Studio Art: 2-D Design')"><div class="sublib-card-name">Studio Art: 2-D Design</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','art-2d','Studio Art: 2-D Design')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="studio art: 3-d design ap arts" onclick="sublibNotes('AP','art-3d','Studio Art: 3-D Design')"><div class="sublib-card-name">Studio Art: 3-D Design</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','art-3d','Studio Art: 3-D Design')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="studio art: drawing ap arts" onclick="sublibNotes('AP','art-drawing','Studio Art: Drawing')"><div class="sublib-card-name">Studio Art: Drawing</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','art-drawing','Studio Art: Drawing')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="art history ap arts" onclick="sublibNotes('AP','art-history','Art History')"><div class="sublib-card-name">Art History</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','art-history','Art History')">📄 Papers</button></div></div>
<div class="sublib-card" data-s="music theory ap arts" onclick="sublibNotes('AP','music-theory','Music Theory')"><div class="sublib-card-name">Music Theory</div><div class="sublib-card-btns"><span class="sbc sbc-soon">📖 Soon</span><button class="sbc sbc-papers" onclick="event.stopPropagation();sublibPapers('AP','music-theory','Music Theory')">📄 Papers</button></div></div>
</div></div>
</div>

  </div>
</div>
<!-- ============================================================ -->
<!-- LUMEN ADMIN PORTAL — PRIVATE ACCESS ONLY                     -->
<!-- ============================================================ -->

<!-- Admin login overlay -->
<div id="admin-login-overlay" style="display:none;position:fixed;inset:0;z-index:99999;background:rgba(13,15,14,0.97);backdrop-filter:blur(16px);align-items:center;justify-content:center;flex-direction:column;">
  <div style="width:100%;max-width:400px;padding:0 24px;">
    <!-- Logo -->
    <div style="display:flex;align-items:center;gap:10px;justify-content:center;margin-bottom:36px;">
      <svg width="28" height="28" viewBox="0 0 32 32" fill="none"><circle cx="16" cy="16" r="10" stroke="#c8922a" stroke-width="1.5" fill="none" opacity="0.5"/><line x1="16" y1="2" x2="16" y2="7" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><line x1="16" y1="25" x2="16" y2="30" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><line x1="2" y1="16" x2="7" y2="16" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><line x1="25" y1="16" x2="30" y2="16" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><circle cx="16" cy="16" r="4" fill="#c8922a" opacity="0.8"/></svg>
      <span style="font-family:'Syne',sans-serif;font-weight:800;font-size:22px;color:#f7f5f0;letter-spacing:-0.5px;">Lumen</span>
    </div>

    <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:16px;padding:32px;">
      <div style="font-family:'Syne',sans-serif;font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;text-align:center;">Admin Portal</div>
      <div style="font-family:'JetBrains Mono',monospace;font-size:10px;color:rgba(247,245,240,0.3);text-align:center;letter-spacing:0.08em;margin-bottom:28px;text-transform:uppercase;">Private access only</div>

      <div id="admin-login-err" style="display:none;background:rgba(224,88,88,0.12);border:1px solid rgba(224,88,88,0.25);border-radius:6px;padding:10px 14px;font-size:12px;color:#e05858;font-family:'Syne',sans-serif;margin-bottom:16px;text-align:center;">Incorrect credentials. Please try again.</div>

      <div style="margin-bottom:14px;">
        <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:6px;font-family:'JetBrains Mono',monospace;letter-spacing:0.07em;text-transform:uppercase;">Admin username</div>
        <input id="admin-user-input" type="text" placeholder="Enter username" autocomplete="off"
          style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.15);border-radius:6px;padding:11px 14px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:14px;outline:none;transition:border-color 0.2s;"
          onfocus="this.style.borderColor='rgba(200,146,42,0.5)'" onblur="this.style.borderColor='rgba(247,245,240,0.15)'"
          onkeydown="if(event.key==='Enter')adminLogin()" />
      </div>
      <div style="margin-bottom:24px;">
        <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:6px;font-family:'JetBrains Mono',monospace;letter-spacing:0.07em;text-transform:uppercase;">Password</div>
        <input id="admin-pass-input" type="password" placeholder="Enter password" autocomplete="off"
          style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.15);border-radius:6px;padding:11px 14px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:14px;outline:none;transition:border-color 0.2s;"
          onfocus="this.style.borderColor='rgba(200,146,42,0.5)'" onblur="this.style.borderColor='rgba(247,245,240,0.15)'"
          onkeydown="if(event.key==='Enter')adminLogin()" />
      </div>
      <button onclick="adminLogin()" style="width:100%;font-family:'Syne',sans-serif;font-size:14px;font-weight:700;background:var(--gold);color:#f7f5f0;border:none;padding:13px;border-radius:6px;cursor:pointer;letter-spacing:0.02em;transition:all 0.2s;" onmouseover="this.style.background='#8a610f'" onmouseout="this.style.background='var(--gold)'">Access admin panel →</button>
    </div>

    <button onclick="adminPortalClose()" style="display:block;margin:16px auto 0;font-family:'Syne',sans-serif;font-size:12px;background:transparent;color:rgba(247,245,240,0.25);border:none;cursor:pointer;padding:8px;">← Return to site</button>
  </div>
</div>

<!-- Admin Portal Full Screen -->
<div id="admin-portal" style="display:none;position:fixed;inset:0;z-index:99998;background:#111413;font-family:'Syne',sans-serif;overflow:hidden;flex-direction:column;">

  <!-- Admin Topbar -->
  <div style="height:52px;background:#0d0f0e;border-bottom:1px solid rgba(247,245,240,0.08);display:flex;align-items:center;justify-content:space-between;padding:0 20px;flex-shrink:0;">
    <div style="display:flex;align-items:center;gap:12px;">
      <svg width="20" height="20" viewBox="0 0 32 32" fill="none"><circle cx="16" cy="16" r="10" stroke="#c8922a" stroke-width="1.5" fill="none" opacity="0.5"/><line x1="16" y1="2" x2="16" y2="7" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><line x1="25" y1="16" x2="30" y2="16" stroke="#c8922a" stroke-width="1.5" stroke-linecap="round"/><circle cx="16" cy="16" r="4" fill="#c8922a" opacity="0.8"/></svg>
      <span style="font-family:'Syne',sans-serif;font-weight:800;font-size:15px;color:#f7f5f0;">Lumen Admin</span>
      <span style="font-family:'JetBrains Mono',monospace;font-size:9px;background:rgba(200,146,42,0.15);color:#c8922a;border:1px solid rgba(200,146,42,0.25);padding:2px 8px;border-radius:3px;letter-spacing:0.06em;">PRIVATE</span>
    </div>
    <div style="display:flex;align-items:center;gap:12px;">
      <div style="font-family:'JetBrains Mono',monospace;font-size:10px;color:rgba(247,245,240,0.35);" id="admin-session-info">Logged in as admin</div>
      <div id="admin-save-indicator" style="font-family:'JetBrains Mono',monospace;font-size:10px;color:rgba(91,206,138,0.7);display:none;">✓ Saved</div>
      <button onclick="adminLogout()" style="font-family:'Syne',sans-serif;font-size:11px;font-weight:600;background:rgba(224,88,88,0.1);color:#e05858;border:1px solid rgba(224,88,88,0.2);padding:5px 14px;border-radius:4px;cursor:pointer;">Log out</button>
    </div>
  </div>

  <!-- Admin Layout -->
  <div style="display:flex;flex:1;overflow:hidden;">

    <!-- Admin Sidebar -->
    <div style="width:200px;background:#0d0f0e;border-right:1px solid rgba(247,245,240,0.07);padding:16px 0;display:flex;flex-direction:column;gap:2px;flex-shrink:0;">
      <div style="font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.25);letter-spacing:0.1em;text-transform:uppercase;padding:0 16px 10px;">Content</div>
      <div class="adm-nav active" data-panel="adm-overview" onclick="admSwitch(this)">📊 Overview</div>
      <div class="adm-nav" data-panel="adm-text" onclick="admSwitch(this)">✏ Edit Text</div>
      <div class="adm-nav" data-panel="adm-notes" onclick="admSwitch(this)">📖 Revision Notes</div>
      <div class="adm-nav" data-panel="adm-videos" onclick="admSwitch(this)">🎬 Videos</div>
      <div class="adm-nav" data-panel="adm-docs" onclick="admSwitch(this)">📄 Documents</div>
      <div class="adm-nav" data-panel="adm-code" onclick="admSwitch(this)">⌨ Code Editor</div>
      <div style="height:1px;background:rgba(247,245,240,0.07);margin:12px 0;"></div>
      <div style="font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.25);letter-spacing:0.1em;text-transform:uppercase;padding:0 16px 10px;">Settings</div>
      <div class="adm-nav" data-panel="adm-pricing" onclick="admSwitch(this)">💰 Pricing</div>
      <div class="adm-nav" data-panel="adm-branding" onclick="admSwitch(this)">🎨 Branding</div>
      <div class="adm-nav" data-panel="adm-security" onclick="admSwitch(this)">🔑 Security</div>
    </div>

    <!-- Admin Main Content -->
    <div style="flex:1;overflow-y:auto;padding:24px;" id="admin-main">

      <!-- OVERVIEW -->
      <div class="adm-panel active" id="adm-overview">
        <div style="font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;">Admin Overview</div>
        <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:24px;font-family:'JetBrains Mono',monospace;">All content edits are stored in your browser. Export HTML to deploy changes.</div>
        <div style="display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:24px;">
          <div style="background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:8px;padding:16px;"><div style="font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.35);letter-spacing:0.07em;text-transform:uppercase;margin-bottom:8px;">Text blocks</div><div style="font-size:24px;font-weight:800;color:#f7f5f0;">12</div></div>
          <div style="background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:8px;padding:16px;"><div style="font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.35);letter-spacing:0.07em;text-transform:uppercase;margin-bottom:8px;">Videos</div><div style="font-size:24px;font-weight:800;color:#c8922a;" id="adm-video-count">0</div></div>
          <div style="background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:8px;padding:16px;"><div style="font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.35);letter-spacing:0.07em;text-transform:uppercase;margin-bottom:8px;">Documents</div><div style="font-size:24px;font-weight:800;color:#5ba8e8;" id="adm-doc-count">0</div></div>
          <div style="background:rgba(247,245,240,0.05);border:1px solid rgba(247,245,240,0.1);border-radius:8px;padding:16px;"><div style="font-family:'JetBrains Mono',monospace;font-size:9px;color:rgba(247,245,240,0.35);letter-spacing:0.07em;text-transform:uppercase;margin-bottom:8px;">Notes edits</div><div style="font-size:24px;font-weight:800;color:#5bce8a;" id="adm-notes-count">0</div></div>
        </div>
        <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;padding:18px;margin-bottom:16px;">
          <div style="font-size:13px;font-weight:700;color:#f7f5f0;margin-bottom:12px;">Quick actions</div>
          <div style="display:flex;gap:10px;flex-wrap:wrap;">
            <button onclick="admSwitch(document.querySelector('[data-panel=adm-text]'))" style="font-size:12px;font-weight:600;background:rgba(200,146,42,0.12);color:#c8922a;border:1px solid rgba(200,146,42,0.25);padding:8px 16px;border-radius:5px;cursor:pointer;">✏ Edit site text</button>
            <button onclick="admSwitch(document.querySelector('[data-panel=adm-videos]'))" style="font-size:12px;font-weight:600;background:rgba(91,168,232,0.1);color:#5ba8e8;border:1px solid rgba(91,168,232,0.2);padding:8px 16px;border-radius:5px;cursor:pointer;">🎬 Add a video</button>
            <button onclick="admSwitch(document.querySelector('[data-panel=adm-docs]'))" style="font-size:12px;font-weight:600;background:rgba(91,206,138,0.1);color:#5bce8a;border:1px solid rgba(91,206,138,0.2);padding:8px 16px;border-radius:5px;cursor:pointer;">📄 Upload document</button>
            <button onclick="admSwitch(document.querySelector('[data-panel=adm-code]'))" style="font-size:12px;font-weight:600;background:rgba(247,245,240,0.07);color:rgba(247,245,240,0.6);border:1px solid rgba(247,245,240,0.15);padding:8px 16px;border-radius:5px;cursor:pointer;">⌨ Edit code</button>
            <button onclick="admExportHTML()" style="font-size:12px;font-weight:700;background:var(--gold);color:#f7f5f0;border:none;padding:8px 18px;border-radius:5px;cursor:pointer;">⬇ Export HTML</button>
          </div>
        </div>
        <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;padding:18px;">
          <div style="font-size:13px;font-weight:700;color:#f7f5f0;margin-bottom:10px;">Recent activity</div>
          <div id="adm-activity-log" style="display:flex;flex-direction:column;gap:6px;font-size:12px;color:rgba(247,245,240,0.45);font-family:'JetBrains Mono',monospace;">
            <div>— No changes made yet this session.</div>
          </div>
        </div>
      </div>

      <!-- TEXT EDITOR -->
      <div class="adm-panel" id="adm-text">
        <div style="font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;">Edit Site Text</div>
        <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:20px;font-family:'JetBrains Mono',monospace;">Edit any text block visible on the main site. Changes preview live.</div>
        <div style="display:flex;flex-direction:column;gap:10px;" id="adm-text-blocks"></div>
      </div>

      <!-- REVISION NOTES EDITOR -->
      <div class="adm-panel" id="adm-notes">
        <div style="font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;">Revision Notes Manager</div>
        <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:20px;font-family:'JetBrains Mono',monospace;">Add, edit, or remove revision note topics. Content is saved to localStorage.</div>
        <button onclick="admNotesAdd()" style="font-size:12px;font-weight:700;background:rgba(200,146,42,0.15);color:#c8922a;border:1px solid rgba(200,146,42,0.3);padding:8px 18px;border-radius:5px;cursor:pointer;margin-bottom:16px;">+ Add new topic</button>
        <div id="adm-notes-list" style="display:flex;flex-direction:column;gap:8px;"></div>
      </div>

      <!-- VIDEO MANAGER -->
      <div class="adm-panel" id="adm-videos">
        <div style="font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;">Video Manager</div>
        <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:20px;font-family:'JetBrains Mono',monospace;">Add YouTube videos by URL or ID. Assign to subjects and topics.</div>

        <!-- Add Video Form -->
        <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;padding:18px;margin-bottom:20px;">
          <div style="font-size:13px;font-weight:700;color:#f7f5f0;margin-bottom:14px;">Add new video</div>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:10px;">
            <div>
              <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Title</div>
              <input id="vid-title" placeholder="e.g. Le Chatelier's Principle explained" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;" />
            </div>
            <div>
              <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">YouTube URL or ID</div>
              <input id="vid-url" placeholder="e.g. https://youtube.com/watch?v=... or dQw4w9WgXcQ" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;" />
            </div>
            <div>
              <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Subject</div>
              <select id="vid-subject" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                <option>Biology</option><option>Chemistry</option><option>Physics</option><option>Mathematics</option><option>Economics</option><option>History</option><option>Psychology</option><option>Geography</option><option>English</option><option>Other</option>
              </select>
            </div>
            <div>
              <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Topic / Tag</div>
              <input id="vid-topic" placeholder="e.g. Equilibria, Organic Mechanisms..." style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;" />
            </div>
          </div>
          <button onclick="admVideoAdd()" style="font-size:12px;font-weight:700;background:rgba(200,146,42,0.15);color:#c8922a;border:1px solid rgba(200,146,42,0.3);padding:8px 20px;border-radius:5px;cursor:pointer;">Add video →</button>
        </div>

        <!-- Video Library -->
        <div style="font-size:13px;font-weight:700;color:#f7f5f0;margin-bottom:12px;">Video library <span id="vid-count-label" style="font-family:'JetBrains Mono',monospace;font-size:11px;color:rgba(247,245,240,0.3);font-weight:400;"></span></div>
        <div id="adm-video-library" style="display:grid;grid-template-columns:1fr 1fr;gap:10px;"></div>
        <div id="adm-video-empty" style="font-size:13px;color:rgba(247,245,240,0.3);font-family:'JetBrains Mono',monospace;padding:20px 0;">No videos added yet.</div>
      </div>

      <!-- DOCUMENT MANAGER -->
      <div class="adm-panel" id="adm-docs">
        <div style="font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;">Document Manager</div>
        <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:20px;font-family:'JetBrains Mono',monospace;">Link PDFs, mark schemes, and revision resources. Files are linked by URL or path.</div>

        <!-- Add Document Form -->
        <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;padding:18px;margin-bottom:20px;">
          <div style="font-size:13px;font-weight:700;color:#f7f5f0;margin-bottom:14px;">Add new document</div>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:10px;">
            <div>
              <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Document title</div>
              <input id="doc-title" placeholder="e.g. A-Level Chemistry Notes 2025" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;" />
            </div>
            <div>
              <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">File URL or filename</div>
              <input id="doc-url" placeholder="e.g. alevel_chemistry_v4.pdf or https://..." style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;" />
            </div>
            <div>
              <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Curriculum</div>
              <select id="doc-curriculum" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                <option>A-Level</option><option>GCSE</option><option>IB</option><option>AP</option><option>IGCSE</option><option>All</option>
              </select>
            </div>
            <div>
              <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Type</div>
              <select id="doc-type" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;cursor:pointer;">
                <option value="notes">Revision Notes</option><option value="markscheme">Mark Scheme</option><option value="paper">Past Paper</option><option value="resource">Resource</option>
              </select>
            </div>
          </div>
          <div style="margin-bottom:10px;">
            <div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Description (optional)</div>
            <input id="doc-desc" placeholder="Brief description shown to students..." style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;" />
          </div>
          <button onclick="admDocAdd()" style="font-size:12px;font-weight:700;background:rgba(91,206,138,0.12);color:#5bce8a;border:1px solid rgba(91,206,138,0.2);padding:8px 20px;border-radius:5px;cursor:pointer;">Add document →</button>
        </div>

        <div style="font-size:13px;font-weight:700;color:#f7f5f0;margin-bottom:12px;">Document library <span id="doc-count-label" style="font-family:'JetBrains Mono',monospace;font-size:11px;color:rgba(247,245,240,0.3);font-weight:400;"></span></div>
        <div id="adm-doc-library" style="display:flex;flex-direction:column;gap:8px;"></div>
        <div id="adm-doc-empty" style="font-size:13px;color:rgba(247,245,240,0.3);font-family:'JetBrains Mono',monospace;padding:20px 0;">No documents added yet.</div>
      </div>

      <!-- CODE EDITOR -->
      <div class="adm-panel" id="adm-code">
        <div style="font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;">Live Code Editor</div>
        <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:20px;font-family:'JetBrains Mono',monospace;">Edit CSS, HTML blocks, or JavaScript. Use carefully — changes affect the live site.</div>

        <div style="display:flex;gap:10px;margin-bottom:14px;flex-wrap:wrap;">
          <button onclick="admCodeLoad('css')" class="adm-code-tab active" id="codetab-css" style="font-size:11px;font-weight:700;padding:7px 16px;border-radius:5px;cursor:pointer;background:rgba(200,146,42,0.15);color:#c8922a;border:1px solid rgba(200,146,42,0.3);">CSS Variables</button>
          <button onclick="admCodeLoad('hero')" class="adm-code-tab" id="codetab-hero" style="font-size:11px;font-weight:700;padding:7px 16px;border-radius:5px;cursor:pointer;background:rgba(247,245,240,0.06);color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.12);">Hero Section</button>
          <button onclick="admCodeLoad('nav')" class="adm-code-tab" id="codetab-nav" style="font-size:11px;font-weight:700;padding:7px 16px;border-radius:5px;cursor:pointer;background:rgba(247,245,240,0.06);color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.12);">Navigation</button>
          <button onclick="admCodeLoad('custom')" class="adm-code-tab" id="codetab-custom" style="font-size:11px;font-weight:700;padding:7px 16px;border-radius:5px;cursor:pointer;background:rgba(247,245,240,0.06);color:rgba(247,245,240,0.5);border:1px solid rgba(247,245,240,0.12);">Custom CSS/JS</button>
        </div>

        <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;overflow:hidden;margin-bottom:12px;">
          <div style="display:flex;align-items:center;justify-content:space-between;padding:8px 14px;background:rgba(247,245,240,0.03);border-bottom:1px solid rgba(247,245,240,0.08);">
            <span id="adm-code-label" style="font-family:'JetBrains Mono',monospace;font-size:10px;color:rgba(247,245,240,0.4);letter-spacing:0.06em;">CSS Variables</span>
            <div style="display:flex;gap:6px;">
              <button onclick="admCodeApply()" style="font-size:11px;font-weight:700;background:rgba(200,146,42,0.15);color:#c8922a;border:1px solid rgba(200,146,42,0.3);padding:4px 12px;border-radius:4px;cursor:pointer;">Apply →</button>
              <button onclick="admCodeReset()" style="font-size:11px;background:rgba(224,88,88,0.1);color:#e05858;border:1px solid rgba(224,88,88,0.2);padding:4px 10px;border-radius:4px;cursor:pointer;">Reset</button>
            </div>
          </div>
          <textarea id="adm-code-editor" spellcheck="false" style="width:100%;min-height:340px;background:transparent;border:none;padding:16px;color:rgba(247,245,240,0.85);font-family:'JetBrains Mono',monospace;font-size:12px;line-height:1.7;resize:vertical;outline:none;tab-size:2;"></textarea>
        </div>
        <div id="adm-code-feedback" style="font-family:'JetBrains Mono',monospace;font-size:11px;color:rgba(91,206,138,0.7);display:none;padding:4px 0;">✓ Changes applied to the live page.</div>
        <div style="background:rgba(224,88,88,0.07);border:1px solid rgba(224,88,88,0.18);border-radius:8px;padding:12px 16px;margin-top:12px;">
          <div style="font-size:11px;font-weight:700;color:#e05858;margin-bottom:4px;">⚠ Warning</div>
          <div style="font-size:11px;color:rgba(247,245,240,0.45);line-height:1.6;">CSS/JS changes apply immediately. Incorrect syntax may break the page layout. Use the Reset button to restore defaults. Export the HTML after testing to save your changes permanently.</div>
        </div>
      </div>

      <!-- PRICING EDITOR -->
      <div class="adm-panel" id="adm-pricing">
        <div style="font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;">Pricing Settings</div>
        <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:20px;font-family:'JetBrains Mono',monospace;">Update subscription pricing and plan descriptions.</div>
        <div style="display:flex;flex-direction:column;gap:12px;">
          <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;padding:18px;">
            <div style="font-size:13px;font-weight:700;color:#f7f5f0;margin-bottom:14px;">Annual plan</div>
            <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;">
              <div><div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Price (€)</div><input id="price-annual" value="98" type="number" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:14px;font-weight:700;outline:none;" /></div>
              <div><div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Trial length (days)</div><input id="price-trial" value="14" type="number" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:14px;font-weight:700;outline:none;" /></div>
            </div>
            <button onclick="admPricingApply()" style="margin-top:12px;font-size:12px;font-weight:700;background:var(--gold);color:#f7f5f0;border:none;padding:8px 20px;border-radius:5px;cursor:pointer;">Apply pricing →</button>
          </div>
        </div>
      </div>

      <!-- BRANDING -->
      <div class="adm-panel" id="adm-branding">
        <div style="font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;">Branding</div>
        <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:20px;font-family:'JetBrains Mono',monospace;">Adjust colours, site name, and tagline.</div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:12px;">
          <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;padding:16px;">
            <div style="font-size:12px;font-weight:700;color:#f7f5f0;margin-bottom:12px;">Colour palette</div>
            <div style="display:flex;flex-direction:column;gap:10px;">
              <div style="display:flex;align-items:center;justify-content:space-between;"><span style="font-size:12px;color:rgba(247,245,240,0.65);">Gold accent</span><input type="color" value="#c8922a" onchange="admColorChange('--gold',this.value)" style="width:36px;height:28px;border:none;background:none;cursor:pointer;border-radius:4px;" /></div>
              <div style="display:flex;align-items:center;justify-content:space-between;"><span style="font-size:12px;color:rgba(247,245,240,0.65);">Background</span><input type="color" value="#f7f5f0" onchange="admColorChange('--paper',this.value)" style="width:36px;height:28px;border:none;background:none;cursor:pointer;border-radius:4px;" /></div>
              <div style="display:flex;align-items:center;justify-content:space-between;"><span style="font-size:12px;color:rgba(247,245,240,0.65);">Ink (text)</span><input type="color" value="#0d0f0e" onchange="admColorChange('--ink',this.value)" style="width:36px;height:28px;border:none;background:none;cursor:pointer;border-radius:4px;" /></div>
            </div>
          </div>
          <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;padding:16px;">
            <div style="font-size:12px;font-weight:700;color:#f7f5f0;margin-bottom:12px;">Site identity</div>
            <div style="margin-bottom:10px;"><div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Site name</div><input id="brand-name" value="Lumen" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:13px;font-weight:700;outline:none;" /></div>
            <div><div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Hero tagline</div><input id="brand-tagline" value="The AI Exam Coach" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:12px;outline:none;" /></div>
            <button onclick="admBrandingApply()" style="margin-top:12px;font-size:12px;font-weight:700;background:var(--gold);color:#f7f5f0;border:none;padding:8px 18px;border-radius:5px;cursor:pointer;">Apply →</button>
          </div>
        </div>
      </div>

      <!-- SECURITY -->
      <div class="adm-panel" id="adm-security">
        <div style="font-size:18px;font-weight:800;color:#f7f5f0;margin-bottom:4px;">Security Settings</div>
        <div style="font-size:12px;color:rgba(247,245,240,0.4);margin-bottom:20px;font-family:'JetBrains Mono',monospace;">Change your admin credentials. These are stored locally in this file.</div>
        <div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;padding:20px;max-width:440px;">
          <div style="font-size:13px;font-weight:700;color:#f7f5f0;margin-bottom:16px;">Change admin credentials</div>
          <div style="margin-bottom:12px;"><div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">New username</div><input id="sec-newuser" placeholder="Enter new username" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:9px 12px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:13px;outline:none;" /></div>
          <div style="margin-bottom:12px;"><div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">New password</div><input id="sec-newpass" type="password" placeholder="Enter new password" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:9px 12px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:13px;outline:none;" /></div>
          <div style="margin-bottom:20px;"><div style="font-size:10px;color:rgba(247,245,240,0.4);margin-bottom:5px;font-family:'JetBrains Mono',monospace;letter-spacing:0.06em;text-transform:uppercase;">Confirm new password</div><input id="sec-confpass" type="password" placeholder="Repeat new password" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:9px 12px;color:#f7f5f0;font-family:'Syne',sans-serif;font-size:13px;outline:none;" /></div>
          <div id="sec-feedback" style="display:none;font-size:12px;padding:8px 12px;border-radius:5px;margin-bottom:12px;"></div>
          <button onclick="admSecuritySave()" style="font-size:13px;font-weight:700;background:var(--gold);color:#f7f5f0;border:none;padding:10px 24px;border-radius:5px;cursor:pointer;">Save credentials →</button>
        </div>
        <div style="background:rgba(200,146,42,0.07);border:1px solid rgba(200,146,42,0.2);border-radius:8px;padding:14px 16px;margin-top:16px;max-width:440px;">
          <div style="font-size:12px;font-weight:700;color:#c8922a;margin-bottom:4px;">Important</div>
          <div style="font-size:11px;color:rgba(247,245,240,0.5);line-height:1.6;">Credentials are stored in this HTML file via localStorage. After changing them, export the HTML file to preserve the new login. Share the exported file only with trusted admins.</div>
        </div>
      </div>

    </div>
  </div>
</div>

<style>
  .adm-nav {
    display: flex; align-items: center; gap: 8px;
    padding: 9px 16px; font-family: 'Syne', sans-serif; font-size: 12px; font-weight: 500;
    color: rgba(247,245,240,0.45); cursor: pointer; transition: all 0.15s;
    border-left: 2px solid transparent;
  }
  .adm-nav:hover { color: rgba(247,245,240,0.75); background: rgba(247,245,240,0.04); }
  .adm-nav.active { color: #f7f5f0; background: rgba(247,245,240,0.06); border-left-color: #c8922a; }
  .adm-panel { display: none; }
  .adm-panel.active { display: block; }
  #admin-login-overlay.open { display: flex !important; }
  #admin-portal.open { display: flex !important; }
  .adm-text-row { background: rgba(247,245,240,0.04); border: 1px solid rgba(247,245,240,0.1); border-radius: 8px; padding: 14px 16px; }
  .adm-text-label { font-family: 'JetBrains Mono', monospace; font-size: 10px; color: rgba(247,245,240,0.4); letter-spacing: 0.07em; text-transform: uppercase; margin-bottom: 6px; }
  .adm-text-input { width: 100%; background: rgba(247,245,240,0.07); border: 1px solid rgba(247,245,240,0.14); border-radius: 5px; padding: 8px 10px; color: #f7f5f0; font-family: 'Syne', sans-serif; font-size: 12px; outline: none; resize: vertical; }
  .adm-text-input:focus { border-color: rgba(200,146,42,0.4); }
</style>

<script>
// ===== ADMIN CREDENTIALS (change via Security panel) =====
let ADMIN_CREDS = JSON.parse(localStorage.getItem('lumen_admin_creds') || 'null') || { user: 'lumenadmin', pass: 'Lumen@2025!' };

// ===== ADMIN PORTAL OPEN/CLOSE =====
function adminPortalOpen() {
  document.getElementById('admin-login-overlay').classList.add('open');
  document.getElementById('admin-user-input').focus();
}
function adminPortalClose() {
  document.getElementById('admin-login-overlay').classList.remove('open');
  document.getElementById('admin-user-input').value = '';
  document.getElementById('admin-pass-input').value = '';
  document.getElementById('admin-login-err').style.display = 'none';
}
function adminLogin() {
  const u = document.getElementById('admin-user-input').value.trim();
  const p = document.getElementById('admin-pass-input').value;
  if (u === ADMIN_CREDS.user && p === ADMIN_CREDS.pass) {
    document.getElementById('admin-login-overlay').classList.remove('open');
    document.getElementById('admin-portal').classList.add('open');
    document.getElementById('admin-session-info').textContent = 'Logged in as ' + u + ' · ' + new Date().toLocaleTimeString();
    admInit();
  } else {
    document.getElementById('admin-login-err').style.display = 'block';
    document.getElementById('admin-pass-input').value = '';
    document.getElementById('admin-pass-input').focus();
  }
}
function adminLogout() {
  document.getElementById('admin-portal').classList.remove('open');
}

// ===== ADMIN PANEL SWITCHER =====
function admSwitch(el) {
  document.querySelectorAll('.adm-nav').forEach(n => n.classList.remove('active'));
  document.querySelectorAll('.adm-panel').forEach(p => p.classList.remove('active'));
  el.classList.add('active');
  const panel = document.getElementById(el.dataset.panel);
  if (panel) panel.classList.add('active');
}

// ===== ACTIVITY LOG =====
const admLog = [];
function admActivity(msg) {
  const time = new Date().toLocaleTimeString();
  admLog.unshift('[' + time + '] ' + msg);
  const el = document.getElementById('adm-activity-log');
  if (el) el.innerHTML = admLog.slice(0,8).map(l => '<div>'+l+'</div>').join('');
}

// ===== ADMIN INIT =====
function admInit() {
  admBuildTextBlocks();
  admRenderVideos();
  admRenderDocs();
  admRenderNotes();
  admCodeLoad('css');
  // Set counts
  const vids = JSON.parse(localStorage.getItem('lumen_videos') || '[]');
  const docs = JSON.parse(localStorage.getItem('lumen_docs') || '[]');
  const notesEdits = JSON.parse(localStorage.getItem('lumen_admin_notes') || '[]');
  document.getElementById('adm-video-count').textContent = vids.length;
  document.getElementById('adm-doc-count').textContent = docs.length;
  document.getElementById('adm-notes-count').textContent = notesEdits.length;
}

// ===== TEXT EDITOR =====
const TEXT_BLOCKS = [
  { id:'tb-hero-h1', label:'Hero headline', selector:'.hero h1', type:'html', defaultVal:'Stop revising.<br>Start <em>training</em><br>for your exam.' },
  { id:'tb-hero-sub', label:'Hero subheading', selector:'.hero-sub', type:'text', defaultVal:'Lumen is the intelligent revision system built for GCSE, A-level, IB, and AP students who demand measurable grade improvement — not another content library.' },
  { id:'tb-hero-tag', label:'Hero announcement tag', selector:'.hero-tag', type:'text', defaultVal:'AI-Powered Exam Coach — Now Live' },
  { id:'tb-problem-title', label:'Problem section title', selector:'.problem-section .section-title', type:'html', defaultVal:"Other platforms teach you to <em>read</em>. We train you to <em>perform</em>." },
  { id:'tb-features-body', label:'Features section description', selector:'.features-section .section-body', type:'text', defaultVal:'Lumen is not a content platform. It is an adaptive training system that models how examiners think and forces you to think the same way — under pressure, at speed.' },
  { id:'tb-cta-title', label:'CTA section title', selector:'.cta-title', type:'html', defaultVal:"Your exam date is not moving. <em>Neither should you.</em>" },
  { id:'tb-cta-sub', label:'CTA subtext', selector:'.cta-sub', type:'text', defaultVal:'Join thousands of students who stopped wasting revision time and started training with purpose. 14 days free. No card required.' },
  { id:'tb-footer-tagline', label:'Footer tagline', selector:'.footer-tagline', type:'text', defaultVal:'The intelligent exam coach for GCSE, IGCSE, A-level, IB, and AP students worldwide. Built to guarantee measurable grade improvement.' },
  { id:'tb-pricing-annual-desc', label:'Annual plan description', selector:'.pricing-card.recommended .pricing-desc', type:'text', defaultVal:'Full unlimited access to every feature. The complete Lumen experience.' },
];
function admBuildTextBlocks() {
  const el = document.getElementById('adm-text-blocks');
  if (!el) return;
  const saved = JSON.parse(localStorage.getItem('lumen_text_edits') || '{}');
  el.innerHTML = TEXT_BLOCKS.map(b => {
    const live = document.querySelector(b.selector);
    const current = saved[b.id] || (live ? (b.type==='html' ? live.innerHTML : live.textContent) : b.defaultVal);
    const isTextarea = current.length > 80;
    return '<div class="adm-text-row">'
      +'<div class="adm-text-label">'+b.label+'</div>'
      +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:9px;color:rgba(247,245,240,0.2);margin-bottom:6px;">'+b.selector+'</div>'
      +(isTextarea
        ? '<textarea class="adm-text-input" id="'+b.id+'" rows="3">'+current+'</textarea>'
        : '<input class="adm-text-input" id="'+b.id+'" value="'+current.replace(/"/g,'&quot;').replace(/<[^>]+>/g,'').trim()+'" />'
      )
      +'<button onclick="admTextApply(\''+b.id+'\',\''+b.selector+'\',\''+b.type+'\')" style="margin-top:8px;font-size:11px;font-weight:700;background:rgba(200,146,42,0.12);color:#c8922a;border:1px solid rgba(200,146,42,0.25);padding:5px 14px;border-radius:4px;cursor:pointer;">Apply →</button>'
      +'</div>';
  }).join('');
}
function admTextApply(id, selector, type) {
  const val = document.getElementById(id).value;
  const targets = document.querySelectorAll(selector);
  targets.forEach(el => { if (type === 'html') el.innerHTML = val; else el.textContent = val; });
  const saved = JSON.parse(localStorage.getItem('lumen_text_edits') || '{}');
  saved[id] = val;
  localStorage.setItem('lumen_text_edits', JSON.stringify(saved));
  admActivity('Text updated: ' + selector);
  admShowSaved();
}

// ===== VIDEO MANAGER =====
let admVideos = JSON.parse(localStorage.getItem('lumen_videos') || '[]');
function admVideoAdd() {
  const title = document.getElementById('vid-title').value.trim();
  const url = document.getElementById('vid-url').value.trim();
  const subject = document.getElementById('vid-subject').value;
  const topic = document.getElementById('vid-topic').value.trim();
  if (!title || !url) { alert('Please enter a title and YouTube URL/ID.'); return; }
  let id = url;
  const match = url.match(/(?:v=|youtu\.be\/|embed\/)([a-zA-Z0-9_-]{11})/);
  if (match) id = match[1];
  else if (url.length === 11) id = url;
  admVideos.push({ title, id, subject, topic, added: new Date().toLocaleDateString() });
  localStorage.setItem('lumen_videos', JSON.stringify(admVideos));
  document.getElementById('vid-title').value = '';
  document.getElementById('vid-url').value = '';
  document.getElementById('vid-topic').value = '';
  document.getElementById('adm-video-count').textContent = admVideos.length;
  admRenderVideos();
  admActivity('Video added: ' + title);
  admShowSaved();
}
function admRenderVideos() {
  const lib = document.getElementById('adm-video-library');
  const empty = document.getElementById('adm-video-empty');
  const count = document.getElementById('vid-count-label');
  if (!lib) return;
  if (count) count.textContent = '(' + admVideos.length + ' total)';
  if (admVideos.length === 0) { lib.innerHTML = ''; empty.style.display = 'block'; return; }
  empty.style.display = 'none';
  lib.innerHTML = admVideos.map((v,i) =>
    '<div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:8px;overflow:hidden;">'
    +'<div style="position:relative;padding-top:56.25%;background:#000;">'
    +'<iframe src="https://www.youtube.com/embed/'+v.id+'" frameborder="0" allow="accelerometer;autoplay;clipboard-write;encrypted-media;gyroscope;picture-in-picture" allowfullscreen style="position:absolute;inset:0;width:100%;height:100%;"></iframe>'
    +'</div>'
    +'<div style="padding:10px 12px;">'
    +'<div style="font-family:\'Syne\',sans-serif;font-size:12px;font-weight:700;color:#f7f5f0;margin-bottom:3px;">'+v.title+'</div>'
    +'<div style="display:flex;align-items:center;justify-content:space-between;">'
    +'<div style="font-family:\'JetBrains Mono\',monospace;font-size:10px;color:rgba(247,245,240,0.35);">'+v.subject+(v.topic?' · '+v.topic:'')+' · Added '+v.added+'</div>'
    +'<button onclick="admVideoDelete('+i+')" style="font-size:10px;background:rgba(224,88,88,0.1);color:#e05858;border:1px solid rgba(224,88,88,0.2);padding:3px 8px;border-radius:3px;cursor:pointer;">Delete</button>'
    +'</div></div></div>'
  ).join('');
}
function admVideoDelete(i) {
  if (!confirm('Remove this video?')) return;
  admVideos.splice(i, 1);
  localStorage.setItem('lumen_videos', JSON.stringify(admVideos));
  document.getElementById('adm-video-count').textContent = admVideos.length;
  admRenderVideos();
  admActivity('Video removed');
}

// ===== DOCUMENT MANAGER =====
let admDocs = JSON.parse(localStorage.getItem('lumen_docs') || '[]');
function admDocAdd() {
  const title = document.getElementById('doc-title').value.trim();
  const url = document.getElementById('doc-url').value.trim();
  const curriculum = document.getElementById('doc-curriculum').value;
  const type = document.getElementById('doc-type').value;
  const desc = document.getElementById('doc-desc').value.trim();
  if (!title || !url) { alert('Please enter a title and file URL.'); return; }
  admDocs.push({ title, url, curriculum, type, desc, added: new Date().toLocaleDateString() });
  localStorage.setItem('lumen_docs', JSON.stringify(admDocs));
  document.getElementById('doc-title').value = '';
  document.getElementById('doc-url').value = '';
  document.getElementById('doc-desc').value = '';
  document.getElementById('adm-doc-count').textContent = admDocs.length;
  admRenderDocs();
  admActivity('Document added: ' + title);
  admShowSaved();
}
function admRenderDocs() {
  const lib = document.getElementById('adm-doc-library');
  const empty = document.getElementById('adm-doc-empty');
  const count = document.getElementById('doc-count-label');
  if (!lib) return;
  if (count) count.textContent = '(' + admDocs.length + ' total)';
  if (admDocs.length === 0) { lib.innerHTML = ''; empty.style.display = 'block'; return; }
  empty.style.display = 'none';
  const typeColors = { notes:'#5bce8a', markscheme:'#5ba8e8', paper:'var(--gold)', resource:'rgba(247,245,240,0.5)' };
  lib.innerHTML = admDocs.map((d,i) =>
    '<div style="display:flex;align-items:center;justify-content:space-between;padding:12px 14px;background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:8px;">'
    +'<div style="display:flex;align-items:center;gap:10px;">'
    +'<div style="font-size:18px;">📄</div>'
    +'<div>'
    +'<div style="font-family:\'Syne\',sans-serif;font-size:12px;font-weight:700;color:#f7f5f0;">'+d.title+'</div>'
    +'<div style="display:flex;align-items:center;gap:8px;margin-top:3px;">'
    +'<span style="font-family:\'JetBrains Mono\',monospace;font-size:9px;letter-spacing:0.06em;text-transform:uppercase;background:rgba(247,245,240,0.07);color:rgba(247,245,240,0.4);padding:2px 6px;border-radius:3px;">'+d.curriculum+'</span>'
    +'<span style="font-family:\'JetBrains Mono\',monospace;font-size:9px;letter-spacing:0.06em;text-transform:uppercase;color:'+(typeColors[d.type]||'rgba(247,245,240,0.4)')+';">'+d.type+'</span>'
    +(d.desc ? '<span style="font-size:11px;color:rgba(247,245,240,0.35);">'+d.desc+'</span>' : '')
    +'</div></div></div>'
    +'<div style="display:flex;align-items:center;gap:8px;">'
    +'<a href="'+d.url+'" target="_blank" style="font-size:11px;font-weight:600;background:rgba(91,168,232,0.1);color:#5ba8e8;border:1px solid rgba(91,168,232,0.2);padding:5px 10px;border-radius:4px;text-decoration:none;">Open ↗</a>'
    +'<button onclick="admDocDelete('+i+')" style="font-size:11px;background:rgba(224,88,88,0.1);color:#e05858;border:1px solid rgba(224,88,88,0.2);padding:5px 10px;border-radius:4px;cursor:pointer;">Delete</button>'
    +'</div></div>'
  ).join('');
}
function admDocDelete(i) {
  if (!confirm('Remove this document?')) return;
  admDocs.splice(i, 1);
  localStorage.setItem('lumen_docs', JSON.stringify(admDocs));
  document.getElementById('adm-doc-count').textContent = admDocs.length;
  admRenderDocs();
  admActivity('Document removed');
}

// ===== NOTES MANAGER =====
let admAdminNotes = JSON.parse(localStorage.getItem('lumen_admin_notes') || '[]');
function admNotesAdd() {
  admAdminNotes.push({ id:'anote_'+Date.now(), subject:'', topic:'', content:'', added: new Date().toLocaleDateString() });
  localStorage.setItem('lumen_admin_notes', JSON.stringify(admAdminNotes));
  document.getElementById('adm-notes-count').textContent = admAdminNotes.length;
  admRenderNotes();
}
function admRenderNotes() {
  const el = document.getElementById('adm-notes-list');
  if (!el) return;
  if (admAdminNotes.length === 0) { el.innerHTML = '<div style="font-family:\'JetBrains Mono\',monospace;font-size:12px;color:rgba(247,245,240,0.3);padding:12px 0;">No custom notes topics yet. Click "+ Add new topic" to begin.</div>'; return; }
  el.innerHTML = admAdminNotes.map((n,i) =>
    '<div style="background:rgba(247,245,240,0.04);border:1px solid rgba(247,245,240,0.1);border-radius:10px;padding:14px 16px;">'
    +'<div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:8px;">'
    +'<input placeholder="Subject (e.g. Chemistry)" value="'+n.subject+'" oninput="admNoteUpdate('+i+',\'subject\',this.value)" style="background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:7px 10px;color:#f7f5f0;font-family:\'Syne\',sans-serif;font-size:12px;outline:none;" />'
    +'<input placeholder="Topic (e.g. Organic Mechanisms)" value="'+n.topic+'" oninput="admNoteUpdate('+i+',\'topic\',this.value)" style="background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:7px 10px;color:#f7f5f0;font-family:\'Syne\',sans-serif;font-size:12px;outline:none;" />'
    +'</div>'
    +'<textarea placeholder="Write the full revision note content here..." rows="5" oninput="admNoteUpdate('+i+',\'content\',this.value)" style="width:100%;background:rgba(247,245,240,0.07);border:1px solid rgba(247,245,240,0.14);border-radius:5px;padding:8px 10px;color:#f7f5f0;font-family:\'Literata\',serif;font-size:13px;line-height:1.6;resize:vertical;outline:none;margin-bottom:8px;">'+n.content+'</textarea>'
    +'<div style="display:flex;justify-content:flex-end;gap:8px;">'
    +'<button onclick="admNoteSave('+i+')" style="font-size:11px;font-weight:700;background:rgba(91,206,138,0.12);color:#5bce8a;border:1px solid rgba(91,206,138,0.2);padding:5px 12px;border-radius:4px;cursor:pointer;">Save note</button>'
    +'<button onclick="admNoteDelete('+i+')" style="font-size:11px;background:rgba(224,88,88,0.1);color:#e05858;border:1px solid rgba(224,88,88,0.2);padding:5px 12px;border-radius:4px;cursor:pointer;">Delete</button>'
    +'</div></div>'
  ).join('');
}
function admNoteUpdate(i, field, val) { admAdminNotes[i][field] = val; }
function admNoteSave(i) {
  localStorage.setItem('lumen_admin_notes', JSON.stringify(admAdminNotes));
  document.getElementById('adm-notes-count').textContent = admAdminNotes.length;
  admActivity('Note saved: ' + (admAdminNotes[i].topic || 'untitled'));
  admShowSaved();
}
function admNoteDelete(i) {
  if (!confirm('Delete this note?')) return;
  admAdminNotes.splice(i, 1);
  localStorage.setItem('lumen_admin_notes', JSON.stringify(admAdminNotes));
  document.getElementById('adm-notes-count').textContent = admAdminNotes.length;
  admRenderNotes();
}

// ===== CODE EDITOR =====
const CODE_SNIPPETS = {
  css: ':root {\n  --gold: #c8922a;\n  --gold-light: #f5e9d0;\n  --gold-dark: #8a610f;\n  --ink: #0d0f0e;\n  --ink-2: #2a2d2b;\n  --ink-3: #5a5f5c;\n  --paper: #f7f5f0;\n  --paper-2: #eeeae2;\n  --paper-3: #e4dfd4;\n  --emerald: #1a6644;\n  --radius: 4px;\n  --radius-lg: 8px;\n  --radius-xl: 16px;\n}',
  hero: '/* Edit hero section text in "Edit Text" tab.\nTo override hero layout styles, add CSS here: */\n\n.hero {\n  /* min-height: 100vh; */\n  /* padding: 120px 48px 80px; */\n}\n\n.hero h1 {\n  /* font-size: clamp(44px, 7vw, 92px); */\n  /* letter-spacing: -2px; */\n}',
  nav: 'nav {\n  /* height: 64px; */\n  /* background: rgba(247,245,240,0.94); */\n}\n\n.nav-logo {\n  /* font-size: 22px; */\n}\n\n.nav-cta {\n  /* background: var(--ink); */\n  /* color: var(--paper); */\n}',
  custom: '/* Add your custom CSS and JS here.\nThis block is injected into the page when you click Apply. */\n\n/* Example: change button hover colour */\n/*\n.btn-primary:hover {\n  background: #1a3a6b;\n}\n*/',
};
let admCodeCurrent = 'css';
function admCodeLoad(type) {
  admCodeCurrent = type;
  const saved = JSON.parse(localStorage.getItem('lumen_code_edits') || '{}');
  document.getElementById('adm-code-editor').value = saved[type] || CODE_SNIPPETS[type];
  document.getElementById('adm-code-label').textContent = { css:'CSS Variables', hero:'Hero Section CSS', nav:'Navigation CSS', custom:'Custom CSS / JS' }[type];
  document.querySelectorAll('.adm-code-tab').forEach(t => {
    const isActive = t.id === 'codetab-' + type;
    t.style.background = isActive ? 'rgba(200,146,42,0.15)' : 'rgba(247,245,240,0.06)';
    t.style.color = isActive ? '#c8922a' : 'rgba(247,245,240,0.5)';
    t.style.borderColor = isActive ? 'rgba(200,146,42,0.3)' : 'rgba(247,245,240,0.12)';
  });
  document.getElementById('adm-code-feedback').style.display = 'none';
}
function admCodeApply() {
  const code = document.getElementById('adm-code-editor').value;
  const saved = JSON.parse(localStorage.getItem('lumen_code_edits') || '{}');
  saved[admCodeCurrent] = code;
  localStorage.setItem('lumen_code_edits', JSON.stringify(saved));
  if (admCodeCurrent === 'css' || admCodeCurrent === 'nav' || admCodeCurrent === 'hero') {
    let styleEl = document.getElementById('admin-injected-css');
    if (!styleEl) { styleEl = document.createElement('style'); styleEl.id = 'admin-injected-css'; document.head.appendChild(styleEl); }
    const allCode = Object.entries(saved).filter(([k])=>k!=='custom').map(([,v])=>v).join('\n');
    styleEl.textContent = allCode;
  }
  if (admCodeCurrent === 'custom') {
    try {
      let customEl = document.getElementById('admin-custom-inject');
      if (!customEl) { customEl = document.createElement('style'); customEl.id = 'admin-custom-inject'; document.head.appendChild(customEl); }
      customEl.textContent = code.replace(/<script[^>]*>[\s\S]*?<\/script>/gi, '');
    } catch(e) {}
  }
  document.getElementById('adm-code-feedback').style.display = 'block';
  admActivity('Code applied: ' + admCodeCurrent);
  admShowSaved();
}
function admCodeReset() {
  if (!confirm('Reset this code block to default?')) return;
  document.getElementById('adm-code-editor').value = CODE_SNIPPETS[admCodeCurrent];
  admActivity('Code reset: ' + admCodeCurrent);
}

// ===== PRICING APPLY =====
function admPricingApply() {
  const price = document.getElementById('price-annual').value;
  const trial = document.getElementById('price-trial').value;
  document.querySelectorAll('.price-amount').forEach((el,i) => { if (i===1) el.textContent = price; });
  document.querySelectorAll('.pricing-btn').forEach((el,i) => {
    if (i===0) el.textContent = 'Start ' + trial + '-day free trial →';
    if (i===1) el.textContent = 'Start for €' + price + '/year →';
  });
  admActivity('Pricing updated: €' + price + '/yr · ' + trial + '-day trial');
  admShowSaved();
}

// ===== BRANDING APPLY =====
function admColorChange(varName, val) {
  document.documentElement.style.setProperty(varName, val);
  admActivity('Colour changed: ' + varName + ' → ' + val);
}
function admBrandingApply() {
  const name = document.getElementById('brand-name').value.trim();
  if (name) {
    document.querySelectorAll('.nav-logo span, .footer-brand').forEach(el => el.textContent = name);
    document.title = name + ' — The AI Exam Coach';
  }
  admActivity('Branding applied');
  admShowSaved();
}

// ===== SECURITY =====
function admSecuritySave() {
  const u = document.getElementById('sec-newuser').value.trim();
  const p = document.getElementById('sec-newpass').value;
  const c = document.getElementById('sec-confpass').value;
  const fb = document.getElementById('sec-feedback');
  if (!u || !p) { fb.style.display='block'; fb.style.background='rgba(224,88,88,0.1)'; fb.style.color='#e05858'; fb.style.border='1px solid rgba(224,88,88,0.2)'; fb.textContent='Username and password cannot be empty.'; return; }
  if (p !== c) { fb.style.display='block'; fb.style.background='rgba(224,88,88,0.1)'; fb.style.color='#e05858'; fb.style.border='1px solid rgba(224,88,88,0.2)'; fb.textContent='Passwords do not match.'; return; }
  ADMIN_CREDS = { user: u, pass: p };
  localStorage.setItem('lumen_admin_creds', JSON.stringify(ADMIN_CREDS));
  fb.style.display='block'; fb.style.background='rgba(91,206,138,0.1)'; fb.style.color='#5bce8a'; fb.style.border='1px solid rgba(91,206,138,0.2)'; fb.textContent='✓ Credentials updated. Export the HTML to save permanently.';
  document.getElementById('sec-newuser').value = '';
  document.getElementById('sec-newpass').value = '';
  document.getElementById('sec-confpass').value = '';
  admActivity('Admin credentials changed');
}

// ===== EXPORT HTML =====
function admExportHTML() {
  const html = '<!DOCTYPE html>\n' + document.documentElement.outerHTML;
  const blob = new Blob([html], { type: 'text/html' });
  const a = document.createElement('a');
  a.href = URL.createObjectURL(blob);
  a.download = 'lumen_site_' + new Date().toISOString().slice(0,10) + '.html';
  a.click();
  admActivity('HTML exported');
}

// ===== SAVE INDICATOR =====
function admShowSaved() {
  const ind = document.getElementById('admin-save-indicator');
  if (!ind) return;
  ind.style.display = 'block';
  clearTimeout(admShowSaved._t);
  admShowSaved._t = setTimeout(() => { ind.style.display = 'none'; }, 2000);
}

// ===== APPLY SAVED TEXT ON LOAD =====
document.addEventListener('DOMContentLoaded', () => {
  const saved = JSON.parse(localStorage.getItem('lumen_text_edits') || '{}');
  TEXT_BLOCKS.forEach(b => {
    if (saved[b.id]) {
      const targets = document.querySelectorAll(b.selector);
      targets.forEach(el => { if (b.type === 'html') el.innerHTML = saved[b.id]; else el.textContent = saved[b.id]; });
    }
  });
});
</script>
</body>
</html>
