# Write Your First C# Code

## Overview

This module covers the fundamentals of writing C# code, including console output, user input, and string manipulation. I completed exercises that display personalized greetings and interact with users.

## Objectives

- Display output to the console using Console.WriteLine() and Console.Write()
- Accept user input using Console.ReadLine() and store it in variables
- Manipulate strings using concatenation, string interpolation, and string methods
- Build programs that interact with users and display personalized messages

## What I Learned

I learned how to write C# programs that interact with users through the console. I practiced using the online C# IDE to write and run code without local installation. I understand the difference between Console.Write() and Console.WriteLine(), how to collect user input, and how to format strings using interpolation.

## Important Concepts

### Console Output

Console.WriteLine() prints text and adds a line break at the end. Console.Write() prints text without adding a line break, keeping the cursor on the same line.

### User Input

Console.ReadLine() pauses the program and waits for user input. It always returns a string value, which can be stored in a variable.

### String Interpolation

String interpolation uses the $"..." syntax to combine text and variables. For example: $"Hello, {name}!" inserts the value of the name variable into the string.

### String Methods

C# provides built-in methods to modify strings:
- .ToUpper() converts text to uppercase
- .ToLower() converts text to lowercase
- .Replace() replaces specific characters or substrings

### Escape Characters

Escape characters like \n (newline) and \t (tab) control formatting within strings.

## Code

### Personalized Greeting Exercise

File: personalized-greeting.cs

```csharp
// Display a welcome message
Console.WriteLine("Welcome to this program!");

// Ask for the user's name
Console.Write("What is your name?: ");
string name = Console.ReadLine();

// Display a personalized greeting
Console.Write($"Hello, {name}! It's nice to meet you.");
```

### User Interaction Challenge

File: user-interaction-challenge.cs

```csharp
// Ask for the user's name
Console.Write("What's your name?: ");
string name = Console.ReadLine();

// Ask for the user's age
Console.Write("How old are you?: ");
string age = Console.ReadLine();

// Display a personalized message that includes both pieces of information
Console.WriteLine($"Hello, {name}! You are {age} years old.");
```

## Challenges

No significant challenges encountered. The exercises were straightforward and the online C# IDE worked well for writing and testing code.

## How I Solved Them

I followed the guiding comments provided in the exercises to structure the code. I tested each program in the online IDE to verify the output matched expectations.

## Key Takeaways

- Console.WriteLine() adds a line break, Console.Write() does not
- Console.ReadLine() always returns a string
- String interpolation with $"..." is the cleanest way to combine text and variables
- Comments help organize code but are ignored during execution
- All C# statements must end with a semicolon
- String literals must use double quotes

## Related Learning

- Microsoft Learn: Write Your First C# Code module
- Online C# IDE: https://microsoftlearning.github.io/c-sharp-minor

## Module Assessment

Score: 100%

### Question 1: What is the primary job of the compiler?

Correct answer: The compiler primarily converts your code into an executable format that the computer can understand.

### Question 2: Which of the following statements is true about C#?

Correct answer: You use double quotation marks to create a literal string.

### Question 3: What is wrong with this line of code? Console.WriteLine("What is wrong with me?")

Correct answer: It's missing a semi-colon at the end.

## Microsoft Learn Trophy

Achievement earned: Write Your First Code Using C#

Share link: https://learn.microsoft.com/api/achievements/share/en-us/ShintaroASuzuki-4657/H294R4D8?sharingId=B3D7CC70C129FFC1

## freeCodeCamp Assignment

Question: What is the difference between Console.Write and Console.WriteLine?

Answer: Console.WriteLine appends a new line after the output.

Status: Completed correctly
