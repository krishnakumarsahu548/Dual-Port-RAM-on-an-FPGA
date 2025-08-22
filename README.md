# Dual-Port-RAM-on-an-FPGA
A Dual Port RAM is a type of memory that has two independent ports, allowing simultaneous read and write operations (or two reads, or two writes) from different addresses. 
 # What is a Dual Port RAM?
A Dual Port RAM has two sets of address, data, and control lines:

Port A: Used for one set of operations (e.g., write or read).
Port B: Used for another set of operations (e.g., read or write).
This dual-port nature enables parallel access, unlike a Single Port RAM where only one operation can occur per cycle.

Key Features:

Two Ports: Each port has its own address, data input/output, and control signals (e.g., write enable).
Synchronous: Operations are typically synchronized with a clock.
Conflict Resolution: If both ports attempt to write to the same address simultaneously, arbitration logic is needed (not included in this basic example).
Applications: Used in FIFO buffers, image processing, and multi-threaded systems.
