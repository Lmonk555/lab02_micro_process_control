# lab02_micro_process_control

This repository contains the report, source code, and Proteus simulation files for Lab 02 of the Microprocessors & Microcontrollers course.

## Directory Structure

```
lab02_micro_process_control/
├── latex/
│   ├── contents/       # LaTeX source files for the report content
│   ├── examples/
│   ├── main_code/      # Pure C code listings (as .txt)
│   ├── pictures/       # Images used in the report
│   ├── codespace.sty
│   ├── hcmut-report.cls
│   ├── main.tex
│   ├── main.pdf
│   ├── LICENSE.txt
│   └── README.txt
└── Proteus8/           # contains .hex and .pdsprj files
```

## Contents

### `latex/contents/`
The main LaTeX source files where the report itself is written — each exercise's write-up, schematic and answers to the problem (all in `bai_2.tex`).

### `latex/main_code/`
Plain C source code for each exercise, saved as `.txt` files (`ex01.txt` through `ex10.txt`). These are the pure code listings referenced/included in the report, separate from the LaTeX formatting. In order to use it, paste the code in the STM32CubeIDE application (particularly in `Core/Src/main.c`)

### `latex/pictures/`
All images used throughout the report — illustrations, schematics, etc.

### `Proteus8/`
Proteus simulation files for each exercise:
- **`.hex`** — compiled hex output used for STM32F103C6.
- **`.pdsprj`** — the Proteus project file containing the circuit schematic and simulation setup.

Each exercise (`ex_01` through `ex_10`) has its own `.hex` files. In this lab session, we just use 2 `.pdsprj` through the whole session.

## Building the Report

The report `Nguyễn Đức Phi Long_2452689_CC04_Lab 02.pdf` is compiled from `latex/main.tex` as the final version.