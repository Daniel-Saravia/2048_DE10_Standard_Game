2048 Game for DE10-Standard FPGA Board
Overview
This project is an implementation of the popular 2048 game, designed to run on the DE10-Standard FPGA board. It utilizes the board's LCD display to render the game's graphical interface and handle user inputs.

Key Features
Graphical LCD Interface: The game features a graphical interface displayed on the LCD screen of the DE10-Standard board.
Game Logic: Implements the core mechanics of the 2048 game, including tile movements and merging.
Hardware Interaction: Directly interacts with the hardware registers of the FPGA board for display and control.
File Structure
main.c: The entry point of the program, handling the initialization and main game loop.
gameLogic.c & gameLogic.h: Contains the core game logic and mechanics.
LCD_Driver.c & LCD_Driver.h: Manage the LCD display, including initialization and rendering functions.
LCD_Lib.c & LCD_Lib.h: Provide additional functionalities for the LCD display.
lcd_graphic.c & lcd_graphic.h: Handle graphical rendering on the LCD.
font.c & font.h: Define the fonts used in the game's display.
terasic_lib.c & terasic_lib.h: Include utility functions for the Terasic DE10-Standard board.
How to Run
Clone the repository to your local machine.
Compile the source code using the provided Makefile.
Load the compiled program onto the DE10-Standard FPGA board.
Interact with the game using the board's input peripherals.
License
This project is licensed under the terms of the MIT license.

Acknowledgments
Special thanks to Terasic Technologies Inc. for providing the base code for LCD interaction and hardware abstraction.
