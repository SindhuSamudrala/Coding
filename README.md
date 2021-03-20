# Coding
Leetcode questions
There are N rooms with keys in them we need to return if we can visit all the rooms or not.

https://leetcode.com/explore/challenge/card/march-leetcoding-challenge-2021/590/week-3-march-15th-march-21st/3677/

I used the concept of DFS and tried to solve the problem.

Firstly a list is created initializing False values with the length of the rooms and then whenever a key is found we change the visited value from False to True. Using Stack we keep the record of all the keys and will be returning the value True if all the visited values are True else False.
![image](https://user-images.githubusercontent.com/63176075/111860941-e7b35c80-8907-11eb-9761-5893de26a076.png)

