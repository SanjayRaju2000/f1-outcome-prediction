# Predicting Formula 1 Race Finishing Categories

Estimate each driver's likelihood of Podium / Points / No Points / DNF **before** a race, using qualifying results, team/driver form, track traits, and weather data.

## Project Structure
- **data/**: Raw and processed datasets (not tracked in Git)
- **notebooks/**: Jupyter notebooks for EDA, feature engineering, modeling
- **figures/**: Saved plots for README and reports

## Workflow
1. Data collection & cleaning
2. Feature engineering
3. Model training & evaluation
4. Visualisation & interpretation

## Setup
\`\`\`bash
# Create and activate virtual env
python -m venv .venv
source .venv/Scripts/activate   # Git Bash

# Install dependencies
pip install -r requirements.txt
\`\`\`
