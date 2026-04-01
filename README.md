# 2-Input C Calculator

A simple command-line calculator written in C that performs basic arithmetic operations on two numbers.

## Features

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`) with division-by-zero protection
- Supports decimal numbers (double precision)
- Results displayed to 2 decimal places

## Requirements

- A C compiler (e.g., `gcc`, `clang`)

## Compilation

```bash
gcc 2InputCcalculator.c -o calculator
```

## Usage

Run the compiled program:

```bash
./calculator
```

You will be prompted to enter:
1. **First number** – any integer or decimal value
2. **Second number** – any integer or decimal value
3. **Operator** – one of `+`, `-`, `*`, `/`

### Example

```
Enter first number: 10
Enter second number: 4
Enter operator (+, -, *, /): /

result:2.500000
```

## Error Handling

| Scenario | Output |
|---|---|
| Division by zero | `Error! Division by zero.` |
| Invalid operator | `Error! Invalid operator.` |

## Notes

- Input numbers are stored as `double` for decimal precision.
- Division results display full precision; all other operations display 2 decimal places.
