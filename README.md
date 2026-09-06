# 🏁 Car Management & Race Simulation System

A **C++ console-based Car Management and Race Simulation System** built to demonstrate practical implementation of **Data Structures, Algorithms, Dynamic Memory Allocation, and Object-Oriented Programming (OOP)**.

The application allows users to manage a virtual car garage, upgrade vehicles, organize race participants, sort cars by speed, sell vehicles, and simulate head-to-head races.

---

## ✨ Features

* 🏎️ **Add Cars** — Add individual cars with name, speed, and price.
* 🚗 **Add Multiple Cars** — Add multiple vehicles to the garage.
* 🎲 **Random Car Generator** — Generate cars with randomized specifications.
* 📋 **Display Garage** — View all cars currently stored in the garage.
* 🔍 **Search Cars** — Search for a car using its name.
* 📊 **Sort by Speed** — Sort cars based on top speed.
* 🏁 **Race Queue** — Add cars to a FIFO race queue.
* ⚡ **Upgrade Cars** — Increase a car's top speed.
* 🗑️ **Delete Cars** — Remove cars from the garage.
* 🏆 **Race Simulation** — Race two cars and determine the winner based on speed.
* 💰 **Sell Cars** — Sell vehicles and increase the player's balance.
* 💵 **Balance System** — Track the money earned from selling cars.

---

## 🧠 DSA & OOP Concepts

This project focuses on implementing fundamental DSA concepts without relying entirely on built-in containers.

| Concept                          | Usage                                             |
| -------------------------------- | ------------------------------------------------- |
| **Singly Linked List**           | Stores and manages cars dynamically in the garage |
| **Queue (****`std::queue`****)** | Maintains race participants using FIFO            |
| **Bubble Sort**                  | Sorts cars based on top speed                     |
| **Searching**                    | Finds cars by their model/name                    |
| **Dynamic Memory Allocation**    | Creates and deletes car nodes at runtime          |
| **Classes & Objects**            | Represents cars and garage operations             |
| **Encapsulation**                | Combines data and related operations              |
| **Pointers**                     | Used for linked-list node management              |

---

## 🎮 Application Menu

```text
------ Car Game Menu ------

1.  Add Car to Garage
2.  Add Multiple Cars to Garage
3.  Generate Random Car
4.  Display All Cars
5.  Search Car by Name
6.  Sort Cars by Speed
7.  Add All Cars to Race Queue
8.  Exit Car from Race Queue
9.  Upgrade Car (Increase Speed)
10. Delete Car by Name
11. Start Race
12. Sell Car for Money
13. Show Balance
14. Exit
```

---

## 📸 Sample Output

### Add a Car

```text
Enter choice: 1

Enter Car Name: BMW
Enter Speed: 230
Enter Price: 20000

Car added to garage.
```

### Generate a Random Car

```text
Enter choice: 3

Car added to garage.

Random Car Generated:
Name  : Storm75
Speed : 130 km/h
Price : 21296
```

### Race Simulation

```text
Enter choice: 11

Race Started!

Car Ferrari running at 210 km/h!
Car Audi running at 220 km/h!

Race Finished!

Winner: Audi
Speed : 220 km/h
```

---

## ⚙️ Requirements

Before running the project, make sure you have:

* **C++ compiler**
* **C++11 or later**
* GCC / g++
* Clang
* MSVC (Visual Studio)

---

## 🚀 Installation & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/uttkarsh-chimane/Car-Management-and-Race-Simulation-Using-CPP.git
```

### 2. Navigate to the Project

```bash
cd car-management-race-simulation
```

### 3. Compile the Program

```bash
g++ -std=c++11 car_game.cpp -o car_game
```

### 4. Run

#### Linux / macOS

```bash
./car_game
```

#### Windows

```bash
car_game.exe
```

---

## 🔄 How It Works

### Garage Management

Cars are stored using a **Singly Linked List**. Each node contains information about a car and a pointer to the next node.

```text
Head
 ↓
[ BMW | 230 | 20000 ] → [ Audi | 220 | 18000 ] → [ Ferrari | 210 | 25000 ] → NULL
```

This allows cars to be dynamically added and removed during program execution.

### Race Queue

Cars are added to a `std::queue` following the **FIFO (First-In-First-Out)** principle.

```text
Front
 ↓
Ferrari → Audi → BMW → NULL
                         ↑
                        Rear
```

Cars are removed from the front of the queue when races are started.

### Sorting

The garage can be sorted according to the cars' top speeds using **Bubble Sort**.

Example:

```text
Before:
BMW      → 230 km/h
Ferrari  → 210 km/h
Audi     → 220 km/h

After:
BMW      → 230 km/h
Audi     → 220 km/h
Ferrari  → 210 km/h
```

---

## 📈 Complexity

| Operation     | Complexity |
| ------------- | ---------: |
| Add Car       |       O(n) |
| Search Car    |       O(n) |
| Delete Car    |       O(n) |
| Sort Cars     |      O(n²) |
| Queue Enqueue |       O(1) |
| Queue Dequeue |       O(1) |

> Complexity may vary slightly depending on the specific implementation of the linked-list operations.

---

## 🎓 Learning Objectives

This project was developed to gain practical experience with:

* Data Structures
* Algorithms
* C++ Programming
* Object-Oriented Programming
* Pointers
* Dynamic Memory Allocation
* Linked Lists
* Queues
* Sorting Algorithms
* Searching Algorithms
* Basic Simulation Design

---
