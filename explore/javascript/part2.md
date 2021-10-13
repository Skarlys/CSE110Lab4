A Little more of a Challenge..

1. prints "3" to console
i is a var type that gets incremented in a for loop until it reaches prices.length.
Thus, console.log prints the length of the prices array, in this case its 3.

2. prints "150" to console
discountedPrice is a var that applies a discount to an element in prices.
discountedPrice gets overridden every loop of the for loop, so at the end, it takes on the final
discount of the final element in prices. In this case, 300 * (1-0.5) = 150 = discountedPrice

3. prints "150" to console
finalPrice is a var that rounds the price after a discount has been applied
finalPrice gets overridden every loop of the for loop, so at the end, it takes on the final
discount of the final element in prices and rounds it.
In this case, it rounds 150, which still equals 150

4. returns the discounted array. In this case, its [50, 100, 150]
The for loop applies the discounts to each element in price, and pushes it into the discounted array.
Then it returns the discounted array.

5. error, console.log(i) is out of the scope of its declaration because they used "let i" which is
a block scope.

6. error, console.log(discountedPrice) is out of the scope of its declaration because they used
"let discountedPrice" which is a block scope.

7. returns "150" to console. finalPrice is declared outside of the for loop so its scope reaches
the console.log(finalPrice) code.

8. returns the discounted array, in this case: [50, 100, 150]. discounted is within the scope, so
the array is reachable and thus returnable.

9. error, console.log(i) is out of the scope of its declaration because they used "let i" which is
a block scope.

10. prints "3" to console
length of the prices array is 3, which is initially stored in const length. Thus it prints 3.

11. returns discounted array. In this case [50, 100, 150]. Even though discounted is const, its an
array. Thus, pushing onto the existing array isn't reassigning it so there are no errors. Functionality
is normal.


2. Data Types:
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]


3. Arithmetic
A. = 32
Concats 2 to '3' because '3' is a string and + is string concat
B. = 1
turns '3' into int and subtracts 2 because - is arithmetic operation
C. = 3
since 3 is int, treats null as 0
D. = 3null
since '3' is string, treats null as string 'null'
E. = 4
converts to int and treats true as int because + is arithmetic op (true = 1 like in C)
F. = 0
converts to int and treats false as 0 (like in C), and null as 0 since arithmetic op
G. = 3undefined
converts to string because '3' is string, and concats string 'undefined'
H. = NaN
converts '3' to string and undefined to a number. Tries to subtract, but results in not a number
because undefined cannot be converted to a number


4. Comparison
A. true
converted to int and checked, 2>1
B. false
string checked lexicographically, '2' < '1' returns false
C. true
checks equality with type conversion so 2 == 2
D. false
checks equality without type conversion, '2' and 2 have diff types
E. false
since true = 1, after type conversion, 1 != 2
F. true
Boolean(2) converts 2 to boolean true, so they're equal


5. == checks for equality with type conversions
=== checks for equality without type conversions (so diff types will return false)


7. functions
returns [2, 4, 6]
we pass an array, and a function to modifyArray.
modifyArray applies a function to each element in the given array, and stores it into a new
array called newArr. It then returns newArr.
Since we pass in doSomething, which multiplies an element by 2, and modifyArray applies this,
we get a resulting array where every element is multiplied by 2.


9. setInterval, setTimeout, clearTimeout
output is:
1
4
3
2
