---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hello, I’m Wei Lai (赖葳), a first-year Master's student at Sichuan University. I am passionate about Real-time Rendering, 3D Gaussian Splatting (3DGS), and Game Engine Technologies.

# 🔥 News
- *2026.02*: &nbsp;🎉🎉  I started the Tencent Games Remote Engine Technology Research & Practice Program.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CGF</div><img src='images/cgf.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Gaussian Splatting for Large‐Scale Aerial Scene Reconstruction From Ultra‐High‐Resolution Images](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.70265)

Qiulin Sun, **Wei Lai**, Yixian Li, Yanci Zhang

- This work proposes a dual-space partitioning method to enable high-quality 2DGS reconstruction of large-scale aerial scenes from 9K-resolution images on a single consumer GPU (e.g., RTX 4090) by strictly controlling memory usage. 
</div>
</div>

# 🚀 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UE / C++</div><img src='images/ugs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UnrealGaussianSplatting](https://github.com/laiwei0304/UnrealGaussianSplatting)

- An Unreal Engine 5.5.4 plugin for importing, loading, and rendering 3DGS data. It supports standard 3DGS PLY assets, runtime file loading, and a billboard-based rendering pipeline with basic editor tooling for inspection and scene placement.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Vulkan / C++</div><img src='images/chimi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ChimiEngine](https://github.com/laiwei0304/ChimiEngine)

- A personal real-time rendering engine designed as a hands-on exploration of graphics architecture, engine systems, and rendering workflows. It currently includes a platform layer, Vulkan rendering abstractions, ECS-based scene management, material and texture systems, and runnable samples.
</div>
</div>

# 🎖 Honors and Awards
- *2024.05*, China College Student Computer Design Competition - **Provincial Second Prize**. 
- *2024.04*, Lanqiao National Software and Information Technology Professional Talent Competition (Algorithm Group - C/C++) - **Provincial Second Prize**. 
- *2024.04*, National English Competition for College Students - **Provincial Third Prize**. 
- *2023.12*, Chinese Mathematics Competition - **Provincial Third Prize**. 

# 📖 Educations
- *2025.09 - 2028.06 (expected)*, Master of Electronic Information, Sichuan University. 
- *2021.09 - 2025.06*, Bachelor of Software Engineering, Sichuan University. 

# 💻 Internships
- Coming soon!
