Analysis about Profit from AWS SaaS Sales and Marketing Report

# Background
Amazon Web Services (AWS) is a cloud service provider that offers a range of product options, including Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). AWS derives profits through various business models and services that they provide to customers. AWS serves a diverse array of customers, encompassing both Business-to-Consumer (B2C) and Business-to-Business (B2B) categories. AWS provides services that can be utilized by a variety of organizations and users, including individuals, companies, governments, non-profit institutions, startups, large enterprises, and more.

They offer SaaS, which is a cloud-based software model, including database management services. They also provide IaaS for IT infrastructure, such as computing, storage, and networking resources delivered over the internet, and lastly, they offer PaaS with a platform-based cloud computing model. Each of these services has its own pricing model, signifying that every time customers use these services, AWS generates revenue. As a company grows following their utilization of AWS services, they tend to remain subscribed to AWS services, which can contribute to a sustained revenue stream for AWS.

# Problem Statement
After examining the profits obtained from the years 2020-2023, we have identified that the issue arises due to fluctuations in profit. For profits that experience a significant decrease, we can conduct an analysis to prevent substantial declines from occurring.

Columns
1. Row ID: A unique identifier for each transaction.
2. Order ID: A unique identifier for each order.
3. Order Date: The date when the order was placed.
4. Date Key: A numerical representation of the order date (YYYYMMDD).
5. Contact Name: The name of the person who placed the order.
6. Country: The country where the order was placed.
7. City: The city where the order was placed.
8. Region: The region where the order was placed.
9. Subregion: The subregion where the order was placed.
10. Customer: The name of the company that placed the order.
11. Customer ID: A unique identifier for each customer.
12. Industry: The industry the customer belongs to.
13. Segment: The customer segment (SMB, Strategic, Enterprise, etc.).
14. Product: The product was ordered.
15. License: The license key for the product.
16. Sales: The total sales amount for the transaction.
17. Quantity: The total number of items in the transaction.
18. Discount: The discount applied to the transaction.
19. Profit: The profit from the transaction.

# Conclusion and Recommendation
From the conducted analysis, we can draw conclusions about the most popular products and those yielding the highest profits:

- ContactMatcher had up to 1842 transactions with a median profit of $28.79.
- Alchemy was sold 86 times with a median profit of $1099.98.
- The top 3 customers generating the most negative profits were Bosch, Ford Motor, and Itochu.
- The top 3 customers with the highest number of transactions resulting in negative profits were Morgan Stanley, Bosch, and Itochu.
- The region with the highest frequency of negative profit transactions was APJ, amounting to -$21583.6618.
- The most frequent purchasers of Alchemy were Coca-Cola India, followed by Mondelez International in Canada, and Lowes in the Philippines, ranking as the top 3.
- Discounts applied to ContactMatcher sales included 80% for 233 transactions, 50% for 18 transactions, and 30% for 44 transactions.
- The most frequent Alchemy purchasers with the lowest profits were located in the APJ region, totaling $17819.8729.
- The lowest profit was associated with Allstate at -$2796.2935, while the highest was recorded for Valero Energy at $10308.6297.
- For customer Allstate, the quantity of ContactMatcher purchases was 411 with a frequency of 10 transactions specifically for the ContactMatcher product.
- The lowest decrease occurred in January 2021, while the highest was recorded in November 2022

Characteristics of ContactMatcher and Alchemy:

- ContactMatcher achieved the highest sales, but also had the highest incidence of negative profits, ranking second-lowest overall.
- Alchemy had the lowest sales but yielded the highest profits, never experiencing negative profit outcomes.
- A notable number of discounts were provided for the ContactMatcher product in the APJ region.
- The largest purchaser of Alchemy was Coca-Cola and the smallest was Daimler
- Alchemy's lowest sales occurred in the APJ region.
- The customer with the lowest profit was Allstate, whereas the highest was Valero Energy.
- Allstate demonstrated loyalty as a customer but contributed the lowest profit through ContactMatcher purchases
- ContactMatcher plays a significant role when observing the decline in profit that reaches its lowest point over a span of 4 years, as evidenced by the data

Characteristic Time of Profit
- When examining the sales trend, we notice a decline in sales at the turn of the year followed by an increase towards the end of the year. This pattern offers insights into potential causes, with ContactMatcher's role in the lowest sales contributing to the profit decline.

- Upon dissecting the data per year, we observe that in even years, low profits occur in Q1 and rise in Q3, while the opposite holds true for odd years. Notably, in 2021, there was also an increase in Q3.

# Recommendation
- Reducing Discounts for ContactMatcher Sales, Especially for Customers with High Transaction History
- The main focus is to enhance ContactMatcher features to cater to specific needs, particularly in the APJ region, with a cost-effective approach. Offer product trials to users and subsequently raise the price. Provide a discount for monthly subscriptions and a larger discount for annual subscriptions.
- Enhance marketing efforts in the APJ region, considering that the ContactMatcher, Alchemy, and overall product profitability is predominantly observed in this region
- It's important to focus on these time periods to identify factors contributing to profit fluctuations, including decreases and spikes. By analyzing the sales strategy, product offerings, promotional activities, and targeted regions of the periods with increasing or decreasing profits, we can derive valuable insights to enhance sales strategies

By reducing discounts, we can potentially boost profits and allocate funds towards enhancing features. This could also serve as an opportunity to gradually raise prices while appearing to offer discounts. The hope is that this approach will enable well-performing products to generate profits post-marketing. Additionally, introducing new features will contribute to greater product recognition and reach.
