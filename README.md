## FizzBuzz Pair Programming Challenge

#### Technologies:
Ruby

RSpec

### The Challenge:

The objective of Fizzbuzz is to create a program with the following specification:

- The program can be passed a number.
- When passed a number that is a multiple of 3, the program returns the message 'Fizz'.
- When passed a number that is a multiple of 5, the program returns the message 'Buzz'.
- When passed a number that is a multiple of both 3 and 5, the program ignores the previous 2 rules and returns the message 'Fizzbuzz'.
- In all other cases, the program simply returns the given number.

Example:
```

(1..20).each {|number| puts "#{number} --> #{fizzbuzz(number)}"}

1 --> 1
2 --> 2
3 --> fizz
4 --> 4
5 --> buzz
6 --> fizz
7 --> 7
8 --> 8
9 --> fizz
10 --> buzz
11 --> 11
12 --> fizz
13 --> 13
14 --> 14
15 --> fizzbuzz
16 --> 16
17 --> 17
18 --> fizz
19 --> 19
20 --> buzz
```

Throughout the challenge we switched roles between driver/navigator, using **TDD** and the **RED - GREEN - REFACTOR** process to increase code quality and program design.
