# Diabetes_Exploration_and_Prediction
## Project Overview:
This first part of this project explores statistical significance of various factors in predicting whether a women over the age of 21 has a diabetes diagnosis. Initial analysis determined that the number of pregnancies was statistically significant in differentiating individuals with and without diabetes, though insufficient as a standalone predictor. Additional factors, including glucose levels, BMI, age, and blood pressure, were also statistically significant based on p-values and u-stats. However, further analysis is needed to distinguish between different types of diabetes, as their distinct physiological mechanisms influence variable significance. 

The second part of this project investigates a dataset containing medical records of individuals diagnosed with various types of diabetes, but focused on differentiating type I vs type II diabetes. A random forest classification approach revealed fluctuating feature importance, with BMI, cholesterol, and age frequently ranking highest. BMI's relevance aligns with its role in insulin resistance and type 2 diabetes development, while age differentiates between type 1 and type 2 onset. Elevated cholesterol, particularly LDL, was also identified as a contributing factor, as visceral fat can impair insulin sensitivity. Interestingly, training and testing errors remained equal across different feature sets, warranting further investigation.

*Aside: This was one of the first data analysis projects I completed from start to finish by myself. Naively I didn't realize these datasets were most likely generated. Knowing this now, I don't believe the results are conclusive in what we see in real life as BMI is not a great measure of people's health.*

## Project Structure:
* **data/** : contains the raw data files.
* **diabetes_output3.ipynb** : jupyter notebook file containing analysis and codes.
* **insulin.png** : diagram of how/when insulin is released into the human body.
