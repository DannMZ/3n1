# Project: Collatz Conjecture Batch Script

## Description
This batch script executes a sequence of calculations based on the Collatz conjecture (or 3n+1 problem). The script takes a user-inputted number and performs iterations until the number reaches 1. Additionally, it keeps track of the maximum value encountered during the process.

## Features
- Takes a user input (integer) and verifies it.
- Handles incorrect inputs and prompts again.
- Tracks the number of iterations.
- Displays the highest number encountered in the sequence.
- Allows enabling/disabling iteration output for better readability.

## Usage
1. Run the script by double-clicking the `.bat` file or executing it from the command line.
2. Enter a number when prompted.
3. The script will perform calculations following these rules:
   - If the number is even: divide by 2.
   - If the number is odd: multiply by 3 and add 1.
4. The script displays:
   - The input number.
   - The total number of iterations.
   - The highest number encountered during the sequence.
5. To enable/disable iteration output, type `on` or `off` when prompted.

## Example Output
```
(write off/on to disable/enable iterations output)
Number? 12
Iteration: 0 _ 12
Iteration: 1 _ 6
Iteration: 2 _ 3
Iteration: 3 _ 10
Iteration: 4 _ 5
...
---------------------------------
Number   is   12
Calculations = 9
Max number= 16
---------------------------------
Press any key to continue...
```

## Notes
- The script loops continuously, allowing multiple calculations without restarting.
- Uses basic batch scripting logic for user input validation.
- May not handle extremely large numbers efficiently due to batch scripting limitations.

## License
This project is open-source. Feel free to modify and use it as needed.

## Author
Mazarin

