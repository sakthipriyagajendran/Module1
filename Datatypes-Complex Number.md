# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
real_part = int(input("Enter the real part: "))
imag_part = int(input("Enter the imaginary part: "))
complex_number = complex(real_part, imag_part)
print("Complex Number:", complex_number)
print("Real Part:", complex_number.real)
print("Imaginary Part:", complex_number.imag)

## Output
<img width="407" height="302" alt="image" src="https://github.com/user-attachments/assets/3eb215ce-8dbb-4075-b19d-534586cce3b5" />

## Result
Thus,the program was implemented and executed successfully,and the required output was obtained.
