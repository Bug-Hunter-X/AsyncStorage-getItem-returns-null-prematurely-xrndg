# React Native AsyncStorage Premature null Return

This repository demonstrates a common error when using AsyncStorage in React Native:  `getItem` returning `null` before the asynchronous `setItem` operation completes.  The `bug.js` file shows the problematic code, resulting in `null` being logged.  The solution in `bugSolution.js` uses `await` correctly to ensure data is stored before retrieval.