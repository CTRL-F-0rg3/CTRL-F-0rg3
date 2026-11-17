
# ctrl-F-0rg3 — Kacper Kosiński

> *Low-level systems programmer and hardware researcher from Inowrocław, Poland. Building custom operating system architectures, toolchains, memory management subsystems, and bare-metal software environment from scratch.*



## About

I focus on a **strict from-scratch philosophy**: understanding low-level systems and hardware execution models by implementing every layer ground-up without third-party frameworks. 

My primary work revolves around **TrangorgeOS** and its custom driver policy architecture, alongside direct hardware engineering, RISC-V design research, and bare-metal C/Rust systems development.



## Tech Stack

**Primary / Core:**
`Rust` `C` `x86_64 ASM` `Nim` `C++` `Ada/SPARK`

**Secondary / Occasional:**
`Zig` `Python` `Java` `JS` `TS` `HTML` `CSS`

**Operating Systems & Environments:**
`Arch Linux` `Void Linux` `LFS (Linux From Scratch)` `Gentoo` `Parrot OS`



## Hardware & Hardware Engineering

**Lab Setup:**
Dual-monitor workstation, dedicated Linux business laptop, local home server, primary desktop PC.

**Hardware & Electronics:**
Bench equipment, soldering station, and physical prototyping tools. Actively involved in hardware design, processor architecture development, and custom RISC-V research.



## Key Projects

### [TrangorgeOS](https://github.com/CTRL-F-0rg3/TrangorgeOS)
A modern bare-metal operating system built on a custom **Separated Tri-Partition Architecture** (*Architektura Trójpodziału Rozdzielnego*).
- **Architecture:** Replaces standard hybrid/microkernels by enforcing strict driver isolation, modular trust domains, and fine-grained kernel policy enforcement over all system data flows.
- **Memory Management:** Features a fully custom, bare-metal memory management subsystem and dynamic allocator written entirely in C.
- **Stack:** `C`, `Rust`, `x86_64 ASM`

### ctrlfile
A custom build automation tool and project runner built specifically to handle the strict execution requirements of TrangorgeOS as a precise alternative to standard Makefiles.
- **Features:** High-precision target execution, zero external runtime dependencies, dual implementation history.
- **Stack:** `Rust` (main stable release) / `Zig` (experimental)

### Dual BIOS/UEFI Bootloader
A compact, standalone dual BIOS/UEFI bootloader featuring a custom graphical TUI boot selection menu written in under 1,000 lines of code.
- **Features:** Multi-boot selection, direct hardware initialization, ultra-lightweight footprint.
- **Stack:** `C`, `x86_64 ASM`



## Philosophy


```

If you can build it yourself, why rely on someone else's black box?
Don't use a tool because it's popular. Use it because it solves the problem.

```
### GitHub Stats & Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=CTRL-F-0rg3&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CTRL-F-0rg3&layout=compact&theme=tokyonight&hide_border=true" alt="Most Used Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=CTRL-F-0rg3&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

### 🛠️ Tech Stack Badges

<p>
  <img src="https://img.shields.io/badge/Rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Assembly-%236E4C13.svg?style=for-the-badge&logo=assemblyscript&logoColor=white" alt="Assembly" />
  <img src="https://img.shields.io/badge/Arch%20Linux-%231793D1.svg?style=for-the-badge&logo=arch-linux&logoColor=white" alt="Arch Linux" />
  <img src="https://img.shields.io/badge/QEMU-%23D8112A.svg?style=for-the-badge&logo=qemu&logoColor=white" alt="QEMU" />
</p>


<p align="center">
  <i>Inowrocław, PL — Bare metal, one commit at a time.</i>
</p>

