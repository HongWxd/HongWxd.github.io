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

I am the second year PhD student at the Sustainable Energy and Environment Thrust of The Hong Kong University of Science and Technology (Guangzhou), under the supervision of [Prof. Jiaqiang HUANG](https://seejhuang.people.ust.hk/) and [Prof. Jia LI](https://sites.google.com/view/lijia). Previously, I obtained my B.Eng. in Computer Science and Technology from Dalian Maritime Univerity in 2024.

My research interest includes AI for batteries, electrolyte optimization, and battery life prediction.


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2025</div><img src='images/BatteryLife.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BatteryLife: A Comprehensive Dataset and Benchmark for Battery Life Prediction](https://dl.acm.org/doi/10.1145/3711896.3737372)

Ruifeng Tan*, **Weixiang Hong***, Jiayue Tang, Xibin Lu, Ruijun Ma, Xiang Zheng, Jia Li, Jiaqiang Huang, Tong-Yi Zhang

[**Project Link**](https://github.com/Ruifeng-Tan/BatteryLife)

- Github stars ⭐:
<strong>
  <span id="batterylife-stars"> loading... </span>
</strong>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const repo = "Ruifeng-Tan/BatteryLife";
  const apiUrl = `https://api.github.com/repos/${repo}`;

  fetch(apiUrl, {
    headers: {
      "Accept": "application/vnd.github+json"
    }
  })
    .then(response => {
      if (!response.ok) {
        throw new Error("GitHub API request failed");
      }
      return response.json();
    })
    .then(data => {
      const stars = data.stargazers_count;
      document.getElementById("batterylife-stars").textContent =
        `${stars.toLocaleString()}`;
    })
    .catch(error => {
      console.error(error);
      document.getElementById("batterylife-stars").textContent = "";
    });
});
</script>


</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.