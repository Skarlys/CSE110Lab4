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
