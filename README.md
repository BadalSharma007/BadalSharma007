# Badal Kumar Sharma

🌐 **Portfolio:** [badalsharma.me](https://badalsharma.me)

B.Tech CSE (AI & ML), Sharda University — 4th year. I build language models, computer vision systems, and agentic AI pipelines. Sometimes hardware too.
---

## Competitions & Rankings

| Competition | Result |
|---|---|
| **Amazon ML Challenge 2025** | Rank **663 / 80,332 teams** — XGBoost + TF-IDF + 400+ engineered features |
| **Kaggle · Heart Disease Prediction** | Rank **16 / 4,507 — Top 0.4%** · AUC 0.95410 |
| **Kaggle · Road Accident Risk (S5E10)** | Rank **445 / 10,285 — Top 4.3%** · LightGBM + XGBoost ensemble |
| **Kaggle · Student Test Scores (S6E1)** | Rank **613 / 4,319 — Top 15%** |
| **NCAA March ML Mania 2026** | 5-model ensemble · RF + XGB + CatBoost + LGB + PyTorch · Optuna + Elo features |
| **Hacknovate Hackathon** | **Rank 3** |
| **LeetCode** | Rating **1770** · Best Contest Rank **54** |
| **Codeforces** | Rating **1054** |
| **Kaggle** | **Expert** · 13 Badges · Best Rank 16 / 4,568 |

---

## Projects

**[Third Eye](https://github.com/BadalSharma007/Third_Eye)** — Offline AI voice assistant for visually impaired users. ESP32-CAM captures frames, a locally-hosted Ollama LLM describes the scene, gTTS reads it aloud. No internet, no cloud — runs entirely on local hardware.

**Remindee.ai** — Production email assistant built on FastAPI + Gmail API + OAuth2. Parses 500+ emails/day, extracts deadlines and tasks via spaCy + regex at 92% accuracy. Redis caching cut inference latency ~60%. Stack: FastAPI · PostgreSQL · Redis · NLP · OAuth2. *(Private repo)*

**[GPT from scratch](https://github.com/BadalSharma007/Entire-coding-Transformer-block-GPT2-)** — 124M-parameter GPT-2 style transformer in PyTorch. Multi-head self-attention, positional embeddings, AdamW + cosine annealing, tiktoken. Pushed validation perplexity 42.3 → 16.8.

**Autonomous Driving Robot** — ESP32-based self-driving robot with ultrasonic + IR obstacle detection, OpenCV lane following, A* path planning, and LLaVA-7B as the decision-making brain for scene understanding. Runs at 15 FPS. *(Private repo)*

**[NexaAI Website Generator](https://github.com/BadalSharma007/nexaai-agentic-website-generator)** — Agentic pipeline: Gemini Vision extracts design spec from a reference screenshot → LLM generates Next.js TSX pages → Selenium screenshots each page → Gemini Vision scores it → regenerates if score < 65. Zero human input, four pages fully built.

**[Face Recognition Attendance](https://github.com/BadalSharma007/FaceRecognitionSystem)** — EfficientNet-B4 with transfer learning on a 200-identity custom dataset, 85% accuracy across varying lighting. TensorRT quantized for 30+ FPS on edge devices, deployed via Flask.

**[Amazon ML Challenge 2025](https://github.com/BadalSharma007/AmazonMl-Challenge-2025--Rank-663)** — Product price prediction from catalog text. TF-IDF + SVD embeddings combined with 400+ regex-extracted attributes (pack size, weight, volume, brand signals). Log-price transformation + 5-fold CV. Rank 663 out of 80,332 teams.

**[ANPR](https://github.com/BadalSharma007/Number-Plate-Recognition)** — License plate detection + OCR pipeline. YOLOv8 at 94% mAP, EasyOCR for character recognition, handles 5+ regional plate formats in real time.

---

## Experience

**Shell-Edunet / AICTE** · AI Intern · Jan–Mar 2025
Built an ML pipeline for EV charging demand prediction on 50K+ records — improved station deployment efficiency by 70%. Also ran NLP analysis on 10K+ dialogue samples for customer insight extraction.

**VOIS (Vodafone)** · Conversational AI Intern · 2025
Designed LLM-based NLP pipelines on enterprise dialogue data. Applied prompt engineering to improve model output accuracy 30%+. Prototyped agentic workflow automations for conversational systems.

**IBM-SkillsBuild** · Data Analytics Intern · 2025
Built Power BI dashboards over 15K+ customer feedback entries. Surfaced 3 key churn drivers that informed the retention strategy — projected 18% churn reduction.

---

## Stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash"/>
</p>

**AI / ML**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black" alt="YOLO"/>
</p>

**Data & Analytics**

<p>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
</p>

**Backend & Databases**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
</p>

**DevOps & Cloud**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

---

<p>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=BadalSharma007&layout=compact&theme=dark&hide_border=true&langs_count=8" alt="Top Languages"/>
  &nbsp;&nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com?user=BadalSharma007&theme=dark&hide_border=true" alt="GitHub Streak"/>
</p>

---

## Contact

[![Gmail](https://img.shields.io/badge/sonusharma4201434@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sonusharma4201434@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/badal-kr-sharma-471a19263/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/Badal_kr_sharma)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/BadalSharma007)
[![Codeforces](https://img.shields.io/badge/Codeforces-1054-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Badal_07)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/Cloudy_9_3)
