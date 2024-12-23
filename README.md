# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React applications: creating an infinite loop within the `useEffect` hook.  The `useEffect` hook is designed to perform side effects after rendering, but if it modifies state in a way that triggers another render, an infinite loop can occur.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the error in the browser's console and the infinite rendering in the UI.

## Solution

The solution involves correctly managing dependencies in the `useEffect` hook. See the `bugSolution.js` file for the corrected code.