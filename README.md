<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0a2a4a,100:00d4ff&height=210&section=header&text=Jeevanandh%20R&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=RTL%20Design%20Engineer%20%7C%20VLSI%20%7C%20RISC-V%20%7C%20FPGA&descAlignY=60&descSize=19&descColor=00d4ff&animation=fadeIn" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=2800&pause=1000&color=00D4FF&center=true&vCenter=true&multiline=true&width=750&height=80&lines=Designing+silicon%2C+one+clock+cycle+at+a+time+%E2%9A%A1;RISC-V+Cores+%7C+AXI4+%7C+APB+%7C+SPI+%7C+UART+%7C+FPGA;Actively+seeking+VLSI+%2F+RTL+Design+Internships+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jeevanandhr/)
[![Gmail](https://img.shields.io/badge/Email-Hire%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jeevanandh510@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-Download%20PDF-00D4FF?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://drive.google.com/file/d/1bVbQK60cJrhqG4bVwNaTJrVcys5PjVTZ/view?usp=drive_link)

</div>

---

## 🧬 Who Am I?

```verilog
module jeevanandh_r (
  input  wire  passion,
  input  wire  curiosity,
  output reg   production_ready_rtl,
  output reg   silicon_dreams
);
  // Identity
  localparam NAME     = "Jeevanandh R";
  localparam COLLEGE  = "B.E. ECE — Final Year | Madurai, India";
  localparam GOAL     = "RTL / VLSI Design Engineer";
  localparam STATUS   = "Open to Internships & Full-Time Roles";

  // Core Skills
  localparam HDL      = {"Verilog", "SystemVerilog"};
  localparam ARCH     = {"RISC-V Single-Cycle", "RISC-V 5-Stage Pipeline", "Mini SoC"};
  localparam BUS      = {"AXI4-Lite", "APB Master/Slave"};
  localparam PROTO    = {"SPI", "UART"};
  localparam TOOLS    = {"Xilinx Vivado", "ModelSim"};

  always @(posedge passion) begin
    production_ready_rtl <= design_rtl(curiosity, ARCH, BUS, PROTO);
    silicon_dreams       <= synthesize_and_place_route(production_ready_rtl);
  end

endmodule
```

> 🎯 I'm a **Final Year ECE student** obsessed with **RTL Design and Digital VLSI**.
> I've built everything from a **RISC-V pipelined processor** to a **full Mini SoC with AXI4-APB interconnect** — all from scratch in Verilog.
> I'm actively hunting for **VLSI / RTL Design internships and full-time roles** where I can turn logic into silicon.

---

## ⚡ Technical Stack

<div align="center">

| Domain | Skills |
|--------|--------|
| **HDL Languages** | Verilog · SystemVerilog |
| **CPU Architecture** | RISC-V ISA · Single-Cycle Core · 5-Stage Pipeline · Hazard Handling |
| **Bus Protocols** | AXI4-Lite (Master + Slave) · APB (Master + Slave) |
| **Serial Protocols** | SPI · UART |
| **EDA Tools** | Xilinx Vivado · ModelSim |
| **Design Concepts** | RTL Design · FSM · Booth Multiplication · Timer + Interrupt Logic |
| **Other** | Python · C · Git |

</div>

<br/>

<div align="center">

![Verilog](https://img.shields.io/badge/Verilog-RTL%20Design-00D4FF?style=for-the-badge)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-Testbench-6E40C9?style=for-the-badge)
![RISC-V](https://img.shields.io/badge/RISC--V-Processor%20Design-FF6B35?style=for-the-badge)
![AXI4](https://img.shields.io/badge/AXI4--Lite-Bus%20Protocol-0078D7?style=for-the-badge)
![APB](https://img.shields.io/badge/APB-Peripheral%20Bus-00897B?style=for-the-badge)
![Vivado](https://img.shields.io/badge/Xilinx%20Vivado-Synthesis-E01F27?style=for-the-badge)

</div>

---

## 🚀 Featured Projects

> Every project below is handcrafted in Verilog/SystemVerilog — no HLS, no IP black boxes.

---

### 🏆 Mini SoC — RISC-V + AXI4-Lite + APB

```
┌──────────────────────────────────────────────────────────────┐
│                       Mini SoC                               │
│                                                              │
│   ┌─────────────┐    AXI4-Lite     ┌──────────────────┐      │
│   │  RISC-V     │ ──────────────►  │   AXI-APB Bridge │      │
│   │  Core       │                  └────────┬─────────┘      │
│   │  (Master)   │                           │ APB            │
│   └─────────────┘              ┌────────────┼────────────┐   │
│                                │            │            │   │
│                             ┌──▼──┐     ┌──▼──┐     ┌──▼─┐   │
│                             │GPIO │     │Timer│     │UART│   │
│                             └─────┘     └─────┘     └────┘   │
└──────────────────────────────────────────────────────────────┘
```

A complete **System-on-Chip** integrating a custom RISC-V core, AXI4-Lite interconnect, AXI-to-APB bridge, and peripheral subsystem. This project demonstrates **full-stack digital design** — from the processor to the bus fabric to the peripherals.

**Key highlights:** Custom RISC-V as AXI Master · AXI4-Lite compliant interconnect · AXI-APB protocol bridge · Peripheral block (GPIO / Timer / UART) · Fully verified in simulation

[![View Repo](https://img.shields.io/badge/View%20Repo-mini__soc-00D4FF?style=flat-square&logo=github)](https://github.com/JeevaMatrix/riscv-axi-soc)

---

### ⚙️ Pipelined RISC-V Core (RV32I)

```
  ┌────┐   ┌────┐   ┌────┐   ┌─────┐   ┌────┐
  │ IF │──►│ ID │──►│ EX │──►│ MEM │──►│ WB │
  └────┘   └──┬─┘   └──┬─┘   └──┬──┘   └────┘
              │         │        │
              └────── Hazard Unit ──────────────
                   (Forwarding + Stall + Flush)
```

A **5-stage pipelined RISC-V processor** implementing the full RV32I base integer ISA, complete with:
- **Data forwarding** (EX-EX and MEM-EX paths)
- **Load-use stall** detection and insertion
- **Branch flush** on misprediction

[![View Repo](https://img.shields.io/badge/View%20Repo-pipelined__riscv-6E40C9?style=flat-square&logo=github)](https://github.com/JeevaMatrix/pipelined_cpu)

---

### 🔁 Single-Cycle RISC-V Core

A clean **single-cycle RV32I** implementation — ALU, register file, instruction memory, data memory, decode logic and control unit — the bedrock before the pipeline was added.

[![View Repo](https://img.shields.io/badge/View%20Repo-single__cycle__riscv-FF6B35?style=flat-square&logo=github)](https://github.com/JeevaMatrix/single_cycle_riscv_core)

---

### 🔌 Protocol IP Cores

| Protocol | Description | Link |
|----------|-------------|------|
| **AXI4-Lite** | Full Master + Slave with handshake (AWVALID/WVALID/BREADY) | [![Repo](https://img.shields.io/badge/Repo-00D4FF?style=flat-square&logo=github)](https://github.com/JeevaMatrix/axi4_lite) |
| **APB Master/Slave** | APB controller with peripheral interface and address decode | [![Repo](https://img.shields.io/badge/Repo-6E40C9?style=flat-square&logo=github)](https://github.com/JeevaMatrix/APB_master_slave) |
| **SPI** | Configurable SPI controller (CPOL/CPHA modes, shift register) | [![Repo](https://img.shields.io/badge/Repo-FF6B35?style=flat-square&logo=github)](https://github.com/JeevaMatrix/SPI) |
| **UART** | Full-duplex UART Tx/Rx with programmable baud rate generator | [![Repo](https://img.shields.io/badge/Repo-0078D7?style=flat-square&logo=github)](https://github.com/JeevaMatrix/uart_controller) |

---

### 🧮 Booth Multiplier

Signed **Radix-2 Booth Multiplier** in RTL — efficient partial product generation, addition tree, and sign-extended output. Correct for all signed edge cases.

[![View Repo](https://img.shields.io/badge/View%20Repo-booth__multiplier-00897B?style=flat-square&logo=github)](https://github.com/JeevaMatrix/booth_multiplier)

---

### ⏱️ Timer with Interrupt Controller

Programmable **hardware timer** peripheral with interrupt generation, acknowledge, and clear logic — designed to plug directly into an APB peripheral subsystem.

[![View Repo](https://img.shields.io/badge/View%20Repo-timer__interrupt-FFA000?style=flat-square&logo=github)](https://github.com/JeevaMatrix/Timer-Interrupt)

---

## 🗺️ Design Roadmap

```
2024 ──────────────────────────────────────────────────────────► 2025+
  │                                                                 │
  ├─ ✅  Single-Cycle RISC-V Core (RV32I)                          │
  ├─ ✅  5-Stage Pipelined RISC-V (Hazard + Forwarding)            │
  ├─ ✅  AXI4-Lite Master / Slave IP                               │
  ├─ ✅  APB Master / Slave IP                                      │
  ├─ ✅  SPI & UART Protocol Controllers                           │
  ├─ ✅  Booth Multiplier + Timer/Interrupt                         │
  ├─ ✅  Mini SoC (RISC-V + AXI4 + APB peripherals)               │
  │                                                                 │
  ├─ 🔄  UVM Testbenches for Protocol IPs                          │
  ├─ 🔄  Timing Constraints & STA (Vivado)                         │
  ├─ 📌  FPGA Implementation & Utilisation Report                  │
  └─ 📌  Formal Verification (SVA Assertions)                      │
                                                                    ▼
                                             RTL Design Engineer @ Semiconductor Co.
```

---

## 💼 Open to Opportunities

<div align="center">

### 🚨 Available Now — Internship & Full-Time

| | |
|---|---|
| 🎓 **Degree** | B.E. Electronics & Communication Engineering — Final Year |
| 📍 **Location** | Madurai, Tamil Nadu · Open to Relocate Anywhere in India |
| 🎯 **Target Role** | RTL Design Engineer · VLSI Design Intern · Digital Design Engineer |
| 🏢 **Dream Companies** | Qualcomm · MediaTek · Intel · Samsung Semiconductor · NVIDIA · Synopsys · Cadence · Ericsson |
| ⏰ **Availability** | Immediate |

</div>

<br/>

<div align="center">

**If you're hiring someone who can design a RISC-V SoC from a blank file — I'm your engineer.**

<br/>

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jeevanandhr/)
&nbsp;
[![Email](https://img.shields.io/badge/Send%20Me%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jeevanandh510@gmail.com)
&nbsp;
[![Resume](https://img.shields.io/badge/Download%20My%20Resume-00D4FF?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://drive.google.com/file/d/1bVbQK60cJrhqG4bVwNaTJrVcys5PjVTZ/view?usp=drive_link)

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,50:0a2a4a,100:0d1117&height=130&section=footer&text=Let%27s%20Build%20Silicon%20Together&fontSize=22&fontColor=ffffff&fontAlignY=65&animation=fadeIn" />

*"First, solve the problem. Then, write the RTL."*

</div>
