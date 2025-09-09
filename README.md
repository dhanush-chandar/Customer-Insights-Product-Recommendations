# CardioGoodFitness: Customer Insights & Product Recommendations

## Overview  
This project performs an **exploratory data analysis (EDA)** on the **CardioGoodFitness** dataset to uncover customer trends, build profiles, and provide **data-driven business recommendations**. The goal is to help the company improve **marketing strategies**, **product positioning**, and **customer targeting**.  

---

## Dataset  
**File:** `CardioGoodFitness.csv`  
**Description:** The dataset contains customer information such as demographics, fitness levels, income, and treadmill product purchases.  

| Column           | Description                                                   |
|------------------|---------------------------------------------------------------|
| Product          | Model number of the treadmill                                  |
| Age              | Age of the customer (in years)                                 |
| Gender           | Gender of the customer                                         |
| Education        | Years of education completed                                   |
| Marital Status    | Single or Partnered                                            |
| Usage            | Avg. weekly treadmill usage (times/week)                       |
| Fitness          | Self-rated fitness score (1–5)                                  |
| Income           | Annual income of the customer                                   |
| Miles            | Expected miles to run                                           |

---

## Objectives  
- Perform **univariate** and **multivariate analysis**  
- Build **customer profiles** for each product  
- Identify **key demographics** for product sales  
- Provide **actionable business recommendations** for marketing and product strategies  

---

## Key Insights  
- **TM195** is the most popular product with **44.4%** of sales  
- **Age 25–35** contributes the largest customer segment  
- **Partnered customers** purchase more products than single customers  
- **TM798** attracts **high-income, fitness-oriented** customers → premium product positioning  
- Most products are purchased by customers with **16 years of education** (college-level)  

---

## Business Recommendations  
- **Targeted Marketing:** Expand campaigns to **20–25** and **35–40** age groups using social media  
- **Referral Programs:** Partnered customers can be leveraged to bring in **female customers**  
- **Product Strategy:**  
  - Maintain **TM195** as an all-rounder model  
  - Upgrade **TM498** with additional features to boost sales  
  - Position **TM798** as a premium, high-performance product  
- **Fitness Campaigns:** Attract moderate-fitness customers with **goal-oriented fitness plans**  

---

## Tech Stack  
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib  
- **Tools:** Jupyter Notebook, Power BI (optional for dashboards)  

---

## Setup Instructions  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/CardioGoodFitness_EDA.git
   cd CardioGoodFitness_EDA
2. Install dependencies:
   pip install -r requirements.txt
3. Open the notebook:
   jupyter notebook notebooks/CardioGoodFitness_EDA.ipynb

## Next Steps
- Build a Power BI dashboard for interactive visualization
- Develop a customer segmentation model using clustering
- Run A/B testing for targeted marketing campaigns

## Results
This analysis provides insights into customer behavior, product positioning, and marketing opportunities, helping the company increase sales and customer engagement with data-driven decisions.
