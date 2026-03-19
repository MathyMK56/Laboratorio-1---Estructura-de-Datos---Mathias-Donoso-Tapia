# C Lab - List and Stack ADTs

## Overview
This is a C programming laboratory focused on implementing functions using List and Stack Abstract Data Types (ADTs). Students implement specific functions in `exercises.c` and run tests via `test.sh`.

## Project Structure
- `exercises.c` — Student implementation file (functions to complete)
- `arraylist.c` / `arraylist.h` — List ADT implementation
- `stack.h` — Stack ADT (wrapper over the list)
- `test.c` — Test suite (includes `exercises.c` directly)
- `test.sh` — Build + test runner script (compiles with gcc, runs tests, optionally pushes to GitHub)
- `log` — Compilation and test score log

## Build
```bash
gcc -g test.c -Wall -Werror -o a.out
```

## Running Tests
```bash
bash test.sh
```

## Workflow
- **Start application**: runs `bash test.sh` (console output)

## Exercises
1. `crea_lista()` — Create a list with integers 1–10
2. `sumaLista(List *L)` — Sum elements of a list
3. `eliminaElementos(List *L, int elem)` — Remove all occurrences of an element
4. `copia_pila(Stack *P1, Stack *P2)` — Copy stack P1 into P2 preserving order
5. `parentesisBalanceados(char *cadena)` — Check balanced parentheses using a stack
