# Bash Programs – FreeCodeCamp

Bash scripts created as part of the freeCodeCamp Bash/Linux curriculum. Each script
practices core shell scripting concepts — variables, conditionals, loops, functions,
arrays, random numbers, and user input — in a real Linux environment.

## Scripts Included

### `questionnaire.sh`
Asks the user a series of questions and prints a personalized message.
**Concepts**: variables, `read` for user input, `echo` formatting.

### `countdown.sh`
Counts down to zero from a positive integer passed as a command-line argument.
**Concepts**: positional parameters (`$1`), `if`, `while`, arithmetic, `sleep`.

### `bingo.sh`
Generates a random Bingo number (1–75) and assigns the correct letter (B, I, N, G, O).
**Concepts**: `$RANDOM`, arithmetic evaluation `(( ))`, `if`/`elif`.

### `fortune.sh`
A fortune teller that answers a yes/no question, validating it ends with a question mark.
**Concepts**: arrays, functions, regular expressions, input validation, `until` loop.

### `five.sh`
Runs the other four scripts in sequence.
**Concepts**: script execution, basic automation, orchestration.

### `castle.sh`
A beginner script built entirely with the Nano text editor.
**Concepts**: creating/editing files in Nano, saving/exiting, handling stopped processes (`Ctrl+Z`, `fg`).

## Tech Stack

- Bash / shell scripting
- Linux terminal, GNU utilities

## How to Run

```bash
git clone https://github.com/aleoviedo071298/fcc-bash-learning.git
chmod +x *.sh

./questionnaire.sh
./countdown.sh 5
./bingo.sh
./fortune.sh

# or run all at once
./five.sh
```

## Learning Objectives

Bash scripting fundamentals, user input handling, conditionals and loops, functions
and arrays, random number generation, script execution and automation.

## Author

**Alejandro Oviedo**
Argentina — freeCodeCamp / Teclab / UNER student
