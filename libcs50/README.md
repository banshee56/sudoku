# CS50 Tiny Search Engine (TSE) utility library

These modules support the TSE project.  Feel free to drop in your implementation of the data-structure modules, but **do not change any of the other source files in this directory.**

## Usage

To build `libcs50.a`, run `make`. 
The starter kit includes a pre-built library, `libcs50-given.a`, in case you prefer to use our Lab3 solutions rather than your own.

If you prefer our data-structure implementation over your own, modify the Makefile to replace the rule for `$(LIB)`:

```
$(LIB): libcs50-given.a
	cp libcs50-given.a $(LIB)
```
Notice that command just copies the relevant pre-compiled library to `libcs50.a`.

To clean up, run `make clean`.

## Overview

 * [`file`](file.md) - functions to read files (includes readlinep)