# Sales-and-Operations-Planning-Project

In this project, we are going to simulate a sales and operations planning using the zero stock level strategy. Project is to demonstrate this with a Python program that asks the user to enter the following data:

- An initial stock level for a product
- The number of month(s) to plan for
- The planned/estimated sales quantity for each month

Based on this data, the required production quantity will be calculated as follows:

- If the estimated sales quantity is smaller than the stock level of the previous month, the production quantity is 0
- If the estimated sales quantity is larger than the stock level of the previous month, the production quantity is this difference

Below is an example execution of the program:
> Enter initial stock level: 600


> Enter number of month to plan for: 6


> Enter the estimated sales quantity for month 1: 400


> Enter the estimated sales quantity for month 2: 300


> Enter the estimated sales quantity for month 3: 250


> Enter the estimated sales quantity for month 4: 500


> Enter the estimated sales quantity for month 5: 350


> Enter the estimated sales quantity for month 6: 250




`The required production quantities to be achieved for each month are:`


> The required production quantity to be achieved for Month 1 is 0


> The required production quantity to be achieved for Month 2 is 100


> The required production quantity to be achieved for Month 3 is 250


> The required production quantity to be achieved for Month 4 is 500


> The required production quantity to be achieved for Month 5 is 350


> The required production quantity to be achieved for Month 6 is 250




Elaboration: \
The initial stock level is 600. 
- In the first month 400 pieces are sold. Therefore, nothing needs to be produced since there was leftover stock of 200 (= 600 - 400). 
- In the second month 300 pieces are sold. Since the stock level after the month 1 was 200, therefore 100 pieces needed to be produced. The stock level reduced to 0 (= 200 + 100 - 300). - In the third month 250 pieces are sold. Since the stock level after the month 2 was 0, therefore 250 pieces needed to be produced. The stock level reduced to 0 (= 250 - 250).
- In the forth month 500 pieces are sold. Since the stock level after the month 3 was 0, therefore 500 pieces needed to be produced. The stock level reduced to 0 (= 500 - 500).
- In the fifth month 350 pieces are sold. Since the stock level after the month 4 was 0, therefore 350 pieces needed to be produced. The stock level reduced to 0 (= 500 - 500).
- In the sixth month 250 pieces are sold. Since the stock level after the month 5 was 0, therefore 250 pieces needed to be produced. The stock level reduced to 0 (= 500 - 500).
