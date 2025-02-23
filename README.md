# CS-280-Write-a-C-program-that-reads-from-a-file-specified-in-the-command-line
Write a C++ program that reads from a file specified in the command line


Download Link : https://programming.engineering/product/write-a-c-program-that-reads-from-a-file-specified-in-the-command-line/

Write a C++ program that reads from a file specified in the command line as an argument. The program should read from the file words until the end of file. In case the file is empty, print out on a new line the message “File is empty.” and then exit. However, if no file name is provided, the program should print on a new line “NO SPECIFIED INPUT FILE NAME.”, and exit. If the file cannot be opened, print on a new line “CANNOT OPEN THE FILE “, followed by the file name, and exit. A word is defined as a sequence of one or more non-whitespace characters separated by whitespace.

The program should recognize words that represent integer numbers, fixed-point numbers and special names. An integer is defined as a word that starts by a digit, or a sign (i.e., – or +) followed by a digit, that may be followed by zero or more digits. A fixed-point number is defined as a word that starts by a digit, or an optional sign followed by a digit, and followed by zero or more digits, a decimal point (i.e., a dot) and one or more digits. For example, “0.4”, “2.5”, “-3.75” are valid fixed-point numbers, but “5.”, “.8”, “5.6.7” are not valid fixed-point numbers. A special name is defined as a word that starts by ‘$’ and followed by a letter which may be followed by zero or more letters, digits or underscores. For example, $value, $num_234_ten, and are valid names, but $9val, and $_num are not.

The program should count and display the number of recognized integers, fixed-point numbers and special names. Then the program should display the value of each word category and the number of occurrences of that word. The program should print out the results according to the format and order given by the example below, as the list of integers first, followed by the list of reals second, then the list of special names third.

Hint: You can create a simple directory for each kind of words (integers, fixed-point numbers, names) using the <map> container, where the key is a number or a name, and the value is the number of its occurrences.

For example, with an input file of the following contents:

extension from Canvas. Your implementation will be graded based on the expected correct output for each test case. Use the test cases to test your implementation.

    If you want to look at the input for one of the test cases on Vocareum, use the linux “cat” command. The cases are in the directory $LIB/public/RA_Spring2023/RA4. You can, for example, look at infile3 by saying “cat $LIB/public/ RA_ Spring2023/ infile3 “, and you can look at the expected output by saying:

“cat $LIB/public/ RA_ Spring2023/infile3.correct”.

Submission Guidelines

    Please name your file as “RAx_firstinitial_lastname.cpp”. Where, “firstinitial” and “lastname” refer to your first name initial letter and last name, respectively, and “x” refers to the recitation assignment number (e.g., 1, 2, etc). Your program Submission is to Vocareum environment. Follow the link of Recitation Assignment 2 on Canvas in the Modules or Assignments pages to connect to the current assignment on Vocareum.

    Submissions after the due date are accepted with a fixed penalty of 25% from the student’s score. No submission is accepted after Wednesday 11:59 pm, February 15, 2023.

Grading Table

            Testing Cases
            	

            Points

            Case 1: No file name is found (nofile.correct)
            	

            0.5
            	

            Case 2: File cannot be opened (cantopen.correct)
            	

            0.5
            	

            Case 3: Empty File (empty.correct)
            	

            0.5
            	

            Case 4: Blank file (blank.correct)
            	

            0.5
            	

            Case 5: Real numbers only. (reals.correct)
            	

            2.0
            	

            Case 6: Numbers only. (numbers.correct)
            	

            2.0
            	

            Case 7: Special names only. (names.correct)
            	

            2.0
            	

            Case 8: All cases. (all.correct)
            	

            2.0
            	

            Compiles Successfully
            	

            1.0
            	

            Total
            	

            11
            	
