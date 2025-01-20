# RetroASM

This is a modern recreation of Ken Thompson's journey of creating UNIX,
divided in three steps:

1. Creation of a text editor
2. Creation of a programming language
3. Creation of a kernel (operating system)

Originally Ken Thompson completed these steps in three weeks, but we are not
Ken Thompson.

## The Text Editor

It has to be written in assembly and it will only support x86_64 processors
and for simplicity purposes it will support only POSIX compliant operating
systems.

It should allow the user to:
- Move around
- Insert text
- Save file
- Exit

## The Programming Language

It will have to be written in the text editor created above, there will probably
be more and it will have to start with assembly and build from there on probably
from Assembly to Forth to a C like programming language.

In the end the programming language should have:
- Basic data types (`int`, `char`, etc.)
- Arrays
- Structs
- Pointers
- Control flow (`if`, `else`, `while`, maybe `for`)
- A module system (As of now I don't know what would be a simple
enough module system but I would like something that doesn't need header files)


## The Kernel (OS)
I will use [this](https://operating-system-in-1000-lines.vercel.app/) as
a reference and it needs to be written using the programming language from
above in the editor created by us.

So it will implement:
- Multitasking
- Exception handler
- Paging
- System calls
- Device drivers
- File system
- Command-line shell
