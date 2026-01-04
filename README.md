# ft_printf - 42 Project

## 📚 Description

**ft_printf** is a project from the 42 curriculum aimed at recreating the famous `printf` function from the C standard library. You must write your own version, named `ft_printf`, capable of printing formatted text while handling different types and formatting options, all while respecting the behavior of the original.

This project requires careful management of type conversions, buffering, flags, and parsing of variable arguments (`va_arg`).

---

## 🛠️ Features

- Handling of conversions: `%c`, `%s`, `%p`, `%d`, `%i`, `%u`, `%x`, `%X`, `%f`, `%lf`, `%ld` `%lld`, `%zu`, `%o`, `%n` and `%%`.
- Handling of flag: `#`, ` `, `.`, `+`, `-`, `0`.
- Formatted output to standard output
- Handling of pointers and signed/unsigned integers
- Counts and returns the number of characters printed
- Respects the constraints and behavior of the standard function

---

## 📂 Project Structure

- `ft_printf.c` : Main function
- `*.c` : All srcs files
- `ft_printf.h` : Header grouping prototypes and macros
- `Makefile` : Project compilation

---

## 🚀 Usage

### 1. Compilation

```bash
make
```

### 2. Usage in your projects

Include the header in your code:

```c
#include "ft_printf.h"
```

Usage example:

```c
ft_printf("Hello %s! Number: %d\n", "world", 42);
```

## 📝 Constraints

- Respect prototypes and standard behavior
- Correct handling of errors and memory
- Forbidden to use ``printf``, ``sprintf``, etc.
- Use of ``va_list``, ``va_start``, ``va_arg``, ``va_end``

## 💡 Tips

- Test all formatting cases, including edge cases
- Use ``valgrind`` to check for memory leaks
- Respect the 42 coding standard (Norminette)
