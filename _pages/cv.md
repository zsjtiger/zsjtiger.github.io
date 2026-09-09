---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **M.Eng. in Engineering Management**, Beijing Institute of Technology, 2024–2026
  * School of Management and Economics
* **B.S.**, Peking University, 2012–2016
* **B.Eng. in Computer Software Engineering**, Beijing University of Posts and Telecommunications, 2007–2011

---

## Work Experience

**CrossNow** — Founder & CTO *(Nov 2023 – Present)*
* Built a multi-tenant pharmaceutical commercialization SaaS and MaaS platform from the ground up on AWS EKS
* Platform covers HCP profiling, SFE modules, LLM agent capabilities, and multi-tenant schema-isolation architecture
* Designed and implemented MCP server support, Pydantic AI-based visit management agents, and PPT generation agents

**Veeva Systems** — Principal Software Engineer *(Apr 2019 – Jan 2024)*
* Designed and built CRM SaaS on AWS for pharmaceutical clients
* Architected multi-tenant management based on Docker
* Built high-availability SaaS platform and automated CI/CD release platform with Jenkins

**Veeva Systems** — Senior Software Engineer *(May 2016 – Jan 2024)*

**Servier** — Senior Software Developer *(Mar 2014 – May 2016)*
* Designed and developed SFE and CRM systems
* Built doctor survey/classification processing and territory maintenance tools

**Pfizer (Contractor)** *(Aug 2010 – Mar 2014)*
* Performance optimization of MDM (Master Data Management) covering products, hospitals, pharmacies, distributors
* Developed Barcode and DCS systems for product flow data and reporting

---

## Skills

* **ML / Training** — PyTorch, torchtitan (HSDP), vLLM, SGLang, llama-server; AWQ · GPTQ 
* **Languages** — Python, SQL, JavaScript, C++,Rust
* **Infrastructure** — AWS EKS, Route53, IAM/IRSA, Kubernetes,cuda
* **Frontend** — React, JavaScript

---

## Publications

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

---

## Talks

{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
