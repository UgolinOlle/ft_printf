# ft_printf

<p align="center">
  <img src="https://github.com/mcombeau/mcombeau/blob/main/42_badges/ft_printfe.png" alt="ft_printf 42 project badge"/>
</p>

[![42 School Project](https://img.shields.io/badge/42%20Project-printf-blue)](https://github.com/your_username/ft_printf)
[![Language: C](https://img.shields.io/badge/language-C-green.svg)](<https://en.wikipedia.org/wiki/C_(programming_language)>)

A reimplementation of the C library function `printf()` for educational purposes, as part of the 42 School curriculum.

## Table of Contents

- [About](#about)
- [Usage](#usage)
- [Functionality](#functionality)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## About

This project, "ft_printf," is part of the 42 School curriculum and aims to re-implement the standard C library function `printf()`. The project focuses on understanding variadic functions, parsing, and formatting output.

## Usage

To use the `ft_printf` function in your C program, here's an example of how to use it in your code:

```c
#include "ft_printf.h"

int main() {
    ft_printf("Hello, %s!\n", "world");
    return (0);
}
```

## Functionality

The ft_printf function supports a subset of the format specifiers used by the standard printf() function. Supported format specifiers include:

- %c for characters
- %s for strings
- %d and %i for integers
- %u for unsigned integers
- %x for hexadecimal numbers (lowercase)
- %X for hexadecimal numbers (uppercase)
- %p for pointers
- %o for octal numbers
- %% for the percent sign

## Installation

To compile the ft_printf library, run the following commands:

1. Clone this repository:

```bash
git clone https://github.com/your_username/ft_printf.git
```

2. Include the `ft_printf.h` header file in your C file.
3. Compile your program with:

```bash
make
```

This will generate the `libftprintf.a` library, which you can link with your C programs as mentioned in the usage section.

## Contributing

Contributions to this project are welcome. If you find any issues or want to improve the code, please feel free to open a pull request or issue.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
