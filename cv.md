---
layout: cv
title: CV
---

# Curriculum Vitæ

{% include contact.html %}

---
<center>PROFESSIONAL EXPERIENCE</center>

## Lockheed Martin

<div style="display: flex; justify-content: space-between;">
<span><em>Tech Lead, Senior Staff ML Enginer</em></span>
<span>2022-present</span>
</div>
Brooklyn, NY

Tech lead for the Lockheed Martin AI Consulting team. Working across all Lockheed Martin business areas to prototype, build, and deploy performant AI solutions. Teaching as I go.

* Leads 26 Reseach and ML Engineers.
* Leads ML for "internal chatGPT". Entirely on-prem for compliance with sensative data types, serving 100,000 internal users.
    * Project saved $X00,000 last year (estimated using mid-year OpenAI token prices).
    * core contributer for the `next.js` front-end.
    * contributer to wire-compatible OpenAI Assistants API in `golang`.
    * serving 20+ models with `vllm`, `TGI`, and `kserve`.
* Led AI for Firefighting reinforcement learning team.
    * Built state-of-the-art fire simulation and fire propogation models in pure `numpy`.
    * Architected a novel hierarchical reinforcement learning system. Implenemnted in `pytorch` and `rllib`.
    * Presented this work at 2024 Ray Summit.
* Led Software Copilot projects, which included:
    * Code translation / modernization focused on C++, Rust.
    * Unit test generation in ~100,000 loc C++ or python codebases.
    * Python documentation generator: automatically keep your python codebase documented and up-to-date.

<div style="display: flex; justify-content: space-between;">
<span><em>Staff ML Enginer</em></span>
<span>2021-2022</span>
</div>
Washington, DC

Joined the enterprise AI Consulting team (office of CTO).
Project lead and staff ML Engineer on work spanning all five Lockheed Martin business areas.

* Led technical strategy and implementation for $X million AI R&D project focused on anomaly detection on petabyte-scale telemetry data.
* Taught corporation-wide master classes in deep learning and AI.

<div style="display: flex; justify-content: space-between;">
<span><em>Staff Data Scientist</em></span>
<span>2021-2022</span>
</div>
Washington, DC

* Grew Data Science team from 3 to 7 engineers.
* Built NLP system for Flight Safety Team using spacy and 🤗 transformers.
    * Reduced engineering labor time 10x (hours per report to minutes).
* Built clustering solution for manufacturing defects.
    * Analyzes 500,000+ defects, daily, across 20 manufacturing sites.

<div style="display: flex; justify-content: space-between;">
<span><em>Senior Data Scientist</em></span>
<span>2019-2021</span>
</div>
Washington, DC

Led a Data Science team focused on rotary and mission systems. Making the birds and the business faster, safer, and more reliable.

* Built analytics and machine learning models for Facilities, analyzing
10,000 buildings sensors for anomalies.
    * Identified approximately $X00,000 in cost reduction in 2020.
    * Won two 2020 Excellence awards for this project.

## Food and Drug Administration

<div style="display: flex; justify-content: space-between;">
<span><em>Biomedical Enginer</em></span>
<span>2014-2019</span>
</div>
Washington, DC

* Mined and analyzed data from hospital sources to automate safety signal detection, improve strategy, and support FDA policy development on CMMS Data Capture Project.
    * Led project from "Pilot" to Commisionar's "Critical Path" award.
    * Used clustering, LDA, XGBoost, and neural networks.
    * Won 2018 Excellence Award

* Triaged reports of medical device failure, investigated device failure mode and forensic testing, elevating critical failures to FDA’s Safety Signal working groups. Presented these reviews, conclusions, opinions, and recommendations to appropriate scientific review panels.

* Division subject matter expert in Cardiovascular Plumbing device area, contributed to FDA Cardiovascular Device Safety working group in safety communications, safety actions.

* Interfaced with over 60 hospitals, acting as primary FDA contact, fielded regulatory questions.

* Supported and provided feedback to FDA’s Digital Health team in two policy areas: cybersecurity, artificial intelligence/machine learning.

* Researched and wrote technical articles for the Journal of Clinical Engineering, most recent on FDA’s Unique Device Identifier database for clinical engineers, published in April, 2018.

## The Children's Hospital of Philadelphia

<div style="display: flex; justify-content: space-between;">
<span><em>Laboratory Technician</em></span>
<span>2010-2013</span>
</div>
Philadelphia, PA

Worked summer and winters in Dr. Kushner's T1DM laboratory. 

