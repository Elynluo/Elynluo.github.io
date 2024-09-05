---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="https://scholar.google.com/citations?user=YGzd7BMAAAAJ">my Google Scholar profile</a>.</div>
{% endif %} -->


<html>
<head>
<style>
  div.pub {
    line-height: 120%;
  }

  .publication {
    display: grid; /* Use grid display for layout */
    grid-template-columns: 150px 1fr; /* Two columns: 150px for image, 1fr for text */
    align-items: flex-start; /* Align items to the top */
    gap: 10px; /* Add some gap between image and text */
    margin-bottom: 45px;
  }

  .publication-image {
    margin-right: 10px;
    width: 150px; /* Set a fixed width for the image container */
    height: 150px; /* Set a fixed height for the image container */
    overflow: hidden; /* Hide any overflowing content within the container */
  }

  .publication-image img {
    width: 100%; /* Ensure the image fills the container horizontally */
    height: 100%; /* Ensure the image fills the container vertically */
    object-fit: cover; /* Maintain aspect ratio and crop if necessary */
  }

  .publication-details {
    display: inline-block;
    vertical-align: top;
    flex-grow: 1; /* Expand to fill available space */
  }
</style>
</head>
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-J4XRR1S1L4"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-J4XRR1S1L4');
</script>
<body>

<!-- pub 1 -->
<div class="publication">
  <div class="publication-image">
    <img src="https://raw.githubusercontent.com/elynluo/elynluo.github.io/master/_publications/senile_plaque.png" alt="Sulfur" width="150" height="150">
  </div>
  <div class="publication-details">
    <font size="4">
      <a href="https://doi.org/10.1364/OL.42.004247" style="text-decoration: none;">
        <span style="color: #191717;">
          <strong>
            1. Label-free brainwide visualization of senile plaque using cryo-micro-optical sectioning tomography
          </strong>
        </span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: #A4907C;">
        <span style="color: #213555;"><strong>Yilin Luo*,</strong></span> , Anle Wang*, Mengmeng Liu, Tian Lei, Xiaochuan Zhang, Zhaobing Gao, Hualiang Jiang, Hui Gong, and Jing Yuan
      </span>
    </font>
    <br>
    <font size="3" style="font-family: 'Font', Calibri;">
      <a style="text-decoration: none;">
        <span style="color: #B2533E;"> Optics Letters, Vol. 42, Issue 21, pp. 4247-4250 (2017) </span>
      </a>
      <a href="https://github.com/elynluo/elynluo.github.io/blob/master/_publications/Sulfur_dioxide_gas-sensitive.txt" style="text-decoration: none;">
        &nbsp; &nbsp; <span style="color: #B5CB99;">(BibTex)</span>
      </a>
    </font>
    <br>
    <font size="3">
      <span style="color: gray;">
        we develop cryo-micro-optical sectioning tomography (cryo-MOST) to capture intrinsic fluorescence distribution of senile plaques at a micrometer-level resolution in the whole brain.
      </span>
    </font>
  </div>
</div>


<font size="2">
  <br>
  <span style="color: gray;">
    Updated on Aug. 22, 2024
  </span>
</font>




<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=feZDslgAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %} -->

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->