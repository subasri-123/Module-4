Exp.No:4c
EXCEPTION HANDLING
AIM

To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.
ALGORITHM

    Begin the program.
    Read a string input_str from the user using input().
    Split the input string using commas (,) to create a list of grades.
    Use a try block to attempt converting each item in the grades list to an integer and store the result in l1.
    If the conversion is successful, print the list l1 containing the integer values.
    If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: "The grades you entered were in an invalid format." along with the original grades list.
    Terminate the program.

PROGRAM

try:
    a=int(input())
    b=int(input())
    print(a+b)
except:
    print("cannot add integer with string")

OUTPUT
image
RESULT

Therefore, the output is the example to create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.
