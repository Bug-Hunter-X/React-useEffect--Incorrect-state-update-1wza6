# React useEffect: Incorrect State Update

This repository demonstrates a common error in React's `useEffect` hook where the state variable is directly modified, causing unexpected behavior.  The code attempts to increment the `count` state within the `useEffect` hook but fails to trigger a re-render because it doesn't use the `setCount` function.