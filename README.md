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
An e-commerce shipping company is experiencing 60% late deliveries, leading to poor customer satisfaction. To understand the drivers of delay, we analyzed 10,999 shipment records and trained three classification models: (1) Logistic Regression, (2) Random Forests, and (3) Histogram-based Gradient Boosting. Based on recall and F1-score, Logistic Regression was the most appropriate for this use case. The model indicates that higher discounts are a primary driver of late delivery, suggesting promotions are creating demand spikes that the current supply chain cannot absorb.

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
