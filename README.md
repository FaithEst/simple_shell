# 0x16. C - Simple Shell

<img src="https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/235/shell.jpeg" height="auto" width="900">

This project is an implementation of the shell ```sh``` written in C at **ALX School**.

## Installation

- Clone this repo:
```git clone https://github.com/FaithEst/simple_shell.git```

- Compile with:
```gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh```

## Usage

After compilation, the resulting program can run stand-alone, either in interactive or non-interactive mode

### Interactive Mode

In interactive mode, simply run the program and wait for the prompt to appear. From there, you can type commands freely, exiting with either the "exit" command or ctrl-D.

### Non-Interactive Mode

In non-interactive mode, echo your desired command and pipe it into the program like this:

```sh
echo "ls" | ./shell
```

In non-interactive mode, the program will exit after finishing your desired command(s).


## Contributors
* [**Faith Mutitu**](https://github.com/faithest)
* [**Edwin Ogwel**](https://github.com/edwinogwel)
