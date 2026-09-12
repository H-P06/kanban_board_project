# C Board Management Program

A command line C application for managing a board made up of lists and items.

## Features

- Display the current board and its items.
- Load a board from a text file.
- Save the current board to a text file.
- Add, edit, and delete lists.
- Add, edit, and delete items within lists.
- Uses dynamically allocated linked-list structures.

## Project Structure

- `main.c` – Contains the main menu, program setup, and user interaction.
- `display.h` – Displays the board and its items.
- `editBoard.h` – Adds, edits, and deletes lists.
- `editList.h` – Adds, edits, and deletes items.
- `LoadFromFile.h` – Loads board data from a text file.
- `SaveToFile.h` – Saves board data to a text file.

## Notes

The program stores the board using linked lists and dynamically allocated memory. Board data can be saved and loaded using text files.
