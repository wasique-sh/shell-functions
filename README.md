# Shell Functions
A repository containing all of my (posix) shell functions. Intended for Linux but should work on any Unix-like operating system (such as macOS, BSD) and environments (like WSL).


## Table of Contents
- [About](#about)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)


## About
### **cht.func**
[`cht.func`](https://github.com/wasique-sh/shell-functions/blob/main/cht.func) provides a simple way to interact with [cheat.sh](https://cheat.sh) website.

### **ocr.func**
[`ocr.func`](https://github.com/wasique-sh/shell-functions/blob/main/ocr.func) extracts text from the clipboard image and replaces the image with its corresponding text.

### **run.func**
[`run.func`](https://github.com/wasique-sh/shell-functions/blob/main/run.func) simplifies running any program code using a single command. It is specifically designed for executing simple programs and an ideal learning tool for individuals who are new to coding.

It supports the following programming languages (so far)
- C
- Java
- Python
- Rust
- Shell


## Dependencies
### **cht.func**
- [Curl](https://curl.se/)

### **ocr.func**
- [Xclip](https://github.com/astrand/xclip)
- [Tesseract](https://github.com/tesseract-ocr/tesseract)

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
### **cht.func**
```sh
cht <command>
```

### **ocr.func**
```sh
ocr
```

### **run.func**
```sh
run <path/to/file>
```
