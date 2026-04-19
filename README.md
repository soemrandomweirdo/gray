# Gray
A free and open‑source Linux‑based operating system focused on simplicity, clarity, and a unified desktop experience.

Gray is built to be a complete, user‑friendly OS that avoids the complexity of traditional Linux systems. It includes its own userland, its own GUI framework, and a clean filesystem layout designed for predictability and ease of development.

---

## Features

Native GUI
Gray includes a graphical interface built directly into the operating system.  
It's not a desktop environment or shell layered on top — the GUI is part of the core system and does not rely on the X Window System.

Custom Userland
Gray uses its own userland instead of the traditional GNU/Linux stack.  
This includes a set of built‑in applications designed to work together seamlessly:

- File Manager — manage, move, delete, and open files  
- Notes — write and organize information  
- Draw — lightweight sketching and painting  
- Voice — record audio memos and ideas  
- Calculator — basic and scientific calculations  
- Settings & Advanced Options — configure system behavior  
- Archive Manager — open/create ZIP, TAR.GZ, TAR.XZ, 7Z, BZ, BZ2  
- Packages — GUI and CLI package manager

These tools make Gray usable immediately without installing extra software.

---

## Filesystem Layout
Gray uses a modern, simplified filesystem structure.  
The Linux 6.6 LTS kernel is configured to follow this layout directly:

`
/system
    /kernel
        /modules
        /firmware
        /proc
        /sys
    /core
        /init
        /services
        /libs
    /apps
    /ui
    /data
    /config
    /devices
`

Each directory has a clear purpose, keeping the OS clean and predictable.

---

## Development
Gray is currently in early development.  
The project aims to build a consistent, well‑designed system with a small but dedicated core team.

Roles Needed
- Kernel Integrator  
- Init/Userland Developer  
- GUI Framework Developer  
- Application Developer  
- General Contributor (C/C++)

You don’t need to commit full‑time — just be consistent, communicate, and enjoy OS development.

If you’re interested in contributing, feel free to open an issue, start a discussion, or reach out.

---

## Roadmap (High‑Level)
- Core filesystem implementation  
- Init system and service manager  
- GUI framework and windowing system  
- Base applications  
- Package manager  
- Installer and live environment  
- Hardware support expansion  

(A more detailed roadmap will be added as development progresses.)

---

## License
it's licensed under the GPLv2.

---

## Contact
Questions, ideas, or contributions are welcome.  
Join the discussion in the repository’s Discussions tab.
