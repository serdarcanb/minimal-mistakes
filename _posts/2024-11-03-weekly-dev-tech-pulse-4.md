---
layout: splash
classes: wide
modified: 2024-11-03
excerpt: "<br>"
author: Serdarcan Buyukdereli
title: Weekly Dev Tech Pulse#4
author_profile: false
comments: true
categories:
- Weekly
header:
   overlay_color: "#5e616c"
   overlay_image: https://serdarcanb.github.io/assets/images/Weekly-2.png
   overlay_filter: .8
   teaser: https://serdarcanb.github.io/assets/images/Weekly-2.png
tags:
- Weekly
- DevOps
- Tech

excerpt: Weekly Dev Tech Pulse 4 is here with the latest in DevOps and software trends!

pinned: false
toc: false
toc_label: Weekly Dev Tech Pulse
toc_icon: "cog"
image: https://serdarcanb.github.io/assets/images/Weekly-2.png
seo_title: Weekly Dev Tech Pulse
seo_description: Stay updated with Weekly Dev Tech Pulse, your go-to source for the latest developer tools, tech articles, and open-source repos. Discover fresh insights and stay ahead in the world of software development.

---

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
  /* Genel tasarım iyileştirmeleri */
  body {
    background-color: #f5f5f5;
    font-family: 'Roboto', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
  }

  .newsletter-header {
    text-align: center;
    margin-top: 30px;
    margin-bottom: 40px;
  }

  .section-title {
    margin-bottom: 40px;
    font-size: 28px;
    font-weight: bold;
    color: #333;
  }

  .card {
    border-radius: 20px;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
    background-color: #fff;
    margin-bottom: 30px;
  }

  .card:hover {
    transform: scale(1.03);
    box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
  }

  .card-title {
    font-size: 22px;
    font-weight: bold;
    color: #0056b3;
  }

  .card-text {
    font-size: 16px;
    color: #666;
  }

  .tags a {
    margin-right: 10px;
    font-size: 14px;
  }

  .btn-outline-light:hover {
    background-color: #0056b3;
    border-color: #0056b3;
    color: white;
  }

  .small-image {
    max-width: 70px; /* Resim genişliği küçültüldü */
    height: auto; /* Oranlarını koruyarak yüksekliği otomatik ayarla */
  }
  /* Responsive ayarlar */
  @media (max-width: 576px) {
    .card-title {
      font-size: 18px;
    }

    .card-text {
      font-size: 14px;
    }

    .section-title {
      font-size: 24px;
    }

    .tags a {
      font-size: 12px;
    }

    .card img {
      max-width: 80px; /* Küçük ekranlarda resim küçültüldü */
    }
  }

  @media (max-width: 768px) {
    .section-title {
      font-size: 26px;
    }

    .card-title {
      font-size: 20px;
    }

    .card-text {
      font-size: 15px;
    }

    .tags a {
      font-size: 13px;
    }
  }

</style>

