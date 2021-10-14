Q1: The method console.log() accesses the variable i; since i was declared with var in the for loop, it is still defined outside the for loop, and its value is now 3 after the for loop operating. Thus, line 12 will print the value of i, which is 3.

Q2: The method console.log() accesses the variable discountedPrice; since discountedPrice was declared with var in the for loop, it is still defined outside the for loop, and its value is 150 now since the last time the for loop run--when i=2--assigned 300*(1-0.5) to discountedPrice. Line 13 will print the value 150.

Q3: The method console.log() accesses the variable finalPrice; since finalPrice was declared with var at the beginning of the function, it is defined when accessed by console.log(). The variable finalPrice was assigned to 150 in the last round of the for loop with Math.round(discountedPrice*100)/100. Line 14 will print out 150.

Q4: The function will return an array [50, 100, 150], which is the variable discounted after the for loop operated. It is the variable declared at the beginning of the function, and in each round of the for loop one more price is pushed to the array. After three round in total, it will contain the three final price values, and is returned by the function.

Q5: It will cause a ReferenceError. Since i was declared with let, it is not accessable any more outside the block of the for loop; thus, line 12 trying to access an undefined variable will cause a ReferenceError.

Q6: It will cause a ReferenceError. Since discountedPrice was declared with let, it is not defined any more outside the block of the for loop; thus, line 13 trying to access an undefined variable will cause a ReferenceError.

Q7: Line 14 will print out 150, which is the value of finalPrice assigned in the last round of the for loop. The variable finalPrice was declared with let, but could be accessed within the block which here is the function. Line 14 is inside the function, thus it can access the variable finalPrice and print out its value.

Q8: The function will return an array [50, 100, 150], which is the variable discounted after the for loop operated. The variable discounted was declared with let at the beginning at the function, so it is accessable in the function. Thus, the value [50, 100, 150] will be returned correctly.

Q9: It will cause a ReferenceError. Since i was declared with let, it is not accessable any more outside the block of the for loop; thus, line 11 trying to access an undefined variable will cause a ReferenceError.

Q10: Line 12 will print out 3. Length is the const variable declared at the beginning of the function and is not reassigned in the following code. The value assignedd is the length of the array prices, which is 3. Thus line 12 will print out value of length.

Q11: The function will return an array [50, 100, 150], which is the variable discounted after the for loop operated. The variable is declared with const, but it was not reassigned. The method .push() can add values to the array without reassign the variable. The const variable discountedPrice is also not reassigned but actually redeclared in each loop.

Q12:
A. student.name
B. student["Grad Year"]
C. student.greeting()
D. student["Favorite Teacher"].name
E. student.courseLoad[0]

Q13:
A. 32, because 2 maps to string '2', and + concatenates the two strings
B. 1, because string 3 maps to integer 3 and 3-2=1
C. 3, because null maps to 0
D. 3null, because it is two strings added together
E. 4, because true maps to integer 1
F. 0, because both false and null map to 0
G. 3undefined, because + concatenates the two strings
H. NaN, because it is not a number

Q14:
A. true, because string '2' becomes a number 2
B. false, because ascii of 1 is samller than of 2
C. true, because string '2' becomes a number 2
D. false, because there's type conmerge when compared by ===
E. false, because ture becomes 1
F. true, because Boolean(2) maps true

Q15:
== is a non-strict check which make type correction and then check only the value of two variables, while === is a strict check which has no type correction and check both value and datatype.

Q16: part2-question16.js

Q17: The result will be [2, 4, 6]. By calling modifyArray, we create an empty array newArr and go over each element of the inputted array by the for loop. In round i of the for loop we apply the method doSomething to the corresponding element and push the result to newArr. There are three rounds in total, each time multiple the input by 2, thus we overall push 1*2, 2*2, and 3*2 to newArr. In conclusion, will get [2, 4, 6] returned.

Q18: part2-question18.js

Q19: 1432