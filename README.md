# Everythn-Data-Capstone
A repo of my capstone project for the Everythn Data Program **Capstone** project.

## Overview
This project explores predictive modelling in the context of online learning programs. Using enrollee data from a previous cohort, I developed a classification model to predict the likelihood of successful program completion based on various participant attributes such as age, gender, motivation, intended study hours, years of experience, and test performance.

The project demonstrates a structured approach to data-driven decision making particularly in identifying meaningful questions from the data and translating them into testable hypotheses. With most MOOCs recording less than 15% completion rates, I hope this inspires instructors to try and predict which of their students are likely to complete the program and give attention to those flagged as potential drop outs.

## Key Objectives
- To analyze participant-level attributes and identify factors associated with program completion.
- To build a robust classification model capable of predicting outcomes using realistic educational data.
- To evaluate model performance and interpret which variables contribute most to the prediction.


## Tech Stack
- **Python**
- **pandas** – Data manipulation and preprocessing  
- **matplotlib** & **seaborn** – Exploratory data visualization
-  **NLP libraries** to process responses from the students
- **Gradient Boosting (GB)** & **Support Vector Machines (SVM)** – Classification algorithms

---

## Methodology
1. **Exploratory Data Analysis (EDA)** – Examined distributions, relationships, and patterns in enrollee attributes.  
2. **Feature Engineering** – Prepared features based on engagement and intent metrics.  
3. **Model Building** – Trained and compared Gradient Boosting and SVM classifiers.  
4. **Evaluation** – Assessed performance using appropriate classification metrics (accuracy, precision, recall, F1-score).

Throughout this process, I aimed to not only optimize performance metrics but also to interpret model outputs to derive actionable insights for program design and learner support.

---

## Reproducibility
Due to privacy considerations, the training datasets used in this project are **not publicly available**.  
However, the repository contains scripts and notebook templates that can be adapted to similar datasets.
