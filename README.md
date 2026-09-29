# Strings to structure array

**42 C fundamentals** · Converts a string array into records containing the original pointer, its length and a separately allocated copy.

## Build and use

```sh
cc -Wall -Wextra -Werror -c ft_strs_to_tab.c
```

The command builds an object file; this repository has no standalone main program.

## Implementation note

Function-only source; see ft_stock_str.h. The caller owns each allocated copy and the returned array.

Source: [`ft_strs_to_tab.c`](ft_strs_to_tab.c). [License](LICENSE).
