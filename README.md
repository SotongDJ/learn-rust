# learn-rust

## Setup

1. Clone repo

    ```bash
    git clone git@github.com:SotongDJ/learn-rust.git
    ```

2. Check dependence and check code

    ```bash
    cargo check
    ```

## Command

- Test run

    ```bash
    cargo run
    # binary was created at target/debug/learn-rust
    ```

- Build binary

    ```bash
    cargo build
    # to run binary
    target/debug/learn-rust
    ```

- Build and optimize binary

    ```bash
    cargo build --release
    # to run binary
    target/release/learn-rust
    ```

- Update dependant packages

    ```bash
    cargo update
    ```

## References

- <https://doc.rust-lang.org/book/title-page.html>
- [Primitive Data Types](https://learning-rust.github.io/docs/a8.primitive_data_types.html)
- [Arrays in Rust](https://www.educative.io/answers/arrays-in-rust)
- [Rust Print Array](https://linuxhint.com/rust-print-array/)
- [Crate indexmap](https://docs.rs/indexmap/latest/indexmap/)
- [Equivalent macro to Python's dictionary comprehension syntax](https://stackoverflow.com/a/53688928)
