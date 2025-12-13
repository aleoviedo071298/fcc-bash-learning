# 🐧 Bash Programs – FreeCodeCamp

This repository contains **Bash scripts** created as part of the **FreeCodeCamp Bash / Linux curriculum**.  
Each script focuses on practicing core **shell scripting concepts** such as variables, conditionals, loops, functions, arrays, random numbers, and user input.

This project is intended for **learning purposes**, helping to understand how Bash scripts work in real Linux environments.

---

## 📂 Scripts Included

### 1️⃣ questionnaire.sh
An interactive script that asks the user a series of questions and then prints a personalized message.

**Concepts used:**
- Variables
- `read` for user input
- `echo` formatting

---

### 2️⃣ countdown.sh
Counts down to zero from a positive integer passed as a command-line argument.

**Concepts used:**
- Positional parameters (`$1`)
- `if` conditional
- `while` loop
- Arithmetic operations
- `sleep`

---

### 3️⃣ bingo.sh
Generates a random Bingo number (1–75) and assigns the correct letter (B, I, N, G, O).

**Concepts used:**
- Random numbers (`$RANDOM`)
- Arithmetic evaluation `(( ))`
- Conditional logic (`if`, `elif`)
- Variables and formatted output

---

### 4️⃣ fortune.sh
A fortune teller script that asks the user a yes/no question and returns a random response, validating that the question ends with a question mark.

**Concepts used:**
- Arrays
- Functions
- Regular expressions
- Input validation
- `until` loop
- Random index selection

---

### 5️⃣ five.sh
A master script that runs the other four programs in sequence.

**Concepts used:**
- Script execution
- Basic automation
- Program orchestration

---

### 📝 castle.sh
A beginner Bash script built entirely using the **Nano text editor**, emphasizing hands-on learning of terminal editing workflows.

**Concepts learned:**
- Creating and modifying files with Nano
- Navigating and editing text in a terminal editor
- Saving, exiting, and reopening files
- Handling stopped processes (`Ctrl + Z`, `fg`)
- Executing scripts using `bash`

## 🛠️ Technologies & Tools

- **Bash / Shell scripting**
- **Linux terminal**
- **GNU utilities**
- **FreeCodeCamp**

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/five-bash-programs-fcc.git
Give execution permissions:

bash
Copiar código
chmod +x *.sh
Run individual scripts:

bash
Copiar código
./questionnaire.sh
./countdown.sh 5
./bingo.sh
./fortune.sh
Or run all programs at once:

bash
Copiar código
./five.sh
🎯 Learning Objectives
Through these programs, I practiced:

Bash scripting fundamentals

User input handling

Conditionals and loops

Functions and arrays

Random number generation

Script execution and automation

📘 Context
This repository is part of my FreeCodeCamp learning journey, focused on:

Linux fundamentals

Bash scripting

Understanding how command-line programs work internally

👤 Author
Alejandro Oviedo
📍 Argentina
🎓 FreeCodeCamp, TECLAB, UNER Student
🔐 Web Development and Cybersecurity Learner
