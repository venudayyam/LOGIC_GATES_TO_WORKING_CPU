# LOGIC_GATES_TO_WORKING_CPU

Works best with Logisim 2.7.1 (https://sourceforge.net/projects/circuit/) and requires Java Runtime (https://www.java.com/en/download/manual.jsp) to run.

## 1. Open the following file from this project in Logisim. 

       CPU_LEVEL_ONE/CIRCUIT_DESIGN/8BIT_CPU.circ 



## 2. Getting CPU Simulation ready.
 * Enable Simulation if not done by default on file open.
 
 * Open the required CPU circuit (CPU_NON_IO or CPU_IO) in 8BIT_CPU.circ 
   
 * Press RESET Pin (Global) a few times before Loading Machine Code and Running/Clocking CPU.
   
 * If you see any red/error connections: Right-click the supporting files (REGISTERS.circ, 8BIT_ALU.circ) and select Reload Library. Then press Reset Pin. Repeat this until no errors.
 ## 3. Load test code (Machine Code) to memory.
* Open the required CPU circuit (*CPU_NON_IO or CPU_IO*) in *8BIT_CPU.circ
  
* Double-click FETCH to open the FETCH sub-circuit
  
* Locate the LOGISIM_RAM used as instruction memory and load the corresponding machine code from TEST_CODE folder.
  
* Return from FETCH to main circuit.
      
## 4. Clock/Run the CPU
   * FOR NON IO CPU:<br>
    Verify the final values in registers, data memory, stack, etc.. after the cpu halt. (with/against values in file *TEST_CODE_NON_IO.txt*)
   * FOR IO CPU:<br>
    Enter random text on keyboard before running CPU. Sit back while the program prints the input text onto display character by character. Deliberately stop the CPU afterwards as it waits infinitely for key input.
    
<br>
<br>

*Supporting circuit files (such as *REGISTERS.circ, 8BIT_ALU.circ*) are included in the project. If Logisim does not load them automatically, kindly select them from the same directory.

*For details on opcodes, ISA, Timing and Execution States kindly check out the following folder.

    CPU_LEVEL_ONE/DOCUMENTATION/

*For further assistance contact me through email. Thank You. 
<br><br><br>
Copyright © 2026 [VENUGOPAL REDDY DAYYAM]. All rights reserved.
