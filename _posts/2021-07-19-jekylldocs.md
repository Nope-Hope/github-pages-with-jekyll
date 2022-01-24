---
layout: post
title: "Introduction to gdb and ddd"
date: 2020-07-19
---

###Introduction to gdb and ddd
The purpose of a debugger is to allow you to see what is going on inside your C program while it runs. In addition, you can use gdb to see what your program was doing at the moment it crashed.
Here are some of the usful actions that gdb can perform:

Start your program and step through it line by line
Make your program stop on specified conditions
Show the values of variables used by your program
Examine the contents of any frame on the call stack
Set breakpoints that will stop your program when it reaches a certain point. Then you can step through part of the execution using step and next, and type continue to resume regular execution.
For C and C++ programs, gdb and ddd are debuggers that you can use. ddd is a easy-to-use GUI wrapper around an inferior debugger (gdb for GNU compiled C or C++ code). ddd allows you to interact with the debugger by using either GUI menu options or the under-lying debugger's command line interface. In addition, ddd automatically displays source code when breakpoints are reached.

There are some example programs and some documentation on using gdb to debug them that you can copy from here: /home/newhall/public/gdb_examples/