<div class="container">

  <!-- Header -->
  <div class="newsletter-header">
    <h1 class="text-uppercase fw-bold">Weekly Dev Tech Pulse</h1>
    <p class="lead">*Weekly DevOps & Developer News and Highlights*</p>
    <p><strong>Date:</strong> Week of November 03th, 2024</p>
  </div>

  <!-- Top GitHub Projects -->
  <h2 class="section-title text-center">🔥 Top GitHub Projects of the Week</h2>

  <!-- Project Card 1 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://serdarcanb.github.io/assets/images/logos/github.svg" class="img-fluid rounded-start" alt="GitHub Logo">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">AppFlowy-IO/AppFlowy</h5>
          <p class="card-text">AppFlowy is an open-source alternative to Notion, designed for users who want complete control over their productivity tool.</p>
          <p class="card-text tags"><strong>Tags:</strong> 
            <a href="#" class="badge bg-primary text-decoration-none">notion-alternative</a>
            <a href="#" class="badge bg-primary text-decoration-none">open-source</a>
            <a href="#" class="badge bg-primary text-decoration-none">productivity</a>
            <a href="#" class="badge bg-primary text-decoration-none">customizable</a>
            <a href="#" class="badge bg-primary text-decoration-none">self-hosted</a>
          </p>
          <a href="https://github.com/AppFlowy-IO/AppFlowy" class="btn btn-outline-dark btn-sm">View the Project</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Project Card 2 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://serdarcanb.github.io/assets/images/logos/github.svg" class="img-fluid rounded-start" alt="GitHub Logo">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">mattermost/mattermost</h5>
          <p class="card-text">Mattermost is an open-source messaging and collaboration platform designed for secure team communication and workflow integration.</p>
          <p class="card-text tags"><strong>Tags:</strong> 
            <a href="#" class="badge bg-primary text-decoration-none">team-communication</a>
            <a href="#" class="badge bg-primary text-decoration-none">open-source</a>
            <a href="#" class="badge bg-primary text-decoration-none">self-hosted</a>
            <a href="#" class="badge bg-primary text-decoration-none">slack-alternative</a>
            <a href="#" class="badge bg-primary text-decoration-none">collaboration</a>
          </p>
          <a href="https://github.com/mattermost/mattermost" class="btn btn-outline-dark btn-sm">View the Project</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Project Card 3 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://serdarcanb.github.io/assets/images/logos/github.svg" class="img-fluid rounded-start" alt="GitHub Logo">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">semaphoreui/semaphore</h5>
          <p class="card-text">Semaphore is an open-source, self-hosted platform for deploying and managing Ansible playbooks with an intuitive web interface.</p>
          <p class="card-text tags"><strong>Tags:</strong> 
            <a href="#" class="badge bg-primary text-decoration-none">open-source</a>
            <a href="#" class="badge bg-primary text-decoration-none">ansible</a>
            <a href="#" class="badge bg-primary text-decoration-none">terraform</a>
            <a href="#" class="badge bg-primary text-decoration-none">ui</a>
            <a href="#" class="badge bg-primary text-decoration-none">self-hosted</a>
          </p>
          <a href="https://github.com/semaphoreui/semaphore" class="btn btn-outline-dark btn-sm">View the Project</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Project Card 4 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://serdarcanb.github.io/assets/images/logos/github.svg" class="img-fluid rounded-start" alt="GitHub Logo">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">netdata/netdata</h5>
          <p class="card-text">Netdata is an open-source, real-time monitoring and troubleshooting tool for systems and applications, providing detailed insights through an intuitive web interface. </p>
          <p class="card-text tags"><strong>Tags:</strong> 
            <a href="#" class="badge bg-primary text-decoration-none">open-source</a>
            <a href="#" class="badge bg-primary text-decoration-none">real-time</a>
            <a href="#" class="badge bg-primary text-decoration-none">ui</a>
            <a href="#" class="badge bg-primary text-decoration-none">monitoring</a>
            <a href="#" class="badge bg-primary text-decoration-none">self-hosted</a>
          </p>
          <a href="https://github.com/netdata/netdata" class="btn btn-outline-dark btn-sm">View the Project</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Project Card 5 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://serdarcanb.github.io/assets/images/logos/github.svg" class="img-fluid rounded-start" alt="GitHub Logo">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">dgtlmoon/changedetection.io</h5>
          <p class="card-text">changedetection.io is an open-source tool that monitors websites for content changes, alerting users to updates, restocks, and price changes. </p>
          <p class="card-text tags"><strong>Tags:</strong> 
            <a href="#" class="badge bg-primary text-decoration-none">open-source</a>
            <a href="#" class="badge bg-primary text-decoration-none">crawler</a>
            <a href="#" class="badge bg-primary text-decoration-none">website-monitoring</a>
            <a href="#" class="badge bg-primary text-decoration-none">self-hosted</a>
          </p>
          <a href="https://github.com/dgtlmoon/changedetection.io" class="btn btn-outline-dark btn-sm">View the Project</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Updates & Innovations Section -->
  <h2 class="section-title text-center">📢 Updates & Innovations</h2>

  <!-- Update Card 1 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://cdn-icons-png.flaticon.com/512/2512/2512773.png" class="img-fluid rounded-start small-image" alt="Update Icon">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">argmaxinc/WhisperKit v0.9.2</h5>
          <a href="https://github.com/argmaxinc/WhisperKit/releases/tag/v0.9.2" class="btn btn-outline-primary btn-sm">Get the Changelogs</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Update Card 2 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://cdn-icons-png.flaticon.com/512/2512/2512773.png" class="img-fluid rounded-start small-image" alt="Update Icon">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">golemcloud/golem v1.0.25</h5>
          <a href="https://github.com/golemcloud/golem/releases/tag/v1.0.25" class="btn btn-outline-primary btn-sm">Get the Changelogs</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Featured Articles Section -->
  <h2 class="section-title text-center">📝 Featured Articles</h2>

  <!-- Article Card 1 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fdf574dc8-f7cd-41f3-9210-2ec0500d00ac_1200x630.gif" class="img-fluid rounded-start" alt="Article Image">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">How Amazon S3 Works</h5>
          <p class="card-text">Discover how S3 architecture enhances large-scale data storage and how ClickHouse’s new data type for JSON improves data processing efficiency.</p>
          <a href="https://newsletter.systemdesign.one/p/s3-architecture" class="btn btn-outline-success btn-sm">Read the full article</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Article Card 2 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb0d33e20-43fe-49ac-ab7e-f3e33066e642_2339x1679.png" class="img-fluid rounded-start" alt="Article Image">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">Git Branching Strategies</h5>
          <p class="card-text">Explore different Git branching strategies and find out which approach best suits your projects for a more efficient workflow.</p>
          <a href="https://newsletter.techworld-with-milan.com/p/git-branching-strategies" class="btn btn-outline-success btn-sm">Read the full article</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Article Card 3 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*MC8Ev9ttPqvBRxw5-CQ7lQ.png" class="img-fluid rounded-start" alt="Article Image">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">10 Best Resources to Learn Software Architecture in 2025</h5>
          <p class="card-text">Discover the top resources to learn software architecture in 2025 and gain in-depth knowledge to advance your career in the software industry.</p>
          <a href="https://medium.com/javarevisited/10-best-resources-to-learn-software-architecture-in-2025-2524ac91dc76" class="btn btn-outline-success btn-sm">Read the full article</a>
        </div>
      </div>
    </div>
  </div>

  <h2 class="section-title text-center">🎧 Podcasts & Videos</h2>

  <!-- Videos Card 1 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/ef/Youtube_logo.png" class="img-fluid rounded-start" alt="Video Image">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">The Untold Story of GitHub</h5>
          <p class="card-text">From a bar chat to a platform with 100 million users, GitHub’s journey is packed with twists—Microsoft’s acquisition and Copilot’s ethical controversies fuel intrigue. How did this platform revolutionize global software collaboration? 👇</p>
          <a href="https://www.youtube.com/watch?v=THtsXAewIVc" class="btn btn-outline-danger btn-sm">Watch / Listen</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Tools & Resources Section -->
  <h2 class="section-title text-center">🚀 Tools & Resources</h2>

  <!-- Tool Card 1 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://github.com/gitbutlerapp/gitbutler/raw/master/crates/gitbutler-tauri/icons/128x128@2x.png" class="img-fluid rounded-start" alt="Tool Image">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">gitbutler</h5>
          <p class="card-text">The GitButler version control client, backed by Git, powered by Tauri/Rust/Svelte.</p>
          <a href="https://github.com/gitbutlerapp/gitbutler" class="btn btn-outline-info btn-sm">Explore the Tool</a>
        </div>
      </div>
    </div>
  </div>


  <!-- Tool Card 2 -->
  <div class="card p-4">
    <div class="row g-0">
      <div class="col-12 col-sm-3 col-md-2 d-flex align-items-center">
        <img src="https://raw.githubusercontent.com/RickWong/Captain/main/public/Icon.png" class="img-fluid rounded-start" alt="Tool Image">
      </div>
      <div class="col-12 col-sm-9 col-md-10">
        <div class="card-body">
          <h5 class="card-title">Captain</h5>
          <p class="card-text">Manage Docker containers from the menu bar in macOS</p>
          <a href="https://getcaptain.co/" class="btn btn-outline-info btn-sm">Explore the Tool</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Stay Connected Section -->
  <h2 class="section-title text-center">🔗 Stay Connected</h2>

  <div class="text-center mb-5">
    <a href="mailto:serdarcanbuyukdereli@gmail.com" class="btn btn-outline-dark">Contact Me via Email</a>
    <a href="https://serdarcanb.github.io" class="btn btn-outline-dark">Visit My Website</a>
    <a href="https://github.com/serdarcanb" class="btn btn-outline-dark">GitHub Profile</a>
    <a href="https://linkedin.com/in/serdarcanbuyukdereli/" class="btn btn-outline-dark">LinkedIn Profile</a>
    <a href="https://dly.to/pK9N9ZBBwrP" class="btn btn-outline-dark">Daily Dev</a>
  </div>

</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>