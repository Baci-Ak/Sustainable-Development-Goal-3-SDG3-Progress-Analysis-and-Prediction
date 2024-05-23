# Sustainable Development Goal 3 (SDG3) Progress Analysis and Prediction

## Overview
This repository contains the code and data for analyzing and predicting the progress and performance of Sustainable Development Goal 3 (SDG3) - Good Health and Well-being. The project aims to provide insights into health and well-being indicators associated with SDG3, develop a quantifiable representation of SDG3 progress, and apply machine learning techniques for prediction.

## Project Structure
- **data/**: This directory contains the datasets used in the project.
  - `SGD3_data.csv`: Final dataset used for analysis and prediction.
  - `SGD3_Cleaned_data.csv`: Cleaned dataset.
  - `SGD3_Standardized_data.csv`: Standardized dataset.
- **notebooks/**: This directory contains Jupyter notebooks with the code for various stages of the project.
  - `formatting_data.ipynb`: Code for formatting the dataset.
  - `Pre_processing.ipynb`: Code for data pre-processing.
  - `EDA.ipynb`: Exploratory Data Analysis.
  - `Model_development.ipynb`: Code for machine learning model development and evaluation.
- **README.md**: Project overview and instructions.
- **LICENSE**: License information for the project.

## Quantifiable Representation of SDG3 Progress
The SDG3 composite index, a quantifiable representation of SDG3 progress, was developed using a systematic approach:

1. **Indicator Transformation**: Standardization was applied to ensure that all indicators were on a comparable scale, facilitating their combination into a single performance variable.
2. **Distance Measure Calculation**: Euclidean Distance was used to quantify the difference between each country's indicator values and their respective targets, providing a measure of relative performance for each indicator.
3. **SDG3 Composite Index Calculation**: The composite index was computed by averaging the distance measures obtained from the Euclidean distance calculations. This provided an aggregated measure of performance, capturing a country's overall progress towards SDG3.

## Techniques Used
- **Data Formatting**: The dataset was formatted using Python, ensuring consistency and compatibility for analysis.
- **Data Pre-processing**: Data pre-processing techniques were applied to clean and standardize the dataset, including handling missing values and normalization.
- **Exploratory Data Analysis (EDA)**: EDA was performed to understand the patterns, distributions, and relationships within the dataset, focusing on SDG3 indicators.
- **Machine Learning Models**: Linear regression, Random Forest, and Support Vector Machines (SVM) were developed to analyze and predict SDG3 progress based on its indicators.

## Analysis and Outcome
- The analysis revealed variations in SDG3 indicators across regions and time periods, with improvements observed in maternal and child health outcomes.
- The SDG3 composite index showed an improving trend over time, indicating enhancement in overall performance.
- Disparities in SDG3 achievements among regions were identified, emphasizing the need for targeted interventions, particularly in Africa.
- Correlation analysis highlighted significant relationships between indicators and SDG3 progress, guiding the identification of key influencing factors.
- Machine learning models, particularly Random Forest, demonstrated effectiveness in predicting SDG3 progress, providing valuable insights for policymaking and decision support.

## How to Use
1. Clone this repository to your local machine.
2. Navigate to the `notebooks/` directory.
3. Open and run the Jupyter notebooks in sequential order for data formatting, pre-processing, EDA, and model development.
4. Follow the instructions and comments within each notebook for detailed guidance.
5. Make sure to have the necessary dependencies installed (e.g., Python, Jupyter, pandas, scikit-learn).
6. Refer to the `data/` directory for the datasets used in the project.

## Dependencies
- Python 3
- Jupyter Notebook
- pandas
- scikit-learn

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- The datasets used in this project were sourced from [The UN Repository>>](https://unstats.un.org/sdgs/dataportal/database).


