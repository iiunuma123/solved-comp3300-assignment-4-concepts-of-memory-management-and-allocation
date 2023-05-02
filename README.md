Download Link: https://assignmentchef.com/product/solved-comp3300-assignment-4-concepts-of-memory-management-and-allocation
<br>
The aim of this assignment is to help students understand the main concepts of memory management and allocation. Students will obtain hands on experience in working with C routines for fast memory allocation.

<strong>Tasks:  </strong>

<ol>

 <li>Assume that a system has a 32-bit virtual address with a 4-KB page size. Write a C program that is passed a virtual address (in decimal) on the command line and have it output the page number and offset for the given address. As an example, your program would run as follows:</li>

</ol>




./a.out 19986




and the program would output:




The address 19986 contains:

Page number = 4

Offset = 3602




Writing this program will require using the appropriate data type to store 32 bits. We encourage you to use unsigned data types as well. All calculations should be performed as fast as possible (i.e., nearly in real time). For this purpose, the use of left/right shift and/or mask operators in C (or equivalent) is required.




Run your program with 5 different virtual addresses and show the results in your report.




Change your program to generate <em>n</em> random virtual addresses between 0 and 2<sup>32</sup>-1 and compute the page number and offset for each address – do not output anything on the console. Run your program with <em>n</em> = 1,000,000 random addresses and compute the total CPU time. In your report, show how you run it and comment on your results