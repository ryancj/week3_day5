#Week 3 Day 5

###Associations
- One to Many
- One to One
- Many to Many

![alt text](http://fms-itskills.ncl.ac.uk/db/ER.png)

###Joins
- Inner join
- Inner section
[alt text][chart]
[chart]: http://www.w3schools.com/sql/img_innerjoin.gif
```
SELECT * FROM students
INNER JOIN projects ON projects.student_id = students.id
ORDER BY student_id;
```

- Left join
[alt text][chart2]
[chart2]: http://www.w3schools.com/sql/img_leftjoin.gif
```
SELECT * FROM students
LEFT JOIN projects ON projects.student_id = students.id
ORDER BY students.id
LIMIT 100;
```
