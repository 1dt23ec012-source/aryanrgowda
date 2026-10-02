<div align="center">
  <h1>Hi there, I'm Aryan R Gowda 👋</h1>
  <p><strong>Digital VLSI Design | Analog/Mixed-Signal IC | RISC-V Microarchitecture | FPGA Prototyping</strong></p>
  <p>Electronics & Communication Engineering Undergraduate at <strong>DSATM, Bengaluru</strong> (Class of 2027)</p>

  <p>
    <a href="mailto:aryanrgowda1817@gmail.com"><img src="https://img.shields.io/badge/Email-aryanrgowda1817%40gmail.com-blue?style=flat&logo=gmail" alt="Email" /></a>
    <a href="https://www.linkedin.com/in/aryan-r-gowda/"><img src="https://img.shields.io/badge/LinkedIn-Aryan%20R%20Gowda-0A66C2?style=flat&logo=linkedin" alt="LinkedIn" /></a>
    <a href="https://github.com/1dt23ec012-source/aryanrgowda"><img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=flat&logo=github" alt="GitHub" /></a>
    <img src="https://img.shields.io/badge/Location-Bengaluru%2C%20India-orange?style=flat" alt="Location" />
  </p>
</div>

---

### 👨‍💻 About Me

I am an Electronics and Communication Engineering undergraduate focused on **end-to-end silicon design**—from theoretical microarchitectural specification and RTL authoring to full-custom polygon layout, static timing analysis (STA), and physical FPGA bring-up. 

* 🏛️ **Digital VLSI & Architecture:** Implementing custom instruction extensions on 32-bit RISC-V (RV32I) cores, AMBA AXI4 interconnects, and high-throughput cryptographic co-processors on AMD-Xilinx Artix-7 FPGAs.
* ⚡ **Analog & Mixed-Signal IC:** Designing submicron CMOS circuits (0.18-µm node), including Slew-Rate-Enhanced Recycling Folded Cascode (ERFC) OTAs with active gain-boosting and on-chip LDO regulators; verified 100% DRC clean with bit-exact LVS match and 3D PEX in Magic/Netgen/Ngspice.
* 🏎️ **Automotive Powertrain Leadership:** **Powertrain Team Lead** for our national Formula Bharat & Solar EV team, securing **4th Place Overall Nationally** through hands-on high-voltage distribution, safety interlocks (LOTO), and custom wiring harness fabrication.

---

### 🛠️ Technical Arsenal

<div align="left">

