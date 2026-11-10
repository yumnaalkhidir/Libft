# Libft

A reimplementation of core C standard library functions, plus a singly-linked-list utility library, written from scratch in C. Used as the foundation for later 42 School projects.

## Concepts covered
- String and memory manipulation (`ft_strlen`, `ft_memcpy`, `ft_strlcpy`, `ft_split`, `ft_strtrim`, `ft_itoa`, ...)
- Character classification and conversion (`ft_isalpha`, `ft_isdigit`, `ft_toupper`, `ft_tolower`, ...)
- File-descriptor output helpers (`ft_putstr_fd`, `ft_putnbr_fd`, ...)
- Bonus: a generic singly-linked-list module (`ft_lstnew`, `ft_lstadd_front/back`, `ft_lstmap`, `ft_lstiter`, `ft_lstclear`, ...)

## Build & run
```sh
make        # builds libft.a (mandatory part)
make bonus  # also adds the linked-list functions to libft.a
make clean  # remove object files
make fclean # remove object files and libft.a
make re     # fclean + all
```

Link against the resulting `libft.a` and include `libft.h` in your project.

---
Part of the 42 School curriculum.
