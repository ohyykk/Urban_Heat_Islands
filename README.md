## Motor Vehicle Risks in Toronto: Uncovering Collision and Theft Patterns
## Overview
This repository contains the analysis for the [paper](https://github.com/ohyykk/Toronto_Motor_Viehicle/blob/main/paper/paper.pdf) **"Motor Vehicle Risks in Toronto: Uncovering Collision and Theft Patterns"**. The study evaluates motorbike theft and collision risks in Toronto using a composite risk score model. Data from [OpenDataToronto](https://open.toronto.ca/dataset/motor-vehicle-collisions-involving-killed-or-seriously-injured-persons/) informs logistic regression and theft index calculations, highlighting key factors such as temporal patterns, environmental conditions, and neighborhood characteristics. The findings offer practical guidance for enhancing motorbike safety and urban mobility.
## Shiny app

An application featuring the Motorbike Risk Index by neighborhood can be found [here](https://ohyykk.shinyapps.io/TorontoMotorVehicle/)

## File Structure

The repository is organized as follows:

- `data/00-simulated_data`: Contains the simulated data used as the preview of actual the datasets
- `data/01-raw_data`: Contains the original datasets used for analysis, including collision data and theft data
- `data/02-analysis_data`: Includes the processed and cleaned datasets used for analysis and modeling
- `models`: Contains the collision model, theft indext model and final risk model used in this paper
- `paper`: Contains all materials for the paper, including:
  - The Quarto document for drafting and compiling the paper
  - The final PDF version of the paper
  - Bibliography and citation files
- `scripts`: Includes the R code for data simulating, cleaning, analysis, and visualization
- `other/datasheet`: Contains the detailed datasheet for the collision and theft dataset
- `other/llm`: Contains record of various conversations with ChatGPT that contributed to the development of this paper
- `other/sketches`: Includes drafts of the charts and models featured in the final research paper
- `other/shiny`: Include files used for the shiny app

## Tools and Methodology

The analysis involves:
1. **Geospatial Analysis**:  Mapping motorbike theft and collision risks across Toronto while incorporating neighborhood characteristics

2. **Statistical Modeling**: Employing a logistic regression model to analyze the relationships between collision risks, environmental factors, and temporal variables
  
4. **Visualization**: Static plots are utilized to present key findings and emphasize statistical and temporal trends.

Software tools used include:
- **R**: For statistical modeling, data manipulation, and visualizations (e.g., `ggplot2`).

## Statement on LLM Usage

ChatGPT 4o is utilized to support data cleaning, plot generation, and grammar checks. The complete interaction history is documented in `other/llm_usage.txt` for transparency. 
