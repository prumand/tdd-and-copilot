# TDD and Co-Pilot, the sweet spot

1. [Introduction](#introduction)
2. [My testing journey](#my-testing-journey)
    1. [Write Code and check manually](#write-code-and-check-manually)
    2. [Write Code and also write tests](#write-code-and-also-write-tests)
    3. [Code tests first and then write code](#code-tests-first-and-then-write-code)
    4. [Red, Green, Refactor](#red-green-refactor)
    5. [Write Specifications and fullfill them](#write-specifications-and-fullfill-them)
3. [Co-Pilot](#co-pilot)
    1. [What is Co-Pilot](#what-is-co-pilot)
    2. [How does Co-Pilot work](#how-does-co-pilot-work)
    3. [What are the strenght of Co-Pilot](#what-are-the-strenght-of-co-pilot)
    4. [What are the weaknesses of Co-Pilot](#what-are-the-weaknesses-of-co-pilot)
4. [Using Co-Pilot to write your tests](#using-co-pilot-to-write-your-tests)
    1. [Establishing context](#establishing-context)
    2. [Write out specifications](#write-out-specifications)
    3. [Write imperative tests](#write-imperative-tests)

## Introduction

Co-Pilot is a tool that uses artificial intelligence to assist developers in writing code. It can suggest code snippets, refactor code, and generate tests based on natural language descriptions. Co-Pilot can work with any programming language and framework, and can integrate with popular code editors. 

# Notes
1. first try writing the introduction, promted vs code
    1. prompted bing to write the introduction
    ```
    [git: 0.0.1]
    TDD and Co-Pilot for a meetup about testing.

    Test-driven development (TDD) is a software development process that involves writing tests before writing code. The idea is to specify the expected behavior and functionality of the code, and then write the code that passes the tests. TDD can help developers write cleaner, more reliable, and more maintainable code.

    Co-Pilot is a tool that uses artificial intelligence to assist developers in writing code. It can suggest code snippets, refactor code, and generate tests based on natural language descriptions. Co-Pilot can work with any programming language and framework, and can integrate with popular code editors.

    In this meetup, we will explore how TDD and Co-Pilot can work together to improve the quality and efficiency of software development. We will see some examples of how Co-Pilot can generate tests based on TDD principles, and how TDD can guide Co-Pilot to produce better code. We will also discuss some of the benefits and challenges of using these tools, and share some tips and best practices for getting the most out of them.
    ```
    2. First paragraph with VS Code and Co-Pilot
