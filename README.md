# Java Advanced: Exception Handling & Collections 

This repository showcases **advanced Java concepts**, focusing on **custom exceptions**, **robust error handling**, and **Java Collections Framework** usage.  
It includes **five fully implemented tasks (Q1–Q5)** accompanied by code screenshots for clarity and reference.

---

## 📁 Project Structure

```
├── AgeNotWithinRangeException.java     # Custom exception for invalid student age
├── NameNotValidException.java          # Custom exception for invalid name
├── Student.java                        # Student class using custom exceptions (Q1)
├── Voter.java                          # Voter class with age validation (Q2)
├── QuestionThree.java                  # Weekday array + exception handling (Q3)
├── QuestionFour.java                   # HashMap for student grades (Q4)
├── QuestionFive.java                   # Stack implementation using collections (Q5)
├── Screenshots/
│   ├── 1.a.png 1.b.png 1.c.png 1.d.png
│   ├── 2.a.png 2.b.png
│   ├── 3.a.png 3.b.png 3.c.png
│   ├── 4.a.png 4.b.png 4.c.png 4.d.png
│   └── 5.png
└── README.md
```

---

## 🧩 Task Overviews

### **Q1 — Student Management System (Custom Exceptions)**  
Implements:
- `Student` class with:
  - `rollNo`, `name`, `age`, `course`
- Custom exceptions:
  - **AgeNotWithinRangeException** → age must be between **15–21**
  - **NameNotValidException** → name must contain only letters
- Validates input using constructor-based rules.

📸 **Screenshots:**  
![1.c](1.c.png)  
![1.d](1.d.png)

---

### **Q2 — Voter Age Validation**  
`Voter` class validates:
- Age must be **18 or above**
- Throws an exception for invalid age

📸 **Screenshots:**  
![2.a](2.a.png)  
![2.b](2.b.png)

---

### **Q3 — Weekday Array + Exception Handling**  
- Stores weekday names in an array (index 0 = Sunday)
- Accepts user index input
- Handles:
  - **ArrayIndexOutOfBoundsException**
  - Prints helpful error message

📸 **Screenshots:**  
![3.a](3.a.png)  
![3.b](3.b.png)  
![3.c](3.c.png)

---

### **Q4 — Student Grades Using HashMap**  
Implements:
- Add student + grade  
- Remove student  
- Display grade by name  

Uses Java **HashMap** to store key–value pairs.

📸 **Screenshots:**  
![4.a](4.a.png)  
![4.b](4.b.png)  
![4.c](4.c.png)  
![4.d](4.d.png)

---

### **Q5 — Stack Implementation Using Collections**  
Implements:
- `push()`
- `pop()`
- `isEmpty()`

Built using a Java **Stack** or similar collection class.

📸 **Screenshot:**  
![5](5.png)

---

## ▶️ How to Run

### **1. Clone the Repository**
```bash
git clone https://github.com/thesoulseizure/task-4.git
cd task-4
```

### **2. Compile All `.java` Files**
```bash
javac *.java
```

### **3. Run Any Task**

| Task | Command |
|------|----------|
| Q1 — Student | `java Student` |
| Q2 — Voter | `java Voter` |
| Q3 — Weekday Array | `java QuestionThree` |
| Q4 — HashMap Grades | `java QuestionFour` |
| Q5 — Stack | `java QuestionFive` |

---

## 📌 Requirements
- **JDK 8 or higher**
- Any IDE or terminal that can compile and run Java programs

---

## 📄 License  
This project is for **educational purposes** and demonstrates core Java error-handling & collections concepts.

---


