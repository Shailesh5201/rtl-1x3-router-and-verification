# rtl-1x3-router-and-verification
This project involves the design and verification of a **1x3 Router** using Verilog for RTL design and UVM (Universal Verification Methodology) for verification. The router is responsible for routing data packets from one input port to one of three output ports based on a routing logic.

![block dia](https://github.com/user-attachments/assets/c72289ab-12a9-4dcc-933d-9a0d5ab4a5c2)

**Functionality:-**

1.The 1x3 Router takes a single input data stream and routes it to one of three output ports based on a control signal.

2.The router supports packet-based communication, where each packet contains a header (for routing information) and a payload (data).

3.The routing decision is made based on the header of the incoming packet.

4.The router ensures that data is correctly routed to the intended output port without loss or corruption.

**Components:-**

**1.Input Port**: Receives data packets.

**2.Routing Logic**: Decides the output port based on the packet header.

**3.Output Ports**: Three output ports to route the data.

**4.Arbiter**: Ensures fair access to output ports in case of contention.

**5.FIFO Buffers**: Temporary storage for incoming packets to handle data flow.

**Steps Covered in the Project:-**

**1.Block Diagram**:

- Created a high-level block diagram of the 1x3 Router, illustrating the input port, routing logic, arbiter, FIFO buffers, and output ports.
 
- Defined the interfaces and data flow between components.

**2.RTL Design using Verilog**:

- Designed the RTL (Register Transfer Level) implementation of the router using Verilog.
 
- Implemented the routing logic, FIFO buffers, and arbiter.

- Ensured the design meets timing and functional requirements.

**3.Verification Plan**:

- Developed a comprehensive verification plan to validate the functionality of the router.
 
- Identified test scenarios, including normal operation, edge cases, and error conditions.
 
- Defined coverage metrics to ensure all aspects of the design are tested.

**4.UVM-Based Verification**:

- Built a UVM testbench to verify the RTL design.
 
- Created UVM components such as agents, drivers, monitors, and scoreboards.
 
- Developed test cases to validate the routing logic, FIFO behavior, and arbiter functionality.
 
- Achieved functional coverage and ensured the design is bug-free.

**Key Features:-**

- Modular and scalable design.
 
- Efficient routing logic with minimal latency.
 
- UVM-based verification for robust and reusable testbenches.
 
- Comprehensive test coverage for all functional scenarios.

**Tools Used:-**

**Simulation**: ModelSim/QuestaSim or any Verilog simulator.

**Verification**: UVM framework.

**Design**: Verilog for RTL design.

**Documentation**: Block diagrams and verification plans.
