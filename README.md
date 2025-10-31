PC increments by one because I based this off of the the block diagram.
Instruction memory reads the address based off of the the 4 most signifigcant bits.
Looked at module test bench, clock is attached mainly drives the adder, instruction memory and latch.
PC not driven by clock edge because it caused a sync issue where two diiferent addresses would be pushed out when psrc was lo.

Top.v is the Fetch.v of this assignment
