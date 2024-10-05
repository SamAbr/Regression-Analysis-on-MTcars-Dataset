# 🚗 Regression Analysis of the MTcars Dataset

**Author:** Samuel Abrha G.mariam  
**Date:** 2024-02-22  

---

## 📖 Overview

This project explores the relationship between **horsepower** (hp) and **miles per gallon** (mpg) using the **mtcars** dataset, featuring 32 cars from the 1974 Motor Trend US magazine.

---

## 📊 Key Features

- **Descriptive Statistics:** Mean, standard deviation, and five-number summary for mpg and hp.
- **Correlation Analysis:** Pearson correlation coefficient to assess the strength and direction of the relationship.
- **Regression Model:** Simple linear regression to predict mpg based on hp.

---

## 🔧 Technologies Used

- **R**: For data manipulation and analysis
- **tidyverse**: For data visualization and manipulation

---

## 📈 Installation

To run this analysis, ensure you have R and the following packages installed:

```r
install.packages("tidyverse")
install.packages("dplyr")
```

---

## 📄 Usage

1. Load the required libraries:
    ```r
    library(tidyverse)
    library(dplyr)
    ```

2. Load the **mtcars** dataset and perform the analysis.

3. Explore the **correlation** and **regression** outputs to understand the relationship between hp and mpg.

---

## 🎯 Key Findings

- **Strong Negative Correlation:** r = -0.776 indicates that higher horsepower leads to lower miles per gallon.
- **Regression Equation:**  
  **Predicted mpg = 30.10 - 0.0682 × horsepower**  
  This suggests that each additional horsepower reduces mpg by approximately 0.0682.

---

💬 **Thank you for checking out this analysis!** 🚀
