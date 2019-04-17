# LispEvaluatorFlexAndBison
Lisp evaluator for addition and multiplication implemented using Flex and Bison

Invoke the makefile to compile

### Prerequisites

You must have Flex and Bison installed on your Unix system. 

### Instructions

```
make -B
```

Run the C file

```
./sexp
```

Enjoy performing Lisp additions and multiplications!

### Usage

Example 1:

```
> (+ 1 2 3)
```

Will output

```
6
```

Example 2:

```
> (+ 1 (* 1 2 3) 3)
```

Will output

```
10
```
