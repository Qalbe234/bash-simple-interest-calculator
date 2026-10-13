# Simple Interest Calculator

A lightweight Bash-based calculator that calculates simple interest using user-provided financial inputs. This project demonstrates fundamental shell scripting, user input handling, arithmetic calculations, and formatted output.

## Overview

The Simple Interest Calculator accepts a principal amount, an annual interest rate, and a time period in years. It calculates and displays the simple interest using the standard mathematical formula.

## Features

- Interactive command-line interface
- User input for principal amount, interest rate, and time period
- Accurate simple interest calculation
- Results formatted to two decimal places
- Lightweight implementation using Bash and `awk`

## Formula

The simple interest is calculated using the following formula:

**Simple Interest (SI) = (P × R × T) / 100**

Where:

- **SI** = Simple Interest
- **P** = Principal amount (initial amount invested or borrowed)
- **R** = Annual interest rate (percentage)
- **T** = Time period (in years)

### Example Calculation

Given:

- Principal (P) = 10,000
- Annual Interest Rate (R) = 5%
- Time (T) = 2 years

Calculation:

**SI = (10,000 × 5 × 2) / 100**

**SI = 100,000 / 100**

**SI = 1,000.00**

Therefore, the simple interest is **1,000.00**.

## Technologies Used

- **Bash** — Shell scripting and user interaction
- **awk** — Floating-point arithmetic and result formatting
- **Git and GitHub** — Version control and project hosting

## Getting Started

### Prerequisites

- A Bash-compatible terminal
- The `awk` utility

Linux and macOS typically include these tools. Windows users can use WSL or Git Bash with the necessary utilities available.

### Installation

Clone the repository:

```bash
git clone https://github.com/Qalbe234/bash-simple-interest-calculator.git
```

Navigate to the project directory:

```bash
cd bash-simple-interest-calculator
```

### Running the Calculator

Make the script executable:

```bash
chmod +x simple-interest.sh
```

Run the calculator:

```bash
./simple-interest.sh
```

Alternatively, run it directly using Bash:

```bash
bash simple-interest.sh
```

## Source Code

The complete contents of `simple-interest.sh` are shown below:

```bash
#!/bin/bash

# Simple Interest Calculator

echo "Simple Interest Calculator"

read -p "Enter principal amount: " principal
read -p "Enter rate of interest (%): " rate
read -p "Enter time period (years): " time

interest=$(awk "BEGIN {printf \"%.2f\", ($principal * $rate * $time) / 100}")

echo "Simple Interest: $interest"
```

## Example Output

```text
Simple Interest Calculator
Enter principal amount: 10000
Enter rate of interest (%): 5
Enter time period (years): 2
Simple Interest: 1000.00
```

## Project Structure

```text
bash-simple-interest-calculator/
├── README.md
├── LICENSE
├── CODE_OF_CONDUCT
├── CONTRIBUTING.md
└── simple-interest.sh
```

## Learning Outcomes

This project demonstrates:

- Basic Bash scripting and command-line interaction
- Collecting and processing user input
- Performing arithmetic calculations with `awk`
- Formatting numerical output to two decimal places
- Documenting and maintaining a project using GitHub

## License

This project is licensed under the Apache License 2.0. See the `LICENSE` file for details.

## Author

Qalbe234
GitHub: @Qalbe234

**Qalbe234**

GitHub: [@Qalbe234](https://github.com/Qalbe234)
