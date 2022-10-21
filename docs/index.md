# Welcome to the Techolab C# course!

## Contacts

+374 93 573219

Samvel Arustamyan (samvel.arustamyan"shnik"gmail.com)

## Participants

*Ani Baghdasaryan

## Resources 

* [C# Programming for Absolute Beginners](https://www.goodreads.com/book/show/58230269-c-programming-for-absolute-beginners) by Radek Vystavěl
* [Illustrated C# 7](https://www.goodreads.com/book/show/36902257-illustrated-c-7) by Daniel Solis
* [Microsoft Courses](https://dotnet.microsoft.com/en-us/learn/csharp)

## Prerequisites

1. Development environment

   1. Install Visual Studio Community Edition (with .NET desktop development option): [https://visualstudio.microsoft.com/vs/community/](https://visualstudio.microsoft.com/vs/community/)
   2. Use [https://dotnetfiddle.net/](https://dotnetfiddle.net/) whenever VS is not available
   
## Lesson 0 - Introduction

### In Class

1. Console.WriteLine()
2. Arithmetic and string operations
3. ASCII characters

### Home Assignments

1. Create a Console Application project and print "Hello World" to the output.
2. Print double-backslashes, i.e. "\\\\" 
3. Create a spinner animation using the following characters: \|,/,-,\ (use `Thread.Sleep()` to slow it down)
4. Learn about Git

## Lesson 1 - Types, Variables & Conditions

### In Class

1. Basic types, strings 
2  Variables and scopes
3. Boolean operators (&&, \|\|, !)
4. Conditional Statements

### Home Assignments

**Coding**

1. Fix the "days of month" riddle

**Git**

1. Install git: [https://git-scm.com/download](https://git-scm.com/download)
2. Create a GitHub account: [https://github.com/join](https://github.com/join)
3. Add an ssh key to the GitHub account: [https://docs.github.com/en/authentication/connecting-to-github-with-ssh](https://docs.github.com/en/authentication/connecting-to-github-with-ssh).
4. Create a repository for class projects and push to github: [https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github). NOTE: use the SSH instead of HTTPS for remote URL.

## Lesson 2 - Loops

### In Class

1. `while` loops
  * Enhance the command line spinner
  * Print all the numbers from 1 to 20
2. `for` loops
  * Calculate the sum of all the numbers from 1 to 100
  
### Home Assignments

**Coding**

1. Calculate the sum of all the numbers from 1 to 100 that are a multiple of 3
2. For the given number of iterations `n` calculate approximation of pi using the Leibniz formula: [https://en.wikipedia.org/wiki/Leibniz_formula_for_%CF%80)](https://en.wikipedia.org/wiki/Leibniz_formula_for_%CF%80). *Side quest: watch a video on Newton's formula for pi: [https://www.youtube.com/watch?v=gMlf1ELvRzc](https://www.youtube.com/watch?v=gMlf1ELvRzc) *
3. Print `true` if the given nubmer is a prime number
4. Calculate the sum of all the prime numbers between 2 and 100 

**Git**

1. Fork the repository [https://github.com/sarustamyan/technolab-csharp](https://github.com/sarustamyan/technolab-scharp) (see [https://docs.github.com/en/get-started/quickstart/fork-a-repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo) for help)
2. Checkout the branch `master`
3. Edit `docs/index.md` to add yourself to the list of participants under the section "Participants".	
4. Create a pull request with the changes ([https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork))

## Lesson 3 - Arrays

### In Class

1. Arrays, high-level overview.
2. String representations. ASCII vs Unicode.

**Coding**

1. Find the max item of the array
2. Convert a string to lowercase

### Home Assignments

1. Print "True" if the given string is a palindrome (i.e. if it reads the same both left-to-right and right-to-left), "False" otherwise. I.e. for "car" the program should print "False", whereas for "racecar" it should print "True".
2. For a given string, find the number of words in it. I.e. for the string "There are only 10 types of people in the world: those who understand binary and those who don't." the answer should be 18. 
3. Find the second smallest item of the array. You can assume there are no duplicates.
4. For the given arrays `a1` and `a2`, find all the items that belong to both `a1` and `a2`.
