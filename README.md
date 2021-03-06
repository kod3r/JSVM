#JSVM

Javascript virtual machine is one instruction set machine to parse and execute an assembly like code. This machine is written to be used by students studying compilers and willing to test and debug generated byte code in a simple manner.

##1. Instruction set

| Instruction | Argument | Description                                    |
| ------------|:--------:| :----------------------------------------------|
| #String:    | -        | Define label                                   |
| PUSH        | #Number  | Push a number to the stack                     |
| POP         | -        | Pop from stack                                 |
| DATA        | #String  | Define variable with name                      |
| STORE       | #String  | Put head in variable                           |
| LOAD        | #String  | Push variable's value to stack                 |
| ADD         | -        | Addition                                       |
| SUB         | -        | Substruction                                   |
| MULT        | -        | Multiplication                                 |
| DIV         | -        | Division                                       |
| MOD         | -        | Remainder                                      |
| AND         | -        | And                                            |
| OR          | -        | Or                                             |
| Not         | -        | Ones' complement                               |
| LT          | -        | Lower than                                     |
| LE          | -        | Lower or equal to                              |
| JMP         | #Label   | Unconditional jump to label                    |
| BEQ         | #Label   | Branch to label if equal                       |
| BNE         | #Label   | Branch to label if not equal                   |
| PRINT       | -        | Print integers in stack as characters until \0 |
| PRINTN      | -        | Print number head of stack                     |
| READ        | -        | Read string and push it to stack               |
| READN       | -        | Read number and push it to stack               |
  

##2. Features

- Drag and drop byte code file
- Step by step execution
- Full code execution
- GUI: Stack, Symbol table and Program counter


##3. Todo

- Tests
- More tests
- Add more instructions
- Better strings support

Enjoy !
