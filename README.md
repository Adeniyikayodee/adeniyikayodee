# Kayode Adeniyi

**PhD researcher in Engineering at Imperial College London** working on model-data alignment and uncertainty quantification in machine learning, with water risk as the setting where the ground truth is thin, missing or quietly wrong.

[![Email](https://img.shields.io/badge/Email-adeniyikayode22%40gmail.com-1f2937?style=flat-square&logo=gmail&logoColor=white)](mailto:adeniyikayode22@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kadeniyi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kadeniyi)
[![X](https://img.shields.io/badge/X-@mkbadeniyi-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/mkbadeniyi)
[![freeCodeCamp](https://img.shields.io/badge/freeCodeCamp-author-0A0A23?style=flat-square&logo=freecodecamp&logoColor=white)](https://www.freecodecamp.org/news/author/mkbadeniyi/)
[![LogRocket](https://img.shields.io/badge/LogRocket-author-764ABC?style=flat-square)](https://blog.logrocket.com/author/kayodeadeniyi/)

---

## About

I trained as a geographer at the University of Ilorin and spent my early career mapping floods, farms and public infrastructure across Nigeria, first as a GIS analyst and later as a geospatial software engineer. That work moved into full stack engineering at Flutterwave, where I designed enterprise payment integrations, and then to the London School of Economics for an MSc in Management of Information Systems and Digital Innovation, where I worked on machine learning for satellite imagery and flood risk.

My doctoral research asks how machine learning can inform the design of hardware sensors for measuring global water risk, so that we know how much fresh water remains and where it is. Running through all of it is a question I care about more than any single application, which is whether a model and the data it was trained and tested on actually agree about the world.

## Research interests

- **Model-data alignment as a source of uncertainty.** A model can only be as certain as its agreement with the data allows, so I study where that agreement breaks, through target leakage, hidden provenance and benchmarks whose shortcuts survive repair, and how to quantify the uncertainty those gaps leave behind
- **Uncertainty quantification under absent ground truth**, including how much evidence a single human observation adds to a spatial decision when no validation set exists
- **Reliability of AI agents** that call scientific tools, where units, vertical datums and record quality are silently dropped at the tool boundary
- **Machine learning for water risk**, from sensor design to community-sensed flood warning

## Awards and recognition

- **Most Practical Project**, MSc Management of Information Systems and Digital Innovation, London School of Economics
- **Winner, Luminance Challenge**, Hack_the_Law Cambridge 2025, with [Risk IQ](https://hackthelaw-cambridge.com/hackathon-2025/), a contract risk platform that tracks regulatory and economic events and scores their impact on individual contract clauses
- **Winner, Phelan US Centre AI Essay Competition 2025** at LSE, for [*AI in the US: The Next Space Race or the Next Subprime Crisis?*](https://blogs.lse.ac.uk/usappblog/2025/03/17/ai-in-the-us-the-next-space-race-or-the-next-subprime-crisis/), which I later presented to members of the UK Parliament
- **Fully funded PhD** in Engineering at Imperial College London
- **freeCodeCamp top open source contributor** in 2022 and 2025

## Selected work

| Project | What it does |
| --- | --- |
| [**quantity-guard**](https://github.com/Adeniyikayodee/quantity-guard) | Enforces units, vertical datums, timezones and record quality at an AI agent's tool boundary. In a benchmark of 4,288 runs across eleven models, every model that reached the tool passed cubic feet per second into a cubic metres parameter without converting it, and nothing in the output revealed the error. |
| [**gagelink**](https://github.com/Adeniyikayodee/gagelink) | An MCP server that gives agents hydrology data from USGS, NOAA, Hub'Eau, the UK Environment Agency and SWOT, with every value carrying its unit, datum and provenance. Available on PyPI. |
| [**leakage-benchmarks**](https://github.com/Adeniyikayodee/leakage-benchmarks) | Code for the paper *Removing Data Leakage Does Not Fix Benchmarks*, which shows that when shortcut pathways are redundant, repairing one leak leaves the metric unchanged and the benchmark no more informative than before. |
| [**derives-from**](https://github.com/Adeniyikayodee/dependency_manifest) | A dependency manifest for public statistical data, with a linter that rejects covariates your prediction target was built from. Archived on [Zenodo](https://doi.org/10.5281/zenodo.22274757). |
| [**Reliability-Caps**](https://github.com/Adeniyikayodee/Reliability-Caps) | Measures how much evidence one resident's report carries about whether a zone of a settlement is in hazard, given a partition learned from satellite representations. |
| [**fathom**](https://github.com/Adeniyikayodee/fathom) | Parametric flood insurance that settles on resident reports for dense settlements in Lagos where a satellite trigger cannot see the water. |

## Talks and tutorials

- **Community-Sensed Flood Warning**, tutorial for the Tackling Climate Change with Machine Learning workshop at NeurIPS 2026, using a geospatial foundation model as the prior and residents as the posterior ([notebook](https://github.com/Adeniyikayodee/NeurIPS-2026-Workshop))
- **Mapping floods where there is no ground truth**, London Geo Meetup #5 at Birkbeck, 12 August 2026 ([code](https://github.com/Adeniyikayodee/LondonGeoMeetUp))

## Writing

I have written for freeCodeCamp since 2022 and was named one of its top open source contributors in both 2022 and 2025. At LogRocket I write about product management, with a recent focus on AI risk, compliance and how teams should run AI products.

**freeCodeCamp**

- [How to Detect Hidden Target Leakage in Public Datasets with Python and a Dependency Graph](https://www.freecodecamp.org/news/how-to-detect-hidden-target-leakage-in-public-datasets-with-python-and-a-dependency-graph/)
- [How to Manage Context Files in Your Codebase and Get Better Output From AI Coding Agents](https://www.freecodecamp.org/news/how-to-manage-context-files-in-your-codebase-and-get-better-agent-output/)
- [How Feature Flags and Role-Based Access Control Can Help Secure Your DevOps Process](https://www.freecodecamp.org/news/feature-flags-and-role-based-access-control-devops/)
- [How to Implement Infrastructure as Code with AWS](https://www.freecodecamp.org/news/how-to-implement-infrastructure-as-code-with-aws/)

**LogRocket**

- [How to add a harm score to product prioritization](https://blog.logrocket.com/product-management/harm-score-product-prioritization/)
- [Stress-testing AI products: A red-teaming playbook](https://blog.logrocket.com/product-management/stress-testing-ai-products-red-teaming-playbook/)
- [AI compliance: A core product competency you shouldn't skip](https://blog.logrocket.com/product-management/ai-compliance-core-product-competency-you-shouldnt-skip/)
- [How to run your AI products like a portfolio, not a project](https://blog.logrocket.com/product-management/how-to-run-your-ai-products-portfolio-not-project/)
- [Why you should treat data as inventory, not infrastructure](https://blog.logrocket.com/product-management/treat-data-inventory-not-infrastructure/)

The full lists are on my [freeCodeCamp](https://www.freecodecamp.org/news/author/mkbadeniyi/) and [LogRocket](https://blog.logrocket.com/author/kayodeadeniyi/) author pages.

## Tools I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

---

If you work on uncertainty, data quality in machine learning or water risk and think we should talk, I would be glad to hear from you at [adeniyikayode22@gmail.com](mailto:adeniyikayode22@gmail.com).
