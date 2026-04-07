# 4.1 Research Questions

* **Proportion Analysis (Z-test):** "Is the proportion of students who felt sad or hopeless for two weeks or more in 2007 different from the 2005 benchmark of 28.5% ($p_0 = 0.285$)?"
  
* **Mean Analysis (T-test):** "Is the mean BMI percentile of students in 2007 different from the historical average of 65.0 ($\mu_0 = 65.0$)?"

# 4.2 Variable Definition

### Variable 1: SadOrHopeless (Categorical)
* **Variable Name:** `SadOrHopeless`
* **What it measures:** Depressive symptoms (feeling sad or hopeless almost every day for 2+ weeks in a row).
* **Valid Codes Used:** * `1`: Yes
    * `2`: No
* **Handling of Missing Values:** All missing values (NaN) and invalid responses are excluded using `.dropna()`.
* **Final Sample Size:**13,845**

### Variable 2: BMIPCT (Continuous)
* **Variable Name:** `BMIPCT`
* **What it measures:** Body Mass Index percentile of the student.
* **Valid Codes Used:** Continuous numerical values from 0.0 to 100.0.
* **Handling of Missing Values:** Observations with missing BMI data are excluded.
* **Final Sample Size:**13,062**
