#### QUESTION 1
Write an SQL query to insert a new student named John Doe into the "Students" table.
```sql
Insert into Students Values
(5,'John','Doe','2002-07-20','johndoe@gmail.com','9876543210')
```
![alt text](<Screenshot 2024-06-15 214133.png>)

#### QUESTION 2
Write an SQL query to enroll an existing student in a course, specifying the enrollment date.
```sql
Insert into Enrollments Values
(5,5,3,'2024-03-20')
```
![alt text](image.png)

#### QUESTION 3
Update the email address of a teacher in the "Teachers" table.
```sql
Update Teachers 
Set Email='sarahbrown123@gmail.com' 
Where Teacher_ID=3;
```
![alt text](image-1.png)

#### QUESTION 4
Write an SQL query to delete a specific enrollment record, choosing based on the student and course.
```sql
Delete From Enrollments
Where Student_ID=1 AND Course_ID=2;
```
![alt text](image-2.png)