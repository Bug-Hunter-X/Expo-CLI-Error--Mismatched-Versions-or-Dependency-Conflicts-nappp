# Expo CLI Error: Version Mismatch or Dependency Conflicts

This repository demonstrates a common error encountered when using the Expo CLI: version mismatches or dependency conflicts that lead to unexpected build or runtime errors.

The `bug.js` file showcases a project with potentially conflicting dependencies. The `bugSolution.js` file presents a solution to resolve these conflicts.

## Reproduction Steps

1. Clone this repository.
2. Navigate to the project directory.
3. Attempt to run the Expo CLI commands (e.g., `expo start`). Observe the error(s).
4. Refer to `bugSolution.js` for a step-by-step guide on resolving the issue.

## Solution

The key is to ensure that all the dependencies in your `package.json` file are compatible with your current Expo CLI version and with each other.  This may involve updating packages, downgrading packages, or carefully resolving peer dependency conflicts using tools like `npm-check-updates` or yarn.