# Java Advanced: Exception Handling & Collections

![Build Status](https://github.com/TheComputationalCore/java-advanced-exceptions-collections/actions/workflows/java-build.yml/badge.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Java](https://img.shields.io/badge/Java-100%25-orange)
![Repo Size](https://img.shields.io/github/repo-size/TheComputationalCore/java-advanced-exceptions-collections)

---

## 📚 Overview

This repository showcases **advanced Java concepts**, focusing on:

- Custom exception handling  
- Collections framework usage  
- Stack implementation  
- HashMaps  
- Array exception management  

It contains **five structured tasks (Q1–Q5)**, each reinforced with code screenshots laid out in elegant grids.

---

## 🛠️ Tech Stack

| Language | Paradigm | Topics |
|---------|----------|--------|
| **Java 8+** | OOP, Exception Handling | Collections, Custom Exceptions, Stack, HashMap |

---

## 📁 Project Structure

```
src/
├── AgeNotWithinRangeException.java
├── NameNotValidException.java
├── Student.java
├── Voter.java
├── QuestionThree.java
├── QuestionFour.java
├── QuestionFive.java
└── screenshots/
    ├── 1.a.png
    ├── 1.b.png
    ├── 1.c.png
    ├── 1.d.png
    ├── 2.a.png
    ├── 2.b.png
    ├── 3.a.png
    ├── 3.b.png
    ├── 3.c.png
    ├── 4.a.png
    ├── 4.b.png
    ├── 4.c.png
    ├── 4.d.png
    └── 5.png
```

---

# 📝 Tasks Overview

---

# **Q1 — Student Management System (Custom Exceptions)**

### ✔ Validates:
- Age range (15–21)
- Name characters (no digits/symbols)

### ✔ Custom Exceptions:
- `AgeNotWithinRangeException`
- `NameNotValidException`

### 📸 Screenshots
| 1.a | 1.b |
|---|---|
| ![](screenshots/1.a.png) | ![](screenshots/1.b.png) |

| 1.c | 1.d |
|---|---|
| ![](screenshots/1.c.png) | ![](screenshots/1.d.png) |

---

# **Q2 — Voter Age Validation**

Throws exception if voter age < 18.

### 📸 Screenshots
| 2.a | 2.b |
|---|---|
| ![](screenshots/2.a.png) | ![](screenshots/2.b.png) |

---

# **Q3 — Weekday Array Handling**

Handles `ArrayIndexOutOfBoundsException` for invalid day index.

### 📸 Screenshots
| 3.a | 3.b |
|---|---|
| ![](screenshots/3.a.png) | ![](screenshots/3.b.png) |

| 3.c | — |
|---|---|
| ![](screenshots/3.c.png) |  |

---

# **Q4 — Student Grades with HashMap**

Enables:
- Add student + grade  
- Remove student  
- Display grade by name  

### 📸 Screenshots
| 4.a | 4.b |
|---|---|
| ![](screenshots/4.a.png) | ![](screenshots/4.b.png) |

| 4.c | 4.d |
|---|---|
| ![](screenshots/4.c.png) | ![](screenshots/4.d.png) |

---

# **Q5 — Stack Implementation (Collections)**

Implements push, pop, isEmpty using Java Collections.

### 📸 Screenshot
| 5 |
|---|
| ![](screenshots/5.png) |

---

# ▶️ How to Run

```bash
git clone https://github.com/TheComputationalCore/java-advanced-exceptions-collections.git
cd java-advanced-exceptions-collections
javac *.java
java Student        # Q1
java Voter          # Q2
java QuestionThree  # Q3
java QuestionFour   # Q4
java QuestionFive   # Q5
```

---

# 📄 License

Distributed under the MIT License.

---

