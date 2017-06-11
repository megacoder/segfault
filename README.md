# SEGFAULT

## What

Compiling a gcc(1) program to intentionally cause a segmentation fault (SIGSEGV) is surprisingly hard.  The problem is the gcc(1) optimizer passes do too good a job of dead code removal and expression evaluation.

## How

    $ segfault

