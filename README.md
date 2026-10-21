<h1 align="center">Hi, I'm Virav Shah 👋</h1>

<p align="center">
  <b>Bioengineering @ IIT Mandi · Minor in Data Science (Intelligent Systems)</b><br>
  I build retrieval systems, agentic AI tools, and deep learning models for medicine and finance.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/virav-shah"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:shahvirav@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/Virav-Shah?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"></a>
</p>

---

## 🧭 About

- 🎓 B.Tech Bioengineering at **IIT Mandi** (2024 – 2028), CGPA **8.62 / 10**
- 🔬 Working across **RAG and semantic search**, **agentic LLM systems**, **3D medical image registration** and **explainable risk modelling**
- 🏆 **Silver Medal**, GOGEC 2026 Virtual Research Conference · **4th Overall & 1st in Domain Track**, Hack60 2026 (HCLTech) · **13th of 23 IIT teams**, Inter IIT Tech Meet 14.0 (Adobe)
- 🎤 Head of Management & Communications, **TEDx IIT Mandi** · Core member, **E-Cell** · Coordinator, **Kamand Bioengineering Club**

---

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/LightGBM-02B875?style=flat-square" alt="LightGBM">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph">
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant">
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j">
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama">
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
</p>

| Area | Tools |
|---|---|
| **Languages** | Python, SQL |
| **ML / DL** | PyTorch, scikit-learn, LightGBM, SHAP |
| **GenAI & Retrieval** | RAG, semantic search, LangChain, LangGraph, Sentence-Transformers, Qdrant, Neo4j, Ollama, Gemini |
| **Backend & Deployment** | FastAPI, React, Streamlit, Docker, Git |

---

## 🚀 Featured Projects

### 🔭 [Quro: NASA Bioscience Research Platform](https://github.com/Virav-Shah/Quro)
*React · FastAPI · Qdrant · Neo4j · Gemini*
A full-stack RAG research assistant over **500+ NASA bioscience papers**, with answers cited to their source papers.
- Guardrails against unsupported answers: conversation-aware query rewriting, similarity thresholds and an LLM sufficiency check with a cited fallback
- Evaluated with RAGAS: **0.62 context precision**, **0.68 faithfulness** baseline
- Question answering over uploaded PDFs, plus an interactive Neo4j knowledge-graph explorer

### 🎙️ [AI Photo Editor with Agentic, Voice-Based Editing](https://github.com/Virav-Shah/Agentic-AI-Photo-Editor)
*Inter IIT Tech Meet 14.0 · Adobe Product Development · Ollama · Llama 3.2 · Gemma 3*
Language-model layer that turns text or voice requests into multi-step edits across **nine image tools**.
- A local **Llama 3.2 3B** model writes structured JSON edit plans; the orchestrator asks follow-ups when a request is unclear
- Fast path with **Gemma 3 1B** for single-step commands, with a keyword fallback
- Runs fully on local hardware with no external LLM service; ranked **13th of 23 IIT teams**

### 🧠 Multimodal Medical Image Registration (DL Research)
*PyTorch · 3D UNet · custom GPU kernel · OASIS Brain MRI*
- Predicts a coarse grid of control points, interpolated into a differentiable deformation field over the full volume
- **100–150× faster** than classical solvers, **0.768 Dice** overlap
- Cut coordinate folding to **0.01%**, versus ~0.88% for unconstrained transformers such as TransMorph
- 📹 Video and 📄 Report available (code is not public due to research guidelines)

### 📉 Explainable ML for NSE Stock Risk Forecasting *(ongoing)*
*LightGBM · SHAP · Streamlit*
- LightGBM quantile model for **95% and 99% risk forecasts** across 10 NSE stocks, anchored by rolling Student-t forecasts
- At 99%, lowered mean pinball loss by **5.5%** versus Student-t; calibration met the coverage criterion for **10/10 stocks**
- SHAP explanations to interpret and adjust forecasts

---

## 🏅 Competitions & Awards

| Year | Achievement |
|---|---|
| 2026 | 🥈 **Silver Medal**, GOGEC 2026 Virtual Research Conference (Team KBG): drug repurposing pipeline using gene activity, deep learning binding prediction and safety screening. **0.84 macro recall**, **92% disease hit rate** on 347 drugs. [Code](https://github.com/Virav-Shah/KBG_IITMD_gogec) |
| 2026 | 🏆 **4th Overall & 1st in Domain Track**, Hack60, HCLTech Deep Learning Hackathon: real-time webcam pose capture retargeted onto a simulated humanoid using ROS and MuJoCo |
| 2025 | 🥉 **4th Place (INR 10,000)**, VeriWise, iHub IIT Mandi Multimodal AI Hackathon: end-to-end fact checker for text, image, audio and video |
| 2025 | 🎓 **A grade**, GATIMU Design Practicum (IC 202P): wearable gait-analysis system with dual IMU sensors at **78% lower cost** than current market solutions |

---

## 📌 Pinned Repositories

<p align="center">
  <a href="https://github.com/Virav-Shah/Quro">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Virav-Shah&repo=Quro&theme=github_dark&hide_border=true" alt="Quro">
  </a>
  <a href="https://github.com/Virav-Shah/Agentic-AI-Photo-Editor">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Virav-Shah&repo=Agentic-AI-Photo-Editor&theme=github_dark&hide_border=true" alt="Agentic-AI-Photo-Editor">
  </a>
</p>
<p align="center">
  <a href="https://github.com/Virav-Shah/KBG_IITMD_gogec">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Virav-Shah&repo=KBG_IITMD_gogec&theme=github_dark&hide_border=true" alt="KBG_IITMD_gogec">
  </a>
  <a href="https://github.com/Virav-Shah/InXiteOut_Agentic_AI_PS">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Virav-Shah&repo=InXiteOut_Agentic_AI_PS&theme=github_dark&hide_border=true" alt="InXiteOut_Agentic_AI_PS">
  </a>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Virav-Shah&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub stats">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Virav-Shah&layout=compact&theme=github_dark&hide_border=true" alt="Top languages">
</p>

---

## 🤝 Let's Connect

I'm open to research collaborations, internships and hackathon teams in **applied ML, GenAI systems and medical AI**.

📧 [shahvirav@gmail.com](mailto:shahvirav@gmail.com) · 💼 [linkedin.com/in/virav-shah](https://www.linkedin.com/in/virav-shah)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Virav-Shah&label=Profile+views&color=0e75b6&style=flat-square" alt="Profile views">
</p>
