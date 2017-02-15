# DOWHILE

Evaluates code while there's `1` on top of the stack 

Input stack: `code`

Output stack: 

## Allocation

Runtime allocation for code generation

## Errors

EmptyStack error if there are less than one item on the stack

InvalidValue error if the value being checked for truth is not a boolean.

## Examples

```
1 2 3 [1 EQUAL? NOT] DOWHILE =>
```

## Tests

```
1 2 3 [1 EQUAL? NOT] DOWHILE =>
```