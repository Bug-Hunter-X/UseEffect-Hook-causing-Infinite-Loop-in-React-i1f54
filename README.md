# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug involving the `useEffect` hook. The provided `MyComponent` initially has an infinite loop in the `useEffect` hook because it is missing a dependency array. The solution provides a corrected `useEffect` hook with the correct dependency array to fix this issue.