# Expo CLI `expo prebuild` Failure on Windows

This repository demonstrates a bug encountered when using the `expo prebuild` command within the Expo CLI on a Windows machine. The command fails with a generic "Error: Command failed" message, providing no specific details. The project builds without issue on macOS, suggesting a potential environment-specific problem.

## Reproduction

1. Clone this repository.
2. Navigate to the project directory using the command line.
3. Attempt to run `expo prebuild`. Observe the error.

## Solution

The solution involved identifying and correcting an incorrect environment variable or path setting that was interfering with the `expo prebuild` process. See `expoPrebuildSolution.js` for the detailed solution and explanation.