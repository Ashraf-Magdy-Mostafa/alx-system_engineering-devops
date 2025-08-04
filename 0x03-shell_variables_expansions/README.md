# alx-system_engineering-devops. Shell, init files, variables and expansions

This project covers key concepts of shell initialization files, variables, expansions, and simple bash scripting.


## Project Purpose

- Understand the function of shell initialization files (`~/.bashrc`, `/etc/profile`, etc.)
- Work with global and local shell variables
- Use shell expansions, arithmetic, and parameter substitution
- Safely create aliases and scripts with specific requirements
- Manipulate environment variables
- Practice printing and converting numbers in bash
- Learn technical writing and commenting in code

## Scripts

All scripts are in the directory `0x03-shell_variables_expansions/`.  
All scripts:

- Start with `#!/bin/bash`
- Contain exactly 2 lines (requirement)
- Are executable (`chmod +x filename`)

| File                         | Description                                                                              |
|------------------------------|------------------------------------------------------------------------------------------|
| `0-alias`                    | Creates an alias named `ls` that removes all files in current directory (`rm *`).        |
| `1-hello_you`                | Prints `hello user` where `user` is the currently logged-in user.                        |
| `2-path`                     | Adds `/action` to the end of the `$PATH` environment variable.                           |
| `3-paths`                    | Prints the number of directories in the current `$PATH`.                                 |
| `4-global_variables`         | Lists all environment variables.                                                         |
| `5-local_variables`          | Lists all local and environment variables, as well as shell functions.                   |
| `6-create_local_variable`    | Creates a new local variable `BEST` set to `School`.                                    |
| `7-create_global_variable`   | Creates a new global variable `BEST` set to `School`.                                   |
| `8-true_knowledge`           | Prints the result of `128 + $TRUEKNOWLEDGE`.                                            |
| `9-divide_and_rule`          | Prints the result of dividing `$POWER` by `$DIVIDE`.                                    |
| `10-love_exponent_breath`    | Prints `$BREATH` to the power of `$LOVE`.                                               |
| `11-binary_to_decimal`       | Converts the value of `$BINARY` (base 2) to base 10.                                    |
| `12-combinations`            | Prints all two-letter combinations from `aa` to `zz`, except `oo`.                      |
| `13-print_float`             | Prints the value of `$NUM` with two decimal places.                                     |