* Confirmed persistent ß-cells even in long-standing T1DM patients via immunohistochemisty, high-throughput microscopy.

* Investigated causes of persistence including turnover, regional immunity, and ⍺-cell transdifferentiation. 

* Discovered novel relationship between disease duration and elevated T1DM endocrine replication.

* Trained four lab techs in basic lab techniques, immunohistochemical staining, high throughput microscopy. Coordinated team of two interns and a fellow Lab Technician investigating ß-cell persistence.

---
<center>EDUCATION</center>


<div style="display: flex; justify-content: space-between; align-items: center;">
<h2 style="margin: 0;">Brown University</h2>
<span>2010-2014</span>
</div>
<em>B.Sc. in Biomedical Engineering</em>

* Senior capstone project: “Coherence of polychronic firing patterns in neural networks with various 3D architectures”.
    * Built a neural network in MATLAB using the Izhikevich STDP model, optimized network for variables including synaptic strength, conductance, and runtime under to biological plausible constraints.
    * Investigated temporal coherence of neuron “braids” in various 3D architectures.
* Significant coursework includes Transport and Biotransport Processes, Neuroengineering, Computational Neuroscience, Biomechanics, Biophotonics, Biomaterials, Instrumentation Design

<div style="display: flex; justify-content: space-between; align-items: center;">
<h2 style="margin: 0;">University of Glasgow</h2>
<span>2012</span>
</div>
<em>Course in Biomedical Engineering</em>

Studied abroad in Glasgow, Scotland in the fall of 2012.

* Significant coursework includes Fluid Dynamics, Tissue Engineer, Professional Bagpipe (not a joke)

---
<center>AWARDS</center>
<br>
{% include title-date.html
title="<b>Facilities Excellence Award</b>, <em>Lockheed Martin</em>"
date="2020" %}
for outstanding work on the SmartBuilding initiative.


{% include title-date.html
title="<b>ESH Excellence Award</b>, <em>Lockheed Martin</em>"
date="2020" %}
for outstanding work on the SmartBuilding initiative.


{% include title-date.html
title="<b>CDRH Excellence in Postmarket Safety Award</b>, <em>FDA</em>"
date="2018" %}
for excellence in enhancing and taking new approaches to safety signal detection.

{% include title-date.html
title="<b>CDRH Excellence in Customer Service Award</b>, <em>FDA</em>"
date="2018" %}
for excellence in providing consistent customer service to internal and external stakeholders.

---
<center>SCHOLARSHIP</center>

<br>
{% include title-date.html
title="<b>Deep Reinforcement Learning for Wildland Fire Management</b>"
date="Oct 2024" %}
<em>Ray Summit -- San Fransisco, CA</em>

* Oral presentation on our multi-agent, hierarchical reinforcement learning approach.
* Full presentation available upon request.

{% include title-date.html
title="<b>Highly Proliferative ⍺-Cell-Related Islaet Endocrine Cells in Human Pancreata</b>"
date="Apr 2018" %}
Lam CJ, Cox AR, Jacobson DR, Rankin MM, Kushner JA.
Diabetes 2018 Apr; 67(4):674-686. doi: 10.2337/db17-1114.

{% include title-date.html
title="<b>Unique Device Identifier Database Integration for Clinical Engineers</b>"
date="Apr 2018" %}
Jacobson, Daniel R.
Journal of Clinical Engineering. 443(2):71-74, April/June 2018.
doi: 10.1097/JCE.0000000000000264

{% include title-date.html
title="<b>B-Cells Persist in T1D Pancreata Without Evidence of Ongoing B-Cell Turnover or Neogenesis</b>"
date="Aug 2017" %}
Lam CJ, Jacobson DR, Rankin MM, Cox AR, Kushner JA.
Journal of Clinical Endocrinology & Metabolism. 2017 Aug 1;102(8):2647-2659.
doi: 10.1210/jc.2016-3806

{% include title-date.html
title="<b>American Diabetes Association’s 72 Scientific Sessions</b>"
date="Jun 2012" %}
<em>Philadelphia, PA</em>

* Poster Session: ß-cells persist in some T1DM pancreata without evidence of ß-cell turnover nor insulin- glucagon co-expression.
* One of eight abstracts selected guided audio showcase before chief
researchers in the field.

{% include title-date.html
title="<b>Network for Pancreatic Organ Donors Annual Conference</b>"
date="Jan 2012" %}
<em>Miami, FL</em>

* Oral Presentation and Poster Session: ß-cells persist in some T1DM pancreata without evidence of ß-cell turnover nor insulin-glucagon co-expression.