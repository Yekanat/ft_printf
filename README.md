# 🖨️ ft_printf - Custom printf Implementation

## 📖 Overview
`ft_printf` is a reimplementation of the standard `printf` function in C, built from scratch as part of the 42 School curriculum.  
This project aims to explore variadic functions, format string parsing, and efficient output management.

## ⚡ Features
- Supports most standard format specifiers:  
  `%c`, `%s`, `%p`, `%d`, `%i`, `%u`, `%x`, `%X`, `%%`
- Handles flags, width, and precision
- Uses variadic functions (`stdarg.h`)
- Modular design for ease of extension and readability

## 🛠️ Technologies
- **Language**: C
- **Compiler**: GCC
- **Standard**: C99

## 📦 Installation
To build the library:
```bash
git clone https://github.com/Yekanat/ft_printf.git
cd ft_printf
make
