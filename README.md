# Adventure-Works-Power-BI-Project
## Overview:
AdventureWorks is a popular database from Microsoft used for learning and demonstrating various data technologies. The data represents the operations of a fictional company called Adventure Works, which manufactures and sells bicycles and related accessories.

## Data Source: 
https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms

## Modeling:
Star schema 
![image](https://github.com/nohamhmd/Adventure-Works-Power-BI-Project/assets/156810723/20356c31-bf33-4704-9212-18af9da435f7)

## Explaination for some measures:
Subtotal: This refers to the total sales price of the products ordered before applying any discounts or taxes. It's essentially the sum of the individual product prices multiplied by their respective quantities.

Total Tax: This represents the amount of sales tax applied to the subtotal. The exact tax rate might vary depending on the location specified in the dataset (sales tax rates can differ based on regions).

Total Freight: This refers to the transportation cost associated with delivering the order to the customer. It's essentially a fee for shipping and handling.

Total Due: This represents the final amount a customer owes for the order. It's calculated by adding the subtotal, tax, and freight:

## Some Insights:
![image](https://github.com/nohamhmd/Adventure-Works-Power-BI-Project/assets/156810723/7c9cea32-08a3-4373-87d7-75574675dc9a)
The graph suggests that there is a seasonal trend in order volume for Adventure Works, with sales peaking in the later months of the year. It also suggests that most orders are shipped around their due date.

