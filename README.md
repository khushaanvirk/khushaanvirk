## Khushaan Virk

Electrical Engineering at UBC (BASc, expected 2028). I build embedded and hardware systems — and the software that makes them measurable.

Right now I'm a Software Engineer at **Advizr**, shipping Python/FastAPI backends and automation pipelines for client systems in production. Before that, most of my work has been closer to the silicon: STM32 and 8051 firmware, discrete MOSFET motor drivers, analog signal conditioning, and a 4-layer PCB currently at fab.

The thread through all of it is pulling a trustworthy signal out of a noisy physical system, then proving how well it actually worked.

**Looking for:** an engineering co-op — embedded, firmware, hardware, or systems software.

---

### Selected work

**[Pedestrian Dead Reckoning](https://github.com/khushaanvirk/pedestrian-dead-reckoning)** · Python, NumPy, SciPy
Reconstructing a walked path from a phone's accelerometer and gyroscope alone, then measuring how far inertial drift pushes it off a known 76.2 m route. Band-pass step detection, gyro bias correction, and loop-closure error measurement — **5.14 m of drift (6.7%)**, validated across two runs with a held-out parameter check. Both raw recordings are in the repo, so every number reproduces.

**[khushaanvirk.com](https://github.com/khushaanvirk/portfolio)** · Next.js, React, TypeScript
My portfolio, built as a content-driven system: every project is a typed data object rendered by shared components, statically generated so a malformed entry fails the build rather than the page.

**65% Mechanical Keyboard PCB** · Altium
67-key hot-swap board — STM32F072 with crystal-less USB, 4-layer stackup, 90 Ω USB differential pair computed by hand from the real prepreg geometry. At JLCPCB for fab and assembly.

**Team firmware projects** (ELEC 291, teams of 6)
[Field-following robot](https://github.com/ELEC-291-2026/Project2.0) — dual-MCU autonomous robot that tracks a current-carrying wire via LC-tank pickup coils, with optocoupler-isolated H-bridges to keep motor switching noise out of the inductive sensors.
[Reflow oven controller](https://github.com/ELEC-291-2026/Project1.0) — closed-loop thermal control to ±3 °C with a thermocouple front-end and a Python serial DAQ harness for verification.

---

Full write-ups — schematics, measurements, build logs, and what went wrong — at **[khushaanvirk.com](https://khushaanvirk.com)**.
