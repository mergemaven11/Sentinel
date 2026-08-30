# Sentinel Command Cheat Sheet

A small reference for commands used while learning C and building Sentinel.

## C / GCC

### Check that GCC is installed
```powershell
gcc --version
```

### Compile a C file
```powershell
gcc hello.c -o hello
```

What this means:
- `gcc` — run the GNU C compiler
- `hello.c` — the C source file
- `-o hello` — create an executable named `hello`

### Run the compiled program in PowerShell
```powershell
.\hello
```

You can also run:
```powershell
.\hello.exe
```

## Git

### Check Git version
```bash
git --version
```

### Clone the Sentinel repository
```bash
git clone https://github.com/mergemaven11/Sentinel.git
```

### See changed files
```bash
git status
```

### Add changes
```bash
git add .
```

### Commit changes
```bash
git commit -m "describe what changed"
```

### Push changes
```bash
git push
```

## MSYS2 / UCRT64

### Update packages
```bash
pacman -Syu
```

### Install GCC for UCRT64
```bash
pacman -S mingw-w64-ucrt-x86_64-gcc
```

### Find GCC inside MSYS2
```bash
which gcc
```

## Windows PATH used for GCC

```text
C:\msys64\ucrt64\bin
```

## First Sentinel desktop test

Source file:
```c
#include <stdio.h>

int main(void) {
    printf("Sentinel version 0.1!\n");
    return 0;
}
```

Compile:
```powershell
gcc hello.c -o hello
```

Run:
```powershell
.\hello
```

Expected output:
```text
Sentinel version 0.1!
```

---

This file is meant to grow as Sentinel grows. Add commands here whenever something is useful enough that you do not want to rely on memory alone.
