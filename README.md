# 🔢 Recursive Digit Sum in C

This C program calculates the sum of digits of an integer using a **recursive function**.

---

## 💻 Language

C

---

## 📋 Description

- Uses a recursive function `sum(int n)` to compute digit sum
- Logic:
  - `n % 10` gives the last digit
  - `n / 10` reduces the number
  - Calls `sum(n / 10)` until `n` becomes 0
- Base case: when `n == 0`, return 0

---

## 🧪 Sample Output

Sum of digits in 12345 is 15

---

## 🛠️ How to Run

1. Save the file as `digit_sum.c`

2. Compile using GCC:
```bash
gcc digit_sum.c -o digitsum

3. Run the executable:
./digitsum

🌱 What I Learned

How recursion works in C

Breaking down a number using % and /

Using base cases effectively in recursive functions
