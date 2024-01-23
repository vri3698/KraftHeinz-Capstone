# KraftHeinz-Capstone

**Project Title: Optimizing Order Fulfillment for Kraft Heinz**

### Project Timeline

<img width="800" height="500" alt="Screenshot 2024-01-23 at 2 26 27 PM" src="https://github.com/vri3698/KraftHeinz-Capstone/assets/157519502/b241a72d-f60e-4e94-bddd-5e2db4d4d961">


### Overview and Problem Statement
The Kraft Heinz Company is planning to establish a new distribution facility and has provided historical order data for analysis. The goal is to optimize the order fulfillment process by understanding customer behaviors and suggesting improvements to maximize asset utilization and minimize inventory policies.

### Exploratory Data Analysis Findings
- **Seasonal Patterns:** Identified a seasonal pattern with peak orders during the Thanksgiving period.
- **Ordering Behavior:** Stores tend to place more orders on weekdays in anticipation of weekend customer shopping.
- **Truck Utilization Rate:** Discovered a low overall truck utilization rate (20%).

### Two-Fold Approach and Recommendations

1. **Demand-side Optimization:**
   - *Metric Used:* Average order quantity across orders.
   - *Strategy:* Stratified stores based on order quantity and set a ratio threshold. Flagged stores below the threshold as potentially needing attention.
   - *Action:* Engage with flagged stores to understand ordering behavior and explore possibilities of increasing order quantity or aggregating orders.

2. **Supply-side Optimization:**
   - *Optimization Model:* Developed a model for truck loading, combining orders by days of the week and dispatching fully loaded trucks.
   - *Constraints Considered:* Weight, volume, and height constraints for optimal loading.
   - *Results:* Applied the model to ten stores, resulting in a 4x increase in utilization rate and a 78% reduction in average shipments.

### Recommendations
- **Combining Orders Strategy:** Combine orders placed on Mondays and Tuesdays, Wednesday, Thursday, and Friday, and Saturday and Sunday to achieve similar results across all stores.
- **Customer Engagement:** Engage with customers to understand their needs and preferences, especially those flagged for potential optimization.

### Benefits and Outcomes
- **Cost Savings:** Significant reduction in average shipments leading to cost savings.
- **Efficiency Improvements:** 4x increase in utilization rate demonstrates enhanced operational efficiency.
- **Customer-Centric Approach:** Valuable insights gained through customer engagement for better service alignment.

In conclusion, our data-driven approach, coupled with customer engagement, offers actionable insights for Kraft Heinz. The combination model for truck loading stands out as a practical and effective solution for optimizing operations, showcasing the potential for substantial cost savings and efficiency improvements.
