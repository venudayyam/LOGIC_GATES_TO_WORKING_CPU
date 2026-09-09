# LOGIC_GATES_TO_WORKING_CPU

Works best with Logisim 2.7.1 (https://sourceforge.net/projects/circuit/) and requires Java Runtime (https://www.java.com/en/download/manual.jsp) to run.

## 1. Open the following file from this project in Logisim. 

       CPU_LEVEL_ONE/CIRCUIT_DESIGN/8BIT_CPU.circ 



## 3. Run the simulation to explore the CPU.
 1. Press Global Reset a few times before Loading Machine Code and Running/Clocking CPU.
 2. If you see any error(red) connections, reload supporting files (such as *REGISTERS.circ*) a few times until they disappear.
 3. Load test code (Machine Code) to memory.
    1. Open the required CPU circuit (*CPU_NON_IO or CPU_IO*) in *8BIT_CPU.circ*
    2. Double-click FETCH to open the FETCH sub-circuit
    3. Locate the LOGISIM_RAM used as instruction memory and load the corresponding machine code from TEST_CODE folder.
    4. Return from FETCH to main circuit.
4. Clock/Run the CPU
   1. FOR NON IO CPU:<br>
    Verify the final values in registers, data memory, stack, etc.. (with values in file *TEST_CODE_NON_IO.txt*)
   2. FOR IO CPU:<br>
    Enter random text on keyboard before running CPU. Sit back while the program prints the input text onto display character by character. Deliberately stop the CPU afterwards as it waits infinitely for key input.
    
<br>
<br>

*Supporting circuit files (such as *REGISTERS.circ, 8BIT_ALU.circ*) are included in the project. If Logisim does not load them automatically, kindly select them from the same directory.

*For details on opcodes, ISA, Timing and Execution States kindly check out the following folder.

    CPU_LEVEL_ONE/DOCUMENTATION/

*For further assistance contact me through email. Thank You. 
<br><br><br>
Copyright © 2026 [VENUGOPAL REDDY DAYYAM]. All rights reserved.
