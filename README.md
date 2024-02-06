![image](https://github.com/Daniel-Saravia/2048_DE10_Standard_Game/assets/108732138/b944b09d-c37b-4308-8e1c-267181dfebd3)

![image](https://github.com/Daniel-Saravia/2048_DE10_Standard_Game/assets/108732138/dfd517ee-bf83-46bc-97f2-d10224ed323c)

2048 FPGA Game for DE10-Standard
Overview
This project brings the addictive 2048 puzzle game to the DE10-Standard FPGA board, showcasing an engaging blend of software engineering and hardware interaction. Leveraging the board's LCD display, this implementation offers a graphical interface for real-time gameplay, making efficient use of the FPGA's capabilities for handling user inputs and rendering.

Key Features
Graphical LCD Interface: A vivid and responsive graphical interface on the DE10-Standard's LCD screen, enhancing the gameplay experience.
Game Logic: Faithfully implements the 2048 game's core mechanics, such as tile movements and merging, providing a challenging yet intuitive puzzle-solving experience.
Hardware Interaction: Direct manipulation of the FPGA board's hardware registers enables precise control over the display and input mechanisms, offering a seamless interaction between the player and the game.
File Structure
plaintext
Copy code
- main.c: Serves as the program's entry point, orchestrating the game's initialization and main loop.
- gameLogic.c & gameLogic.h: Define the game's mechanics and rules.
- LCD_Driver.c & LCD_Driver.h: Responsible for managing the LCD display, including its initialization and rendering operations.
- LCD_Lib.c & LCD_Lib.h: Offer extended functionalities for the LCD display.
- lcd_graphic.c & lcd_graphic.h: Specialize in graphical rendering on the LCD.
- font.c & font.h: Contain font definitions for the game's text elements.
- terasic_lib.c & terasic_lib.h: Provide utility functions specific to the Terasic DE10-Standard board.
Getting Started
Prerequisites
Ensure you have the following tools and resources available for a Windows environment:

Intel Quartus Prime: Download Link
DE10-Standard Board: Available with an educational discount at Terasic's Official Website
Putty for Windows: Download Link
FileZilla: Download Link
GCC Compiler: Installation Guide
Installation
Clone the repository to your local machine.
Compile the source code using the provided Makefile.
Load the compiled program onto your DE10-Standard FPGA board using Quartus Prime.
Running the Game
Interact with the game through the DE10-Standard board's input peripherals following the on-screen instructions. Enjoy the classic 2048 puzzle with the enhanced experience of hardware interaction.

Acknowledgments
Special thanks to Terasic Technologies Inc. for their foundational code, which significantly facilitated LCD management and hardware abstraction in this project.

