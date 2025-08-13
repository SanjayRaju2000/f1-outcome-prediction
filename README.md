# Predicting Formula 1 Race Finishing Categories

## Executive Summary

### Problem Space
Formula 1 race outcomes are determined by a complex mix of factors — driver skill, team performance, track characteristics, weather, and qualifying results. While professional teams have sophisticated analytics, public-facing prediction tools are often simplistic, relying mainly on grid position. This leaves a gap for more nuanced, data-driven forecasts that can also reveal which factors truly influence racing success.

### ML Solution
This project develops a machine learning pipeline to predict a driver’s finishing position category — **Podium (P1–P3), Points (P4–P10), No Points (P11+), or DNF** — before the race begins. The model uses multi-source historical data, engineered performance metrics, and environmental conditions to generate forecasts. In addition to making predictions, the system identifies and ranks the most influential features, offering deeper insight into the dynamics behind race performance.

### Impact
The solution delivers reliable, pre-race predictions that go beyond simple pole position analysis. It also enables an understanding of which factors — such as team reliability, driver form, or track overtaking difficulty — have the greatest impact on success. These insights can inform commentary, fan engagement, and strategic thinking, making the results valuable to both technical and non-technical audiences.

### Commercial Opportunities
Potential applications include:
- **Sports Broadcasting** – Enhance pre-race coverage with data-backed insights.  
- **Fan Engagement Platforms** – Integrate predictions into fantasy F1 apps or interactive dashboards.  
- **Sponsorship & Marketing** – Target likely podium finishers for brand exposure.  
- **Team Strategy Tools** – Provide quick, visual summaries of competitor performance scenarios.  

By combining predictive accuracy with feature-level insights, this project provides both an engaging forecasting tool and a foundation for deeper analysis of what drives success in Formula 1.


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
### Create and activate virtual env
python -m venv .venv
source .venv/Scripts/activate   # Git Bash

### Install dependencies
pip install -r requirements.txt
\`\`\`
