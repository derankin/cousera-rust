# Hello World in Rust

This is a simple "Hello, World!" program written in Rust.

## 1. Quick Start

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
rustup default stable
cargo run
```

## 2. Install Rust (with rustup)

Install Rust using `rustup`:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Then reload your shell and confirm installation:

```bash
rustup --version
rustc --version
cargo --version
```

Optional: ensure the stable toolchain is active:

```bash
rustup default stable
```

## 3. Running the Program

Once Rust is installed, you can run the program using the following command:

```bash
cargo run
```

## 4. Expected Output

When you run the program, you should see the following output:

```
Hello, world!
```

## 5. Program Structure

The project has one function in `src/main.rs`:

- `fn main()` is the entry point of the program.
- It prints `Hello, world!` to the console using `println!`.

## 6. Credits

This program was created as part of a Rust programming course on Coursera.

## 7. Open in GitHub Codespaces

1. Push this repository to GitHub.
2. Open the repository page on GitHub.
3. Click **Code** -> **Codespaces**.
4. Click **Create codespace on main**.
5. Wait for setup to complete.

This repo includes a `.devcontainer` configuration, so Rust tooling is preconfigured automatically.

### Run in Codespaces

Run the project with Cargo:

```bash
cargo run
```
