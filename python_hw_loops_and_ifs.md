# Question 1: Print Even Numbers

Create a list containing **10 numbers**.

Use a `for` loop to go through every number in the list. For each number, check whether it is even. Print only the even numbers.

## Hint: Checking Whether a Number Is Even

The `%` symbol is called the **modulo operator**.

It divides one number by another and returns the **remainder**.

Example 1:
We know `5` is odd. Given the code below:

```python
5 % 2
```

When you divide an odd number like `5` by `2`, the remainder is always `1`. Therefore, the result is:

```python
1
```

Example 2: We know `4` is even.
Given the code below

```python
4 % 2
```

When you divide an even number like `4` by `2`, the remainder is always `0`. Therefore, the result is:

```python
0
```


The code below checks if a number is even by dividing it by `2` and then checking if the result `is equal to (==)` zero.

```python
if number % 2 == 0:
    print(number)
```

## Your Task

1. Create a list of 10 numbers.
2. Use a `for` loop to check each number.
3. Print every even number.

```python
numbers = [
    # Add 10 numbers here
]

# Write your for loop below

# Print even numbers using if
    if number % 2 == 0:
        print(number)
```


# Question 2a: Predict the Output

Without running the code below, read it carefully, line by line, and answer in brief detail:

1. What will be the output of the program?
2. What do you think the `>` and `<` operators do? 

```python
numbers = [4, -2, 0, 7, -9]

for number in numbers:
    if number > 0:
        print("Positive")
    elif number < 0:
        print("Negative")
    else:
        print("Zero")
```

## Question 2b: Confirm the Output
Copy the python code above (in 2a) to your python file and run it. 
Is the answer what you expected?
If not, what was the difference?
