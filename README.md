# Coding
Leetcode questions
There are N rooms with keys in them we need to return if we can visit all the rooms or not.

https://leetcode.com/explore/challenge/card/march-leetcoding-challenge-2021/590/week-3-march-15th-march-21st/3677/

I used the concept of DFS and tried to solve the problem.

Firstly a list is created initializing False values with the length of the rooms and then whenever a key is found we change the visited value from False to True. Using Stack we keep the record of all the keys and will be returning the value True if all the visited values are True else False.
![image](https://user-images.githubusercontent.com/63176075/111860941-e7b35c80-8907-11eb-9761-5893de26a076.png)

Day 13:
The Employee table holds all employees. Every employee has an Id, and there is also a column for the department Id.

https://leetcode.com/problems/department-top-three-salaries/



By using the concept of the window function. Firstly the employee table is partitioned by the department and ordered based on salary in descending order and then using the dense_rank() function rank is given and then join is performed on the department table to know the department name and only 3 records are printed from each department.
![image](https://user-images.githubusercontent.com/63176075/111893182-0d02a200-89be-11eb-961d-900aa440dfad.png)

Day 14:
Finding the number of emails in each label such as 'Promotion', 'Social', 'Shopping, etc.

https://platform.stratascratch.com/coding-question?id=10068&python=
Using the case statement and finding the count of emails under each label and performing the GROUP BY to get the individual user values.


![image](https://user-images.githubusercontent.com/63176075/111948223-12ceb500-8a9c-11eb-8875-60579ea97eea.png)

Day18:
Today it's a Leetcode problem from March Month Challenge. 

Words Subsets. Two lists of words are given as input. The first list is the list of words and the Second list is a list of words or letters which can be a subset of words present in the first list.
![image](https://user-images.githubusercontent.com/63176075/112742548-67fb4280-8f44-11eb-8252-9b52d9c78d5a.png)

Day19:
SQL query to get the share of active users of Facebook in the USA.

https://platform.stratascratch.com/coding-question?id=2005&python=

Using the case and where statement finding the number of active users in the USA 
compare it with the total number of users.
I found a good article about the CASE statement. In the below query we are using a CASE statement and performing an aggregation.
https://www.quest.com/community/blogs/b/database-management/posts/sql-case-statement-what-is-it-and-what-are-the-best-ways-to-use-it

![image](https://user-images.githubusercontent.com/63176075/112795934-19ba7200-901e-11eb-988b-fb55df5b9a40.png)





