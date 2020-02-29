# Alexa Query Assistant
Querying database instance using voice input developed by Amazon Alexa!

## Project Description
#### Contributors:    
- Mo Shi  
- Zekun Zhang  
- Ziqi Wang  
#### Implementation:    
- A MySQL InstaCart sample DB instance that contains product-order information (see the schema in .pptx presentation)
- A web interface for users to interact with the DB instance, i.e., accepting the voice input and display the results.
- __Alexa skills that mines information from the database by transforming the voice input into dynamic SQL queries__

## Alexa Skills Introduction
#### General Query Intent:
General _SELECT_ function to query the database and return the results  
- _WHERE_ clause supported
- Single/Multiple/All attributes selection supported
- Basic aggregate functions (_SUM/COUNT/MAX/etc._) supported
- Users "speak out" the SQL queries

#### Product Info Intent:   
Given a product's ID, find its corresponding information
- Information includes: 1.department 2.location 3.product name

#### Find Product Intent:
Find the most/least popular products in the market
- Find the x most/least popular products given an integer x
- Popularity measured by the product's frequency of occurance in all orders
- Results sorted by the product's popularity

## Demonstration
See our project demo at: https://www.youtube.com/watch?v=FJ8jGS_ebKs     
Also, find more details in our .pptx presentation!
