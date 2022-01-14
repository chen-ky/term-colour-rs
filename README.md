# term-colour-rs
Terminal text colour library for Rust

## Using this library

1. Navigate to your project's `Cargo.toml` file.
2. Insert `term_colour = { git = "https://github.com/chen-ky/term-colour-rs", package = "term-colour-rs"}` into the `dependencies` section of your `Cargo.toml` file.
3. Use format string to insert colours. `println!("{}Error:{} {}", term_colour::RED_BOLD, term_colour::NO_COLOUR, "Something went wrong.");` will result in "Error:" being bolded and red with "Something went wrong." following the terminal text colour. (Refer to `src/lib.rs` in this repository for possible colours)
