---
name: Karthik D K
header:
  - text: <span class="iconify" data-icon="tabler:phone"></span> (+91) 9108567200
  - text: <span class="iconify" data-icon="tabler:mail"></span> karthikdkwork@gmail.com
    link: mailto:karthikdkwork@gmail.com
  - text: <span class="iconify" data-icon="tabler:brand-github"></span> Karthik-d-k
    link: https://github.com/Karthik-d-k
  - text: <span class="iconify" data-icon="tabler:brand-linkedin"></span> karthik-d-k
    link: https://www.linkedin.com/in/karthik-d-k-319853166/
  - text: <span class="iconify" data-icon="charm:person"></span> 0x646b
    link: https://karthik-d-k.github.io/
  - text: <span class="iconify" data-icon="ic:outline-location-on"></span> Bengaluru, Karnataka, India
    link: https://maps.app.goo.gl/idnpQRieGHHeyU1v8
    newLine: true
---

## Summary

Firmware Engineer building the RISC-V software ecosystem for automotive and IoT at Bosch's TrusteD-V Innovation Team. 6+ years of embedded systems experience spanning kernel development, RTOS porting, and automotive ECU application software. Expertise in Rust, C, and Python for bare-metal and safety-critical systems. RISC-V Summit 2025 featured contributor.

\\[10px]

## Experience

*Firmware Engineer*
  ~ *Bosch Global Software Technologies*
  ~ *August 2019 - Present*

----

\\[10px]

**Hubris OS Port to RISC-V** <a href="https://github.com/Karthik-d-k/exhubris-riscv-hazard3">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>
- Ported Hubris OS to RISC-V - kernel primitives, trap/exception handlers, and PMP-based memory isolation for the Hazard3 core on Raspberry Pi Pico 2.
- Enabled dual-architecture support across ARM [Cortex-M33](https://github.com/Karthik-d-k/exhubris-demo-rp235x) and RISC-V [Hazard3](https://github.com/Karthik-d-k/exhubris-riscv-hazard3/tree/rp235x-hazard3) via custom linker scripts and startup code; worked around RP2350 errata and validated bring-up using OpenOCD/GDB over the Raspberry Pi Debug Probe.


**TrusteD-V RTOS**
- Developed proof-of-concept RTOS port for Mindgrove Secure IoT development board with working QEMU emulation support.
- Debugged kernel bring-up issues using Segger J-Link with OpenOCD and GDB.

\\[10px]

**Rust SDK for CDAC VEGA Processor**
- Created the first Rust bare-metal ecosystem for the CDAC VEGA ARIES v3 board (THEJAS32 RISC-V SoC).
- Reverse-engineered register maps from the VEGA C SDK into a Python-based SVD generator, producing type-safe PACs for 15+ peripherals (UART, SPI, I2C, Timer, GPIO, ADC, PWM, PLIC) validated with bare-metal examples.

\\[10px]

**SiFive E34 Board Bring-up (Trina-Pi)**
- Performed complete bare-metal bring-up of the UpBeatTech Trina-Pi board (SiFive E34 RISC-V core) entirely in Rust.
- Implemented a UART peripheral driver from scratch for serial console and debug I/O.

\\[10px]

**MLLib DecisionTree Inference**
- Built a lightweight C DecisionTree inference engine for a resource-constrained PowerTrain ECU, using FlatBuffers for model serialization and calibration-tool parameterization.

\\[10px]

**Advanced Exhaust Temperature Management (Onsite — Germany, 3 months)**
- Developed a CAN-based temperature-sensor component with diagnostics and statistical catalyst monitoring to meet EU7 emission standards.

\\[10px]

## Skills

**Programming:** Rust, C, Python

\\[10px]

**RTOS/Kernel:** Hubris OS, xv6, bare-metal programming

\\[10px]

**Debug Tools:** OpenOCD, GDB, tio, RP Debug Probe, Segger J-Link

\\[10px]

**Development Tools and Frameworks:** WSL, Git, Claude Code, PyTorch, Cargo, Make, Just, ASCET

\\[10px]

## Certifications
**Machine Learning: Stanford University (Andrew Ng)**
  ~ [Certificate](https://www.coursera.org/account/accomplishments/certificate/9DKFWDW79GAA)

*Coursera*
  ~ 2020

\\[10px]

## Achievements

- **RISC-V Summit 2025:** TrusteD-V project contributor (featured talk). <a href="https://youtu.be/O73rm9p6fTY?si=o1rWW-0pa3EEiumr">
  <span class="iconify" data-icon="tabler:brand-youtube-filled"></span>
</a>
- **Bosch Recognition:** Best Developer Award, Crowdsourcing Champ, AI Hackathon Winner. <a href="https://www.linkedin.com/in/karthik-d-k-319853166/details/honors/">
  <span class="iconify" data-icon="tabler:brand-linkedin-filled"></span>
</a>
- **Chess**: State-Level Championship participant.

\\[10px]

## Education

**University Vishweshwaraya College of Engineering, Bengaluru**
  ~ **75.2%**

B.E in Electronics and Communication
  ~ 2019

\\[10px]

**Devaraja URS PU College, Doddaballapur**
  ~ **94.5%**

PUC
  ~ 2015

\\[10px]

## Blogging

- Writing on firmware, systems programming, Rust, and motorcycles - a public knowledge repository that documents my work and helps others (and my future self). <a href="https://karthik-d-k.github.io/">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>

\\[10px]

## Open Source Projects

**Contributions** <a href="https://github.com/pulls?q=is%3Apr+archived%3Afalse+is%3Aclosed+author%3AKarthik-d-k">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>

- Active open-source contributor with merged pull requests into oreboot (Rust boot firmware) and the fastai and FluxML deep-learning libraries.

\\[10px]

**robot-hat-rs** <a href="https://github.com/Karthik-d-k/robot-hat-rs">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>
- Developed no_std Rust drivers (I2C, PWM, ADC) and a hardware abstraction layer for motor control, servo actuation, and analog sensor reading on the Robot HAT platform.
- Published on [crates.io](https://crates.io/crates/robot-hat-rs), receiving 4,000+ downloads from the community.

\\[10px]

**ixv** <a href="https://github.com/Karthik-d-k/ixv">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>
- Developed a Rust CLI for verifying Intel HEX files. Published on [crates.io](https://crates.io/crates/ixv) with 4,000+ downloads.

\\[10px]

**picars** <a href="https://github.com/Karthik-d-k/picars">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>
- Created an autonomous vehicle system using Raspberry Pi and PiCar-X kit, leveraging Rust and Python.
- Developed Rust bindings and interfaced with Python to optimize execution speed.

\\[10px]

## Languages

- English, Kannada, Telugu

\\[10px]
