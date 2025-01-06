# React Navigation useNavigation Hook Error

This repository demonstrates a common error encountered when using the `useNavigation` hook in React Navigation:  the error 'Cannot find a navigator above'.  The error occurs when the hook is used outside of a `NavigationContainer` or a screen within a navigator.

## Bug

The `useNavigationError.js` file shows how the error is reproduced.  The `App` component attempts to use `useNavigation` outside of a navigation context, causing the error.

## Solution

The `useNavigationSolution.js` file demonstrates the correct way to use `useNavigation`, ensuring it's within a valid navigation container.