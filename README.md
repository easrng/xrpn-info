# xrpn-info
Docs for XRPN (eXtended Reverse Polish Notation)

## Synatx
One statement per line.
Ex:
```
2
2
+
o
```
All numbers are pushed to stack
Everything else is a command.
It's just RPN.
## Commands
### Logic (`<`, `>`, `=`)
Pops 2 from stack, compares, and pushes 1 for true, 0 for false.
### Math (`+`, `-`, `/`, `*`, `%`)
Pops 2 from stack, does operation, and pushes the result.
### `g`
Pops 1 from stack and goes to that location in the program.
### `i`
Pops 2 from stack and goes to that location in the program specified by 2nd one if 1st one is true.
### `o`
Pops one and outputs it.
### `w`
Pops one and waits the number of senconds specified.
### `d`
Pops one, then pushes it back on twice.
### `p`
Pops one, and deletes.
## How to run?
See [implementations](implementations.md).
