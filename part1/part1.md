## Part 1a

### var declaration
1. 20
2. 20

### let declaration
3. 20
4. Error: result is not defined. This is because the let declaration only defines result in the scope of the if block. It cannot be accessed outside of the if block.

### const declaration
5. TypeError: Assignment to constant variable. This is because you cannot change a const variable.
6. TypeError: Assignment to constant variable. This is because you cannot change a const variable.

## Part 1b
1. 3 will be printed since the array has a size of 3 and the for loop runs depending on the array size. i is a var which allow its scope to be the entire function.
2. 150 will be printed because discountedPrice is a var which allows its scope to be the entire function. Also, 300 * 0.5 = 150. 
3. 150 will be printed because finalPrice is a var which allows its scope to be the entire function. The final price after the discount was 150.
4. The function will return [50, 100, 150] because the input was [100, 200, 300]. The function will return an array with the same values but multiplied by 0.5. 
5. ReferenceError: i is not defined. This is because the let declaration only defines i inside the scope of the for loop. It cannot be accessed outside of the for loop.
6. ReferenceError: discountedPrice is not defined. This is because the let declaration only defines discountedPrice inside the scope of the for loop. It cannot be accessed outside of the for loop.
7. 150 will be printed because finalPrice was declared inside the function but not inside any specific blocks such as for loops or if statements. Therefore, the scope of finalPrice is the whole function. 
8. The function will return [50, 100, 150] because the function returns an array with the same values inputted but multiplied by 0.5. discounted was declared inside the main body of the function so its scope is the entire function. 
9. ReferenceError: i is not defined. i is a let which allows its scope to only be inside the for loop. It cannot be accessed outside of the for loop.
10. 3 will be printed because length was declared inside the main body of the function so its scope includes the whole function. Also, the array size is 3.
11. This function will return [50, 100, 150] because the function returns the an array with the same values inputted but multipled by 0.5. While discounted is declared as a const, the objects inside the array can still be manipulated.

### Data Types
12. Notation:
    1.  (A) student.name
    2.  (B) student['Grad Year']
    3.  (C) student.greeting()
    4.  (D) student['Favorite Teacher'].name
    5.  (E) student.courseLoad[0]

### Basic Operators & Type Conversion
13. Arithmetic
    1.  (A) 32 because the + operation is concatenating the 2 objects and because integers map to their exact string representation.
    2.  (B) 1 because the - operation cannot contenate so it maps the '2' into an integer.
    3.  (C) 3 because the null is mapped to 0
    4.  (D) 4 because the null is mapped to 1
    5.  (E) 3null because the + operation is concatenating the 2 objects. It converts null to a string.
    6.  (F) 0 because false and null is mapped to 0
    7.  (G) 3undefined because the + operation is concatenating the 2 objects. It converts undefined to a string.
    8.  (H) NaN because you cannot subtract a number with undefined. 
14. Comparison
    1.  (A) True because it will convert '2' to an integer and 2 is greater than 1.
    2.  (B) False because the first character of '2' is greater than the first character of '12'. 
    3.  (C) True because it will convert '2' to an integer and 2 equals 2. 
    4.  (D) False because 2 and '2' are different types.
    5.  (E) False because true equals 1, not 2.
    6.  (F) True because Boolean(2) equals true and true equals true.
15. The == checks for equality and converts different types to integers. The === checks for equality but does not convert different types to integers.

### Loops
16. in part1b-question16.js

### Functions
17. [2, 4, 6] is the result. modifyArray iterates through the array that is passed in and  calls the function doSomething for each value. As a result, each value inside the array is doubled because doSomething doubles the value that is passed through and a new array will be returned with the new values.

### setInterval(), setTimeout(), clearTimeout()
18. in part1b-question18.js
19. The output is 1, 4, 3, 2. 