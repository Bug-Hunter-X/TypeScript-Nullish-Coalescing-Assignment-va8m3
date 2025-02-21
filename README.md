# TypeScript Nullish Coalescing Assignment Bug

This repository demonstrates a common TypeScript error related to nullish coalescing assignment and how to resolve it.

## Bug Description

The `printName` function attempts to call `toUpperCase()` on a string that might be `null`. This causes a TypeScript error: `Object is possibly 'null'.`

## Solution

The solution involves adding null check before using toUpperCase().