# Experiment-7

1. Aim: To study and implement C++ Arrays and Strings

THEORY :
• Arrays store multiple elements of the same data type in contiguous memory locations, enabling efficient data management.
• Using loops (commonly a for loop), the program iterates through the array indices to access and print each element.
• Printing array elements helps in verifying the correctness of data storage and manipulation within the program.
• This basic operation forms the foundation for more complex data handling and algorithm implementation in C++.

ALGORITHM:
1. Start the program.
2. Declare an integer array arr of size 5.
3. Display the message "Enter 5 integers:" to prompt the user for input.
4. Use a loop that runs from 0 to 4 (total 5 times):
5. Read an integer from the user.
6. Store the input value in the array at the current index.
7. Display the message "Array elements are:" to indicate the output.
8. Use another loop that runs from 0 to 4:
9. Access each array element at the current index.
10. Print the element followed by a space.
11. Print a newline to end the output line.
12. End the program.

2. AIM: TO FIND A NUMBER IN A GIVEN ARRAY

THEORY
- The program searches for a specific number within an array using linear search.
- Each element is checked sequentially until the number is found or the array ends.
- Detecting whether a number exists in an array helps in data validation and decision-making tasks.
- This concept forms the basis of more advanced search algorithms.

ALGORITHM
1. Start the program.
2. Declare an integer array arr[5], an integer num for the number to search, and an integer flag found = 0.
3. Prompt the user to enter 5 integers and store them in arr.
4. Prompt the user to enter the number to search.
5. Use a loop (i = 0 to 4):
   - If arr[i] == num, set found = 1 and break.
6. If found == 1, print "Number is present."
   - Else print "Number is not present."
7. End the program.


3. AIM: SUM AND AVERAGE OF ARRAY ELEMENTS

THEORY
- The program computes the sum of array elements and the average by dividing sum by total elements.
- Demonstrates array traversal and arithmetic calculation in C++.
- Helps understand the overall distribution and central tendency of data.

ALGORITHM
1. Start the program.
2. Declare an integer array arr[5], integer sum = 0, float avg.
3. Input 5 integers in arr using a loop.
4. Add each element to the sum.
5. Calculate avg = sum / 5.0.
6. Print sum and average.
7. End the program.


4. AIM: TO FIND MTHE INIMUM AND MAXIMUM NUMBER

THEORY
- The program identifies the largest (max) and smallest (min) numbers in an array.
- Keeps track of current max and min values as it iterates through the array.
- Helps understand the range and distribution of data.

ALGORITHM
1. Start the program.
2. Input the number of elements n.
3. Declare an integer array arr[n].
4. Input n elements into arr.
5. Initialize max = arr[0], min = arr[0].
6. Loop i = 1 to n-1:
   - If arr[i] > max, update max.
   - If arr[i] < min, update min.
7. Print max and min.
8. End the program.


5. AIM: DIFFERENT WAYS TO DECLARE AND INITIALISE A STRING

THEORY
- Demonstrates four methods of declaring strings in C++.
- Includes C-style character arrays and C++ std::string.
- Shows flexibility and difference between character arrays vs string objects.

ALGORITHM
1. Start the program.
2. Declare character array a[4] = "abc".
3. Declare character array b[] = {'a','b','c','\0'}.
4. Declare character array c[4] = {'a','b','c','\0'}.
5. Declare std::string d = "abc".
6. Print heading "Different ways to declare a string in C++".
7. Print the contents of a, b, c, and d.
8. End the program.


6. AIM: CONCATENATION OF STRINGS

THEORY
- Concatenation combines two or more strings into one continuous string.
- In C++, done using + or .append() for std::string.
- For C-style strings, strcat() or loops are used.

ALGORITHM
1. Start the program.
2. Declare str1, str2 as strings.
3. Input two strings from the user.
4. Concatenate them into result = str1 + str2.
5. Display concatenated string.
6. End the program.


7. AIM: PRINTING STRING IN REVERSE

THEORY
- Program prints a given string in reverse order.
- Helps understand string indexing and manipulation.
- Useful in applications like palindrome checking.

ALGORITHM
1. Start the program.
2. Declare string str.
3. Input the string.
4. Loop from str.length()-1 down to 0: print each character.
5. End the program.


08. AIM: PALINDROME CHECKING

THEORY
- A palindrome reads the same forwards and backwards.
- Involves comparing characters from opposite ends moving towards the center.
- Useful in pattern recognition, validation, and algorithmic problem solving.

ALGORITHM
1. Start the program.
2. Input string str.
3. Calculate n = str.length().
4. Initialize flag = 0.
5. Loop i = 0 to n/2:
   - If str[i] != str[n-i-1], set flag = 1 and break.
6. If flag == 0 → print "Palindrome".
   Else → print "Not Palindrome".
7. End the program.


CONCLUSION
This experiment covered essential operations with arrays and strings in C++, including:
- Declaration, initialization, traversal, searching, summation, finding extremes, concatenation, reversing, and palindrome checking.
- Enhanced understanding of manipulating data structures and applying control statements effectively.
- Mastering these concepts is vital for building strong programming skills and tackling more advanced problems in C++ development.


