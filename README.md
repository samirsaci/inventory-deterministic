## Inventory Management for Retail — Deterministic Demand 📈
*Build a simple model to simulate the impact of several replenishment rules (Basic, EOQ) on the inventory costs and ordering costs*

<p align="center">
  <img align="center" src="https://miro.medium.com/max/1280/1*GrAHw2d9Sa5qShf-cKhYYA.png">
</p>

For most retailers, inventory management systems take a fixed, rule-based approach to forecast and replenishment orders management.

Considering the distribution of the demand, the objective is to build a replenishment policy that will minimize your ordering, holding and shortage costs.
-Ordering Costs: fixed cost to place an order due to administrative costs, system maintenance or manufacturing costs in (Euros/Order)
- Holding Costs: all the costs required to hold your inventory (storage, insurance, and capital costs) in (Euros/unit x time)
- Shortage/Stock-out Costs: the costs of not having enough inventory to meet the customer demand (Lost Sales, Penalty) in (Euros/Unit)

### Article
In this [Article](https://www.samirsaci.com/inventory-management-for-retail-deterministic-demand/), we will present a simple methodology using a discrete simulation model built with Python to test several inventory management rules based assuming:
- Deterministic Constant Demand: D (Units/Year)
- Lead Time between ordering and replenishment (Days)
- Cost of shortage and storage (Euros/Unit)

### Problem Statement
As an Inventory Manager of a mid-size retail chain, you are in charge of setting the replenishment quantity in the ERP.

Based on the feedbacks of the store manager, you start to doubt that the replenishment rules of the ERP are the most optimal especially for the fast runners because your stores are facing lost sales due to stock-outs.

For each SKU, you would like to build a simple simulation model to test several inventory rules and estimate the impact on:
- Total Costs: how much does it cost to receive, store and sells this product?
- Shortages: what is the % of lost sales due to stock-out?

### Objective
1. Visualize the current rule used by the store's manager
2. Calculate the Economic Order Quantity and simulate the impact
3. Visualize the impact of lead time between ordering and receiving
4. Real-Time Visualization of COGS for each rule

### Data set
This analysis will be based on the M5 Forecasting dataset of Walmart stores sales records ([Link](
https://www.kaggle.com/c/m5-forecasting-accuracy)).

## Code
This repository code you will find all the code used to explain the concepts presented in the article.

## About me 🤓
Senior Supply Chain Engineer with an international experience working on Logistics and Transportation operations. \
Have a look at my portfolio: [Data Science for Supply Chain Portfolio](https://samirsaci.com) \
Data Science for Warehousing📦, Transportation 🚚 and Demand Forecasting 📈 

