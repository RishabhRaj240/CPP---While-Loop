# Do-While Loop Demonstration in C++

A simple beginner-friendly C++ program demonstrating the use of a `do-while` loop.

This project helps beginners understand how a `do-while` loop executes at least once, even when the condition is false.

---

## 📌 Features

* Demonstrates `do-while` loop syntax
* Prints output before checking the condition
* Shows loop variable incrementing
* Displays the final value of the variable after loop execution

---

## 🛠️ Technologies Used

* C++
* Standard Input/Output (`iostream`)

---

## 📂 Program Logic

The program:

1. Initializes the variable `i` with value `2`
2. Executes the `do` block once
3. Prints:

   * `"Rishab"` along with the value of `i`
4. Increments `i`
5. Checks the condition `i <= 1`
6. Since the condition is false, the loop stops
7. Prints the final value of `i`

---

## 📸 Screenshot

<img width="1051" height="475" alt="Screenshot 2026-06-13 095443" src="https://github.com/user-attachments/assets/2cb97841-a5cc-4558-9ff1-4051162d2e68" />

Example folder structure:

```txt id="jlwm42"
project-folder/
│
├── main.cpp
├── README.md
└── screenshots/
    └── output.png
```

---

## 💻 Source Code

```cpp id="h3jw9e"
#include<iostream>
using namespace std;

int main() {

    int i = 2;

    do {
        cout << "Rishab " << i << endl;
        i = i + 1;

    } while (i <= 1);

    cout << i << endl;

    return 0;
}
```

---

## ▶️ How to Run

1. Compile the program:

```bash id="o92md1"
g++ main.cpp -o main
```

2. Run the executable:

```bash id="9dj3a1"
./main
```

---

## 📸 Example Output

```txt id="c9e3q2"
Rishab 2
3
```

---

## 📖 Learning Concepts

This project helps beginners understand:

* `do-while` loops
* Loop execution flow
* Increment operations
* Condition checking
* Difference between `while` and `do-while`

---

## 🔍 Key Observation

A `do-while` loop executes the code block at least once before checking the condition.

In this example:

```cpp id="o1h8sv"
while (i <= 1)
```

The condition is false from the beginning because `i = 2`, but the loop still runs once.

---

## 👨‍💻 Author

Developed as a beginner-friendly C++ practice project for learning loops and iteration.
