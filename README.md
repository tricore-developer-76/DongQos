#DongQos
/the offical github repository\
this project is for learning OS development
#rust
#osdev

DongQos

An operating system project built from the ground up.

DongQos is an independent operating system development project focused on low-level systems programming, kernel development, and graphical user-interface development.

The project is currently under development.

Project Architecture

Component| Purpose| Technology
Qos| Main operating-system kernel| Rust
Rags| Built-in command-line shell| Planned shell component
GUI| Graphical user interface| C++ and OpenGL
Low-level routines| Assembly-level operations| NASM

Development Toolchain

The development environment uses:

- VS Code — source-code editor
- GCC — C compiler
- G++ — C++ compiler
- Rust toolchain — Rust compilation
- NASM — assembler
- CMake — build-system configuration
- QEMU/KVM — virtual-machine testing

Development Goals

The project aims to develop:

- A custom kernel named Qos.
- A built-in shell named Rags.
- A graphical interface using C++ and OpenGL.
- Low-level hardware and device drivers.
- A bootable operating-system image.
- A stable development and testing workflow.

These are development goals, not claims that every component is already implemented.

Development Progress

DongQos is being developed as a long-term project with a target of 1,826 development days.

Progress and milestones are documented in "creation_logs.txt".

Testing

The kernel is intended to be tested in a virtualized environment using QEMU/KVM before being considered ready for physical hardware.

License

This project is licensed under the MIT License. See "LICENSE" (LICENSE) for details.

---

DongQos — built one step at a time.
