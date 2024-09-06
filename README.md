# CPF

This Python module provides tools for validating and formatting CPF numbers.

## Installation

To install, you can use pip:

```bash
pip install cpf
```

## Usage

### Validation

```python
from cpf import validate_cpf

cpf = "123.456.789-09"
if validate_cpf(cpf):
    print("Valid CPF!")
else:
    print("Invalid CPF.")
```

### Formatting

```python
from cpf import format_cpf

cpf = "12345678909"
formatted_cpf = format_cpf(cpf)
print(formatted_cpf)  # Output: 123.456.789-09
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
