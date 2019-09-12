# Hello, World!

## Story

Welcome to Codecool! No question that your first programming exercise must be a [Hello, World!](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) implementation.

## What you gonna learn?

You have to use functions, parameters, call your function with arguments, and also be able to run your script from command line with arguments!

## Tasks

1. Implement the `hello_world()` function which returns “Hello, World!”
2. Create and implement the parametrized function `hello(name)` with one string input which returns `"Hello, <name>!"`
3. Create and implement the `print_hello(name)` function which prints the result of `hello(name)`!
4. Implement the main (outside any functions) part of `hello.py` so that it prints the result of `hello(name)` when called from the command line by `python3 hello.py <name>`
5. Implement the main (outside any functions) part of `hello.py` so that it prints the result of `hello(name)` when called from the command line with multiple arguments by `python3 hello.py <name1> <name2> <name3>`. The required result is `"Hello, <name1> <name2> <name3>!"`

## Requirements

- [1.1] MANDATORY! The returned string of the function is exactly "Hello, World!"
- [1.2] Function `hello_world()` does not print itself.
- [2.1] For any non-empty String return `"Hello, <name>!"`
- [2.2] If `name` is empty or None, return `"Hello, World!"`
- [2.3] Function `hello(name)` does not print itself
- [3.1] Calling `print_hello(name)` prints `"Hello, <name>!"`
- [3.2] Function `print_hello()` calls `hello()` and uses its return value
- [4.1] Calling from the command line with one argument prints `"Hello, <name>!"` to the console
- [4.2] The command line call uses `hello(name)`'s return value
- [5.1] Calling from the command line with multiple argument prints `"Hello, <name1> <name2> <name3>!"` to the console
- [5.2] The command line call uses `hello(name)`'s return value
- [5.3] It works for any number of arguments

## Preparations

Have an installed a Python 3 environment, and an editor to write code!

## Background materials

- [Installing VS Code editor](https://learn.code.cool/progbasics/#/../pages/tools/vs-code)
- [Introduction to Python](https://learn.code.cool/progbasics/#/../pages/python/introduction-to-the-python-language)
- [Python basics](https://learn.code.cool/progbasics/#/../pages/python/python-basics-variables-conditions-loops-lists-strings-functions-user-interactions-file-handling)
- [Command line arguments in Python](https://appdividend.com/2019/01/22/python-sys-argv-tutorial-command-line-arguments-example/)
