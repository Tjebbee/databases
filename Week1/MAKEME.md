> This homework assumes you have installed the software [MySQL](https://dev.mysql.com/downloads/mysql/) to your computer. If not please do that first!

# Homework week 1

This week you'll be writing a Node.js file that makes a connection to a MySQL database instance. These are the requirements that the file must fulfill:

1. Use the `mysql` package (https://www.npmjs.com/package/mysql)
2. Make a connection to MySQL, using the login credentials
3. Write JavaScript code that incorporates SQL commands:
    - Create a database called 'world'
    - Create a table called 'country'
    - Create a table called 'city'
4. Write queries (that's a technical term meaning 'requests for information from a database') that retrieve the following data that answer the following questions:
    1. What are the names of countries with population greater than 8 million
    2. What are the names of countries that have “land” in their names ?
    3. What are the names of the cities with population in between 500,000 and 1 million ?
    4. What's the name of all the countries on the continent ‘Europe’ ?
    5. List all the countries in the descending order of their surface areas.

BONUS:

5. If you have time left over and want more practice, you can write queries that answer the following questions:
    6. What are the names of all the cities in the Netherlands?
    7. What is the population of Rotterdam ?
    8. What's the top 10 countries by Surface Area ?
    9. What's the top 10 most populated cities?
    10. What is the population of the world ?

Tip: Before writing any query, first get a working version of the [example](https://www.npmjs.com/package/mysql#introduction) going. This will help you understand the basic structure of making a database connection and query.

Tip: If you want to learn how SQL itself works check out the following online tutorial: [SQL Teaching](https://www.sqlteaching.com/)
