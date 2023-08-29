# Logisim-CPU-Simulator
A 8 bit CPU project made using Logisim with a simple instruction set (add, halt, move, read, write).


## Requirements
* To run the simulation you need [logisim](http://www.cburch.com/logisim/) version 2.7.1 (might work on newer versions)
* requires java

## How to run
* Run logisim
* Select file>open and then select the CPU.circ file
* optionally load my program (simple adder) by clicking on the instruction memory, select contents > open and select the "instr" file
* optionally load the values I used in testing by clicking on the RAM with the right mouse button > edit content and select the "RAM" file
* That's it!


The instruction memory already comes preloaded. The program contained within adds all values within the RAM. 

I added a RAM file if you wish to quickly load the RAM with the values 1, 2 , 3 and 4. The CPU should return the sum 10 in the first RAM address.

You can add custom values and instructions if you desire to run on the computer. The txt file "Instruction IDs" contains the opcodes for the instructions.

This project was made in 2021.



