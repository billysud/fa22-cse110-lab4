# Lab 4 Part 2
1. The code returns the value 3. This is the total amount of values in the given array
2. The code returns the value 150. This is because in the last iteration of the loop we have 300 as our prices[i] and 300 * (1-0.5) = 150.
3. The code returns the value 150. This is because in the last iteration of the loop we have 150 as our discounted price and ceil((150 * 100)) / 100 = 150.
4. The function will return the given array of prices at the discount given. So in this example it would half the prices to [50, 100, 150]. But since it just returns the array and never gets printed in a call after line 19 nothing will be printed.
5. We will get an error here since i was declared with let and it's scope is only within the for loop. Thus trying to access it outside will give us an error.
6. Again here discountedPrice was declared with let inside the for loop so we will have an error trying to print it outside the scope of the loop.
7. Refer to answer for 3.
8. Refer to answer for 4.
9. Refer to answer for 5.
10. Refer to answer for 1.
11. Refer to answer for 4. 
12. A. student.name;
    B. student['Grad Year'];
    C. student.greeting();
    D. student['Favorite Teacher'].name;
    E. student.courseLoad[0];
13. A. 32
    B. 1
    C. 3
    D. '3null'
    E. 4
    F. 0
    G. 3undefined
    F. NaN
14. A. True
    B. False
    C. True
    D. False
    E. False
    F. True
15. It seems like == just checks if contents are the same regardless of datatypes vs === will evaluate it then compare.
    
    
