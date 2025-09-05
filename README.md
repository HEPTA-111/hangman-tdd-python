# Hangman — TDD Python

A Hangman game implemented using Test-Driven Development (pytest).  
Two levels:
- Basic: single word
- Intermediate: phrase (spaces/punctuation shown)

Features
- Words/phrases come from dictionary files in `words/`
- 15-second timer per guess (visible countdown). Timeout deducts a life.
- Correct guesses reveal all occurrences of the letter.
- Wrong guesses deduct a life. Player loses on 0 lives.
- Player can attempt full-word/phrase guesses (wrong full guess deducts life).
- Tests designed for TDD and CI.

## Quick start
1. Create and activate virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   # .venv\Scripts\Activate.ps1 on Windows PowerShell
