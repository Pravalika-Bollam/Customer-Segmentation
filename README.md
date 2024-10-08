#   Customer Segmentation SQL 



# * RPA Customer Segmentation*


##  Goals
   The marketing department of Reputable Product Agency (RPA) is looking to segment the company users by a number of different criteria. In this context, a segment is a subset of users that meet different conditions. Segments are used to send marketing campaigns to users who meet specific criteria or to measure the performance of specific marketing campaigns. I tried to retrieve data under following circumstances with sql query.
   
   - The marketing department wants to send a Born in the ‘80s email to the appropriate users.
   - We are interested in the cohort of users that signed up prior to May 2017.
   - There was an A/B test performed on users that used cute animal clipart to encourage users to sign up. We’d like to see how the group that was shown ‘bears’ is performing.
   - A total of 4 advertising campaigns were run over this period. There were two sets of ad copy (set 1 and set 2) and both were run on two search engine sites (AAA and BBB). The resulting campaign values are:

     - AAA-1
     - AAA-2
     - BBB-1
     - BBB-2
     
     Lets find all the emails of all users who received a campaign on website BBB.
   - Find all the emails of all users who received ad copy 2 in their campaign.
   - Find the emails for all users who received both a campaign and a test. These users will have non-empty entries in the campaign and test columns. 
   
<a href="https://github.com/Pravalika-Bollam/Customer-Segmentation/blob/main/RPA-Customer.sql">
  <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" width="32" height="32" alt="SQL Icon" />
  View SQL Script for Customer Segmentation
</a>





   
<br><br><br>   



 
   
   # * marketing click through rate analytics*


   ##  Goals
   CoolTShirts sells shirts of all kinds, as long as they are T-shaped and cool. Recently, CTS started a few marketing campaigns to increase website visits and purchases. Using touch attribution, they’d like to map their customers’ journey: from initial visit to purchase. They can use that information to optimize their marketing campaigns.I tried to answer following questions with sql query.
   
   - How many campaigns and sources does CoolTShirts use? Which source is used for each campaign?
   - What pages are on the CoolTShirts website?
   - How many first touches is each campaign responsible for?
   - How many last touches is each campaign responsible for?
   - How many visitors make a purchase?
   - How many last touches on the purchase page is each campaign responsible for?
   - CoolTShirts can re-invest in 5 campaigns. Given your findings in the project, which should they pick and why? 
   
   
<a href="https://github.com/Pravalika-Bollam/Customer-Segmentation/blob/main/Marketing%20Click%20Through%20Rate%20Analytics.sql">
  <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" width="32" height="32" alt="SQL Icon" />
  View SQL Script for Marketing Click-Through Rate Analytics
</a>



<br><br><br>

# * World Populations *


##  Goals
   Here I worked on a dataset of world population by country data from recent years. Tried to write queries to retrieve interesting data and answer a set of specific questions.
   
   - How many entries in the countries table are from Africa?
   - What was the total population of the continent of Oceania in 2005?
   - What is the average population of countries in South America in 2003?
   - What country had the smallest population in 2007?
   - What is the average population of Poland during the time period covered by this dataset?
   - How many countries have the word “The” in their name?
   - What was the total population of each continent in 2010? 
   
   
  <a href="https://github.com/Pravalika-Bollam/Customer-Segmentation/blob/main/Population_queries.sql">
  <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" width="32" height="32" alt="SQL Icon" />
  View SQL Script for Population Queries
</a>




<br><br><br>

# * Trends in Startups*


##  Goals
   The task was to write an article on the rising trends in the startup world. To get started with the research, I started with a project.sqlite file that contains a table called startups. It is a portfolio of some of the biggest names in the industry. Data collected from [TechCrunch](https://techcrunch.com/).
   
   - Calculating total number of companies in the table.
   - We want to know the total value of all companies in this table.
   - What is the highest amount raised by a startup at 'Seed' Stage?
   - In what year was the oldest company on the list founded?
   - Let's find out the valuations among different sectors:
      - Average valuation, in each category.
   - What are the most competitive markets?
      - What are the most competitive markets?
   - Let's see if there's a difference in startups sizes among different locations:
      - What is the average size of a startup in each location, with average sizes above 500? 

     <br>    
<a href="https://github.com/Pravalika-Bollam/Customer-Segmentation/blob/main/Startups.sql">
  <img align="left" alt="SQL" width="32px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" />
  View SQL Script for Startups
</a>


   
<br><br><br>   



# * RPA Fraud Detection*


##  Goals
   Reputable Product Agency (RPA) has started receiving complaints from their credit card processor about fraudulent transactions.
   I tried to answer following assumptions with sql query.
   
   - The finance department noted that some of the fraudulent transactions were recorded as coming from Smokey Bear’s zip code (20252).
   - Finance has also noticed a number of pseudonyms associated with fraudulent transactions.
     The fraudsters thought it would be funny to use ‘Art Vandelay’ for their full name or add a ‘der’ for their middle name.
   - There are some irregularities in the IP addresses where transactions are originating from.
     For example, any IP address beginning with ‘10.’ is reserved for internal use.
   - Users are making fraudulent transactions using a temporary email address service. These services provide a short-lived email that can be verified and then self-destructs.
   - The finance department is looking for a specific transaction. They know that the transaction occurred from an ip address starting with ‘120.’ and their full name starts with ‘John’. 

   <br>

<a href="https://github.com/Pravalika-Bollam/Customer-Segmentation/blob/main/RPA_FRAUD_DETECTION.sql">
  <img align="left" alt="SQL" width="32px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" />
  View SQL Script for RPA Fraud Detection
</a>



<br><br><br>


   
# * Davie's Burgers Subway Ad*


## 
 Goals
   'Davie’s Burgers' the restaurant business has been booming and it is now looking to place a catchy advertisement in the local subway station. Lets help them dig into their orders table to see if there is anything interesting in there for a funny tagline!
   
   - How recent is this data?
   - The special_instructions column stores the data where Davie’s Burgers customers leave a note for the kitchen or the delivery. Lets see the result to 20 rows.
   - Let’s search for special instructions that have the word ‘sauce’. Are there any funny or interesting ones?
   - Let’s search for special instructions that have the word ‘door’. Any funny or interesting ones?
   - Let’s search for special instructions that have the word ‘box’. Any funny or interesting ones?
   - Some of these are marketing gold! But what are their order numbers? 
   
   
   
<a href="https://github.com/Pravalika-Bollam/Customer-Segmentation/blob/main/Davie's%20Burgers%20Subway%20Ad.sql">
  <img align="left" alt="SQL" width="32px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/sql/sql.png" />
  View SQL Script for Davie's Burgers Subway Ad
</a>

