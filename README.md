# Java Word Count (javawc)

## Author
**Arushi Rathore**  
GitHub: https://github.com/arushirrathore  

---

## Project Description
Java Word Count (javawc) is a command-line utility built using Java that replicates the core functionality of the Unix `wc` command. The application reads a text file and computes the total number of **lines, words, and characters**.

This project demonstrates strong fundamentals in **Java programming, object-oriented design, file handling, exception management, and unit testing**, making it suitable for entry-level Java developer and software engineering roles.

---

## Features
- Reads text files using Java NIO
- Calculates:
  - Line count
  - Word count
  - Character count
- Modular and maintainable object-oriented architecture
- Unit tests implemented using JUnit
- Gradle-based build and dependency management

---

## Tech Stack
- **Language:** Java  
- **Build Tool:** Gradle  
- **Testing Framework:** JUnit  
- **Concepts Used:**  
  - Object-Oriented Programming (OOP)  
  - File I/O and Exception Handling  
  - String Processing and Regular Expressions  
  - Unit Testing  

---

src/
├── main/java
│ ├── FileLoader.java
│ ├── WordCount.java
│ └── Main.java
└── test/java
├── FileLoaderTest.java
└── WordCountTest.java


---

## How It Works
1. The application loads a text file using the `FileLoader` class.
2. File content is passed to the `WordCount` class.
3. The program processes the content to compute:
   - Number of lines
   - Number of words
   - Number of characters
4. The results are printed to the console.

---

▶️ Run Java Project in VS Code (Gradle)
1️⃣ Open project in VS Code
code .

2️⃣ Open VS Code Terminal

Shortcut:

Ctrl + `

3️⃣ Build the project
gradlew build

4️⃣ Run the project
gradlew run

▶️ Direct Java Run (Without Gradle)

If you want to run using javac and java:

javac src/main/java/com/oracle/javawc/main/Main.java
java com.oracle.javawc.main.Main

▶️ Run using VS Code UI (Easiest)

Open Main.java

Click ▶ Run above public static void main

Output will appear in the Terminal