#### **Hardware Description & Architecture**
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-IEEE%201800-00599C?style=flat-square)
![Verilog HDL](https://img.shields.io/badge/Verilog-IEEE%201364-2B5B84?style=flat-square)
![RISC-V](https://img.shields.io/badge/RISC--V-RV32I%20Custom%20ISA-black?style=flat-square&logo=riscv)
![AMBA AXI](https://img.shields.io/badge/Bus%20Protocols-AXI4%20%7C%20AXI4--Lite%20%7C%20DMA-blue?style=flat-square)
![Cryptography](https://img.shields.io/badge/Hardware%20Crypto-NIST%20FIPS--197%20AES--128-red?style=flat-square)

#### **EDA Tools, Layout & Physical Verification**
![Vivado](https://img.shields.io/badge/Xilinx%20Vivado-2025.2-E23D28?style=flat-square)
![Magic VLSI](https://img.shields.io/badge/Magic%20VLSI-Full%20Custom%20Layout-purple?style=flat-square)
![Netgen LVS](https://img.shields.io/badge/Netgen-LVS%20Graph%20Isomorphism-brightgreen?style=flat-square)
![Ngspice](https://img.shields.io/badge/Ngspice-Direct%20Linear%20Solver-darkgreen?style=flat-square)
![Xschem](https://img.shields.io/badge/Xschem-Schematic%20Capture-lightgrey?style=flat-square)
![Process Node](https://img.shields.io/badge/CMOS%20Node-0.18µm%20Mixed--Signal%20(1P6M)-orange?style=flat-square)

#### **Embedded Systems, DSP & Instrumentation**
![FreeRTOS](https://img.shields.io/badge/OS-FreeRTOS-yellow?style=flat-square)
![ESP32](https://img.shields.io/badge/Hardware-ESP32%20Dual--Core-red?style=flat-square&logo=espressif)
![ADC](https://img.shields.io/badge/Precision%20ADC-TI%20ADS1256%20(24--bit%20ΔΣ)-blue?style=flat-square)
![Protocols](https://img.shields.io/badge/Protocols-SPI%20%7C%20UART%20(3--phase)%20%7C%20I2C-green?style=flat-square)
![PCB Standards](https://img.shields.io/badge/PCB%20Safety-IPC--2221B%20%7C%20IPC--2152-black?style=flat-square)

#### **Software, Languages & Acceleration**
![C](https://img.shields.io/badge/C-Bare--Metal%20Firmware-A8B9CC?style=flat-square&logo=c)
![C++](https://img.shields.io/badge/C++-Embedded-00599C?style=flat-square&logo=c%2B%2B)
![Python](https://img.shields.io/badge/Python-3.10+%20(PySerial%20%7C%20NumPy)-3776AB?style=flat-square&logo=python)
![MATLAB](https://img.shields.io/badge/MATLAB-DSP%20%7C%20Vision-e1673a?style=flat-square)
![CUDA](https://img.shields.io/badge/NVIDIA-CUDA%20Acceleration-76B900?style=flat-square&logo=nvidia)

</div>

---

### 🚀 Flagship Hardware & Silicon Projects

<table>
  <thead>
    <tr>
      <th>Project</th>
      <th>Domain</th>
      <th>Key Technical Highlights</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Task-Aware Object Selection AI Hardware Accelerator</strong><br><em>DVCon India 2026 Contest</em></td>
      <td>Digital VLSI / Edge AI</td>
      <td>
        • AXI4-compliant accelerator for autonomous vision agents with 64-bit Master DMA.<br>
        • Signed Q1.15 fixed-point DSP48E1 engine + 5-stage tournament reduction tree ($O(\log_2 N)$).<br>
        • Closed timing at 50 MHz ($+2.475\text{ ns } WNS$) on Artix-7; <strong>17 mW dynamic power</strong>, delivering <strong>28.2× speedup</strong> over CPU.
      </td>
    </tr>
    <tr>
      <td><strong>Aegis-Analog: 0.18-µm CMOS ERFC OTA & LDO</strong></td>
      <td>Analog / Mixed-Signal IC</td>
      <td>
        • 37-transistor ERFC OTA with active current recycling ($G_{m,eff} \approx 1.18\text{ mA/V}$) and dynamic Non-Linear Feedback (NLF).<br>
        • Boosted slew rate by <strong>84.7×</strong> ($13.55\text{ V/µs}$) at $9.91\text{ µA}$ static current with dual Bult-Geelen gain boosters ($98.77\text{ dB } A_{OL}$).<br>
        • Full-custom mask layout in Magic VLSI: <strong>100% DRC Clean</strong>, <strong>unique LVS match</strong> in Netgen, and 3D PEX post-layout stability ($88.50^\circ\text{ PM}$).
      </td>
    </tr>
    <tr>
      <td><strong>Aegis-V: FPGA-Based Hardware Security Module (HSM)</strong></td>
      <td>Digital Design / Crypto</td>
      <td>
        • Timing-closed NIST FIPS-197 AES-128 co-processor isolating keys in dedicated silicon registers.<br>
        • Solved $-9.16\text{ ns}$ cascade violation via a pipelined multi-cycle key expander (1 key/cycle across 11 register banks).<br>
        • Full-duplex UART engine with 3-phase handshaking; <strong>100% bit-for-bit validation</strong> against NIST SP 800-38A vectors.
      </td>
    </tr>
    <tr>
      <td><strong>RV32I RISC-V Processor with Custom Cryptographic Extension</strong></td>
      <td>Computer Architecture</td>
      <td>
        • 32-bit RV32I integer CPU datapath with custom instruction decoding (<code>AES.ENC</code> / <code>AES.DEC</code>) mapped into custom-0 opcode space.<br>
        • 3-phase register marshalling FSM routing 128-bit operands across four 32-bit registers.<br>
        • Synthesized and routed on Artix-7 FPGA: closed timing at 50 MHz with <strong>$+7.397\text{ ns}$ setup slack</strong> ($F_{max} = 79.35\text{ MHz}$).
      </td>
    </tr>
    <tr>
      <td><strong>Hospital-Grade 6-Lead Biopotential Acquisition Platform</strong></td>
      <td>Biomedical DSP / Embedded</td>
      <td>
        • 24-bit delta-sigma acquisition front-end with <strong>TI ADS1256 ADC</strong> and active Right Leg Drive (RLD) loop ($>100\text{ dB}$ CMRR).<br>
        • Input noise floor of $27\text{ nV}$ RMS; embedded FreeRTOS pipeline executing IIR bandpass/notch filtering and Pan-Tompkins QRS detection ($98.5\%$ accuracy).
      </td>
    </tr>
    <tr>
      <td><strong>Solid-State Capacitive Touch AC Switching PCB</strong></td>
      <td>Mixed-Signal PCB</td>
      <td>
        • Double-sided FR4 hardware switching 230V AC / 10A mains loads using CD4017 bistable latch and saturated BJT relay driver.<br>
        • Full compliance with <strong>IPC-2221B</strong> electrical insulation: $\ge 2.5\text{ mm}$ air clearance and $1.5\text{ mm}$ creepage isolation slots.
      </td>
    </tr>
  </tbody>
</table>

---

### 🏆 Honors & Key Achievements

* 🏅 **4th Place Overall (National Level)** — *Formula Bharat & Solar Electric Vehicle Championship (SEVC)* (Powertrain Team Lead).
* 🎯 **Design Contest Contributor** — *DVCon India 2026 Design Contest* (Task-Aware Object Selection AI Hardware Accelerator).
* 📜 **CMOS Digital VLSI Design** & **RTL to GDSII Design Flow** — *NPTEL*.
* 📜 **VLSI SoC Overview** & **Digital Design - Hands On** — *Maven Silicon*.

---

### 🔬 Currently Exploring
* **Universal Verification Methodology (UVM) & SystemVerilog Assertions (SVA)**
* **Open-Source Digital ASIC Implementation Flow (OpenROAD / SkyWater 130nm)**
* **Post-Quantum Cryptography (PQC) Hardware Accelerators (ML-KEM / Dilithium)**

---

<div align="center">
  <sub>Engineered with precision by <strong>Aryan R Gowda</strong>. Always open to discussing RTL design, analog layout, and silicon architecture!</sub>
</div>

Bengaluru, India

---

Thank you for visiting my profile!
