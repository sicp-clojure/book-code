# sicp-clojure

This repository contain the course code for the book "Structure and Interpretation of Computer Programs" by Abelson, Sussman, and Sussman.

This code is identical to the official MIT course code, with the exception of it being modified from the original MIT Scheme to Clojure (v 1.8).

This is an early work in progress.

## Installation and execution

The code is based on a leinengen project and dependencies can be downloaded by cloning the repo and using leinengen to pull down the dependencies:
```
$ lein deps
```

I have been using Atom with proto-repl as a development environment, and there is a dependency for this in the project file, which can be removed if not required.

## Code Structure

### Chapter 1

ch1.scm	Complete chapter 1 code

### Chapter 2

ch2.scm	Complete chapter 2 code
ch2support.scm	Extra code required to run chapter 2 material
ch2tests.scm	Tests of programs from 2.4 and 2.5

### Chapter 3

ch3.scm	Complete chapter 3 code
ch3support.scm	Extra code required to run chapter 3 material

### Chapter 4

ch4.scm	Complete chapter 4 code
ch4-mceval.scm	Metacircular Evaluator (sections 4.1.1-4.1.4)
ch4-analyzingmceval.scm	Analyzing Evaluator (section 4.1.7)
ch4-leval.scm	Lazy Evaluator (section 4.2)
ch4-ambeval.scm	Amb Evaluator (section 4.3)
ch4-query.scm	Query Evaluator (section 4.4.4)

### Chapter 5

ch5.scm	Complete chapter 5 code
ch5-regsim.scm	Register-Machine Simulator (section 5.2)
ch5-eceval.scm	Explicit-Control Evaluator (section 5.4)
ch5-eceval-support.scm	Support for Explicit-Control Evaluator machine operations
load-eceval.scm	Loader for Explicit-Control Evaluator Files
ch5-syntax.scm	Syntax procedures (used by ec-eval and by compiler)
ch5-compiler.scm	Compiler (section 5.5)
ch5-eceval-compiler.scm	Explicit-Control Evaluator, interfaced to compiled code (section 5.5.7)
load-eceval-compiler.scm	Loader for Explicit-Control Evaluator with compiled code interface


## License

All source files in this repository are licensed under Creative Commons Attribution-ShareAlike 4.0 International License (cc by-sa).
