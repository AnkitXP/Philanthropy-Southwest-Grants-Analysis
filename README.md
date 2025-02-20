# Analysis of Granting Patterns of Foundations Across the Southwest

## Overview
This project provides an in-depth analysis of how philanthropic institutions allocate their grants across the southwestern region of the United States, covering Arizona, Arkansas, Colorado, New Mexico, Nevada, Oklahoma, and Texas. By analyzing grant-making patterns, we uncover trends in donations and grant distribution to identify disparities and patterns in donor behavior and recipient demographics.

The project involves data collection from IRS Form 990 XMLs, Census datasets, and other publicly available sources. The analysis is visualized through interactive dashboards built in Tableau, providing stakeholders with an intuitive tool to explore granting trends in the Southwest region.

## Project Objectives
- **Analyze grant sources**: Identify and categorize the origins of grants across southwestern states.
- **Examine utilization patterns**: Investigate how grants are distributed and utilized across different sectors.
- **Identify recipient types**: Categorize and analyze various types of grant recipients.
- **Assess population-wise distribution**: Evaluate grants against population demographics to determine funding allocation effectiveness.
- **Conduct geographic analysis**: Examine the geographic breakdown of grants, highlighting urban vs. rural grant distribution.
- **Categorize donors**: Develop a classification system for donors and analyze donation behaviors.
- **Explore institutional relationships**: Investigate relationships between donor institutions and recipients.

## Data Collection and Processing
- Data was collected from multiple sources, including IRS Form 990 XMLs, Census data, HUD Crosswalks, and NCCS Business Master Files.
- Python scripts were developed to scrape, clean, and transform raw XML data into structured CSV files.
- Exploratory Data Analysis (EDA) was conducted to identify patterns, correlations, and insights.

## Data Sources
- **IRS Form 990 / 990-PF datasets** ([IRS Website](https://www.irs.gov))
- **NCCS Business Master File** ([NCCS Website](https://nccs.urban.org))
- **HUD Crosswalks Datasets** ([HUD Website](https://www.huduser.gov))
- **Census Datasets** ([Census Website](https://www.census.gov))
- **Guidestar/Candid** ([Guidestar Website](https://www.guidestar.org))

## Interactive Dashboard
The project's results are visualized using Tableau Public. The dashboard enables users to explore various aspects of the grant-making process, including:
- Demographics of grants received by counties
- Grant distribution trends by sector
- Grantmaker analysis and financial statistics
- Geographic breakdown of grants received vs. given

### Access the Tableau Dashboard:
[**Philanthropy Southwest Grants Analysis Dashboard**](https://public.tableau.com/app/profile/ankit.basu5156/viz/PhilanthropySouthwestGrantsAnalysisDashboard/DemographicsDashboard)

## How to Refresh the Dashboard
1. Download and install **Tableau Public** on your local machine.
2. Download the `.twbx` file from Tableau Public.
3. Open Tableau Public and go to the **Data Source Tab**.
4. Select the updated CSV files as data sources.
5. Refresh the dashboard to update visualizations.
6. Publish the updated version to Tableau Public.

## Findings & Insights
- **93% of grants** are generated in Metropolitan Statistical Areas (MSAs), and **89%** of those grants are received in MSAs, leaving micropolitan areas underserved.
- **Public, Societal Benefit** organizations receive **45.7% of total grants**, making it the largest sector.
- Most grants remain within the same state, county, and CBSA regions.
- Texas contributes **49% of all grants** in the Southwest, followed by Colorado (**13.8%**) and Oklahoma (**9.5%**).
- **Private Grantmaking Foundations** contribute nearly **3x more funding** than other types of foundations.

## Challenges Faced
- **Data Incompleteness**: Lack of sufficient online data sources required extensive independent data gathering.
- **Categorization Issues**: Difficulty in categorizing grants due to unstructured text data.
- **LLM Classification Limitations**: Large-scale dataset classification using LLMs was ineffective due to a lack of domain-specific fine-tuning.

## Conclusion
This project successfully visualizes key granting patterns in the Southwestern U.S. through a Tableau dashboard. The analysis highlights disparities in grant distribution, especially the concentration of funding in metropolitan areas. These insights can help stakeholders make data-driven decisions to ensure equitable grant distribution.

---
For more details, visit our Tableau Public dashboard linked above.
