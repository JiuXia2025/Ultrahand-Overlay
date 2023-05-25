# Ultra Hand Overlay (System Manager)

The Ultra Hand File Management System is a C++ program that provides a user-friendly main menu overlay for performing various file operations. It is designed to run on various platforms, including the Nintendo Switch, and utilizes the TESLA library to create an interactive menu interface.

## Features

- Create directories
- Copy files
- Delete files
- Move files

## Nintendo Switch Compatibility
The Ultra Hand File Management System is compatible with the Nintendo Switch, allowing users to manage files and perform file operations directly on their Switch console.

To run the Ultra Hand File Management System on the Nintendo Switch, you need to have the necessary homebrew environment set up on your console. This typically involves running custom firmware or using homebrew launcher software. Once you have the homebrew environment set up, you can transfer the compiled executable file to your Switch and launch it using the homebrew launcher.

Please note that running homebrew software on your Nintendo Switch may void your warranty and can carry certain risks. Ensure that you understand the implications and follow the appropriate guidelines and precautions when using homebrew software.



## Getting Started

### Prerequisites

To compile and run the program, you need to have the following dependencies installed:

- TESLA library
- Standard C++ libraries


### Usage

1. After building the program, the executable file will be generated.

2. Transfer the executable file to your target platform or emulator.

3. Run the executable to launch the Ultra Hand File Management System.

4. Use the main menu interface to navigate and select file operations.

## Configuration

The program reads options and commands from an INI file named `config.ini`. If the file does not exist, it creates a default INI file with some sample options and commands.

The structure of the INI file should follow the format:

[Option 1]
command1 argument1 argument2
command2 argument1 argument2

[Option 2]
command1 argument1
command2 argument1 argument2 argument3


- Each option should be defined within square brackets `[Option]`.
- Each command should be specified on a new line under the corresponding option.
- Arguments for each command should be separated by spaces.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please create an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

