# Unique Character Finder

This program finds the first unique character in each word of a given text.

## Problem Description

The algorithm follows these steps:

1. Receive the input text.
2. Split the text into separate words.
3. For each word, find the first character that is not repeated in that word.
4. Collect all these characters into a set.
5. Select the first unique character from the set (i.e., the character that is not used again in the set).
6. Return the selected unique character.

## Usage

The `find_unique_character(text)` function implements the algorithm described above. It takes a string `text` as input and returns the first unique character found.

Example usage:

```python
from unique_character_finder import find_unique_character

text = "The Tao gave birth to machine language. Machine language gave birth to the assembler."
result = find_unique_character(text)
print(result)  # Output: 'm'
