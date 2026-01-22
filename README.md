# Data_Analysis_Final-Exam_Group5

## Introduction

This project analyzes a health dataset to identify factors associated with diabetes risk. Using Python and standard data analysis techniques, it examines health indicators, lifestyle behaviors, medical history, and demographic characteristics. The project is conducted for academic purposes and demonstrates practical skills in data preprocessing, analysis, and interpretation.


## I. Problem Being Solved

Diabetes is a major public health issue influenced by multiple health, lifestyle, and demographic factors. This project focuses on analyzing a structured health dataset to identify variables associated with diabetes prevalence. The objective is to explore patterns in health indicators, behaviors, and demographic data that may be linked to diabetes risk within a population.


## II. Object-Oriented Design

The project follows an object-oriented design to ensure clarity, modularity, and reusability. Classes are used to represent core components such as data loading, preprocessing, analysis, and visualization. Objects created from these classes manage tasks including data cleaning, feature encoding, statistical analysis, and result visualization.

The target variable is binary, where 0 represents the absence of diabetes and 1 represents the presence of diabetes. Input features include health indicators (BMI, blood pressure, cholesterol, glucose levels), lifestyle factors (physical activity, diet, smoking habits), medical history variables, and demographic information (age and socioeconomic status). Relationships between objects allow processed data to flow logically through each stage of the analysis.


## III. How to Run the Program

The project is developed and executed using **Visual Studio Code**. All analyses are performed through Python scripts that can be run from the VS Code integrated terminal.

**Steps to run the project:**

1. Install Python on your system.
2. Open the project folder in Visual Studio Code.
3. Open the integrated terminal in VS Code.
4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

5. Run the main Python script:

```bash
python main.py
```

Make sure all required libraries are installed before execution.


## IV. Assumptions and Design Decisions

Several assumptions guide this project. Missing values are handled using appropriate statistical methods, and outliers are treated based on their potential impact on analysis results. Feature selection focuses on variables relevant to diabetes risk, and transformations are applied to improve interpretability.

The analysis relies on exploratory data analysis, descriptive statistics, and visualizations. It is assumed that the dataset is representative of the studied population. Observed relationships indicate associations and do not imply causation. The results are intended for academic and illustrative purposes.


## Conclusion

Overall,Body Mass Index (BMI), blood pressure, cholesterol, glucose levels, physical activity, diet, smoking habits, age, and socioeconomic factors are associated with diabetes risk. These findings highlight the main health and lifestyle variables influencing diabetes within the dataset. The results are illustrative and do not imply causation.
