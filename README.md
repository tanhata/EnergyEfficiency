# Factors Impacting Energy Performance
##Introduction

In this project, we explore the following questions:

    Do variables such as glazing, surface area, overall height and relative compactness explain the variability in the total heating load of buildings?

    Are there variables that once introduces improve the accuracy of these features in prediction of heating load?

    Null Hypothesis: The variables of glazing, surface area, overall height and relative compactness do not affect heating load.

    Alternative Hypothesis: Heating Load in Buildings follow predictable patterns based on glazing, surface area, overall height and relative compactness.

## Background

Heating Load is an important factor that contributes to the energy performance of a building. In most climates, heating loads contribute the largest portion of energy usage in buildings, and are at the forefront of sustainability efforts. Heating loads will ideally be as low as possible and are often cut off at 15/kWh for passive house building principles.

We are using the data in this dataset to predict the heating load by using the various dependent variables that contribute to it. By analyzing this, we can identify points of intervention, to minimize heating loads to optimize passive energy usage.

Data Fields

    Relative Compactness,

    Surface Area,

    Wall Area,

    Roof Area,

    Overall Height,

    Orientation,

    Glazing Area,

    Glazing Area Distribution,

    Heating Load,

    Cooling Load

## Method

The data used was taken from UCI Machine Learning Repository. A dataframe was created and exploritory data analysis was performed. Four machine learning regression models were used; Linear Regression, Decision Tree, Random Forest and Support Vector Regression (SVR). The outcome variable for each model was 'Heating Load'. Each model was evaluated by calculating Mean Squared Error for both test and train, Root Mean Squared Error for both test and train, MSE Ratio, Relative Difference and R2 Score.
