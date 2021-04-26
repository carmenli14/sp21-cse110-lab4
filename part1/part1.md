Part 1a
1. values added: 20
2. final result: 20
3. values added: 20
4. Error, we are trying to access the variable `result` outside of its block scope.
5. Error, we are trying to reassign `result` while it's supposed to be a constant.
6. Error, we are trying to reassign `result` while it's supposed to be a constant.

Part 1b
1. Line 12 prints out `3` because `i` keeps track of the element we are on in the array and at the end of the for loop, `i` is 3.
2. Line 13 prints out `150`because at the last iteration of the loop, `discountedPrice` is calculated by taking the last element of 300 and multiplying it by (1-0.5).
3. Line 14 prints out `150` because the last iteration of the loop, `finalPrice` stores the rounded value of 150, which got calculated using the last element of the array, 300.
4. This function returns `[50, 100, 150]` because it takes in an array of prices and calculates the discounted prices. In this case, the original array was `[100, 200, 300]` and the discount was 0.5 so the returning array is half of all the respective prices.
5. Error, `i` is declared with the `let` keyword so it's only accessible within the for loop.
6. Error, `discountedPrice` is declared with the `let` keyword so it's only accessible within the for loop.
7. Line 14 prints out '150' because `finalPrice` was defined within the same block scope and it gets assigned to that value at the last iteration of the loop.
8. This function returns `[50, 100, 150]` because it takes in an array of prices and calculates the discounted prices. In this case, the original array was `[100, 200, 300]` and the discount was 0.5 so the returning array is half of all the respective prices.
9. Error, `i` is declared with the `let` keyword so it's only accessible within the for loop.
10. Line 12 prints out '3' because `const length` gets assigned to the length of the `prices` array, which is 3, and we don't attempt to reassign it.
11. This function returns a `const` array with values `[50, 100, 150]` because it takes in an array of prices and calculates the discounted prices. In this case, the original array was `[100, 200, 300]` and the discount was 0.5 so the returning array is half of all the respective prices.
    
12. A) `student.name` B) `student['Grad Year']` C) `student.greeting` D) `student['Favorite Teacher'].name` E) `student.courseLoad[0]`
    
13. A) `'32'` - the integer 2 gets mapped to its string representation and the two strings get concatenated. B) `1` - string '3' gets mapped to an integer so we can subtract 2 from 3. C) `3` - the `null` gets casted as a 0. D) `3null` - the `null` is mapped into a string and gets concatenated with '3'. E) `4` - `true` maps to `1` so we add the values 1 and 3 together. F) `0` - `false` and `null` are both `0`. G) `3undefined` - `undefined` gets mapped to a string. H) `NaN` - we can't map `undefined` to an integer and we can't perform `-` on strings.
14. A) `true` - '2' gets mapped to its integer value and 2 is greater than 1. B) `false` - '2' is being compared to the first character of '12' which is '1'. C) `true` - '2' gets mapped to its integer value and 2 is equal to 2. D) `false` - 2 and '2' are different types. E) `false` - boolean `true` gets mapped to `1`. F) `true` - `Boolean(2)` is true.
15. `==` checks to see if the values are the same and allows for casting, while `===` checks the types and doesn't allow for casting. 
    
16. answer in file part1b-question16.js
    
17. `[2,4,6]` is the result. `modifyArray` gets called at line 13. Inside this function, a new array `newArr` gets created and then for each element, `doSomething` gets called and returns the double of each element which then gets added to the new array. After the loop, `newArr` gets returned.
    
18. answer in file part1b-question18.js
    
19. ``` javascript
    1
    4
    3
    2