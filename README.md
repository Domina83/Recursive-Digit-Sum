# Recursive Digit Sum

This C program calculates the sum of digits of an integer using a recursive function.

## 💻 Language

C

## 📋 Description

- Uses a recursive function `sum(int n)` to calculate the sum of digits.
- Works by:
  - Taking the last digit using `n % 10`
  - Reducing the number using `n / 10`
  - Recursively calling `sum()` until `n` becomes 0

## 🧪 Sample Output

Sum of digits in 12345 is 15

## 🛠️ How to Run

```bash
gcc digit_sum.c -o digitsum
./digitsum

🌱 What I Learned

How recursion works in C

How to break down a number using % and /

Using base cases in recursive functions
