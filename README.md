# AoC Lisp Executor

Lisp executor for the [Advent of Code Solver](https://github.com/tcollier/aoc_solver).

## Template Code

```lisp
(load "ext/lisp/executor.lisp")

(defun part1 (input)
  (car input)
)

(defun part2 (input)
  (car (cdr input))
)

(executor (list "Hello" "World!") #'part1 #'part2 *posix-argv*)
```
