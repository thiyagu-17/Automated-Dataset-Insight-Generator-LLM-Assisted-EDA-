# Automated Dataset Insight Generator (LLM-Assisted EDA)

This project loads any tabular CSV, runs an automated EDA pipeline
(missingness, type inference, basic quality checks, descriptive statistics, and plots),
and uses the Gemini API to generate human-readable insights and limitations.

## Repository structure

- `src/india_eda.ipynb`: Main notebook that runs the full pipeline on any CSV.
- `data/`: Example datasets used in the demo.
  - `india_population.csv` (development dataset)
  - `other_dataset.csv` (unseen dataset for demo)
- `output/`: Automatically created folder for plots and reports.
- `video/`: Contains the 5–7 minute screencast (or a text file with a link).
- `logs/genai_log.md`: Log of GenAI prompts and responses used during development.
- `requirements.txt`: Python dependencies.

## Setup

1. Create and activate a virtual environment (optional but recommended).
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
