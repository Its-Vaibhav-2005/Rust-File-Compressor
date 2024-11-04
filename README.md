# Rust File Compressor

A simple command-line tool for compressing files using Rust, leveraging the [`flate2`](https://github.com/rust-lang/flate2-rs) library for efficient file compression. This tool compresses the specified file and saves it with a new name provided by the user.

## Features

- **Fast and Lightweight:** Built with Rust, ensuring high performance and memory safety.
- **Compression Algorithm:** Uses the DEFLATE algorithm, provided by the `flate2` Rust crate.
- **Easy CLI Interface:** Simple command-line syntax for quick compression.

## Installation

To use this compressor, you need to have Rust and Cargo installed. You can install Rust by following the instructions on [rust-lang.org](https://www.rust-lang.org/).

Once Rust is installed, clone this repository and navigate to its directory.

```bash
git clone https://github.com/Its-Vaibhav-2005/Rust-File-Compressor.git
cd Rust-File-Compressor
```

## Usage

To compress a file, use the following command:

`cargo run ./path/to/input_filename ./path/to/output_filename`

- **`input_filename`**: Path to the file you want to compress.
- **`output_filename`**: Path and name for the compressed output file.

### Example

`cargo run ./data/sample.txt ./data/sample.txt.gz`

The above command compresses `sample.txt` and creates a compressed file named `sample.txt.gz`.

## Dependencies

This project uses the following dependency:

- [`flate2`](https://github.com/rust-lang/flate2-rs) - A compression library that supports DEFLATE and other algorithms.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.

## Acknowledgements

- [Rust Programming Language](https://www.rust-lang.org/)
- [`flate2` crate](https://github.com/rust-lang/flate2-rs) for providing the compression functionality.
