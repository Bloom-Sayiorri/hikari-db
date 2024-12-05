# Hikari-DB

## Description
Hikari-db is a relationla database.

## Table Of Contents
- [Introduction](#introduction)
- [Setup](#setup)

## Directory Structure
- `src/`: Contains the source code files.
- `include/`: Contains header files.
- `build/`: Contains compiled artifacts.

### Introduction
Hikari in Japanese means light.
I chose this name as a beginning to something creative and exciting that I get to build and hopefully be used by other people in future.

## Setup

### Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/Bloom-Sayiorri/hikari-db.git
cd hikari-db
```

### How to Build
1. Run `make` to build the project.
2. Run the program using `./build/my_c_project`.

### How to Clean
Run `make clean` to remove compiled files.

### Building the project
For manual compilation 
``` bash 
    $ gcc -Iinclude src/main.c src/utils.c -o build/my_c_project 
    $ ./build/my_c_project
```
Compile the project
``` bash
    $ make
    $ ./build/my_c_project
    $ make clean
```
For debugging the project
``` bash
    $ gdb ./build/my_c_project
```

## Usage
Start the application:
```bash
npm start
```

## Features
- Easy-to-use interface
- Customizable settings
- Cross-platform compatibility

## Contributing
Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
Maintained by [Bloom Sayiorri](https://github.com/Bloom-Sayiorri).