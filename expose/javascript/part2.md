1. ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^

3
when `i` incremented to 3, the for loops break. Since i is declared by `var`,  `i` lives outside the for loop.

2. What will happen at line 13 and why? If the code causes an error, explain why. ^^^
   
   150
    when `i` incremented to 3, the for loops break. Since `discountedPrice` is declared by `var`,  `discountedPrice` lives outside the for loop. In the last execution of the loop, `discountedPrice` is calculated to be 300*(1-0.5)=150

3. What will happen at line 13 and why? If the code causes an error, explain why. ^^^
   
   150
    when `i` incremented to 3, the for loops break. Since `finalPrice` is declared by `var` outside the for loop,  `finalPrice` lives outside the for loop. In the last execution of the loop, `finalPrice` is calculated to be 150 *100/100=150

4. What will this function return? Give a brief explanation why. If the code causes an error, explain why. ^^^
   
   `[50,100,150]`
   In each iteration, the program calculated the discounted price for the `ith` element in `prices` and added the calculated price to the `discount` array. 

5.  What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).
   
   error: Uncaught ReferenceError: i is not defined
    `i` is declared by `let`, and it lives within the for loop. Outside the forloop, `i` becomes undefined.
6. What will happen at line 13 and why? If the code causes an error, explain why. 
   
   error: Uncaught ReferenceError: discountedPrice is not defined
    `discountedPrice` is declared by `let`, and it lives within the for loop. Outside the forloop, `discountedPrice` becomes undefined.
7. What will happen at line 14 and why? If the code causes an error, explain why.
   
   150
   Although `finalPrice` is defined by `let`, it's declared outside the forloop. The scope of `finalPrice` is the whole function. Thus, in the last execution of the loop, `finalPrice` is calculated to be 150 *100/100=150.

8.  What will this function return? Give a brief explanation. If the code causes an error, explain why. 
   
    `[50,100,150]`
   Although `discounted` is defined by `let`, it's declared outside the forloop. The scope of `discounted` is the whole function. In each iteration, the program calculated the discounted price for the `ith` element in `prices` and added the calculated price to the `discount` array. 

9. What will happen at line 11 and why? If the code causes an error, explain why.
     
     error: Uncaught ReferenceError: i is not defined
    `i` is declared by `let`, and it lives within the for loop. Outside the forloop, `i` becomes undefined.

10. What will happen at line 12 and why? If the code causes an error, explain why.
    
    3
    `length` is defined to be the length of the prices array, which is 3.

11. What will this function return? Give a brief explanation. If the code causes an error, explain why.
   
     `[50,100,150]`
   Although `discounted` is defined by `const`, the restriction is that we can't point discounted to a new array. Modifying the content of an array is ok.
   In each iteration, the program calculated the discounted price for the `ith` element in `prices` and added the calculated price to the `discount` array. 

12. 
    - Accessing the value of the name property in the student object
    student.name
    - Accessing the value of the Grad Year property in the student object
    student['Grad Year']
    - Calling the function for the greeting property in the student object
    student.greeting();
    - Accessing the name property of the object in the Favorite Teacher property in student
    student['Favorite Teacher'].name
    - Access the first index in the array of the courseLoad property of the student object 
    student.courseLoad[0]

13. Arithmetic
‘3’ + 2 : '32'
‘3’ - 2: 1
3 + null: 3
‘3’ + null: '3null'
true + 3: 4
false + null:0
'3' + undefined: '3undefined'
'3' - undefined: NaN
14. Comparison
‘2’ > 1: true
‘2’ < ‘12’: false
2 == ‘2’ : true
2 === ‘2’: false
true == 2 : fase
true === Boolean(2) : true
15. Explain the difference between the == and === operators.
    
    `==`is a comparison operator, which transforms the operands having the same type before comparison.

    `===` is a strict equality comparison operator in JavaScript, which returns false for the values which are not of a similar type. This operator performs type casting for equality. 
    (source: https://www.guru99.com/difference-equality-strict-operator-javascript.html)

16. 
    [2,4,6]
    In the `modifyArray` func, for each elements in array,
    it performs the operation defined in doSomething, and push the return value to newArr. Thus, the program simply takes each element from array, multiply it by 2 and put the new value into newArr.

17. 
1
4
2
3
