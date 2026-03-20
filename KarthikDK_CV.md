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
  - text: <span class="iconify" data-icon="ic:outline-location-on"></span> 12/431, Doddaballapur, Bengaluru Rural - 561203
    link: https://maps.app.goo.gl/JkBfG4sNpjDEPEtc6/
    newLine: true
---

## Summary

Firmware Developer building the RISC-V software ecosystem for automotive and IoT at Bosch's TrusteD-V Innovation Team. 6+ years of embedded systems experience spanning kernel development, RTOS porting, and automotive ECU application software. Expertise in Rust, C, and Python for bare-metal and safety-critical systems. RISC-V Summit 2025 featured contributor.

\\[10px]

## Experience

*Firmware Architect*
  ~ *Bosch Global Software Technologies*
  ~ *August 2019 - Present*

----

\\[10px]

**Hubris OS Port to RISC-V** <a href="https://github.com/Karthik-d-k/exhubris-riscv-hazard3">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>
- Ported Hubris OS to RISC-V, implementing kernel primitives, trap/exception handlers, and PMP-based memory isolation for Hazard3 core on Raspberry Pi Pico 2.
- Configured linker scripts and startup code for dual-architecture support across ARM [Cortex-M33](https://github.com/Karthik-d-k/exhubris-demo-rp235x) and RISC-V [Hazard3](https://github.com/Karthik-d-k/exhubris-riscv-hazard3/tree/rp235x-hazard3) cores.
- Overcame RP2350 errata and PMP configuration challenges; validated bring-up using OpenOCD and GDB over SWD with Raspberry Pi Debug Probe.


**TrusteD-V RTOS (In-house)**
- Developed proof-of-concept RTOS port for Mindgrove Secure IoT development board with working QEMU emulation support.
- Debugged kernel bring-up issues using Segger J-Link with OpenOCD and GDB.

\\[10px]

**Rust SDK for CDAC VEGA Processor**
- Created the first Rust bare-metal ecosystem for the CDAC VEGA ARIES v3 board (THEJAS32 RISC-V SoC).
- Built a Python-based SVD generator by reverse-engineering register maps and drivers from the VEGA C SDK.
- Produced a reproducible PAC generation pipeline with type-safe access for 15+ peripherals (UART, SPI, I2C, Timer, GPIO, ADC, PWM, PLIC) and validated with bare-metal working examples.

\\[10px]

**MLLib DecisionTree Inference**
- Developed a lightweight DecisionTree inference engine in C for deployment on a PowerTrain ECU with constrained resources.
- Utilized FlatBuffers for model serialization, enabling parameterization through calibration tooling.

\\[10px]

**Advanced Exhaust Temperature Management (Onsite — Germany, 3 months)**
- Developed a comprehensive component for reading temperature sensors via CAN and implementing sensor diagnostics to comply with EU7 standards.
- Implemented statistical analysis to monitor temperature distribution across catalyst, improving emission control efficiency.

\\[10px]

## Skills

**Programming:** Rust, C, Python

\\[10px]

**RTOS/Bare-Metal:** Hubris OS, FreeRTOS, Zephyr, bare-metal programming

\\[10px]

**Debug Tools:** Segger J-Link, RP Debug Probe, OpenOCD, GDB, minicom

\\[10px]

**Development Tools and Frameworks:** WSL, Git, PyTorch, Cargo, Make, ASCET

\\[10px]

## Certifications
**Machine Learning**
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

- Documenting my knowledge with programming, software engineering and motorcycles to create a knowledge repository for future reference, aiding both emerging LLMs and my personal growth. <a href="https://karthik-d-k.github.io/">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>

\\[10px]

## Open Source Projects

**Contributions** <a href="https://github.com/pulls?q=is%3Apr+archived%3Afalse+is%3Aclosed+author%3AKarthik-d-k">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>

- Active open-source contributor with notable pull requests merged into fastai and FluxML Deep Learning libraries.

\\[10px]

**robot-hat-rs** <a href="https://github.com/Karthik-d-k/robot-hat-rs">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>
- Developed no_std Rust drivers for I2C, PWM, and ADC peripherals targeting the Robot HAT robotics platform.
- Implemented hardware abstraction layer for motor control, servo actuation, and analog sensor reading.
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

**GeekyMicky** <a href="https://github.com/Karthik-d-k/GeekyMicky">
  <span class="iconify" data-icon="pajamas:github"></span>
</a>
- Tackled the Micro-Mouse Maze Challenge using Arduino Uno and C programming.

\\[10px]

## Languages

- English, Kannada, Telugu

\\[10px]
