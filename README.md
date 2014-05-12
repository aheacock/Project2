# Introduction to Lists and Loops in Python


## Background Info
In python, a list is a rough equivalent to an array, with significantly more functionality, and for loops also have significantly different functions as compared to C or C++. An example of this would be the following:

                my_list = [1,9,3,8,5,7]

                for number in my_list:
                        print number

This code will go through each element in 'my_list' and print it. Unlike C/C++, there is no 'i' variable which counts up, instead this will access each element of the list, and within the loop you can easily manipulate each element in the list. The generic code for this is:

        for variable in list_name:
                #Do something

Keep in mind that a list can incorporate any data type that is built in to python, string, int, etc.

## Assignment

Your assignment is to write a script in python which will take this list of names:

        smith_family = ['Elisa','Adam','Matthew','Grace','Joshua','Ashley']

Firstly, you will add 2 names to the list. This can be done using the 'List' [functions](https://docs.python.org/2/tutorial/datastructures.html "Title") for python.

Secondly, you will remove everything but the first initial of the names. The string functions for python can be found [here](https://docs.python.org/release/2.5.2/lib/string-methods.html "Title").

Thirdly, you will append each of the names so that they include their last name; 'Smith'.

Finally, you will print out each of the names with it's index preceeding it so that it appears like this:

        1: E. Smith
        2: A. Smith

### Grading
This assignment will be graded as follows:
10% Submission
10% Creation of a list
20% Addition of 2 names to the list
20% Removal of all but Initial
20% Appending of Last name
20% Correctly formatted printing of names
