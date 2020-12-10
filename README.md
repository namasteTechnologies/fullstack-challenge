# Full-Stack Code Challenge

Our product team has a new mission for you: develop the new generation of Product Card for [CannMart.com](http://cannmart.com)! With this new improved card, we want to increase our conversion rate from the PLP to the PDP of more than 2%.

PLP means "Product Listing Page". This is the layout you see when visiting a collection, or when you search for a keyword.
PDP means "Product Detail Page". This is the page where you see product details.
A Product Card is the box that appears on the PLP. Often, customers click on it to access the PDP.

This challenge has 4 steps. We are interested by your code quality, and your technical knowledge. Each step maps a domain where our current full-stack software engineers operate.

You should be free of choosing the frameworks and libraries of your choice. The only restrictions are to use React in the frontend, Node.js in the backend, and SQLite for the database. You can add your solutions to the tasks in a public repository of your choice (Github for instance), or send us a .zip file.

## Step 1: SQL

- In the Github repository, you can find a file named "data_mini.jsonl". It contains information about a small set of products offered by CannMart:
    - Basic product information like the title, description, price, or images. The price is in CAD.
    - Reviews information: the score a customer gave to the product and a comment.
- First, we would like you to load this JSON into a SQLite database. Could you provide us with the manual SQL queries or the script that allows you to do so?
- Could you also give us the SQLite file so we can test your project end-to-end?

## Step 2: API Backend

- Once your data is in SQLite, create a simple API, using Node.js, to retrieve product information.

## Step 3: Frontend

- Our designer provided you with the new design for our improved card. See the file "design_product_card.png" in the Github repository.
- Create 1+ React components to display a Product Card based on the design.
- Create 1+ React components to display the Listing Page. We will review your implementation of the Product Card, so keep it simple here!

## Step 4: External API integration

Our newly-designed product cards are live on [CannMart.com](http://cannmart.com) since 2 weeks. Thanks to an A/B test, we see an augmentation of the conversion rate PLP to PDP of +3%. Well done, that's better than expected! 

Our product team comes back to you. They want to repeat this success for our French website. There is only 1 problem! The prices should be in € (euro) so French customers can pay in their currency.

All the product prices need to be converted in EUR, from CAD.

To optimise on the rendering time, you decide with your engineering squad to implement this change on the backend. 

- Can you extend the code written in Step 2 to use [https://exchangeratesapi.io/](https://exchangeratesapi.io/), to get the EUR price from the CAD one?
- You can create a dropdown in the frontend, so the customer picks their preferred currency.
