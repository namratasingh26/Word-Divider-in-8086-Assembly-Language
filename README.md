## Description  
This is an 8086 Assembly Language program that reads a user-inputted string, processes each character, and displays them separated by commas. It uses DOS interrupts for input and output operations.  

## Features  
- Prompts the user to enter a word.  
- Reads the input string.  
- Displays each character with a comma separator.  
- Ensures proper formatting with a newline before and after processing.  

## Requirements  
- An emulator like *DOSBox* or *EMU8086* to run the program.  
- MASM or NASM assembler for assembling and executing the code.  

## How It Works  
1. Displays a prompt message: "Enter a word:"  
2. Reads user input and stores it in a buffer.  
3. Iterates through each character in the buffer.  
4. Displays each character followed by a comma.  
5. Ends with a newline and exits.  

## Assembly Instructions Used  
- *INT 21h*: DOS interrupt for I/O operations.  
- *MOV AH, 09h*: Display a string.  
- *MOV AH, 0Ah*: Read a string from the user.  
- *MOV AH, 02h*: Display a single character.  
- *MOV AH, 4Ch*: Terminate the program.  

## Running the Program  
1. Assemble the code using MASM or NASM.  
2. Link the object file.  
3. Run the executable in a DOS environment (DOSBox recommended).  

## Example Output  

Enter a word: Hello
H,e,l,l,o,


## License  
This project is open-source and free to use for educational purposes.
