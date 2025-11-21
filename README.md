# Java Advanced: Exception Handling & Collections

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Java](https://img.shields.io/badge/Java-100%25-orange)
![Repo Size](https://img.shields.io/github/repo-size/TheComputationalCore/java-advanced-exceptions-collections)

---

## 🚀 Overview

This repository contains **advanced Java exercises (Q1–Q5)** focusing on:

- Custom Exception Handling  
- Input Validation  
- Java Collections Framework  
- HashMap operations  
- Stack implementation  
- User‑driven logic & error handling  

All tasks include **screenshots**, **organized source code**, and a **fully automated CI workflow**.

---

## 📁 Project Structure

```
java-advanced-exceptions-collections/
│
├── .github/workflows/
│   └── java-build.yml
│
├── screenshots/
│   ├── 1.a.png
│   ├── 1.b.png
│   ├── 1.c.png
│   ├── 1.d.png
│   ├── 2.a.png
│   ├── 2.b.png
│   ├── 3.a.png
│   ├── 3.b.png
│   ├── 3.c.png
│   ├── 4.a.png
│   ├── 4.b.png
│   ├── 4.c.png
│   ├── 4.d.png
│   └── 5.png
│
├── src/
│   ├── AgeNotWithinRangeException.java
│   ├── NameNotValidException.java
│   ├── Student.java
│   ├── Voter.java
│   ├── QuestionThree.java
│   ├── QuestionFour.java
│   ├── QuestionFive.java
│   └── (supporting logic)
│
├── LICENSE
└── README.md
```

---

## 🧠 Task Breakdown

### **Q1 — Student Class with Custom Exceptions**
Validates:
- Age must be **between 15–21**
- Name must *not* contain numbers or special symbols

Uses two custom exceptions:
- `AgeNotWithinRangeException`
- `NameNotValidException`

---

### **Q2 — Voter Age Validation**
Ensures:
- Age ≥ 18  
Else throws **Invalid Age Exception**.

---

### **Q3 — Weekday Array Handling**
- Takes a day index as input
- Prints weekday name
- Handles:
  - Invalid numeric input  
  - Array out‑of‑bounds cases  

---

### **Q4 — Student Grades Using HashMap**
Supports:
- Add student + grade  
- Remove student  
- Fetch grade  

Uses:
```java
HashMap<String, Integer>
```

---

### **Q5 — Stack Implementation (Collections)**
Operations:
- `push()`
- `pop()`
- `isEmpty()`

Uses:
```java
Stack<Integer>
```

---

## 🖼️ Screenshots (Grid Layout)

### **Q1 — Student Management**
<table>
<tr>
<td><img src="screenshots/1.a.png" width="260"></td>
<td><img src="screenshots/1.b.png" width="260"></td>
</tr>
<tr>
<td><img src="screenshots/1.c.png" width="260"></td>
<td><img src="screenshots/1.d.png" width="260"></td>
</tr>
</table>

---

### **Q2 — Voter Age Validation**
<table>
<tr>
<td><img src="screenshots/2.a.png" width="260"></td>
<td><img src="screenshots/2.b.png" width="260"></td>
</tr>
</table>

---

### **Q3 — Weekday Array**
<table>
<tr>
<td><img src="screenshots/3.a.png" width="260"></td>
<td><img src="screenshots/3.b.png" width="260"></td>
<td><img src="screenshots/3.c.png" width="260"></td>
</tr>
</table>

---

### **Q4 — HashMap Grades**
<table>
<tr>
<td><img src="screenshots/4.a.png" width="260"></td>
<td><img src="screenshots/4.b.png" width="260"></td>
</tr>
<tr>
<td><img src="screenshots/4.c.png" width="260"></td>
<td><img src="screenshots/4.d.png" width="260"></td>
</tr>
</table>

---

### **Q5 — Stack**
<img src="screenshots/5.png" width="320">

---

## ▶️ How to Run

### Clone
```bash
git clone https://github.com/TheComputationalCore/java-advanced-exceptions-collections.git
```

### Navigate
```bash
cd java-advanced-exceptions-collections/src
```

### Compile Everything
```bash
javac *.java
```

### Run Any Task
```bash
java Student          # Q1
java Voter            # Q2
java QuestionThree    # Q3
java QuestionFour     # Q4
java QuestionFive     # Q5
```

---

## 📜 License
Distributed under the **MIT License**.

---

## ⭐ Contribution
Feel free to open PRs, file issues, or suggest improvements!

