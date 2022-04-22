# Word Count, Python Edition
This program will open a file and read its contents, then output: a word count, the longest word, 
and the average word length. It will be written in python.

## Requirements
- The program will not take any input from the keyboard.
- The file to be processed will be specified when the program is called.
- Words will be split by any character in the following string: `" \t\n\r.!?,"`.
- Words will have their ends stripped of the following characters:
`"!?,.- :;'()[]{}@#$%^&*_+=/<>`~ \"\t\n\r"`.
  - If one of these characters appears in the middle of a word, like the apostrophe in "don't",
  it must be left alone.
  - Numbers and words containing digits shall not be counted.
  - Empty strings must not be counted.
- The word count is a whole number.
- The longest word must be enclosed in double-quotation marks.
- The average word length must always show one decimal place.
- Input files are provided.
- Only submit your source code.

## Sample Run
input.HERBERT
```
❯ python3 wsuid_hwxtra02.py input.HERBERT
There are 61 words
The longest word is "obliteration"
The average word length is 3.9 letters
```

## Hints
- Functions are always good, but python will provide most of what you'd want.
  - You might still need to write at least one function.
- Translate your algorithms, not your lines of code.
  - Since this is a python assignment, write python. Don't write transliterated C++.
- Look into `argparse` to have your python program take arguments on the command line.
  - The tutorial available from the official documentation should be enough to get you what you need.

## Reminders
- Name your file *wsuid*\_hwxtra02.py
- You are required to place a comment block at the top of the file. Refer to the Coding Guidelines
handout.
