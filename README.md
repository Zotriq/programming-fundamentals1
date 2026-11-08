# Programming Fundamentals (C++)

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SFML](https://img.shields.io/badge/SFML-8CC445?style=flat-square&logo=sfml&logoColor=white)

My first-semester C++ coursework: assignments, lab tasks, practice problems and a final project.

## 🐍 Final project: Snake Game

A graphical Snake game built with **SFML**, with a home screen, pause menu, score tracking, sound effects and
background music.
Source: [`Programing  Fundamentals/Final Project (snake game)/Game/Game.cpp`](Programing%20%20Fundamentals/Final%20Project%20(snake%20game)/Game/Game.cpp)

## Contents

| Folder | What's inside |
|---|---|
| `Assignment/` | Graded assignments: prime sums, square roots, factorials, a credit-card validator, shape patterns, games |
| `Labs/` | Weekly lab tasks |
| `Misc/` | Practice problems: spiral matrix, array rotation, `atoi`, longest substring without repeating characters, median of two sorted arrays, Armstrong numbers |
| `Final Project (snake game)/` | SFML Snake game (Visual Studio solution) |

## Running

Any single file:

```bash
g++ "file.cpp" -o program && ./program
```

The Snake game needs [SFML 2](https://www.sfml-dev.org/) and builds from the included Visual Studio solution on Windows.
