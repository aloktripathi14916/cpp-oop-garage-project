# cpp-oop-garage-project
# 🚗 C++ Vehicle Management System

A console-based OOP project in C++ that simulates different types of vehicles using inheritance and polymorphism.

## 🔥 Features

* Abstract base class `vehicle`
* Multi-level inheritance (vehicle → airplane → jet)
* Hierarchical inheritance (vehicle → car → BMW, Ferrari, Lamborghini)
* Virtual functions & runtime polymorphism
* Operator overloading (`>` for jets)
* Dynamic object creation using pointers
* User input-based vehicle creation

## 🧠 Concepts Used

* OOP (Encapsulation, Inheritance, Polymorphism)
* Virtual Functions
* Dynamic Memory Allocation
* Function Overloading
* STL (vector)

## ▶️ How to Run

```bash
g++ main.cpp -o main
./main
```

## 📌 Sample Input

```
Number of vehicles:
1
Choice:
BMW
Name:
M5
Wheels:
4
Seats:
5
Maxspeed:
250
Weight:
2
Fuel Type:
Petrol
```

## 📌 Sample Output

```
BMW: M5
Series: ...
Max Speed: 250 km/h
```

## 💡 Future Improvements

* Add file saving (persistent storage)
* Add menu system instead of repeated input
* Use smart pointers instead of raw pointers
* Add GUI (maybe using Qt)

## 👨‍💻 Author

Alok Tripathi
