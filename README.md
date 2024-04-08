# Water Potability Prediction

## Overview
This dataset contains water quality measurements and assessments related to potability, which is the suitability of water for human consumption. The dataset's primary objective is to provide insights into water quality parameters and assist in determining whether the water is potable or not. Each row in the dataset represents a water sample with specific attributes, and the "Potability" column indicates whether the water is suitable for consumption.

## Objective
The main objective of this dataset is to assess and predict water potability based on water quality attributes. It can be used for evaluating the safety and suitability of water sources for human consumption, making informed decisions about water treatment, and ensuring compliance with water quality standards.

## Files
- **water_potability.csv**: Dataset containing water quality attributes and potability information.
- **Water_Quality_and_Potability.ipynb**: Jupyter notebook containing the analysis, preprocessing, modeling, and evaluation of the dataset.

## Dataset
The dataset contains the following columns:
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

## Approach
1. **Data Exploration**: Understanding the distributions, relationships, and patterns in the data.
2. **Data Preprocessing**: Handling missing values.
3. **Model Development**: Training machine learning models to predict water potability.
4. **Model Evaluation**: Assessing model performance using evaluation metrics such as precision and recall.

## Machine Learning Model
- Model: RandomForestClassifier
- Evaluation Metrics:
  - Precision Score: 0.6316
  - Recall Score: 0.2981

## Dependencies
- pandas
- numpy
- scipy
- matplotlib
- seaborn
- scikit-learn
- lazypredict

## Usage
1. Clone the repository: `git clone https://github.com/your-username/water-quality-potability-prediction.git`
2. Navigate to the project directory.
3. Open and run the Jupyter notebook `Water_Quality_and_Potability.ipynb` to explore the analysis and models.

## Conclusion
The project aims to provide insights into water quality parameters and assist in determining whether the water is potable or not. Further analysis and model refinement may be required to optimize performance and ensure reliable predictions.
