---
layout: page
permalink: /talks/
title: talks
description: Conference talks and posters.
nav: true
nav_order: 6
---

<div class="talks-list">

  <p class="talks-intro">It is possible that we have met at one of these conferences:</p>

  <section class="talk-year">
    <h2>2026</h2>

    <div class="talk-entry">
      <div class="talk-heading">
        <span class="talk-event">Optimization 2026</span>
        <span class="talk-type">talk</span>
      </div>
      <div class="talk-title">Symmetric gauge theory for cutting-plane methods in semidefinite programming</div>
      <div class="talk-meta">Lisbon, Portugal · July 20–22, 2026</div>
      <div class="talk-links">
        <a href="https://optimization2026.iseg.ulisboa.pt">conference</a>
      </div>
    </div>

    <div class="talk-entry">
      <div class="talk-heading">
        <span class="talk-event">Journées SMAI-MODE 2026</span>
        <span class="talk-type">poster</span>
      </div>
      <div class="talk-title">Spectral-gauge cuts for semidefinite programming</div>
      <div class="talk-meta">Nice, France · March 18–20, 2026</div>
      <div class="talk-links">
        <a href="https://mode2026.sciencesconf.org">conference</a>
      </div>
    </div>
  </section>

  <section class="talk-year">
    <h2>2025</h2>

    <div class="talk-entry">
      <div class="talk-heading">
        <span class="talk-event">44th National Congress of Applied and Computational Mathematics</span>
        <span class="talk-type">talk</span>
      </div>
      <div class="talk-title">An extension of Kac’s lemma for Furstenberg’s ergodic multiple recurrences</div>
      <div class="talk-meta">Rio de Janeiro, Brazil · September 15–19, 2025</div>
      <div class="talk-links">
        <a href="https://eventos.galoa.com.br/cnmac-2025/page/5559-home">conference</a>
      </div>
    </div>

    <div class="talk-entry">
      <div class="talk-heading">
        <span class="talk-event">16th Global Optimization Workshop</span>
        <span class="talk-type">talk</span>
      </div>
      <div class="talk-title">On computational evaluation of lower bounds for the fractional quadratic program over the standard simplex</div>
      <div class="talk-meta">Stockholm, Sweden · September 2–5, 2025</div>
      <div class="talk-links">
        <a href="https://sites.google.com/view/stogo25/">conference</a>
      </div>
    </div>
  </section>

</div>

<style>
  .talks-list {
    max-width: 860px;
  }

  .talks-intro {
    margin-bottom: 2.2rem;
    color: var(--global-text-color-light);
  }

  .talk-year {
    display: grid;
    grid-template-columns: 5.5rem minmax(0, 1fr);
    column-gap: 1.6rem;
    margin-bottom: 2.5rem;
  }

  .talk-year > h2 {
    margin: 0;
    padding-top: 0.1rem;
    font-size: 1rem;
    font-weight: 600;
    color: var(--global-text-color-light);
  }

  .talk-entry {
    grid-column: 2;
    position: relative;
    padding: 0 0 1.65rem 1.2rem;
    border-left: 1px solid var(--global-divider-color);
  }

  .talk-entry:last-child {
    padding-bottom: 0;
  }

  .talk-entry::before {
    content: "";
    position: absolute;
    left: -4px;
    top: 0.42rem;
    width: 7px;
    height: 7px;
    border-radius: 50%;
    background: var(--global-theme-color);
  }

  .talk-heading {
    display: flex;
    align-items: baseline;
    flex-wrap: wrap;
    gap: 0.45rem 0.7rem;
    margin-bottom: 0.2rem;
  }

  .talk-event {
    font-weight: 600;
  }

  .talk-type {
    font-size: 0.78rem;
    text-transform: lowercase;
    color: var(--global-text-color-light);
  }

  .talk-title {
    margin: 0.12rem 0 0.25rem;
    font-style: italic;
    line-height: 1.45;
  }

  .talk-meta,
  .talk-links {
    font-size: 0.9rem;
    color: var(--global-text-color-light);
  }

  .talk-links {
    margin-top: 0.3rem;
  }

  .talk-links a {
    color: var(--global-theme-color);
    text-decoration: none;
  }

  .talk-links a:hover {
    text-decoration: underline;
  }

  .talk-links span {
    margin: 0 0.25rem;
  }

  @media (max-width: 576px) {
    .talk-year {
      display: block;
    }

    .talk-year > h2 {
      margin-bottom: 1rem;
      font-size: 1.05rem;
    }

    .talk-entry {
      margin-left: 0.25rem;
      padding-left: 1rem;
    }
  }
</style>
