# Hi, I'm Byeonggeon Go! 👋

I'm an **AI Engineer** specializing in **optimization, reinforcement learning, and production AI systems**.

My work focuses on reducing computational costs, improving model reliability, and building practical AI solutions across industrial and environmental domains.

**Core Expertise:** Bayesian Optimization · Reinforcement Learning · Time-Series ML · LLM Systems · Computational Optimization

📧 **Contact:** [Email](mailto:rhqudrjs7@gmail.com)

---

## 🛠️ Tech Stack & Areas of Interest

- **Research Interests:** Bayesian Optimization, Reinforcement Learning, Model Interpretability, and Time-Series Forecasting
- **Languages:** Python, C#, JavaScript, Dart
- **ML & Optimization:** PyTorch, TensorFlow, JAX, numba, scikit-learn, SHAP, Hyperopt
- **Backend & Data:** FastAPI, PostgreSQL/PostGIS, SQLite, Playwright
- **Application Domains:** Industrial AI, Environmental AI, and Time-Series Modeling

---

## 🎓 Education
- **M.S. in Environmental Engineering** - *University of Seoul* (Mar 2020 ~ Aug 2021)
- **B.S. in Environmental Engineering** - *University of Seoul* (Mar 2016 ~ Feb 2020)

## 📝 Research Highlights

- **Bayesian Optimization:** Optimized five species distribution models using TPE-based hyperparameter search, identifying convergence within 50–100 trials for selected models.
- **Time-Series Interpolation:** Developed a pattern-matching-based interpolation method that increased the number of usable high-quality samples, reducing prediction interval width by **3%**.
- **SHAP-Guided Optimization:** Analyzed model behavior and domain consistency across optimization budgets, identifying conditions that reduced the required search from 1,000 to 100 trials (90%) without compromising predictive performance or domain-consistent behavior.

---

## 💼 Professional Experience

### AI Engineer | Kunhwa Co., Ltd.
*AITF Team · Jan 2026 – Present*

- **LLM Pipeline Optimization:** Reduced document-processing latency from **12s to 4s (~67%)** by profiling retrieval bottlenecks and implementing batched embeddings, caching, and asynchronous workers.
- **Agentic RAG:** Built LLM tool-calling pipelines integrating GIS (PostGIS, WFS/WMS), PDF/Excel processing, Playwright automation, and regulatory databases for automated engineering compliance reporting.
- **Production Engineering:** Deployed FastAPI/React-based internal applications with automated source verification and traceable citations to document cells, coordinates, and regulations.

### LLM Benchmark Engineer | Ebit Co., Ltd.
*Freelance · Nov 2025 – Present*

- **Benchmark Design:** Developed domain-specific LLM coding-agent evaluation tasks involving scientific computing, environmental simulation, and parameter estimation.
- **Evaluation Infrastructure:** Implemented sandboxed execution and Pytest-based automated grading to validate numerical results and multi-step tool-use workflows.

### Data Scientist | OnePredict Inc.
*Data Intelligence Team 1 · Aug 2023 – Nov 2024*

- **Performance Optimization:** Reduced per-sample preprocessing time from **15s to 0.12s (125× speedup)** by redesigning moving RMS calculations with cumulative sums and optimizing correlation operations using Numba and JAX FFT.
- **Industrial PdM:** Developed automated reference-signal template selection and adaptive thresholds for variable-speed motor fault detection, supporting on-premises monitoring of approximately **200 motors**.
- **Production Validation:** Resolved all **188 recorded error cases** in a motor-diagnostics validation set and verified optimized numerical outputs against the original SciPy implementation.
- **Signal-Based Anomaly Detection:** Combined frequency-domain signal analysis, pseudo-labeling, and autoencoder-based anomaly detection to identify noise patterns and subtle bearing defects.

### Data Scientist | EHR&C Co., Ltd.
*Data Science Team · Dec 2021 – Aug 2023*

- **Simulation Acceleration:** Developed surrogate models using U-Net, conditional GANs, and Random Forest ensembles to reduce air-quality scenario evaluation from approximately **one month to seconds**.
- **Computational Optimization:** Achieved approximately **800× training speedup** through JAX/Flax-based reimplementation and computational optimization of simulation-related ML workflows.
- **Offline Reinforcement Learning:** Developed AWAC-based indoor air quality control policies using historical equipment logs, achieving approximately **5% reduction in operating time** in offline evaluation.
- **Environmental Data Engineering:** Automated species distribution modeling for approximately **800 species**, reducing data integration time by **~95%**, and implemented weather-dependent CO₂ sensor calibration.

