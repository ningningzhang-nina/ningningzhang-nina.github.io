---
layout: default
title: Conferences
---

<style>
.conference-card {
  max-width: 800px;
  margin: 20px auto;
  padding: 20px;
  background: white;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  transition: transform 0.2s ease;
}

.conference-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.15);
}

.conference-link {
  display: block;
  text-align: center;
  margin-bottom: 15px;
}

.conference-image {
  width: 100%;
  height: auto;
  border-radius: 6px;
  max-height: 300px;
  object-fit: cover;
  border: 1px solid #e1e4e8;
  transition: opacity 0.3s ease;
}

.conference-link:hover .conference-image {
  opacity: 0.9;
}

.conference-title {
  font-size: 1.4em;
  color: #24292e;
  margin: 15px 0 8px;
  text-align: center;
}

.conference-description {
  color: #586069;
  line-height: 1.6;
  text-align: center;
  margin-bottom: 15px;
}

.conference-details {
  text-align: center;
  font-size: 0.9em;
  color: #6a737d;
}

.conference-date {
  font-weight: bold;
  color: #0366d6;
}
</style>

<div class="conference-card">
  <a href="https://icml.cc" class="conference-link" target="_blank">
    <img src="/assets/Images/hku.jpeg" alt="ICML 2023 Conference" class="conference-image">
  </a>
  <h2 class="conference-title">ICML 2023 Workshop on Causal ML</h2>
  <p class="conference-description">
    Presented our research on <strong>causal discovery methods for financial time series</strong>. 
    This workshop brought together researchers from academia and industry to discuss the latest advances in causal machine learning.
  </p>
  <div class="conference-details">
    <span class="conference-date">July 23-24, 2023</span> | Honolulu, Hawaii
  </div>
</div>

