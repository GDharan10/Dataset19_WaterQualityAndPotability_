# Water Potability Prediction

## Overview
This dataset contains water quality measurements and assessments related to potability, which is the suitability of water for human consumption. The dataset's primary objective is to provide insights into water quality parameters and assist in determining whether the water is potable or not. Each row in the dataset represents a water sample with specific attributes, and the "Potability" column indicates whether the water is suitable for consumption.

## Objective
The main objective of this dataset is to assess and predict water potability based on water quality attributes. It can be used for evaluating the safety and suitability of water sources for human consumption, making informed decisions about water treatment, and ensuring compliance with water quality standards.

## Columns
- pH: The pH level of the water.
- Hardness: Water hardness, a measure of mineral content.
- Solids: Total dissolved solids in the water.
- Chloramines: Chloramines concentration in the water.
- Sulfate: Sulfate concentration in the water.
- Conductivity: Electrical conductivity of the water.
- Organic_carbon: Organic carbon content in the water.
- Trihalomethanes: Trihalomethanes concentration in the water.
- Turbidity: Turbidity level, a measure of water clarity.
- Potability: Target variable; indicates water potability with values 1 (potable) and 0 (not potable).

## Dependencies
- pandas
- numpy
- scipy
- matplotlib
- seaborn
- scikit-learn
- lazypredict

## Data Preprocessing
- Missing Value Handling: The pH and Sulfate columns are filled using backward fill (`method='bfill'`) and forward fill (`method='ffill'`) respectively. Trihalomethanes missing values are filled with the mean.

## Machine Learning Model
- Model: RandomForestClassifier
- Evaluation Metrics:
  - Precision Score: 0.6316
  - Recall Score: 0.2981
