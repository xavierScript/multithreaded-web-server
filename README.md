# Multithreaded Web Server — Rust Book Final Project

This repository is the completed final chapter and project from "The Rust Programming Language" (the Rust Book).

It implements a small, educational multithreaded web server in Rust. The code demonstrates:

- Basic TCP listener and request parsing
- Serving simple HTML files
- A thread pool for handling multiple connections concurrently
- Graceful handling of requests and basic routing

Files of interest:

- `Cargo.toml` — crate manifest
- `src/main.rs` — server entrypoint
- `src/lib.rs` — library code (thread pool and helpers)
- `hello.html` — example static response used by the server
- `404.html` — another example response

Prerequisites

- Rust toolchain (stable). Install from https://rustup.rs

Build and run

```bash
# build (release recommended)
cargo build --release

# run (server listens on the port defined in the code, typically 7878)
cargo run --release
```

Usage

Open your browser and visit `http://127.0.0.1:7878` (or the port configured in the source).

Notes

- This project is intended as an educational exercise following the Rust Book; it is not hardened for production use.

Acknowledgements

This is based on the final chapter project from "The Rust Programming Language".
