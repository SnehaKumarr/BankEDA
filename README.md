# Banking Domain - Exploratory Data Analysis (EDA)

This project explores customer behavior and financial patterns in the banking domain using Exploratory Data Analysis (EDA) techniques. 
It aims to uncover trends, correlations, and insights that can be useful for customer segmentation, risk assessment, and business decision-making.

---

## Dataset

The dataset used for this EDA project is stored in the file: **`Banking.csv`**. 
It contains anonymized banking records of individual and business customers. It includes features related to income, age, account balances, deposits, loans, and more.


---

## Dataset Overview

| Feature Name              | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Age                      | Age of the customer                                                         |
| Estimated Income         | Approximate annual income                                                   |
| Superannuation Savings   | Retirement or pension fund account balance                                  |
| Credit Card Balance      | Current total balance across credit cards                                   |
| Bank Loans               | Total outstanding loans from the bank                                       |
| Bank Deposits            | Total funds deposited in the bank                                           |
| Checking Accounts        | Balance in the checking/current account                                     |
| Saving Accounts          | Balance in the customer’s savings account                                   |
| Foreign Currency Account | Amount held in a foreign currency account                                   |
| Business Lending         | Total borrowed under business loan products                                 |
| Properties Owned         | Number of properties owned by the customer                                  |


---

## Technologies Used

### 1. Data Analysis & Visualization Libraries
- **Pandas** – For data manipulation, cleaning, and exploratory analysis.
- **NumPy** – Used for numerical operations and array handling.
- **Matplotlib** – For creating basic visualizations like line plots, bar charts, and histograms.
- **Seaborn** – For advanced visualizations like correlation plots and regression plots.

### 2. Development Environment
- **Google Colab** – Used for running Python code, performing data analysis, and visualizing results in the cloud.

### 3. Programming Language
- **Python** – Used for all analysis tasks including data loading, preprocessing, visualization, and insight generation.

---

## Insights from EDA (Simplified)

1. **Deposits and Savings Go Hand in Hand**
   - People who deposit more money in the bank also tend to have higher savings.
   - This suggests a common habit of actively managing funds.

2. **Older and Higher-Income Customers Save More**
   - Older people and those earning more usually have more in their savings, retirement (superannuation), and checking accounts.

3. **Property Ownership Isn't Linked Strongly**
   - Owning property doesn't seem closely tied to income, age, or bank balances.
   - It may depend more on outside factors like inheritance or market conditions.

4. **Business and Personal Loans Are Somewhat Connected**
   - Some customers who take out business loans also have personal loans.
   - But overall, business loans behave differently from typical customer savings or deposits.

5. **Checking vs. Foreign Currency Accounts**
   - Customers who maintain higher checking balances don’t necessarily have much in foreign currency accounts.
   - Suggests separate use cases or customer types.

6. **Credit Card Balances Often Rise with Loans**
   - People with larger bank loans tend to have higher credit card debt as well.
   - May point to overall higher borrowing behavior.

7. **Income Ties in with Checking Behavior**
   - Those with higher estimated income tend to keep more in their checking accounts.
   - A sign of better financial flow or liquidity.
  
---

# Author
Sneha Kumar (NITRR)
