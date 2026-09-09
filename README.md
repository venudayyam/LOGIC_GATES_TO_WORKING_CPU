# LOGIC_GATES_TO_WORKING_CPU

Works best with Logisim 2.7.1 (https://sourceforge.net/projects/circuit/) and requires Java Runtime (https://www.java.com/en/download/manual.jsp) to run.

## 1. Open the following file from this project in Logisim. 

       CPU_LEVEL_ONE/CIRCUIT_DESIGN/8BIT_CPU.circ 

## 2. Load test code (Machine Code) to memory.

   1. Open the required CPU circuit (*CPU_NON_IO or CPU_IO*) in *8BIT_CPU.circ*
   2. Double-click FETCH to open the FETCH sub-circuit
   3. Locate the LOGISIM_RAM used as instruction memory and load the corresponding machine code from TEST_CODE folder.
   4. Return back from FETCH to main circuit.

## 3. Run the simulation to explore the CPU.

<br>
<br>

*Supporting circuit files (such as *REGISTERS.circ, 8BIT_ALU.circ*) are included in the project. If Logisim does not load them automatically, kindly select them from the same directory.

*For details on opcodes, ISA, Timing and Execution States kindly check out the following folder.

    CPU_LEVEL_ONE/DOCUMENTATION/
