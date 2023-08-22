Absolutely, here's the complete README.md content in Markdown format:

```markdown
# Simple Shell Project

A basic implementation of a shell in C, allowing users to execute commands.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Compilation](#compilation)
  - [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)

## Description

This project is a simple shell implementation in C, where users can enter commands similar to a Unix shell. The shell supports executing internal commands like "cd" as well as external commands available on the system.

## Features

- Execution of external commands
- Changing the current working directory using the "cd" command
- Interactive mode and non-interactive mode
- Basic error handling and clean code structure

## Getting Started

### Compilation

To compile the shell, use the following command:

```sh
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o myshell
```

### Usage

#### Interactive Mode

Run the shell in interactive mode by executing the compiled binary:

```sh
./myshell
```

The shell will prompt with `($)`, and you can enter commands to execute.

#### Non-Interactive Mode

You can also use the shell in non-interactive mode by providing commands via input redirection:

```sh
echo "/bin/ls" | ./myshell
```

### Example

```sh
($) /bin/ls
file1.txt file2.txt
($) cd ..
($) exit
```

## Contributing

Contributions are welcome! If you find a bug or have a suggestion, please create an issue or a pull request.
```
