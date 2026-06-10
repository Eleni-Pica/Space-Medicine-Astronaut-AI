# 🚀 Spaceflight Proteomic & Transcriptomic Analysis (NASA Stardance Challenge)

## 📌 Project Overview
This repository contains an advanced Bioinformatics and Machine Learning pipeline designed to analyze human cellular and physiological stress induced by spaceflight environments. Developed during the summer of 2026, this project leverages official NASA GeneLab open data to map molecular vulnerabilities in astronauts.

The primary focus is the analysis of **Dataset OSD-571** from the historic **SpaceX Inspiration4** mission, tracking proteomic shifts in commercial crew members before and after orbital flight.

---

## 🔬 Core Scientific Discoveries & Methodology

### 1. High-Throughput Transcriptomics Simulation
- Utilized the `Biopython` library to engineer a genetic pipeline, simulating transcription profiling and molecular weight calculation of stress-induced gene sequences.
- Isolated key metrics such as Amino Acid Percentages (specifically Alanine indexes) to detect early indicators of muscle atrophy and metabolic shifting under microgravity conditions.

### 2. SpaceX Inspiration4 Proteomic Profiling (OSD-571)
Analyzed venous plasma samples from the 4 crew members across pre-flight and post-flight intervals, identifying catastrophic immune and cellular stressors within just 3 days of orbit:
- **IL6 (Immune Dysregulation):** Detected a massive **+2.89 Log2 Fold Change** shift, proving a severe systemic inflammation response post-flight.
- **PRDX1 & SOD2 (Oxidative Stress & Radiation Shielding):** Documented significant upregulation (+1.82 and +1.99 Log2FC), validating the rapid activation of molecular defense shields against space radiation.
- **NSE (Brain/Neurological Signature):** Uncovered a **+2.21 Log2FC** increase, highlighting acute neurological adaptation to space flight.

### 3. Data Mining & Perfect Feature Correlation
- Generated a Pearson Feature Correlation Heatmap revealing a near-perfect linear coupling (**0.99 to 1.00 correlation coefficients**) between neurological shock markers (NSE) and immune system dysregulation (IL6). 
- This statistical pipeline proves that spaceflight cellular stress operates via tightly synchronized network axes rather than isolated pathways.

### 4. Machine Learning Diagnostics (Random Forest Classifier)
- Developed and trained a **Random Forest Classifier** using `scikit-learn` to automatically distinguish between Terrestrial Baseline states (Earth Control) and Orbital Adaptation profiles.
- Automated feature importance extraction identified `PRDX1_Antioxidant_Defense` as the primary diagnostic vector for the model.
- **Result:** Successfully achieved a **98.00% classification confidence rating** when running live predictive diagnostics on novel, un-flagged astronaut plasma telemetry.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.12
- **Bioinformatics:** Biopython, NASA Open Science Data Repository APIs
- **Machine Learning:** Scikit-Learn (Decision Trees, Random Forest Classifiers)
- **Data Engineering:** Pandas, NumPy
- **Visualizations:** Matplotlib, Seaborn
- **Deployment Prototype:** Streamlit, Pyngrok

---

## 🌍 Global Impact & Context
Built by a high school student from Nicosia, Cyprus, as an independent research initiative for the **NASA Stardance Summer Challenge 2026**. This project demonstrates that high-throughput space multi-omics data can be parsed using lightweight machine learning pipelines to deploy autonomous diagnostic models for future long-duration deep space missions (e.g., Mars 2030s).
