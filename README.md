<h1 align="center">Tolga Arslan</h1>

<p align="center">
  <b>Software Developer · Python · FastAPI · React · Machine Learning</b><br>
  Computer Engineering graduate (English-taught) · İstanbul, Türkiye
</p>

<p align="center">
  <a href="https://tolgaarslann.github.io"><img src="https://img.shields.io/badge/Portfolio-tolgaarslann.github.io-1f6feb?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/tolga-arslan-dev/"><img src="https://img.shields.io/badge/LinkedIn-Tolga%20Arslan-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:tolgaarslan.dev@gmail.com"><img src="https://img.shields.io/badge/Email-tolgaarslan.dev%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://tolgaarslann.github.io/assets/cv/Tolga_Arslan_CV_EN.pdf"><img src="https://img.shields.io/badge/CV-PDF-555?style=flat-square" alt="CV"></a>
</p>

---

I build **end-to-end projects**: from collecting and cleaning data, through modeling, to **FastAPI services, automated tests, CI and live demos**. I care about results that hold up: honest baselines, leakage-free evaluation and decisions backed by measurements.

🎯 **Open to junior Software Developer / ML Engineer roles** in İstanbul or remote.

## 🚀 Featured Projects

### 💳 Card Fraud Detection · [Live Demo](https://card-fraud-detection-demo.streamlit.app) · [Code](https://github.com/TolgaARSLANN/card-fraud-detection)
Scores card transactions in real time using only what is known at that moment, and explains every alert.
- **0.959 PR-AUC** on 1.85M synthetic transactions (Kaggle Sparkov) with a ~0.5% fraud rate (logistic regression: 0.534), time-based split, one-shot test evaluation
- An expected-cost alert rule raised **2,522 alerts in 6 months at 74% precision**, caught **87% of fraud cases and 98% of fraud value**, and cut total cost from **$1.13M to $45.5K**
- FastAPI scoring service that returns the **top 3 reasons** per alert (SHAP), and a Streamlit panel deployed publicly with per-session isolation and pseudonymized card numbers
- **176 tests**, Ruff and GitHub Actions CI

`Python` `LightGBM` `XGBoost` `SHAP` `Optuna` `FastAPI` `Streamlit` `pytest`

### 🌫️ HavaUyarı: Air Quality Early Warning · [Code](https://github.com/TolgaARSLANN/havauyari)
Forecasts PM2.5 levels 24 hours ahead for 8 monitoring stations in 5 Turkish cities and warns before unhealthy air.
- 12-month walk-forward backtest (62.6K station-hours): **MAE 12.9 → 6.8 µg/m³**, **47.7% lower** than the raw CAMS forecast and **25.4% lower** than the best simple baseline
- Alert precision raised from **0.36 to 0.73**, with 80% prediction intervals and a "why this forecast?" explanation
- FastAPI service with PostgreSQL storage and a Streamlit dashboard, run via docker-compose; **152 tests**, including data-leakage checks and PostgreSQL integration tests, run on every commit

`Python` `LightGBM` `FastAPI` `PostgreSQL` `Docker` `Streamlit` `pytest` `Open-Meteo API`

### 🐾 Pawfect Care: Pet Care Platform (Capstone) · [Live Demo](https://pawfect-care-inky.vercel.app/) · [Code](https://github.com/TolgaARSLANN/PetCareApp)
Full-stack web app for tracking pets' health records, vaccinations, medications, weight and vet appointments.
- REST API with **46 endpoints**, secured by httpOnly JWT cookies, bcrypt, rate limiting, CSP headers and per-user data access
- **~300 tests** (Jest/Supertest for the API, Vitest/React Testing Library for the UI) in GitHub Actions; frontend on Vercel, API on Render
- Rule-based care recommendations from species, weight and health history

`React` `Node.js` `Express.js` `MongoDB` `JWT` `Jest` `Vitest`

### 🧩 Sudoku Solver · [Live Demo](https://sudoku-cozucu.onrender.com/) · [Code](https://github.com/TolgaARSLANN/sudoku-cozucu)
Reads a Sudoku from a phone photo, solves it and draws the answer back onto the photo as if written in pen. It can also check a puzzle you filled in by hand.
- On **40 unseen newspaper photos** it solved **37** and showed **0 wrong solutions**
- A handwriting CNN (PyTorch → ONNX) flags **~90% of wrongly written digits** with only **3 false alarms in 2,073 digits**
- React/TypeScript frontend and Flask API in Docker on Render; **111 tests** plus Playwright end-to-end tests

`Python` `OpenCV` `PyTorch` `ONNX` `Flask` `React` `TypeScript` `Playwright`

## 🛠️ Tech Stack

| | |
|---|---|
| **Languages** | Python, JavaScript, TypeScript, SQL, C# (basic) |
| **Backend** | FastAPI, Flask, Node.js, Express.js, REST APIs, JWT |
| **Frontend** | React, TypeScript, HTML, CSS |
| **Databases** | PostgreSQL, SQL Server, MongoDB |
| **ML / Data** | scikit-learn, LightGBM, XGBoost, SHAP, Optuna, PyTorch / ONNX, OpenCV, Pandas, NumPy, Streamlit |
| **Testing / DevOps** | pytest, Playwright, Jest, Vitest, GitHub Actions, Docker, Git |

## 💼 Experience

- **DeepTech/AI Intern**, ArVis Technology, Teknopark İstanbul (2024): prepared training data for a CNN-based early Alzheimer's diagnosis project in a 16-person R&D team
- **Software Intern**, VBT Yazılım (2023): hands-on development with C#, .NET Core and SQL Server

## 📫 Get in Touch

The fastest way to reach me is [email](mailto:tolgaarslan.dev@gmail.com) or [LinkedIn](https://www.linkedin.com/in/tolga-arslan-dev/). You can also find my CV and projects on my [portfolio](https://tolgaarslann.github.io).
