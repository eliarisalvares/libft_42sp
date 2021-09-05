
# Libft

:books: *Your very first own library.*

Libft is the first project of the 42cursus. The aim is to recode several functions from the standard C library and some additional functions that may be used throughout the course.

## Why is  libft important?

This project allows students to work with the basics of the language. Pointers, memory allocation, operations with data structures, as well as the creation of header and Makefile files.

## Grade and Badge

![image](https://user-images.githubusercontent.com/85964972/132143431-66093bfc-2abc-4ab0-a780-d29c99e15a71.png)
![image](https://user-images.githubusercontent.com/85964972/132143244-c89cd42b-ec35-4bb0-a348-3370efc89db2.png)

## Skills
* Algorithms & AI
* Imperative programming
* Rigor

## Mandatory part
**Libc functions**


| function | description |
|--|--|
|ft_isascii|tests if a given character, in the current locale, can be represented as a valid 7–bit US-ASCII character.        
|ft_isprint         |checks whether a character is a printable character or not.            
|ft_isalpha        |checks if the passed character is alphabetic.`
|ft_isdigit        |checks if the passed character is a decimal digit character.
|ft_isalnum        |checks if the passed character is alphanumeric.
|ft_tolower        |converts a given letter to lowercase.
|ft_toupper        |converts a given letter to uppercase.
|ft_strlen        |computes the length of the string str up to, but not including the terminating null character.
|ft_strchr        |searches for first occurrence of _c_ in the string _*str_.
|ft_strrchr        |searches for the last occurrence of the character _c_ (an unsigned char) in the string pointed to, by the argument _str_.
|ft_strnstr        |locates the first occurrence of the null-terminated string pointed by _little_ in string pointed by _big_. Characters that appear after a _'\0'_ or _len_ are not searched.
|ft_strncmp        |compares at most the first _n_ bytes of _str1_ and _str2_.
|ft_strlcpy        |copies up to _size - 1_ characters from the NUL-terminated string _src_ to _dest_, NUL-terminating the result.
|ft_strlcat       |appends the NUL-terminated string _src_ to the end of _dest_. It will append at most _size - strlen(dst) - 1 bytes_, NUL-terminating the result.
|ft_strdup        |returns a pointer to a new string duplicated of the string _s_. Memory for the new string is obtained with malloc.
|ft_atoi        |converts the initial portion of the string pointed to by _str_ to int.
|t_memset       |fills memory with a constant byte.
|ft_bzero        |copies _n_ bytes, each with a value of zero, into string _s_.
|ft_memcpy        |copies _n_ bytes from memory area _src_ to memory area _dest_. The memory areas must not overlap. Use **ft_memmove** if the memory areas do overlap.
|ft_memmove        |copies _n_ bytes from memory area _src_ to memory area _dest_ and will not be corrupted if memory areas do overlap.
|ft_memchr        |Searches within the first _n_ bytes of the block of memory pointed by _str_ for the first occurrence of _c_ (interpreted as an unsigned char), and returns a pointer to it.
|ft_memcmp       |compares _n_ byte string s1 against _n_ byte string s2.
|ft_calloc        |allocates _size_ bytes and returns a pointer to the allocated memory. The memory is not initialized.

**Additional functions**

In this second part, students must code a set of functions that are either not included in the libc, or included in a different form. 

| function | description |
|--|--|
ft_substr | allocates (with malloc) and returns a substring from the string _s_. The substring begins at index _start_ and is of maximum size _len_. |
| ft_strjoin | allocates (with malloc) and returns a new string, which is the result of the concatenation of _s1_ and _s2_.
| ft_strtrim | allocates (with malloc) and returns a copy of _s1_ with the characters specified in _set_ removed from the beginning and the end of the string
|ft_split| allocates (with malloc) and returns an array of strings obtained by splitting _s_ using the character _c_ as a delimiter. The array must beended by a NULL pointer.
|ft_itoa| allocates (with malloc) and returns a string representing the integer received as an argument. Negative numbers must be handled.
|ft_strmapi| applies the function _f_ to each character of the string _s_ to create a new string (with malloc) resulting from successive applications of _f_.
|ft_striteri| applies the function _f_ to each character of the string passed as argument, and passing its index as first argument. Each character is passed by address to f to be modified if necessary.
|ft_putchar_fd| outputs the character _c_ to the given file descriptor.
|ft_putstr_fd| outputs the string _s_ to the given file descriptor.
|ft_putendl_fd| outputs the string _s_ to the given file descriptor, followed by a newline.
|ft_putnbr_fd| outputs the integer _n_ to the given file descriptor.
