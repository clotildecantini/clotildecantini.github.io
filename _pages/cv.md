---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version of this CV is available [here](/files/cv.pdf).

Education
======
* **M.Sc. in Operations Research (MPRO)**, ENSTA Paris, 2024–2025
  * Coursework: optimization and graphs, metaheuristics, convex optimization, deep learning for combinatorial optimization, advanced combinatorial optimization, constraint programming.
* **M.Sc. in Mathematical and Computer Engineering**, École des Ponts ParisTech, 2021–2023
  * Coursework: software engineering, deep learning, machine learning, convex optimization, information processing and machine learning, advanced programming and algorithms, operations research, stochastic processes and applications.
* **Preparatory class MPSI/PSI\***, Lycée Montaigne, Bordeaux, 2019–2021
* **Baccalauréat**, scientific track, highest honors, Lycée Beaulieu, Cognac, 2019

Research and work experience
======
* **Pre-PhD research assistant**, CERMICS, École des Ponts ParisTech (May 2026 – December 2026)
  * Airline revenue management
  * Competition-aware dynamic pricing algorithms

* **Deep learning research intern**, LIPADE, Université Paris Cité (August – December 2025)
  * Researched and implemented self-supervised learning methods for satellite image time series (SITS) and videos
  * Built an end-to-end training pipeline for representation learning and temporal analysis of spatio-temporal data, using PyTorch on the Jean Zay supercomputer
  * Benchmarked models against state-of-the-art baselines

* **Operations research intern**, SNCF (February – July 2025)
  * Developed heuristics and metaheuristics for real-time railway traffic management and conflict resolution
  * Fixed bugs and implemented new features in a real-time railway traffic simulator
  * Designed and tested an optimization pipeline in Python, reducing scheduling delays in simulation scenarios

* **Machine learning / AI intern**, Swiss Life, Zürich (January – July 2024)
  * Contributed to a company-wide AI transformation initiative; deployed ML classifiers for customer feedback categorization and sentiment analysis
  * Conducted a side research project on exact solutions for liquid-time-constant neural networks with piecewise linear signals
  * First author of a research paper accepted for publication (IEEE)

* **Machine learning research intern**, Callyope, Paris (June – December 2023)
  * Designed and implemented an end-to-end speech-processing pipeline secured with fully homomorphic encryption (FHE) and compatible with quantization schemes
  * Benchmarked the CKKS and TFHE schemes
  * Created quantized methods for audio feature extraction
  * Contributed to a research article and a blog post on Gammatone features

* **Private tutor** (2021 – present)
  * Mathematics, computer science, physics and French for high school students preparing the baccalauréat

Skills
======
* **Programming**: Python, C++, MATLAB, Julia
* **Tools**: Git/GitHub, Google Cloud, Azure ML, TensorFlow, PyTorch, Jean Zay supercomputer (CNRS/IDRIS)
* **Languages**: French (native), English (fluent, TOEIC 880), German (intermediate, DSD B1)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>