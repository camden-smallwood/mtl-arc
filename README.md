mtl-arc
=======
A new implementation of the Arc language

This is a major work in progress, and will change quite often. 
The core is a bare-minimum C interpreter designed for building Arc on top of. 
It currently consists of just over 550 lines of code. 
My goal is to maintain the simplicity, readability and speed of the core, while defining as much of Arc in Arc itself as possible (like macros). 
There is currently no garbage collection; I'm looking over what I consider 'options'.

Features:
=========
* Double-precision floating-point numbers, strings, characters, tables...
* Implicit string indexing
* Implicit table referencing
* Builtin "place" assignments (table & conses)
* TBD...

Special Forms:
==============
```quote, quasiquote, unquote, unquote-expand, assign, if, while, fn```

Builtin Functions:
==================
```is, type, table, annotate, +, -, *, /, <, pr, cons, car, cdr```

Defined Functions:
==================
``` list, ```