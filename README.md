# Predicting Voter Tendencies Using County Demographics: Analysis of the 2016 Election

## Project Overview
This repository explores whether **county-level demographic data** can accurately predict voting outcomes in the **2016 U.S. presidential election**. By combining **primary election results** with a wide range of demographic indicators (e.g., population, age distribution, race, economic activity), we built and evaluated **logistic regression** models to classify counties as **Republican** or **Democratic** leaning. The project illustrates the challenges of dealing with **missing data**, **geographic imbalances**, and **multicollinearity**, and highlights how **urban vs. rural** demographics play a key role in voting patterns.

## File/Folder Organization

- **articles/**  
  Contains written content for external publication (e.g., a LinkedIn article). These articles summarize the main findings, methods, and insights from this analysis in a more narrative style.

- **data/**  
  Stores raw and processed CSV files with county demographics and election outcomes. This includes:
  - **Demographic data** on population, business figures, racial composition, education, etc.
  - **Election results** data aggregated by county for the 2016 presidential primaries and/or general election.

- **notebooks/**  
  Contains the Jupyter notebook used for data cleaning, exploratory data analysis (EDA), feature engineering, model training, and validation.
  - **2016_Elections_Prediction_Model.ipynb** – 

- **presentations/**  
  Contains presentation materials (e.g., PDFs, slides) that provide a high-level summary of the analysis and results. These are typically used for communicating findings to stakeholders or at meetups/conferences.

- **.DS_Store / .gitignore**  
  System files and Git settings for ignoring temporary or OS-specific files (e.g., `.DS_Store` on macOS).

- **README.md**  
  This file you’re reading, which explains the project’s structure and purpose at a glance.

## Key Findings
- **Density vs. Population**: High-density (urban) counties tend to vote Democratic, whereas counties with large land area but lower density favor Republican outcomes.  
- **Data Imbalance**: More counties lean Republican, but total Democratic votes remain competitive due to high urban populations.  
- **Feature Engineering**: L1 (Lasso) logistic regression highlighted the strongest predictors, including **population density**, **economic activity**, and **age distributions**.

## Data Sources
1. **Election Results**: County-level 2016 outcomes from public election data.  
2. **Demographic Data**: U.S. Census or similar agencies offering population estimates, income, educational attainment, and business metrics.

## How to Use
1. **Clone or Download** this repository.  
2. Explore the **notebooks/** folder in numerical order to see how data cleaning, EDA, and modeling were performed.  
3. See **articles/** and **presentations/** for a concise summary and visual highlights of the project.

## Future Work
- **Additional Features**: Incorporate voting data from subsequent elections or more detailed economic indicators.  
- **Advanced Models**: Experiment with tree-based and ensemble methods.  
- **Geospatial Analysis**: Investigate adjacency effects (e.g., how neighboring counties influence voting patterns).
