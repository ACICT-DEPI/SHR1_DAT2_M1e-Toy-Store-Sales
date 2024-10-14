# Maven Toys Sales & Inventory Analysis Dashboard

## Data Overview

### Calendar Table
- This table includes all relevant dates, allowing for time-based analysis of sales trends and performance metrics.

### Inventory Table
- Contains information on the stock levels of toys available at each store.

### Products Table
- Lists all products available in the store, including their categories, costs, and prices.

### Sales Table
- Captures transaction details, including sales dates, quantities sold, and associated stores.

### Stores Table
- Contains details about each store location, including its name, city, and operational status.

## Data Structure

### Calendar Table
- **Key Fields**: `Date`

### Inventory Table
- **Key Fields**: `Store_ID`, `Product_ID`, `Stock_On_Hand`

### Sales Table
- **Key Fields**: `Sale_ID`, `Date`, `Store_ID`, `Product_ID`, `Units`

### Products Table
- **Key Fields**: `Product_ID`, `Product_Name`, `Product_Category`, `Product_Cost`, `Product_Price`

### Stores Table
- **Key Fields**: `Store_ID`, `Store_Name`, `Store_City`, `Store_Location`, `Store_Open_Date`

## ETL Process

### Extract
- Data extracted from Maven Analytics in CSV format.

### Transform
- Filtering rows (e.g., removing nulls or irrelevant data).
- Replacing values (e.g., handling missing data).
- Splitting/merging columns.
- Pivoting/Unpivoting data for better structure.
- Grouping data for aggregations (sum, count, etc.).
- Data type conversion (e.g., dates, decimals).
- Adding custom columns with calculated fields using Power Query’s M language.

### Load
- After transformation, the cleaned data is loaded into Power BI's data model for reporting.

## Data Modeling
- Create relationships between different data sources (fact and dimension tables).
- Define measures and optimize the data model for analysis.
- ![Screenshot 2024-10-08 135021](https://github.com/user-attachments/assets/7fba3dde-8e38-45a5-a0eb-4d8038ee01bf)

## Key Metrics to Be Analyzed
- Sold Units
- Previous Month Metrics
- Profit
- Orders
- Adjusted Price
- Revenue
- Adjusted Revenue
- Adjusted Profit
- Average Retail Price
- Stock on Hand
- Store Count
- Profit Margin
- Total Cost
- Inventory Cost

## Key Visualizations

### Sales Performance
- **Objective**: Assess overall sales trends and identify peak sales periods, particularly around holidays and promotional events.

### Inventory Analysis
- **Objective**: Analyze stock levels across different stores, ensuring popular items are adequately stocked while minimizing excess inventory.

### Profitability Analysis
- **Objective**: Evaluate profit margins across different product categories and identify best-selling items contributing to overall revenue.

### Comparative Metrics
- **Objective**: Compare current month performance against previous months to identify growth trends and areas for improvement.

## Dashboard Key Findings

### Overall Performance Page
- **KPIs**: 
  - Total sales
  - Total revenue
  - Total profit
  - Profit margin
- **Visuals**:
  - Line chart: Revenue per month
  - Column chart: Product categories
  - Table with drill-through to the top 15 products
  - Treemap: Revenue by store location
  - KPIs comparing with previous month
  - ![Screenshot 1: Overall Performance](https://github.com/user-attachments/assets/4e474a3c-90b4-4aa4-bc97-9cb12081fd46)

### Product Performance
- **Key Metrics**: Units sold, revenue, profit margin
- **Highlight**: Top-selling categories and products
- ![Screenshot 2: Product Performance](https://github.com/user-attachments/assets/bef76d1d-95ba-4879-9cee-b266eb367d50)

### Store Performance
- **Key Metrics**: Revenue, store count
- **Highlight**: High-performing locations and potential areas for improvement
-![Screenshot 3: Store Performance](https://github.com/user-attachments/assets/f38defc8-cea9-479c-9d06-c46e65bb8863)

### Inventory Analysis
- **Key Metrics**: Total inventory cost, average profit margin, total stock on hand
- **Highlight**: Inventory management challenges and opportunities
- ![Screenshot 4: Inventory Analysis](https://github.com/user-attachments/assets/433057b2-ad36-472e-af5a-2cfb4dfaee9b)

## Conclusions and Recommendations

### Key Findings:
- **Art & Crafts**: High sales volume, potential for further growth.
- **Colorbuds**: Best profit margin, ensure adequate stock and marketing.
- **Inventory Management**: Optimize practices to reduce costs and avoid stockouts.
- **Downtown Store**: Success factors driving sales should be replicated in other locations.
- **Toluca 1 Store**: Analyze success factors and apply to other stores.

### Recommendations:
- **Promote Art & Crafts**: Introduce new products and create bundles.
- **Focus on Colorbuds**: Ensure ample stock and feature in marketing.
- **Optimize Inventory**: Review management practices to avoid overstocking.
- **Learn from Downtown**: Analyze factors driving success and replicate them in other locations.
- **Invest in Toluca 1**: Support with marketing, inventory, and further analysis.

### Additional Recommendations:

1. **Seasonal Sales Strategy**:
   - **Insight**: Sales trends around holidays or school breaks could be capitalized upon.
   - **Recommendation**: Develop a seasonal sales plan, introducing holiday-specific products or bundles and using previous data to predict demand spikes.

2. **Product Lifecycle Management**:
   - **Insight**: Some products may have declining sales as they age.
   - **Recommendation**: Implement product lifecycle analysis to determine when products need to be discounted, replaced, or discontinued to maintain profitability.

3. **Customer Segmentation**:
   - **Insight**: Different stores or regions may have varying customer preferences.
   - **Recommendation**: Conduct customer segmentation to create tailored marketing strategies for different regions or demographic groups.

4. **Cross-Selling Opportunities**:
   - **Insight**: Certain product categories complement others.
   - **Recommendation**: Introduce cross-selling and up-selling strategies, promoting commonly purchased items together.

5. **Store Performance Benchmarking**:
   - **Insight**: High-performing stores can serve as benchmarks for other locations.
   - **Recommendation**: Benchmark low-performing stores against high-performing locations to identify best practices.

6. **Supply Chain Optimization**:
   - **Insight**: Stockouts or overstock situations may occur at different stores.
   - **Recommendation**: Streamline supply chain operations using demand forecasting and optimizing reorder points for each store.

7. **Staff Training and Development**:
   - **Insight**: Staff performance may impact store success.
   - **Recommendation**: Conduct staff training to improve customer service, upselling techniques, and inventory management.

8. **Digital Sales Channel Expansion**:
   - **Insight**: Competition from online retailers is growing.
   - **Recommendation**: Explore or expand digital sales channels, integrating inventory between physical and online stores.

9. **Localized Marketing Campaigns**:
   - **Insight**: Different cities may respond better to localized campaigns.
   - **Recommendation**: Invest in city-specific marketing initiatives to drive traffic to underperforming stores.

10. **Customer Feedback Integration**:
    - **Insight**: Customer satisfaction can inform product and service improvements.
    - **Recommendation**: Collect and integrate customer feedback into the analysis to continuously adapt products and services.

## Contact

For further inquiries or collaboration, feel free to reach out:

**Email**: mohamedelsayedfandoud@gmail.com

---

This dashboard highlights my expertise in transforming raw data into actionable insights through Power BI. It showcases advanced data modeling, dynamic visualizations, and interactive features that enable users to make informed business decisions.
