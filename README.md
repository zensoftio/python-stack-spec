# Before writing any Python code

## Python Style Guide

[PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008)

## Naming

There is a good article on how to name variable names. [Good variable names](http://wiki.c2.com/?GoodVariableNames)

## Documentation

Write documentation only if you think other developers may have problems with understanding functions, methods, classes, modules or packages.

Do not describe obvious things in documentation like:
```python
#BAD! never do it!

def add(x, y):
    """Returns sum of x and y"""
    return x + y
``` 

Docstring style - [Google Style Python Docstrings](http://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html)

## Commit checklist

* Run Pylint - [Pylint website](https://www.pylint.org/)
* Run tests
