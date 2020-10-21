This is a C program to test the data sharing ability of a thread and process.

1. Parent process has 3 variables.
2. Parent will create a child using fork, and wait untill the child does some calculations.
3. Parent will create a thread and do the same tasks as the child, we will evaluate the results, to see how child and thread differ in execution.