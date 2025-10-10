# Supply-Chain-Optimization
Machine Learning for Supply Chain Optimization: Using Predictive Models to Optimize E-Commerce Shipping

**Partner(s)/Contributor(s)**:<br>
Jorge Roldan, Stephanie Smith, Nikita Rogers

### Installation
 To clone the repository:
   ```sh
   git clone https://github.com/jorgeroldan5/Supply-Chain-Optimization.git
   ```

### Project Summary
An e-commerce shipping company is seeing 60% of deliveries arrive late, driving poor customer satisfaction. To determine what is causing the delays, a sample of 10,999 were analyzed and used to train a classification model. The logistic regression results show higher discounts are a primary driver of late delivery.

#### Project Objectives
1. Find drivers of lateness across product and logistics features.
2. Build an interpretable and accurate model to rank orders by late risk.
3. Provide actionable insights.

**Methods Used**<br>
• Exploratory Data Analysis • Data Visualization • Data Preprocessing • Feature Engineering • Machine Learning • Model Evaluation
 
**Technologies**<br>
• Python

### Data
**Source:** Gopalani, P. (2021). E-commerce shipping data [Data set]. Kaggle. https://www.kaggle.com/datasets/prachi13/customer-analytics<br>
**Rows:** 10,999 orders<br>
**Features:** `ID`, `Weight_in_gms`, `Discount_offered`, `Cost_of_the_Product`, `Mode_of_Shipment`, `Warehouse_block`, `Product_importance`, `Customer_care_calls`, `Customer_rating`, `Prior_purchases`, `Gender`<br>
**Target:** `Reached.on.Time_Y.N`: (1 = late, 0 = on-time)
