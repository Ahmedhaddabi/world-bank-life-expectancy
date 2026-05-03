# World Bank Life Expectancy Prediction

## Motivation
Life expectancy is one of the most important indicators of a country’s overall well-being.
This project explores how economic and social factors such as GDP, population,
CO₂ emissions, and internet usage relate to life expectancy across countries.
Using World Bank development indicators, a machine learning model is built to
predict life expectancy and understand which factors matter most.

## Questions of Interest
1. What socioeconomic factors are most strongly related to life expectancy?
2. How does economic development (GDP per capita) influence health outcomes?
3. Can life expectancy be accurately predicted using development indicators?

## Dataset
The dataset comes from the **World Bank – World Development Indicators (WDI)** and includes
country-level data on:
- Life expectancy
- GDP per capita
- Population
- CO₂ emissions
- Internet usage

## Files in This Repository
- `notebook.ipynb`: Jupyter notebook containing data exploration, cleaning, modeling, and evaluation.
- `data/`: Folder containing the cleaned World Bank dataset.
- `README.md`: Project overview and summary.
- `images/`: Visualizations used in the analysis and blog post.

## Methodology
This project follows the **CRISP-DM** process:
1. Business Understanding
2. Data Understanding (EDA & visualizations)
3. Data Preparation (cleaning and feature selection)
4. Modeling (regression model)
5. Evaluation (R², MAE, RMSE)
6. Deployment (example prediction scenario)

## Results Summary
The final model shows that GDP per capita and internet usage have strong relationships
with life expectancy. The regression model is able to explain a significant portion
of the variation in life expectancy across countries.

## Example Prediction
The model was used to predict life expectancy for a hypothetical country with
medium GDP, moderate emissions, and growing internet access, demonstrating how
development improvements can translate into better health outcomes.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Acknowledgments
- World Bank Open Data
- Udacity Data Science Nanodegree
