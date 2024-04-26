Program takes in 3 runtime arguments in the run command

java -jar IrisClassifier.jar args[0] args[1] args[2]

Order of runtime arguments :
args[0] = Name of training data file
args[1] = Name of test data file
args[2] = Name of parameter file

Parameter File values:
[0] : learning Rate = 0.001
[1] : Batch Size (Number of inputs within a single batch) = 15
[2] : Maximum Number of epochs before convergence = 15 000

Program results and output will be written to a file named "output.txt",
Program will also print some basic information to the console.