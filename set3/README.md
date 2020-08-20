# Exercise Set 3

## 1 - Simple Math

_Source and credits: Exercises for Programmers (2015) by Brian P. Hogan_

### Focus

Input, Output, Conversion, Compiling, Running

### Description

Write a program that prompts for two numbers. Print the sum, difference, product, and quotient of thos numbers.

### Example output

```
First number: 10
Second number: 5
10 + 5 = 15
10 - 5 = 5
10 * 5 = 50
10 / 5 = 2
```

## 2 - Temperature Converter

_Source and credits: Exercises for Programmers (2015) by Brian P. Hogan_

### Focus

Input, Output, Math

### Description

Write a program that converts temperatures from Fahrenheit to Celsius or Celsius to Fahrenheit.

The formulas are:

```
C = (F - 32) * 5/9
```

```
F = (C * 9/5) + 32
```

### Example output

```
Press C to convert from Fahrenheit to Celsius.
Press F to convert from Celsius to Fahrenheit.
Your choice: C

Enter Fahrenheit: 100
Temperature in Celsius: 37.78
```

## 3 - Word Frequency Finder

_Source and credits: Exercises for Programmers (2015) by Brian P. Hogan_

### Focus

Input, Output, File, State

### Description

Create a program that reads a file containing some text and counts the frequency of words in the file.

Text alternative 1: [Gangsta ipsum](http://lorizzle.nl/?feed=1)
Text alternative 2: [Shakespeare's Macbeth](http://shakespeare.mit.edu/macbeth/full.html)

### Example output

Given this text

```
badger badger badger badger mushroom mushroom snake badger badger badger
```

the program would produce the following output:

```
badger:   *******
mushroom: **
snake:    *
```

### Part 2 - Writing file

Modify the program to also write the results to a file next to the input file.

If you fed the program the file `/home/myself/macbeth.txt` then the results should be saved as `/home/myself/macbeth-word-frequency.txt`.
