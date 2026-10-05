---
layout: page
title: Research
hide_title: false
---

<style>
.research-publication {
  margin: 0 0 2rem;
}

.research-publication__title {
  margin: 0 0 0.4rem;
  font-size: 1.1em;
  font-weight: 700;
  line-height: 1.45;
}

.research-publication__authors {
  margin: 0 0 0.5rem;
  line-height: 1.5;
}

.research-publication__status,
.research-publication__note {
  margin: 0 0 0.5rem;
  font-size: 0.9em;
}

.research-publication__summary {
  margin: 0.75rem 0 1rem;
  font-size: 0.95em;
  line-height: 1.6;
}

.research-publication__links {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 6px;
  margin: 0.75rem 0 1rem;
}

.research-publication__links a {
  display: inline-flex;
  padding: 0;
  border: 0;
  box-shadow: none;
  text-decoration: none;
}

.research-publication__links img {
  display: block;
  width: auto;
  height: 20px;
  margin: 0;
  border: 0;
  border-radius: 0;
  box-shadow: none;
}

.research-publication__gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 12px;
  max-width: 900px;
  margin: 1rem auto 1.5rem;
}

.research-publication__gallery img {
  display: block;
  width: 100%;
  max-width: 100%;
  height: auto;
  margin: 0;
  border-radius: 6px;
}

@media (max-width: 640px) {
  .research-publication__gallery {
    grid-template-columns: 1fr;
  }
}
</style>

## Preprints

<div class="research-publication">
  <h3 class="research-publication__title">
    Regularized estimation of sparse spectral precision matrices (2024)
  </h3>

  <p class="research-publication__authors">
    <strong>Navonil Deb</strong>, Amy Kuceyeski, Sumanta Basu
  </p>

  <p class="research-publication__summary">
    <strong>TL;DR.</strong>
    In multivariate time series, spectral precision matrices characterize
    the conditional dependence structure among the component series. In
    neuroscience, they can be used to describe functional connectivity
    among brain regions within specific frequency bands. This work develops
    an adaptive method for estimating spectral precision matrices at any
    frequency while accounting for heterogeneity in scale across
    time-series components. We provide theoretical error guarantees in
    high dimensions and introduce a fast, scalable coordinate-descent
    algorithm tailored to the complex-valued setting.
  </p>

  <p class="research-publication__links">
    <a href="https://doi.org/10.48550/arXiv.2401.11128">
      <img
        src="https://img.shields.io/badge/arXiv-b31b1b?logo=arxiv&amp;logoColor=white"
        alt="Read the preprint on arXiv">
    </a>
    <a href="https://github.com/navonildeb/cxreg">
      <img
        src="https://img.shields.io/badge/R%20Package-276DC3?logo=r&amp;logoColor=white"
        alt="View the R package on GitHub">
    </a>
    <a href="{{ '/files/sspm_slides.pdf' | relative_url }}">
      <img
        src="https://img.shields.io/badge/Slides-0A66C2?logo=microsoftpowerpoint&amp;logoColor=white"
        alt="View the presentation slides (PDF)">
    </a>
  </p>

  <!-- Check these alt descriptions against the actual figures. -->
  <div class="research-publication__gallery">
    <img
      src="{{ '/images/sspm/runtime.png' | relative_url }}"
      alt="Runtime comparison for spectral precision matrix estimation"
      loading="lazy">
    <img
      src="{{ '/images/sspm/rmse.png' | relative_url }}"
      alt="Root mean squared error comparison for spectral precision matrix estimation"
      loading="lazy">
    <img
      src="{{ '/images/sspm/scaling.png' | relative_url }}"
      alt="Effect of component scaling on spectral precision matrix estimation"
      loading="lazy">
    <img
      src="{{ '/images/sspm/hcp.png' | relative_url }}"
      alt="HCP data analysis for spectral precision matrix estimation"
      loading="lazy">
  </div>
</div>

<div class="research-publication">
  <h3 class="research-publication__title">
    Counterfactual forecasting for panel data (2025)
  </h3>

  <p class="research-publication__authors">
    <strong>Navonil Deb</strong>, Raaz Dwivedi, Sumanta Basu
  </p>

  <!-- Add this paper's summary and links here; they were not in the excerpt. -->
</div>

## Working Papers

<div class="research-publication">
  <h3 class="research-publication__title">
    Inference for high-dimensional sparse spectral precision matrices
  </h3>

  <p class="research-publication__status">
    <em>In preparation</em>
  </p>

  <p class="research-publication__authors">
    <strong>Navonil Deb</strong><sup>&#42;</sup>,
    Younghoon Kim<sup>&#42;</sup>,
    Sumanta Basu
  </p>

  <p class="research-publication__note">
    <sup>&#42;</sup> Equal contribution
  </p>

  <p class="research-publication__summary">
    <strong>TL;DR.</strong>
    Inference for time-series graphical models in the spectral domain is
    challenging in high dimensions. We develop entrywise confidence
    intervals and hypothesis tests for the entries of spectral precision
    matrices of high-dimensional stationary time series, enabling
    uncertainty quantification and recovery of conditional dependence
    graphs at a fixed frequency.
  </p>
</div>

## Selected Earlier Work

<div class="research-publication">
  <h3 class="research-publication__title">
    Finding optimal cancer treatment using Markov decision process to improve overall health and quality of life (2020)
  </h3>

  <!-- Add this paper's authors, summary, and links here; they were not in the excerpt. -->
</div>
