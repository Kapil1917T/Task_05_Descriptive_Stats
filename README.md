# 🧠 Task 05 – Descriptive Statistics with Large Language Models (LLMs)

This project explores how effectively large language models (LLMs) such as ChatGPT can interpret real-world sports statistics through natural language prompts. The task involves analyzing the 2025 season performance of the Syracuse Women’s Lacrosse team.

---

## 📊 Dataset Overview

- **Source**: Official 2025 season stats – [Syracuse Women’s Lacrosse](https://cuse.com/sports/2013/1/16/WLAX_0116134638)
- **Data Format**: Extracted manually from PDF into structured CSVs
- **Coverage**: Player stats, team stats, goalie stats, period-wise breakdowns, and game logs

### 📁 CSVs Created (not included in repo)
- `Player_Stats_2025.csv`
- `Team_Stats_2025.csv`
- `Goalie_Stats_2025.csv`
- `Game_Log_2025.csv`
- `Goals_by_Period_2025.csv`
- `Shots_by_Period_2025.csv`
- `SOG_by_Period_2025.csv`
- `Saves_by_Period_2025.csv`

> ⚠️ **Note**: As per assignment instructions, raw datasets are excluded from this repository.

---

## 🧪 LLM Prompting Strategy

### Goals:
- Ask natural language questions about the data
- Evaluate LLM’s ability to interpret structured input
- Compare factual and interpretive prompt performance

### LLMs Used:
- ChatGPT (GPT-4)
- Claude (planned)

### Prompt Examples:
See [`prompts/prompt_log.md`](prompts/prompt_log.md) for complete Q&A history.

---

## 🧠 Sample Prompts Used

- “Who scored the most goals?”
- “Which player had the most assists?”
- “Who is the most well-rounded player based on goals, assists, and turnovers?”
- “Was Syracuse stronger in the first or second half of games?”

---

## 🧮 Validation

Python scripts (to be added) are used to:
- Cross-verify LLM answers using actual stats
- Calculate metrics like goals-per-shot, assists-to-turnovers, etc.

---

## ✅ Next Steps
- Expand LLM prompt set with more advanced reasoning questions
- Compare LLM performance across GPT and Claude
- Add more seasons (e.g., 2024, 2023) for longitudinal analysis
- Visualize trends using matplotlib or seaborn (optional)

---

## 📬 Submission Notes
- GitHub repo name: `Task_05_Descriptive_Stats`
- Raw datasets are not uploaded
- Prompt logs and validation scripts are included
