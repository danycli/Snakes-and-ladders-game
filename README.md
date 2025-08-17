## 🎲 Snake & Ladders in C

Welcome to the Snake & Ladders by DANY — a lightweight, fun, and interactive CLI-based board game written in pure C, designed to bring the classic childhood game to your terminal! 🐍🪜

## Features

- Two-Player Gameplay → Player 1 (♞) vs Player 2 (♛)

- Dice Roll Simulation 🎲 with Unicode dice symbols ⚀ ⚁ ⚂ ⚃ ⚄ ⚅

- Colorful Console Board → ASCII grid with ladders 🪜 and snakes 🐍

- Interactive Console UI → Centered, styled text with escape colors

- Simple Rules → Roll 6 to start, reach 100 to win 🏆

- Cross-Platform → Works on Windows/Linux (Windows requires conio.h)

## Preview
<img width="660" height="828" alt="Screenshot 2025-08-15 142208" src="https://github.com/user-attachments/assets/b556a3e7-499c-450f-b423-546d92bb316d" />

## Key	Action
SPACE	Start the game
ENTER	Roll the dice 🎲
6 (roll)	Required to start movement
🪜 Ladder	Jump forward
🐍 Snake	Slide backward

## Tech Stack

- C (ISO C90 style)

- ASCII + Unicode → for board, snakes, ladders, dice

- conio.h (getch()) → for key handling on Windows

- time.h + rand() → for dice randomization

- ANSI Escape Codes → for colorful console output

## Requirements

- Any C Compiler (MinGW, TDM-GCC, Turbo C, etc.)

- Windows/Linux terminal (with UTF-8 support)

- ANSI escape codes enabled (system("chcp 65001 > nul"); is already handled in code)

## Acknowledgements

- Designed & Developed by DANY
- Inspired by the classic Snake & Ladders board game 🐍
