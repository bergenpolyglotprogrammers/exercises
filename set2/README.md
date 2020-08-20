# Exercise Set 2

## 1 - Mad Lib

_Source and credits: Exercises for Programmers (2015) by Brian P. Hogan_

### Focus

Input, Output, Compiling, Running

### Description

Mad libs are a simple game where you create a story template with blanks for words.
Create a mad-lib program that prompts for a noun, a verb, an adverb, and an adjective and create a simple story.

### Example output

```
Enter a noun: dog
Enter a verb: walk
Enter an adjective: blue
Enter an adverb: quickly
Do you walk your blue dog quickly? That's hilarious!
```

## 2 - Blood Alcohol Calculator

_Source and credits: Exercises for Programmers (2015) by Brian P. Hogan_

### Focus

Input, Output, Math

### Description

Create a program that prompts for you weight, gender, number of drinks, the amount og alcohol by volume of the drinks consumed, and the amount of time since your last drink.

The BAC forumla:

```
BAC = (A * 5.14 / W * r) - .015 x H
```

where

- `A` is total alcohol consumed, in ounces (oz)
- `W` is body weight in pounds
- `r` is the alcohol distribution ratio, `0.73` for men and `0.66` for women
- `H` is number of hours since the last drink

Display whether or not it's legal to drive by comparing the blood alcohol content to 0.08 (USA).

### Example output

```
Your BAC is 0.08
It is not legal for you to drive
```

## 3 - Parsing a data file

_Source and credits: Exercises for Programmers (2015) by Brian P. Hogan_

### Focus

Input, Output, File, CSV, Parsing

### Description

Create a file on disk that contains the following data

```
Ling,Mai,55900
Johnson,Jim,56500
Jones,Aaron,46000
Jones,Chris,34500
Swift,Geoffrey,14200
Xiong,Fong,65000
Zarnecki,Sabrina,51500
```

Create a program that reads the file, parses each line into an Employee object, and prints the results on the screen as a table.

### Example output

```
Last      First     Salary
-----------------------------------
Ling      Mai       55900
Johnson   John      56500
Jones     Aaron     46000
Jones     Chris     34500
Swift     Geoffrey  14200
Xiong     Fong      65000
Zarnecki  Sabrina   51500
```

### Part 2 - Sorting

Modify the program to also sort the list of employees by salary

### Example output

```
Last      First     Salary
-----------------------------------
Swift     Geoffrey  14200
Jones     Chris     34500
Jones     Aaron     46000
Zarnecki  Sabrina   51500
Ling      Mai       55900
Johnson   John      56500
Xiong     Fong      65000
```
