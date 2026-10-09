<!-- TOJIN VARKEY SIMSON — ENGINEERING PORTFOLIO -->

<p align="center">
  <img src="./assets/hero.svg" width="100%" alt="Tojin Varkey Simson — Software Engineer. Building reliable software, intelligent systems, and thoughtful experiences. Simplify3x Software, Bengaluru, India." />
</p>

<p align="center">
  <a href="https://github.com/TechieTojin"><img src="https://img.shields.io/badge/GitHub-TechieTojin-0F172A?style=flat-square&logo=github&logoColor=0F172A&labelColor=F8FAFC&color=F1F5F9" alt="GitHub" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/tojin-varkey-simson"><img src="https://img.shields.io/badge/LinkedIn-Tojin_Varkey_Simson-0F172A?style=flat-square&logo=linkedin&logoColor=2563EB&labelColor=F8FAFC&color=F1F5F9" alt="LinkedIn" /></a>&nbsp;
  <a href="mailto:tojinsimson28@gmail.com"><img src="https://img.shields.io/badge/Email-tojinsimson28-0F172A?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=F8FAFC&color=F1F5F9" alt="Email" /></a>
</p>

Software Engineer at **Simplify3x Software**, Bengaluru. I build production web and mobile products — TypeScript and React Native on the client, Node.js and Express on the service layer, MongoDB and MySQL for persistence. I develop features end-to-end, debug production issues to root cause, and care about API contracts, state consistency, and code that the next person can maintain.

Background in statistics and computer science. Published research in deepfake detection. Three first-place hackathon finishes. Currently interested in system design, AI-assisted tooling, and local-first architectures.

---

### Flagship Project

<p align="center">
  <img src="./assets/atlas-system.svg" width="100%" alt="Atlas — AI Research Infrastructure. Five-stage pipeline: Planning → Evidence → Critique → Synthesis → Knowledge Graph. With retry on validation failure. Built with React, TypeScript, Python, FastAPI, LangGraph, Ollama, SQLite." />
</p>

**Atlas** is a local-first AI research platform I built to solve three problems with existing tools: they lose state when they fail, they can't trace a generated claim back to its source, and they require a cloud connection.

Atlas orchestrates cooperating agents through a five-stage pipeline — planning, evidence gathering, critique, synthesis, and knowledge graph generation. Every claim is traced back to its source with deterministic validation; if validation fails, the pipeline retries from the critique stage rather than starting over. Research persists as a navigable knowledge graph with project-scoped semantic memory, and completed sessions can be compared side by side.

**Design decisions:** Local-first with SQLite for portability and offline use. Cancellation-safe — any stage can be interrupted and resumed without data loss. LangGraph for agent orchestration because it provides explicit state machines over implicit chain-of-thought. FastAPI for the service layer because research sessions are long-running and benefit from async I/O.

---

### Projects

<p align="center">
  <img src="./Crop-Genie.png" width="100%" alt="Crop-Genie — AI agricultural decision-support with health scoring, analytics charts, and mobile companion view" />
</p>

**Crop-Genie** — AI crop advisory for smallholder farmers. Cross-platform app designed for modest hardware and unreliable networks. Typed end-to-end with a React Native/Expo client and Python/Scikit-learn intelligence layer.
<br/><sub>React Native · Expo · TypeScript · Python · Scikit-learn — <a href="https://github.com/TechieTojin/Crop-Genie">Repository →</a></sub>

<br/>

<p align="center">
  <img src="./FaceVerification.png" width="100%" alt="FaceVerification — real-time webcam face detection and identity verification" />
</p>

**Face Verification** — Real-time webcam identity verification using embedding-based matching, not pixel comparison. Swappable DeepFace backends for accuracy-vs-speed tuning.
<br/><sub>Python · OpenCV · DeepFace — <a href="https://github.com/TechieTojin/FaceVerification">Repository →</a></sub>

<br/>

<p align="center">
  <img src="./Bus-Reservation-System.png" width="100%" alt="Bus Reservation System — console booking with seat map and route table" />
</p>

**Bus Reservation System** — Full booking lifecycle in C with file-backed persistence, seat inventory consistency, and manual memory management. No framework safety net.
<br/><sub>C · File I/O · Data Structures — <a href="https://github.com/TechieTojin/Bus-Reservation-System">Repository →</a></sub>

<details>
<summary><b>More projects</b></summary>
<br/>

**Campus Rush** — Multi-interface campus ordering platform with shared state across web and mobile.
<br/><sub>React Native · React · Node.js · Express · MongoDB · Redux</sub>

**Soccer AR/VR** — Experimental football simulation across 2D, 3D, AR, and VR rendering modes.
<br/><sub>Python · Pygame · OpenGL · OpenCV · NumPy</sub>

**FinTech Advisory** — Transaction advisory system with rule-based validation and analytics dashboards.
<br/><sub>Flask · SQL · Pandas</sub>

**Journey Uplift** — Typed analytics interface with simulated data, designed as a reusable dashboard template.
<br/><sub>React · React Query · Tailwind · shadcn/ui</sub>

**Finance Portal** — Financial analytics portal. Awarded 2nd place at AMUHACKS 4.0.
<br/><sub>React · SQL</sub>

<a href="https://github.com/TechieTojin?tab=repositories">Browse all repositories →</a>
</details>

---

### Experience

**Simplify3x Software Pvt. Ltd.** — Bengaluru
<br/>Software Engineer · Jul 2026 → Present · *Intern · Feb–Jun 2026*

