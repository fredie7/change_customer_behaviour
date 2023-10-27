# A MACHINE LEARNING MODEL BUILT TO TWEAK CUSTOMER BEHAVIOR IN A SEEMINGLY FOREDOOMED BUSINESS THAT WAS ON THE VERGE OF LOSING A HUGE NUMBER OF CUSTOMER BASE.

## A super store giant seeks to find out and nullify factors debilitating against her business and figure out what works best for them, in efforts to optimizing sales and maximizing profit potential.
This project breeds some incisive analytics and points through the right direction in unravelling a business model that optimizes profit potential through a surge in sale numbers using the Lasso Regression model.
Here's a step-wise progression on pointers to the aforementioned business solution:
* Imported project dependencies
* Imported dataset
* Visualized the first 5 rows to have an idea of the inherent features and inputs
* Generated an informative overview of the data types
* Renamed columns as some of names seemed broken
* Dropped the row_id column for its insignificance
* In order to spread analysis on factors behind unprofitable customer behaviour, I had to consider figuring out the nummber of days from order placement until delivery
* I also had to consider the price-per-item as wwll in efforts to guage customer bias
* I was also important to calculate the total expenditures for each customer
* Caught a sight of possible numerical columns since machine learning models work best with numbers
* Viewd possible outliers on quantity purchases to have an idea on the biases in demand
* A link to the below analysis with visualization would be provided somewhere below as you read along
* Checked for numerical distribution across the numerical column and found that the "quantity" column was scewed-right due to lower bound distribution as compared with the other features. This is due to constraints imposed on prices and discounts from the obvious single category of customers on the "sales" chat. This seemed likely due to the fact that other categories of customers were not getting as much discount as evident on the "discount" chat. Hence, this calls for a revision of discount of discount incentives allotted to customers across board.
* Next, I established a correlation between the numeric features and found a positive inverse correlation between "sales" and "spent"(customer spend), but also note that the outsome was based on "discount biases" attached to a single category of customers.
* Explored the categorical features
* Closely examined the relationship between "categories" and "sales" and found that there had never been a corresponding performance on sales of "office appliances" and "furniture" as much as "technology products"
* Examined the relationship between customer segment and sales and butressed the idea that marketing and discounts incentive efforts need be spread towards "home office" category of customers and "cooperate segment" of customers
* Encoded categorical features since machine learning is most potent with numbers
* Identified and removed outliers from the dataset
* Defined training and test dataset
* Scaled the dataset for uniform distribution of numeric values
* Split dataset
* Built models using Linear, Ridge and Lasso Regression algorithms, and chose to stick with Lasso Regression model for it's highest metric score value and performance.
* Created a new dataset obtained from test result that closes the gap on uneven appropriation of discounts and optimizes sales across board. Though, this came at a cost of some changes in price per item across board but the new business model promises a surge in record "sale" value of 85,741 as against the previous 85,324.
* More detailed analysis with accompanying visuals can be accessed from the following link below:
<a href="https://github.com/fredie7/change_customer_behaviour/blob/main/sales_pred.ipynb">https://github.com/fredie7/change_customer_behaviour/blob/main/sales_pred.ipynb</a>
