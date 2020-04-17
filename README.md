# House Price Prediction

## Problem Statement

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

So what actually contributes to the price of a house? There are the main easy attributes such as square footage, has a pool, neighbourhood, etc. But in truth there is so much more that influences it, and realtors need to understand everything there is to know about it in order to make an accurate price.

This project is intended to help us have a deeper understanding about what actually influences the price of houses and whether, based on these attributes we can effectively and accurately predict these prices. This could serve as a way of helping realtors make a better informed decision or even clients that want to know how much their perfect house would cost.

The data and the result should be able to answer:

1. What are the highest correlated features to the Sale Price?
2. Are people building bigger houses in recent years?
3. Do older houses tend to have less overall quality?
4. Are Foundations different throughout the years?
5. What is the best model to predict the prices of houses?

## Libraries

The libraries used for this project are:

**Processing**:
- pandas 
- numpy 

**Modelling**:
- xgboost 
- eli5
- sklearn

**Vizualization**:
- matplotlib
- seaborn

## Files

There are 4 files in this repository:

- train.csv (Training data containing all attributes and labels)
- test.csv (Test data contaning all attributes but no labels)
- House Sales.ipy (Jupyter Notebook containing Preprocessing, Analysis, Modelling and Results of the project)
- data_description.txt (File with the description of all attributes in the data)

## Conclusion Summary

1. It is effectively and somewhat accurately to predict the house prices using the data provided.
2. The usage of high correlated features to construct a reasonable preedicting model.
3. Results are more promissing using One Hot Encoding rather then Label Encoding.
4. From the three regression techniques used, the widely accepted XGBoost Regressor provides the best results.
5. The submission of the test data, using XGBoost Regressor, returned an accuracy of ......

## Acknowledgments

Special thanks to Kaggle for the dataset.



