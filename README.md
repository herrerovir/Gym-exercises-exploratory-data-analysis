# 🏋🏽 Exploratory Data Analysis: Gym Exercises

This repository contains an exploratory data analysis of gym exercises using Python. 

## Table of content
 - [Intro](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Introduction)
 - [Goal](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Goal)
 - [Project Overview](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Project-Overview)
 - [Dependencies](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Dependencies)
 - [Technical skills](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Technical-skills)
 - [Data set](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Data-set)
 - [Data Cleaning](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Data-cleaning)
 - [Data Exploration](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Data-exploration)
 - [Data Visualization](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Data-visualization)
 - [Insights](https://github.com/herrerovir/Exploratory-data-analysis-gym-exercises/blob/main/README.md#Insights)

## Introduction
This data analysis project focuses on exploring data from a csv dataset using Python. 

The goal of this work is to explore and analyze the dataset to obtain valuable information about gym workouts.

The analysis process covers key steps such as data loading, data cleaning, data exploration, data analysis and data visualization using Python. 

## Goal
The ultimate goal of this project is to explore the csv file dataset to obtain all relevant information about a large collection of gym exercises.

Once the data is loaded, it will be cleaned and preprocessed to undergo univariate and bivariate exploration to then display and visualize the significant results obtained. 

Through the exploration and analysis of the data, it is expected to find answers to the following points:

* Most trained muscle groups
* Most frequently used equipment
* Most performed type of exercise
* Most frequent type of user: beginner, intermediate, or expert
* Most used muscle group and equipment in the different exercise types
* User segmentation

## Project overview
   1. Data loading
   2. Data cleaning: prepare the dataset for further exploration
   3. Data exploration:
      - Univariate analysis
      - Bivariate analysis
   5. Data visualization of the information obtained during the exploration
   6. Insights

## Dependencies
The following tools are necessary to carry out this project:

* Python 3
* Jupyter Notebooks
* Python libraries: 
    - Numpy
    - Pandas
    - Matplotlib.pyplot
    - Seaborn

## Technical skills
The following skills were used throughout the implementation of this project:

* Data loading
* Data cleaning
* Data exploration
* Data visualization

## Data set
The data for this analysis is loaded from a csv file which can be found uploaded in this repository.

The dataset consists of:
* 2918 entries
* 9 columns

## Data cleaning
Once the dataset was loaded, it was required to clean it to ensure its readability, comprehensibility, integrity and reliability. 

For this purpose, column names were modified to make them more informative and improve readability, and missing values, duplicates and outliers were properly handled. 

## Data exploration
To obtain useful information from this dataset, an in-depth exploratory analysis was carried out. The dataset was analyzed in a univariate and bivariate basis.

Univariate analysis involved analyzing each variable in the dataset separately.

The bivariate analysis consisted of examining two different variables to determine whether there is a dependence or relationship between them.

## Data visualization
Data visualization plays a crucial role in data analysis, as it is the stage at which the conclusions drawn from the analysis are effectively communicated.

This stage focuses on creating visual representations of the insights gained during the analysis. The Python libraries Matplotlib and Seaborn were used for this purpose.

## Insights
The project successfully analyzed a wide range of existing gym exercises.

As expected from this project, the following questions were answered:

### **Most trained muscle group**
The muscle groups that are trained the most are: abdominals, quadriceps and shoulders.

![Exercise distribution per muscle group](https://github.com/user-attachments/assets/04c6ed2c-8abd-4744-aa3e-61ccc8dc1887)

### **Most frequent type of user: beginner, intermediate, or experts**
Intermediate level users have the widest amount of exercises available, followed by beginners.

![Exercise distribution per difficulty level](https://github.com/user-attachments/assets/b566fe38-b7d0-41d7-8d06-f9488b9eb57a)

### **Most performed type of exercise**
Strength and stretching are the most popular type of exercises.

![Exercise distribution per exercise type](https://github.com/user-attachments/assets/e79e98a1-cc22-441d-baea-3736be15cb54)

### **Most frequently used equipment**
Bodyweight (body only), dumbbells and barbells are the most used gym equipment.

![Exercise distribution per equipment](https://github.com/user-attachments/assets/f57dd1df-2d27-4e99-8d51-3ea594c527d2)

### **Most efficient equipment**
The most efficient equipments are bands and body only.

![Equipment efficiency](https://github.com/user-attachments/assets/8aab765f-b3e7-473f-b9f4-a082fb81968c)

The body part that used the most amount of equipment are the shoulders.

![equipment efficiency_muscle groups frequency](https://github.com/user-attachments/assets/4f62e966-641d-4eb1-8859-0b8666877494)


### **Most used muscle group and equipment in the different exercise types**
These are the most trained muscle group and gym equipment per exercise type.

| Exercise Type | Muscle Group | Equipment |
| ------------- | ------------ | --------- |
| Cardio | Quadriceps | Body only | 
| Olympic weightlifting | Quadriceps | Barbell | 
| Plyometrics | Quadriceps | Body only | 
| Powerlifting | Hamstrings | Barbell | 
| Strength | Abdominals | Body only | 
| Stretching | Hamstrings | Body only | 
| Strongman | Quadriceps | Other equipment | 

 Most targeted muscle group per exercise type
 
![Muscle group vs Exercise Type](https://github.com/user-attachments/assets/3a3650b9-ec88-474d-a73c-e33000d3f268)

Most used equipment per exercise type
![Equipment vs Exercise Type](https://github.com/user-attachments/assets/cb2c4035-4415-4865-94c1-910cc5e08f7b)


### **User segmentation**

* **Beginners:**
    - mainly perfom strenght exercises,
    - focus their training in: quads, chest and hamstrings, and
    - mostly use their own bodyweight and barbells.

* **Intermediate users:**
    - mainly train strength,
    - target: abdominals, quadriceps and shoulders, and
    - mostly use their own bodyweight and dumbbels.

* **Experts:**
    - focus on strength training,
    - their training targets mainly:quadriceps, abdominalss and lats, and
    - mostly use their own body weight and barbells.

### **Best rated exercises by Muscle Group**
These are the best rated exercises for each muscle group.

| Muscle Group | Exercise Name | 
| ------------ | ------------- |
| Abdominals | Landmine twist | 
| Adductors | Thigh adductor | 
| Biceps | Incline Hammer Curls | 
| Calves | Smith Machine Calf Raise | 
| Chest | Pushups | 
| Glutes | Barbell glute bridge | 
| Lats | Weighted pull-up | 
| Lower Back | Atlas Stones | 
| Middle Back | T-Bar Row with Handle | 
| Neck | Lying Face Down Plate Neck Resistance | 
| Quadriceps | Single-Leg Press | 
| Shoulders | Dumbbell front raise to lateral raise | 
| Traps | Smith machine shrug | 
| Triceps | Triceps dip | 

### **Full body strength beginner routine with barbell equipment**
These are the exercises for a perfect beginner full body strength routine in which only a barbell is necessary.

| Muscle Group | Exercise Name | 
| ------------ | ------------- |
| Abdominals | Bench barbell roll-out | 
| Biceps | Wide-grip barbell curl | 
| Calves | Rocking Standing Calf Raise | 
| Chest | Wide-grip bench press | 
| Lats | Barbell pull-over to press | 
| Lower Back | Stiff Leg Barbell Good Morning | 
| Middle Back | Yates Row Reverse Grip | 
| Quadriceps | Weighted Jump Squat | 
| Shoulders | Snatch-Grip Behind-The-Neck Overhead Press | 
| Triceps | Decline Close-Grip Bench To Skull Crusher | 

### **Full body stretch routine with no equipment**
This is a great full body stretching routine suitable for all levels of difficulty with no equipment required. 

| Muscle Group | Exercise Name |
| ------------ | ------------- |
| Abdominals | Stomach Vacuum |
| Abductors | Standing Hip Circles |
| Adductors | Groiners |
| Biceps | Seated Biceps |
| Calves | Peroneals-SMR |
| Glutes | Lying glute stretch |
| Lats | One Arm Against Wall |
| Lower Back | Superman |
| Middle Back | Rhomboids SMR |
| Neck | Side Neck Stretch |
| Quadriceps | Kneeling hip flexor stretch |
| Shoulders | Upward Stretch |
| Triceps | Tricep Side Stretch |

### **Top 5 exercises: abdominals, quadriceps and shoulders**

* **Abdominals:**

| Muscle Group	| Exercise Name	| Equipment |
| ------------- | ------------- | --------- |
| Abdominals	| Landmine twist	| Other |
| Abdominals	| Dumbbell V-Sit Cross Jab	| Dumbbell |
| Abdominals	| Dumbbell spell caster	| Dumbbell |
| Abdominals	| Suspended ab fall-out	| Other |
| Abdominals	| Bottoms Up	| Body Only |

* **Quadriceps:**

| Muscle Group	| Exercise Name	| Equipment |
| ------------- | ------------- | --------- |
| Quadriceps	| Single-Leg press | Machine |
| Quadriceps	| Clean from Blocks	| Barbell |
| Quadriceps	| Tire flip	| Other |
| Quadriceps	| Barbell Full Squat | Barbell |
| Quadriceps	| Push-press | Barbell |

* **Shoulders**

| Muscle Group	| Exercise Name	| Equipment |
| ------------- | ------------- | --------- |
| Shoulders	| Dumbbell front raise to lateral raise	| Dumbbell |
| Shoulders	| Single-arm palm-in dumbbell shoulder press | Dumbbell |
| Shoulders	| Clean and press | Barbell |
| Shoulders	| Clean and jerk | Barbell |
| Shoulders	| Single-arm kettlebell push-press | Kettlebells |
