# ft_strs_to_tab

This repository provides a C library containing the `ft_strs_to_tab` function, which converts an array of strings into an array of `t_stock_str` structures. Each structure contains the length of the string, the original string, and a copy of the string. This library is useful for managing arrays of strings and their metadata in C projects.

## Overview

The library consists of two main parts:
- The `ft_stock_str.h` header file, which defines the `t_stock_str` structure.
- The `ft_strs_to_tab` function, which allocates and populates an array of `t_stock_str` structures based on an array of strings.
