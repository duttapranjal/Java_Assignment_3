# Java_Assignment_3
# 🎓 Student Result Management System (Java)

## 📘 Project Overview
The **Student Result Management System** is a Java console-based application that manages student details, validates marks, calculates averages, and displays results.  
It also demonstrates the use of **exception handling** in Java, including:
- Custom exceptions  
- Built-in exceptions  
- `try-catch-finally` blocks  
- `throw` and `throws` keywords  

---

## 🧩 Problem Statement
Create a Java program to:
- Accept student details (Roll Number, Name, and Marks in 3 subjects).  
- Validate that marks are between **0 and 100**.  
- If invalid marks are entered, raise a **custom exception**.  
- Display the student's result with **average marks** and **pass/fail** status.  
- Handle invalid inputs and unexpected runtime errors gracefully.  

---

## 🧠 Key Features
- Uses a **custom exception class (`InvalidMarksException`)**.  
- Handles **input errors** using `InputMismatchException`.  
- Implements **object-oriented programming** (OOP) principles.  
- Provides a **menu-driven interface** for user interaction.  

---

## 🧱 Class Structure

### 1. `InvalidMarksException`
A custom exception class that handles invalid marks input (less than 0 or greater than 100).

```java
class InvalidMarksException extends Exception {
    public InvalidMarksException(String message) {
        super(message);
    }
}
