# Kaggle Dataset: Country Clustering for Aid Allocation

## Problem Statement

HELP International is an international humanitarian NGO dedicated to fighting poverty and providing basic amenities and disaster relief in underdeveloped countries. With approximately $10 million in funds, the organization faces the critical task of strategically allocating these resources. To make data-driven decisions, we need to categorize countries based on socio-economic and health factors that influence their overall development. By clustering countries based on these conditions, we can allocate funds for disaster relief and assistance effectively. This problem involves unsupervised learning, where our goal is to create clusters of countries based on their unique characteristics.

## Aim

Our aim is to cluster countries based on numerical features, utilizing unsupervised learning techniques. This dataset presents an opportunity for exploratory data analysis (EDA), feature engineering, and clustering model implementation.

## Dataset Attributes

- **country**: Name of the country
- **child_mort**: Child mortality rate (per 1000 live births)
- **exports**: Exports of goods and services per capita (as a percentage of GDP per capita)
- **health**: Total health spending per capita (as a percentage of GDP per capita)
- **imports**: Imports of goods and services per capita (as a percentage of GDP per capita)
- **income**: Net income per person
- **inflation**: Annual inflation rate (measured as the growth rate of the total GDP)
- **life_expec**: Average life expectancy at birth
- **total_fer**: The number of children per woman (based on current age-fertility rates)
- **gdpp**: GDP per capita (calculated as the Total GDP divided by the total population)

## Notebook Contents

1. Dataset Information
2. Exploratory Data Analysis (EDA)
3. Summary of EDA
4. Feature Engineering
5. Modeling
6. Conclusion

## What You Will Learn

In this analysis, you will explore the following topics:

- Data visualization techniques.
- Feature engineering and dimensionality reduction using PCA (Principal Component Analysis).
- Comparison of K-Means Clustering, DBSCAN Clustering, and Hierarchical Clustering model performance.

## Column Information

Here's a summary of the columns in the dataset:

- `country`: Country names (167 non-null, object)
- `child_mort`: Child mortality rate (167 non-null, float64)
- `exports`: Exports as a percentage of GDP per capita (167 non-null, float64)
- `health`: Health spending as a percentage of GDP per capita (167 non-null, float64)
- `imports`: Imports as a percentage of GDP per capita (167 non-null, float64)
- `income`: Net income per person (167 non-null, int64)
- `inflation`: Annual inflation rate (167 non-null, float64)
- `life_expec`: Average life expectancy (167 non-null, float64)
- `total_fer`: Children per woman (167 non-null, float64)
- `gdpp`: GDP per capita (167 non-null, int64)

## Usage

This dataset can be used to identify countries in dire need of aid and resource allocation to reduce child poverty and child mortality rates worldwide. The insights gained from this analysis can inform decisions on where funding is most urgently required.

