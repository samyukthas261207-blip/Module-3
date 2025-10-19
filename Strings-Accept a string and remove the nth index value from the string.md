# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
string = input()

n = int(input())

def remove(string):

    for i in range(len(string)):
        if i != n:
            print(string[i], end="")


## Output

<img width="878" height="296" alt="Screenshot (88)" src="https://github.com/user-attachments/assets/191fb26a-3055-4084-84c8-c96a65fb1958" />

## Result
Thus program is executed successfully.
