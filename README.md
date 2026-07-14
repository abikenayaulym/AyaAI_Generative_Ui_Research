# AyaAI_Generative_Ui_Research

This repository contains the dataset and the Python analysis script for my UX research project: **"Generative UI vs. Text Chat: Reducing Cognitive Load in Educational Search"**.

# Project Overview
This research evaluates how Generative UI (interactive, AI-generated widgets) affects user performance compared to standard text-based AI chat interfaces. The goal was to quantify the "Prompt Fatigue" problem and prove that visual constraints can lead to faster and less stressful interactions.

# Methodology
*   **Study Type:** Comparative A/B Testing.
*   **Participants:** 87 people.
*   **Task:** Search for a specific Master's program in Japan under strict constraints.
*   **Metrics:** Task completion time (seconds) and self-reported cognitive load (NASA-TLX scale).

# Repository Structure
*   `/data`: Contains the `ayaai_data.csv` file with 87 anonymized responses.
*   `/analysis`: Contains the Jupyter Notebook/Python script used for cleaning the data, plotting visualizations, and performing statistical analysis (T-test).

# Prerequisites
To run the analysis script, ensure you have Python 3.x installed along with the following libraries:
```bash
pip install pandas matplotlib seaborn scipy numpy
