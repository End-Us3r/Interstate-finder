# Interstate-finder

This Java code defines a class named "LabProgram" which has a main method. It first creates a Scanner object to read input from the console. It then reads an integer value from the console and assigns it to the variable "highwayNumber".

The code then checks whether the highway number is a valid interstate highway number and prints out the appropriate message based on the following criteria:

    If the highway number is even and not a multiple of 100, it is a primary highway going east/west if it is between 1 and 99 or an auxiliary highway serving the primary highway with the number (highwayNumber % 100) going east/west if it is between 100 and 999.
    If the highway number is odd and not a multiple of 100, it is a primary highway going north/south if it is between 1 and 99 or an auxiliary highway serving the primary highway with the number (highwayNumber % 100) going north/south if it is between 100 and 999.
    If the highway number is less than or equal to 0 or greater than or equal to 1000, or it is a multiple of 100, it is not a valid interstate highway number and an appropriate error message is printed.

Note that the messages printed to the console are in the format of "I-highwayNumber is ..." where the "I-" prefix is always present, and the "..." part of the message varies based on the conditions met.
