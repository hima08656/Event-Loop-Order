# Event Loop Order Demo

This project demonstrates the execution order in JavaScript:
1. Begin
2. End
3. Promise Task
4. Timeout Task

## Explanation
- Synchronous logs run first.
- Promise `.then()` runs next (microtask).
- `setTimeout` runs last (macrotask).
