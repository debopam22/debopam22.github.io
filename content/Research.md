---
title: "Research"
hide_title: true
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

## Manuscripts &nbsp;&amp;&nbsp;&nbsp;Publications



<div class="pub-list">

  <article class="pub-item">
    <h3 class="pub-title">
      Deep generative conditional density regression for inference in complex surveys
    </h3>
    <p class="pub-authors">
      <strong>Snigdha Das</strong>, Dipankar Bandyopadhyay, Debdeep Pati
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
      Scalable efficient inference in complex surveys through targeted resampling of weights
    </h3>
    <p class="pub-authors">
      <strong>Snigdha Das</strong>, Dipankar Bandyopadhyay, Debdeep Pati
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
    Survey data often arises from complex sampling designs, such as stratified or multistage sampling, with unequal inclusion probabilities. When sampling is informative, traditional inference methods yield biased estimators and poor coverage. Classical pseudo-likelihood based methods provide accurate asymptotic inference but lack finite-sample uncertainty quantification and the ability to integrate prior information. Existing Bayesian approaches, like the Bayesian pseudo-posterior estimator and weighted Bayesian bootstrap, have limitations; the former struggles with uncertainty quantification, while the latter is computationally intensive and sensitive to bootstrap replicates. To address these challenges, we propose the Survey-adjusted Weighted Likelihood Bootstrap (S-WLB), which resamples weights from a carefully chosen distribution centered around the underlying sampling weights. S-WLB is computationally efficient, theoretically consistent, and delivers finite-sample uncertainty intervals which are proven to be asymptotically valid. We demonstrate its performance through simulations and applications to nationally representative survey datasets like NHANES and NSDUH.
  </div>
    
  </article>

  <article class="pub-item">
    <h3 class="pub-title">
      A monotone single index model for spatially referenced multistate current status data
    </h3>
    <p class="pub-authors">
      <strong>Snigdha Das</strong>, Minwoo Chae, Debdeep Pati, Dipankar Bandyopadhyay
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
    Assessment of multistate disease progression is commonplace in biomedical research, such as, in periodontal disease (PD). However, the presence of multistate current status endpoints, where only a single snapshot of each subject’s progression through disease states is available at a random inspection time after a known starting state, complicates the inferential framework. In addition, these endpoints can be clustered, and spatially associated, where a group of proximally located teeth (within subjects) may experience similar PD status, compared to those distally located. Motivated by a clinical study recording PD progression, we propose a Bayesian semiparametric accelerated failure time model with an inverse-Wishart proposal for accommodating (spatial) random effects, and flexible errors that follow a Dirichlet process mixture of Gaussians. For clinical interpretability, the systematic component of the event times is modeled using a monotone single index model, with the (unknown) link function estimated via a novel integrated basis expansion and basis coefficients endowed with constrained Gaussian process priors. In addition to establishing parameter identifiability, we present scalable computing via a combination of elliptical slice sampling, fast circulant embedding techniques, and smoothing of hard constraints, leading to straightforward estimation of parameters, and state occupation and transition probabilities. Using synthetic data, we study the finite sample properties of our Bayesian estimates, and their performance under model misspecification. We also illustrate our method via application to the real clinical PD dataset. 
  </div>
  </article>

  <article class="pub-item">
    <h3 class="pub-title">
      Blocked Gibbs sampler for hierarchical Dirichlet processes
    </h3>
    <p class="pub-authors">
      <strong>Snigdha Das</strong>, Yabo Niu, Yang Ni, Bani K. Mallick, Debdeep Pati
    </p>
    <p class="pub-venue">
      <em>Journal of Computational and Graphical Statistics</em>, 2024
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
    Posterior computation in hierarchical Dirichlet process (HDP) mixture models is an active area of research in nonparametric Bayes inference of grouped data.  Existing literature almost exclusively focuses on the Chinese restaurant franchise (CRF) analogy of the marginal distribution of the parameters, which can mix poorly and has a quadratic complexity with the sample size. A recently developed slice sampler allows for efficient blocked updates of the parameters, but is shown to be statistically unstable in our article. We develop a blocked Gibbs sampler that employs a truncated approximation of the underlying random measures to sample from the posterior distribution of HDP, which produces statistically stable results, is highly scalable with respect to sample size, and is shown to have good mixing. The heart of the construction is to endow the shared concentration parameter with an appropriately chosen gamma prior that allows us to break the dependence of the shared mixing proportions and permits independent updates of certain log-concave random variables in a block. <em>En route</em>, we develop an efficient rejection sampler for these random variables leveraging piece-wise tangent-line approximations.
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