# NATO Phonetic Alphabet Game

The NATO Phonetic Alphabet Game allows users to input a word and receive its corresponding phonetic code words using the NATO phonetic alphabet.

## Overview

The NATO phonetic alphabet is a spelling alphabet used by various organizations to spell out words over radio or telephone communication lines. Each letter in the alphabet is represented by a specific code word.

## How It Works

### 1. Setup

- Make sure you have Python installed on your system.
- Install pandas library using `pip install pandas`.
- Download or ensure you have the `nato_phonetic_alphabet.csv` file in the same directory as `nato_alphabet_game.py`.

### 2. Running the Game

1. Open `nato_alphabet_game.py` in your Python environment.
2. Run the script.
3. Enter a word when prompted. The word should only contain letters from the alphabet (A-Z).
4. The program will output the corresponding phonetic code words for each letter in the word.

### 3. Example

If you enter the word "Python", the program will output:
['Papa', 'Yankee', 'Tango', 'Hotel', 'Oscar', 'November']


### 4. Error Handling

If you input a word that contains characters other than letters (e.g., numbers or special symbols), the program will prompt you to enter only letters and recursively ask for input until a valid word is provided.

## Requirements

- Python 3
- pandas library

## File Structure

- `nato_alphabet_game.py`: Main script to run the NATO Phonetic Alphabet Game.
- `nato_phonetic_alphabet.csv`: CSV file containing the NATO phonetic alphabet mapping.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
