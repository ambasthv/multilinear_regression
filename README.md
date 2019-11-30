# multilinear_regression without Libraries. 
This is from scratch defining own function which will make you understand the calculation behind each step. 
Also  you will understand how Linear Regression Libraries works in background.

# multilinear_regression without Libraries. This is from scratch defining own function which will make you understand the calculation behind each step. Also you will understand how Linear Regression Libraries works in background
# Module Structure
- nonlinear_regression.py
- linear_algebra.py
- gauss_newton.py
- main.py 
•	nonlinear_regression.py : Module contain a class NonLinearRegression which has method for each type of nonlinear_regression. Currently we support following kinds of non linear model.
1.	Polynomial Model
o	Equation: Y = B0+B1*X+B2*X^2+B3*X^3 + -- + --
o	Any order of polynomial regression can be performed.
2.	Sinusoidal Model
o	Equation: Y = B0 * Sin(B1*X+B2)+B3
o	Order for this model is fixed to 4.
3.	Exponential Model
o	Equation: Y = B0 * (1-exp^B1x)
o	Order for this model is fixed to 2
•	linear_algebra.py : This module has all Matrix related operations such as finding inverse, tranpose, multiplication etc operations of matrix.
o	Used internally by nonlinear_regression.py
•	gauss_newton.py : This has the implementation for least square gauss newton method.
o	Used for implementing sinusoidal and exponential regression.
•	main.py : This module shows example of how to use the nonlinear_regression.py to perform the listed regression. main.py can be ignored when project is integrated with other modules.


#More to come on this page....
