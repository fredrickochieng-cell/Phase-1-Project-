# Aviation Risk Analysis: Identifying Safer Aircraft Models for Purchase Recommendations  

## Overview  
This project analyzes global aviation accident records to identify safer aircraft models and provide actionable insights for a company planning to expand into the aviation industry. Using data cleaning, aggregation, and visualization, the analysis highlights accident frequency, severity, and operator/country trends to support data-driven business recommendations.  

## Business Understanding  
The primary stakeholder is the head of the new aviation division, who requires evidence-based guidance on which aircraft to purchase for commercial and private operations.  

**Key Business Questions:**  
1. Which aircraft models/types are safer?  
2. What are the accident trends over time?  
3. Which operators and countries account for the most accidents?  

## Data Understanding and Analysis  
**Source of Data:**  
[Kaggle – Aviation Accident Database (1919–2023)](https://www.kaggle.com/datasets/drealbash/aviation-accident-from-1919-2023)  
File used: `aviation-accident-data-2023-05-16.csv`  

**Description of Data:**  
The dataset contains aviation accident records with details such as date, aircraft type, operator, fatalities, location, country, and year. After cleaning, the final dataset consisted of **22,887 rows and 8 columns**.  

**Key Visualizations (from Notebook and Presentation):**  
- Top 10 aircraft types by accidents and fatal accidents  
- Accident trends over time (per year and per decade)  
- Top operators and countries by accident counts  

## Conclusion  
The analysis provides three major findings:  

1. **Aircraft Models:** The Douglas C-47 series has the highest accident and fatal accident counts, while modern models such as the Boeing 767 and 777 appear in very few accidents, suggesting safer performance.  
2. **Trends:** Accident counts peaked in the 1940s and have steadily declined over the decades, with the 2020s showing continued improvement in safety.  
3. **Operators and Countries:** Military operators (USAAF, USAF, RAF) and high-activity countries (USA, Russia, U.K.) dominate accident records, while commercial operators and other regions appear significantly safer.  

**Recommendation:**  
Avoid high-risk aircraft models and operators, and prioritize safer, lower-accident models and partnerships aligned with regions that demonstrate stronger safety performance. 
