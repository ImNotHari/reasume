# Harishankar Suresh

Systems-oriented developer and Computer Science undergraduate with a focus on local machine learning pipelines, edge computing, and distributed embedded systems. Passionate about deterministic latency, efficient memory management, and practical software architecture.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-harishankar--suresh-18181b?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harishankar-suresh-2aa657201/)
[![Email](https://img.shields.io/badge/Email-harishankar.suresh%40gmail.com-18181b?style=flat-square&logo=gmail&logoColor=white)](mailto:harishankar.suresh@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-ImNotHari-18181b?style=flat-square&logo=github&logoColor=white)](https://github.com/ImNotHari)

---

### About

I build software focused on systems, local machine learning setups, and embedded hardware, with an emphasis on keeping things lightweight and running without cloud dependencies.

- **Focus:** Local AI inference, embedded sensor networks, and practical full-stack tools.
- **Community:** Technical Coordinator for the IEEE Computer Society (GEC Idukki), helping organize practical sessions on Git and web basics for students.
- **Education:** B.Tech in Computer Science and Engineering, Government Engineering College Idukki (2024 to 2028).

---

### Core Stack & Technologies

<p align="left">
  <img src="https://img.shields.io/badge/C-18181b?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/Python-18181b?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-18181b?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-18181b?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Java-18181b?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-18181b?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-18181b?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-18181b?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-18181b?style=flat-square&logo=linux&logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/ONNX_Runtime-18181b?style=flat-square&logo=onnx&logoColor=white" alt="ONNX Runtime" />
  <img src="https://img.shields.io/badge/PyTorch-18181b?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/FastAPI-18181b?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Streamlit-18181b?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/MQTT-18181b?style=flat-square&logo=eclipsemosquitto&logoColor=white" alt="MQTT" />
  <img src="https://img.shields.io/badge/Electron-18181b?style=flat-square&logo=electron&logoColor=white" alt="Electron" />
</p>

| Domain                  | Tools & Technologies                                                                                                   |
| :---------------------- | :--------------------------------------------------------------------------------------------------------------------- |
| **Languages**           | C, Python, TypeScript, JavaScript, Java, SQL, RISC-V Assembly                                                          |
| **AI, ML & Geospatial** | PyTorch (Multimodal Attention, LSTM), XGBoost, ONNX Runtime, llama.cpp (GGUF), Kokoro TTS, GeoPandas, Rasterio, Folium |
| **Backend & Systems**   | Spring Boot, FastAPI, Streamlit, REST APIs, Microservices, Multi-threading, IPC, MQTT, Apache Parquet                  |
| **DevOps & Platforms**  | Docker, Git, GitHub Actions, Linux, PostgreSQL, PostGIS, Supabase, Vercel                                              |

---

### Featured Systems & Projects

#### [EarthSense](https://github.com/ImNotHari/Earthsense)

> **Multimodal Deep Learning Landslide Susceptibility & 24h Early Warning Platform**

- **Technologies:** Python, PyTorch, XGBoost, Sentinel-1 SAR, FastAPI, Streamlit, GeoPandas, Parquet
- Fused Sentinel-1 SAR/MSI imagery, 5-day rainfall LSTMs, and terrain MLPs via Cross-Modal Multi-Head Attention over 1 km UTM grids, achieving **0.9581 PR-AUC** (0.9901 ROC-AUC) on the 2020 Pettimudi holdout and **88.4%** cross-region concordance in Wayanad.
- Engineered a vectorized CPU serving pipeline (**49.45 ms** p95 across 4,496 cells), dual-gated OASIS CAP v1.2 / NDMA SACHET alerting, and 12 Papermill-gated reproducible notebooks.

#### [Gomosy](https://github.com/ImNotHari/gomosy)

> **Offline, Zero-Cloud PDF-to-Speech AI Studio and TTS Neural Narration Engine**

- **Technologies:** Python, Electron, llama-cpp-python, Kokoro TTS, ONNX Runtime, PyMuPDF
- Architected a privacy-first desktop platform converting complex multi-column academic and technical PDFs into human-like audio locally without cloud APIs.
- Engineered memory-reclamation routines and chunked PCM-to-MP3 streaming buffers, curbing peak hardware footprint to $\le$ 1.0 GB RAM and $\le$ 2.5 GB VRAM on consumer hardware.

#### [Project TRACE](https://github.com/ImNotHari/TRACE)

> **LEO Satellite Orbital Decay & Atmospheric Drag Simulation Platform**

- **Recognition:** Global Nominee — NASA International Space Apps Challenge 2025
- **Technologies:** JavaScript, Physics Modeling, Chart.js, HTML5
- Developed numerical integration algorithms modeling atmospheric drag and ballistic decay across Low Earth Orbit (120–450 km) independent of radar/TLE telemetry feeds.
- Built interactive multi-scenario trajectory visualizations to assist operators with lifetime estimation and space debris mitigation compliance.

#### [Distributed Air Purifier System (DAPS)](https://github.com/ImNotHari)

> **Collaborative Multi-Node Embedded Environmental Network**

- **Technologies:** C, Embedded Systems, Multi-Sensor Fusion, MQTT, I2C / SPI
- Authored modular microcontroller firmware interfacing with optical particulate sensors (PM2.5 / PM10) over I2C and SPI.
- Designed dynamic multi-modal sensor fusion and load-balancing algorithms over lightweight MQTT queues, reducing cumulative power draw by ~15%.

#### [RISC-V Branch Prediction Analysis](https://github.com/ImNotHari)

> **Hardware Architecture Simulation & Pipeline Benchmarking**

- **Technologies:** QtRvSim, RISC-V Assembly, Python Instrumentation
- Conducted cycle-accurate simulation on a 5-stage RISC-V processor pipeline, comparing static branch strategies (BTFN) against dynamic predictors (1-bit / 2-bit bimodal saturating counters).
- Extracted cycle logs via automated Python scripts to compute branch misprediction penalties and CPI stall impacts under varied loop workloads.

#### [Full-Stack Expense Tracker](https://github.com/ImNotHari/expensetracker)

> **Personal Finance Platform with Strict Data Isolation**

- **Technologies:** Spring Boot, Java 17, PostgreSQL, Docker, Vue.js / React, JWT
- Structured relational schemas with indexed date and multi-category queries, delivering consistent sub-100ms response latencies.
- Implemented automated CI/CD container build and regression testing pipelines with GitHub Actions.

### Community & Activities

- **Technical Coordinator, IEEE Computer Society (GEC Idukki):**
  - Helped organize practical sessions for club members on basic Git, web development, and project setups.
  - Assisted juniors and batchmates with debugging, tool installations, and getting started on their coursework projects.
  - Helped manage technical events, hackathon entries, and project presentations for the chapter.

---

### Current Focus & Exploration

- Hardware-efficient quantization and low-latency inference runtimes on edge devices.
- Processor microarchitecture simulation and pipeline hazard optimization.
- Scalable, self-organizing IoT networks with resilient low-bandwidth telemetry.

---

<div align="center">
  <sub>Designed with restraint · Built for performance · <a href="https://github.com/ImNotHari">github.com/ImNotHari</a></sub>
</div>
