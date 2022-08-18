# Notes

https://realpython.com/courses/variables-python/

## Variables in Python

- Variable assignments
- Object references
- Object identity
- Variable names
- Reserved keywords

## Variable Assignments

- Standard variable assignment
    - Name variable with assignment of '='
    - Variables are mutable
- Chained assignment
    - Assign variables to the same name
    - n = m = x = y = 400, they all can be called separately and reference same value
- Multiple assignment
    - Can assign more than one value at the same time
    - a, b = 300, 400
    - Amount of variables used left need to be same as values on the left
- Variable types
    - Don't have to be fixed in Python
    - Can check type of variable - type(n)
- Variables in Python reference an object

## Object References

- Everything in Python is an object
- Variables as references
- Orphaned objects
    - References changed based on variable changing value
    - Garbage collection will clean unused variables and values

## Object Value vs Object Identity

- Object value vs object identity
    - Every object in Python has a memory
    - Can type id(n) which tells where Python object lives
- Small integer caching
    - Python caches small integers
    - Anything between -5 and 256
    - Variable will point to same value in memory
- Challenge: Python Pub Quiz
    - pub-quiz.py

## Naming Conventions

- Any length
- Upper and lowercase characters, or mix of two
- Use lowercase with underscore and try to be descriptive
- Can use digits in variable name but not at the beginning
- Can use unicode characters for variable names
- Longer names should use snake case - descriptive names with underscores between words

## PEP 8

- Document where all variable naming conventions are documented for reference
- Python Enhancement Proposal 8 - style guide for naming conventions and other objects in Python

## Reserved Keywords

- Special words
- Syntax error
- Getting help()
    - Type help("keywords") for list of keywords
    - Can type keyword within help - help("False")
    - 35 keywords
    - Can use import keyword, then type keyword.kwlist
    - Ask if something is a keyword (need keyword import module), keyword.iskeyword("False")