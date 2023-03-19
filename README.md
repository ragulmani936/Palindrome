# Palindrome

## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### STEP 1: 
Declare string variables to store the input string and its reversed form respectively.
### STEP 2:
Use the Console.Write() to get string, and read the input string using the Console.ReadLine() method.
### STEP 3:
Use a for loop to iterate over the characters in the string from the last index to the first index, and append each character to the invers variable.
### STEP 4:
Compare the reversed string invers with the original string. If they are equal, print the string is a palindrome. Otherwise, print the string is not a palindrome.
### STEP 5:
Use the Console.WriteLine() method to print the result to the console.

## Program:
~~~
Name : Ragul M
Ref no : 212221230080
~~~
```python
using System;
namespace palindrome
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, invers = "";
            Console.Write(" Enter string ");
            s = Console.Write(" Enter string ");
            s = s.ToLower();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                invers += s[i];
            }
            if (invers == s)
            {
                Console.WriteLine("{0} is Palindrome", s);
            }
            else
            {
                Console.WriteLine("{0} is not Palindrome", s);
            }
        }
    }
}
```
## Output:
![output](img%201.png)
![output](img%202.png)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
