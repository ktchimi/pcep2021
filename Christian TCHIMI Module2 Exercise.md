## Exercises
### Write the pseudocode for these problems. 

#### Define the problem by constructing an IPO diagram showing input, output, and processing steps
Ask yourself
- What control structures (sequence, selection and repetition) are required?
- What variables are required?

Show a check of your solution with **test data** for at least **two valid test cases**
If you use the numbers provided in the example then the correct pseudocode will calculate the same result.
    

#### 1. Find the average score
A program is needed to prompt the user operator for exam scores, calculate the average score and display the result to the screen. The average score is calculated as the sum of the scores divided by the number of scores.

input = exam scores 
process= calculate the average score ( sum exam scores / number of exam scores)
output= average score


Type Markdown and LaTeX:  𝛼2

#### 2. How much water runs off a roof in a rain storm?
To calculate the runoff from any given rainfall: Take the dimensions of the footprint of the roof and convert them to inches. (So, a 50' x 20' roof is 600" x 240"). Multiply the roof dimensions by the number of inches of rainfall. As an example, 600" x 240" x 1" = 144,000 cubic inches of water for an inch of rainfall. Divide that result by 231 to get the number of gallons (because 1 gallon = 231 cubic inches). (144,000/231 = 623.38).

input= dimensions of the footprint of the roof(x,y)
process= 1) convert x and y to inches 2)i=x*y*number of inches of rainfall 3) divide i/231 
output= result in gallons.

Type Markdown and LaTeX:  𝛼2



#### 3. Process customer record
A program is required to read a customer’s name, a purchase amount and a tax code. The tax code has been validated and will be one of the following: 0 tax exempt (0%) 1 state sales tax only (3%) 2 federal and state sales tax (5%) 3 special sales tax (7%) The program must then compute the sales tax and the total amount due,and print the customer’s name, purchase amount, sales tax and total amount due.

Type Markdown and LaTeX:  𝛼2

input= customer's name , amount of the purchase (x)
process : w= x + Z=(x*0.03+x*0.05+x*0.07) 
output = customer's name, purchase amount (x) , sales tax (z) , total amount due (w)

#### 4. Calculate employee's pay 
A program is required by a company to read an employee’s number, pay rate and the number of hours worked in a week. The program is then to validate the pay rate field and the hours worked field and, if valid, compute the employee’s weekly pay and then print it and the input data.

Validation: According to the company’s rules, the maximum hours an employee can work per week is 60 hours, and the maximum hourly rate is $25.00 per hour. If the hours worked field or the hourly rate field is out of range, the input data and an appropriate message are to be printed and the employee’s weekly pay is not to be calculated.

Weekly pay calculation: Weekly pay is calculated as hours worked times pay rate. If more than 35 hours are worked, payment for the overtime hours worked is calculated at time-and-a-half.

input= employee's number , hours worked(H)
process : 1) if H<= 60 , calculate pay rate  ; 2) if H > 60, print (" weekly pay is not to be calculated")
output : pay rate = H*25 if H<35 , if H > 35 , pay rate = H*35 + ( (H-35) * 52.5)

Type Markdown and LaTeX:  𝛼2
