# Capstone Project: Restaurant Inspection Result with Yelp API

### Forward
The goal of this project is to predict the inspection score (grade) of NYC restaurants using Department of Health and Mental Hygiene (DOHMH) New York City Restaurant Inspection Results data and Yelp API.  Within this repository, you will find a documented process for sourcing, cleaning, modeling, and combining Yelp data with the inspection data.  The models and methods contained here are intended for use by DOHMH NYC government representative for reference but we invite and encourage any NYC restaurant to use this analysis to predict what there inspection score (grade) might be based on details about the restaurant and customer created yelp data.

# Executive Summary

### Problem Statement
New York City is the biggest city on the east coast of the United States and there are tons of different kinds of foods and restaurants in the melting pot. With the huge food market, NYC restaurant inspection is one of the most important issue since there are various ways to cook, store, and serve different kinds of food. I resolved to tap into this wealth of information, and use it to create a tool to provide NYC restaurant inspectors by applying statistical models with some recommendations. (although a savvy user could use this analysis as a reference to predict the inspection score (grade) of their own restaruant!). 

### NYC OpenData
- [**DOHMH NYC Inspection Results**](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j)
- [**New York State ZIP Codes-County FIPS Cross-Reference**](https://data.ny.gov/Government-Finance/New-York-State-ZIP-Codes-County-FIPS-Cross-Referen/juva-r6g2)

### Project Files and Workflow
- [1.Data_Collection](https://github.com/ggoo156/project_capstone/blob/master/code/1.data_collection.ipynb)
- [2.Expolratory_Data_Analysis](https://github.com/ggoo156/project_capstone/blob/master/code/2.EDA.ipynb)
- [3.Preprocessing](https://github.com/ggoo156/project_capstone/blob/master/code/3.Preprocessing.ipynb)
- [4.Modeling & Conclusion](https://github.com/ggoo156/Project_capstone/blob/master/code/4.Modeling_classification_B.ipynb)

### Conclusion and Recommendation
- One unit higher in restaurant rating will decrease the chance to get **C** grade by 23%.
- During the summer season, the probability to get **C** will be increased by 50%.
- Manhattan area tends to have worst inspection score than other boroughs.
