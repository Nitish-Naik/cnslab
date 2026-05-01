# CNS Lab

A Python library for classical and modern cryptography algorithms, built for educational use and experimentation.

## Features

- Implementations of cryptographic ciphers and hashing algorithms
- Pure Python code suitable for learning and demonstrations
- Includes classical ciphers, modern symmetric and asymmetric cryptography, and hashing
- Organized as a Python package with reusable modules

## Package Contents

The `cns_lab` package includes the following algorithm modules:

- `caesar.py` - Caesar cipher
- `vigenere.py` - Vigenère cipher
- `playfair.py` - Playfair cipher
- `railfence.py` - Rail Fence cipher
- `hill.py` - Hill cipher
- `aes.py` - Advanced Encryption Standard
- `des.py` - Data Encryption Standard
- `rsa.py` - RSA public-key encryption
- `deffie.py` - Diffie-Hellman key exchange
- `dss.py` - Digital Signature Standard (DSS)
- `md5.py` - MD5 hashing
- `sha_512.py` - SHA-512 hashing
- `ids.py` - Example intrusion detection support utilities
- `all.py` - Convenience module importing all algorithm implementations

## Installation

Install the package locally with pip:

```bash
pip install .
```

Or install in editable mode for development:

```bash
pip install -e .
```

## Usage

Import the package or individual algorithm modules:

```python
from cns_lab.programs import caesar

ciphertext = caesar.encrypt('HELLO', 3)
print(ciphertext)
```

For full access to all implementations:

```python
from cns_lab.programs import all as cns_all
```

## Development

- The package metadata is defined in `setup.py`
- Source code lives under `cns_lab/programs/`
- Built package copies are available in `build/lib/cns_lab/`
