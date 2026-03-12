# C Lab: Lists and Stacks

## Project Overview

A C programming lab exercise focused on implementing data structures — specifically a linked list (ArrayList) and a stack. Students complete exercises in `exercises.c` only.

## Project Structure

- `exercises.c` — Student work file (the only file students should modify)
- `test.c` — Test suite (includes `exercises.c` and `arraylist.c`)
- `arraylist.c` / `arraylist.h` — ArrayList (linked list) implementation
- `stack.h` — Stack interface (implemented via ArrayList)
- `test.sh` — Test runner script: compiles with gcc, runs tests, logs results

## Build System

- Language: C
- Compiler: gcc (GCC 14.3.0)
- Build command: `gcc -g test.c -Wall -Werror -o a.out`
- Test runner: `bash test.sh`

## Workflow

- **Start application**: `bash test.sh` (console output)
  - Compiles and runs tests, showing pass/fail results
  - Logs results to `log` file and commits to git

## Important Notes

- Students must only modify `exercises.c`
- `test.c` and `log` are reset by `test.sh` via git
- No frontend or web server — pure C terminal project
