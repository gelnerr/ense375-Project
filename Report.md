# 💣 MineSweeper CLI - Report

## 1. Introduction
This project focuses on the development of a command-line Minesweeper application designed to apply structured software engineering and testing principles. The system is implemented using test-driven development and follows the Model–View–Controller architecture to ensure testability. Minesweeper was selected due to its clear rules and state-based logic, making it suitable for verification. The following sections will describe the design constraints, development process, implementation approach, and testing strategy used in this project.

## 2. Design Problem
### 2.1 Problem Definition
The objective of this project is to design and implement a command-line version of **MineSweeper**. It aims to successfully test and validate all core mechanics of the game. The project will correctly handle grid generation, random mine placements, user inputs and state transitions in a deterministic manner. It will prioritize the use of the MVC architecture, separating code cleanly making debugging and editing simpler and straightforward. The end product will focus more on reliability and sustainability more than graphical complexity.

### 2.2 Design Requirements
#### 2.2.1 Functions
* Displaying an m x n minefield grid.
* Select a spot on the grid.
* Display numbers based on how many mines surround a particular spot.
* Detect and switch to Win / Playing / Loss states. 

#### 2.2.2 Objectives
* Maintain clear adherence to the Model View Controller (MVC) architecture
* Support TDD - Test Driven Development and well-defined test cases.
* Provide a simple and easy to navigate interface for the game.

#### 2.2.3 Constraints
| Constraint | Satisfiable? |
|-----------------------------|----------|
| Needs to operate exclusively on the command line | Yes |
| Should use Model-View-Controller architecture | Yes |
| Include automated **unit** testing using JUnit | Yes |
| Produce deterministic game behavior and results | Yes |
| Fully executable on a standard Java environment | Yes |

## Team Members

| Name | Student ID |
|-----------------------------|----------|
| Glen Issac | 200499313 |
| Shivam Jigneshbhai Soni | 200474721 |
| Luka Dundjerovic | 200494589 |
