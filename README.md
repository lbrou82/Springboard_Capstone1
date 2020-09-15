# Springboard_Capstone_1

**Description**:  

This is a repository for my first Capstone Project as part of the Springboard's Data Science Career Track Program. More information about the project is below. 

**Summary**:
This project sought to predict home prices in one area of Los Angeles County: South Bay. Home price information is helpful for a number of clients such as new home buyers/sellers, real estate agents, and new home builders. 

Data Wrangling and Exploratory Data Analysis (EDA) were done primarily using the pandas library in Python. The original dataset was manually downloaded from Redfin.com into 84 separate files. It was merged, cleaned and reduced to 13,631 sales, with 18 individual features, ranging from 2018 and 2020.

Some insights from the project include: 

- More homes were sold in the summer,  and there seems to be a price difference between homes sold in summer versus homes sold in other seasons. 

- The top two predictors of home prices in this area were Square Feet and Longitude (i.e. proximity to the ocean).

- Other predictors of home price include: Year Built, Lot Size, and whether a home is in a specific neighborhood, with homes in Hermosa Price being a larger predictor than other neighborhoods. 

- I was able to train a model using Random Forest Regression in scikit-learn to predict homes with an R2 of 0.84. Corresponding code for the project and other write ups (including slides) can be found in the project folders. 


**Project Components**: 

* /data   
    - /interim 
    - /processed: Cleaned dataset for modeling  
    - /raw: Includes original downloaded files from Redfin.com   
    
    
* /notebooks
    - 01.Capstone1_HomePrices_DataWranglingCode.ipynb
    - 02.Capstone1_HomePrices_DataStoryCode.ipynb
    - 03.Capstone1_HomePrices_ApplyStatisticsCode.ipynb
    - 04.Capstone1_HomePrices_InDepthAnalysisCode.ipynb  
    
* /reports
    - 00.Capstone1_HomePrices_ProjectProposal.pdf
    - 01.Capstone1_HomePrices_DataWrangling.pdf
    - 02.Capstone1_HomePrices_ApplyStatistics.pdf
    - 03.Capstone1_Milestone Report.pdf
    - 04.Capstone1_HomePrices_InDepthAnalysis.pdf  
    
* Presentation Slides: Capstone1_HomePrices_Presentation.pdf

* Final Report: Capstone1_HomePrices_FinalReport.pdf 
  
 
