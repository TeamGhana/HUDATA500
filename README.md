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

```text
├── README.md                 # This file
├── syllabus/                 # Course syllabus and schedule
├── modules/                  # Weekly module materials
├── datasets/                 # Environmental justice & anti-surveillance datasets
├── notebooks/                # Jupyter notebooks (JupyterHub-ready)
├── containers/               # Podman / container definitions
├── assignments/              # Problem sets, memos, and project prompts
├── final-project/            # Lightning talk & final deliverable guidelines
└── resources/                # Setup guides for Jetstream2, JupyterHub, Podman
