# Rust

## Installation

https://doc.rust-lang.org/book/ch01-01-installation.html

## rustup

A command line tool for managing Rust versions and associated tools.

## linker

A program that Rust uses to join its compiled outputs into one file. 

If you get linker errors, you should install a C compiler, which will typically include a linker.

A C compiler is also useful because some common Rust packages depend on C code and will need a C compiler.

## rustfmt

Formatter

## Functions

## Macros

macros don’t always follow the same rules as functions.

## Compilation

Rust is an ahead-of-time compiled language, meaning you can compile a program and give the executable to someone else, and they can run it even without having Rust installed.

## Cargo tool

Cargo is Rust’s build system and package manager.

Cargo handles a lot of tasks for you, such as building your code, downloading the libraries your code depends on, and building those libraries.

Get the `rustup` version

- `cargo --version`

Create new project

- `cargo new hello_cargo`

Initialize a new Git repository along the Cargo project

- `cargo new --vcs=git`

Build the project

```
cargo build
./target/debug/hello_cargo
```

Compile it with optimizations

- `cargo build --release`

Compile the code and then run the resultant executable

- `cargo run`

Checks your code to make sure it compiles but doesn’t produce an executable

- `cargo check` 

## Commands

Get the `rustup` version

- `rustc --version`

Update `rustup`

- `rustup update`

Uninstall Rust and `rustup`

- `rustup self uninstall`

Open the local documentation in your browser

- `rustup doc`

Compile and run the file

```bash
rustc main.rs
./main
```

Run the formatter

`rustfmt main.rs` 

