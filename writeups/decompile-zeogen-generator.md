---
title: Zeogen Generator
date: 2024-08-03
tags: ["writeup"]
Description  : "decompile everything"
---

## Source of executable
- Guy send me this EXE file on Discord
- Executable was a supposed Amazon Storecard generator

## Reversing steps
- Using `strings`, we can identify PyInstaller was used to convert the PY script to EXE
- Using `PyInstxtractor`, we can decompile it into the python bytecode files
- Using `pycadas`, we can decompile python bytecode files into readable instructions!
- Tool appears to be just a RNG and generating fake card details
- The file "zeogen.pyc" stood out, a quick Google search shows its on GitHub!
- Comparing the sources, seems like it has been rebranded and sold multiple times

## Conclusion
- Don't buy stupid scripts LOL
- Open source is used by scammers too!

.
