# ft_printf - 42 Project

## 📚 Description

**Libft** is one of the first projects of the 42 curriculum.
Its purpose is to recreate a custom standard C library containing common utility functions (string handling, memory management, conversions, linked lists, etc.) in order to strengthen your understanding of the C language and the fundamentals of programming.

You implement your own versions of functions such as `memset`, `strcpy`, `atoi`, `split`, as well as a generic linked list module.

## 🛠️ Features

- Memory manipulation functions (`memset`, `memcpy`, etc.)
- String handling functions (`strlen`, `strchr`, etc.)
- Conversion functions (`atoi`, `itoa`, etc.)
- Output functions (`putchar`, `putstr`, etc.)
- Linked list management (`lstnew`, `lstadd_front`, `lstsize`, etc.)
- Fully compliant with the rules and standards of 42 School

## 📂 Project Structure

- `libft.h` : Header file containing all prototypes
- `*.c` : Source files for each function
- `Makefile` : Handles the compilation of the library

## 🚀 Usage

### 1. Compilation

```c
make
```

This command generates the `libft.a` file (static library).

### 2. Integration in your projects

Include the header in your code:

```c
#include "libft.h"
```

And when compiling, link the library:

```bash
gcc your_file.c -L. -lft
```

## 📝 Constraints

- Respect the prototypes and behaviors of the standard C library
- Proper error handling (NULL pointers, memory allocation, etc.)
- Most libc functions are forbidden (except those allowed by the project requirements)

## 💡 Tips

- Test each function individually
- Use valgrind to check for memory leaks
- Follow the 42 coding standard (Norminette)
