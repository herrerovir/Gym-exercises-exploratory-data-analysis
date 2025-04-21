# 🏋🏽 Exploratory Data Analysis of Gym Exercises

This repository contains an exploratory data analysis (EDA) of gym exercises using Python.

## 📚 Table of Contents

- [Introduction](#intro)
- [Goal](#goal)
- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Dependencies](#dependencies)
- [How to Run the Project](#how-to-run-the-project)
- [Repository Structure](#repository-structure)
- [Technical Skills](#technical-skills)
- [Dataset](#data-set)
- [Data Cleaning](#data-cleaning)
- [Data Exploration](#data-exploration)
- [Data Visualization](#data-visualization)
- [Insights](#insights)
- [Future Work](#future-work)

## 📌 Intro

This data analysis project focuses on exploring data from a CSV dataset using Python.

The goal of this work is to explore and analyze the dataset to obtain valuable information about gym workouts. The analysis process covers key steps such as data loading, data cleaning, data exploration, data analysis, and data visualization using Python.

## 🎯 Goal

The ultimate goal of this project is to explore the CSV file dataset to obtain all relevant information about a large collection of gym exercises.

Once the data is loaded, it will be cleaned and preprocessed to undergo univariate and bivariate exploration, to then display and visualize the significant results obtained.

Through the exploration and analysis of the data, it is expected to answer the following questions:

- Most trained muscle groups
- Most frequently used equipment
- Most performed type of exercise
- Most frequent type of user: beginner, intermediate, or expert
- Most used muscle group and equipment in the different exercise types
- User segmentation

## 🛠️ Project Overview

- **Data Loading**: Import the dataset into Python for further analysis.
-  **Data Cleaning**: Prepare the dataset for further exploration, removing inconsistencies and handling missing data.
-   **Data Exploration**:
   - Univariate analysis: Analyze each variable separately.
   - Bivariate analysis: Examine the relationship between two variables.
- **Data Visualization**: Use visualizations to effectively communicate the insights obtained.
- **Insights**: Conclude with key findings and insights drawn from the analysis.

## ⚙️ Dependencies

The following tools are required to run the project:

- Python 3
- Jupyter Notebooks
- Python libraries:
  - Numpy
  - Pandas
  - Matplotlib
  - Seaborn

## 💻 How to Run the Project

1. **Clone the Repository**

   Start by cloning the repository to your local machine using the following command:

   ```shell
   git clone https://github.com/herrerovir/Gym-exercises-exploratory-data-analysis.git
   ```

   Change to the project directory:

   ```shell
   cd Gym-exercises-exploratory-data-analysis
   ```

2. **Install Dependencies**

   Install the required dependencies listed in the `requirements.txt`:

   ```shell
   pip install -r requirements.txt
   ```

   This will install all necessary libraries such as pandas, numpy, matplotlib, and seaborn.

3. **Run the Jupyter Notebook**

   After installing the dependencies, you can run the Jupyter notebook to perform the data analysis. To start the notebook, use the following command:

   ```shell
   jupyter notebook notebooks/EDA-gym-exercises.ipynb
   ```

## 📂 Repository Structure

```
Gym-exercises-exploratory-data-analysis/
|
├── data/
│   ├── raw/
│   │   └── Gym-exercises-dataset.csv
│   ├── processed/
│   │   └── Gym-exercises-cleaned-dataset.csv
|
├── figures/
│   └── Equipment-efficiency.png
│   └── Equipment-per-difficulty-level.png
│   └── Equipment-per-exercise-type.png
│   └── Exercise-distribution-per-difficulty-level.png
│   └── Exercise-distribution-per-equipmente-type.png
│   └── Exercise-distribution-per-exercise-type.png
│   └── Exercise-distribution-per-muscle-group.png
│   └── Exercise-type-per-difficulty-level.png
│   └── Muscle-groups-frequency.png
│   └── Muscles-per-difficulty-level.png
│   └── Muscles-per-equipment.png
│   └── Ratings-distribution.png
|
├── notebooks/
│   └── EDA-gym-exercises.ipynb
|
├── requirements.txt
└── README.md
```

## 🧠 Technical Skills

The following skills were used throughout the implementation of this project:

- **Data Loading**: Importing and loading CSV data into Python.
- **Data Cleaning**: Handling missing values, duplicates, and outliers.
- **Data Exploration**: Conducting univariate and bivariate analysis to extract insights.
- **Data Visualization**: Using `matplotlib` and `seaborn` to visualize trends and relationships.

## 📊 Dataset

The dataset used for this analysis contains 2918 rows and 9 columns. The data is provided in a CSV file, which is available in the data/raw directory of this repository.

## 🧹 Data Cleaning

After loading the dataset, it was necessary to clean it to ensure its readability, integrity, and reliability. This involved:

- Modifying column names for better clarity.
- Handling missing values and duplicates.
- Correcting any inconsistencies or outliers in the data.

## 🔍 Data Exploration

In this stage, both **univariate** and **bivariate** analyses were performed:

- **Univariate analysis**: Analyzed each variable individually to understand its distribution and characteristics.
- **Bivariate analysis**: Examined relationships between variables to identify correlations or dependencies.

## 📊 Data Visualization

Data visualization was used to present the results of the analysis in a meaningful way. Using libraries like Matplotlib and Seaborn, various plots were created to visualize key insights.

## 💡 Insights

The project successfully analyzed a wide range of gym exercises. Here are some of the key findings:

- **Most trained muscle groups**: Abdominals, quadriceps, and shoulders are the most commonly trained muscle groups.
- **Most frequently used equipment**: Bodyweight exercises, dumbbells, and barbells are the most frequently used equipment in gym exercises.
- **Most performed types of exercise**: Strength training and stretching exercises are the most common.
- **User segmentation**:
  - **Beginners**: Primarily perform strength exercises with focus on quads, chest, and hamstrings, using bodyweight and barbells.
  - **Intermediate users**: Mostly engage in strength training with a focus on abdominals, quadriceps, and shoulders, utilizing bodyweight and dumbbells.
  - **Experts**: Focus on strength training targeting quadriceps, abdominals, and lats, with bodyweight and barbells as the main equipment.
- **Best-Rated Exercises by Muscle Group**
  - **Abdominals**: Landmine twist
  - **Biceps**: Incline Hammer Curls
  - **Quadriceps**: Single-Leg Press
  - **Shoulders**: Dumbbell front raise to lateral raise

## 📈 Future Work

There are several opportunities to extend this analysis further:

- **Build predictive models**: Use machine learning algorithms to predict workout effectiveness based on exercise type, equipment, and muscle groups.
- **Expand dataset**: Include additional data points such as user demographics or advanced workout metrics to enrich the analysis.
