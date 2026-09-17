# Andrew Chen

**MS ECE @ Carnegie Mellon | Computer Architecture · RTL Design · ASIC/FPGA**

I build processors and digital hardware from microarchitecture through RTL and implementation. Currently working on a 2-way superscalar RISC-V processor and an INT8 neural-network accelerator.

Previously Design Lead @ [ASICWRU — CWRU CHIPS ASIC Design](https://asicwru.netlify.app).

## Featured Projects

### [RISC-V v3 — 2-Way Superscalar RV32I](https://github.com/AxC1271/RISCV-v3) · In Progress

2-way superscalar in-order processor exploring instruction-level parallelism and branch prediction.

* 2-wide fetch/dispatch, dual ALUs, 4R/2W register file, multi-lane forwarding, and instruction replay
* Always Not-Taken, Bimodal, and Gshare branch prediction
* ~**1.85 IPC** on independent instruction streams, approaching the theoretical 2.0 IPC maximum
* Comparing predictor accuracy, IPC, and implementation complexity across application workloads
* Moving toward synthesis, timing analysis, and physical implementation

### mini-NPU — INT8 Systolic Accelerator · Early Development

Building a custom INT8 neural processing unit in SystemVerilog around a planned **8×8 systolic MAC array** for matrix-heavy inference workloads.

The current work is focused on the parameterized INT8/INT32 processing element and the dataflow required to scale it into a systolic array. The project will explore array utilization, tiling, data reuse, memory bandwidth, and the gap between theoretical and sustained compute throughput.

**Target:** 64 MACs/cycle · INT8 operands · INT32 accumulation · SkyWater 130nm

### [RISC-V v2 — 5-Stage Pipelined RV32I](https://github.com/AxC1271/RISCV-v2)

5-stage in-order processor with forwarding, hazard detection, and split L1 caches.

**58.8 MHz post-synthesis · 85 MHz FPGA · 0.64–0.76 IPC**

Direct-mapped I-cache and 2-way set-associative write-back D-cache, with synthesis and static timing analysis targeting SkyWater 130nm.

### [CWRU CPU — RISC-V ASIC](https://github.com/john-paul-sm/ASICWRU_SimpleCounter)

Led an undergraduate design team through RTL development and tapeout of a single-cycle RISC-V processor via Tiny Tapeout.

[View GDS →](https://gds-viewer.tinytapeout.com/?model=https://john-paul-sm.github.io/ASICWRU_SimpleCounter/tinytapeout.oas&pdk=gf180mcuD)

### [Tiny Pong — SkyWater 130nm](https://github.com/AxC1271/Tiny-Pong)

VGA Pong controller implemented in Verilog and taped out on SkyWater 130nm through Tiny Tapeout.

[View GDS →](https://axc1271.github.io/TinyPong/)

### [STM32 Development Board](https://github.com/AxC1271/STM32-DevBoard)

Custom STM32F103 development board designed in KiCad and fabricated at JLCPCB, with FPGA-based UART validation.

## Tools

**RTL:** SystemVerilog · Verilog · VHDL · RISC-V Assembly
**EDA:** Vivado · Yosys · OpenSTA · SymbiYosys · Icarus Verilog · KiCad
**Software:** C · Python · Bash · Git · Linux · Docker

## Outside Hardware

Needle felting, poetry, music, baking, skateboarding, chess, reading, and handstand push-ups.
