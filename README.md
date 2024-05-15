# Pizza Insights with Power BI

## Description

This project utilizes Power BI to visualize a dataset of pizza sales, aiming to uncover trends in sales, employee performance, and product performance.

## Tools Used

- **Power BI**: Used for visualization.
- **Power Query**: Employed for data cleaning and constructing a snowflake schema.

## Dataset

- `Fact_Order`
- `Dim_Pizza`
- `Dim_Date`
- `Dim_Time`

## Questions from Stakeholders

1. **Sales Trend Analysis**: Analyze sales trends over time to identify patterns, seasonal variations, or anomalies. This analysis should cover daily, weekly, and monthly sales performance, including year-over-year changes to gauge growth or decline.
2. **Working Performance**: Determine which hours and days of the year yield the highest pizza sales.
3. **Product Performance**: Assess the performance of different pizza categories and specific pizzas within those categories by quantity sold and revenue generated. Identify top-selling and underperforming products to adjust the product offering.
4. **Price Sensitivity Analysis**: Examine which pizza sizes are popular and most profitable. Based on this analysis, are there pricing strategies that could be implemented to increase profits? Provide any recommendations for marketing strategies.

## Sale trend analysis
![power_bi_sale_trend](https://github.com/phildinh/pizza_power_bi/assets/169891895/15449437-156d-46ad-82af-d73f74b1b204)

- The sales trend dashboard indicates that while the total number of orders increased in Quarter 3, revenue did not follow the same trend. In detail, August shows a higher order volume compared to November, yet this is not reflected in the revenue, which is higher in November. 

- Specifically, August depicted a lower pizza quantity than November, with the majority being Large-sized, despite having the smallest average order value in the period. Conversely, the Large-sized pizzas generated more value than Medium and Small sizes, explaining the significant differences in the sales trends.
- Additionally, major holidays like Black Friday and Thanksgiving in November lead to increased purchases, as evidenced by the average quantity per order being 2.3.

###Recommendation:

- To boost revenue, it is crucial to increase the average order value. Encouraging customers to spend more by upselling additional products, such as drinks and snacks, could be effective. 

- As the data indicates, Extra Large-sized pizzas generate the most revenue. Therefore, focusing sales efforts on upsizing between Large and Extra Large pizzas could substantially increase profits.

## Working Performance
![Screenshot 2024-05-15 195808](https://github.com/phildinh/pizza_power_bi/assets/169891895/2750492b-90ae-4378-9147-d300e703b3d3)

- The visualizations reveal that Friday achieves the highest totals in both orders and revenue, while Sunday records the opposite. Peak hours are observed during lunchtime, between 12 PM and 1 PM, which is the busiest time, and dinner time occurs from 5 PM to 7 PM.

- Additionally, Friday and Saturday show roughly double the total orders compared to other days in the 8 PM to 10 PM slot.
Furthermore, the time slots from 9 AM to 10 AM and from 11 PM exhibit very low order quantities, contributing minimally to the store's revenue.

### Recommendations:
![1](https://github.com/phildinh/pizza_power_bi/assets/169891895/1aa698ef-ca1b-4e72-b6b8-243b0299855b)

- Proper staff allocation is essential to ensure timely production and customer service satisfaction, especially on Fridays and Saturdays from 8 PM to 10 PM.
- Additionally, special attention should be paid to holidays and special days to ensure timely service and efficient production.
- Consider adjusting the store's operating hours, opening at 11 AM and closing at 10 PM, to maximize profit by reducing unproductive time and the associated need for extra wages after 10 PM. 
- Training staff with ability to handle multiple role to adapt heavy works in peak hours.

## Product Performance
![Screenshot 2024-05-15 200315](https://github.com/phildinh/pizza_power_bi/assets/169891895/65bab58b-8660-4d7a-a0c4-cb3d7b84ecd0)

- According to the product performance visualizations, the Classic category exhibits the highest volume of orders, with the Classic Deluxe pizza demonstrating the most significant order volume. The least number of orders and revenue is associated with the Brie Carrer pizza from the Supreme category, while the Thai Chicken pizza from the Chicken category generates the most revenue. 
- Notably, the total quantity of Medium-sized pizzas sold is higher than that of Small-sized ones by 8.3%, yet there is a substantial difference in revenue of approximately 40% between the two sizes. Moreover, the Large-sized pizzas account for the majority of the revenue.

## Price Sensitivity Analysis
![Screenshot 2024-05-15 200723](https://github.com/phildinh/pizza_power_bi/assets/169891895/653e41d3-7cd2-4878-82a8-e3682a4ac10a)
![Screenshot 2024-05-15 200738](https://github.com/phildinh/pizza_power_bi/assets/169891895/d039b231-4531-4e0d-b99f-7862da1dde56)
###Categories, size and ingredient

- Tables (3) and (1) show that pizzas from the Classic category have the highest sales quantities, with the small, medium, and extra-large sizes being particularly popular. Additionally, the Veggie pizza is the best seller in the large size category. With this data, the company can strategically stock ingredients and prepare pizza bases to meet customer demand.
- Tables (1) and (2) reveal that the large size is the most popular and generates the most revenue for the company. While the extra-large size has the highest average revenue per item as per table (7), its sales are quite low. To boost the sales of the extra-large size, we could implement promotions and increase marketing efforts.

### Should we remove the Brie Carre Pizza?
From table (6), the Brie Carre Pizza, available only in a small size, commands a high selling price—approximately double that of other pizzas—and contributes to better revenue compared to other small-sized options.
### Price and AVG revenue for size and categories
- Observing the small sizes in model (1), the Classic category ranks as the best-selling, closely followed by the Supreme category. However, model (4) indicates that the average revenue for Classic's small size is lower than the overall average for small sizes shown in model (7). Table (6) reveals that the selling price of the Classic category is the lowest among all categories, while the Supreme category's high average revenue is primarily due to the Brie Carre Pizza.
- A potential solution is to increase the price of small-sized pizzas in the Classic category or to introduce a promotion where purchasing a Brie Carre Pizza could lead to a discount of 30-50% on a small-sized pizza from the Classic category.
- For medium-sized pizzas, models (1) and (4) suggest a similar pattern to the small-sized Classic category, though the selling quantity among categories is not significantly different. Therefore, increasing the price for the Classic category's medium-sized pizzas could lead to higher profits.
- Moving to the large sizes, model (1) shows that the Veggie category has the highest sales volume, but model (4) indicates that its average revenue is lower than the overall average for large sizes presented in model (7). Increasing the price of large-sized Veggie pizzas could be a beneficial strategy.
- Conversely, the Supreme category's large-sized pizzas display a high price and average revenue according to models (4) and (5), yet the quantity sold is low as per model (1). Reducing the price might be an effective approach to increase sales.
### In summary
Increase the price of small and medium-sized pizzas in the Classic category.
Raise the price of large-sized pizzas in the Veggie category.
Lower the price of large-sized pizzas in the Supreme category.
Offer a deal where purchasing a Brie Carre Pizza will grant a 30-50% discount on a small-sized pizza from the Classic category.

## License

Specify the license under which the project is released

## Contact Information

For further information, collaboration, or inquiries, feel free to contact [Phil Dinh](mailto:dinhthanhtrung2011@gmail.com).
