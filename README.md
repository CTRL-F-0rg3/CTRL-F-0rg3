
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

### Metrics

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=CTRL-F-0rg3&show_icons=false&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true)](https://github.com/CTRL-F-0rg3)

[![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=CTRL-F-0rg3&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)](https://github.com/CTRL-F-0rg3)

<p align="center">
  <i>Inowrocław, PL — Bare metal, one commit at a time.</i>
</p>

