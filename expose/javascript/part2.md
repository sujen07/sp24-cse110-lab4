Question 1: It will print out 3. The for loop exits after i gets to the length of prices which is 3.
Question 2: It will print out 150. the discounted price is updated every iteration in the loop and is 150 on the last iteration.
Question 3: It will print out 150. it is the last final price iteration.

Question 4: it returns a list of [50,100,50]. These are the final prices upsated to the list.
Question 5: it errors because the let is block scoped in the for loop.
Question 6: this also errors out because the discounted price is declared with let which is scope blocked
Question 7: This prints 150 because the let declaratin for final price is outside the for loop so it is not scope blocked.
Question 8: This returns the list [50,100,150] because it is also declared outside the for loop.

Question 9: This errors because the i is defined with let and is scope blocked to the for loop.
Question 10: this prints 3 becuase the length is a constant of the length of prices.
Question 11: This returns [50,100, 150] because the const for the list can be appended.

Question 12:
    part a: student['name']
    part b: student['Grad Year']
    part c: student.greeting()
    part d: student['Favorite Teacher']['name']
    part e: student['courseload'][0]
    
Question 13:
    part a: '32' => The plus concatenates the 3 string with 2 which maps to a string to concatenate
    part b: 1 => the minus only does subtraction and tries to convert both to numbers
    part c: 3 => the null is converted to 0 in numeric context
    part d: '3null' => because the 3 is a string the plus concatenates the 3 and null.
    part e: 4 => the true converts to a 1.
    part f: 0 => the null and false converts to 0s and the plus adds them
    part g: '3undefined' => because the 3 is a string the plus concatenates the 3 and undefined.
    part h: NaN => 3 minus undefined cannot be defined in a numeric sense.

Question 14:
    part a: true => both are converted to numbers.
    part b: false => it uses lexicographical comparison and 2 is greater than 1
    part c: true => they are both converted to the same type
    part d: false => this checks for both type and equality
    part e: false => the true is converted to a 1 and that is not equal to 2
    part f: true => the Boolean(2) is converted to true

Question 15: The == checks for equality and does type conversion. The === checks for equality and type becuase it does not convert any of the types.

Question 17: 
The modify array function first creates a constant list called newArr. then in a loop this is upadted with the value that the callback function returns. The callback function parameter is doSomething which returns the number times 2. so the returned list is [2,4,6] which is double the numbers from the original array.

Question 19:
The output is 1,4,3,2.
