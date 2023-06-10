# Shell Functions
A repository containing all of my (posix) shell functions. Intended for Linux but should work on any Unix-like operating system (such as macOS, BSD) and environments (like WSL).


## Table of Contents
- [About](#about)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)


## About
### **run.func**
[`run.func`](https://github.com/wasique-sh/shell-functions/blob/main/run.func) simplifies running any program code using a single command. It is specifically designed for executing simple programs and an ideal learning tool for individuals who are new to coding.

It supports the following programming languages (so far)
- C
- Java
- Python
- Rust
- Shell


## Dependencies
### **run.func**
- [Python](https://www.python.org/)
- [Java](https://openjdk.java.net/)
- [Rust](https://www.rust-lang.org/)


## Installation
```sh
git clone https://github.com/wasique-sh/shell-functions.git

# Session-Only
source shell-functions/*.func

# Permanent
#echo "source $(pwd)/shell-functions/*.func" >> ~/.bashrc
```

## Usage
### **run.func**
```sh
run <path/to/file>
```
