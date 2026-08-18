# Open for business
This is my analysis and modelling of the Business Formation Statistics data provided by the US Census Bureau. The latest available data as of the creation of this repository is up to June 2026. The modelling is therefore centered around predicting July 2026 numbers.

## Installation
The libraries used include: 
- numpy
- pandas
- matplotlib
- seaborn
- scikitlearn, and
- shap

## Project motivation
This is a project I undertook as part of Udacity's Data Scientist Nanodegree. I worked on the aforementioned dataset to answer the following questions:
1. How does location affect the volume of business applications in the US?
2. Which business application types are more prevalent?
3. Given data up to June 2026, can we predict the numbers for July 2026?

## File description
There is one notebook that contains all the work described above.

## Results
The results of my analysis and modelling were as follows:
- The top 10 states in terms of business application volumes also have more than 50% of the total number of business applications.
- BA is the most recurring type of business application, with HBA coming in second.
- A Random forest model was used to predict July 2026 values based on January-June 2026 data.
- SHAP values indicate that January was the most influential feature in the prediction.
For more information, the results are extensively discussed in an article that can be found [here](https://medium.com/@humura.bliss/open-for-business-84e33ac7972d?postPublishedType=initial).

## Acknowledgments
Credit to Udacity for providing all the necessary resources and guidelines to complete this project, and to the US Census Bureau for the Business Formation Statistics, which can be found [here](https://www.census.gov/econ/bfs/current/index.html).
