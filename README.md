# Integer Factorization Toolkit

This project implements integer factorization algorithms with applications in cryptography. It features two key algorithms—Trial Division and Pollard's Rho—to explore their efficiency and practical use cases, such as RSA decryption. The project also includes a Python-based graphical user interface (GUI) for ease of use.

---

## Features

- **Algorithms**:
  - Trial Division: A simple, deterministic approach for factorization.
  - Pollard's Rho: A probabilistic algorithm optimized for numbers with small factors.

- **Cryptographic Application**: Demonstrates RSA decryption by factorizing the modulus to extract private keys.

- **Interactive GUI**: A user-friendly interface for:
  - Factorizing numbers.
  - Comparing algorithm performance.
  - Decrypting RSA-encrypted messages.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Furqan1208/integer-factorization-algorithms.git
   cd integer-factorization-algorithms
   ```

---

## Usage

### Command Line

1. Run the factorization scripts directly:
   ```bash
   python trial_division.py
   python pollards_rho.py
   ```

2. Provide input numbers to see their prime factors.

### GUI Mode

1. Launch the GUI:
   ```bash
   python gui.py
   ```

2. Features in GUI:
   - Input numbers for factorization.
   - Choose between Trial Division and Pollard's Rho.
   - Perform RSA decryption with provided modulus, exponent, and ciphertext.

---

## Examples

### Factorization
- **Input**: `8051`
- **Output**: `83, 97` (Prime factors via Pollard's Rho)

### RSA Decryption
- **Modulus (n)**: `77`
- **Ciphertext (c)**: `13`
- **Decrypted Message**: `41`

---

## Performance

| Algorithm     | Small Numbers | Large Numbers |
|---------------|---------------|---------------|
| Trial Division| Slow          | Very Slow     |
| Pollard's Rho | Fast          | Efficient     |

---

## Future Enhancements

- Hybrid algorithms for large numbers.
- Optimized cycle detection in Pollard’s Rho.
- Support for visualizing algorithm steps in the GUI.

---

## Contributing

Contributions are welcome! Please fork the repository, make changes, and submit a pull request.
