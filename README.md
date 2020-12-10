# Full-Stack Code Challenge

Our product team has a new mission for you: develop the new generation of PLP (Product Listing Page) Product Card for [CannMart.com](http://cannmart.com)! With this new improved card, we hope to increase our conversion rate from the PLP to the PDP of more than 2% (Product Detail Page).

This challenge goes through 4 steps, that allow us to see your code quality and how you perform in the domains where our current software engineers operate. From your side, you can get familiar with the jargons of the e-commerce world, some details from the products attributes we sell and get your hands dirty on a real project - the type of project our software engineers are working on!

You can add your solutions to the tasks in a public repository of your choice (Github for instance), or send us a .zip file.

## Step 1: SQL

- In the Github repository, you can find a file named "data_mini.jsonl". It contains information about a small set of products:
    - Basic product information like its title, description, price (in the currency CAD) or images.
    - Reviews information. The score a customer gave to the product and a comment.
- Could you load this JSON into a SQLite database and provide us with the manual SQL queries or the script that allows you to do so?
- Could you also provide us with the SQLite file so we can test your project end-to-end?

## Step 2: API Backend

- Once your data is loaded, create a simple API, using Node.js, to retrieve product information.

## Step 3: Frontend

- Our designer provided you with the new design for our improved card.
- Create 1+ React components to display a Product Card based on the design.
- Create 1+ React components to display the Listing Page. Make something simple here, we will mainly review your implementation of the Product Card.

## Step 4: External API integration

Our newly-designed product cards are live on [CannMart.com](http://cannmart.com) since 2 weeks. Thanks to an A/B test, we see an augmentation of the conversion rate PLP to PDP of +3%. Well done, that's better than expected! 

Our product team comes back to you: they would love to see the same conversion rate for the French website (NB: Namaste only operates in Canada for now). There is only 1 problem: the prices need to be displayed in € (euro), so French customers can pay in their currency.

All the original prices need to be converted in Euro, from CAD.

To optimise on the rendering time, you decide with your engineering squad to implement this change on the backend. 

- Can you extend the code written in Step 2 to use [https://exchangeratesapi.io/](https://exchangeratesapi.io/), in order to obtain the EUR price from the CAD one?
- You can create a dropdown in the frontend, so the customer picks their preferred currency.

## Recommendations

Feel free to use any framework and libraries you want. The only restriction is to use React in the frontend, Node.js in the backend and SQLite as the database.

We are judging you on the code quality and structure you will come with. We don't have any preferences, for this code challenge. We like well-written projects, simple to understand and easy to evolve.
