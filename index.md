---
layout: home
title: Home
---

<div class="hero">
  <div class="hero__top">
    <h1 class="hero__title">Bora Atakan</h1>
    <p class="hero__subtitle">
      Computer Science (Co-op) at the University of Waterloo. I like building practical systems for search, ML, and robotics.
    </p>

    <div class="pill-row">
      <a class="pill" href="mailto:{{ site.author.email }}"><span>Email</span><code>{{ site.author.email }}</code></a>
      <a class="pill" href="{{ site.social.github }}" target="_blank" rel="me"><span>GitHub</span></a>
      <a class="pill" href="{{ site.social.linkedin }}" target="_blank" rel="me"><span>LinkedIn</span></a>
    </div>
  </div>
</div>

<section class="section" id="education">
  <h2>Education</h2>
  <div class="grid">
    <div class="card">
      <div class="card__title">
        <strong>University of Waterloo — BCS (Honours), Co-op</strong>
        <span class="meta">2025 – 2030</span>
      </div>
      <p>GPA: 3.9/4.0. Advanced coursework includes functional programming, calculus, and linear algebra.</p>
    </div>
  </div>
</section>

<section class="section" id="skills">
  <h2>Skills</h2>
  <div class="grid">
    <div class="card">
      <p><strong>Languages:</strong> Python, Racket/Lisp, C (beginner)</p>
      <p><strong>Focus:</strong> Machine Learning, Robotics, GPU Programming</p>
      <p><strong>Hardware:</strong> SolidWorks, Arduino, Welding/Fabrication</p>
    </div>
  </div>
</section>

<section class="section" id="experience">
  <h2>Experience</h2>
  <div class="grid">
    <div class="card">
      <div class="card__title">
        <strong>Thresh Power — Software Development Intern</strong>
        <span class="meta">Summer 2024</span>
      </div>
      <ul>
        <li>Shipped full-text search using Elasticsearch + Python, indexing thousands of PDF documents.</li>
        <li>Consolidated search behind a single API and tuned ranking across filename/summary/content signals.</li>
        <li>Implemented search result highlighting in React.</li>
      </ul>
    </div>

    <div class="card">
      <div class="card__title">
        <strong>RedFox Robotics — Co-founder / Team Lead</strong>
        <span class="meta">2022 – Present</span>
      </div>
      <ul>
        <li>Co-led a 26-person team; raised $10,000+ for a workshop; trained 23 new members.</li>
        <li>Built simulations to iterate faster on robot controls; competed in FRC (playoff captain role).</li>
      </ul>
    </div>
  </div>
</section>

<section class="section" id="projects">
  <h2>Projects</h2>
  <div class="grid">
    <div class="card">
      <div class="card__title">
        <strong>CUDA Kernel Dev RL Environment</strong>
        <span class="meta">CUDA / Modal / A10 GPUs</span>
      </div>
      <p>
        Built an RL environment for CUDA kernel development for fused ML ops (LayerNorm, Residual, SiLU), with a
        correctness + performance judge harness using nvcc tooling and curated IO pairs.
      </p>
    </div>

    <div class="card">
      <div class="card__title">
        <strong>WAT.ai — Deep Learning Race Car Team</strong>
        <span class="meta">PPO / PyBullet / Raspberry Pi</span>
      </div>
      <ul>
        <li>Trained and tuned control policies using PPO (Stable-Baselines3).</li>
        <li>Built a PyBullet simulation environment for faster iteration; led RC platform assembly/integration.</li>
        <li>Implemented camera vision for line detection.</li>
      </ul>
    </div>

    <div class="card">
      <div class="card__title">
        <strong>Speech to Phonemes</strong>
        <span class="meta">Datasets / Training</span>
      </div>
      <p>
        Created a 183GB Hugging Face dataset for phoneme detection; ran training jobs on A10/A100 GPUs and improved
        end-to-end evaluation metrics.
      </p>
    </div>
  </div>
</section>

<section class="section" id="resume">
  <h2>Resume</h2>
  <div class="card">
    <div class="resume">
      <div>
        <strong>Download PDF</strong>
        <div class="meta">Last updated: Jan 20, 2026</div>
      </div>
      <a class="button" href="{{ '/assets/cv/Bora_Atakan_Resume.pdf' | relative_url }}" target="_blank" rel="noopener">
        Bora_Atakan_Resume.pdf
      </a>
    </div>
  </div>
</section>
