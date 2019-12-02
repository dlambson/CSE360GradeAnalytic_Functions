# CSE360GradeAnalytic_Functions
Functions for CSE360 Grade Analytic team project

The function code is in the src folder. 

Global Variables: 
inputTextField is the variable that will contain the string that the user creates when inputting data. I have it made as a string until it
get converted to an input via the textfield box. 

importGrades is the float array that has all the data from the file, in float form. 

LowBound is the lower bound, initialized to 0.

highBound is the higher bound, initialized to 100 by default. 

I also made 2 files, grades.txt and grades2.txt for testing. 

I made a main so the program can be tested, so disregard anything in there. 

CreateNewSet, AppendFromFile, and AppendFromKeyboard are the functions provided in this code. The code may look long and redundant but
whatever it took to make the file reading and error checking work. 

Note I had to throw in FileNotFoundExceptions for the first 2 functions and a NumberFormatException to shut the compiler up when reading in
the files and input. 

So if you need to access the data set, importGrades is what you'll need.  

