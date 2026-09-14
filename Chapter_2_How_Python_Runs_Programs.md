# Chapter 2

## How Python Runs Programs

### Notes

>Python uses what's called an interpreter to run programs. It is necessary to take the text of the code and interpret its function. From the programmer's view it takes that code of statements and performs the function that was written. In the example of printing text, it will print what is typed. If it needs to make a calculation that is also done with the interpreter. Many lines of text can be coded that when combined, they are considered a script that can be executed. The interpreter is the vehicle for that execution.
>Python will compile the code and then provide that bytecode to the system. Your code is the source code and the bytecode is saved in a directory called __pycache__. The reasons for saving here is to be able to skip the start-up of compiling if the bytecode is present.
>Python adds version numbering to the bytecode. This is used to know when to recompile the code.
>The Python virtual machine is the code being looped through each instruction. It runs the scripts and is the last step of the interpreter.
>Development implications are that there are no distinction between the development or execution environments. The compiler is always present at runtime.
>Execution model variations. It appears that there are many Python implementation alternatives. They are feature rich and specific to what needs accomplished. There are C, .NET, Java, numeric and hybrid models.

---
---

### Synopsis

>What is important to know is that Python is at a ready state to be run. Regardless of the execution model being used the code will iterate line by line and execute accordingly.
