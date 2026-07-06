![Iris](Iris banner.png)


# Iris: An Exploratory Data Analysis

This project explores the classic Iris dataset to discover patterns and relationships across the different flower species.

## Table of Contents
* [Project Overview](#project-overview)
* [Data Sources](#data-sources)
* [Tools](#tools)
* [Data Cleaning/Preparation](#data-cleaningpreparation)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Results/Findings](#resultsfindings)
* [Recommendations](#recommendations)
* [Limitations](#limitations)
* [References](#references)
* [Author](#author)

---

## Project Overview
The goal of this project is to analyze the physical properties of three iris flower species (Setosa, Versicolor, and Virginica). By using statistical summaries and data visualizations, the project demonstrates how features like petal and sepal lengths can be used to easily differentiate between these species.

## Data Sources
* **Iris.csv:** The primary dataset used for this analysis was sourced from [Kaggle](https://www.kaggle.com/). It contains 150 samples of iris flowers, four physical traits or feautures, and the species label.

## Tools
* **JupyterLab / Jupyter Notebook:** Environment used for interactive analysis.
* **Python:** Programming language.
* **Pandas & Numpy:** For data loading, manipulation, and inspection.
* **Matplotlib & Seaborn:** For plotting and visualization.

## Data Cleaning/Preparation
Before diving into analysis, the data went through the following quality checks:
1. Examined the dataset for **missing values** and found none.
2. Checked for and eliminated **duplicate values.** 
3. Dropped the `Id` column as it is irrelevant to the analysis.

## Exploratory Data Analysis
The analysis focused on answering several key questions:
* What is the overall distribution of sepal and petal measurements?
* Which physical features show the strongest correlation?
* How easily can the three species be differentiated based on combinations of features (e.g., Petal Length vs. Petal Width)?

## Results/Findings
* Iris-setosa is the smallest of the three species, while virginica is the largest.
* Iris-setosa appears notably distinguished (especially in petal length and petal width) from the other two.
* Iris-versicolor and Iris-virginica show more signs of overlap in their sepal measurements, and were more distinguishable in petal properties.
* The clearest/strongest correlation among paired features exist between petal length and petal width.

## Recommendations
* For machine learning classification tasks, give priority to **petal length** and **petal width** over sepal metrics, as they will prove more effective in prediction.

* Because Setosa is visibly separable, and the other two have only some overlap,simple linear models (like Logistic Regression) or simple decision trees will likely work better in terms of accuracy.

## Limitations
* The dataset contains only 150 records (50 per species), which is small for training highly robust generalized models.
* The data may not fully capture the real-world variations caused by different soil types, climates, or geographic regions.

### References

* [Mastering Iris Dataset Analysis with Python](https://bytemedirk.medium.com/mastering-iris-dataset-analysis-with-python-9e040a088ef4) 

* [Intro to Machine Learning with Python 2: Exploratory Data Analysis](https://youtu.be/6BagRiSY1ds?si=bCgpgT9Ear1-SdfK)
  
* [Iris Data Classification Tutorial / Project Resource](https://youtu.be/WesX_DNhToM?si=3Jsh8TZZhM4PW5QP) 

## Author

**Ibinabo Direh**

Machine Learning Specialist | Data Scientist

- 🔗 https://www.linkedin.com/in/ibinabo-direh
- 💼 https://github.com/ibinabo-direh
- 📧 ibinabo.id@gmail.com
