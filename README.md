# Label Prediction for News Articles

This project aims to predict news article's labels based on the semantic content of the article's text.

The repository contains:
  * one PDF with the description of the project
  * one .CSV file for reproducibility and 
  * three codes that were used in the project for the data collection, the data preparation, and the analysis.

I recommend first reading **'Machine_Learning_Project_Imre_Gémes.pdf'** to have an understanding of the project.
**'telex_scrape.ipynb'** contains the scraping code that I used to obtain the data.
**'telex_data_preparation.ipynb'** contains the data preparation and the exploratory data analysis.

You can skip these two codes and use the **'merged_df.csv'** file, the result of the data preparation. With this file, you can reproduce my results using the constructed models in **'models.ipynb'**.
**'models.ipynb'** contains four differnet models, constructed to predict article labels. These models are Logit, Bagging, Random Forest, and Gradient Boosting Tree models.
