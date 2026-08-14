# HUDATA500
**Introduction to an Open Source Future: Decolonizing Technology & Data Sovereignty**

**Howard University** · A FacultyHack@Gateways 2026 Collaboration 
**Faculty Participant:** Agbeli Ameko  

[![FacultyHack@Gateways 2026](https://img.shields.io/badge/FacultyHack-Gateways%202026-2b6cb0)](https://hackhpc.github.io/facultyhack-gateways26/)
[![SGX3](https://img.shields.io/badge/SGX3-NSF%20Award%202231406-1a365d)](https://sciencegateways.org/)
[![License](https://img.shields.io/badge/license-Open%20Source-green)](LICENSE)

---

## Overview

This repository contains the curriculum redesign materials developed during **FacultyHack@Gateways 2026**.  

The project integrates **SGX3 cyberinfrastructure** — Jetstream2 virtual machines, multi-user JupyterHub, and Podman containers — into *Introduction to an Open Source Future: Decolonizing Technology and Data Sovereignty* at Howard University.  

Students progress through a single, continuous **dataset-driven project** focused on environmental justice and anti-surveillance data. They move from Linux fundamentals and data exploration (JupyterLab + Metabase) to containerized workflows and local open-source AI, while critically examining digital colonialism and data sovereignty.

The redesign builds practical confidence in open-source tools and gives every student — regardless of personal hardware — access to a shared, reproducible computing environment.

---

## Course Goals

- Master core concepts of open-source operating systems, local tooling, and ethical computing practices that challenge digital colonialism and advance data sovereignty.
- Develop computational problem-solving skills by applying JupyterLab, Metabase, Python, and containerized workflows to progressive analysis of environmental justice and anti-surveillance datasets.
- Emphasize professional best practices in documentation, reproducibility, and collaborative work through shared JupyterHub environments and version-controlled analysis pipelines.
- Gain practical proficiency with SGX3 cyberinfrastructure by using **Jetstream2**, **JupyterHub**, and **Podman** as the persistent computing foundation for all course projects.

---

## Why This Course Matters

Many students enter the course with limited Linux and command-line experience yet strong interest in questions of data sovereignty and big-tech power. Howard’s Applied Data Science and Analytics curriculum already emphasizes Python, R, Tableau, and GIS for social-impact work. This course fills the critical gap in open-source operating systems, containers, and national cyberinfrastructure so that students can build fully reproducible, autonomous analytical environments and critically evaluate the infrastructures that shape knowledge production.

---

## Key Technologies

| Resource              | Role in the Course                                      |
|-----------------------|---------------------------------------------------------|
| **Jetstream2**        | Persistent VMs and classroom computing environment      |
| **JupyterHub**        | Multi-user, shared notebook environment                 |
| **Podman**            | Secure, rootless containerization                       |
| **JupyterLab**        | Interactive data exploration and analysis               |
| **Metabase**          | Open-source dashboards and visualization                |
| **Ollama**            | Local open-source AI models                             |
| **Linux (Pop!_OS / Zorin)** | Student daily-driver open-source operating systems |

---

## Repository Structure

├── README.md                 # This file
├── syllabus/                 # Course syllabus and schedule
├── modules/                  # Weekly module materials
├── datasets/                 # Environmental justice & anti-surveillance datasets
├── notebooks/                # Jupyter notebooks (JupyterHub-ready)
├── containers/               # Podman / container definitions
├── assignments/              # Problem sets, memos, and project prompts
├── final-project/            # Lightning talk & final deliverable guidelines
└── resources/                # Setup guides for Jetstream2, JupyterHub, Podman

## References

Bright Coding. (2025, September 18). *Build a private, powerful AI stack at home: The complete guide to self-hosting with n8n, Ollama, Supabase, Open WebUI & more*. https://www.blog.brightcoding.dev/2025/09/18/build-a-private-powerful-ai-stack-at-home-the-complete-guide-to-self-hosting-with-n8n-ollama-supabase-open-webui-more/

Center for Biological Diversity. (n.d.). *City council letter* [Sample memo template]. https://www.biologicaldiversity.org/action/toolbox/protecting_the_ca_coast/city_council_letter.html

Digital Sovereignty Coalition. (n.d.). *Plurality of digital sovereignty*. https://digitalsovereigntycoalition.org/digital-sovereignty

Doctorow, C. (2025). *Enshittification: Why everything suddenly got worse and what to do about it*. Farrar, Straus and Giroux.

Electronic Frontier Foundation & University of Nevada, Reno Reynolds School of Journalism. (n.d.). *Atlas of Surveillance: Data library*. https://www.atlasofsurveillance.org/data-library

FoggedLens. (2026). *deflock* [Computer software]. GitHub. https://github.com/FoggedLens/deflock

Jung, M. (2023, February 7). Digital capitalism is a mine not a cloud: Exploring the extractivism at the root of the data economy. *Transnational Institute*. https://www.tni.org/en/article/digital-capitalism-is-a-mine-not-a-cloud

Kwet, M. (2021, March 4). Digital colonialism: The evolution of US empire. *Transnational Institute*. https://longreads.tni.org/digital-colonialism-the-evolution-of-us-empire

U.S. Environmental Protection Agency. (n.d.). *EJScreen: Environmental justice screening and mapping tool* [Interactive map]. https://epa.maps.arcgis.com/apps/webappviewer/index.html?id=5f239fd3e72f424f98ef3d5def547eb5

Wilkinson, M. D., Dumontier, M., Aalbersberg, I. J., Appleton, G., Axton, M., Baak, A., Blomberg, N., Boiten, J.-W., da Silva Santos, L. B., Bourne, P. E., Bouwman, J., Brookes, A. J., Clark, T., Crosas, M., Dillo, I., Dumon, O., Edmunds, S., Evelo, C. T., Finkers, R., … Mons, B. (2016). The FAIR guiding principles for scientific data management and stewardship. *Scientific Data, 3*, Article 160018. https://doi.org/10.1038/sdata.2016.18
