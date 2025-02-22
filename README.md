# RAM_DESIGN


NAME:Abhilash 
COMPANY:Codetech It Solution 
ID:COD1234 
DOMAIN:VLSI 
DURATION:JAN - MARCH 2025 
MENTOR: NEELA SANTHOSH

This project implements and tests a simple synchronous RAM (Random Access Memory) module in Verilog. Let’s break down the key parts:

  Synchronous RAM Module
        Parameters:
            DATA_WIDTH: Size of the data word (e.g., 8 bits).
            ADDRESS_WIDTH: Number of address bits (e.g., 4 bits for 16 locations).
            DEPTH: Total number of memory locations.
        Ports:
            clk: Clock signal, ensures synchronous operations.
            we: Write enable, controls whether data is written to memory.
            addr: Memory address for read/write.
            din: Data input for writing.
            dout: Data output for reading.
        Behavior:
            On the rising edge of the clock:
                If we is high, data is written to the memory location.
                Data from the addressed location is always read and assigned to dout.

   Testbench
        Generates the clock signal.
        Applies test cases for write and read operations.
        Uses $display to show read data, verifying the RAM’s behavior.

   Project Flow
        Write the synchronous RAM module.
        Develop a testbench to simulate the RAM’s functionality.
        Simulate and check if write and read operations work correctly.


        
  #output

  
