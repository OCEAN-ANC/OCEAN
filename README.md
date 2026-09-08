# 🌊 OCEAN
## Open Control Environment for Active Noise Control

**OCEAN** is an open-source, low-cost platform for teaching, research, and rapid prototyping in **Active Noise Control (ANC)**.

The project provides a complete hardware and software ecosystem that enables students, researchers, and engineers to build and operate a real-time ANC demonstrator for approximately **€150** using commercially available components.

---

## Why OCEAN?

Although Active Noise Control is a mature research field, practical experimentation is often limited by expensive laboratory equipment and proprietary development platforms.

OCEAN lowers this barrier by providing an affordable, reproducible, and fully documented experimental platform that combines:

- Open-source hardware
- Open-source software
- Model-based design
- Real-time embedded implementation
- Comprehensive documentation

The platform is intended for education, research, student projects, and rapid algorithm development.

---

## Key Features

- 🎓 Designed for education and academic research
- 💶 Complete system cost of approximately **€150**
- 🖨️ 3D-printable duct geometry
- 🔊 Two loudspeakers
- 🎤 Two digital MEMS microphones (I²S)
- ⚡ STM32 Nucleo embedded platform
- 📊 MATLAB® / Simulink® workflow
- 💻 Native C implementation
- 📖 Fully documented assembly and calibration
- 🌍 Open-source and community-driven

---

## Hardware Overview

The reference hardware consists of:

- STM32 Nucleo development board
- Audio power amplifier
- Two loudspeakers
- Two digital MEMS microphones
- 3D-printed acoustic duct
- Standard cables and connectors

A complete Bill of Materials (BOM) is available in the `hardware/` directory.

---

## Software

OCEAN supports multiple development workflows:

- MATLAB / Simulink
- Embedded C
- STM32 development environment
- Real-time DSP implementation

The initial release focuses on feedforward Active Noise Control using the Filtered-x LMS (FxLMS) algorithm. Future releases will include additional algorithms and advanced control architectures.

---

## Repository Structure

```text
OCEAN/
├── docs/
├── hardware/
├── firmware/
├── simulink/
├── matlab/
├── examples/
├── images/
└── papers/
```

---

## Roadmap

### Version 1.0
- Feedforward ANC
- FxLMS implementation
- MATLAB / Simulink reference model
- STM32 firmware
- Hardware documentation
- Assembly guide

### Future Releases

- Feedback ANC
- Hybrid ANC
- MIMO Active Noise Control
- Automatic secondary-path identification
- Real-time parameter tuning
- Additional embedded targets

---

## Contributing

Contributions are welcome.

Whether you would like to:

- improve the software,
- extend the hardware,
- add new control algorithms,
- improve the documentation,
- or report issues,

please feel free to open an Issue or submit a Pull Request.

---

## Citation

If you use OCEAN in your research or teaching, please cite the corresponding publication (coming soon).

---

## License

Software, hardware, and documentation are released under their respective open-source licenses. See the `LICENSE` file for details.

---

## Acknowledgements

OCEAN was initiated to make Active Noise Control more accessible for education and research by providing a low-cost, reproducible, and open experimental platform for the international ANC community.
