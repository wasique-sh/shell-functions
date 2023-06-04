# Shell Functions
A repository containing all of my shell functions

## Table of Contents
- [About](#about)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)

## About
### **run.func**
[`run.func`](https://github.com/wasique-sh/shell-functions/blob/master/run.func) is a posix shell function which simplifies running any program code using a single command.

It supports the following programming languages (so far)
- C
- Java
- Python
- Rust
- Shell

## Dependencies
- GNU Core Utilities
- Bash

### **run.func**
- Python
- Java
- Rust

## Installation
```sh
git clone https://github.com/wasique-sh/shell-functions.git
```
Session-Only
```sh
source shell-functions/*.func
```

Permanent
```sh
echo "source shell-functions/*.func" >> ~/.bashrc
```

## Usage
### **run.func**
```sh
run <file/to/file>
```