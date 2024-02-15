# Sales-and-Operations-Planning-Project-using-python
This Python program simulates a sales and operations planning using the zero-stock level strategy. The program prompts the user to enter initial stock level, the number of months to plan, and the planned sales quantity for each month. Based on this input, it calculates and displays the required production quantity for each month.

## How to Use
1. Run the program.
2. Enter the initial stock level.
3. Specify the number of months to plan.
4. Input the planned sales quantity for each month as prompted.
5. The program calculates and displays the production quantity for each month based on the zero-stock level strategy.

### Explanation
**initial_stock:** Initial stock level for the product.
**num_months:** Number of months to plan.
**stock_level:** Current stock level, updated iteratively.
**planned_sales:** Sales quantity input for each month.
**production_quantity:** Calculated production quantity based on the zero-stock level strategy.

### Code Explanation
**Initialization** 
  -initial_stock: This variable stores the initial stock level of the product, which the user is prompted to input.
  -num_months: This variable stores the number of months for which the sales and operations planning will be conducted, entered by the user.
**Iteration Over Months**
  -A for loop iterates over each month, prompting the user for the planned sales quantity for that month.
**Production Quantity Calculation**
  -The production quantity for the current month is calculated based on the zero-stock level strategy. It considers the difference between planned sales and the available stock level.
**Stock Level Update**
 -The stock level is updated for the next month based on the production quantity and planned sales. It ensures that the stock level does not go below zero.
**Display Production Quantities**
-Finally, the program displays the production quantities for each month. It iterates through the list of production quantities and prints the results.

### AUTHOR
HELDANA NATNAEL AMBAW
