---
permalink: /
layout: default
title: "Xiaopeng Wang"
excerpt: "Xiaopeng Wang — M.S. in Computer Science student at Dartmouth College. Research interests in Scientific Machine Learning."
redirect_from:
  - /about/
  - /about.html
---

<link rel="stylesheet" href="{{ '/assets/css/homepage.css' | relative_url }}">
<main id="main" class="academic-home">
  <section class="home-hero" aria-labelledby="home-name">
    <div class="home-intro">
      <p class="home-eyebrow">DARTMOUTH · COMPUTER SCIENCE</p>
      <h1 id="home-name">Xiaopeng Wang<span aria-hidden="true">.</span></h1>
      <p class="home-focus">Exploring Scientific<br>Machine Learning.</p>
      <p class="home-bio">I'm an M.S. in Computer Science student at Dartmouth College. I graduated from the University of Science and Technology of China (USTC) in 2026 with a B.S. in Information Security. I have the honor of collaborating with Prof. <a href="https://sites.google.com/site/yangyaoqingcmu/home">Yaoqing Yang</a> and Dr. <a href="https://paulpuren.github.io/">Pu Ren</a>.</p>
      <div class="home-actions">
        <a class="home-button" href="{{ '/publications/' | relative_url }}">View publications <span aria-hidden="true">↗</span></a>
        <a class="home-text-link" href="mailto:{{ site.author.email }}">Get in touch <span aria-hidden="true">↗</span></a>
      </div>
    </div>
    <figure class="home-portrait">
      <img src="{{ '/images/profile.png' | relative_url }}" alt="Portrait of Xiaopeng Wang" width="440" height="520" fetchpriority="high">
      <figcaption><span class="home-dot" aria-hidden="true"></span> Dartmouth College</figcaption>
    </figure>
  </section>
  <div class="home-details">
    <section aria-labelledby="research-title">
      <p class="home-eyebrow">01 / RESEARCH</p>
      <h2 id="research-title">Research interests</h2>
      <p class="home-research">Scientific Machine Learning</p>
      <a class="home-text-link" href="{{ '/publications/' | relative_url }}">Explore my publications <span aria-hidden="true">↗</span></a>
    </section>
    <section aria-labelledby="education-title">
      <p class="home-eyebrow">02 / EDUCATION</p>
      <h2 id="education-title">Academic background</h2>
      <p class="home-degree">M.S. in Computer Science</p>
      <p>Dartmouth College</p>
      <p class="home-muted">Currently enrolled</p>
      <p class="home-degree" style="margin-top:24px;">B.S. in Information Security</p>
      <p>University of Science and Technology of China</p>
      <p class="home-muted">Graduated 2026</p>
      <a class="home-text-link" href="{{ '/awards/' | relative_url }}">Honors &amp; awards <span aria-hidden="true">↗</span></a>
    </section>
  </div>
  <section class="home-contact" aria-label="Contact and profiles">
    <p>Let's connect<span class="home-muted"> / </span></p>
    <div>
      <a href="mailto:{{ site.author.email }}">Email ↗</a>
      <a href="{{ site.author.googlescholar }}">Google Scholar ↗</a>
      <a href="https://github.com/{{ site.author.github }}">GitHub ↗</a>
    </div>
  </section>
</main>
