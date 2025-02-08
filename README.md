# React Router Dom v6 Nested Route Issue

This repository demonstrates a common issue encountered when using nested routes in React Router Dom v6.  The catch-all route (`/*`) unexpectedly overrides other routes, preventing correct rendering of nested components.  The `bug.js` file shows the problem, while `bugSolution.js` presents the solution.

## Problem
Nested routes are not working as expected. The catch-all route always takes precedence.