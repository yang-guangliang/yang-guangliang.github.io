---
layout: default
title: home
---

<style>
  .hero-container {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    padding: 2rem;
  }

  .main-title {
    font-size: clamp(6rem, 20vw, 12rem);
    font-weight: 900;
    letter-spacing: -0.04em;
    margin: 0;
    color: #000;
    line-height: 0.9;
  }

  .coming-soon {
    font-size: clamp(1.5rem, 4vw, 2.5rem);
    color: #aaa;
    margin: 3rem 0 5rem 0;
    font-weight: 300;
  }

  .tagline {
    font-size: clamp(1.5rem, 3.5vw, 2.5rem);
    color: #666;
    font-weight: 300;
    max-width: 800px;
    text-align: center;
    line-height: 1.5;
  }

  .highlight {
    color: #000;
    font-weight: 400;
  }
</style>

<div class="hero-container">
  <h1 class="main-title">Yian</h1>
  
  <p class="tagline">
    a pure and safe language with <span class="highlight">provable memory safety</span>
  </p>
</div>