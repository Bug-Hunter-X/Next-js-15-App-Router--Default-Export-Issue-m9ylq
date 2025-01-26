# Next.js 15 App Router Default Export Issue

This repository demonstrates an unexpected behavior encountered when using a default export in a page component within Next.js 15's app directory.

## Bug Description

When using a default export in a page component, Next.js 15 might exhibit unusual behavior or errors.  The specific issue is detailed in `bug.js`. 

## Solution

The recommended approach is outlined in `bugSolution.js` and involves using a named export instead of a default export for page components in the app directory. This change ensures compatibility and expected functionality.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe the unexpected behavior or errors in the browser. 
5. Compare the original file (`bug.js`) with the updated file (`bugSolution.js`) to see the resolution.