- Built catalog browsing, cart management, weight-based quantity handling, order placement, and delivery timelines across a B2B retail platform in React Native and TypeScript
- Designed and integrated REST API contracts between mobile clients and Node.js services
- Resolved client/server state divergence and synchronisation issues across mobile and web surfaces
- Investigated production defects through structured logging and systematic reproduction steps
- Contributed to an AI-assisted test automation platform with execution tracking and reporting
- Developed reusable shared component libraries; participated in cross-team code review

---

### Toolkit

<table>
<tr><td>

**Languages**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=fff&labelColor=F8FAFC&color=EFF6FF" height="20" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000&labelColor=F8FAFC&color=FFFBEB" height="20" alt="JavaScript" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=3776AB&labelColor=F8FAFC&color=EFF6FF" height="20" alt="Python" />
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logoColor=336791&labelColor=F8FAFC&color=EFF6FF" height="20" alt="SQL" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logoColor=ED8B00&labelColor=F8FAFC&color=FFF7ED" height="20" alt="Java" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=A8B9CC&labelColor=F8FAFC&color=F1F5F9" height="20" alt="C" />

</td></tr>
<tr><td>

**Frontend & Mobile**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=0EA5E9&labelColor=F8FAFC&color=F0F9FF" height="20" alt="React" />
<img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=0EA5E9&labelColor=F8FAFC&color=F0F9FF" height="20" alt="React Native" />
<img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=000&labelColor=F8FAFC&color=F1F5F9" height="20" alt="Expo" />

</td></tr>
<tr><td>

**Backend**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=16A34A&labelColor=F8FAFC&color=F0FDF4" height="20" alt="Node.js" />
<img src="https://img.shields.io/badge/Express-000?style=flat-square&logo=express&logoColor=475569&labelColor=F8FAFC&color=F1F5F9" height="20" alt="Express" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=0D9488&labelColor=F8FAFC&color=F0FDFA" height="20" alt="FastAPI" />
<img src="https://img.shields.io/badge/Flask-000?style=flat-square&logo=flask&logoColor=475569&labelColor=F8FAFC&color=F1F5F9" height="20" alt="Flask" />

</td></tr>
<tr><td>

**Data**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=16A34A&labelColor=F8FAFC&color=F0FDF4" height="20" alt="MongoDB" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=2563EB&labelColor=F8FAFC&color=EFF6FF" height="20" alt="MySQL" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=2563EB&labelColor=F8FAFC&color=EFF6FF" height="20" alt="SQLite" />
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=7C3AED&labelColor=F8FAFC&color=F5F3FF" height="20" alt="Pandas" />

</td></tr>
<tr><td>

**AI/ML**&nbsp;&nbsp;
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=EA580C&labelColor=F8FAFC&color=FFF7ED" height="20" alt="Scikit-learn" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=7C3AED&labelColor=F8FAFC&color=F5F3FF" height="20" alt="OpenCV" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=475569&labelColor=F8FAFC&color=F1F5F9" height="20" alt="LangGraph" />
<img src="https://img.shields.io/badge/Ollama-000?style=flat-square&logoColor=475569&labelColor=F8FAFC&color=F1F5F9" height="20" alt="Ollama" />
<img src="https://img.shields.io/badge/DeepFace-5C3EE8?style=flat-square&logoColor=7C3AED&labelColor=F8FAFC&color=F5F3FF" height="20" alt="DeepFace" />

</td></tr>
<tr><td>

**Tools**&nbsp;&nbsp;Git · GitHub · Docker · Postman · VS Code · EAS Build

</td></tr>
</table>

---

### Achievements

<p align="center">
  <img src="./assets/achievements.svg" width="100%" alt="3 first-place finishes (InnovateX RHAPSODY at IISc, Code Hunter, Hack-4-Mini 2.0), 1 second place (AMUHACKS 4.0), 1 national top 100 (HACKHAZARD 25)." />
</p>

---

### Publications

**A Study on Analysis of Deep Learning Approaches for Detecting Fake News, Audio & Video**
<br/><sub>Comparative analysis of deep learning methods across text, audio, and video misinformation.</sub>

**Automated Detection of Deepfakes Using Integrated AI and Computer Vision Strategies**
<br/><sub>Combining AI models with computer vision pipelines for automated deepfake detection.</sub>

### Education

**Master of Computer Applications** — Christ University, Bangalore (2024–2026) · 8.2 CGPA
<br/>**B.Sc. Statistics & Computer Science** — St. Joseph's University (2021–2024) · 7.5 CGPA

**Student Coordinator** — Smart India Hackathon 2025. Coordinated across five university campuses.

---

<p align="center">
  <img src="https://streak-stats.demolab.com?user=TechieTojin&theme=default&hide_border=true&border_radius=0&ring=2563EB&fire=7C3AED&currStreakLabel=475569&sideLabels=475569&dates=94A3B8&sideNums=0F172A&currStreakNum=0F172A&background=FFFFFF" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/TechieTojin/TechieTojin/output/snake-dark.svg" width="88%" alt="Contribution graph" />
</p>

---

<p align="center">
  <a href="https://github.com/TechieTojin"><img src="https://img.shields.io/badge/GitHub-TechieTojin-0F172A?style=flat-square&logo=github&logoColor=0F172A&labelColor=F8FAFC&color=F1F5F9" height="22" alt="GitHub" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/tojin-varkey-simson"><img src="https://img.shields.io/badge/LinkedIn-Connect-0F172A?style=flat-square&logo=linkedin&logoColor=2563EB&labelColor=F8FAFC&color=F1F5F9" height="22" alt="LinkedIn" /></a>&nbsp;
  <a href="mailto:tojinsimson28@gmail.com"><img src="https://img.shields.io/badge/Email-tojinsimson28-0F172A?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=F8FAFC&color=F1F5F9" height="22" alt="Email" /></a>
</p>

<p align="center"><sub>Bengaluru, India</sub></p>
