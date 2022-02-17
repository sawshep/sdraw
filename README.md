# sdraw

**Please contact me if you are the copyright holder of this
program and would like this repository to be taken down.**

From the book "Common Lisp:  A Gentle Introduction to
Symbolic Computation" by David S. Touretzky.  

The Benjamin/Cummings Publishing Co., 1990.

This is the generic version; it will work in any legal
Common Lisp.

Revised to include support for circular structures.

Revised again, August, 2003, to work with ANSI Common Lisp
and Allegro v6.

User-level routines:
```lisp
(sdraw obj)  ; draws obj on the display
(sdraw-loop) ; puts the user in a read-eval-draw loop
(scrawl obj) ; interactively crawl around obj
```

Variables:
```lisp
*sdraw-print-circle*  ; If bound, overrides *print-circle*.
*sdraw-leading-arrow* ; Initially nil. Set to t to get leading arrows.
```
