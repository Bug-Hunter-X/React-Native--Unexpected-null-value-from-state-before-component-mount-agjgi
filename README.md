# React Native: Unexpected null value from state before component mount

This repository demonstrates a common React Native bug where attempting to access component state before it's fully mounted results in unexpected `null` values.  The issue is often encountered when dealing with asynchronous operations within lifecycle methods like `componentDidMount`.

The `bug.js` file showcases the problematic code.  The solution, provided in `bugSolution.js`, addresses this by conditionally rendering the component's content only after the state has been properly populated.