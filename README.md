# fasta2mif
+ my english is not well enough...
+ just copy ACGTU from .fasta to data_in.txt and run; then you will get a data.mif which you want
+ file of .fasta(file of gene sequence) change into file of .mif(memory initialization file)
+ we can use .mif when using fpga or somewhere else
+ you can choose whether add title of altera (for learning use only I guess)
+ gene sequence data in .mif is in type of 
```
-- Copyright (C) 2018  Intel Corporation. All rights reserved.
-- Your use of Intel Corporation's design tools, logic functions 
-- and other software and tools, and its AMPP partner logic 
-- functions, and any output files from any of the foregoing 
-- (including device programming or simulation files), and any 
-- associated documentation or information are expressly subject 
-- to the terms and conditions of the Intel Program License 
-- Subscription Agreement, the Intel Quartus Prime License Agreement,
-- the Intel FPGA IP License Agreement, or other applicable license
-- agreement, including, without limitation, that your use is for
-- the sole purpose of programming logic devices manufactured by
-- Intel and sold by Intel or its authorized distributors.  Please
-- refer to the applicable agreement for further details.

-- Quartus Prime generated Memory Initialization File (.mif)

WIDTH=2;
DATA_RADIX=1640;

ADDRESS_RADIX=UNS;
DEPTH=UNS;

CONTENT BEGIN
	0  :   0;
	1  :   3;
	2  :   1;
	3  :   1;
	4  :   0;
    .
    .
    .
	1636  :   3;
	1637  :   2;
	1638  :   3;
	1639  :   1;
END;
```
