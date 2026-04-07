# 4.2 Data Check and Recoding Rules

### 1. Recoding Rule for SadOrHopeless (Proportion Analysis)
* **Definition of Success:** A "Success" is defined as a student who responded **Yes** (indicating they experienced significant sadness or hopelessness).
* **Recoding Logic:**
    * Original Code `1` (Yes) -> **Recoded as 1 (Success)**
    * Original Code `2` (No) -> **Recoded as 0 (Failure)**
* **Verification Results:** * **Success Count (is_sad = 1): 4,153** 
    * **Failure Count (is_sad = 0): 9,692**
    * **Total (Check): 13,845**

### 2. Recoding Rule for BMIPCT (Mean Analysis)
* **Recoding Logic:** No recoding was applied to the `BMIPCT` variable. Raw percentile values are used directly for the T-test.

### 3. Data Check Summary
* **Raw Data Source:** `YRBS_2007.csv`
* **Cleaning Process:** 1. Filtered for target variables: `SadOrHopeless` and `BMIPCT`.
    2. Removed rows with missing values (NaN).
    3. Verified the final counts using `value_counts()`.
