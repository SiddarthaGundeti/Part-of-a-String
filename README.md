# Part-of-a-String

In this coding question, you need to write a program that reads a word and two indices (X, Y). The program should print a part of the word from the index X to the index Y. The indices will be such that Y will always be greater than or equal to X.

Input:Growing
3
6

Output: wing

Approach
To solve this problem, we will follow these steps:
Read the input word.
Read the start and end index.
Extract the part of the word from the start index to the end index.
Print the extracted part of the word.

Step-by-Step Explanation

Step 1: Read the input word

First, we need to read the word from the input. We can use the input() function to read the input.
This piece of code waits for your input and saves it in the variable word.

Step 2: Read the start and end index

Next, we need to read the start index and end index. We can use the input() function to read the input and int() to convert it into an integer.
Here, the first two lines read the start index and convert it into an integer. The next two lines do the same for the end index.

Step 3: Extract the part of the word

Now, we need to extract the part of the word from the start index to the end index. We can do this by slicing the word.
This line slices the word from the start index to the end index.

Step 4: Print the part of the word

Finally, we need to print the part of the word that we extracted. We can use the print() function to do this.
This line of code prints the sliced part of the word.
