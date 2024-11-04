# HW2 Breakdown - and what to submit

## Overview
Homework 2 has 3 parts. 
1. Lucas Numbers
2. Details of Lucas Numbers
3. Subirachs Magic Square

Parts 1 and 2 can be combined as part 2 encapsulates part 1. However, part 3 is a standalone part.

<br>

## Parts 1 and 2 (Lucas Numbers + details)

Once you have completed parts 1 and 2, you should have a program that accepts a number `n` and prints the Lucas Numbers from `0` to `n`. You should then display the 
times taken to calculate these values (`0` to `n`) and their ratios.

Answer the question `What is the order of growth of your algorithm?` in either your code and display it to the terminal or in your `README.txt`/`README.md` file attached in 
your submission.

Lastly, repeat the process above with a custom sequence of numbers (change the starting values of `number 0` and `number 1`).

#### Sample Output:
|Index|Lucas Number|Time Taken To Calculate|Lucas Ratio          |Time Ratio|
|-----|------------|-----------------------|---------------------|----------|
|`0`  |`Lucas(0)`  |`calc_time(lucas(0))`  |`Lucas(1) / Lucas(0)`|`CT(L(1)) / CT(L(0))`|
|`1`  |`Lucas(1)`  |`calc_time(lucas(1))`  |`Lucas(2) / Lucas(1)`|`CT(L(2)) / CT(L(1))`|
|`2`  |`Lucas(2)`  |`calc_time(lucas(2))`  |`Lucas(3) / Lucas(2)`|`CT(L(3)) / CT(L(2))`|

<br>

## Part 3 (Subirachs Magic Square)

Most students get tripped up by the "square" and try to encapsulate its properties in their code. **Don't do that**.

After reading part 3 of the assignment (before starting to write code), students **should** see that the square itself is not relevant, but instead, the values are 
what's important. The sum of the rows is also important.

* ##### JAVA:
    ```java
    public static final int[] square = {1, 14, 14, 4, 11, 7, 6, 9, 8, 10, 10, 5, 13, 2, 3, 15};
    public static final int sum_of_rows = 33;
    ```
* ##### C:
    ```c
    const int square[16] = {1, 14, 14, 4, 11, 7, 6, 9, 8, 10, 10, 5, 13, 2, 3, 15};
    const int sum_of_rows = 33;
    ```

Display all 4 element combinations of the square (array) that add up to the sum (33).

Next, display all element combinations of the square (array) that add up to the `sum` (`33`) regardless of how many elements are used.

Next, display all element combinations of each sum from `0` to `sum(square)`.

Lastly, answer the final bullet point.

<br>

#### [back](./)
