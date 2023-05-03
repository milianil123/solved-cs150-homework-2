Download Link: https://assignmentchef.com/product/solved-cs150-homework-2
<br>
Write a program that asks the user to enter the size of a triangle to write to atext file (an integer from 1 to 50), then print the triangle into a file byprinting a series of lines consisting of asterisks. Print “Triangle saved tofile” to the screen, but do NOT print the triangle itself to the screen, only tothe file. Name the output file triangle.txt

__Input Validation:__ If the user enters an integer less than 1 or more than 50tell them it is out of range and have them re-enter it (do not print thetriangle for the invalid input, only for the final value in the range of 1-50inclusive: 1 and 50 are both ok).

The first line will have one asterisk, the next two, and so on, with each linehaving one more asterisk than the previous line, up to the number entered by theuser. On the next line print one less asterisk and continue by decreasing thenumber of asterisks by 1 for each successive line until only one asterisk isprinted. Hint: Use nested for loops; the outside loop controls the number oflines to print, and the inside loop controls the number of asterisks to print ona line.