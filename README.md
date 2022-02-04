<p align="center">

  <a aria-label="Completed" href="https://www.42sp.org.br/">
    <img src="https://img.shields.io/badge/42.sp-LIBFT-682998?logo="></img>
  </a>

  <a href="https://github.com/m-carecho/42SP_Libft/commits/main">
    <img src="https://img.shields.io/github/last-commit/m-carecho/42SP_Libft?color=682998">
  </a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/m-carecho/42SP_Libft?color=682998">

</p>

<div align="center">
<a href="https://github.com/m-carecho/42SP_Libft"><img height="100px" src="https://user-images.githubusercontent.com/98053054/151611442-dc327b44-b61e-430d-85c8-9789af8824be.png" /></a>
</div>

---

# 🔖 Index

* [What is Libft?](#sparkles-what-is-libft)
* [List of Functions](#bookmark_tabs-list-of-functions)
* [Technologies](#computer-technologies)

---

# :sparkles: What is Libft?

Libft is an individual project at 42 that requires us to re-create some standard C library functions including some additional ones that can be used later to build a library of useful functions for the rest of the program.

At 42 we're not allowed to use some standard libraries on our projects, so we have to keep growing this library with our own functions as we go farther in the program.

---

# :bookmark_tabs: List of Functions

## Functions from `<ctype.h>`

- [x] [`ft_isalpha`](https://github.com/m-carecho/42SP_Libft/blob/main//ft_isalpha.c)	- checks for an alphabetic character.
- [x] [`ft_isdigit`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_isdigit.c)	- check for a digit (0 through 9).
- [x] [`ft_isalnum`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_isalnum.c)	- checks for an alphanumeric character.
- [x] [`ft_isascii`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_isascii.c)	- checks whether c fits into the ASCII character set.
- [x] [`ft_isprint`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_isprint.c)	- checks for any printable character.
- [x] [`ft_toupper`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_toupper.c)	- convert char to uppercase.
- [x] [`ft_tolower`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_tolower.c)	- convert char to lowercase.

## Functions from `<string.h>`

- [x] [`ft_strlen`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strlen.c)	- calculate the length of a string.
- [x] [`ft_memset`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_memset.c)	- fill memory with a constant byte.
- [x] [`ft_bzero`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_bzero.c)	- zero a byte string.
- [x] [`ft_memcpy`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_memcpy.c)	- copy memory area.
- [x] [`ft_memmove`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_memmove.c)	- copy memory area.
- [x] [`ft_strlcpy`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strlcpy.c)	- copy string to a specific size.
- [x] [`ft_strlcat`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strlcat.c)	- concatenate a string to a specific size.
- [x] [`ft_strchr`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strchr.c)	- locate character in a string.
- [x] [`ft_strrchr`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strrchr.c)	- locate character in a string.
- [x] [`ft_strncmp`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strncmp.c)	- compare two strings.
- [x] [`ft_memchr`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_memchr.c)	- scan memory for a character.
- [x] [`ft_memcmp`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_memcmp.c)	- compare memory areas.
- [x] [`ft_strnstr`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strnstr.c)	- locate a substring in a string.
- [x] [`ft_strdup`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strdup.c)	- creates a duplicate for the string passed as a parameter.

## Functions from `<stdlib.h>`
- [x] [`ft_atoi`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_atoi.c)	- convert a string to an integer.
- [x] [`ft_calloc`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_calloc.c)	- allocates memory and sets its bytes' values to 0.

## Non-standard functions
- [x] [`ft_substr`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_substr.c)	- returns a substring from a string.
- [x] [`ft_strjoin`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strjoin.c)	- concatenates two strings.
- [x] [`ft_strtrim`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strtrim.c)	- trims the beginning and end of a string with a specific set of chars.
- [x] [`ft_split`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_split.c)	- splits a string using a char as parameter.
- [x] [`ft_itoa`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_itoa.c)	- converts a number into a string.
- [x] [`ft_strmapi`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_strmapi.c)	- applies a function to each character of a string.
- [x] [`ft_striteri`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_striteri.c)	- applies a function to each character of a string.
- [x] [`ft_putchar_fd`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_putchar_fd.c)	- output a char to a file descriptor.
- [x] [`ft_putstr_fd`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_putstr_fd.c)	- output a string to a file descriptor.
- [x] [`ft_putendl_fd`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_putendl_fd.c)	- output a string to a file descriptor, followed by a new line.
- [x] [`ft_putnbr_fd`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_putnbr_fd.c)	- output a number to a file descriptor.

## Linked list functions

- [x] [`ft_lstnew`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_lstnew.c)	- creates a new list element.
- [x] [`ft_lstadd_front`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_lstadd_front.c)	- adds an element at the beginning of a list.
- [x] [`ft_lstsize`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_lstsize.c)	- counts the number of elements in a list.
- [x] [`ft_lstlast`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_lstlast.c)	- returns the last element of the list.
- [x] [`ft_lstadd_back`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_lstadd_back.c)	- adds an element at the end of a list.
- [x] [`ft_lstclear`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_lstclear.c)	- deletes and free list.
- [x] [`ft_lstiter`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_lstiter.c)	- applies a function to each element of a list.
- [x] [`ft_lstmap`](https://github.com/m-carecho/42SP_Libft/blob/main/ft_lstmap.c)	- applies a function to each element of a list.

---

# :computer: Technologies

This Project was made with:

* [C](https://devdocs.io/)
* [Makefile](https://www.gnu.org/software/make/manual/make.html)
* [Shell](https://unixguide.readthedocs.io/en/latest/unixcheatsheet/)
* [clang](https://clang.llvm.org/)

---

<p align="center">
made with 💖 by m-carecho
</p>