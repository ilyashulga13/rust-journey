# Guessing Game (Chapter 2)

This is my second Rust project, created while reading [The Rust Programming Language](https://doc.rust-lang.org/book/ch02-00-guessing-game-tutorial.html) book.

## What it does

This is a simple command-line game where the computer generates a random number, and the player has to guess it. The program gives "Too big" or "Too small" hints until the player guesses correctly.

## How to run

Make sure you have Rust and Cargo installed.

1. Navigate to this folder:
   ```bash
   cd guess_game
   ```
2. Run the project:
   ```bash
   cargo run
   ```

## Concepts learned

- Handling user input with `io::stdin()`.
- Generating random numbers with the `rand` crate.
- Using `match` and `cmp` for comparisons.
- Using loops (`loop`, `break`).
