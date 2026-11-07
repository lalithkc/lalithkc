<h1 align="center">Hi, I'm Lalithkumar B S 👋</h1>
<p align="center">
  <b>B.Tech, Electronics & Communication Engineering @ IIT Guwahati</b><br/>
  Digital design · Computer architecture · RTL-to-GDSII · Hardware for ML & cryptography
</p>

<p align="center">
  <a href="mailto:lalithkumar.b.sreeni@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
  <a href="mailto:s.lalithkumar@iitg.ac.in"><img src="https://img.shields.io/badge/IITG%20Mail-0A66C2?style=flat&logo=maildotru&logoColor=white"/></a>
</p>

---

### About me

- I design hardware from RTL to silicon: microarchitecture, Verilog/SystemVerilog, synthesis, place & route, sign-off.
- **Research Intern, IIT Guwahati (May–Aug 2026):** validated RTL-to-GDSII flows for a sovereign **HF RFID Reader ASIC** on **SCL 180nm** with Cadence and Synopsys tools, compared **Shakti E-Class** and **PicoRV32** cores for the team's core selection, and wrote **AMBA APB** bridges between the core, SRAM and the encryption engine.
- **RISC-V SoC on SCL 180nm (2026):** integrated a PicoRV32 SoC with an NPU, a uFPGA and an RFID/crypto macro, and took it from RTL to a chip GDS with a CIO250 pad ring. Added a flash-to-SRAM boot DMA, byte-lane SRAM and RV32IM, then closed sign-off: **Calibre LVS clean, antenna clean**, PrimeTime timing met, equivalence checked.
- Currently working on a **low-power CKKS homomorphic encryption accelerator** (NTT engine + homomorphic MAC core).

---

### Featured projects

| Project | What it is | Highlights |
|---|---|---|
| **SoC Integration** *(private)* | PicoRV32 SoC + NPU, uFPGA and RFID/crypto macros on SCL 180nm (4M1L) | 4 × 4 mm die, 28-pad CIO250 ring · flash-to-SRAM boot DMA with CRC check · 4 byte-lane SRAM macros · Genus → ICC2 → PrimeTime → Calibre: **LVS clean, 0 antenna**, setup/hold met at 50 MHz · Conformal LEC RTL ≡ layout netlist |
| [**7-Stage-RV32I-Core**](https://github.com/lalithkc/7-Stage-RV32I-Core) | Dual-core RV32I RISC-V SoC, RTL through GDSII | 2-wide, 7-stage dual-issue pipeline · MESI-lite coherence · 64-entry BTB · ICC2 on SCL180nm, **143 MHz, zero WNS**, 100% routed, clean GDSII · Formality + Xcelium GLS |
| [**Systolic-Array**](https://github.com/lalithkc/Systolic-Array) | 4x4 INT8 weight-stationary systolic accelerator | Reuses a 4-lane SIMD MAC datapath · AXI4-Lite slave wrapper · 2x2 round-robin crossbar, deadlock-free with 2 masters / 2 slaves |
| [**2-stage-OTA**](https://github.com/lalithkc/2-stage-OTA) | Miller-compensated two-stage OTA, TSMC 180nm | 64.28 dB gain · 61° PM · 15 MHz UGB · 526 µW · 38.68 V/µs slew |
| [**UART-Communication-System**](https://github.com/lalithkc/UART-Communication-System) | UART TX/RX with FIFOs on a Nexys4 DDR (Artix-7) | Parameterised baud tick generator, 16x oversampling, Vivado project script |
| [**Analog-Calculator**](https://github.com/lalithkc/Analog-Calculator) | Analog computer for +, −, ×, nth root | Wi-Fi input via NodeMCU, PWM-to-DC inputs, op-amp circuits |
| [**Rain-Rain-Go-Away**](https://github.com/lalithkc/Rain-Rain-Go-Away) | Rain-sensing wiper controller with no microcontroller | Op-amp ADC, shift-register/MUX PWM generator, 4 speed levels |
| [**detecting-parkinsons-disease**](https://github.com/lalithkc/detecting-parkinsons-disease) | ML classifier for Parkinson's from voice features | Logistic regression, decision tree, random forest, gradient boosting (scikit-learn) |

---

### Tech stack

**HDLs:** Verilog · SystemVerilog
**Languages:** C/C++ · Python · Tcl
**Synopsys:** SpyGlass · Design Compiler · Formality · VCS · IC Compiler II · PrimeTime
**Cadence:** Xcelium · Genus · Innovus · Voltus · Conformal LEC
**Siemens EDA:** Calibre (DRC / LVS / antenna)
**Other:** Vivado · LTspice · MATLAB · Linux · Git

<p>
  <img src="https://img.shields.io/badge/Verilog-FF6F00?style=flat"/>
  <img src="https://img.shields.io/badge/SystemVerilog-8A2BE2?style=flat"/>
  <img src="https://img.shields.io/badge/RISC--V-283272?style=flat&logo=riscv&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tcl-4E9A06?style=flat"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"/>
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lalithkc&show_icons=true&hide_border=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lalithkc&layout=compact&hide_border=true" height="150"/>
</p>
