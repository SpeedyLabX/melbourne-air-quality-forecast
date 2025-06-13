# Proactive Air Quality Forecasting and Health Alert System for Melbourne

<!-- Badges -->
<p align="left">
  <img src="https://img.shields.io/badge/Status-Planning-blue" alt="Project Status">
  <img src="https://img.shields.io/badge/Conference-AJCAI%202025%20Target-brightgreen" alt="Conference Target">
  <img src="https://img.shields.io/github/LICENSE/SpeedyLabX/melbourne-air-quality-forecast" alt="License">
  <a href="https://github.com/SpeedyLabX/melbourne-air-quality-forecast/issues"><img src="https://img.shields.io/github/issues/SpeedyLabX/melbourne-air-quality-forecast" alt="GitHub issues"></a>
</p>

This repository hosts the research and development of a comprehensive system for forecasting air quality (AQI), detecting bushfire smoke, and delivering proactive health alerts for the city of Melbourne, Australia. The project leverages multimodal data, advanced machine learning models, and explainable AI (XAI) to enhance transparency and public safety.

**Primary Goal:** Submission of a research paper to the **Australasian Joint Conference on Artificial Intelligence (AJCAI) 2025**.

---

## 📌 Project Overview

Melbourne's population is frequently exposed to poor air quality events, driven by both urban pollution and seasonal bushfire smoke. These events pose significant health risks, particularly to vulnerable groups. This project aims to address these challenges by developing an integrated system with four key pillars:

1.  **Multimodal Data Fusion:** Combining official environmental data (EPA), satellite imagery (MODIS/Sentinel-2), social media feeds (Twitter, Reddit), and meteorological data to create a rich, holistic view of air quality.

2.  **Advanced Predictive Modeling:** Implementing and comparing a diverse set of models, including a robust **XGBoost** baseline, a time-series **Bi-LSTM with Attention**, and a novel **Transformer-based architecture (SmokeNet)** for spatio-temporal analysis.

3.  **Explainable AI (XAI):** Integrating techniques like **SHAP**, **Integrated Gradients**, and **DiCE** to provide transparent, human-interpretable explanations for model predictions, building trust and enabling actionable insights.

4.  **Proactive Alerting Framework:** Designing a system capable of automatically issuing timely, location-aware health warnings and suggesting safe indoor shelters to at-risk individuals.

## 🎯 Research Objectives

*   To demonstrate the superiority of a multimodal approach over single-source data for AQI forecasting.
*   To evaluate the effectiveness of Transformer-based models in capturing the complex dynamics of bushfire smoke propagation.
*   To develop a comprehensive XAI framework that explains model behavior at both global and local levels.
*   To present a novel, user-centric system that bridges the gap between AI-driven forecasts and actionable public health interventions.

## 🚧 Project Roadmap & Status

This project is currently in the **planning and data collection phase**. The core activities are organized and tracked on our [**GitHub Project Board**](link-to-your-project-board).

The high-level timeline is as follows:
*   **Phase 1 (June 13-17):** Data Sourcing & Exploratory Data Analysis (EDA).
*   **Phase 2 (June 18-25):** Model Development, Training & Experimentation.
*   **Phase 3 (June 26-30):** Results Analysis & Paper Finalization for Submission.

Future work, post-submission, will focus on building the end-to-end agent-based pipeline and the public-facing dashboard.

## 🤝 The Team

This project is a research initiative by **SpeedyLabX**, a student-led AI research group at FPT University.

| Member | Role | GitHub Profile |
| :--- | :--- | :--- |
| Gia Bảo | Data Engineering & XAI | `[Link to Gia Bao's GitHub]` |
| XXX | Modeling & Research Writing | `[Link to XXX's GitHub]` |

**Mentor:** Ms. Minh Thư

## 📄 License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
