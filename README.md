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

My portfolio includes standalone RTL designs, integrated digital systems, and team-based accelerator work. The projects below are grouped by where their source code and supporting material are available.

### Published GitHub Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/mohamed-abdulraziq/Multi-Clock-Digital-System">Multi-Clock Digital System</a></h3>
      <p>An integrated multi-clock digital system combining UART communication, an asynchronous FIFO, system controller, register file, ALU, and clock/reset management.</p>
      <ul>
        <li>Two clock domains with CDC structures and reset synchronization.</li>
        <li>UART RX/TX, FIFO buffering, ALU operations, and register-file control.</li>
        <li>Includes synthesis, scan DFT, Formality, and post-route implementation reports.</li>
      </ul>
      <p><b>Focus:</b> RTL integration · CDC · UART · FIFO · ASIC flow</p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/mohamed-abdulraziq/Parameterized-Systolic-Matrix-Multiplier">Parameterized Systolic Matrix Multiplier</a></h3>
      <p>A configurable output-stationary N × N systolic array for signed matrix multiplication, built from processing elements and an operand/control skew network.</p>
      <ul>
        <li>Parameterized PE array, reduction length, and accumulator width.</li>
        <li>Wavefront alignment, valid/first/last control propagation, and stall support.</li>
        <li>Self-checking regression across four parameter configurations.</li>
      </ul>
      <p><b>Focus:</b> Computer architecture · MAC datapaths · Pipelining · SystemVerilog</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/mohamed-abdulraziq/Parameterized-APB-Interconnect">Parameterized APB Interconnect</a></h3>
      <p>A single-master, parameterized multi-slave APB interconnect with a centralized bridge and configurable RAM endpoints.</p>
      <ul>
        <li>Three-state APB controller: IDLE, SETUP, and ACCESS.</li>
        <li>Byte-write strobes, per-slave protection, and address-range error handling.</li>
        <li>Self-checking testbench evidence: 186 checks passed, 0 failed.</li>
      </ul>
      <p><b>Focus:</b> AMBA APB · Bus interconnects · Parameterized RTL · Verification</p>
    </td>
    <td width="50%" valign="top">
      <h3>More RTL Design Work</h3>
      <p>Additional processor and digital-design work complements the published repositories, including a MIPS single-cycle processor project and reusable hardware blocks.</p>
      <ul>
        <li>UART transmitter/receiver and asynchronous FIFO.</li>
        <li>Clock divider, clock/reset control, and synchronizer structures.</li>
        <li>ALU and register-file blocks integrated in the multi-clock system.</li>
      </ul>
      <p><b>Note:</b> These modules are represented within the linked integrated-system repository where applicable; not every item has a separate public repository.</p>
    </td>
  </tr>
</table>

### Graduation & Team Project

#### Transformer FPGA Accelerator — Sponsored by STMicroelectronics Egypt

A team graduation project focused on the architecture and RTL implementation of an FPGA-based accelerator for Transformer workloads.

- Participated in defining the accelerator architecture and algorithms.
- Implemented and integrated the matrix multiplication unit.
- Integrated the accelerator as a custom AXI4-Lite IP.
- Worked on functional verification using QuestaSim, reference models, and constrained testbenches.
- Worked through FPGA implementation and bitstream-based hardware validation.

*The graduation project is separate from the standalone repositories listed above.*

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
| **ASIC Flow** | Synopsys Design Compiler, Formality, scan DFT, Cadence Encounter |

---

## Community & Leadership

**Director — IEEE Helwan Student Branch, Communications Society (ComSoc)**

- Helped introduce Digital IC Design and Analog IC Design learning tracks.
- Contributed to organizing technical training, competitions, and student activities.
- Delivered Digital IC Design instruction and supported the development of new technical volunteers.

---

## Connect With Me

- **LinkedIn:** [Mohamed Abdulraziq](https://linkedin.com/in/mohamed-abdulrazeq-638871274)
- **GitHub:** [@mohamed-abdulraziq](https://github.com/mohamed-abdulraziq)

---

<p align="center"><i>Designing digital hardware from architecture to implementation.</i></p>
