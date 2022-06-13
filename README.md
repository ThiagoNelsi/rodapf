# nzma

Live reload tool for basic c programming.

## Installation

`npm install -g nzma`

## Usage

`nzma ../path/to/file.c`

## Options

- `-i`, `--in`, `--input`:

  `nzma ../path/to/file.c -i input.txt`

  The same of manually running:

  `gcc ../path/to/file.c -o compiled.out && compiled.out < input.txt`

- `-o`, `--out`, `--output`:

  `nzma ../path/to/file.c -o output.txt`

  The same of manually running:

  `gcc ../path/to/file.c -o compiled.out && compiled.out > output.txt`

---

> The code will be recompiled and executed whenever the c file is changed or the input file is changed.

