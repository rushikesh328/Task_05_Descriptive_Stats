# Task_05_Descriptive_Stats

This project is part of Research Task 05 and focuses on evaluating how effectively a large language model (LLM) like ChatGPT can analyze a small real-world dataset using natural language prompts. The selected dataset contains **Formula 1 sprint race results from the 2024 season**.

The project is divided into two reporting periods. This README now documents progress for both Reporting Period 1 and 2.

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

### Prompt Testing (LLM)
- Used basic prompts to test the model’s ability to reason about sprint race data. 

Results were compared to Python outputs and documented.

---

## Reporting Period 2: Completed Tasks (Aug 1–15)

### Advanced Prompt Testing (LLM)

- Explored multi-step and reasoning prompts using LLMs that support Python and visual outputs.

- Tested LLM’s ability to generate complex insights, such as:

  - Track-specific team performance analysis

  - Identifying which drivers consistently outperform starting grid positions

  - Ranking drivers by efficiency (points gained vs starting position)

- Evaluated the quality, accuracy, and limitations of LLM reasoning compared to Python results.

### Enhanced Data Analysis

- Conducted deeper statistical analysis including:

- Driver performance trends across multiple tracks

- Team performance stability per track

- Correlations between starting grid, finishing position, and points by track

## Reflections and Findings

- LLM is effective for generating descriptive statistics and high-level insights, especially for summary-level questions.

- LLM reasoning can sometimes misinterpret multi-step logic, particularly when aggregations or track-specific filtering are required.

- Python outputs remain essential for validation and precise calculations.
---
