# 🧮 Arbitrary Precision Calculator (APC) using C

A C-based implementation of an Arbitrary Precision Calculator that performs arithmetic operations on very large integers using the Doubly Linked List data structure.

This project eliminates standard data type limitations by dynamically storing and processing numbers of any size.

---

## 🚀 Features

- ➕ Addition of very large integers  
- ➖ Subtraction with proper borrow handling  
- ✖️ Multiplication using digit-by-digit logic  
- 📦 Supports numbers beyond built-in data type limits  
- 🔗 Uses Doubly Linked List for efficient traversal  
- 🧠 Dynamic memory-based arithmetic processing  

---

## ⚙️ Working Principle

1️⃣ Accept large integers as input (string format).  
2️⃣ Convert each digit into a node of a Doubly Linked List.  
3️⃣ Maintain links to both previous and next nodes.  
4️⃣ Traverse from least significant digit for computation.  
5️⃣ Handle carry and borrow during operations.  
6️⃣ Store result in a new Doubly Linked List.  
7️⃣ Display final computed large integer.  

---

## 🧠 Data Structure Used

- 🔗 Doubly Linked List  
- 📌 Each node contains:
  - A single digit  
  - Pointer to previous node  
  - Pointer to next node  
- 🏗️ Dynamic allocation for flexible memory management  

---

## 📚 Concepts Used

- 📌 Dynamic memory allocation (`malloc`, `free`)  
- 🔁 Forward and backward traversal  
- 🔗 Pointer manipulation  
- ➕ Carry and borrow logic  
- 🧠 Large integer arithmetic using DSA  

---

## 👨‍💻 Author

S Sreedhar
