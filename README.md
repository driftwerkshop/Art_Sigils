
Sigilizer

This project provides a Python-based tool to generate animated sigils from phrases using their hexadecimal representation. The sigils are drawn in a circular pattern, where each point represents a character of the phrase, and the animation gradually reveals the sigil step by step.

Features:
- Hexadecimal Conversion: Converts any phrase into its hexadecimal equivalent.
- Sigil Drawing: Generates a circular sigil from the hexadecimal representation of the phrase.
- Animation: Creates an animated GIF that gradually draws the sigil point by point.

Dependencies:
The following Python libraries are required to run this project:
- matplotlib
- numpy
- pillow

You can install them using pip:
pip install matplotlib numpy pillow

Usage:

Example: Generate a Sigil for a Phrase
You can use the provided functions to generate and animate a sigil for any phrase. Here's an example:

# Import the necessary functions
from sigilizer import animate_sigil

# Define the phrase you want to sigilize
target_phrase = "Every phrase has a unique sigil."

# Output filename for the animated GIF
output_gif = "target_sigil.gif"

# Generate and save the animated sigil
animate_sigil(target_phrase, output_gif)

This will save an animated GIF of the sigil for the phrase in the current directory.

Customization:
- Phrase to Sigil: You can customize the phrase to generate different sigils.
- Output: The output filename for the GIF can be customized as needed.

Example Output:
The repository includes a sample GIF of the sigil for the phrase: "Every phrase has a unique sigil."

License:
This project is licensed under a Creative Commons Attribution 4.0 International License. You are free to:
- Share: Copy and redistribute the material in any medium or format.
- Adapt: Remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:
- Attribution: You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

For more information, visit: https://creativecommons.org/licenses/by/4.0/
