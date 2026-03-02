---
layout: home
title: Home
---

<div class="hero">
  <div class="hero__top">
    <h1 class="hero__title">Bora Atakan</h1>
    <p class="hero__subtitle">
      Computer Science (Co-op) student at the University of Waterloo. I build practical systems for search, reinforcement learning, and robotics.
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
        <strong>University of Waterloo — Bachelor of Computer Science (Honours), Co-op</strong>
        <span class="meta">2025 – 2030</span>
      </div>
      <p>Waterloo, Ontario, Canada</p>
      <p>GPA: 3.9/4.0</p>
      <p><strong>Advanced Courses:</strong> Designing Functional Programs, Calculus 2, Linear Algebra 1</p>
    </div>
  </div>
</section>

<section class="section" id="skills">
  <h2>Skills</h2>
  <div class="grid">
    <div class="card">
      <p><strong>Languages:</strong> Python, Racket/Lisp, C (beginner)</p>
      <p><strong>Technical Skills:</strong> Machine Learning, Robotics, Welding, Fabrication, SolidWorks, Arduino</p>
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
        <li>Worked on search and information retrieval, gathering requirements and shipping backend and frontend features used by paying customers.</li>
        <li>Shipped full-text search with Elasticsearch and Python, indexing thousands of PDF documents.</li>
        <li>Consolidated search under a single API, tuned ranking across filename/summary/content, and implemented result highlighting in React.</li>
      </ul>
    </div>
  </div>
</section>

<section class="section" id="projects">
  <h2>Projects</h2>
  <div class="grid">
    <div class="card">
      <div class="card__title">
        <strong>WAT.ai — Deep Learning Race Car Team</strong>
        <span class="meta">PPO / PyBullet / Raspberry Pi</span>
      </div>
      <ul>
        <li>Built a miniature RC race car platform that runs on a simulation track.</li>
        <li>Trained and tuned PPO policies (Stable-Baselines3) and built a PyBullet simulation environment for faster iteration.</li>
        <li>Led hardware selection and integration on Raspberry Pi, including camera vision for line detection.</li>
      </ul>
    </div>

    <div class="card">
      <div class="card__title">
        <strong>Minecraft-like Model Training Sandbox</strong>
        <span class="meta">Simulation / RL Data / React / FastAPI</span>
      </div>
      <ul>
        <li>Built a 3D game environment with seed-based deterministic generation, physics, and interactive objects.</li>
        <li>Implemented headless screenshot-based regression testing and replay tooling.</li>
        <li>Added RL data collection and a React + FastAPI admin control UI.</li>
      </ul>
    </div>

    <div class="card">
      <div class="card__title">
        <strong>CUDA Kernel Dev RL Environment</strong>
        <span class="meta">CUDA / Modal / A10 GPUs</span>
      </div>
      <ul>
        <li>Built an RL environment for fused ML CUDA kernels (LayerNorm, Residual, SiLU).</li>
        <li>Implemented a correctness and performance judge harness using Modal A10 GPUs, `nvcc`, and curated I/O datasets.</li>
        <li>Reached a 20% success rate on Claude Haiku 4.5 over 100 attempts with 5 retries per attempt.</li>
      </ul>
    </div>

    <div class="card">
      <div class="card__title">
        <strong>Speech to Phonemes</strong>
        <span class="meta">Datasets / Training</span>
      </div>
      <p>
        Created a 183GB Hugging Face dataset for phoneme detection, built mixed-dataset dataloaders, and ran training
        jobs on A10 and A100 GPUs to improve end-to-end evaluation metrics.
      </p>
    </div>

    <div class="card">
      <div class="card__title">
        <strong>Fatigue Detection System</strong>
        <span class="meta">OpenCV / MediaPipe / PyQt</span>
      </div>
      <p>
        Built healthcare-oriented software that detects eye-related fatigue signals and suggests next steps, with
        handling for user eye geometry and camera distance differences.
      </p>
    </div>

    <div class="card">
      <div class="card__title">
        <strong>Smart Screen Lock</strong>
        <span class="meta">OpenCV / Tkinter</span>
      </div>
      <p>
        Built a Windows application that locks the computer when an unknown user is detected peeking at the screen.
      </p>
    </div>
  </div>
</section>

<section class="section" id="extracurricular">
  <h2>Extracurricular</h2>
  <div class="grid">
    <div class="card">
      <div class="card__title">
        <strong>Leadership — RedFox Robotics</strong>
        <span class="meta">2022 – Present</span>
      </div>
      <ul>
        <li>Co-founded RedFox Robotics and co-led a 26-person team.</li>
        <li>Raised over $10,000 for workshop infrastructure and trained 23 new members.</li>
        <li>Built simulations to speed up control iteration; placed 11th in regional qualification and advanced to playoffs as Alliance 7 captain.</li>
      </ul>
    </div>

    <div class="card">
      <div class="card__title">
        <strong>Competitions & Awards — FIRST Robotics Competition (FRC)</strong>
        <span class="meta">2022 – Present</span>
      </div>
      <ul>
        <li>Received 6 awards across two FRC teams (2022–2025).</li>
      </ul>
    </div>
  </div>
</section>

<section class="section" id="resume">
  <h2>Resume</h2>
  <div class="card">
    <div class="resume">
      <div>
        <strong>Download PDF</strong>
        <div class="meta">Last updated: Mar 1, 2026</div>
      </div>
      <a class="button" href="{{ '/assets/cv/Bora_Atakan_Resume.pdf' | relative_url }}" target="_blank" rel="noopener">
        Bora_Atakan_Resume.pdf
      </a>
    </div>
  </div>
</section>
