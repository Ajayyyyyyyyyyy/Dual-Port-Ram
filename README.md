# Dual-Port-Ram

What is Dual Port RAM?
Dual Port RAM is a type of memory that allows two independent accesses at the same time—either reads, writes, or both—through two separate ports (Port A and Port B).

Why Dual Port RAM?
* In digital systems (like processors or FPGA designs), sometimes two units need to access memory at the same time:
* A processor may write data while a peripheral reads it.
* Two blocks in a system may want to communicate via shared memory without waiting.
* Dual Port RAM enables parallelism and faster communication.

Types of Dual Port RAM:
Type	                        Description
True Dual Port RAM	          Both ports can read or write simultaneously.
Simple Dual Port RAM	        One port is read-only, and the other is write-only.

