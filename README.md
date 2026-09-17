# Andrew Chen

**MS ECE @ Carnegie Mellon | Computer Architecture · RTL Design · ASIC/FPGA**

I build processors and digital hardware from RTL through implementation. Currently exploring superscalar execution, branch prediction, and the performance/complexity tradeoffs behind microarchitectural design.

Previously Design Lead @ [ASICWRU — CWRU CHIPS ASIC Design](https://asicwru.netlify.app).

## Featured Projects

### [RISC-V v3 — 2-Way Superscalar RV32I](https://github.com/AxC1271/RISCV-v3) · In Progress

2-way superscalar in-order processor written in SystemVerilog.

* 2-wide fetch/dispatch with dual integer ALUs and 4R/2W register file
* Multi-lane forwarding, dependency detection, structural hazard handling, and instruction replay
* Always Not-Taken, Bimodal, and Gshare branch prediction
* ~**1.85 IPC** on independent instruction streams, approaching the 2.0 IPC theoretical maximum
* Benchmarking predictor accuracy and IPC across Fibonacci, Binary Search, Insertion Sort, GCD, and String Search
* Evaluating predictor performance vs. implementation complexity for synthesis and timing closure

### [RISC-V v2 — 5-Stage Pipelined RV32I](https://github.com/AxC1271/RISCV-v2)

5-stage in-order RISC-V processor with forwarding, hazard detection, and split L1 caches.

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
