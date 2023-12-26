```markdown
# Rust Port Scanner

A simple port scanning tool written in Rust.

## Usage

```bash
cargo run -j 4 127.0.0.1
```

Replace `4` with the desired number of threads and `127.0.0.1` with the target IP address.

## Arguments

- `-j`: Specify the number of threads for parallel scanning.
- `-h` or `--help`: Show the help message.

## Features

- Scans a range of TCP ports on a specified IP address.
- Uses multiple threads for parallel scanning.

## Getting Started

1. Make sure you have Rust installed: [Install Rust](https://www.rust-lang.org/learn/get-started)
2. Clone this repository: `git clone https://github.com/sandy2108/ip-sniffer.git`
3. Navigate to the project directory: `cd ip-sniffer`
4. Build and run the program: `cargo run -j 4 127.0.0.1`

=
