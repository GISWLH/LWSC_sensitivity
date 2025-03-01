# Local Weighted Shapley Chain (LWSC) Sensitivity Analysis

## Overview
This project implements a Local Weighted Shapley Chain (LWSC) approach for machine learning model interpretation, focusing on feature importance analysis and model explainability.

## Model Interpretability Visualization
![Model Interpretability](https://imagecollection.oss-cn-beijing.aliyuncs.com/office/20250301161330.png)

## Project Structure

## Features
- Implementation of LWSC for feature importance analysis
- CatBoost model training and evaluation
- SHAP value visualization
- Comprehensive data processing pipeline

## Data Description
The project uses machine learning datasets stored in both CSV and Excel formats in the `data` directory:
- `machine_l.csv`: Primary dataset for model training
- `machine_l.xlsx`: Excel version of the dataset with additional metadata

## Installation
1. Clone the repository
2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage
1. Open `ml.ipynb` in Jupyter Notebook
2. Follow the step-by-step analysis process
3. Execute cells sequentially for model training and interpretation

## Model Analysis
- Feature importance evaluation using SHAP values
- Local interpretation of model predictions
- Weighted chain analysis for feature interactions

## Requirements
See `requirements.txt` for detailed package dependencies.

## Contact
For questions or collaborations, please contact:
- Email: hhuwlh@163.com

## License
This project is licensed under the MIT License - see the LICENSE file for details. 