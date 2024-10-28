java c
CS/ECE/ISyE 524
Introduction to Optimization
Fall 2024
Homework 3: Duality and Integer Programming
Due date: Friday October 25, 2022
All solutions should be uploaded to Canvas.
1.  [5 points] Stigler’s supplement.  Consider Stigler’s diet problem from Homework 2.  To help further lower the cost of your diet, a friend offers to sell you calcium supplements. Each calcium pill contains 500 mg of calcium.
a) What is the most you would be willing to pay per pill? Hint: use duality!
b)  Suppose  you  can  buy  calcium  pills  at  a  cost  $0.01  each.   How  do  you  need  to  modify  your optimization model to account for the availability of this new “food”?
c) Implement and solve the new version of the problem.  With the available calcium pills, what is your new optimal diet?  How much money does it save compared to the original optimal diet that didn’t have access to the calcium supplement?
2.  [10 points] Dual interpretation.  Suppose t ∈ [0, 2π] is a parameter.  Consider the following LP:

a)  Plot the optimal objective of this LP as a function of t and explain what you see.Hint:  you can do this by looping over values of t, and solving a separate LP for each different value of t. To interpret what you’re seeing, you may want to separately consider the cases where cos(t) and sin(t) are positive or negative (four cases).
b) Write out the dual LP. Interpret and solve the dual LP graphically, considering different values for t. Does your solution agree with the solution found in part a)?
3.  [10  points] Voting.  Governor Blue of the state of Berry is attempting to get the state legislature to gerrymander Berry’s congressional districts.  The state consists of ten cities, and the numbers of registered Republicans and Democrats (in thousands) in each city are shown in the table below.

Berry has five congressional representatives.  To form. the five congressional districts, cities must be grouped together according to the following restrictions:
•  Districts cannot subdivide cities; all voters in a city must be in the same district.
•  Each district must contain between 150,000 and 250,000 voters (there are no independent voters, i.e., the number of voters correspond to the numbers in the table).Governor Blue is a Democrat.  Assume 100% voter turnout and that each voter always votes according to their registered party. Formulate and solve an optimization problem to help Governor Blue maximize th代 写CS/ECE/ISyE 524 Introduction to Optimization Fall 2024 Homework 3: Duality and Integer ProgrammingC/C++
代做程序编程语言e number of congressional districts that have a Democratic majority.
a) Write the mathematical formulation for the problem.  Make sure to clearly define the decision variables and problem parameters, and write the mathematical equations and explanations for the objective function and constraints.
b) Implement the problem in a Julia notebook and solve it. Make sure to run all cells so we can see the output, and ensure that the output clearly answers the following question: Which cities belong to which district?  Which of the districts have a Democratic majority?  How many Democratic districts did you get?
c)  Do you think the assignment of cities to districts is fair?  Please consider the input data and your solution when explaining why/why not.  (Note: There is not only one answer to this question.)4.  [10  points] ABC Investments.  ABC Inc.  is considering several investment options.  Each option has a minimum and maximum investment allowed (only if the option is chosen).  These restrictions, along with the expected return are summarized in the following table (figures are in millions of dollars):
Because of the high-risk nature of Option 5, company policy requires that the total amount invested in Option 5 be no more that the combined amount invested in Options 2, 4 and 6.  In addition, if an investment is made in Option 3, it is required that at least a minimum investment be made in Option 6.  ABC has $80 million to invest and obviously wants to maximize its total expected return on investment. Which options should ABC invest in, and how much should be invested?
a) Write the mathematical formulation for the problem.  Make sure to clearly define the decision variables and problem parameters, and write the mathematical equations and explanations for the objective function and constraints.
b) Implement the problem in a Julia notebook and solve it.  Make sure to run all cells so we can see the output, and ensure that the output answers the following question: How much should be invested in each option?
5.  [Final  project]  Please upload your initial idea for a final project using the template provided on Canvas!  The deadline for submitting the initial pitch is Sunday,  October 27.  Make sure to come to class on Tuesday, October 29, prepared to present your idea to your group.  Note: Your group members will be asked to provide feedback on your pitch after the class.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
