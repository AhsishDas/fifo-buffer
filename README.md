### fifo-verilog


1.A synchronous FIFO buffer is designed with verilog
2.The input data is of 32-bit and also the output data is of 32-bit
3.1-bit clock is used to clock the input
4.EN int the module section represents the enable pin
5.Rst in the input module is the active high reset
6.RD and WR are the variables to represent the read and write operations respectively

## FIFO Operation in the code


1. Two output lines are there as FULL and EMPTY
2. If the either of these two pins gets HIGH, it means the buffer is either full or empty
3. If RST is set, both the read counter and write counter initializes to 0
