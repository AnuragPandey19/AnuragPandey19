<div align="center">

# Hi, I'm Anurag Pandey 👋

**B.Tech Computer Science (AI/ML) — UPES, Dehradun**

Building end-to-end ML systems — and checking that they actually work: held-out testing, calibration, and catching models that learn the wrong thing.

[![Portfolio](https://img.shields.io/badge/-Portfolio-00e5ff?style=for-the-badge&logo=githubpages&logoColor=white)](https://anuragpandey19.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anurag-pandey-154259280/)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AnuragPandey19)
[![Gmail](https://img.shields.io/badge/-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anuragpandeygct@gmail.com)

</div>

---

## About Me

<img align="right" alt="Coding" width="380" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif">

🎓 B.Tech CSE (AI/ML), UPES Dehradun — graduating May 2027

💼 Recently: AI/ML Intern at **IBM** (June–July 2026) — led architecture and deployment of a fraud-detection system

🛠️ Java is my preferred language; I use Python for ML and backend work

📦 Five deployed projects across fraud detection, browser security, RAG, computer vision, and desktop apps

🌐 Live portfolio: **[anuragpandey19.github.io/portfolio](https://anuragpandey19.github.io/portfolio/)**

<br clear="right"/>

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=for-the-badge)
![SHAP](https://img.shields.io/badge/SHAP-FF0D57?style=for-the-badge)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**GenAI / LLM**

![RAG](https://img.shields.io/badge/RAG-6A1B9A?style=for-the-badge)
![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-FFD21E?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

**Backend & Databases**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗_Hugging_Face-FFD21E?style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## Featured Projects

### 💳 CHIMERA-FD — Fraud Detection (IBM Internship)
Four-person IBM internship project; I led architecture, engineering, and deployment. Each checkout becomes 30 features scored by LightGBM, calibrated with isotonic regression, then routed: approve, send to a human analyst, or block — with SHAP reasons for every decision. Multi-tenant FastAPI + Next.js app with PostgreSQL, JWT auth, and bcrypt. On 3M synthetic held-out cases: **92.13% decisive accuracy**, 29.1% routed to review, **93% of fraud blocked or reviewed**, zero engine errors.

**Tech:** Python · LightGBM · Isotonic Calibration · SHAP · FastAPI · Next.js · PostgreSQL · JWT · Docker · GitHub Actions

➜ [Live Demo](https://undebuggedbit-chimera-fd.hf.space/)

---

### 🛡️ SurfVigil — Real-Time Browser Threat Detection
Chrome Manifest V3 extension + FastAPI/PostgreSQL backend (four-person team). Four ML models score phishing, XSS, cryptomining, and anomalous behaviour, and a rule cascade decides Allow / Warn / Block in under 250 ms. After launch I fixed three models that were silently returning zero behind HTTP 200, recalibrated five thresholds to cut false warnings on legitimate sites, and added an optional Google Safe Browsing pre-check.

**Tech:** Python · FastAPI · XGBoost · Random Forest · Isolation Forest · Autoencoder · PostgreSQL · Chrome Extension (MV3) · Docker

➜ [Repository](https://github.com/AnuragPandey19/SurfVigil) · [Live Site](https://surfvigil.com/) · [Chrome Web Store](https://chromewebstore.google.com/detail/surfvigil/glalkjnmdnblfobilebjkelocclcojcn)

---

### 🤖 Conversational Assessment Recommender — Agentic RAG
Chat assistant that helps recruiters pick assessments: asks a clarifying question when a request is vague, then returns a grounded shortlist. Hybrid retrieval (BM25 + MiniLM, fused with Reciprocal Rank Fusion); the LLM only picks names from retrieved candidates and the server attaches real catalog URLs, so links can't be hallucinated. Portfolio version on a synthetic 114-assessment catalog, runs on Groq or Gemini.

**Tech:** Python · FastAPI · BM25 · Sentence-Transformers (MiniLM) · Groq · Gemini · Pydantic · Docker

➜ [Repository](REPO_LINK_HERE) · [Live Demo](DEMO_LINK_HERE)

---

### 🌾 Rice Leaf Disease Detector — Two-Stage Vision Ensemble
Three-person team project; I owned architecture and engineering. Two-stage, five-model ensemble (EfficientNet-B3 + DenseNet-121 + MobileNetV3 → ViT-B/16 + ConvNeXt-Tiny). Found the original model was judging the background instead of the leaf, proved it with counterfactual tests, and rebuilt the dataset (4,302 images, source-stratified). Held-out accuracy: **94.51% Stage 1, 95.29% Stage 2**, zero false rejections across 656 test images; real field photos reported separately (81.67% / 86.67%).

**Tech:** PyTorch · Flask · Docker · Hugging Face Spaces · ViT · ConvNeXt

➜ [Repository](https://github.com/AnuragPandey19/Rice-Disease-Detector) · [Live Demo](https://undebuggedbit-rice-leaf-disease-detector.hf.space/)

---

### 🏙️ Smart City Guide — Java Desktop Application
Four-layer Java Swing app on a seven-table MySQL database, covering city profiles, tourism, transport, and user accounts. Prepared statements for every query and PBKDF2-HMAC-SHA256 password hashing (120K iterations, per-user salt). First-run flow creates and seeds the database automatically; Windows installer with a bundled JRE via jpackage (local MySQL required).

**Tech:** Java · Swing · JDBC · MySQL · PBKDF2 · jpackage

➜ [Repository](https://github.com/AnuragPandey19/Smart-City-Application-) · [Release v1.0](https://github.com/AnuragPandey19/Smart-City-Application-/releases/tag/v1.0)

---

## Experience

**AI/ML Intern — IBM** *(June 2026 – July 2026)*
Led architecture, engineering, and deployment for CHIMERA-FD, a four-person fraud-detection project: integrated the LightGBM + isotonic-calibration model, orchestrated retraining, and built the FastAPI/PostgreSQL backend with JWT auth and company-scoped data access verified through integration tests.

**AI/ML Intern — Notebrain Software & Services Pvt. Ltd.** *(Aug 2025 – Oct 2025)*
AI/ML researcher and model trainer on a client-confidential sports-outcome prediction system. Built and compared multiple deep-learning models in a shared team pipeline, with consistent validation and class-level error analysis.

**AI/ML Intern — Venture Launcher (Startup)** *(June 2025 – July 2025)*
Built Random Forest and LightGBM proof-of-concept models on 10,000 synthetic startup records to estimate funding-demand trends and investor-match relevance for a pre-seed founding team — framed as feasibility evidence, not real-market performance.

---

## Leadership

**Core Member — UPES ACM & ACM-W Student Chapters**
Served as Program Head for ICPC Code Nexus, managing logistics and technical operations. Awarded Certificate of Appreciation for execution and contribution.

---

## Get in Touch

🌐 **Portfolio:** [anuragpandey19.github.io/portfolio](https://anuragpandey19.github.io/portfolio/)

📧 Primary: [anuragpandeygct@gmail.com](mailto:anuragpandeygct@gmail.com)

🎓 College: [Anurag.120453@stu.upes.ac.in](mailto:Anurag.120453@stu.upes.ac.in)

🔗 [LinkedIn](https://www.linkedin.com/in/anurag-pandey-154259280/)

<div align="center">

*Open to internship and full-time opportunities in SDE and AI/ML roles — 2027 graduating batch.*

</div>
