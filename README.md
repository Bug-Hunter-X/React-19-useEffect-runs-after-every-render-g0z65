# React 19 useEffect Bug: Missing Dependency

This repository demonstrates a common error in React 19 involving the `useEffect` hook.  The issue arises when a dependency is missing from the `useEffect` hook's dependency array, causing it to run on every render instead of only when a specified dependency changes.

The `bug.js` file contains the buggy code. The `bugSolution.js` demonstrates the correct implementation.

## Bug Description
The `useEffect` hook, without the correct dependencies listed in the array, will cause a re-render on every render cycle.  This can lead to unexpected behavior and performance problems, particularly in complex applications.