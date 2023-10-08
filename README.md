# King County, WA housing price prediction modelling
**Author**: [Raye Yoo](mailto:y100265@gmail.com)

![housing](https://github.com/Rayeyoo1/housing_sales_analysis/blob/main/KC%20Cover.jpg)

## Project Overview
To provide business solutions that can be taken immediately through scientific data analysis, and offer suggestions that can maximise the business profits and customer satisfaction.
King County's population grew by 9.7% from the 1.9 million people who lived there in 2010, while the population in the US grew by 3.7% and the population in Washington grew 6.3% during that period.
Between 2010 and 2015, the county grew by an average of 1.9% per year. As an inevitable consequence, the demand for the real estate market & house flipping is getting higher.

## Business Problem
SKY Home Renovation and Extension is a King County-based home renovation company offering custom designs and quality builds.
Given the high market demand for house renovation & flipping, they have decided to establish a new consulting team to provide their potential customers with maximising house values based on data analysis.
They look forward to increasing business opportunities based on the most impactful features.

## The Data
#### Data source
King County house sales dataset (data/kc_house_data.csv), 2014-2015

#### Understanding data
Main data (variables):
* price: Prediction target
* bedrooms: Number of Bedrooms/House
* bathrooms: Number of bathrooms/bedrooms
* sqft_livingsquare: footage of the home
* sqft_lotsquare: footage of the lot
* floors: Tota floors (levels) in house
* waterfront: House which has a view to a waterfront
* condition: How good the condition is ( Overall )
* grade: Overall grade given to the housing unit, based on King County grading system
* sqft_basement: Square footage of the basement

#### Data Analysis Approach
Multiple Regression Analysis

## Key Points

The most effective feature is house grade scores in relation to the house values To maximise the house values in the market, need to aim to get a Grade score of 10.
The 2nd most effective feature is the size of the living area (Coef: 0.40, t: 45.96), and the 3rd most effective feature is the House condition Score which should be aimed at more than 3.
Based on the general analysis, The waterfront properties have much more higher values, which are highly correlated to the house values.

## Conclusion
#### Suggestion
* Focusing on interior and exterior renovation solutions as a main business model to maximise the house grades
* Identifying spare spaces in houses that can be turned into a part of a living area, impacts house values significantly and directly

#### Next step
* Analysing the latest data based on the residential grade/condition scoring system for better targeting
* Investigating further for return of Investment in the house flipping market
* Analysing geographical data for key neighbourhoods

## For more details
* [Presentation](https://github.com/Rayeyoo1/housing_sales_analysis/blob/main/presentation.pdf)
* [Jupyter Notebook](https://github.com/Rayeyoo1/housing_sales_analysis/blob/main/KC_housing_analysis.ipynb)
* [Data Source](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)
