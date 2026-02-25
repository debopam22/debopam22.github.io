---
title: "Research"
hide_title: true
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

## Manuscripts &nbsp;&amp;&nbsp;&nbsp;Publications



<div class="pub-list">

  <article class="pub-item">
    <h3 class="pub-title">
      Title of the manuscript
    </h3>
    <p class="pub-authors">
      <strong>Debopam Goswami</strong>, authors
    </p>
    <p class="pub-venue">
      <em>In preparation</em>, 2025+
    </p>
    <!-- <div class="pub-links">
      <a class="pub-tag" href="#">arXiv</a>
      <a class="pub-tag" href="#">Code</a>
    </div> -->
  </article>

  <article class="pub-item">
    <h3 class="pub-title">
      Title of the manuscript
    </h3>
    <p class="pub-authors">
      <strong>Debopam Goswami</strong>, authors
    </p>
    <p class="pub-venue">
      <em>Submitted</em>, 2025+
    </p>
    <div class="pub-links">
      <button class="pub-tag pub-abstract-toggle" data-target="abs-swlb">
      Abstract
      </button>
      <a class="pub-tag" href="https://arxiv.org/abs/2504.11636">arXiv</a>
      <a class="pub-tag" href="https://github.com/das-snigdha/S-WLB">Code</a>
      <!-- <a class="pub-tag" href="#">BibTeX</a> -->
  </div>

  <!-- hidden abstract -->
  <div id="abs-swlb" class="pub-abstract">
    About the manuscript.
  </div>
    
  </article>

  <article class="pub-item">
    <h3 class="pub-title">
      Title of the manuscript
    </h3>
    <p class="pub-authors">
      <strong>Debopam Goswami</strong>, authors
    </p>
    <p class="pub-venue">
      <em>Biometrics</em>, 2025
    </p>
    <div class="pub-links">
      <button class="pub-tag pub-abstract-toggle" data-target="abs-msim">
      Abstract
      </button>
      <a class="pub-tag" href="https://doi.org/10.1093/biomtc/ujaf105">DOI</a>
      <a class="pub-tag" href="https://arxiv.org/abs/2507.09057">arXiv</a>
      <a class="pub-tag" href="https://github.com/das-snigdha/BayesSPMSM">Code</a>
      
  </div>

  <!-- hidden abstract -->
  <div id="abs-msim" class="pub-abstract">
    About the manuscript.
  </div>
  </article>

  <article class="pub-item">
    <h3 class="pub-title">
      Title of the manuscript
    </h3>
    <p class="pub-authors">
      <strong>Debopam Goswami</strong>, authors
    </p>
    <p class="pub-venue">
      <em>Journal</em>, 2024
    </p>
    <div class="pub-links">
      <button class="pub-tag pub-abstract-toggle" data-target="abs-hdp">
      Abstract
      </button>
      <a class="pub-tag" href="https://doi.org/10.1080/10618600.2024.2388543">DOI</a>
      <a class="pub-tag" href="https://arxiv.org/abs/2304.09945">arXiv</a>
      <a class="pub-tag" href="https://github.com/das-snigdha/blockedHDP">Code</a>
  </div>

  <!-- hidden abstract -->
  <div id="abs-hdp" class="pub-abstract">
    About the manuscript.
  </div>
  </article>

</div>


<script>
document.addEventListener("click", function (e) {
  if (e.target.matches(".pub-abstract-toggle")) {
    const id = e.target.getAttribute("data-target");
    const box = document.getElementById(id);
    if (box) {
      const isHidden = window.getComputedStyle(box).display === "none";
      box.style.display = isHidden ? "block" : "none";
    }
  }
});
</script>
