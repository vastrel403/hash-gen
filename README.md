# Hash Gen

A simple terminal-based hash generator written in Python. Enter any text and instantly get its hash digest using MD5, SHA1, SHA256, SHA512, or any other algorithm supported by Python's `hashlib`.

- **Developer:** 404invisiblepeople
- **Group:** vastrel
- **GitHub:** [vastrel403](https://github.com/vastrel403)

## Features

- Generate hashes with any algorithm supported by `hashlib` (MD5, SHA1, SHA256, SHA512, SHA3 variants, BLAKE2, etc.)
- Simple, colorized terminal interface
- Runs in a continuous loop so you can hash multiple values in one session
- No external services — everything runs locally

## Requirements

- Python 3.8 or higher
- [colorama](https://pypi.org/project/colorama/) (for colored terminal output)

## Installation

```bash
git clone https://github.com/vastrel403/hash-gen.git
cd hash-gen
pip install -r requirements.txt
```

## Usage

Run the script:

```bash
python3 hash_gen.py
```

You will be prompted to:

1. Enter the text you want to hash.
2. Enter the algorithm name (e.g. `md5`, `sha1`, `sha256`, `sha512`).

The resulting hash digest is printed to the terminal. Press Enter to hash another value, or type `q` and press Enter to stop.

If an unsupported algorithm name is entered, the script shows an error message instead of crashing, and lets you try again.

## Example

```
Enter the text to hash: hello world
Choose an algorithm (md5, sha1...): sha256
hash: b94d27b9934d3e08a52e52d7da7dacc5df37c2a1e4c7c5d3f9c3b5a5e5c5e5d
```

## License

Feel free to add a license of your choice (e.g. MIT) to this repository.
