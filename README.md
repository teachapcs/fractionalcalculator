AP Computer Science
Wallenberg High School
Project #1
Fraction Calculator
Implement a basic calculator that handles fractions.
1.	Final Required Behavior
-	The program should read in fraction equations and print the results in a continuous loop until the user types "quit"
-	Input will be either mixed fractions, proper fractions, improper fractions or integers
-	Input will be separated by spaces – exactly one space between each fraction and operator.
-	The integer and fraction parts of a mixed fraction will be separated by an underscore.
-	Negatives are allowed – the negative sign should go immediately before the whole part of the number (with no space in between)
-	The operators will be +, -, *, and /
-	The output needs to be in standard mixed fractions, properly reduced (i.e. 1/2 instead of 2/4, 1_1/4 instead of 5/4)


2.	Sample Execution Log (user input in bold)
Welcome to the Fraction Calculator!
Enter an expression (or "quit"): 1/2 + 1/3
5/6
Enter an expression (or "quit"): 1_1/2 + 1/4
1_3/4
Enter an expression (or "quit"): 8/4 + 2
4
Enter an expression (or "quit"): -1 * -1/2
1/2
Enter an expression (or "quit"): -11/17 + -1/17
-12/17
Enter an expression (or "quit"): 1/3 * 3
1
Enter an expression (or "quit"): quit
Goodbye!
3.	Additional Comments
-	No numbers in the fraction will exceed the limits of a Java int (between -2,147,483,648 and 2,147,483,647) after they are multiplied – which means the input will be between -32,768 and 32767.
-	As you make changes think about how you are going to ensure all different scenarios still work. In other words figure out how you want to test this in advance.

4.	Checkpoints and grades: 
-	Like in the real world, you will build this project in multiple steps and each checkpoint will build upon the last checkpoint code. We will have 4 checkpoints for evaluation.

4.1.	Checkpoint 1: 10 Points
-	Accept fraction string as input and display corresponding improper fraction.
-	Example: 
Enter the fraction: 1_1/2
Improper Fraction: 3/2
Goodbye!
-	Breakdown of Points: 
o	2 Points: Comments: Header, Methods, Logic
o	1 Points: Proper formatting/Indentation
o	3 Points: Handling Whole number, fractions, Mixed Numbers 
o	2 Points: Calculating Correct improper fraction
o	1 Points: Correct input/output formatting
o	1 Points: Breaking into reusable code for future checkpoints
 

4.2.	Checkpoint 2: 20 Points
-	Parsing the fractions: displays mixed and improper fractions and operation entered. Interpret Quit command: exit on this command otherwise continue processing.
-	Example: 
Enter an expression (or "quit"): 1/4 + 1_1/2
Fraction 1: 1/4 = 1/4
Operator: +
Fraction 2: 1_1/2 = 3/2
Enter an expression (or "quit"): quit
Goodbye!
-	Breakdown of Points: 
o	4 Points: Comments, formatting, Indentation, modular code
o	3 Points: Handling Whole number, fractions, Mixed Numbers 
o	2 Points: Calculating Correct improper fraction
o	4 Points: Correct Parsing of Equation String
o	2 Points: Handling Quit
o	3 Points: Correct loop implementation
o	2 Points: Correct input/output formatting
•	
4.3.	Checkpoint 3: 20 Points
-	Do one operation (+) fully functional including improper, mixed fractions.
-	Example:
Welcome to the Fraction Calculator!
Enter an expression (or "quit"): 1_1/2 + 1/4
1_3/4
Enter an expression (or "quit"): 8/4 + 2
4
Enter an expression (or "quit"): quit
Goodbye!
-	Breakdown of Points: 
o	3 Points: Comments, formatting, Indentation, modular code
o	2 Points: Handling Whole number, fractions, Mixed Numbers 
o	3 Points: Correct loop implementation, Quit
o	2 Points: Correct Parsing of Equation String
o	2 Points: Calculating Correct improper fraction
o	3 Points: Correct Addition implementation
o	3 Points: Correct Result calculation in reduced format 
o	2 Points: Correct input/output formatting  
4.4.	Final Submission: 50 Points
-	Everything should work as described in section 2.
-	Breakdown of Points: 
o	5 Points: Comments, formatting, Indentation, modular code
o	5 Points: Handling Whole number, fractions, Mixed Numbers 
o	4 Points: Correct loop implementation, Quit
o	5 Points: Correct Parsing of Equation String
o	10 Points: All operations implementation
o	5 Points: Calculating Correct improper fraction
o	10 Points: Correct Result calculation in reduced format 
o	5 Points: Correct input/output formatting
o	6 Points: Handling corner cases (divide by 0, wrong fractions etc)

5.	Extra Credit:
-	5 points: calculators that can handle more than one operation (e.g. 1 + 1 + 1 - 1/2)
-	5 points: correctly handling the order of operations with more than two inputs (e.g. 1 - 2 * 4 returning -7 instead of -4)
-	5 points: handling bad input gracefully (e.g. 1 + + 1/2 does not cause the program to crash)
-	10 points: an infinite precision calculator.  This means your calculator can handle very large numbers and still produce the right results. You may look at Java BigInteger class. This involves a lot of extra work, so consider it carefully or do it only after you have finished the required parts.
Additional extra credit for other advanced behavior based on complexity and completeness. 
Maximum extra credit available 30 points.

