# Heart Disease Data Analysis

## Background and Overview

This project focuses on analyzing heart disease data using R to uncover patterns and insights through data visualization. The primary aim is to explore specific research questions regarding heart disease prevalence using a dataset of cardiovascular health indicators. The analysis employs **R** libraries such as `ggplot2` and `plotly` to visualize relationships between clinical and demographic variables and their impact on heart disease risk.

For technical details about the analysis and implementation, please refer to the following:

- [**data_cleaning.R**](https://github.com/pbahrami2/Heart-Disease-Data-Analysis/blob/main/data_cleaning.R): Handles data preparation and cleaning.
- [**data_analysis.R**](https://github.com/pbahrami2/Heart-Disease-Data-Analysis/blob/main/data_analysis.R): Contains the statistical analysis and modeling.
- [**data_visualisation.R**](https://github.com/pbahrami2/Heart-Disease-Data-Analysis/blob/main/data_visualisation.R): Responsible for generating the visualizations.

## Data Structure Overview

The dataset, available from [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/volodymyrgavrysh/heart-disease), contains various clinical and demographic variables, including:
- **Age**
- **Sex**
- **Chest pain type (cp)**
- **Resting blood pressure (trestbps)**
- **Serum cholesterol (chol)**
- **Fasting blood sugar (fbs)**
- **Resting electrocardiographic results (restecg)**
- **Maximum heart rate achieved (thalach)**
- **Exercise-induced angina (exang)**
- **ST depression induced by exercise (oldpeak)**
- **Number of major vessels colored by fluoroscopy (ca)**
- **Thalassemia (thal)**
- **Target**: Indicates the presence of heart disease.

## Executive Summary

This analysis of the Heart Disease Dataset aimed to explore factors contributing to heart disease using visualizations and basic statistical methods. Key findings indicated that:
- Older individuals, especially males, have a higher prevalence of heart disease.
- Chest pain type and other clinical variables, like cholesterol and blood pressure, significantly correlate with heart disease risk.
- Exploratory analysis of heart rate, cholesterol, and their interactions helped to uncover nuanced patterns, supporting more personalized healthcare approaches.

The project demonstrated how visualizations could effectively highlight critical risk factors, aiding in clinical decision-making.

## Insights Deep Dive

### 1. **Age and Heart Disease**
- **Metric**: Age distribution between individuals with and without heart disease.
- **Finding**: Individuals above 50 have a notably higher incidence of heart disease. 
- **Visualization**: A dual-coloured histogram revealed a skew toward older individuals for heart disease prevalence. This highlights the need for targeted preventive care in older populations.
![image](https://github.com/user-attachments/assets/d01ca419-3e33-4e27-93ae-d638f945dfcc)

### 2. **Gender Differences in Heart Disease**
- **Metric**: Comparison of heart disease prevalence between males and females.
- **Finding**: Males are more prone to heart disease, with a significantly higher prevalence across all age groups.
- **Visualization**: Bar charts with 95% confidence intervals showcased the gender disparity in heart disease.
![image](https://github.com/user-attachments/assets/49806109-31e8-4f9b-b89c-ff893fab28a1)

### 3. **Chest Pain Type and Heart Disease**
- **Metric**: Relationship between chest pain type and heart disease prevalence.
- **Finding**: Certain chest pain types (particularly types 2 and 3) were highly correlated with a higher incidence of heart disease.
- **Visualization**: Stacked bar charts were used to show how different chest pain types corresponded to higher or lower rates of heart disease.
![image](https://github.com/user-attachments/assets/6b25df4c-dd93-4862-984c-41226726ee79)

### 4. **Interaction Effects: Cholesterol and Blood Pressure**
- **Metric**: Interaction between cholesterol levels and resting blood pressure.
- **Finding**: High cholesterol, when combined with high blood pressure, showed a compounded effect on heart disease prevalence.
- **Visualization**: Scatter plots and heatmaps illustrated the relationship between these variables and their cumulative impact on heart disease risk.

## Exploratory Analysis
In addition to the initial questions, the project explored:
- **Maximum heart rate (thalach) across different age groups**.
![image](https://github.com/user-attachments/assets/2295e224-9457-4ba2-a51c-dc42e53586ce)

- **Interaction effects between cholesterol levels (chol) and resting blood pressure (trestbps)** and their combined impact on heart disease prevalence.
![image](https://github.com/user-attachments/assets/40ce9df5-49f7-4552-9605-f2fc88fb6c38)

## Recommendations

The findings from this analysis are crucial for improving heart disease prevention and care:
- **Personalized Healthcare**: Early interventions should be targeted at older adults, especially males, who exhibit symptoms of chest pain and have elevated cholesterol or blood pressure.
- **Preventive Measures**: Routine health checkups focusing on cholesterol and blood pressure management can help reduce the risk of heart disease.
- **Further Research**: A deeper exploration of the interactions between various clinical factors could lead to more effective treatment strategies for at-risk groups.
