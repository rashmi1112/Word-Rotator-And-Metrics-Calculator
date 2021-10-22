# Implement a program for word rotation and calculate the required metrics given below:
 1. Average Words Per Sentence
 2. Average Word Length
 
## Name: Rashmi A. Badadale

-----------------------------------------------------------------------
-----------------------------------------------------------------------


Following are the commands and the instructions to run ANT on your project.
#### Note: build.xml is present in wordPlay/src folder.

-----------------------------------------------------------------------
## Instruction to clean:

####Command: ant -buildfile wordPlay/src/build.xml clean

Description: It cleans up all the .class files that were generated when you
compiled your code.

-----------------------------------------------------------------------
## Instruction to compile:

####Command: ant -buildfile wordPlay/src/build.xml all

Description: Compiles your code and generates .class files inside the BUILD folder.

-----------------------------------------------------------------------
## Instruction to run:

####Command: ant -buildfile wordPlay/src/build.xml run -Dinput="input.txt" -Doutput="output.txt" -Dmetrics="metrics.txt"

Note: Arguments accept the absolute path of the files.


-----------------------------------------------------------------------
## Description:

The goal of the assignment is to process the given input file that contains sentences and also to calculate some metrics. 

An instance of the StringBuilder class has been used to store the processed input and pass it on to the output file and the standard output.

Citations: 
 1. For formatting the output. 
 
https://www.programiz.com/java-programming/examples/round-number-decimal 

