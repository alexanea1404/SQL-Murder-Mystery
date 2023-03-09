# My Solution to SQL Murdery Mystery

## Credits:
The SQL Murder Mystery was created by Joon Park and Cathy He. You can find more details here http://mystery.knightlab.com

## SQL Concepts Practised:
- SELECT ... FROM ...
- WHERE clause with operators: =, BETWEEN ... AND ..., LIKE
- ORDER BY
- JOINs
- SUBQUERIES

## Case
> A crime has taken place and the detective need your help. The detective have you tje crime scene report, but you somehow lost it. You vaguely remember that the crime was a ​murder​ that occurred sometime on **​Jan.15, 2018**​ and that it took place in **​SQL City**​. Start by retrieving the corresponding crime scene report from the police department’s database.

## Finding the witnesses
> First let's find the report of the murder from ​Jan.15, 2018 in SQL City
```SQL
SELECT * FROM crime_scene_report
WHERE date = 20180115 AND city = 'SQL City' AND type = "murder"
```
> Security footage shows that there were 2 witnesses. The first witness lives at the last house on "Northwestern Dr". The second witness, named Annabel, lives somewhere on "Franklin Ave".