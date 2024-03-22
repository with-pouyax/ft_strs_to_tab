# ft_strs_to_tab

## Description

This repository contains a C program that converts an array of strings into an array of structures, with each structure containing the original string, its length, and a copy of the string. This project demonstrates memory management in C, including dynamic memory allocation (`malloc`), and deep copying of strings.

The project includes:
- A function to calculate the length of a string (`ft_strlen`).
- A function to copy a string (`ft_strcpy`).
- A function to convert an array of strings into an array of structures (`ft_strs_to_tab`).

This is particularly useful for applications that need to manipulate strings and their metadata collectively.

## Structure Definition

The `t_stock_str` structure is defined as follows in the `ft_stock_str.h` header file:

```c
typedef struct s_stock_str
{
    int     size;
    char    *str;
    char    *copy;
}   t_stock_str;
