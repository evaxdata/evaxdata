<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Linda Eva – GitHub README Preview</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Mono:wght@300;400;500&display=swap');

  :root {
    --ink: #0f1117;
    --paper: #f5f2eb;
    --gold: #c9980a;
    --gold-light: #f0d060;
    --muted: #6b6560;
    --rule: #d4cfc6;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: #e8e4db;
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    padding: 2rem;
    font-family: 'DM Mono', monospace;
  }

  .card {
    background: var(--paper);
    border: 1.5px solid var(--rule);
    max-width: 640px;
    width: 100%;
    padding: 3rem 3.5rem 2.5rem;
    position: relative;
    box-shadow: 6px 6px 0 var(--ink);
    animation: rise 0.6s cubic-bezier(0.16, 1, 0.3, 1) both;
  }

  @keyframes rise {
    from { opacity: 0; transform: translateY(20px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .corner {
    position: absolute;
    top: 12px; right: 12px;
    width: 24px; height: 24px;
    border-top: 1.5px solid var(--gold);
    border-right: 1.5px solid var(--gold);
  }
  .corner-bl {
    top: auto; right: auto;
    bottom: 12px; left: 12px;
    border-top: none; border-right: none;
    border-bottom: 1.5px solid var(--gold);
    border-left: 1.5px solid var(--gold);
  }

  .label {
    font-size: 0.6rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 1.4rem;
  }

  h1 {
    font-family: 'DM Serif Display', serif;
    font-size: 2.6rem;
    line-height: 1.1;
    color: var(--ink);
    margin-bottom: 0.2rem;
    animation: rise 0.6s 0.1s cubic-bezier(0.16, 1, 0.3, 1) both;
  }

  h1 em {
    font-style: italic;
    color: var(--gold);
  }

  .divider {
    height: 1.5px;
    background: linear-gradient(90deg, var(--ink) 60%, transparent);
    margin: 1.6rem 0;
    animation: widen 0.7s 0.3s cubic-bezier(0.16, 1, 0.3, 1) both;
    transform-origin: left;
  }

  @keyframes widen {
    from { transform: scaleX(0); opacity: 0; }
    to   { transform: scaleX(1); opacity: 1; }
  }

  .lines {
    display: flex;
    flex-direction: column;
    gap: 0.85rem;
  }

  .line {
    display: flex;
    align-items: baseline;
    gap: 0.9rem;
    font-size: 0.82rem;
    color: var(--ink);
    animation: rise 0.5s cubic-bezier(0.16, 1, 0.3, 1) both;
  }

  .line:nth-child(1) { animation-delay: 0.35s; }
  .line:nth-child(2) { animation-delay: 0.45s; }
  .line:nth-child(3) { animation-delay: 0.55s; }

  .tag {
    font-size: 0.6rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    padding: 3px 8px;
    flex-shrink: 0;
    margin-top: 1px;
    font-weight: 500;
  }

  /* Warm amber — education / learning */
  .tag.edu {
    background: #f5c842;
    border: 1.5px solid #c9980a;
    color: #3a2800;
  }

  /* Deep teal — building / craft */
  .tag.data {
    background: #4ecdc4;
    border: 1.5px solid #1a9990;
    color: #002e2c;
  }

  /* Dusty rose — portfolio / identity */
  .tag.web {
    background: #f0a8a8;
    border: 1.5px solid #c96060;
    color: #3a0a0a;
  }

  .line-text { line-height: 1.4; }
  .line-text a {
    color: var(--gold);
    text-decoration: none;
    border-bottom: 1px solid currentColor;
  }
  .line-text a:hover { opacity: 0.7; }

  .footer {
    margin-top: 2rem;
    padding-top: 1rem;
    border-top: 1px dashed var(--rule);
    font-size: 0.58rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
    display: flex;
    justify-content: space-between;
    animation: rise 0.5s 0.65s cubic-bezier(0.16, 1, 0.3, 1) both;
  }
</style>
</head>
<body>
<div class="card">
  <div class="corner"></div>
  <div class="corner corner-bl"></div>

  <div class="label">GitHub · README.md</div>

  <h1>Hi, I'm <em>Linda Eva</em> 👋</h1>

  <div class="divider"></div>

  <div class="lines">
    <div class="line">
      <span class="tag edu">Currently studying</span>
      <span class="line-text">🎓 Business Analytics Student @ Seneca College</span>
    </div>
    <div class="line">
      <span class="tag data">Building</span>
      <span class="line-text">📊 Privacy-aware, business-focused data solutions</span>
    </div>
    <div class="line">
      <span class="tag web">See my work</span>
      <span class="line-text">🌐 <a href="https://evaxdata.github.io" target="_blank">evaxdata.github.io</a></span>
    </div>
  </div>

  <div class="footer">
    <span>Linda Eva</span>
    <span>Data · Privacy · Business</span>
  </div>
</div>
</body>
</html>
