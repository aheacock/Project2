# Introduction to Lists and Loops in Python

In python, a list is a rough equivalent to an array, with significantly more functionality, and for loops also have significantly different functions as compared to C or C++. An example of this would be th
e following:

                my_list = [1,9,3,8,5,7]

                for number in my_list:
                        print number

This code will go through each element in 'my_list' and print it. Unlike C/C++, there is no 'i' variable which counts up, instead this will access each element of the list, and within the loop you can easily manipulate each element in the list. The generic code for this is:

        for variable in list_name:
                #Do something
