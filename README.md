# Heart Disease Data Analysis

This project focuses on analyzing heart disease data using R to uncover patterns and insights through data visualization. The analysis is based on a publicly available dataset of cardiovascular health indicators, with the aim of answering specific research questions related to heart disease prevalence.

## Dataset

The dataset used for this analysis, [Heart Disease Dataset](https://www.kaggle.com/datasets/volodymyrgavrysh/heart-disease), contains clinical and demographic variables such as:
- **Age**
- **Sex**
- **Chest pain type (cp)**
- **Resting blood pressure (trestbps)**
- **Serum cholesterol (chol)**
- **Fasting blood sugar (fbs)**
- **Resting electrocardiographic results (restecg)**
- **Maximum heart rate achieved (thalach)**
- **Exercise-induced angina (exang)**
- **Oldpeak (ST depression induced by exercise)**
- **Number of major vessels colored by fluoroscopy (ca)**
- **Thalassemia (thal)**
- **Target**: Indicates the presence of heart disease.

## Key Questions Explored

### 1. Age and Heart Disease
- **Question**: How does the age distribution differ between individuals with and without heart disease?
- **Approach**: A dual-coloured histogram was created to visualize the age distribution for individuals with and without heart disease. This revealed which age groups are most affected.
![image](https://github.com/user-attachments/assets/d01ca419-3e33-4e27-93ae-d638f945dfcc)


### 2. Gender Differences in Heart Disease
- **Question**: Is there a significant difference in the prevalence of heart disease between males and females?
- **Approach**: A bar chart with 95% confidence intervals was used to compare heart disease prevalence between genders.
![image](https://github.com/user-attachments/assets/49806109-31e8-4f9b-b89c-ff893fab28a1)


### 3. Chest Pain Type and Heart Disease
- **Question**: What is the relationship between chest pain type and heart disease?
- **Approach**: A stacked bar chart was employed to explore how different chest pain types correlate with heart disease presence.
![image](https://github.com/user-attachments/assets/6b25df4c-dd93-4862-984c-41226726ee79)


## Exploratory Analysis
In addition to the initial questions, the project explored:
- **Maximum heart rate (thalach) across different age groups**.
![image](https://github.com/user-attachments/assets/2295e224-9457-4ba2-a51c-dc42e53586ce)

- **Interaction effects between cholesterol levels (chol) and resting blood pressure (trestbps)** and their combined impact on heart disease prevalence.
![image](https://github.com/user-attachments/assets/40ce9df5-49f7-4552-9605-f2fc88fb6c38)



## Visualization Techniques
Interactive visualizations were created using **ggplot2** and **plotly** in R, including:
- **Histograms** for age distribution.
- **Bar charts** for gender comparison.
- **Scatter plots** to explore relationships between variables like maximum heart rate, cholesterol, and blood pressure.

## Conclusion
The analysis confirmed significant findings:
- Age and gender are strong factors in heart disease, with older individuals and males being more affected.
- Chest pain types also have a clear relationship with heart disease prevalence.
- Additional insights were gained from the maximum heart rate analysis and the interaction between cholesterol and blood pressure.

The project highlights the effectiveness of data visualization in healthcare analytics, providing a deeper understanding of heart disease risk factors.

## Files
- **data_cleaning.R**: Handles data preparation and cleaning.
- **data_analysis.R**: Contains the statistical analysis and modeling.
- **data_visualisation.R**: Responsible for generating the visualizations.
