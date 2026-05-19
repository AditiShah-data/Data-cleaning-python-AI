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

- I uploaded the csv by myself and added [basic codes] to get information of my data.
- I used [codes] in order to lowercase my column names and remove unnecessary empty rows.
- I then wrote my prompt in ChatGPT to solve null values of columns like quantity, per unit price and total price.

   - Quantiy = total price/ per unit price
   - Per unit price = total price/quantiy
   - Total price = quantity*per unit price
 
- I again used AI to write me a code to get the information [all items and their per unit price](per_unit_price-items/unit_price-items.png) which was grouped by per unit price.
- Those per unit price with only single items, was used to fill null values in items column for only those rows which had that perticular price.
- For remaining, i left them untouched as i did not have much data a or a column relating with them to fill null values.
- Then, for business recommendation from the data, i made some graphs using AI.

---

## What I learnt?

- I learnt about cleaning the messy data and try to create some relations among columns like quantity, price per unit and total price to fill null values.
- I can write [basic codes] to understand the data.
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



