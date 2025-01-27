# Number Theory
[![Documentation Status](https://readthedocs.org/projects/num-theory/badge/?version=latest)](https://num-theory.readthedocs.io/en/latest/?badge=latest)
[![codecov](https://codecov.io/gh/UBC-MDS/num_theory/graph/badge.svg?token=D83Q1sJfPf)](https://codecov.io/gh/UBC-MDS/num_theory)

A high-performance Python package for number theory operations, optimized for Project Euler and computational mathematics problems.

## Features

- Fast prime number generation and primality testing
- Efficient prime factorization
- Arithmetic progression calculations
- Optimized for computational challenges and competitive programming
- Simple, intuitive API design

## Installation

```bash
pip install num_theory
```

## Usage

### Prime Numbers

```python
from num_theory import get_prime_list_under_n, is_prime, prime_factorization

# Generate all primes under 100
primes = get_prime_list_under_n(100)

# Check if a number is prime
is_prime(997)  # Returns True

# Get prime factorization
factors = prime_factorization(84)  # Returns [(2, 2), (3, 1), (7, 1)]
```

### Arithmetic Progressions

```python
from num_theory import arithmetic_progression

# Generate first 5 terms of AP with a=2, d=3
terms = arithmetic_progression(a=2, d=3, n=5)  # [2, 5, 8, 11, 14]

# Calculate sum of first 10 terms
sum_ap = arithmetic_progression(a=2, d=3, n=10, compute_sum=True)

# Find the 100th term
nth_term = arithmetic_progression(a=2, d=3, n=100, nth_term=True)
```

## Key Functions

| Function | Description | Example |
|----------|-------------|---------|
| `get_prime_list_under_n(n)` | Generates all primes less than n | `get_prime_list_under_n(10)` returns `[2, 3, 5, 7]` |
| `prime_factorization(n)` | Returns prime factors with their powers | `prime_factorization(12)` returns `[(2, 2), (3, 1)]` |
| `arithmetic_progression(a, d, n, ...)` | Handles arithmetic progression operations | See examples above |
| `is_prime(n)` | Tests primality efficiently | `is_prime(17)` returns `True` |

### Relevance in the Python Ecosystem

This package complements existing Python libraries by offering a targeted collection of number theory utilities specifically for solving Project Euler problems.

Related Packages:

- SymPy: This does provide some symbolic mathematics, including some number theory, but isn't optimized for the computational challenges of advanced number theory.
- NumPy: The general-purpose library for numerical computations, but not specialized in number theory.
- primesieve: A highly efficient library for prime generation. This package provides similar functionalities.

## Comparison with Other Libraries

| Feature | num_theory | SymPy | NumPy | primesieve |
|---------|------------|-------|-------|------------|
| Focus | Number Theory | Symbolic Math | Numerical Computing | Prime Generation |
| Optimization | Project Euler | General Math | General Purpose | Prime Numbers |
| Learning Curve | Simple | Steep | Moderate | Simple |
| Speed | Fast | Moderate | Fast | Very Fast |

## Contributing

Interested in contributing? Check out the [contributing guidelines](contributing.md) . Please note that this project is released with a [Code of Conduct](conduct.md). By contributing to this project, you agree to abide by its terms.

## Authors

- Dhruv Garg
- Dominic Lam
- Thamer Aldawood
- Tingting Chen

## License

`num_theory` was created by Dhruv Garg, Dominic Lam, Thamer Aldawood, Tingting Chen. It is licensed under the terms of the MIT license.

## Credits

`num_theory` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).