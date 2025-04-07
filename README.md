# UN Big Data Hackathon: Climate Change and Sustainable Development

## Project Overview

This project was developed as part of the **UN Big Data Hackathon 2022**, focusing on climate change and its impacts on sustainable development. We aligned our efforts with the following Sustainable Development Goals (SDGs):

- **SDG 13**: Take urgent action to combat climate change and its impacts.  
- **SDG 14**: Conserve and sustainably use the oceans, seas, and marine resources.  
- **SDG 15**: Protect terrestrial ecosystems, sustainably manage forests, and combat desertification.

Our main objectives were:
1. Understanding the causes and effects of climate change.
2. Investigating its impact on life below water and on land.
3. Predicting future trends using machine learning.

## Project Structure

The repository is organized as follows:

- **dashboards/**:  
  Contains the project dashboards and a report:  
  - `Dashboards report.pdf`: Summary of the insights.  
  - `Dashboards.pbix`: Power BI dashboard file.

- **data/**:  
  Datasets used for the analysis, structured in subfolders for specific themes:  
  - `energy/`: Data related to energy consumption.  
  - `greenhouse gas emissions/`: Emissions data by region and country.  
  - `temperature/`: Global and regional temperature data.

- **notebooks/**:  
  Jupyter notebooks with data cleaning, analysis, and machine learning implementation:  
  - `energy.ipynb`: Analysis of energy consumption trends.  
  - `greenhouse gas emissions.ipynb`: Study of emissions evolution.  
  - `temperature.ipynb`: Examination of global temperature trends.

- **presentation/**:  
  Contains the team’s presentation delivered at the hackathon:  
  - `DigiTech team - UN Big Data Hackathon presentation.pdf`.

## Methodology

### 1. Data Cleaning
We performed a systematic cleaning process:  
- Removed duplicates, fixed structural errors, and handled missing values.  
- Focused on key indicators such as CO₂ emissions, forest area, and global temperature.

### 2. Exploratory Data Analysis
Explored patterns, tested hypotheses, and gained insights into:  
- Global energy dependency.  
- Trends in greenhouse gas emissions by country and region.  
- Decrease in forest area and its implications.  

### 3. Data Visualization
Created dashboards for visual insights using Power BI.

### 4. Machine Learning
Implemented an LSTM (Long Short-Term Memory) model to predict global temperatures for the next 10 years based on historical data.

## Key Insights

- The Asia-Pacific region emits the highest CO₂ globally, exceeding the combined emissions of all other regions.  
- Forest area is decreasing over time, correlating with temperature rises.  
- Predicted temperature anomalies indicate significant warming in the next decade.

## How to Use This Repository

1. **Dashboards**: Use Power BI to view and interact with the visualized data (`Dashboards.pbix`).  
2. **Jupyter Notebooks**: Run the notebooks in the `notebooks/` folder for code execution and detailed insights.  
3. **Presentation**: Review the project goals, process, and findings in the provided PDF file.
