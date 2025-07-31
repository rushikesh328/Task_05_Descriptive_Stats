# Task_05_Descriptive_Stats

This project is part of Research Task 05 and focuses on evaluating how effectively a large language model (LLM) like ChatGPT can analyze a small real-world dataset using natural language prompts. The selected dataset contains **Formula 1 sprint race results from the 2024 season**.

The project is divided into two reporting periods. This README documents progress for **Reporting Period 1** for now, it will be updated for period 2.

---

##  Dataset

- Dataset used: `Formula1_2024season_sprintResults.csv` (stored locally only)
- Contains sprint results for F1 2024 season across multiple tracks, including:
  - `Driver`, `Team`, `Track`, `Starting Grid`, `Position`, `Points`, and more.

---

## Reporting Period 1: Completed Tasks

### Dataset Analysis (with Python)
- Loaded and summarized the dataset (shape, columns, samples)
- Calculated:
  - Most points by driver and by team
  - Average finishing position per driver
  - Team consistency (standard deviation of positions)
  - Correlations:
    - Starting Grid vs. Finishing Position
    - Improvement vs. Points
    - Starting Grid vs. Points

### Visualizations
- Regression plots of:
  - Starting Grid vs Points
  - Position Improvement vs Points

### 🧠 Prompt Testing (LLM)
- Used basic prompts to test the model’s ability to reason about sprint race data. 

Results were compared to Python outputs and documented.

---

## Reporting Period 2 Goals (Aug 1–15)

- Trying more complex prompts
- Using visual or multi-step prompts with LLMs that support charts or Python
- Document LLM reasoning quality and limitations
- Finalize project summary and reflections for submission

---
