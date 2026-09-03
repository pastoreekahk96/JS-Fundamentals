# JavaScript Fundamentals

A collection of introductory JavaScript exercises covering variables, command-line arguments, conditionals, arrays, loops, functions, and number conversion.

These exercises are intentionally kept as coursework-style programs so the repository shows the learning progression rather than hiding it behind a large framework.

## Exercises

| File | Concept |
|---|---|
| `0-javascript_is_amazing.js` | Constants and console output |
| `1-multi_languages.js` | Variables and multiple outputs |
| `2-arguments.js` | Command-line argument counting |
| `3-value_argument.js` | Reading command-line arguments |
| `4-concat.js` | Combining argument values with a template literal |
| `5-to_integer.js` | Integer conversion and validation |
| `6-multi_languages_loop.js` | Arrays and `for` loops |
| `7-multi_c.js` | Repetition with a loop |
| `8-square.js` | Nested loops and string building |
| `9-add.js` | Functions and numeric addition |

## Requirements

- Node.js
- A terminal or command prompt

No third-party npm packages are required for the current exercises.

## Run an exercise

From the repository root:

```bash
node 0-javascript_is_amazing.js
node 2-arguments.js
node 5-to_integer.js 89
node 7-multi_c.js 3
node 8-square.js 4
node 9-add.js 10 20
```

The programs use `process.argv` to read command-line arguments. Each exercise can therefore be run independently with Node.js.

## Learning focus

The goal is to understand how a program receives input, makes decisions, processes data, and produces output. The exercises provide a foundation for later JavaScript work involving objects, asynchronous programming, APIs, and backend development.

## Repository hygiene

This repository contains small standalone exercises, so a package manager or build system is intentionally not required. Local dependency directories, environment files, logs, coverage output, and editor metadata should not be committed.
