# Java Word Count Tool (javawc)

## 👩‍💻 Author
**Arushi Rathore**  
GitHub: [@arushirrathore](https://github.com/arushirrathore)

---

## 📝 Description

A command-line utility that replicates the Unix `wc` command. Reads text files and calculates **line count, word count, and character count**.

---

## ✨ Features

- Reads text files using Java NIO
- Calculates lines, words, and characters
- Object-oriented architecture
- Unit tests with JUnit
- Gradle build system

---

## 🛠️ Tech Stack

**Language:** Java | **Build Tool:** Gradle | **Testing:** JUnit

---

## 📁 Project Structure

```
src/
├── main/java/
│   ├── Main.java
│   ├── FileLoader.java
│   └── WordCount.java
└── test/java/
    ├── FileLoaderTest.java
    └── WordCountTest.java
```

---

## 🚀 Setup & Installation

### Prerequisites
- Java JDK 8 or higher
- Gradle (optional - wrapper included)

### Clone Repository
```bash
git clone https://github.com/arushirrathore/word_count_tool_ar.git
cd word_count_tool_ar
```

---

## ▶️ How to Run

### Option 1: Using Gradle
```bash
# Build
gradlew build

# Run
gradlew run
```

### Option 2: Using Java Directly
```bash
javac src/main/java/com/oracle/javawc/main/Main.java
java com.oracle.javawc.main.Main
```

### Option 3: Using VS Code
1. Open `Main.java`
2. Click ▶️ Run button above `main` method

---

## 🧪 Run Tests
```bash
gradlew test
```

---

## 💻 Example Output

**Input File:**
```
Hello World
This is a test
```

**Output:**
```
Lines: 2
Words: 6
Characters: 26
```
