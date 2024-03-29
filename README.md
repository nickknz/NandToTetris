# NandToTetris
This is a project building the whole computer from logic gate to tetris 

## Project Description
### Project3
Having built the computer's ALU, this module we turn to building the computer's main memory unit, also known as Random Access Memory, or RAM. This will be done gradually, going bottom-up from elementary flip-flop gates to one-bit registers to n-bit registers to a family of RAM chips. Unlike the computer's processing chips, which are based on combinational logic, the computer's memory logic requires a clock-based sequential logic. 

### Project4
A critically important aspect of building a new computer system is designing the low-level machine language, or instruction set, with which the computer can be instructed to do various things. As it turns out, this can be done before the computer itself is actually built. For example, we can write a Java program that emulates the yet-to-be-built computer, and then use it to emulate the execution of programs written in the new machine language. Such experiments can give us a good appreciation of the bare bone "look and feel" of the new computer, and lead to decisions that may well change and improve both the hardware and the language designs. Taking a similar approach, in this module we assume that the Hack computer and machine language have been built, and write some low-level programs using the Hack machine language. We will then use a supplied CPU Emulator (a computer program) to test and execute our programs. This experience will give you a taste of low-level programming, as well as a solid hands-on overview of the Hack computer platform

### Project 5
Let's recap the last four modules: we've built some elementary logic gates (module 1), and then used them to build an ALU (module 2) and a RAM (module 3). We then played with low-level programming (module 4), assuming that the overall computer is actually available. In this module we assemble all these building blocks into a general-purpose 16-bit computer called Hack. We will start by building the Hack Central Processing Unit (CPU), and we will then integrate the CPU with the RAM, creating a full-blown computer system capable of executing programs written in the Hack machine language.

**Key concepts:** Von Neumann and Harvard architectures, the stored program concept, fetch-execute cycle, data bus, instruction bus, CPU, computer design.

### Project 6
Every computer has a binary machine language, in which instructions are written as series of 0's and 1's, and a symbolic machine language, also known as assembly language, in which instructions are expressed using human-friendly mnemonics. Both languages do exactly the same thing, and are completely equivalent. But, writing programs in assembly is far easier and safer then writing in binary. In order to enjoy this luxury, someone has to translate our symbolic programs into binary code that can execute as-is on the target computer. This translation service is done by an agent called assembler. The assembler can be either a person who carries out the translation manually, or a computer program that automates the process. In this module and final project in the course we learn how to build an assembler. In particular, we'll develop the capability of translating symbolic Hack programs into binary code that can be executed as-is on the Hack platform. Each one of you can choose to accomplish this feat in two different ways: you can either implement an assembler using a high-level language, or you can simulate the assembler's operation using paper and pencil. In both cases we give detailed guidelines about how to carry out your work.

**Key concepts:** Binary and symbolic machine languages, parsing, symbol tables, code generation, cross assembler, assembler implementation.

### Project 7
In some modern languages, most notably Java, the high-level code is not translated directly into machine language. Rather, Java compilers translate the high-level source code into code written in an intermediate language, designed to operate on some abstract processing layer known as a virtual machine.

In this module we begin building a stack-based virtual machine. After presenting the virtual machine architecture and its VM language (which is similar to Java's bytecode), we develop a basic VM translator (similar to Java's JVM), designed to translate VM programs into the Hack machine language. In the next module we'll extend this basic translator into a full-scale VM implementation. This implementation, in turn, will serve as the backend module of the two-tier compiler that we'll develop later in the course.

**Key concepts:** two-tier compilation (overview), virtualization, virtual machines, VM abstraction, stack processing, pointers, VM implementation, VM translators.
<img width="923" alt="image" src="https://github.com/Nick-zhen/NandToTetris/assets/62523802/d9c8244b-c02f-4566-bf15-c60ee4c41ac7">

### Project 8
In this module we'll complete the VM translator by implementing the remaining VM language's branching and function-calling commands.

Branching and function-calling are of course major elements of programming theory and practice. Therefore, we'll start the module with a general overview of their usage, abstraction and implementation. This will set the stage for the remainder of the module, in which we'll complete the specification and implementation of the VM translator.

**Key concepts:** branching, functions, function call-and-return, dynamic memory management, stack processing, pointers, standard mapping, VM implementation.

### Project 9
In this module we introduce the Jack language, as well as Jack programming. The module culminates in a project in which you will develop a simple interactive application of your choice, using Jack.

It's important to note that in and by itself, Jack programming is not an important element of this course. Rather, we want you play with Jack, and experience the language from a programmer's perspective. This familiarity will serve you well when you will set out to develop a Jack compiler and operating system, later in the course.

Key concepts: procedural programming, object-based programming, classes, methods, functions, constructors, list processing, recursion, developing interactive applications, graphics optimization. 

### Project 10


## Project Progress
- [X] Project 1
- [X] Project 2
- [X] Project 3
- [X] Project 4
- [X] Project 5
- [X] Project 6
- [X] Project 7
- [ ] Project 8
- [ ] Project 9
- [ ] Project 10

