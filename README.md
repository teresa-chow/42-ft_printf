# ft_printf
[![42 School: Rank 1](https://img.shields.io/badge/42%20School-Rank%201-%2315bbbb)](https://www.42network.org/)

_Recoding of printf: in C language, printf is used to write formatted output to the standard output stream, stdout. This project was developed during the Common Core curriculum at 42, introducing the concept of variadic functions._
___


### Table of contents
[Usage](#compass-usage) · [Subject](#book-subject) · [Mandatory](#mandatory-part) · [Bonus](#bonus-part) · [License](#license)

___

</br>

# :compass: Usage
## Setup and compilation

1. Clone repository
    ```bash
    git clone git@github.com:teresa-chow/42-ft_printf.git
    ```

2. Go inside project directory and run `make`
    ```bash
    cd ft_printf
    make
    ```
    
3. To use the library in your code, `#include` the following header
    ```c
    #include "ft_printf.h"
    ```

</br>

# :book: Subject
:page_facing_up: [ft_printf subject EN [PDF]](./en_ftprintf_2023.pdf)

</br>

>[!NOTE]
>This codebase follows the applicable programming standard at 42, known as the Norm.

<details open>
  <summary><h2>Mandatory part</h2></summary>
    
Handled conversions:

Format specifier | Description
:--:|--
`%c` | _Prints a single character._
`%s` | _Prints a string of characters._
`%p` | _Prints the_ `void *` _pointer argument in hexadecimal format._
`%d` | _Prints a decimal (base 10) number._
`%i` | _Prints an integer in base 10._
`%u` | _Prints an unsigned decimal number._
`%x` | _Prints a number in hexadecimal (base 16) lowercase format._
`%X` | _Prints a number in hexadecimal uppercase format._
`%%` | _Prints a percent sign._

</details>

___

</br>

### License
This work is published under the terms of [42 Unlicense](./LICENSE).

</br>

[⬆ back to top](#42-ft_printf)
