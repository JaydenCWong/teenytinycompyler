# Teeny Tiny Compyler

This is a 300 line compiler written in python which compiles a BASIC-like language (see [Tiny BASIC](https://en.wikipedia.org/wiki/Tiny_BASIC)) to C code.

This is from [this tutorial (part 1)](https://austinhenley.com/blog/teenytinycompiler1.html) by Austin Z. Henley

[Part 2: parsing grammar](https://austinhenley.com/blog/teenytinycompiler2.html)

[Part 3: emitting code](https://austinhenley.com/blog/teenytinycompiler3.html)

## Things to Learn

- [Lexical Analysis](https://en.wikipedia.org/wiki/Lexical_analysis)
- [Synactic Analysis (Parsing)](https://en.wikipedia.org/wiki/Parsing)
- [Recursive Descent Parsing](https://en.wikipedia.org/wiki/Recursive_descent_parser)
- [Abstract Syntax Tree](https://en.wikipedia.org/wiki/Abstract_syntax_tree)
- [Semantic Analysis](https://en.wikipedia.org/wiki/Semantic_analysis_(compilers))
- [Optimization Passes](https://en.wikipedia.org/wiki/Optimizing_compiler)
- [Code Generation](https://en.wikipedia.org/wiki/Code_generation_(compiler))

## Future Considerations

- Parentheses for expressions
- Logical operators (and, or, not)
- ELSE IF and ELSE
- FOR loop
- Number literals written in binary, hex, and octal
- Better compiler errors (e.g., what line the error occurred)
- Allow multiple code files
- Functions with parameters and return values
- Lexical scope (see [scope](https://en.wikipedia.org/wiki/Scope_\(computer_science\)))
- Standard library (e.g., file operations)
- [Abstract syntax tree](https://en.wikipedia.org/wiki/Abstract_syntax_tree) representation
- More primitive types (e.g., integer, strings, boolean)
- Arrays
- Record types (i.e., structs or tuples)
- Type checking (see [type systems](https://en.wikipedia.org/wiki/Type_system))
- Compiler optimizations (e.g., [constant folding](https://en.wikipedia.org/wiki/Constant_folding))
- Test cases for the compiler (see [unit testing](https://en.wikipedia.org/wiki/Unit_testing) and [test-driven development](https://en.wikipedia.org/wiki/Test-driven_development))
