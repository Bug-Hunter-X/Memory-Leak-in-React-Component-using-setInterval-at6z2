# React setInterval Memory Leak
This repository demonstrates a common error in React applications: using `setInterval` within a `useEffect` hook without proper cleanup.  This leads to memory leaks as the interval continues to run even after the component unmounts.

The `bug.js` file shows the incorrect implementation. The `bugSolution.js` file provides the corrected code.