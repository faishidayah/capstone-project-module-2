# Supermarket customer analysis

This project conducts analysis based on customer demographics. This project aims for Supermarket to know shopping preferences based on consumer groups. So that it allows the company to focus on segments that have the greatest potential and optimize marketing and develop products that are relevant to certain consumers.

In general, the project includes:

### Data Understanding & Data cleansing
- Data understanding in the form of a deeper understanding of the data in the dataset so that we can find out the anomalies contained in the dataset.
- Data cleansing in the form of handling missing values, duplicate data, outliers, changing the name of the value in the categorical column to use a more general term, converting the data type of the column containing the date to the datetime[ns] data type, creating a new column that will be used in the data analysis process, and dropping unused columns
### Data analysis 
- insights gained based on the analysis conducted:
  1. The customer age group is dominated by Middle Age (46-64 years) as many as 49% of total customer.
  2. The most education level of customers is bachelor as many as 50% of total customer. 
  3. The most marital status of customers is married as many as 64% of total cuatomer.
  4. customer income ranges from 0 - 120000 but the most is in the range of 40000-70000 per year.
  5. customers with the Low Income income group are the most with a total of 67% of total customer.
  6. the pattern of product purchase proportions based on demographics for all products almost has the same pattern. where the largest proportion is wine then meat. and the smallest proportion is oranges. The reason why wine is the largest proportion of purchases is because drinking wine in many countries, including the US, has become a tradition. The tradition of drinking wine is often associated with social events, dinners and other special events. a combination of cultural factors, lifestyle trends, marketing, and high purchasing power make many people in the US willing to spend more money on wine. This causes wine consumption to be more valuable than other basic needs in many consumer circles in the US.
  7. Income variable has the strongest correlation to Total Purchase with a value of 0.79. This value is a strong positive correlation, which means that the higher the income, the higher the customer's purchase. Then for the total children variable, it gets a value of -0.39. This value is a moderate negative correlation, which means that the fewer the total children, the more the customer purchases, and vice versa. The Age Group and Education variables have a very weak correlation to total purchases.

### Recommendations for stakeholders
1. Optimize marketing for products that are not selling well, such as fruit products. Optimization can be done by doing Product Bundling Packages. Bundling packages can be in the form of combining the best-selling products with products that are not selling well in the form of bundling (packages), so that customers get more attractive offers.
2. The number of customers who have children around 75% of the total customers. Based on the analysis, the more children a customer has, the fewer purchases they make. This problem can be overcome by launching Educational Products or Packages for Families and Children. because by adding products or services that are more relevant to families, especially for customers who have children, it can increase purchases for customers, especially those who have children.
3. Launch New Variants or vary the packaging size of the best-selling products. This strategy can be done on Wine products because this product has the highest proportion of purchases based on customer demographics. It can also be done on meat products because the proportion of purchases is the second highest.
4. Create member cards to target customers in the low-income category. because the number of customers in the low income category is the most, around 66% of the total customers. and based on the analysis, this category has a low average purchase, even very far compared to the middle income category. This strategy can be in the form of providing exclusive discounts or cashback for members. For example, a purchase of so much will get a interest discount.
5. Optimizing the shopping experience for middle age customers (46-64 years) and Older Adults (over 64 years) in physical stores and websites. This optimization is intended to make the shopping experience in physical stores and websites easier and simpler because the majority of customers are 45 years and over. An example of optimization in physical stores is providing various payment methods, including cash and non-cash payments, as well as fast payment features to facilitate transactions. and an example of optimization on the website such as simplifying the checkout process by reducing the number of steps required to complete a purchase.


packages used:
- pandas 🐼
- numpy #️⃣
- matplotlib.pyplot 📊
- seaborn 📉

 
