#CSC110 Homework: Classroom Seating Chart- Nested Loops

## Overall Task
students are creating a seating chart  for a classroom. 
The classroom has rows and columns, like in cameroon we used to sit in rowws and columns. students will use nested loops to print the chart,and use conditionals inside the loop to show which seats are taken and whcch seats are empty. 
By the end, students will be able to trace nested loops, use an if/elif inside a loop to change what prints for one cell, and explain why the changes.


### Task 1: get_class_size() 
In "get_class_size ()" use python function "input" to ask the user for numerical information about the class:
1.Ask the user the number of rows.
2.Ask the user the number of columns
3.Return both numbers to main as "rows" and "cols"


### Task 2 : print_seating_chart(rows, cols)
Use returned numbers to make a nested loop that prints the full classroom.

1. create a loop for row that prints all rows from 1 to rows
2. Create another loop for columns that prints all columns
3. Use code inside inner loop to print "S" for each seat.
4. print outcomes(tables)

   Your print should look like this:
   ```
   s s s s s
   s s s s s
   s s s s s
   s s s s s
   ```

   ### Task 3:
   print seating chart with absent students

   Modify the code generated above to include absences to create a new version of the chart:
   1. For this task, your instructor tells you which student is absent. ( EXAMPLE the person in row 3, column 4 is absent).
   2. Inside the inner loop, add code to print the absent student:
      - If the student is absent print "X"
      - Else, print"S"


    Your Print shuld look like this:
   ```
    S S S S S
    S S S S S
    S S S X S
    S S S S S
   ```
   ### Task 4 :more absent seats
   Thinking of more  
