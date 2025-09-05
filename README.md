# Hangman — TDD Python

This project is a **Hangman game** implemented in Python using a **Test-Driven Development (TDD)** approach with `pytest`.

The game includes two difficulty levels to choose from:
-   **Basic**: Guess single words.
-   **Intermediate**: Guess phrases, where spaces and punctuation are revealed by default.

---

## Features

-   Words and phrases are dynamically loaded from dictionary files located in the `words/` directory.
-   A 15-second timer for each guess with a visible countdown adds a layer of challenge.
-   Running out of time on a guess automatically deducts one life.
-   Correct letter guesses reveal all occurrences of that letter in the answer.
-   Incorrect guesses deduct a life. The game ends when the player has 0 lives remaining.
-   Players have the option to guess the entire word or phrase at any time. An incorrect full guess will deduct one life.
-   The project includes a comprehensive suite of unit tests, enabling continuous integration and ensuring code reliability.

---

## Quick Start

Follow these steps to get the game running on your local machine.

### 1. Create and Activate a Virtual Environment

First, create a virtual environment to manage project dependencies.

```bash
python3 -m venv .venv