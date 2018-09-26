# A data science project predicting risk of toxic domoic acid events in California coast region
## Background
  While algae are important players in our ecosystem and the marine food web, under certain conditions, some algae can grow rapidly and release large amount of toxins that are harmful to human and other marine animals. Such biological events are known as harmful algal blooms. There are many types of harmful algal blooms; one of them is of particular interest to pacific coastal states of the U.S. That is Pseudo-nitzschia bloom, which produces the toxin, domoic acid. Domoic acid is a neurotoxin that can cause serious neurological symptoms, and sometimes death, if ingested. It is not only dangerous to swimmers and beachgoers, but it can also accumulate in seafood, especially shellfish such as crabs and clams. Therefore, high domoic acid level in coastal waters is not only a public health concern, but also an economic risk. For example, the harmful algal bloom in 2015 caused closures and delays of dungeness crab, rock crab season, which costed millions of dollars to the fishing/seafood industry.<br>
## Problem Statement
  Physical, chemical, and biological conditions such as water temperature, nutrients in the water, seasonality and other algae in the water may contribute to the formation of harmful algal blooms and the production of toxins. This project aims to use these data to predict risks of toxic algal bloom events in California coastal region.<br>
## Findings
  Data was obtained from multiple sources, combined and cleaned. There were 2,750 samples with 17 independent features. There were 120 samples that had dangerous levels of toxin.<br>
  Through exploratory data analysis, I found that Pseudo-nitzchia seriata cell concentration was the most important factor in causing toxic events. Chlorophyll concentration, water temperature, season also had significant impact on risk of toxic events.<br>
  I built logistic regression, support vector machines, random forest, gradient boost, and voting models to predict risk of toxic events. The voting model was the most useful among them, achieving 53% average precision and 91% accuracy.
## File structure
1. **Data wrangling, EDA, machine learning code and figures are in Jupyter Notebook form and can be found in notebooks/**<br>
2. Raw data are in data/raw<br>
3. Cleaned data are in data/cleaned_data.csv<br> 
4. **Find report and a presentation can be found in Final_report.pdf and presentation.pdf**
