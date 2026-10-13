# Simple Interest Calculator

A lightweight Bash-based calculator that computes simple interest using user-provided financial inputs. This project demonstrates fundamental shell scripting, user input handling, arithmetic calculations, and formatted output.

## Overview

The Simple Interest Calculator accepts a principal amount, an annual interest rate, and a time period in years. It calculates and displays the simple interest using the standard mathematical formula.

## Features

- Interactive command-line interface
- User input for principal, interest rate, and time
- Simple interest calculation
- Results formatted to two decimal places
- Lightweight implementation using Bash and `awk`

## Formula

**Simple Interest = (Principal × Rate × Time) / 100**

Where:
- **Principal (P):** Initial amount
- **Rate (R):** Annual interest rate in percent
- **Time (T):** Duration in years

## Technologies Used

- **Bash** — Shell scripting and user interaction
- **awk** — Floating-point arithmetic and result formatting
- **Git and GitHub** — Version control and project hosting

## Getting Started

### Prerequisites

A Bash-compatible terminal and `awk` are required. Linux and macOS typically include both. On Windows, use WSL or Git Bash with the necessary utilities available.

### Installation

Clone the repository:

```bash
git clone https://github.com/Qalbe234/bash-simple-interest-calculator.git
```

Navigate to the project directory:

```bash
cd bash-simple-interest-calculator
```

### Run the calculator

```bash
chmod +x simple-interest.sh
./simple-interest.sh
```

Alternatively, run it directly with Bash:

```bash
bash simple-interest.sh
```

## Example

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

This project demonstrates basic shell scripting, interactive input collection, arithmetic operations, numeric formatting, and the use of GitHub to document and share code.

## License

This project is licensed under the Apache License 2.0. See the `LICENSE` file for details.

## Author

**Qalbe234**

GitHub: [@Qalbe234](https://github.com/Qalbe234)
