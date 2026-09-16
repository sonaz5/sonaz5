# Hi, I'm Nazan Sonal 

**Computer Engineer **  
B.Sc. in Computer Engineering (Adnan Menderes University)

Passionate about building autonomous agentic architectures, stateful LLM workflows, acoustic signal processing, and production-ready machine learning pipelines. Experienced in LangGraph orchestration, metaheuristic hyperparameter optimization (PSO), and dual-language speech NLP systems.

[![IEEE Publication](https://img.shields.io/badge/IEEE_Xplore-Publication-00629B?style=flat&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/document/11636423)
[![SIU Conference](https://img.shields.io/badge/Conference-SIU_2026-blue?style=flat)](https://ieeexplore.ieee.org/document/11636423)

---

## 🛠 Tech Stack & Core Competencies

**Agentic Workflows & LLMs:**  
`LangGraph` `LangChain` `DeepEval` `MCP (Model Context Protocol)` `Hybrid RAG (BM25 + Dense)` `Prompt Engineering`

**Machine Learning & NLP:**  
`Sentence-Transformers (SBERT)` `Word2Vec (Gensim)` `TF-IDF` `Scikit-Learn` `LightGBM` `XGBoost` `CatBoost` `PyTorch`

**Signal & Audio Processing:**  
`Librosa (Mel-Spectrograms)` `Butterworth Filtering` `Digital Signal Processing (DSP)` `Arduino` `LSM6DSM IMU`

**Optimization & Metaheuristics:**  
`Particle Swarm Optimization (PSO)` `Cuckoo Search` `Grey Wolf Optimizer` `Mealpy` `Optuna`

**Cloud, Big Data & Deployment:**  
`Streamlit Cloud` `Docker` `Apache Spark` `AWS Elastic EMR` `SQLite` `Git / GitHub`

---

##  Featured Engineering & Research Projects

###  Metabolic Obesity Phenotype Classification *(Bachelor's Thesis & IEEE Publication)*
> **Paper:** [IEEE Xplore (Document: 11636423)](https://ieeexplore.ieee.org/document/11636423)  
> **Honors:** **Officially Approved and Funded by TÜBİTAK (2209-A)** | Presented at SIU 2026  
> **Stack:** Python, Scikit-Learn, LightGBM, XGBoost, CatBoost, PSO (Mealpy), Pandas

- Developed an end-to-end ML pipeline classifying 6 distinct metabolic obesity phenotypes using clinical data from the CDC NHANES database.
- Formulated rigorous data cleaning, SAS-to-Python ETL pipelines, and clinical feature engineering rules.
- Optimized hyperparameter spaces via Particle Swarm Optimization (PSO), outperforming baseline models and publishing empirical results in IEEE Xplore.
- **Formally approved and sponsored under the national TÜBİTAK 2209-A University Students Research Projects Support Program.**

---

###  Dual-Language Smart Home Voice Command Recognition System
> **Performance:** 99.46% F1-Macro (TR - 66 Classes) | 99.55% F1-Macro (EN - 69 Classes)  
> **Stack:** Python, Librosa, SBERT (all-MiniLM-L6-v2), Word2Vec, Scikit-Learn (MLP, RF, DT), SciPy  

- Designed a 4-phase acoustic and semantic NLP pipeline to process multi-window ASR predictions for 66 Turkish and 69 English smart home commands.
- Implemented audio preprocessing with 6th-order Butterworth bandpass filtering (100–6000 Hz) and 90% overlapping sliding windows (1.0s window / 0.1s hop) converting signals into 20-band Mel-Spectrograms.
- Evaluated semantic vector representations comparing Skip-gram Word2Vec, TF-IDF weighting, and Sentence-BERT transformers across 5 window aggregation strategies (Dominant Command, Confidence Weighted Mean, Weighted Vote).
- Deployed an offline inference runtime achieving 90% (TR) and 100% (EN) live batch test accuracy with sub-millisecond aggregation latency.

---

###  [Eval-Driven Agentic Code Reviewer](https://autonomous-code-studio-rz5qea2djuipl5tzojizin.streamlit.app/)
> **Stack:** Python, LangGraph, Google Gemini, SQLite, DeepEval, Streamlit  
> **Live Demo:** [Streamlit Cloud](https://autonomous-code-studio-rz5qea2djuipl5tzojizin.streamlit.app/)

- Architected an autonomous, 6-phase code evaluation agent with continuous stateful memory via SQLite.
- Implemented self-correction and reflection loops scored against senior engineering criteria using DeepEval.
- Built an interactive production dashboard with unified Git diff visualization and automated PyTest suite synthesis.

---

###  Embedded Sensor Signal Acquisition & Conditioning Pipeline
> **Stack:** C/C++ (Arduino), Python, LSM6DSM (6-DoF IMU), I2C/SPI, SciPy, Matplotlib

- Built a physical telemetry pipeline interfacing an Arduino microcontroller with an LSM6DSM 6-axis inertial measurement unit.
- Designed analog relaxation oscillator and operational amplifier (Op-Amp) circuits on breadboards for signal conditioning and noise suppression.
- Streamed raw accelerometer and gyroscope telemetry to Python for digital filtering, FFT spectral analysis, and noise reduction.

---

###  Multimodal Attention-Based Image Captioning Pipeline
> **Stack:** Python, CNNs (VGG16 / Inception), RNNs (LSTM / GRU), Bahdanau & Luong Attention, NLP

- Engineered an encoder-decoder deep learning architecture on the MS-COCO dataset to generate descriptive natural language captions.
- Integrated Bahdanau and Luong global attention mechanisms alongside Region Attention Networks to resolve long-range token dependencies.
- Evaluated caption fidelity using BLEU, METEOR, and ROUGE-L linguistic metrics.

---

###  Distributed Cloud Big Data Processing
> **Stack:** Apache Spark, AWS Elastic EMR, Python / PySpark, Distributed Computing

- Deployed a multi-node Apache Spark cluster on AWS Elastic MapReduce (EMR) to execute distributed text processing over large-scale datasets (12+ GB).
- Configured Spark core memory distribution, worker node balancing, and cluster storage pipelines for zero-loss distributed computations.

---

##  GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sonaz5&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sonaz5&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

##  Connect With Me

- **IEEE Publication:** [ieeexplore.ieee.org/document/11636423](https://ieeexplore.ieee.org/document/11636423)
- **Live Agent Demo:** [Autonomous Code Review Studio](https://autonomous-code-studio-rz5qea2djuipl5tzojizin.streamlit.app/)
- **Email:** sonalnazan@gmail.com
