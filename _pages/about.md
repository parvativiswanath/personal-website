---
layout: about
title: About
permalink: /

profile:
  align: right
  image: parvati_profile.jpeg
  image_circular: false # crops the image to make it circular
  more_info: >
    <div class="profile-contact-icons" aria-label="Contact links">
      <a href="mailto:bsg5ec@virginia.edu" aria-label="Email" title="Email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://www.linkedin.com/in/parvati-viswanathan-359964214" aria-label="LinkedIn" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
      <a href="https://github.com/parvativiswanath" aria-label="GitHub" title="GitHub"><i class="fa-brands fa-github"></i></a>
    </div>

selected_papers: false # rendered below with a custom homepage heading
social: false # contact icons are displayed below the profile image instead

announcements:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a MS (Thesis) student at the [University of Virginia](https://www.virginia.edu/), advised by [Ferdinando Fioretto](https://nandofioretto.github.io/). Before my MS, I spent one year as a Pre-Doctoral Research Fellow at the [Indian Institute of Science Education and Research (IISER)](https://www.iisertvm.ac.in/) Thiruvananthapuram, where I worked with [Mainak Adhikari](https://www.iisertvm.ac.in/faculty/mainak). 

I am broadly interested in trustworthy AI and agentic AI. Specifically, I am interested in long-term memory in agents, agentic AI safety, self-evolving agents, and more recently, interpretability and contextual integrity. Previously at IISER, I also worked on addressing data heterogeneity and slower convergence in Federated Learning, and validating these algorithms on real autonomous rover systems. 


### Publications and Preprints {#publications-and-preprints}

<ul class="home-publications">
  <li>
    <div class="publication-title"><a href="https://seabench-endogenous-misalignment.github.io/">SEABench: Benchmarking Endogenous Misalignment in Self-Evolving Agents</a></div>
    <div class="publication-authors">Saswat Das, <strong>Parvati Viswanathan</strong>, Daniel Donnelly, Chang Huang, Sahar Abdelnabi, and Ferdinando Fioretto</div>
    <div class="publication-venue">arXiv Preprint, 2026</div>
  </li>
  <li>
    <div class="publication-title"><a href="https://ieeexplore.ieee.org/abstract/document/11727881">Federated Learning Using Nesterov's Momentum for Non-IID Data Handling in Edge Networks</a></div>
    <div class="publication-authors"><strong>Parvati Viswanathan</strong> and Mainak Adhikari</div>
    <div class="publication-venue">IEEE Transactions on Computational Social Systems, 2026</div>
  </li>
</ul>

<style>
  body {
    padding-bottom: 0;
  }

  footer {
    display: none;
  }

  .navbar-brand .font-weight-bold,
  .post-title .font-weight-bold {
    font-weight: inherit !important;
  }

  .profile {
    width: 23%;
  }

  .profile figure,
  .profile picture {
    display: block;
    width: 100%;
  }

  .profile img {
    width: 100%;
    height: auto;
  }

  #publications-and-preprints {
    scroll-margin-top: 5rem;
    font-size: 1.15rem;
    font-weight: 600;
  }

  .home-publications {
    padding-left: 1.25rem;
  }

  .home-publications li {
    margin-bottom: 1.5rem;
  }

  .publication-title {
    margin-bottom: 0.125rem;
    font-weight: 600;
  }

  .publication-authors {
    margin-bottom: 0.125rem;
    color: #333;
    font-size: 0.92rem;
  }

  .publication-venue {
    margin-bottom: 0.25rem;
    color: #666;
    font-size: 0.9rem;
    font-style: italic;
  }

  .publication-badge {
    display: inline-block;
    padding: 0.0625rem 0.4375rem;
    border-radius: 0.1875rem;
    background: #fff4e0;
    color: #8b5c00;
    font-size: 0.82rem;
  }

  .profile-contact-icons {
    display: flex;
    justify-content: center;
    gap: 0.9rem;
    margin-top: 0.75rem;
    font-size: 1.35rem;
  }

  .profile-contact-icons a {
    color: var(--global-text-color);
    line-height: 1;
  }

  .profile-contact-icons a:hover {
    color: var(--global-theme-color);
  }

  @media (max-width: 575.98px) {
    .profile {
      float: none !important;
      width: 58%;
      margin: 0 auto 1.5rem !important;
    }
  }
</style>


