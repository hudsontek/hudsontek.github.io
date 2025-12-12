---
layout: default
title: Home
---

<style>
@import url("https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600&display=swap");
:root { --accent: #0ea5e9; --accent-2: #f97316; --ink: #0f172a; --surface: #f8fafc; }
body { font-family: "Space Grotesk", "Segoe UI", system-ui, -apple-system, sans-serif; color: var(--ink); }
.hero { background: linear-gradient(135deg, rgba(14,165,233,0.14), rgba(249,115,22,0.12)); border: 1px solid rgba(14,165,233,0.18); border-radius: 18px; padding: 32px; box-shadow: 0 20px 60px rgba(0,0,0,0.06); }
.hero h1 { margin-top: 8px; font-size: 2.25rem; letter-spacing: -0.02em; }
.hero p { max-width: 740px; font-size: 1.05rem; line-height: 1.55; }
.eyebrow { text-transform: uppercase; letter-spacing: 0.12em; font-weight: 600; color: #0ea5e9; margin: 0; }
.hero-actions { display: flex; gap: 12px; margin: 20px 0 10px; flex-wrap: wrap; }
.btn { padding: 10px 16px; border-radius: 12px; text-decoration: none; font-weight: 600; border: 1px solid transparent; transition: transform 120ms ease, box-shadow 120ms ease, background 200ms ease; }
.btn.primary { background: linear-gradient(120deg, #0ea5e9, #38bdf8); color: white; box-shadow: 0 12px 30px rgba(14,165,233,0.25); }
.btn.ghost { background: white; color: var(--ink); border-color: rgba(15,23,42,0.12); }
.btn:hover { transform: translateY(-1px); box-shadow: 0 14px 32px rgba(0,0,0,0.08); }
.hero-tags { display: flex; gap: 10px; padding: 0; margin: 8px 0 0; list-style: none; flex-wrap: wrap; }
.hero-tags li { background: white; border: 1px solid rgba(15,23,42,0.08); padding: 6px 10px; border-radius: 999px; font-size: 0.95rem; }
.section-title { display: flex; align-items: center; gap: 10px; margin: 34px 0 14px; }
.section-title span { width: 10px; height: 10px; border-radius: 50%; background: linear-gradient(135deg, #0ea5e9, #f97316); display: inline-block; }
.cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 16px; }
.card { background: white; border: 1px solid rgba(15,23,42,0.08); border-radius: 14px; padding: 16px; box-shadow: 0 12px 30px rgba(0,0,0,0.05); display: flex; flex-direction: column; gap: 6px; }
.card h3 { margin: 0; font-size: 1.1rem; }
.card p { margin: 0; color: #475569; line-height: 1.5; }
.card a { color: var(--accent); font-weight: 600; text-decoration: none; }
.card a:hover { text-decoration: underline; }
.highlight { display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 12px; margin-top: 12px; }
.stat { background: var(--surface); border: 1px solid rgba(15,23,42,0.06); padding: 14px; border-radius: 12px; font-weight: 600; }
.stat small { display: block; color: #64748b; font-weight: 500; margin-top: 4px; }
@media (max-width: 640px) { .hero h1 { font-size: 1.8rem; } .hero { padding: 24px; } }
</style>

<div class="hero">
  <p class="eyebrow">Portfolio</p>
  <h1>Zhixuan Huan — building thoughtful AI & product experiences</h1>
  <p>I explore how machine learning, data storytelling, and clear interfaces can make complex ideas feel approachable. Highlights below show research timelines, planners, and bias explorations in practice.</p>
  <div class="hero-actions">
    <a class="btn primary" href="https://drive.google.com/file/d/1KUxlsKxW5UyDP27KCoztNXY50-BPazva/view?usp=sharing" target="_blank" rel="noopener">View bio</a>
    <a class="btn ghost" href="#projects">See featured work</a>
  </div>
  <ul class="hero-tags">
    <li>AI timelines</li>
    <li>Applied ML</li>
    <li>Bias & fairness</li>
    <li>Product narratives</li>
  </ul>
</div>

<div class="section-title" id="projects"><span></span><h2>Featured Projects</h2></div>
<div class="cards">
  <article class="card">
    <h3><a href="https://docs.google.com/presentation/d/1SLiAc2CeYL0oyAAwIlO24ySNKeEGNIhr/edit?usp=sharing&ouid=113821768755447233365&rtpof=true&sd=true" target="_blank" rel="noopener">AI Timeline</a></h3>
    <p>A visual walkthrough of key AI milestones, balancing technical breakthroughs with human impact and narrative pacing.</p>
  </article>
  <article class="card">
    <h3><a href="https://chatgpt.com/g/g-690529e3ef148191bc3bbcf62bb739f9-astrophotography-planner-gpt" target="_blank" rel="noopener">Astrophotography Planner GPT</a></h3>
    <p>Assistant that schedules shoots around weather, gear, and sky events. Focused on crisp prompts and actionable checklists.</p>
  </article>
  <article class="card">
    <h3><a href="https://docs.google.com/document/d/1TqcPjkxUA1y-SxyOWLIQERs6CXHRolbQCjOWeg7yRBE/edit?usp=sharing" target="_blank" rel="noopener">ML vs. Deep Learning</a></h3>
    <p>Explains where classic ML beats deep nets (and vice versa) with concise comparisons and decision cues.</p>
  </article>
  <article class="card">
    <h3><a href="https://docs.google.com/document/d/1yMQO5gMDDOHjJtARQ-bsJ_lzg2rPrEDq/edit?usp=sharing&ouid=113821768755447233365&rtpof=true&sd=true" target="_blank" rel="noopener">Handling Data Bias</a></h3>
    <p>Practical framework to spot and mitigate dataset bias; includes checklists and remediation tactics for teams.</p>
  </article>
  <article class="card">
    <h3><a href="https://docs.google.com/document/d/1qii7tE9dTLUhIjd4t9MmoAJ2sWMNBg8o3bHdSajEr2w/edit?usp=sharing" target="_blank" rel="noopener">AI Incident Analysis Report</a></h3>
    <p>An analysis report for an incident that is related to AI.</p>
  </article>
</div>

<div class="section-title" id="highlights"><span></span><h2>Highlights</h2></div>
<div class="highlight">
  <div class="stat">4+ featured explorations<small>AI, bias, planners, comparisons</small></div>
  <div class="stat">Audience-first storytelling<small>Slides, docs, and agent UX patterns</small></div>
  <div class="stat">Systems mindset<small>Bridges research clarity to shipped utility</small></div>
</div>

<div class="section-title" id="writing"><span></span><h2>Writing & Notes</h2></div>
<ul>
  <li>Post series coming soon — focused on practical ML heuristics and design notes. Ping me if you want early drafts.</li>
</ul>

<div class="section-title" id="contact"><span></span><h2>Connect</h2></div>
<p>Open to collaborations on AI explainability, product storytelling, and data-informed decision tools. Reach out via the bio link above.</p>
