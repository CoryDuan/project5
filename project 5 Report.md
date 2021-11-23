# Task Planning Report

> Rui Xiao rx12@rice.edu  Chuyu Duan cd58@rice.edu

### Problem Statement and Motivation
For this project we are doing 5.6 Task Planning, that is to design an SAT planner to solve the "Sokoban on Ice" problem. By solving this problem we will understand how to solve robotics problems using task planning, to model the problem into a task planning problem, and finding the optimal methods to solves these problems. Since task planning problems play a important role in industry world, and efficient task planning methods are the key to saving resources as well as increasing efficiency,
### Explanation of Approach

#### How

#### Why

#### Optimization

reduce number of variables

#### BFS
Both python and c++ version of the BFS algorithm are implemented.
For the unmovable python algorithm, the average runtime is around 0.036s. For the movable python algorithm, the average runtime is around 0.05s. While the BFS algorithm generally runs faster than our SAT algorithm, and that the unmovable python algorithm provides 100% correct solution, it should be noted that the movable python algorithm works fine with scene 1 but fails to find the solution for scene 2. That is because an optimal algorithm will decide to not push the movable obstacle on [1,4] while the BFS algorithm doesn't hesitate to do so. A better algorithm is needed to fix this problem.

### Description of Experiments

#### Robot

In the experiment we designed, the robot is tasked with reaching a target cell in the grid world. It can move in any of the four cardinal directions (up, down, left, right). When it starts moving, it can not stop until it hits a static obstacle or the workspace boundary.

#### Environment

#### Potential Solution

假定XX步内有可行解

#### Runtime Platform

运行环境

### Analysis

#### Example

#### Benchmark

Time, Memory(State Number, State Size), Failure, Stability(time)

#### Optimality

#### Completeness

#### Comparison with BFS

### Difficulties of Exercises
