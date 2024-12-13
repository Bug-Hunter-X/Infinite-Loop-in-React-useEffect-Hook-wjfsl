# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React's `useEffect` hook: an infinite loop caused by a missing dependency array. The `useEffect` hook is used to perform side effects after a component renders. When the dependency array is omitted or incorrectly specified, the effect function executes on every render, which can lead to infinite re-renders and crashes.