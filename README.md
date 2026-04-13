# 🗺️ U.S. States Game

A fun geography quiz game built with Python — how many of the 50 U.S. states can you name from memory?

![Blank US Map](blank_states_img.gif)

## How it works

A blank map of the United States is displayed. You're prompted to type in state names one at a time. Each correct guess is written directly onto the map at that state's location. The game ends when you've named all 50 states — or type **Exit** to quit early.

When you exit, any states you missed are saved to missing_states.csv so you can study up for next time.

## Getting started

### Prerequisites

- Python 3.x
- [pandas](https://pandas.pydata.org/)

### Installation

`
git clone https://github.com/YOUR_USERNAME/us-states-game.git
cd us-states-game
pip install pandas
`

### Run the game

`
python main.py
`

## Files

| File | Description |
|------|-------------|
| main.py | Main game script |
| 50_states.csv | State names and their x/y coordinates on the map |
| lank_states_img.gif | The blank US map used as the game background |
| missing_states.csv | Auto-generated when you exit — lists states you didn't guess |

> missing_states.csv is generated at runtime and is listed in .gitignore.

## Built with

- [Turtle graphics](https://docs.python.org/3/library/turtle.html) — Python's built-in drawing library
- [pandas](https://pandas.pydata.org/) — for reading state coordinate data
