1. prints: "values added:  20"

2. prints: "final result:  20"

3. prints: "values added:  20"

4. error, result not found (because "let result" is block scope and the console.log code is outside of this block scope)

5. error, result = num1+num2 tries to modify result which is a const var. This throws an error that prevents line 9 because you cant reassign a const.

6. error, result = num1+num2 tries to modify result which is a const var. This throws an error that prevents line 13 because you cant reassign a const.
