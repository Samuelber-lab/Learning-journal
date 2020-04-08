# Operators and loops
## Operators
The operator is tools that is used to evaluate asituation by comparing one value in the script to what you expect it might be. The resulting output will be a booleean, i.e., ***true*** or ***false***. Some examples of operators are below:

- == ----> IS EQUAL TO
        - it compares two values such as number, strings or booleans if they are same. Example:
        'Hello' == 'Goodbye' returns false
        'Hellow' == 'Hello' returns true
- != ----> IS NOT EQUAL TO
        - it compares if two value (numbers, strings or booleans) are not the same. Example:
        Hello' != 'Goodbye' returns true
        'Hellow' != 'Hello' returns false
However, it is highly preferable and recommended to use comparisons in a strict sense. Such as,
- === ----> STRICT EQUAL TO
        - used to compare if two values if they are the same both in terms of data type and magnitude/ value.
        3 === '3' returns false
        '3' === '3' returns true
- !== ---> STRICT NOT EQUAL TO
        - used to compare if two values are not same in terms of type and value/ magnitude.
        '3' !== 3 returns true
        '3' !== '3' returns false
- > ----> GREATER THAN
        4 > 3 returns true
        3 > 4 returns false
- < ----> LESS THAN
        4 < 3 returns false
        3 <> 4 returns true
- >= ----> GREATER THAN OR EQUAL TO
        4 >= 3 returns true
        3 >= 4 returns false
        3 >= 3 returns true
- <= ----> LESS THAN OR EQUAL TO
        4 <= 3 returns false
        3 <= 4 returns true
        3 <= 3 returns true
## Logical operators
They allow the comparison of results from more than one operators. Example,

- && ----> LOGICAL AND
        ((5 < 2) && (2 >= 3))
          false       false
- || ----> LOGICAL OR
        ((2 < 5) || (2 < 1))
        returns true
- ! ----> LOGICAL NOT
        !(2 < 1)
        returns true

## Loops
Loops check a condition. if it returns true, a code block will run. Then the condition will be checked again and if returns true, a code block will run, and this goes like this repetitively. There are three common types of loops:
- FOR
- WHILE
- DO WHILE
 
        



