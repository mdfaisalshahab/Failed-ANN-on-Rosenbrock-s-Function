# Interesting role of log functions in ANN
## Failed-simple ANN-on-Rosenbrock-s-Function
This is a section where simple ANN algorithm with all type of activation functions were failed. While running prediction on a simple function mainly called as Rosenbrock function because of its steepness.
Rosenbrock function has steepness in such a way that for coordinate (0,0), it is around 0 and at just next adjecent coordinate (0,1), it goes around 10^4 or more.
This simply leads to genration of a dataset very hard to train.

## Modified ANN with a log function
This is a section where the same function was modified with a log fucntion allowing to show the convergence of loss functions.
The log function help in reducing these dataset to of very small variations. If log to the base 10 is used, 10^4 becomes and so on. 
It is a kind of scaling which every data scientist should know in order to reduce the variation of their outputs.
