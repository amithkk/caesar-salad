# CaesarSalad
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Famithkk%2Fcaesar-salad.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Famithkk%2Fcaesar-salad?ref=badge_shield)



![](https://i.imgur.com/kXnquKG.gif)

Command Line tool to crack ROT-n Caesar Ciphers given a sample of text
Wordlist use can be substituted with a wordlist of your choice, provided that the words are newline seperated

This repository uses the [Moby Word List](https://github.com/dwyl/english-words)

Two letter words are ignored.


## Installation:

From PyPi: `pip install caesar-salad`


## Usage

Run by using `caesar-salad` on the terminal

```
caesar-salad [-h] [-d] [-w] [STR]

positional arguments:
  STR                ROT-encoded string to decipher

optional arguments:
  -h, --help         show this help message and exit
  -d, --decode-only  Only output best guess of decoded string
  -w, --which-rot    Find best guess of type of encoding
```


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Famithkk%2Fcaesar-salad.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Famithkk%2Fcaesar-salad?ref=badge_large)