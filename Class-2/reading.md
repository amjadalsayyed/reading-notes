# Class-2 Reading Notes

## If name equals main

> - this is one of the most important topic in python as it give us the abilty to identfy which module is the main one or which module is the scripte is runing mainly so if we run app.py by typing python app.py in trminal we would have app.py as the main module and any module impotrted inside it would be executed as a secondry module

## In Tests We Trust - TDD with Python

> - The post is a gentle introduction to Test-Driven Development (TDD) with Python. It explains that TDD is a strategy to think and write tests first and gives an example of how to apply TDD in a project that requires identifying the gender of a person based on their name using an external API.
> - The post emphasizes the importance of writing descriptive test names, following the AAA (Arrange, Act, Assert) convention, and organizing the test files separately from the production code. It also introduces the TDD cycle, which consists of writing a failing test, implementing the feature to make the test pass, and then refactoring the code.
> - Overall, the post encourages developers to embrace TDD and shows how it can lead to more robust and maintainable code.

### Takeaways

- The greatest advantage about TDD is to craft the software design first
- Your code will be more reliable: after a change you can run your tests and be in peace
- Beginning may be hard — and that’s fine. You just need to practice!

## Recursive

> - A recursive function is a function that calls itself during its execution. The function will keep calling itself and passing a modified input value until it reaches a base case, which is a condition that will cause the function to stop calling itself and return a value. Recursive functions can be used to solve problems that can be divided into smaller subproblems of the same type, and where the solution to the overall problem can be obtained by combining the solutions of the smaller subproblems. Some examples of problems that can be solved with recursive functions are computing factorials, computing Fibonacci numbers, and traversing tree data structures. However, it's important to be careful when using recursive functions, since they can lead to infinite loops or excessive memory usage if not implemented correctly beecuse its time complexty is O(2^n).