---

## 🚀 Selected Personal Projects

### Featured Projects

**[law_chat](https://law-chat-424793710669.asia-northeast3.run.app)** — AI Legal Assistant
- Developed and deployed an LLM-powered legal Q&A application with document retrieval and source references.
- Released as both a web application and an [Android app](https://play.google.com/store/apps/details?id=com.rhqud.lawchat).
- **Focus:** LLM Applications · RAG · Full-Stack Development · Deployment
<img width="312" height="430" alt="image" src="https://github.com/user-attachments/assets/21d4f674-fd15-412c-bc40-abfeac26d2d4" />

**[multi_agent_awac](https://github.com/ByeonggeonGo/multi_agent_awac)** — Multi-Agent Offline Reinforcement Learning
- Implemented an AWAC-based offline RL framework for multi-agent HVAC control and indoor air quality optimization.
- **Focus:** Offline RL · PyTorch · Control Optimization

### Other Projects

| Project | Description |
|---|---|
| [vllm-custom-kv-codec-k8v4](https://github.com/ByeonggeonGo/vllm-custom-kv-codec-k8v4) | Custom 4/8-bit KV-cache codecs for vLLM with Triton kernels: 0.39x cache memory at bf16 decode speed |
| [CmaqProject](https://github.com/ByeonggeonGo/CmaqProject) | CMAQ environmental simulation data processing |
| [GeoVision-AI](https://github.com/ByeonggeonGo/GeoVision-AI) | Geospatial image analysis using YOLO and SAM |
| [geo_sdm](https://github.com/ByeonggeonGo/geo_sdm) | Species distribution modeling and geospatial prediction |
---

## 📝 Publications & Research Projects

### Journal Articles
- **Go, B.**, Shin, J., & Cha, Y. (2021). Development of benthic macroinvertebrate species distribution models using the Bayesian optimization. *Journal of the Korean Society of Water and Wastewater*, 35(4), 259–275.
- Cha, Y., Shin, J., **Go, B.**, Lee, D. S., Kim, Y., Kim, T., & Park, Y. S. (2021). An interpretable machine learning method for supporting ecosystem management: Application to species distribution models of freshwater macroinvertebrates. *Journal of Environmental Management*, 291, 112719.
- Shin, J., Yoon, S., Kim, Y., Kim, T., **Go, B.**, & Cha, Y. (2021). Effects of class imbalance on resampling and ensemble learning for improved prediction of cyanobacteria blooms. *Ecological Informatics*, 61, 101202.
- Kim, Y. W., Kim, T., Shin, J., **Go, B.**, Lee, M., Lee, J., ... & Cha, Y. (2021). Forecasting abrupt depletion of dissolved oxygen in urban streams using discontinuously measured hourly time-series data. *Water Resources Research*, 57(4), e2020WR029188.
- Kim, T., Kim, Y., Shin, J., **Go, B.**, & Cha, Y. (2020). Assessing land-cover effects on stream water quality in metropolitan areas using the water quality index. *Water*, 12(11), 3294.

### Master's Thesis & Conference Presentations
- **Go, B.** (2021). *Development of Species Distribution Models through Bayesian Optimization and Model Interpretation* [Master's thesis, University of Seoul].
- **Go, B.**, Kim, Y., Shin, J., Kim, T., & Cha, Y. (2020). The effect of hyperparameter optimization method and generalization performance estimation method of machine learning model on the performance of river water quality forecasting model. *Korean Society of Environmental Engineers (KSEE) Conference*, Jeju, Korea.

<details> Research Projects
- **Development of Methods for Assessing and Predicting Aquatic Ecosystem Health** (Korea Environmental Industry & Technology Institute, May 2020 – Jun 2021)
- **Development of a Big Data Management and Analysis Platform and Standardization Technologies for Water and Wastewater** (Ministry of Environment, Apr 2020 – Jun 2021)
- **Optimization of Seoul's Roadside Air Quality Monitoring Network to Support Fine Particulate Matter Mitigation Policies** (Seoul Green Environment Center, Apr 2020 – Dec 2020)
- **Development of AI-Based Modular Models for Multiscale Analysis of Multimodal Environmental Data** (Ministry of Science and ICT, Mar 2020 – Jun 2021)
- **Development and Evaluation of Next-Generation Forecasting Models for Water Quality and Aquatic Ecosystems (II)** (National Institute of Environmental Research, Sep 2019 – Oct 2019)
- **Development of a Statistical Framework for Assessing Changes in Water Quality (II)** (National Institute of Environmental Research, Jul 2019 – Mar 2020)
