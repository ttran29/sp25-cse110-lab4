1. 3 because using the var keyword in the for loop is function-scoped and that means that i will be accesible anywhere in the whole function.
2. 150 because using the var keyword in the for loop is function-scoped and that means that i will be accesible anywhere in the whole function. In the last iteration of the for loop discountedPrice = prices[2] * (1 - discount) = 300 * .5 = 150 which is expected.
3. 150 because using the var keyword in the for loop is function-scoped and that means that i will be accesible anywhere in the whole function. This is the same number as the discountedPrice but rounded (but it stays the same because there is nothing to round).
4. Nothing! It prints out nothing because the function is doing the calculation but it does not log the result to the console. 
5. This will lead to a ReferenceError since i is not defined since using let is only for the for loop.
6. This will lead to a ReferenceError since i is not defined since using let is only for the for loop.
7. 150 because the program pushed the finalPrice value to the finalPrice variable which is outside the for loop.
8. Nothing! It prints out nothing because the function is doing the calculation but it does not log the result to the console.
9. Leads to a TypeError because using the const keyword will prevent reassignment to that variable.
10. 3 because the length of the discountPrices has been set already so this number isn't changed which is what we are logging. 
11. Nothing! It prints out nothing because the function is doing the calculation but it does not log the result to the console.
12. 
    1.  a. student.name
    2.  b. student["Grad Year"]
    3.  c. student.greeting()
    4.  d. student["Favorite Teacher"].name
    5.  e. student.courseLoad[0]
13. 
    1.  a. '32'
    2.  b. 1
    3.  c. 3
    4.  d. 3null
    5.  e. 4
    6.  f. 0
    7.  g.  3undefined
    8.  h. NaN
14. a
    1.  a. true
    2.  b. false
    3.  c. true
    4.  d. false
    5.  e. false
    6.  f. true
15. == is loose equality which compares the value after the type conversion and === is strict equality which compares both the value and type without doing any type conversions.
16. part2-question16.js
17. The output should be [2, 4, 6] because the array is [1, 2, 3] and the doSomething function multiplies a number by 2. First in the modifyArray function, we are inputting in that array with the callback for doSomething. It starts with a const array. With a for loop, we are going through the array and we are using the callback on each index in the array, returning this new array. 
18. part2-question18.js
19. 
  1
  4
  3
  2