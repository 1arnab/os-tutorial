os-tutorial
===========

How to create an OS from scratch!

**New lessons will be added about every week, at the same pace that I learn each concept**

I have always wanted to learn how to make an OS from scratch. In college I was taught
how to implement advanced features (pagination, semaphores, memory management, etc)
but:

- I never got to start from my own boot sector
- College is hard so I don't remember most of it.
- I'm fed up with people who think that reading an already existing kernel, even if small, is 
a good idea to learn operating systems.

Inspired by [this document](http://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)
and the [OSDev wiki](http://wiki.osdev.org/), I'll try to make short step-by-step READMEs and
code samples for anybody to follow. Honestly, this tutorial is basically the first document but
split into smaller pieces and without the theory.


Features
--------

- This course is a code tutorial aimed at people who are comfortable with low level computing. For example,
programmers who have curiosity on how an OS works but don't have the time or willpower to start reading the Linux kernel
top to bottom.
- There is little theory. Yes, this is a feature. Google is your theory lecturer. Once you pass college, 
excessive theory is worse than no theory because it makes things seem more difficult than they really are.
- The lessons are tiny and may take 5-15 minutes to complete. Trust me and trust yourself. You can do it!


How to use this tutorial
------------------------

1. Start with the first folder and go down in order. They build on previous code, so if 
you jump right to folder 05 and don't know why there is a `mov ah, 0x0e`, it's because you missed lecture 02.
Really, just go in order. You can always skip stuff you already know.

2. Read each README first. Especially the first line, which details the concepts you should be familiar with
before reading the code.

3. Read the README. It is **very concise**. The only theory is the required to understand the code and there
are tips on what to look at when you open the code file(s)

4. Look at the code examples. Some times you may be able to write them yourself just from the hints on the README.

5. Experiment with them and try to break things. Try to change pointers and registers and see what happens. You know, the usual.


TL;DR: First read the README on each folder, then decide if you will
implement it yourself or just read the provided code files.


Contributing
------------

I'm still learning this. For the moment, please restrict your contributions to fixing possible bugs
or improving existing documents. I'm not yet ready to accept enhancements.
