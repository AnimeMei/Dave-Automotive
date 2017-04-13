# CECS-323-Term-Project
### Views
Use the Create View statement to create the following views:
1. Customer_v – for each customer, indicate his or her name as well as the customer type (prospect, steady or premier) as well as the number of years that customer has been with us.
2. Customer_addresses_v – for each customer, indicate whether they are an individual or a corporate account, and display all of the addresses that we are managing for that customer.
3. Mechanic_mentor_v – reports all of the mentor/mentee relationships at Dave’s, sorted by the name of the mentor, then the name of the mentee.
4. Premier_profits_v – On a year by year basis, show the premier customer’s outlay versus what they would have been charged for the services which they received had they merely been steady customers.
5. Prospective_resurrection_v – List all of the prospective customers who have had three or more contacts, and for whom the most recent contact was more than a year ago. They might be ripe for another attempt.

### Queries
Write the SQL to perform the following queries. If it seems to you that it would make the queries easier to write and understand, please feel free to write additional views to facilitate your query writing. Each query is a single SQL statement. Never return just the ID of a given thing in your queries, always do any necessary joins so that you can display a proper name. I will dock points for using literals in your queries. For instance, use the now() function to get the current date when asked to find visits within the past year, do not use a literal and put in the due date of the assignment for the current date. Be sure that the sample data that you insert into your tables is adequate to return some data from each of these queries:
1. List the customers. For each customer, indicate which category he or she fall into, and his or her contact information. If you have more than one independent categorization of customers, please indicate which category the customer falls into for all of the categorizations.
2. For each service visit, list the total cost to the customer for that visit.
3. List the top three customers in terms of their net spending for the past two years, and the total that they have spent in that period.
4. Find all of the mechanics who have three or more skills.
5. Find all of the mechanics who have three or more skills in common.
a. Please give the name of each of the two mechanics sharing 3 or more skills.
b. Please make sure that any given pair of mechanics only shows up once.
6. For each maintenance package, list the total cost of the maintenance package, as well as a list of all of the maintenance items within that package.
7. Find all of those mechanics who have one or more maintenance items that they lacked one or more of the necessary skills.
8. List the customers, sorted by the number of loyalty points that they have, from largest to smallest.
9. List the premier customers and the difference between what they have paid in the past year, versus the services that they actually used during that same time. List from the customers with the largest difference to the smallest.
10. Report on the steady customers based on the net profit that we have made from them over the past year, and the dollar amount of that profit, in order from the greatest to the least.
11. List the three premier customers who have paid Dave’s Automotive the greatest amount in the past year, and the sum of their payments over that period. Be sure to take into account any discounts that they have earned by referring prospective customers.
12. List the five model, make, and year that have caused the most visits on average to Dave’s automotive per vehicle in the past three years, along with the average number of visits per vehicle.
13. Find the mechanic who is mentoring the most other mechanics. List the skills that the mechanic is passing along to the other mechanics.
14. Find the three skills that have the fewest mechanics who have those skills.
15. List the employees who are both service technicians as well as mechanics.
16. Three additional queries that demonstrate the five additional business rules. Feel free to create additional views to support these queries if you so desire.

### Deliverables
The first part, design, will consist of:
* Your five additional business rules
* Class diagram.
* English description of all classes and associations.
* If you did any denormalization in your design, please include a separate paragraph(s)
stating what you did and why. If you did not do any denormalization, state that and why.

The second part, implementation, will include:
* A revised design, based on feedback from the first part. This includes class diagrams
and English descriptions of classes and associations.
* English description of all attributes.
* The relation scheme, based on the design.
* DDL used to create all the tables and the DML used to insert the data
* Queries to produce the reports, as described above along with sample output for each of
these queries.
  
