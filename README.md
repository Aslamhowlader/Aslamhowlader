<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Md Aslam Howlader — Portfolio</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@latest/tabler-icons.min.css"/>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Segoe UI', system-ui, sans-serif;
      background: #f5f5f0;
      color: #1a1a1a;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 2rem 1rem;
    }

    .port-root {
      max-width: 680px;
      width: 100%;
      background: #fff;
      border-radius: 16px;
      border: 0.5px solid #ddd;
      padding: 2rem;
    }

    .hero {
      display: flex;
      align-items: center;
      gap: 16px;
      margin-bottom: 1.5rem;
    }

    .avatar {
      width: 56px;
      height: 56px;
      border-radius: 50%;
      background: #e6f1fb;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 18px;
      font-weight: 500;
      color: #185fa5;
      flex-shrink: 0;
    }

    .hero-text h1 { font-size: 20px; font-weight: 500; margin-bottom: 2px; }
    .hero-text p  { font-size: 13px; color: #666; }

    .tag-row { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 1.5rem; }
    .tag {
      font-size: 12px; padding: 3px 10px;
      border-radius: 99px; border: 0.5px solid #ccc;
      color: #555; background: #f5f5f0;
    }

    .section-label {
      font-size: 11px; font-weight: 500;
      letter-spacing: 0.08em; text-transform: uppercase;
      color: #999; margin-bottom: 10px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 10px; margin-bottom: 1.5rem;
    }

    .card {
      background: #fff; border: 0.5px solid #e0e0e0;
      border-radius: 12px; padding: 14px 16px;
    }
    .card i { font-size: 20px; color: #185fa5; margin-bottom: 8px; display: block; }
    .card .card-title { font-size: 14px; font-weight: 500; margin-bottom: 4px; }
    .card .card-sub  { font-size: 12px; color: #666; line-height: 1.5; }

    .links-grid { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 1.5rem; }
    .link-btn {
      display: inline-flex; align-items: center; gap: 6px;
      font-size: 13px; padding: 6px 14px;
      border-radius: 8px; border: 0.5px solid #ccc;
      color: #1a1a1a; background: #fff; text-decoration: none;
      transition: background 0.15s;
    }
    .link-btn:hover { background: #f5f5f0; }
    .link-btn i { font-size: 15px; color: #666; }

    .motto {
      border-left: 2px solid #b5d4f4;
      padding: 10px 16px; margin-bottom: 1.5rem;
    }
    .motto p { font-size: 14px; color: #555; line-height: 1.6; font-style: italic; }

    @media (prefers-color-scheme: dark) {
      body { background: #1a1a1a; color: #eee; }
      .port-root { background: #242424; border-color: #333; }
      .hero-text p, .card .card-sub, .motto p { color: #aaa; }
      .tag  { background: #2e2e2e; border-color: #444; color: #bbb; }
      .card { background: #2a2a2a; border-color: #383838; }
      .link-btn { background: #2a2a2a; border-color: #444; color: #eee; }
      .link-btn:hover { background: #333; }
      .link-btn i { color: #aaa; }
      .avatar { background: #0c447c; color: #b5d4f4; }
      .motto { border-left-color: #185fa5; }
    }
  </style>
</head>
<body>
  <div class="port-root">

    <div class="hero">
      <div class="avatar">AH</div>
      <div class="hero-text">
        <h1>Md Aslam Howlader</h1>
        <p>ML Engineer · Data Science Explorer · Competitive Programmer · Bangladesh</p>
      </div>
    </div>

    <div class="tag-row">
      <span class="tag">Python</span>
      <span class="tag">Machine Learning</span>
      <span class="tag">Deep Learning</span>
      <span class="tag">SQL</span>
      <span class="tag">Data Structures</span>
      <span class="tag">Algorithms</span>
      <span class="tag">Docker</span>
      <span class="tag">Power BI</span>
      <span class="tag">Jupyter</span>
    </div>

    <p class="section-label">Focus areas</p>
    <div class="cards">
      <div class="card">
        <i class="ti ti-brain"></i>
        <p class="card-title">ML systems</p>
        <p class="card-sub">Industry-grade pipelines & real-world AI deployment</p>
      </div>
      <div class="card">
        <i class="ti ti-chart-bar"></i>
        <p class="card-title">Data science</p>
        <p class="card-sub">Statistical learning & data-driven solutions</p>
      </div>
      <div class="card">
        <i class="ti ti-tournament"></i>
        <p class="card-title">Competitive programming</p>
        <p class="card-sub">Active on Codeforces as <code>aslam03</code></p>
      </div>
      <div class="card">
        <i class="ti ti-microscope"></i>
        <p class="card-title">AI research</p>
        <p class="card-sub">Open-source & Google Scholar publications</p>
      </div>
    </div>

    <p class="section-label">Links</p>
    <div class="links-grid">
      <a class="link-btn" href="https://resonant-donut-233643.netlify.app/" target="_blank"><i class="ti ti-world"></i>Portfolio</a>
      <a class="link-btn" href="https://github.com/aslamhowlader" target="_blank"><i class="ti ti-brand-github"></i>GitHub</a>
      <a class="link-btn" href="https://www.linkedin.com/in/aslam-howlader-263015329/" target="_blank"><i class="ti ti-brand-linkedin"></i>LinkedIn</a>
      <a class="link-btn" href="https://codeforces.com/profile/aslam03" target="_blank"><i class="ti ti-code"></i>Codeforces</a>
      <a class="link-btn" href="https://scholar.google.com/citations?user=JZhJxXgAAAAJ&hl=en" target="_blank"><i class="ti ti-school"></i>Scholar</a>
      <a class="link-btn" href="https://www.youtube.com/@DataMind_Aslam03" target="_blank"><i class="ti ti-brand-youtube"></i>YouTube</a>
      <a class="link-btn" href="mailto:mdaslamhowlader09@gmail.com"><i class="ti ti-mail"></i>Email</a>
    </div>

    <div class="motto">
      <p>"Designing intelligent systems that learn, adapt, and solve real-world problems through data, discipline, and deep learning."</p>
    </div>

  </div>
</body>
</html>
