# AdaGrams – Python Word Game

## Project Overview

AdaGrams is an interactive command-line word game built with Python, inspired by classic word games like Scrabble.

Players receive a randomly generated set of 10 letters and are challenged to create the highest-scoring word possible using only the available letters.

The application validates player submissions, calculates scores based on individual letter values, and allows players to complete multiple rounds. At the end of the game, it identifies the highest-scoring word using predefined scoring and tie-breaking rules.

## Technologies Used

- **Python 3** – Core game logic, data structures, and user interaction
- **Python Standard Library** – Random letter generation and data manipulation
- **Pytest** – Unit testing and validation of game functionality
- **Command-Line Interface (CLI)** – Interactive gameplay through the terminal

## Key Features

- Randomly generates 10 letters using a weighted letter distribution
- Validates submitted words against the available letters, including letter frequency
- Calculates scores based on Scrabble-inspired letter values
- Awards bonus points for words containing 7–10 letters
- Supports multiple rounds of gameplay
- Identifies the highest-scoring word using custom tie-breaking logic

## What I Learned

This project strengthened my understanding of Python fundamentals and developing reusable functions to solve programming challenges.

I gained hands-on experience with:

- Working with lists, strings, dictionaries, and tuples
- Implementing conditional logic and loops to manage gameplay
- Using randomization and weighted letter distributions
- Designing algorithms for input validation and score calculation
- Handling user input through the command line
- Breaking complex problems into smaller, testable functions
- Writing and running unit tests with Pytest

## Getting Started

Clone the repository:

```bash
git clone https://github.com/fabi01a/adagrams-py.git
cd adagrams-py
```

Create and activate a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the completed game:

```bash
python3 main.py 4
```

Run the automated tests:

```bash
pytest
```

## Video Demo



https://github.com/user-attachments/assets/6109cdce-00a8-4caa-bc6f-b85377247697



The demo showcases random letter generation, word validation, scoring, multiple rounds of gameplay, and the final highest-scoring word.
