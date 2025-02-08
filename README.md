# React Native: Accessing props or state before component mount

This repository demonstrates a common error in React Native: attempting to access component props or state before the component has fully mounted.  This typically results in a `Cannot read properties of undefined` error.

The `bug.js` file shows the erroneous code. The `bugSolution.js` file provides the corrected version.  The solution involves moving the prop and state access into lifecycle methods like `componentDidMount` or using conditional rendering.