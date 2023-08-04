---
title: STOR 612
---

## Overview

This course is designed to introduce the foundations of optimization to graduate students at UNC-Chapel Hill, especially to students at the STOR department. It aims at conveying the most common theoretical elements and methods for graduate students who pursue research and career in different disciplines such as operations research, statistics, machine learning, computer science, engineering, applied math, and data science. The course covers both classical and modern topics from the basic to advanced theory and numerical methods. It starts from common mathematical models: linear programming and quadratic programming and moves to unconstrained convex minimization, nonconvex optimization, and then stochastic optimization. As usual, the background theory of convex optimization is convex sets, convex functions, and theory of polyhedra, which will be formally introduced in this course. Simplex methods, gradient descent algorithms, and Newton schemes that form the foundations of numerical optimization will also be presented in this course. Common models such as LASSO, logistic regression, portfolio optimization, and empirical risk minimization will be used as representative examples during the course. Recent advanced methods such as fast gradient, proximal-based, and stochastic gradient algorithms with variance reduction and adaptive learning rates will be discussed. In addition to theory and algorithms, common optimization modeling software and computer solvers will also be introduced to students.

## Prerequisites

This course requires basic background on numerical linear algebra and some parts of multivariable calculus such as basic topology (e.g., open, closed sets, limits, continuity, derivatives, etc.), gradients, and Hessian of multivariable functions. Students are recommended to take MATH547/MATH577 or an equivalent (e.g., STOR 415) prior to taking this course.

## Course Outline

1. Mathematical Optimization Models
 * Mathematical optimization - Examples and basic concepts: decision variables, objective, constraints, feasible solutions, feasible set, optimal value, and optimal solutions, etc.
 * Linear programming (LP) - Representative examples (old and new): production planning, blending, network flows, transportation, optimal transport, least absolute deviations (LAD), Wasserstein barycenter, etc (if time permits).
 * Forms of LPs and preprocessing (converting to standard form, solution construction, redundancy, etc)
2. Mathematical Tools from Convex Analysis
 * Convex sets, convex hulls, polyhedra, and convex cones: definitions, examples, and basic properties
 * Convex functions: definitions, examples, and basic properties
 * Smooth convex functions and strongly convex functions
 * Geometry of polyhedra and solution structures of LPs: basic feasible solutions, optimal solutions, and existence of solutions
3. Linear Programming (LP)
 * Mathematical aspects of simplex methods: matrix form, tableau form, and examples
 * Two-phase simplex methods and complexity
 * Applications and software for LPs: modeling software and LP solvers
 * Dual problem of LP and its construction, and weak duality
 * Strong duality, complementarity slackness, and Farkas’ lemma
 * Sensitivity analysis and robust LPs (if time permits)
4. Quadratic Programming
 * Mathematical formulations of convex QPs and examples (e.g., SVM, linear optimal control, and portfolio optimization)
 * Simple QPs (e.g., least-squares and QPs with equality constraints) and constrained QPs, KKT conditions, and duality
 * Solution methods for QPs: projected gradient, and active-set methods
 * Introduction to interior-point algorithms.
5. General Nonlinear Optimization (NLP)
 * Mathematical models and composite problems, representative examples (Empirical risk minimization, LASSO, logistic regression, nonnegative matrix factorization, etc).
 * Subdifferentials, normal cone, optimality condition, proximal operators, and projection
 * The gradient descent method, its variants, and convergence analysis
 * The accelerated gradient descent method and its variants
 * Proximal/projection operator calculations; proximal gradient methods; and accelerated proximal gradient methods
 * Other advanced optimization methods: mirror descent, coordinate descent, and conditional gradient methods (backup, if time permits)
 * Implementation aspects: per-iteration complexity analysis, line-search, and specialization, etc (homework, tutorials, or recitations).
 * Newton methods, convergence analysis, and implementation (if time permits)
 * Quasi-Newton methods and BFGS updates (if time permits)
8. Stochastic Optimization
 * Introduction to stochastic optimization and examples
 * Stochastic gradient (SGD) methods, convergence, and complexity theory
 * Stochastic gradient methods with variance reduction and adaptive LR (if time permits)

## Syllabus

The syllabus has yet to be finalized. Once it is, you can find it [here](/syllabus.pdf). Course material will be updated throughout the semester on [Canvas](https://edtech.unc.edu/service/canvas/).
