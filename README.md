# AyaAI Generative UI Research

UX research data and Python analysis script for the project: "Generative UI vs. Text Chat: Reducing Cognitive Load in Educational Search".

## About
This project explores how a two-step Generative UI approach (interactive widgets + targeted AI output) reduces "Prompt Fatigue" compared to standard text-based AI chat. The focus is on cognitive load, task efficiency, and inclusive design.

## Study Design
- **Phase 1:** Interactive Prototype (Figma)
- **Phase 2:** Functional Web App A/B Testing
- **Cohort A (General Sample):** N=87
- **Cohort B (Neurodivergent Participants):** N=7

## Repository Contents
- `forms/General Sample Responses` - Raw survey and performance data (Cohort A).
- `forms/Neurodivergent Responses` - Raw survey and performance data (Cohort B).
- `AyaAI_Data.ipynb` - Jupyter Notebook (data cleaning, T-test, visualizations).

## Requirements
To run the notebook, install the dependencies:

```bash
pip install pandas matplotlib seaborn scipy numpy
```
## Quick Results
Speed: Generative UI reduced task completion time by 3.5x (57.7s vs 199.5s).
Significance: Independent T-test p-value < 0.001.
Preference: 81.6% of users preferred the Generative UI.

Note: Qualitative findings for Cohort B are detailed in the full case study.

## Links
Full UX Case Study in Notion: https://app.notion.com/p/Research-Project-Generative-UI-vs-Text-Chat-for-Reducing-Cognitive-Load-in-Educational-Search-39d90876b79780538d39e6e7fc49f172?source=copy_link

Interactive Video Demo: https://youtu.be/R_6T1GV2QbY

Researcher: Ayaulym Abiken (July 2026)
