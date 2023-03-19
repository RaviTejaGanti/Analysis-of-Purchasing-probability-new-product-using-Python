# Product Purchasing Analytics (Probability) using Python
Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range including machines such as treadmills, exercise bikes, gym equipment, and fitness accessories to cater to the needs of all categories of people
![alt text](https://github.com/RaviTejaGanti/Analysis-of-Purchasing-probability-new-product-using-Python/blob/main/Aerofit_Treadmill.jpg)
# Business Problem
Business Problem
The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.
# About Dataset
The company collected the data on individuals who purchased a treadmill from the AeroFit stores during the prior three months.The dataset has the following features:

Product Purchased:	KP281, KP481, or KP781 

**Age:**	In years 

**Gender:**	Male/Female 

**Education:**	In years

**MaritalStatus:**	Single or partnered

**Usage:**	The average number of times the customer plans to use the treadmill each week.

**Income:**	Annual income (in $)

**Fitness:**	Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape.

**Miles:**	The average number of miles the customer expects to walk/run each week

# Product Protfolio
The KP281 is an entry-level treadmill that sells for $1,500.

The KP481 is for mid-level runners that sell for $1,750.

The KP781 treadmill is having advanced features that sell for $2,500
# Overall Observations
1.Customers with high salary are intended in buying KP781 treadmill

2.Irrespective of the products bought males tend to have higher median of income than females.

3.Total males who purchased tredmills among the list of customers is ~57%

4.Total females who purchased treamills among the list of customers is ~42%

5.Males are little more dominant in purchasing KP481 and KP781 compared to females where the fact behind is the income. To drill down this more we are grouping the customers into males and females among them into different income groups to make our investigation more easier. Also Customers who are partnered and singles have different buying parity.

6.Mens income can indirectly effect the class of treadmill they buy. Like those who earn more income are more aged and also they are not intended to plan for more usage or miles in a week.

7.**The probability Males buying KP281 38.4% , KP481 29.8% , KP781 13.4%**
 
8.**The probability Males with status single buying KP281 44.1% , KP481 23.2% , KP781 32.5%**

9.**The probability Males with status partnered buying KP281 34.1% , KP481 34.1% , KP781 31.1%**

10.**The probability Females buying KP281 38.4% , KP481 29.8% , KP781 13.4%**

11.**The probability Females buying KP281 52.6% , KP481 41.1% , KP781 9.2%**

12.**The probability Females with single status buying KP281 43.3% , KP481 46.6% , KP781 10.0%**

13.**The probability Females with partner status buying KP281 58.6% , KP481 32.6% , KP781 8.6%** 

14. **_For more detailed analysis of how does salary of a customer effect the products being purchased. This invetigation is quite interesting you can better them in the jupyter notebook file inside._**

