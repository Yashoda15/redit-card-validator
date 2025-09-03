# Credit Card Validator

A simple Python implementation of the Luhn algorithm to check if a credit card number is valid.

## How it works
- Reverses the card number.
- Sums digits in odd positions directly.
- Doubles digits in even positions (subtracts 9 if result ≥ 10).
- Adds everything together.
- If the total modulo 10 is 0 → the card number is valid.

## Usage

```bash
python main.py

