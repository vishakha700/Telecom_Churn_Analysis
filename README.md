
### **Telecom Churn Analysis**  

The Telecom Churn Analysis project identifies factors influencing customer churn in a telecom dataset and provides actionable insights to reduce churn rates. **Churn** refers to customers discontinuing the service. Using Python, the analysis includes the following steps:

---

### **1. Data Understanding and Cleaning**  
- **Data Exploration**: The dataset includes customer demographics, service usage, and account information such as tenure, internet service type, and monthly charges.  
- **Data Cleaning**: Missing values and duplicates were handled to ensure accuracy. Variables were formatted appropriately for analysis.

---

### **2. Exploratory Data Analysis (EDA)**  
Visualizations were created to understand churn behavior based on key features:

- **Phone Service**:  
  - Churn rate: **21%** for customers with phone service vs. **25%** for those without it.

- **Internet Service**:  
  - Fiber Optic users had the highest churn rate at **42%**, compared to **18%** for DSL users and **5%** for customers without internet service.

- **Online Security & Backup**:  
  - Customers without online security churned at **46%**, while those with it had a churn rate of only **15%**.  
  - Similarly, customers without online backup services churned at **38%**, compared to **20%** for those with it.

- **Tech Support**:  
  - Customers without tech support churned at **40%**, while those with tech support churned at **17%**.

- **Streaming Services**:  
  - Customers without streaming TV services churned at **20%**, while those with streaming TV churned at **30%**.  
  - For streaming movies, churn was **22%** for those without the service and **28%** for those with it.

- **Contract Type**:  
  - **Month-to-month contracts** had a churn rate of **43%**, significantly higher than **11%** for one-year contracts and **3%** for two-year contracts.

- **Payment Method**:  
  - Customers using electronic checks churned at **45%**, while those using other payment methods (credit cards, bank transfers, mailed checks) churned at **15%-20%**.

- **Tenure and Monthly Charges**:  
  - **Short-tenure customers (1-6 months)** churned at a rate of **50%**, while customers with tenure over 24 months churned at only **5%**.  
  - Customers paying **$90 or more monthly** had a churn rate of **40%**, compared to **10%** for those paying below $50.

---

### **3. Key Insights**  
- **Fiber Optic Internet users** are more likely to churn (**42%**) than DSL users (**18%**).  
- Lack of add-ons like **Online Security** and **Tech Support** significantly increases churn rates.  
- Customers on **month-to-month contracts** or using **electronic checks** are at higher risk of churn.  
- **High monthly charges** and **short tenure** are major churn indicators.

---

### **4. Churn Percentages**  
- **Overall churn rate**: **26%** of customers have churned, while **74%** remain active.  
- **Service-specific churn rates**:  
  - Fiber Optic Internet: **42%**  
  - DSL Internet: **18%**  
  - No Internet: **5%**  
  - No Online Security: **46%**  
  - No Tech Support: **40%**

---

### **5. Recommendations**  
- **Reduce churn among Fiber Optic users** by addressing quality or pricing concerns.  
- Promote **Online Security** and **Tech Support** add-ons to customers, as these services reduce churn significantly.  
- Offer incentives for **long-term contracts** to encourage retention and reduce the high churn rate of month-to-month plans.  
- Target customers with **short tenure** and **high monthly bills** by offering personalized discounts or loyalty rewards.  
- Educate customers about the benefits of non-electronic payment methods to improve retention.



