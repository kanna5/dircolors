# dircolors

Based on [seebi/dircolors-solarized](https://github.com/seebi/dircolors-solarized)

A few modifications were made to make it work better with common color schemes other than Solarized.

1. Do not rely on terminal emulators to render bold text in bright colors. Instead, use color code for bright colors (90~97) explicitly.
   (see https://en.wikipedia.org/wiki/ANSI_escape_code#SGR)
2. Do not assume the use of Solarized palette. "Bright colors" really means bright colors.
