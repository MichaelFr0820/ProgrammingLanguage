# Flux Programming Language

A simple yet powerful programming language designed for educational purposes and formal language studies.

## About Flux

Flux is a beginner-friendly programming language that combines readability with essential programming concepts. It's ideal for students learning the fundamentals of computer science and programming language design.

## Features

- **Simple Syntax** - Easy to learn and understand
- **Strong Typing** - Type-safe with inference capabilities
- **Functions** - First-class function support
- **Control Flow** - If/else, while, and for loops
- **Data Structures** - Arrays and multiple data types
- **Comments** - Single and multi-line support

## Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/flux.git

# Navigate to directory
cd flux
```

### Your First Flux Program

```flux
print("Hello, Flux!");
```

### Running a Program

```bash
flux hello.flux
```

## Directory Structure

```
flux/
├── docs/           # Documentation
├── examples/       # Example programs
├── src/            # Source code (lexer, parser, interpreter)
├── tests/          # Test cases
└── README.md       # This file
```

## Language Syntax

### Variable Declaration
```flux
var x = 42;
const PI = 3.14159;
```

### Functions
```flux
func add(a, b) {
  return a + b;
}
```

### Control Flow
```flux
if (x > 10) {
  print("x is greater than 10");
} else {
  print("x is 10 or less");
}
```

### Loops
```flux
// While loop
while (i < 5) {
  print(i);
  i = i + 1;
}

// For loop
for (var i = 0; i < 5; i = i + 1) {
  print(i);
}
```

## Data Types

- `int` - Integer numbers
- `float` - Floating-point numbers
- `str` - Strings
- `bool` - Boolean (true/false)
- `array` - Arrays/Lists
- `null` - Null value

## Operators

### Arithmetic
```
+ - * / % ^
```

### Comparison
```
== != > < >= <=
```

### Logical
```
&& || !
```

## Examples

Check the `examples/` directory for sample programs including:
- Hello World
- Fibonacci sequence
- Prime number checker
- Array operations
- Function demonstrations

## Documentation

Detailed documentation is available in the `docs/` directory:
- [Language Specification](docs/SPECIFICATION.md)
- [Syntax Guide](docs/SYNTAX.md)
- [Built-in Functions](docs/BUILTINS.md)

## Testing

Run the test suite:
```bash
flux --test
```

## License

This project is provided for educational purposes.

## Author

Created for ATFL (Automata Theory and Formal Languages) Course

---

**Version**: 1.0  
**Last Updated**: May 15, 2026
