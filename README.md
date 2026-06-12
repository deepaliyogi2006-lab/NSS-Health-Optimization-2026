# Track 5: Data Analytics & Insights
## Challenge 5.3: Data-Driven Optimisation of a Social Program

### 📌 Project Overview
This project provides a data-driven framework to evaluate the efficiency of multi-intervention healthcare programs. Using an Ordinary Least Squares (OLS) multi-variable regression model, we analyze which program components drive the strongest maternal health outcomes (specifically, the **Institutional Delivery Rate**) while explicitly controlling for socio-economic confounders (Female Literacy and Poverty Rates).

### 📊 Key Statistical Findings (Effect Sizes)
Our statistical evaluation of 120 administrative districts isolated the following impacts:
* **ASHA Worker Home Visits (High Impact):** Each additional prenatal home visit increases the district's institutional delivery rate by **~2.5%**.
* **Mobile ANM Health Camps (Low Impact):** Each camp held yields a minor, non-justifiable increase of only **~0.3%**.
* **JSY Payout Delays (Negative Impact):** Every day added to administrative cash processing delays reduces facility births by **-0.15%**.

### 🚀 Resource Reallocation & Impact Potential
To satisfy the success metrics of this challenge, we developed a dynamic budget reallocation algorithm. 

**Results:**
* **Budget Shift:** 15% of funds are redirected away from expensive, underperforming Mobile ANM Camps into high-yield frontline ASHA worker home-visit incentives.
* **Financial Constraint:** Total program expenditure remains **strictly constant (0% budget increase)**.
* **Outcome Optimization:** The model projects a **$\ge 15\%$ relative improvement** in the Institutional Delivery Rate across targeted districts.

### 📁 Repository Structure
* `Health_Program_Optimization.ipynb` - The complete, reproducible Python code notebook (run via Google Colab) containing data synthesis, OLS regression modeling, and the budget optimization engine.
* `clean_dataset.csv` - The simulated baseline dataset representing the 120 administrative districts.

### 🛠️ Tech Stack & Methodology
* **Language:** Python 3
* **Libraries:** `pandas` (Data manipulation), `numpy` (Numerical simulation), `statsmodels` (Econometric regression framework)
* **Frameworks Reference:** J-PAL South Asia empirical playbook, controlling explicitly for correlation vs. causation.
