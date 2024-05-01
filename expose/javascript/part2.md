## Question 1
It prints out 2, since ``var`` is function-specific, so the variable i can be seen in the whole function.

## Question 2
It prints out 150, since ``var`` is function-specific, so the variable discountedPrice can be seen in the whole function.

## Question 3
It prints out 150 since the final price was the discounted price rounded to the nearest whole number, and since ``var`` is function-specific, so the variable finalPrice can be seen in the whole function.

## Question 4
It will return the array ``[50, 100, 150]``. It discounts the elements of the input array by the given percent (in decimal form) and output the final price.

## Question 5
It would cause an error, since ``i`` is not available to the program outside of the ``for`` loop.

## Question 6
It would cause an error, since ``discountedPrice`` is not available to the program outside of the ``for`` loop.

## Question 7
It would output 150, since ``finalPrice`` was declared outside of the ``for`` loop, so the program can access it outside of the loop.

## Question 8
It will return the array ``[50, 100, 150]``. It discounts the elements of the input array by the given percent (in decimal form) and output the final price.

## Question 9
The code causes an error; you cannot modify the value of a ``const`` variable after you defined it, so the code crashes before outputting the value of ``i``.

## Question 10
The code causes an error; you cannot modify the value of a ``const`` variable after you defined it, so the code crashes before outputting the value of ``length``.

## Question 11
The code causes an error; you cannot modify the value of a ``const`` variable after you defined it, so the code crashes before getting to the return statement.

## Question 12 
1. ```student.name```
2. ```student["Grad Year"]```
3. ```student.greeting()```
4. ```student["Favorite Teacher"].name```
5. ```student.courseLoad[0]```

## Question 13
1. 32; It converts 2 into a string, then concatenates them
2. 1; Since - is not a valid operation in strings, it converts "3" to an integer and subtracts them.
3. 3; ```null``` becomes 0, so 3 + 0 = 3
4. "3null"; ``null`` becomes a string "null", then concatenated with "3".
5. 4; ``true`` becomes 1, so 3 + 1 = 4.
6. 0; ``false`` becomes 0 and ``null`` is 0, so 0 + 0 = 0
7. NaN, since ``undefined`` results in an error, the calculation becomes an undefined calculation, which prints out NaN.
8. NaN, since ``undefined`` results in an error, the calculation becomes an undefined calculation, which prints out NaN.

## Question 14
1. true; The strings are converted to numbers, which turns into 2 > 1.
2. false; We are comparing strings, and alphabetically, "2..." is greater than "1..."
3. true; The string is converted into the number 2, which is the left hand side.
4. false; They are of different types.
5. false; Any value other than 1 is set to false by implicit conversion, so ``true == false`` is false.
6. true; The boolean conversion of 2 is true, and the two sides are booleans equal to ``true``.

## Question 15
The difference between equality ``==`` and strict equality ``===`` is that strict equality also checks if the variables are of the same type.

## Question 17
It will return the array ``[2,4,6]``. Since newArr doesn't change its value, we can add to the array. The function is updating every array element from the input and multiplying it by 2 then adding it to the new array.

## Question 19
1432; The program prints out the numbers 134 instantly, then after a second prints out 2.