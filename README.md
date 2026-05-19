# Data-cleaning-python-AI
I have done this project just to learn purely about data cleaning be it duplicates, empty rows, null values, etc.
---
## Table content
- [About project](#about-project)
- [Tools used](#tools-used)
- [What I did?](#what-i-did)
- [What I learnt?](#what-i-learnt)
- [What I am confident about?](#what-i-am-confident-about)
- [About me](#about-me)

---

## About project

This project is about a cafe where data regarding items, their per unit cost, quantity of sale, total revenue generated, payment method and in-store/takeaway is given. This data basically tells about customers who purchsed a certain item at a certain quantity and paid price accordingly using certain payment method and chose either in-store or takeaway as per their preference. 

I used this data for purpose of learning data cleaning mainly and increasing my grip on python for data cleaning. This data had various missing values(null, nan, error, etc) in every column. Also, some products containes same per unit price. Hence, it made data cleaning difficult but also helped me gaing confidence and experience.

---

## Tools used

### -> Python
- Numpy
- Pandas
- Matplotlib
- Seaborn

### -> ChatGPT
- For writing long codes for complex work only.
- For getting accurate values for null values.
- For creating graphs.

---

## What I did?

- I uploaded the csv by myself and added [basic codes](basic_code.png) to get information of my data.
- I used [codes] in order to lowercase my column names and remove unnecessary empty rows.
- I then wrote my prompt in ChatGPT to solve null values of columns like quantity, per unit price and total price.

   - Quantiy = total price/ per unit price
   - Per unit price = total price/quantiy
   - Total price = quantity*per unit price
 
- I again used AI to write me a code to get the information [all items and their per unit price](per_unit_price-items/unit_price-items.png) which was grouped by per unit price.
- Those per unit price with only single items, was used to fill null values in items column for only those rows which had that perticular price.
- For remaining, i left them untouched as i did not have much data a or a column relating with them to fill null values.
- Then, for business recommendation from the data, i made some graphs using AI.

### Graphs
- [Location, items and total revenue:](#graph/location.png)
  
This graph shows which item generate more revenue and during in-store or takeaway. Which basically means that, which product generates more revenue and customers buying that product usually prefers either in-store or takeaway. This will help us in future to create or improve things for our customers. Like for takeaway, secured go-to packs that avoids spiling of prduct and also easy to carry. If in-store, we cane improver store atmosphere and maintaing basic qualities. 

- [Payment, items and total revenue:](graph/payment.png)
  
This graph shows which item generates more revenue and what payment method do customers usually prefer for payin for it. This will help us know which payment method is mostly used and so we can improve that payment method and help customer pay without any inconvenience..

- [Items and total revenue:](graph/price&unit.png) 

This graph shows which items generate more revenue which will help in estimating popular item among the consumers. It will help during advertisements to adverstise the business too alson with item. Also, will help business to produce more of this product during demand.

- [Items & months performance](graph/items-performance.png)
  
This graph shows perfomane of months and items. Months are arranged in descending order using total revenue generated each month. Items are also shown in descening order in each month. The winning product was salad and losing product was cookie. And, winning month was June and losing month is February.
---

## What I learnt?

- I learnt about cleaning the messy data and try to create some relations among columns like quantity, price per unit and total price to fill null values.
- I can write [basic codes](basic_code.png) to understand the data.
- I learnt how to use per unit price to get missing items.
- I also learnt that columns like quantity, price per unit and total price helps in analysis.
- Rows with such missing values are less useful.

      
---
## What I am confident about?

- I can write basic codes.
- I can analyse the data using python and AI.
- I can think about business questions like
    - Which items were good perfomers?
    - Which payment method produced more revenue?
    - What customers usually prefer- in store/takeaway? 
    - Which items uses mostly which payment method or location?
- I can write as much as informative prompts for accurate codes to get accurate results, without revealing whole data.

---

## About me

I am Aditi Shah and I am the author of this project. I am an aspiring data analyst learning python, excel, sql and power bi, also with AI using it as an assistant to generate complex code and discussing my hypotheses.



