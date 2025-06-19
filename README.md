# 42_ft_printf

Welcome! This repository contains my implementation of the C `printf` function as required by the 42 school curriculum. The goal of this project was to deeply understand formatted output in C, handle variadic functions, and manage memory and buffers efficiently. I focused on writing clean, modular, and standard-compliant code, closely following the project specifications.

---

## 🚩 Project Overview

I developed a custom version of `printf`, called `ft_printf`, which replicates the essential features and behavior of the standard function as outlined in the 42 subject PDF. This includes support for common format specifiers (`%d`, `%s`, `%c`, `%x`, `%p`, `%i`, `%u`, `%X`, `%%`), flags, width, and precision handling.

### Key Points

- **Comprehensive Format Support:** Handles all required specifiers, flags, width, and precision per the assignment.
- **Modular Source Structure:** Parsing, formatting, and output logic are separated for readability and maintainability.
- **Performance and Safety:** Variadic arguments and buffer management are implemented with care to avoid leaks and undefined behavior.
- **Custom Libft Integration:** Relies on my own C utility library (`libft`), as is standard for 42 projects.

---

## 📁 Main Files and Structure (Partial)

- `ft_printf.c`, `ft_print_*.c` — Main implementation and helper modules  
- `libftprintf.h` — Header with function prototypes and type definitions  
- `libft/` — Personal C library required by the project  
- `Makefile` — Build system for compiling and testing  

> This is a partial listing. For the complete codebase, see the [repository directory](https://github.com/artidek/42_ft_printf/tree/main).

---

## 🛠️ How to Use

1. **Clone the repository:**
   ```sh
   git clone https://github.com/artidek/42_ft_printf.git
   cd 42_ft_printf
   ```

2. **Build the library:**
   ```sh
   make
   ```

3. **Include and use in your code:**
   ```c
   #include "libftprintf.h"
   
   int main(void) {
       ft_printf("Hello, 42! Score: %d\n", 100);
       return 0;
   }
   ```
   Link the generated library when compiling your project.

---

## 🤝 Contributing

Feedback and suggestions are welcome. Please open an issue or submit a pull request if you have improvements or questions.

---

## ⚖️ License

This code is shared for educational and personal use as part of the 42 school curriculum.

---
