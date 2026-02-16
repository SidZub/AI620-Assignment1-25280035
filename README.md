
# AI620 Assignment 1 – AI Labor Markets ELT Pipeline

## Theme
AI Labor Markets: Job trends, salary distribution, and search demand.

## Data Sources
1. Kaggle AI Job Dataset (CSV)
2. Remotive Public Jobs API (JSON)
3. Google Trends (Time-Series)

## Project Structure
data/
    raw/        -> Raw extracted data
    processed/  -> Processed CSV + JSON
    cleaned/    -> Cleaned datasets (Part 2)

## How to Run
1. Upload ai_job_dataset.csv to Colab.
2. Run notebook cells sequentially.
3. Raw data will be stored in data/raw.
4. Processed data will be stored in data/processed.

## Configuration
- Remotive search keyword: "machine learning"
- Google Trends timeframe: "today 5-y"

## Assumptions
- Kaggle dataset is pre-cleaned but may contain missing salary values.
- API data may contain optional fields.
- Trends data is indexed search interest (0-100 scale).
