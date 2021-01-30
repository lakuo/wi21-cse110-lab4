1. The value of i (prices.length - 1) will be printed because it's within the scope of the function.
2. The value of discountedPrice (of the final item in prices[]) will be printed because it's within the scope of the function.
3. The finalPrice (the final discountedPrice rounded) will be printed because it's within the scope of the function.
4. The function returns an int[] containing {50,100,150}. The discount was individually applied to the prices, rounded, and stored in the discounted[].
5. Compiler error because the variable 'i' is out of the scope of the for-loop.
6. Compiler error because the variable 'discountedPrice' is out of th scope of the for-loop.
7. The finalPrice (the final discountedPrice rounded) is printed because it's within scope.
8. The function returns an int[] containing {50,100,150}. The discount was individually applied to the prices, rounded, and stored in the discounted[].
9.  Compiler error because the variable 'i' is called out of the for-loop scope.
10. Error, reassigning a constant variable in line 6.
11. Error, reassigning a constant variable in line 7.
12. The function will not run to return because of const reassigning errors.
13. a) student.name b) student['Grad Year'] c) student.greeting.function()
    d) student['Favorite Teacher'].name e) student.courseLoad[0]
14. a) ‘3’ + 2 = '32' (2 is concatonated with the string '3')
    b) ‘3’ - 2 = 1 (2 is subtracted by 3)
    c) 3 + null = 3 (null has value of 0)
    d) '3' + null = '3null' (null is treated as a string to concat with the string '3')
    e) true + 3 = 4 (true is converted to 1)
    f) false + null = 0 (false and null are converted to 0)
    g) "3" + undefined = '3undefined' (undfined is treated as a string to concat with string '3')
    h) "3" - undefined = NaN (undefined cannot be type converted to be subtracted by 3)
15. a) '2' > 1 = true ('2' is type converted to int)
    b) '2' < '12' = false (in letter-by-letter comparison, 2>1)
    c) 2 == '2' = true ('2' is converted to int)
    d) 2 === '2' = false (not same type)
    e) true == 2 (true is converted to 1)
    f) true === Boolean(2) = true (Boolean(!0)=true)
16. == can convert type to check for equality, === both must also be of same type
17. 'How are you?' gets printed (2 == true is false because true is converted to 1 but in the second condition, 2 is treated as a boolean and is true)
18. (in part1-question18.js)
19. [6,8,10]; 2 is added to each element of array and multiplied by 2.
20. (in part1-question20.js)
21. 1 4 3 2