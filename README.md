***Customer Segmentation using RFM Analysis in Python***

**What is RFM?**

It is a score that consists of the initials of the words Recency, Frequency, and Monetary, and is formed by combining these three metrics after calculating them. It helps customers to analyze their current status and segment them according to these scores.

-   **Recency:** It gives information such as how long the customer has received service from the website/store, and how long he has been a member. The calculation is usually obtained by subtracting the last subscription date/last order date from today.
-   **Frequency:**  It is the metric that shows how often the customer makes a purchase and how often he logs into the site. It usually results in counting the order number/order code.
-   **Monetary:**  It is the sum of the customer’s expenses. The turnover brought to the e-commerce site can also be defined as the revenue collected after the services it receives.
-   ![image](https://user-images.githubusercontent.com/58263509/197523224-aec3254b-536d-4ced-8da4-7be65bcae5bf.png)

**Business Problem**

We load the data named ‘Online Retail II Data Set’ from the UCI Machine Learning Repository database and start the process.  [https://archive.ics.uci.edu/ml/datasets/Online+Retail+II](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)

**_Data Set Information:_**

This Online Retail II data set contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011. The company mainly sells unique all-occasion giftware. Many customers of the company are wholesalers.

**_Attribute Information:_**

-   InvoiceNo: Invoice number. Nominal. A 6-digit integral number is uniquely assigned to each transaction. If this code starts with the letter ‘c’, it indicates a cancellation.
-   StockCode: Product (item) code. Nominal. A 5-digit integral number is uniquely assigned to each distinct product.
-   Description: Product (item) name. Nominal.
-   Quantity: The quantities of each product (item) per transaction. Numeric.
-   InvoiceDate: Invoice date and time. Numeric. The day and time when a transaction was generated.
-   UnitPrice: Unit price. Numeric. Product price per unit in sterling.
-   CustomerID: Customer number. Nominal. A 5-digit integral number is uniquely assigned to each customer.
-   Country: Country name. Nominal. The name of the country where a customer resides.
![image](https://user-images.githubusercontent.com/58263509/197523097-7e806e43-938b-4099-9686-383a3a6d9d97.png)
