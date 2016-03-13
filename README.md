---
layout: readme
---

# rustup

`rustup` installs Rust from the official release channels, enabling
you to easily switch between the stable, beta, and nightly compilers
and keep them updated.

**WARNING: This is seriously beta software.**

## Installation

Follow the instructions at [https://www.rustup.rs].

After installation you will have executables `rustc`, `cargo`, and
`rustup` in Cargo's `bin` directory, which on Unix is located at
`$HOME/.cargo/bin` and on Windows is `$USERPROFILE/.cargo/bin`. These
directories will be in your `$PATH` environment variable, which means
you can run them from the shell without further configuration.

Open a shell and type the following:

```sh
rustc --version
```

If you see something like `rustc 1.7.0 (a5d1e7a59 2016-02-29)` then
you are ready to Rust.

## Keeping Rust up to date

## Working with nightly Rust

## Cross-compilation

## Examples

<a name="tools"></a>
## Additional recommended tools

* `cargo install rustfmt`
