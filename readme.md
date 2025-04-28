# Micro Assembly Shell (monsole)

Welcome to the Micro Assembly powered shell!

## Overview

This project is a simple shell implemented using a custom micro assembly language. It supports basic commands such as `ls`, `echo`, `clear`, and `exit`.

## Features

- **ls**: List directory contents.
- **echo**: Echo input text back to the user.
- **clear**: Clear the terminal screen.
- **exit**: Exit the shell.

## File Structure

- `main.masm`: The main entry point of the shell.
- `commands.masm`: Contains the implementation of shell commands.
- `strings.masm`: Stores string literals used in the shell.
- `shell_helpers.masm`: Helper functions for shell operations.

## Usage

To run the shell, assemble and execute the `main.masm` file. The shell will display a prompt where you can enter commands.

## Example

```
> ls
you said ls

> echo Hello, World!
Enter text to echo: Hello, World!
Hello, World!

> clear
[clear]

> exit
Exiting shell...
```

## Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License.
