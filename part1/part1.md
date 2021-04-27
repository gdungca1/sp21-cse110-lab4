## Part 1a
1) console logs "values added: 20"
2) console logs "values added: 20"
3) console logs "values added: 20"
4) error because result is not defined in the scope
5) error because of reassignment to const
6) same error as question 1.5

## Part 1b
1) console logs 3, which is the value of i by the end of the for loop
2) console logs 150, which is prices[3] * (1 - 0.5) or 50% off 300
3) console logs 150, which is prices[3] * (1 - 0.5) or 50% off 300
4) function returns [50, 100, 150], which is the cost of the original values multiplied by the discount of 0.5 (so 50% is taken off)
5) this is an error because i only exists in the for loop
6) this is an error because discountedPrice only exists in the for loop
7) console logs 150, which is as in 1.2 and 1.3 prices[3] * (1 - 0.5) or 50% off 300
8) function still returns [50, 100, 150], which is the cost of the original values with the discount taken off
9) error again, i only exists within the for loop
10) console logs 3 because that is the length of prices
11) it should return [50, 100, 150], again the cost of the original items with the discounts off
12)
   A) student.name
   B) student['Grad Year']
   C) student.greeting()
   D) student['Favorite Teacher'].name
   E) student.courseLoad[0]
13)
   A) 32
   B) 1
   C) 3
   D) 3null
   E) 4
   F) 0
   G) 3undefined
   H) NaN
14)
   A) true
   B) false
   C) true
   D) false
   E) false
   F) true
15) == is equality test (allows type conversion) whereas === is a strict equality test (doesn't convert)
16) see part1b-question16.js
17) If we were to log the return, modifyArray receives [2, 4, 6] as its array. This is because we push each ith value of the argument "array" into newArr after performing the callback function ("doSomething") on it. doSomething on '1' returns '2', which newArr pushes, and this is done for each element of "array".
18) see part1b-question18.js
19) it outputs (on new lines) 1, 4, 3, then 2. 1 is written first, timeouts are set for logs of 2 and 3, 4 is logged, with a delay of 0 3 is logged, then 2 after 1 second.
