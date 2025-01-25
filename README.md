# Expo Managed Workflow Incompatibility Error

This repository demonstrates a common error encountered in Expo's managed workflow.  It occurs when attempting to use a library or feature incompatible with the managed workflow environment.  The example shows a scenario where using a hypothetical library requiring native modules fails.

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies: `npm install`
3. Run the app: `expo start`

You should observe a runtime error indicating incompatibility with the Expo managed workflow.  The `bugSolution.js` file demonstrates how to resolve this by either choosing an alternative library or switching to an Expo-compatible approach (if available).