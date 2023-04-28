# **Part 2**
Answers:

1. At line 12, `i = 3`, so the console will log **`3`**. This is because `i` is declared as a `var` on line 6. This means that `i` has function scope and can be accessed anywhere even though it is declared in the for-loop declaration.
   
2. At line 13, `discountedPrice = 150`, so the console will log **`150`**. This is because `discountedPrice` is declared as a `var` on line 7. This means that `discountedPrice` has function scope and can be accessed anywhere in the function even though it is declared inside a for-loop.
   
3. At line 14, `finalPrice = 150`, so the console will log **`150`**. This is because `finalPrice` is declared as a `var` on line 4. This means that `discountedPrice` has function scope and can be accessed anywhere in the function.
   
4. The function will return **`[50, 100, 150]`**. To briefly describe the function: first,  `discounted` and `finalPrice` are initialized; then, we iterate through each element `prices` and apply the `discount` to it, and store all new prices in `discounted`. Finally, the function will return `discounted`, which equals `[50, 100, 150]`.
   
5. At line 12, the code **causes an error**. This is because `i` is being declared in the for-loop declaration. Because it is declared using `let`, the variable will have block scope. Therefore, any attempt to access `i` outside the for loop will be denied.
   
6. At line 13, the code **causes an error**. This is because `discountedPrice` is being declared inside the for-loop. Because it is declared using `let`, the variable has block scope and is only accessible inside the for loop. Therefore, when the program tries to access it outside the for loop, it throws an error because it can't access it.
   
7. At line 14, `finalPrice = 150`, so the console will log **`150`**. This is because `finalPrice` is declared as a `var` on line 4. This means that `discountedPrice` has function scope and can be accessed anywhere in the function.
   
8. The function will return **`[50, 100, 150]`**. To briefly describe the function: first,  `discounted` and `finalPrice` are initialized; then, we iterate through each element `prices` and apply the `discount` to it, and store all new prices in `discounted`. Finally, the function will return `discounted`, which equals `[50, 100, 150]`. Even though `discounted` is declared with `let`, this will not cause an error because it is becaue accessed within the block that it is declared in.
   
9.  At line 11, the code **causes an error**. This is because `i` is being declared in the for-loop declaration. Because it is declared using `let`, the variable will have block scope. Therefore, any attempt to access `i` outside the for loop will be denied.
    
10. At line 12, `length = 3`, so the console will log `3`. This is because `length` is declared as a `const` and set to `prices.length`. The program is able to access it at line 12 because it is still withing the same block scope.
    
11. The function will return **`[50, 100, 150]`**. To briefly describe the function: first,  `discounted` and `finalPrice` are initialized; then, we iterate through each element `prices` and apply the `discount` to it, and store all new prices in `discounted`. Finally, the function will return `discounted`, which equals `[50, 100, 150]`. Even though `discounted` is declared with `const`, this will not cause an error because it is becaue accessed within the block that it is declared in. `const` declaration still allows the variable to be manipulated, just not reassigned.
    
12. A: `student.name`
    
    B: `student["Grad Year"]` 
    
    C: `student.greeting`
    
    D: `student["Favorite Teacher"].name`
    
    E: `student.courseLoad[0]`

13. 
    A: `11` - `'3'` is recognized as a character, so the `2` is appended and it becomes a string.

    B: `1` - Even though `'3'` is a character, `2` is substracted, so math arithmetic is performed instead.

    C: `3` - `null` becomes `0` when used in math arithmetic.

    D: `3null` - `null` becomes a string when appended to a character.

    E: `4` - when used in math arithmetic, `true` becomes a `1`.

    F: `0` - `false` and `null` both become `0` when used in math arithmetic. 

    G: `3undefined` - `undefined` becomes a string when appended to a character.

    H: 'NaN' - This is a "conversion fail" because no matter what `undefined` becomes, it will not match with `'3'`. We cannot subtract from a character, so `'3'` becomes `3`. However, undefined becomes NaN in numeric conversion.

14.  
    A: `true` - When comparing a character to an int, the character (`'2'`) becomes an int. 2 > 1 is true.

    B: `false` - When comparing two strings, a dictionary comparison is performed. 2 goes after 12.

    C: `true` - When comparing an int to a character, the character (`'2'`) becomes an int. 2 == 2 is true.

    D: `false` - `===` compares the two sides without converting. Because `2` and `'2'` are of different types, this comparison returns false.

    E: `false` - When comparing a boolean to an int, the boolean (`true`) becomes 1. 1 == 2 is false.

    F: `true` - `Boolean(2)` is true because `2` is not an empty value. Therefore, true === true is true.

15. `==` is a comparison operator that checks for equality after type conversion if needed. `===` is also a comparison operator, but it does not do type conversion. Therefore, if the values on either side of `===` are different, it will automatically return false without converting.

16. *See part2-question16.js*

17. This function will return `[2,4,6]`. As you can see, there are two functions: `modifyArray` and `doSomething`. When `modifyArray` is called, two parameters are passed in: `[1,2,3]` and `doSomething`. The function will iterate through every element in the given array and push the output (of calling `doSomething` on that element) to the returned array.

18. *See part2-question18.js*

19. This function will output the numbers in the following order: `1`, `4`, `3`, `2`.
