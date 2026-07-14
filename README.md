# AyaAI Generative Ui Research

This repository contains the dataset and the Python analysis script for my UX research project: **"Generative UI vs. Text Chat: Reducing Cognitive Load in Educational Search"**.

## Project Overview
This research evaluates how Generative UI (interactive, AI-generated widgets) affects user performance compared to standard text-based AI chat interfaces. The goal was to quantify the "Prompt Fatigue" problem and prove that visual constraints can lead to faster and less stressful interactions.

## Methodology
1. **Study Type:** Comparative A/B Testing.
2. **Participants:** 87 undergraduate/graduate students.
3. **Task:** Search for a specific Master's program in Japan under strict constraints.
4. **Metrics:** Task completion time (seconds) and self-reported cognitive load (NASA-TLX scale).

## Repository Structure
1. `AyaAI - Form responses 1.csv` — Raw, anonymized user survey data.
2. `AyaAI_Data.ipynb` — Jupyter Notebook containing Python code for data cleaning, statistical T-test, and visualizations.

## Prerequisites
To run the analysis script, ensure you have Python 3.x installed along with the following libraries:

`pip install pandas matplotlib seaborn scipy numpy`

## Key Findings
My statistical analysis using Python revealed:
1. **Efficiency:** The Generative UI reduced task completion time by **3.5x** (57.7s vs 199.5s).
2. **Significance:** An independent T-test confirmed statistical significance with a **P-value < 0.001**.
3.  **User Preference:** 81.6% of participants preferred the Generative UI over the standard text chat.

## Detailed Case Study
For a comprehensive breakdown of the design process, user personas, and methodology, visit my full project case study in Notion:
 **[My Case Study in Notion](https://app.notion.com/p/Research-Project-Generative-UI-vs-Text-Chat-for-Reducing-Cognitive-Load-in-Educational-Search-39d90876b79780538d39e6e7fc49f172?source=copy_link)**

---
## Author
**Ayaulym Abiken**
*   **Role:** Undergraduate Student, Eurasian National University (ENU)
*   **Field of Interest:** Human-Computer Interaction (HCI), UX Research, Data Analytics

*Created for Academic Research - July 2026*
