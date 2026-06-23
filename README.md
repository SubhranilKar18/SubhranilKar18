<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1b4332,100:b87333&height=190&section=header&text=Subhranil%20Kar&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Analog%20%26%20Mixed-Signal%20Circuit%20Design%20%7C%20Jadavpur%20University&descAlignY=58&descSize=16" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?lines=Bridging+Circuit+Theory+%26+Hardware+Implementation;LTspice+%7C+MATLAB+%7C+Verilog+HDL+%7C+FPGA;Validating+Every+Design+Through+Rigorous+Simulation&font=Fira%20Code&size=18&pause=1200&color=b87333&center=true&vCenter=true&width=680&height=40&duration=3500" alt="Typing SVG" />

<img src="https://img.shields.io/badge/STATUS-ON%20THE%20BENCH-39ff88?style=for-the-badge&logoColor=white&labelColor=1b4332" />

</div>

<img src="assets/signal-trace.svg" width="100%">

## 🔧 Bill of Materials — Simulation & Design

| Ref | Component | Function |
|:---:|:----------|:---------|
| U1 | **LTspice** | Advanced DC / AC / Transient analysis |
| U2 | **MATLAB** | Numerical computation & signal processing |
| U3 | **Simulink** | System-level block modeling |

## 🔧 Bill of Materials — Hardware & HDL

| Ref | Component | Function |
|:---:|:----------|:---------|
| U4 | **8085 Microprocessor** | Architecture & assembly |
| U5 | **Verilog HDL** | RTL design |
| U6 | **FPGA** | Hardware prototyping |

## 🔧 Bill of Materials — Measurement & Analysis

| Ref | Component | Function |
|:---:|:----------|:---------|
| M1 | **Bode Plots** | Frequency response |
| M2 | **Pole-Zero Analysis** | System stability mapping |
| M3 | **`.tf`** | Transfer function extraction |
| M4 | **`.meas` / `.step`** | Parameterized measurement & sweeps |

## 🔧 Languages

<div align="center">
<img src="https://skillicons.dev/icons?i=c,cpp,python,matlab" />
</div>

<img src="assets/signal-trace.svg" width="100%">

## 📋 Schematic Sheet — Featured Project

### ⚡ [Circuit Theory to Implementation Using LTSpice](https://github.com/SubhranilKar18/Circuit-Theory-to-Implementation-Using-LTSpice)

> A structured series of simulations exploring fundamental circuit theorems, analog behaviors, and sub-micron CMOS characteristics.

**Sheet 1 — Active Devices (180nm CMOS)**
- **Common Drain (Source Follower)** — high-speed voltage buffer; impedance transformation to protect high-gain blocks from heavy loading; mapped sub-micron body effect ($g_{mb}$).
- **Common Source Amplifier** — voltage-divider-biased gain stage; high-pass roll-off from coupling networks; high-frequency limits from Miller-multiplied parasitics.
- **MOSFET Characterization** — nested `.dc` sweeps; extracted $V_{th}$; real-time transconductance via `d(Id(M1))`.

**Sheet 2 — Passive Networks**
- **First-Order RC & RL Transients** — duality between capacitor charging and inductor energizing, via automated $\tau$ extraction.
- **Maxwell L-C Bridge** — frequency-independent balance condition; roll-off from numerical pole-zero mismatch.
- **Maximum Power Transfer** — `.step` sweeps to find $R_L = R_{th}$.
- **Thevenin / Norton / Wheatstone Bridges** — simplified via the 1A test-source method; verified quadratic power relations via multi-pane DC sweeps.

<img src="assets/signal-trace.svg" width="100%">

## 🧪 Engineering Approach

```
Input ──[ Pole-Zero Cancellation ]──▶[ .tran / .ac Duality ]──▶[ SPICE vs. Theory Check ]──▶ Verified Output
```

🔍 Every simulation log is cross-checked against manual derivation — e.g. equating real & imaginary parts of complex impedance — before a design is trusted.

<img src="assets/signal-trace.svg" width="100%">

## 🔬 Currently On The Test Bench

- 🟢 Deepening op-amp non-ideality analysis (offset, slew rate, GBW trade-offs)
- 🟢 Moving from schematic-level sims toward physical layout considerations
- 🟢 Exploring mixed-signal interfacing between analog front-ends and FPGA logic

<img src="assets/signal-trace.svg" width="100%">

## 📫 Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/subhranil-kar-a3a830230/">
  <img src="https://img.shields.io/badge/LinkedIn-1b4332?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:subhranilkar.ece@gmail.com">
  <img src="https://img.shields.io/badge/Email-b87333?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/SubhranilKar18">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:b87333,100:1b4332&height=90&section=footer" width="100%"/>
