# Practice

## 1. For Each and If Statement
Use For Each, Assign and If Statements to find the minimum and maximum number in an array of Int32 elements and print it.

## 2. Adding and Concatenating GenericValue Variables
Create four variables of the GenericValue type in your sequence:
- A with value "123"
- B with value "456"
- C with value 123
- D with value 456
Print to the console various operations with them and see what is the result:
- A + B
- C + D
- A + C
- C + A

## 3. Separate a collection of error codes using Switch

Considering a collection of error codes stored in an Array of Strings, separate them based on their type of error code ("Ax", "Bx" or "Cx") and store them in 3 different arrays.  

**Note:** The initial Array should contain the following values: 
"Ax001","Ax002","Ax003","Ax004","Ax005","Bx001","Bx002","Bx003","Cx001","Cx002","Cx003","Cx004"

## 4. Create a simple interest calculator using a separate workflow and arguments
Create a simple interest calculator. In your `Main` workflow, ask the user to enter the amount of the initial deposit and the period (multiple choice, e.g. 1 year, 3 years, 5 years). Store the input in two variables. Afterwards, create a third variable that will store the value of the final earning.
Create a new workflow and use it to calculate a simple interest using the user input and take into consideration the value of the rate/year. Afterwards, display on screen the cumulated interest at the end of the period and the final deposit balance.
**Note:** The formula to calculate the interest can be 'Principal amount x Rate per year x Period chosen / 100'. Use a `Switch` activity to calculate the interest for all the period options (e.g: 1 year, 3 years, 5 years) and assign the result to an argument.  
