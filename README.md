# Shamir's Secret Sharing - Polynomial Interpolation

## Overview
This project implements a simplified version of Shamir's Secret Sharing algorithm. Given a set of encoded roots in JSON format, the program decodes them and applies Lagrange interpolation to determine the constant term `c` of the polynomial.

## Features
- Reads test cases from JSON files.
- Decodes y-values from different bases.
- Uses Lagrange interpolation to reconstruct the polynomial.
- Calculates and prints the secret `c` for multiple test cases.

## Requirements
- Node.js

## Installation
1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies (if required, e.g., `npm install`).

## Usage
Run the script using:
```sh
node catalog.js
```
Ensure `testcase1.json` and `testcase2.json` exist in the project directory.

## File Structure
- `catalog.js` - Main execution file.
- `testcase1.json` - First test case data.
- `testcase2.json` - Second test case data.

## Output
The script prints:
```
Secret for Test Case 1: <3>
Secret for Test Case 2: <79836264050688>
```

## Notes
- Ensure all JSON files follow the required format.
- Verify base conversions to avoid miscalculations.
- Consider precision issues when dealing with large numbers.

