# Advanced Java Programming Course (20554)
## Spring Semester 2024B - The Open University of Israel

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/java/)
[![JavaFX](https://img.shields.io/badge/JavaFX-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://openjfx.io/)
[![Grade](https://img.shields.io/badge/Grade-100%2F100-brightgreen?style=for-the-badge)](https://github.com/yourusername/advanced-java-20554)

## 📋 Course Overview

This repository contains my solutions for the Advanced Java Programming course (20554) at The University. 
The course covers advanced Java concepts including object-oriented programming, JavaFX GUI development, data structures, multithreading, and more.

## 🎯 Course Objectives

- Master advanced Java programming concepts
- Develop GUI applications using JavaFX
- Implement complex data structures and algorithms
- Work with multithreading and concurrent programming
- Apply object-oriented design principles
- Build real-world applications and simulations

## 📚 Assignments Overview

### Maman 11 (Grade: 100/100)
**Learning Material:** Chapters 1-7  
**Due Date:** April 5, 2024  
**Weight:** 4 points

#### Question 1: Card Game "War" Implementation
- **Points:** 50/100
- **Description:** Implementation of the classic "War" card game
- **Features:**
  - Card and Deck classes using ArrayList
  - Game logic with war scenarios
  - Player management and game state tracking
  - Console-based game interface

#### Question 2: JavaFX Grid Drawing Application
- **Points:** 50/100
- **Description:** Interactive drawing application with matrix grid
- **Features:**
  - 10x10 grid with 10px spacing between lines
  - Random 10% cell filling
  - Button to regenerate random pattern
  - Canvas-based drawing using JavaFX

### Maman 12 (Grade: 100/100)
**Learning Material:** Chapters 1-11  
**Due Date:** April 19, 2024  
**Weight:** 4 points

#### Question 1: Employee Hierarchy System
- **Points:** 50/100
- **Description:** Extended employee management system
- **Features:**
  - Employee hierarchy with polymorphism
  - Birthday tracking and bonus calculation
  - PieceWorker employee type implementation
  - Calendar integration for birthday detection

#### Question 2: Rational Number Calculator
- **Points:** 50/100
- **Description:** Complete rational number arithmetic system
- **Features:**
  - Rational number class with full arithmetic operations
  - GCD-based number reduction
  - Exception handling for invalid operations
  - Interactive calculator interface

### Maman 15 (Grade: 100/100)
**Learning Material:** Chapters 1-23  
**Due Date:** June 14, 2024  
**Weight:** 4 points

#### Question 1: Parallel Array Summation
- **Points:** 50/100
- **Description:** Multithreaded array processing system
- **Features:**
  - Parallel summation using multiple threads
  - Shared buffer implementation
  - Thread synchronization and coordination
  - Configurable thread count and array size

#### Question 2: Airport Flight Simulation
- **Points:** 50/100
- **Description:** Complex multithreaded flight simulation
- **Features:**
  - Airport with multiple runways
  - Flight threading for takeoffs and landings
  - Resource management and synchronization
  - Real-time simulation with logging

## 🛠️ Technologies Used

- **Java SE 8+** - Core programming language
- **JavaFX** - GUI framework for desktop applications
- **ArrayList & Collections** - Data structure implementations
- **Multithreading** - Concurrent programming concepts
- **Exception Handling** - Robust error management
- **Object-Oriented Design** - Inheritance, polymorphism, encapsulation

## 📁 Project Structure

```
advanced-java-20554/
├── maman11/
│   ├── src/
│   │   ├── CardGame/
│   │   │   ├── Card.java
│   │   │   ├── DeckOfCards.java
│   │   │   └── WarGame.java
│   │   └── GridDrawing/
│   │       ├── GridController.java
│   │       └── GridApplication.java
│   └── README.md
├── maman12/
│   ├── src/
│   │   ├── EmployeeHierarchy/
│   │   │   ├── Employee.java
│   │   │   ├── PieceWorker.java
│   │   │   └── EmployeeTest.java
│   │   └── RationalCalculator/
│   │       ├── Rational.java
│   │       └── RationalTest.java
│   └── README.md
├── maman15/
│   ├── src/
│   │   ├── ParallelSum/
│   │   │   ├── SumBuffer.java
│   │   │   ├── SumWorker.java
│   │   │   └── ParallelSumMain.java
│   │   └── AirportSimulation/
│   │       ├── Airport.java
│   │       ├── Flight.java
│   │       └── FlightSimulation.java
│   └── README.md
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- JavaFX SDK (for GUI applications)
- IDE (IntelliJ IDEA, Eclipse, or VS Code)

### Running the Applications

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/advanced-java-20554.git
   cd advanced-java-20554
   ```

2. **Compile and run individual assignments:**
   ```bash
   # For Maman 11 - Card Game
   cd maman11/src/CardGame
   javac *.java
   java WarGame
   
   # For JavaFX applications (make sure JavaFX is in classpath)
   java --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.graphics GridApplication
   ```

3. **Each assignment includes a run.bat file for easy execution**

## 🎓 Learning Outcomes

Through this course, I gained expertise in:

- **Advanced OOP Concepts:** Inheritance, polymorphism, abstract classes, interfaces
- **GUI Development:** JavaFX controls, event handling, graphics programming
- **Data Structures:** Custom implementations of lists, stacks, queues
- **Multithreading:** Thread creation, synchronization, concurrent programming
- **Exception Handling:** Custom exceptions, error recovery strategies
- **Design Patterns:** Observer, Strategy, Factory patterns implementation

## 📊 Course Statistics

- **Total Assignments:** 5 (Maman 11-15)
- **Total Points:** 20 points
- **Average Grade:** 100/100
- **Completion Rate:** 100%

## 🔗 Additional Resources

- [Java Documentation](https://docs.oracle.com/javase/8/docs/)
- [JavaFX Documentation](https://openjfx.io/javadoc/11/)

## 📝 License

This project is created for educational purposes as part of the Advanced Java Programming course at The Open University of Israel. Please respect academic integrity guidelines when referencing this work.

---

**Note:** This repository contains my personal solutions to course assignments. While the code is provided for educational reference, please ensure you follow your institution's academic integrity policies when working on similar assignments.
