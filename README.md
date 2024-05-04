# This is a collection of 3 repositories, the "fancy-projects".
## These repositories will be described one by one here.

# FANCY-CLI: Folder Art with Neat Colors for You

FANCY is a command-line interface (CLI) tool that helps you customize the icons for your folders.

![FANCY logo](fancy-cli/fancy/assets/poster.png)

## Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/pythonkid90/fancy-cli
    ```

2.  Install FANCY:

    ```bash
    pip install ./fancy-cli
    ```

> **Note**: The `dev_install.sh` script is for development purposes and is not required for regular installation.

## Usage

To view all available features, run:

    ```bash
    fancy --help
    ```
    
## Branch Information


*   **main:** This branch is expected to be mostly stable for production use.
*   **dev:** This branch may contain some bugs, and serves as a "staging area" for new features.
*   **canary:** This branch is highly unstable and is only used for development. Do not use this branch.

## Windows Support

FANCY currently does not support Windows. This feature is planned for version 1.0.0.


# Pysh

## Pysh & Shpy - Interactive Python Shells

Pysh is an interactive Python console that includes shell commands too, so you can `ls` and `cd` to your heart's content while still being able to use Python features.

Here are some features of Pysh:

*   Execute Python code directly in the terminal.
*   Get information about your environment like username, Python version, and network name.
*   Navigate directories using the \`cd\` command.
*   Exit the shell using \`exit\` or \`quit\`.

Shpy
----

Shpy is a shell-first variant of Pysh that prioritizes shell command execution. It falls back to Python execution if the shell command fails, while Pysh does the opposite.

## Installation

To use pysh (or shpy), you'll need Python installed on your computer.

Then, you can clone this repository onto your device.

    ```bash
    git clone https://github.com/pythonkid90/pysh
    ```

Next, run pysh.

    ```bash
    python3 pysh/pysh/pysh.py
    ```

For shpy, do

    ```bash
    python3 pysh/pysh/shpy.py
    ```

Your shell is now `pysh`!

To exit `pysh`, type `exit` or `quit`.

# tkfancy
## tkfancy - A Tkinter GUI creator based off customtkinter
tkfancy is still in very early development, so docs cannot be made for it yet.