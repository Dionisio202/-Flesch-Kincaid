# Shakespeare Flesch-Kincaid Grade Level Calculator (Concurrent Java)

This project was developed as part of the Coursera course **"Java Concurrent Functional Programming of Bard Works Analysis"**.

## 📚 Assignment Overview

The goal of this assignment is to calculate the **Flesch-Kincaid Grade Level** for each play written by **William Shakespeare** using Java's concurrent programming features.

Specifically, the solution applies the **Active Object** and **Future** patterns to compute each score **in parallel**, demonstrating efficient concurrent task management.

## 🧩 Technologies and Patterns Used

- Java 17+
- Functional Programming with Streams
- Java Concurrency:
  - `ExecutorService`, `Callable`, `Future`
- **Design Patterns**:
  - Active Object
  - Future

## 🛠️ Project Structure

- `Array.java`: Custom generic array implementation (from previous assignments).
- `FleschKincaidGradeLevelCalculator.java`: Calculates readability scores using syllable, word, and sentence counts.
- `PlayLoader.java`: Loads all Shakespeare plays from the dataset.
- `ConcurrentCalculator.java`: Manages concurrent score computation using Active Object pattern.
- `Main.java`: Entry point that initializes the calculator, dispatches tasks, and prints results.

## 🚀 How to Run

```bash
javac -d out src/**/*.java
java -cp out Main
