<div align="center">
  <img src="./Neon Blue Digital Design Engineer Banner.png" width="100%" alt="Mohamed Abdulraziq - Digital IC Design Engineer">
</div>

<br>

<h2 align="center">Mohamed Abdulraziq</h2>
<h3 align="center">Digital IC Design | RTL Design | SystemVerilog | Computer Architecture</h3>

<p align="center">
  Electronics and Communications Engineering graduate focused on designing, implementing, and verifying digital hardware architectures.
</p>

I work across RTL design, microarchitecture, functional verification, and FPGA/ASIC implementation flows. My interests include parameterized hardware design, processor and accelerator architectures, on-chip communication, clock-domain crossing, and memory systems.

---

## Project Portfolio

### Published GitHub Projects

#### 1. [Multi-Clock Digital System](https://github.com/mohamed-abdulraziq/Multi-Clock-Digital-System)

A modular digital system integrating UART communication, an asynchronous FIFO, a system controller, a register file, an ALU, and clock/reset management. The architecture operates across separate reference-clock and UART-clock domains.

**Architecture and RTL work**
- Integrated a system controller that decodes UART-received commands and sequences register-file and ALU operations.
- Implemented UART RX/TX datapaths, including serial sampling/transmission, parity checking, and framing checks.
- Connected an asynchronous FIFO to transfer information between independently clocked domains.
- Integrated a configurable register file and an ALU supporting arithmetic, logic, comparison, and shift operations.
- Included clock dividers/gating, reset synchronizers, data synchronization, and FIFO pointer synchronization.

**Implementation evidence**
- Repository includes synthesis, scan DFT, Formality, and physical-design report summaries.
- The published reports document mapped area and timing, equivalence comparison results, scan statistics, and post-route timing/physical checks.
- Each reported metric is accompanied by its scope and limitations in the project documentation.

**Technologies:** Verilog/SystemVerilog · UART · Asynchronous FIFO · CDC · ALU · Register File · Design Compiler · Formality · Cadence Encounter

---

#### 2. [Parameterized Output-Stationary Systolic Matrix Multiplier](https://github.com/mohamed-abdulraziq/Parameterized-Systolic-Matrix-Multiplier)

A parameterized N × N SystemVerilog accelerator for signed matrix multiplication, using an output-stationary dataflow. Each Processing Element (PE) owns one output matrix element and accumulates its partial sum locally while operands propagate through the array.

**Architecture and RTL work**
- Designed a configurable PE array with signed multiply-accumulate datapaths.
- Implemented horizontal propagation of A operands and vertical propagation of B operands.
- Developed an operand/control skew network to align matching operands at each PE.
- Propagated valid, first, and last markers alongside the data.
- Added global-enable stall handling across the PE pipeline, skew network, and output collector.
- Implemented ordered row collection, per-row completion tracking, and a matrix-done pulse.

**Verification and implementation evidence**
- Self-checking back-to-back regression across four parameter configurations, plus reset/recovery stress testing.
- The supplied regression reports 380 completed matrices across the four configurations, with no output errors.
- Includes a Synopsys Design Compiler synthesis setup and reports for the default 5×5 configuration.
- The 7×7 configuration is functionally simulated; the repository explicitly separates architectural throughput estimates from measured implementation performance.

**Technologies:** SystemVerilog · Systolic Arrays · Processing Elements · MAC Datapaths · Pipelining · QuestaSim/ModelSim · Synopsys Design Compiler

---

#### 3. [Parameterized Multi-Slave APB Interconnect](https://github.com/mohamed-abdulraziq/Parameterized-APB-Interconnect)

A single-master, parameterized APB interconnect that connects a request interface to a configurable bank of memory-mapped APB RAM slaves through a centralized bridge.

**Architecture and RTL work**
- Implemented an APB bridge controlled by an IDLE / SETUP / ACCESS finite-state machine.
- Parameterized the data width, address width, slave count, and byte-strobe width.
- Used a generate-based structure to instantiate multiple RAM slave endpoints.
- Provided per-slave selection encoding, protection configuration, and memory depth.
- Supported byte-level writes through PSTRB.
- Implemented protection-mismatch and out-of-range address error responses.
- Aggregated the selected slave's PREADY, PRDATA, and PSLVERR responses and supported back-to-back requests.

**Verification and implementation evidence**
- Self-checking testbench covering normal reads/writes, partial-byte writes, address boundaries, invalid addresses, protection mismatches, back-to-back transfers, and randomized transactions.
- Supplied simulation result: **186 checks passed, 0 failed**.
- Supplied Vivado implementation timing summary reports positive setup, hold, and pulse-width slack against the 100 MHz target.
- The repository documents the timing evidence and clearly identifies unavailable utilization/source-flow artifacts.

**Technologies:** SystemVerilog · AMBA APB · Parameterized RTL · FSM Design · Memory Interfaces · Self-Checking Testbench · Vivado

---

### Additional Processor Design Project

#### MIPS Single-Cycle Processor

A separate RTL processor design project focused on a single-cycle MIPS architecture. It is part of my digital-design portfolio, but **a dedicated public GitHub repository has not been published yet**. Its project link will be added here when the source and documentation are released.

---

### Graduation & Team Project

#### Transformer FPGA Accelerator - Sponsored by STMicroelectronics Egypt

A team graduation project focused on designing and implementing a configurable FPGA-based accelerator for Transformer workloads.

**Architecture and implementation work**
- Contributed to defining the accelerator architecture and algorithms.
- Implemented and integrated the matrix multiplication unit.
- Integrated the accelerator as a custom AXI4-Lite IP.
- Worked on functional verification using QuestaSim, reference models, and constrained testbenches.
- Worked through FPGA implementation and bitstream-based hardware validation.
- The project architecture also includes the planned normalization and activation-function stages for Transformer operations.

**Technologies:** SystemVerilog · FPGA · Transformer Workloads · Matrix Multiplication · AXI4-Lite · QuestaSim · Vivado

---

## Technical Skills

| Area | Technologies and Concepts |
|---|---|
| **HDL** | Verilog, SystemVerilog |
| **RTL & Microarchitecture** | FSMs, pipelining, parameterized design, signed arithmetic, MAC datapaths |
| **Interfaces** | AMBA APB, AXI4-Lite |
| **Digital Systems** | UART, asynchronous FIFO, CDC, synchronizers, ALU, register files |
| **Verification** | QuestaSim, ModelSim, self-checking testbenches, reference models, directed and randomized testing |
| **FPGA** | AMD/Xilinx Vivado, synthesis, implementation, timing analysis |
| **ASIC Flow** | Synopsys Design Compiler, Formality |

---

## Community & Leadership

**Director - IEEE Helwan Student Branch, Communications Society (ComSoc)**

- Helped introduce Digital IC Design and Analog IC Design learning tracks.
- Contributed to organizing technical training, competitions, and student activities.
- Delivered Digital IC Design instruction and supported the development of new technical volunteers.

---

## Connect With Me

- **LinkedIn:** [Mohamed Abdulraziq](https://linkedin.com/in/mohamed-abdulrazeq-638871274)
- **GitHub:** [@mohamed-abdulraziq](https://github.com/mohamed-abdulraziq)

---

<p align="center"><i>Designing digital hardware from architecture to implementation.</i></p>
