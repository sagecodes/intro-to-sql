# intro to SQL  

## short URL to this repo [sqlrepo.sage.codes](https://github.com/sagecodes/into-to-sql)

Learn more SQL and other skills with our free online prep courses!

- [Start learning Data Science](http://bit.ly/gprepdata)
- [Start learning Software Engineering](http://bit.ly/gsoftprep)


### FAQ: 

- WIFI: `Galvanize Guest Seattle` | Password is posted on the walls
- Bathrooms: Behind you down the hall to the left
- Kitchen outside back classroom door with Coffee & Tea!
- Snacks + water + swag in back of room


## Setting up your computer:

- You'll only need a web browser. I'll be using [chrome](https://www.google.com/chrome/), but  you can use [Safari](https://www.apple.com/safari/) or [Opera](https://www.opera.com/)(browsers that support [Web SQL](https://en.wikipedia.org/wiki/Web_SQL_Database)). 

- to speed up learning we're going to use an [online editor and database](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) for SQL from [W3Schools](https://www.w3schools.com/). 

That was easy!


## About me:

Hello I'm [Sage Elliott](http://sageelliott.com/). I'm a Technology Evangelist here at Galvanize! For about the past decade I've worked as a software and hardware engineer with Startups and Agencies in Seattle, WA and Melbourne, FL. I love making things with technology! 

Currently I'm working on implementing more machine learning models!

**Note:** I'm not a Galvanize Instructor, they're way better at teaching! 

Reach out to me if interested in:

- breaking into the tech industry 
- learning resources
- meetup recommendations 
- learning more about Galvanize
- giving me suggestions for events!
- being friends

- Website: [sageelliott.com](http://sageelliott.com/)
- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)


## About you!

Give a quick Intro!

- Whats your name?
- Whats your background?
- Why are you interested in learning about SQL?

One of the best things about these in person workshops is being able to meet new people! Talk to each other and hang out after the workshop!


## What this workshop is

A super friendly introduction to SQL No previous experience expected! 

You can't learn EVERYTHING in ~2 hours. But you can learn enough to get excited and comfortable to keep working and learning on your own! 

- This course is for absolute beginners
- Ask Questions!
- Answer Questions!
- Help others when you can
- Its ok to get stuck, just ask for help!
- Feel free to move ahead
- Be patient and nice

### Challenges:

Get the most out of this workkshop! We'll occasionally do a "CHALLENGE" where I give you an exercise to do in several minutes. It can be even more effective to partner up with someome next to you, but you can work on your own if you want. No pressure to solve the challenge. I'll share how I would solve it after the time is up. 


## Why is data important

### What is Data?
Data is information. Imagine a phonebook with hundreds of people and businesses.

### What is a Databases?

A database is computerized storage of data. Imagine an organized digital collections of the same people and businesses from the above phone book.

###### Examples

Examples of products using databases.

- Dynamic sites
	- Facebook
	- Gmail  
- Mobile apps
	- Uber
	- Snapchat 
- Data for recommendations
	- Netflix
	- Amazon products
- Item Tracking
	- Library
	- UPS

Some Professional Roles that work with databases:

- Web Developer
- Data Analysts
- Data scientist
- Database Admin
- Bussiness Analysts
- Product Managers


## What is SQL?

Pronounced `S` `Q` `L` or `Sequel`. Either way is fine!

SQL stands for Structured Query Language. This is the language and syntax we will use to interact with SQL databases.

When we return and search data from a database we call it Querying.

Common SQL Databases:

Each of these databases can be Queried using the SQL programming Language.

- MySQL
- PostgreSQL
- Microsoft SQL
- SQLite
- Oracle

*Note:* There are some slight differences to each database, but most of the SQL commands we're going to cover will be the same or very similar.
 you can read more about the difference on common SQL databases [here](https://www.w3schools.com/sql/sql_ref_mysql.asp).

Some other popular databases to keep an eye out for as you continue to learn:

- MongoDB
- Couchbase
- Redis

These are often referred to noSQL databased. Read more about noSQL [here](https://www.mongodb.com/nosql-explained)


<!--#### Where SQL used?

#### What is an ORM?

ORM stands for Object relation model
-->


## What is a relational database?

The major components in a database:

- Data(Information Stored) and Schema(How the data is organized)
- Sections. Also called tables. This how the data get structured. 


##### Tables
You can typically think of tables kind of as spreadsheets:


|   | Column ↓   |  Column ↓  |
|---|---|---|
| Row →   |   |   | 
| Row →   |   |   |
| Row →   |   |   | 

##### Table Organization

Usually separate tables contain data for a specific type of thing:

If we look at [w3schools](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) again you can see all the different tables in the database

![alt text](img/tables.png "Tables")


Orders table:

| OrderID  |  	CustomerID | 	EmployeeID  | OrderDate  |  ShipperID |
|---|---|---|---|---|
| 10248  | 90  |  5 | 1996-07-04  | 	3  |
| 10249  |  81 |  6 |  1996-07-05 |  1 |
|  10250 | 34  | 4  |  1996-07-08 |  2 |


Products Tables:

| ProductID  | ProductName  | SupplierID  | CategoryID  |  Unit | Price|
|---|---|---|---|---|---|
| 1  |  Chais |  1 |  1 |  10 boxes x 20 bags | 18  |
|  2 |  Chang |  1 |  1 | 24 - 12 oz bottles  | 19 |
|  3 | Aniseed Syrup  | 1  | 2  |  12 - 550 ml bottles | 10  |


<!--Filter data table example:

Rearrange table example:-->

Having multiple tables storing data can seem complicated at first, why not have everything in one giant table?

Each table can have relationships with each other, instead of repeating the same product how ever many times someone buys it, we can instead reference back to that product in a separate table.

Again, don't worry if this is a bit confusing! It will make more sense as we go!



### Data types

data types for table columns are defined in the schema

The most common data types are:

- Text (Names, Descriptions)
- Numeric (cost, age, weight, quantity)
- Dates (Dates and time)
- Null (No value)

Its important to have the correct data type for your data. This ensures that sorting and calculations work properly. We won't be setting up a database from scratch in this workshop, but it something to keep in mind when you do!

### CHALLENGE:
Lets do a quick though experiment on Data types!

- What data type should a Name be?
- What data type should Quantity be?
- What data type age be?
- What data type should a shipped_date be?
- What Data type should a Zip code be?
- What datat type should a Phone number be?


*Note:* Data types may change depending on which database you're using.

We could spend a whole workshop discussing databases, but we're going to focus on querying language SQL for the remainder of this workshop. 

Learn more about databases on your own [here](https://www.w3schools.com/sql/sql_create_db.asp)!

If you would like to see a workshop more focused on Databases and how create them let me know!

## lets do some SQL!

Visit [w3schools](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) and navigate to the SQL section.


### Querying

Important first step is to understand your data.

- How is it structured?
- What does it represent?

### CHALLENGE:

- Lets explore the tables that we have before we begin to query them. On the right side, you can find all the tables that you have access to. Take a look at the information that we have access to in these tables!

### Basic Querying

Lets do some different types querying to figure this out!

Lets take a look at all the categories of products we have

This is a basic query. We're telling it it Select all elements from the table Categories.

`SELECT * FROM Categories;`

Lets see how many customers we have?

we can use the `COUNT()` function built in to SQL. This will count all the records in the Customers Table.

`SELECT COUNT(*) FROM Customers;`

Lets take a look at our orders

`SELECT * FROM Orders;`

Lets sort the orders by date

*Note:* When we query this isn't actually changing the database. You're just choosing what and how to look at the data.

We can sort using the `ORDER BY` keyword in sql. 

```
SELECT * FROM Orders
ORDER BY OrderDate DESC;
```
ASC = Ascending
DESC = Descending

Neat! Lets see which customer made that top order (most recent)! We will take the value from the CustomerID column.

We can filter to specific records or ranges of data using the `WHERE` keyword.

```
SELECT * FROM customers
WHERE CustomerID = 66;
```

Cool! We can also query for matches with multiple crteria using the `AND` keyword.

```
SELECT * FROM OrderDetails
WHERE ProductID = 14 AND Quantity < 10;
```

We can also filter columns by more than one value using the `OR` keyword.

```
SELECT * FROM OrderDetails
WHERE ProductID = 14 OR ProductID < 10;
```

<!--You can also pass in a list of values to look at.

```
SELECT * FROM OrderDetails
WHERE ProductID in (14,10);

```-->

We can also combine the `AND` and `OR` keywords in a query.

```
SELECT * FROM OrderDetails
WHERE (ProductID = 14 OR ProductID = 10)
AND Quantity < 10;
```

you can keep stacking the use of `AND` and `OR`s as much as you want!


<!--We can use the `AND` keyword to search in a range of data, but there is a shorter way of doing it with the `BETWEEN` keyword.-->




### CHALLENGE:

- How would we see all the orders for the product with the ID of 2 and quantity over 10?

- How would we see all the orders for the product with the ID either 14 or 16?

- How would we see all the orders for the product with the ID either 14 or 16 and quantity 10?



### Continue Lecture

So far we have been returning all the columns of a record that match our query. What if we want to only look at a few of them? 

Instead of using `*` to select all we can put in the specific columns we want returned. We can also put them in different order!

```
SELECT Country, city, CustomerName FROM Customers;
```
Lets order by Ascending order (A-Z) of Country Name

```
SELECT Country, city, CustomerName FROM Customers
ORDER BY Country ASC;
```

Lets See just a list of countries 
Using `DISTINCT`. Which will just return one instance.

Run the query below with and without `DISTINCT` to see the difference.

```
SELECT DISTINCT Country FROM Customers
ORDER BY Country ASC;

```

Lets count how many countries our customers are in:

```
SELECT COUNT(DISTINCT Country) FROM Customers
ORDER BY Country ASC;

```


#### Group by

Instead of getting each row, sometimes we want to group them by 


How many customers do we have in each country?

```
SELECT COUNT(*), Country FROM Customers
GROUP by Country;
```

#### searching with Like

Sometimes we want to filter by records that contain values or characters that are not an exact match.

What customers have a name starting with `A`?

```
SELECT * FROM Customers
WHERE CustomerName LIKE 'A%';
```

- 'A%' Starts with an A
- '%A' Ends with an A
- '%A%' Contains an A

Read more types of way to filter [here](https://www.w3schools.com/sql/sql_like.asp).

### CHALLENGE

- Can you query all the products that names start with a T?
- What about all customers whose name begins with H?
- Can you figure out how to return a count of them?
- Using group by how can find which shippers shipped the most products?




## Continue with Lecture


### Functions

If you've used excel you'll probably be familiar with some of these functions. 


- SUM() `SELECT SUM(Quantity) FROM OrderDetails;`
- MAX() `SELECT ProductID, ProductName, MAX(Price) FROM Products;`
- MIN() `SELECT ProductID, ProductName, MIN(Price) FROM Products;`
- AVG() `SELECT AVG(Price) FROM Products;`
- COUNT() `SELECT COUNT(*) FROM Customers;`

### CHALLENGE (5 min):

- Whats the largest order based on Quantity?
- Whats the Smallest order based on Quantity?

### Continue Lecture




### Joins

We're not going to go super deep into joins in this workshop and they can be a bit tricky to understand, so don't worry if you don't quite get it yet! Read about and practice them further [here](https://www.w3schools.com/sql/sql_join.asp).

This of it as essentially joining tables together. We're then returning combined table for use to use. 

A simple Join:

```
SELECT Orders.OrderID, Customers.CustomerName, Orders.OrderDate
FROM Orders
INNER JOIN Customers ON Orders.CustomerID=Customers.CustomerID;
```

By default when you just use 'join' we are creating a inner join. Read more about different joins [here](https://www.w3schools.com/sql/sql_join.asp)
.

Find a helpful graph on joins [here](https://stackoverflow.com/questions/565620/difference-between-join-and-inner-join).

More helpful visilaizatoins and explanations can be found [here](http://www.sql-join.com/sql-join-types/).



A more commplicated join:

Don't worry if this doesn't click 100%. Joins are one of the more complicated parts of SQL!

```
SELECT Orders.OrderID, Customers.CustomerName, Orders.OrderDate,
OrderDetails.ProductID, Products.productName, Products.Price
FROM Orders
JOIN Customers ON Orders.CustomerID=Customers.CustomerID
JOIN OrderDetails ON Orders.OrderID=OrderDetails.OrderID
JOIN Products ON OrderDetails.ProductID=Products.ProductID;
```

### CHALLENGE (5 min):

Make a simple join on other tables!


#### together!

Lets do something useful with grouping & joins. Lets find out which shipper has been used the most. Like we did before using:

```

SELECT COUNT(ShipperID), ShipperID FROM [Orders]
GROUP by ShipperID;
```

But lets use a join to add in the shipper name from the Shippers table!


```
SELECT COUNT(Orders.ShipperID), Orders.ShipperID, Shippers.ShipperName
FROM [Orders]
JOIN Shippers ON Orders.ShipperID=Shippers.ShipperID
GROUP by Orders.ShipperID
ORDER BY COUNT(Orders.ShipperID) DESC;
```

### Comments

Comments are awesome. When you're writing more complex code / queries use comments to help you remember what that piece of code is doing!


```
-- SQL Comment
-- another simple join
SELECT Orders.ShipperID, Orders.ShipperID, Shippers.ShipperName
FROM Orders
JOIN Shippers ON Orders.ShipperID=Shippers.ShipperID;
```


### BONUS: Changing Data to the database

So far we've only been looking at our data in different ways, which is super useful for answering questions, but lets actually make some changes to the database!


#### Insert into

```
SELECT * FROM Customers;
```

```
INSERT INTO Customers (CustomerName, City, Country)
VALUES ('Sage', 'Seattle', 'USA');
```

```
SELECT * FROM Customers;
```

##### What's Null?
You should notice that some of the sections on our new row contain the word `null`. 
In SQL you can think of `null` means that the cell contains no value. 


### CHALLENGE (5 min):

- Insert your name into the customers database and then query all of the customers.
- Insert a new product into the products table.

### Continue Lecture



#### Update

```
SELECT * FROM Customers;
```

```
UPDATE Customers
SET ContactName='Sage', City='Seattle'
WHERE CustomerID=1;
```

```
SELECT * FROM Customers;
```

Its common to select and update more than one single row by ID. 

```
SELECT * FROM Customers
WHERE CustomerName LIKE 'A%'
```

```
UPDATE Customers
SET ContactName='I started with an A', City='A town'
WHERE CustomerName LIKE 'A%'
```

```
SELECT * FROM Customers
WHERE CustomerName LIKE 'A%'
```

#### Delete

```
SELECT * FROM Customers;
```

```
DELETE FROM Customers
WHERE CustomerName='Sage';
```

```
SELECT * FROM Customers;
```

### CHALLENGE:

Delete the record you put in with you name



## More Challenges

Knowing what we just learned lets try to answer some questions about our data!

- How many items have we shipped?
- What is the most expensive item?
- What is the most popular item?
<!--- Which customer has spent the most money?-->
- Which customer has returned the most?
<!-- Whats the most popular category? -->

You can find the answers at the bottom of this repo to help get you going!

Come up with your own questions. What are things you would like to know about the data? Figure out how to answer them.


## Keep Learning!!!

Resources:

- [Data Science Premium Prep](http://bit.ly/gprepdata) - Galvanize
- [Free Software Engineering Prep](https://www.galvanize.com/web-development/prep) - Galvanize
- [w3schools](https://www.w3schools.com/sql/)
- [sqlzoo](https://sqlzoo.net/)
- [Read about what an ORM (Object-relational mapping) is](https://stackoverflow.com/questions/1279613/what-is-an-orm-and-where-can-i-learn-more-about-it)
-[pgexercises](https://pgexercises.com/questions/basic/)

Setup an actual database on your computer!


## Upcoming Events!

Visit the [Learn to code Seattle](https://www.meetup.com/Learn-Code-Seattle/) meetup for all upcoming events.

- [Break into Data Science Discussion Panel](https://www.meetup.com/Learn-Code-Seattle/events/266474850/) - 11/18/19 6:30pm


- [Intro to Machine Learning with Python](https://www.eventbrite.com/e/intro-to-machine-learning-free-tickets-78301755659) - 11/20/19 6:30pm

- [Google AI Study Jam: Machine Learning and Image Processing](http://bit.ly/2NNv5Hz) - 11/21/19 5:00pm


- [Breaking into Software Engineering / Web Development Discussion Panel](https://www.eventbrite.com/e/break-into-software-engineering-alumni-discussion-panel-seattle-tickets-72146364719) - 11/25/19



# What is Galvanize?

> We create a technology ecosystem for learners, entrepreneurs, startups and established companies to meet the needs of the rapidly changing digital world.

![](https://github.com/sagecodes/intro-data-science/raw/master/campus.png)

- Education
- Co-Working
- Events
- Enterprise


## Galvanize Classes

#### Immersive Bootcamp

Transform your career with our immersive programs

- [Software Engineer](http://bit.ly/seawebdev) - 12/09/19 & 2/10/2020
- [Data Science](http://bit.ly/seadatascience) - 12/2/19 & 3/16/2020

Remote options:

check out [Galvanize.com](https://www.galvanize.com/)


#### Part-Time Courses

Learn while working with out evening part-time classes

[Galvanize.com](https://www.galvanize.com/)


#### Co-working Space

[work in our building!](https://www.galvanize.com/entrepreneur)


## Questions

Please feel free to reach out to me with any questions! Let me know what you're planning to do next and how I can help!


- Website: [sageelliott.com](http://sageelliott.com/)
- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)





---------
## Challenge Answers
Answers to the Questions Section:

- Q: How many items have we shipped?
	- A: 12,743
	- `SELECT SUM(Quantity) FROM OrderDetails;`

	
- Q: What is the most expensive item? 
	- A: Côte de Blaye
	- `SELECT ProductID, ProductName, MAX(Price) FROM Products;`
	
- Q: What is the most popular item?
	- A: Gorgonzola Telino

```
SELECT SUM(OrderDetails.Quantity), Products.ProductName, OrderDetails.ProductID
FROM OrderDetails
JOIN Products ON OrderDetails.productID=Products.ProductID
GROUP BY ProductName
ORDER BY SUM(OrderDetails.Quantity) DESC;
```


- Which customer has returned the most?
	- A: Ernst Handel
	
```
SELECT Customers.CustomerName, COUNT(Customers.CustomerID)
FROM Orders
JOIN Customers ON Orders.CustomerID=Customers.CustomerID
JOIN OrderDetails ON Orders.OrderID=OrderDetails.OrderID
GROUP BY Customers.CustomerID
ORDER BY COUNT(Customers.CustomerID) DESC;
```
