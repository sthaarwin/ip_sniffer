# TCP Port Scanner in Rust

A simple multithreaded TCP port scanner built with Rust. This tool scans for open ports on a given IP address and allows users to specify the number of threads to speed up scanning.

## Features
- Scans both IPv4 and IPv6 addresses.
- Customizable thread count with the `-j` flag.
- Displays open ports with multithreading for faster results.

## Usage

```bash
# Basic usage with default 4 threads
cargo run <IP_ADDRESS>

# Specify custom number of threads
cargo run -j <NUM_THREADS> <IP_ADDRESS>

# Display help message
cargo run -h
