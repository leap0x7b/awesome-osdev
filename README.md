# Awesome OSDev [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
List of resources and projects for operating system development.

## Projects
### Indicators
- 🙂 - Work in progress
- 😀 - Finished
- 🙁 - Unmaintained

### Bootloaders
- 😀 [Limine](https://github.com/limine-bootloader/limine) - Modern, advanced, portable, multiprotocol bootloader.
- 🙂 [Sabaton](https://github.com/FlorenceOS/Sabaton) - aarch64 stivale2 bootloader
- 🙂 [Ion](https://github.com/Andy-Python-Programmer/ion) - Modern x86_64 UEFI bootloader
- 🙁 [TomatBoot](https://github.com/TomatOrg/TomatBoot) - A UEFI 64bit Bootloader
- 🙂 [Tosaithe](https://github.com/davmac314/tosaithe) - Very minimalistic UEFI boot menu / Stivale2 bootloader

### Operating Systems
- 😀 [SerenityOS](https://github.com/SerenityOS/serenity) - Graphical Unix-like operating system for x86 computers.
- 🙂 [BRUTAL](https://github.com/brutal-org/brutal) - An operating system inspired by brutalist design that combines the ideals of UNIX from the 1970s with modern technology and engineering
- 🙂 [skiftOS](https://github.com/skiftOS/skift) - A hobby operating system built from scratch in modern C++. Featuring a reactive UI library and a strong emphasis on user experience. (skiftOS is currently being rewritten so a lot of things might not work)
- 😀 [ToaruOS](https://github.com/klange/toaruos) - A completely-from-scratch hobby operating system: bootloader, kernel, drivers, C library, and userspace including a composited graphical UI, dynamic linker, syntax-highlighting text editor, network stack, etc.
- 😀 [Managarm](https://github.com/managarm/managarm) - Pragmatic microkernel-based OS with fully asynchronous I/O
- 😀 [Lyre](https://github.com/lyre-os/lyre) - Lyre is an effort to write a modern, fast, and useful operating system.
- 🙂 [μ](https://github.com/cute-engineering/mu) - µ is a minimalist microkernel
- 😀 [opuntiaOS](https://github.com/opuntiaOS-Project/opuntiaOS) - An operating system targeting x86, ARMv7, and Aarch64
- 😀 [Sortix](https://sortix.org) - Sortix is a small self-hosting operating-system aiming to be a clean and modern POSIX implementation.
- 😀 [Aero](https://github.com/Andy-Python-Programmer/aero) - Aero is a new modern, experimental, unix-like operating system following the monolithic kernel design.
- 😀 [FlorenceOS](https://github.com/FlorenceOS/Florence) - The Renaissance of Operating Systems
- 😀 [duckOS](https://github.com/byteduck/duckOS) - A hobby UNIX-like OS with a graphical window manager for x86 computers.
- 🙂 [nyx](https://github.com/nyx-org/nyx) - A simple operating system with a capability-based microkernel.
- 😀 [Lemon OS](https://github.com/LemonOSProject/LemonOS) - Lemon OS is a UNIX-like 64-bit operating system written in C++.
- 🙂 [Skylight](https://github.com/austanss/skylight) - A clean, well-written minimalist operating system designed to be used as an educational material for operating system development.
- 😀 [SnowflakeOS](https://github.com/29jm/SnowflakeOS) - "It is very special"

### Libraries
- 😀 [ACPICA](https://acpica.org) - A reference ACPI library for operating systems.
- 😀 [LAI](https://github.com/managarm/lai) - LAI is an interpreter for AML, the ACPI Machine Language.
- 😀 [libheap](https://github.com/cute-engineering/libheap) - A simple heap allocation library for hobby operating systems.
- 😀 [frigg](https://github.com/managarm/frigg) - Lightweight C++ utilities and algorithms for system programming
- 😀 [lil](https://github.com/Matt8898/lil) - A lightweight Intel GPU library

#### C Standard Libraries
- 😀 [musl](https://musl.libc.org) - A lightweight C standard library designed for Linux, but should work in other operating systems with some modifications.
- 😀 [Sortix libc](https://sortix.org/source/sortix/tree/master/libc) - The C standard library provided by Sortix. Even though it's designed for Sortix, it's easy to port and [supports over 70+ third-party software](https://gitlab.com/sortix/sortix/wikis/Ports).
- 😀 [mlibc](https://github.com/managarm/mlibc) - Portable C standard library
- 🙂 [chadlibc](https://github.com/cute-engineering/chadlibc) - A simple C standard library. Very incomplete and currently isn’t recommended for use in your operating system.

## Resources
### Tutorials
- [Limine Bare Bones](https://wiki.osdev.org/Limine_Bare_Bones) - Bare bones tutorial to make a 64-bit higher half kernel using the Limine boot protocol.
- [Stivale Bare Bones](https://wiki.osdev.org/Stivale_Bare_Bones) - Bare bones tutorial to make a 64-bit higher half kernel using the Stivale boot protocol.
- [Building an OS](https://youtube.com/playlist?list=PLFjM7v6KGMpiH2G-kT781ByCNC_0pKpPN) [YouTube] - A YouTube series by Nanobyte on how to make your own operating system and bootloader from scratch.
- [Higher Half Multiboot Bare Bones](https://wiki.osdev.org/Higher_Half_x86_Bare_Bones) - A tutorial that shows how to write a higher half kernel.
- [Multiboot Bare Bones](https://wiki.osdev.org/Bare_Bones) - Write a basic 32-bit kernel in C for x86.
- [Meaty Skeleton](https://wiki.osdev.org/Meaty_Skeleton) - A template operating system with a basic kernel-side libc.
- [Writing an OS in Rust](https://os.phil-opp.com/) - A blog series to write a small operating system in Rust.
- [Bran’s Kernel Tutorial](http://www.osdever.net/tutorials/view/brans-kernel-development-tutorial) - A very dated, but still often referenced, tutorial from the now-moribund "Bona Fide OS Development" site.
- [The Little OS Book](http://littleosbook.github.io/) - A third-party OS demonstrator hosted on GitHub. Goes through periods of updating, and known bugs which haven’t yet been fixed are listed in the repo.
- [cfenollosa/os-tutorial](https://github.com/cfenollosa/os-tutorial) - A tutorial to make a complete operating system from a bootloader to a basic shell.
- [Think OS](https://greenteapress.com/thinkos) - A 2015 book written as an introduction to operating systems for programmers, written by Allen B. Downey.
- [Writing a Simple Operating System — From Scratch](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf) [PDF] - A 2010 tutorial based on course material from a class on operating systems at the University of Birmingham, UK, written by Dr. Nicholas Blundell, the original course instructor.
- [isometimes/rpi4-osdev](https://github.com/isometimes/rpi4-osdev) - A tutorial to write a basic operating system for Raspberry Pi 4.
- [Poncho OSDev tutorial (Season 1)](https://youtube.com/playlist?list=PLxN4E629pPnKKqYsNVXpmCza8l0Jb6l8-) [YouTube] - A YouTube series by Poncho on how to make your own 64-bit operating system from scratch.
- [Poncho OSDev tutorial (Season 2)](https://youtube.com/playlist?list=PLxN4E629pPnJxCQCLy7E0SQY_zuumOVyZ) [YouTube] - A YouTube series by Poncho on how to make your own operating system and UEFI bootloader from scratch.
- [James A. Molloy’s Kernel Tutorials](http://jamesmolloy.co.uk/tutorial_html/) - One of the popular OS development tutorials in the past. It is not recommended to follow this tutorial because it has so many [issues and known flaws](https://wiki.osdev.org/James_Molloy%27s_Tutorial_Known_Bugs) that have not been corrected.

### Books
| <img width="240px" src="https://m.media-amazon.com/images/I/51lTsD-LGoL.jpg"> | [Operating Systems: Three Easy Pieces](https://www.amazon.com/Operating-Systems-Three-Easy-Pieces-ebook/dp/B00TPZ17O4) |
|:-:|:--|
| | **Author(s):** Remzi Arpaci-Dusseau and Andrea Arpaci-Dusseau |
| | **Publication date:** February 16th, 2015 |
| | **Description:** A book covering the fundamentals of operating systems, including virtualization of the CPU and memory, threads and concurrency, and file and storage systems. Written by professors active in the field for 20 years, this text has been developed in the classrooms of the University of Wisconsin-Madison, and has been used in the instruction of thousands of students. |

| <img width="240px" src="https://m.media-amazon.com/images/I/511H8QWUL4L._AC_SY780_.jpg"> | [Modern Operating Systems](https://www.amazon.com/Modern-Operating-Systems-Andrew-Tanenbaum/dp/013359162X) 4th Edition |
|:-:|:--|
| | **Author(s):** Andrew S. Tannenbaum and Herbert Bos |
| | **Publication date:** March 10th, 2014 |
| | **Description:** Modern Operating Systems, Fourth Edition, is intended for introductory courses in Operating Systems in Computer Science, Computer Engineering, and Electrical Engineering programs. It also serves as a useful reference for OS professionals. |

| <img width="240px" src="https://m.media-amazon.com/images/I/51tezjsttsL.jpg"> | [Operating System Concepts](https://www.amazon.com/Operating-System-Concepts-Abraham-Silberschatz-ebook/dp/B07CVKH7BD) 10th Edition |
|:-:|:--|
| | **Author(s):** Abraham Silberschatz, Greg Gagne, and Peter B. Galvin |
| | **Publication date:** May 4th, 2018 |
| | **Description:** The tenth edition of Operating System Concepts has been revised to keep it fresh and up-to-date with contemporary examples of how operating systems function, as well as enhanced interactive elements to improve learning and the student’s experience with the material. It combines instruction on concepts with real-world applications so that students can understand the practical usage of the content. End-of-chapter problems, exercises, review questions, and programming exercises help to further reinforce important concepts. New interactive self-assessment problems are provided throughout the text to help students monitor their level of understanding and progress. A Linux virtual machine (including C and Java source code and development tools) allows students to complete programming exercises that help them engage further with the material. |

| <img width="240px" src="https://m.media-amazon.com/images/I/51m-4I8qKzL._AC_SY780_.jpg"> | [The Design of the UNIX Operating System](https://www.amazon.com/Design-UNIX-Operating-System/dp/0132017997) |
|:-:|:--|
| | **Author(s):** Maurice Bach |
| | **Publication date:** May 27th, 1986 |
| | **Description:** This book describes the internal algorithms and the structures that form the basis of the UNIX® operating system and their relationship to the programmer interface. The system description is based on UNIX System V Release 2 supported by AT&T, with some features from Release 3. |

| <img width="240px" src="https://m.media-amazon.com/images/I/51UjzO152QL._AC_SY780_.jpg"> | [Operating Systems: Principles and Practice](https://www.amazon.com/Operating-Systems-Principles-Thomas-Anderson/dp/0985673524) |
|:-:|:--|
| | **Author(s):** Thomas Anderson and Michael Dahlin |
| | **Publication date:** August 21st, 2014 |
| | **Description:** Over the past two decades, there has been a huge amount of innovation in both the principles and practice of operating systems Over the same period, the core ideas in a modern operating system - protection, concurrency, virtualization, resource allocation, and reliable storage - have become widely applied throughout computer science. Whether you get a job at Facebook, Google, Microsoft, or any other leading-edge technology company, it is impossible to build resilient, secure, and flexible computer systems without the ability to apply operating systems concepts in a variety of settings. This book examines the both the principles and practice of modern operating systems, taking important, high-level concepts all the way down to the level of working code. Because operating systems concepts are among the most difficult in computer science, this top to bottom approach is the only way to really understand and master this important material. |

| <img width="240px" src="https://m.media-amazon.com/images/I/41d-8kHHYDL._AC_SY780_.jpg"> | [Operating Systems: Design and Implementation](https://www.amazon.com/Operating-Systems-Implementation-Prentice-Hall-Software/dp/0136374069) 1st Edition |
|:-:|:--|
| | **Author(s):** Andrew S. Tannenbaum |
| | **Publication date:** December 1st, 1986 |
| | **Description:** From one of the Netherland's leading authors of computer science books comes complete coverage of operating systems, plus all the design and implementation issues with a complete operating system — MINIX. |

| <img width="240px" src="https://m.media-amazon.com/images/I/5169V5J687L._AC_SY780_.jpg"> | [Operating Systems: Design and Implementation](https://www.amazon.com/Operating-Systems-Design-Implementation-Second/dp/0136386776) 2nd Edition |
|:-:|:--|
| | **Author(s):** Andrew S. Tannenbaum and Albert S. Woodhull |
| | **Publication date:** January 15th, 1997 |
| | **Description:** Most books on operating systems deal with theory while ignoring practice. While the usual principles are covered in detail, the book describes a small, but real UNIX-like operating system: MINIX. The book demonstrates how it works while illustrating the principles behind it. Operating Systems: Design and Implementation Second Edition provides the MINIX source code. The relevant selections of the MINIX code are described in detail. When it first came out, MINIX caused something of a revolution. Within weeks, it had its own newsgroup on USENET, with 40,000 people. Most wanted to make MINIX bigger and fancier. Instead, Linux was created. That has become quite popular, very large, and complicated. MINIX, on the other hand, has remained small and suitable for instruction and example. The book has been revised to include updates in MINIX, which started out as a v7 unix clone for a floppy-disk only 8088. It is now aimed at 386, 486, and pentium machines and is based on the international posix standard instead of on v7. There are now also versions of MINIX for the Macintosh and SPARC available. Professional programmers will find this book to be a valuable resource and reference. |

| <img width="240px" src="https://m.media-amazon.com/images/I/51TgXvjntUL._AC_SY780_.jpg"> | [Operating Systems: Design and Implementation](https://www.amazon.com/Operating-Systems-Design-Implementation-3rd/dp/0131429388) 3rd Edition |
|:-:|:--|
| | **Author(s):** Andrew S. Tannenbaum and Albert S. Woodhull |
| | **Publication date:** January 4th, 2006 |
| | **Description:** Operating Systems Design and Implementation, 3e, is ideal for introductory courses on computer operating systems. Written by the creator of MINIX, professional programmers will now have the most up-to-date tutorial and reference available today. Revised to address the latest version of MINIX (MINIX 3), this streamlined, simplified new edition remains the only operating systems text to first explain relevant principles, then demonstrate their applications using a Unix-like operating system as a detailed example. It has been especially designed for high reliability, for use in embedded systems, and for ease of teaching.  |

### Reference Projects
- [Linux 0.0.1](https://cdn.kernel.org/pub/linux/kernel/Historic/linux-0.01.tar.gz) - The first version of Linux. This version is very simple compared to subsequent versions after it.
- [Xv6](https://github.com/mit-pdos/xv6-public) [[PDF](https://pdos.csail.mit.edu/6.828/2018/xv6/book-rev11.pdf)] - A modernized version of the classic Dennis Richie’s and Ken Thompson’s UNIX V6, written in ANSI C for x86 and [RISC-V](https://github.com/mit-pdos/xv6-riscv).
- [MINIX 1.0](https://github.com/gdevic/minix1) - The first version of MINIX for Intel 8088 real mode. First appeared in a book released in 1986 called "Operating Systems: Design and Implementation" written by Andrew S. Tanenbaum.
  - [MINIX 1.5.0](https://www.minix-vmd.org/source/std/1.5.0) - A revision of the first version of MINIX that adds support for the 16-bit 286 protected mode and some bug fixes.
  - [MINIX 1.7.0](https://www.minix-vmd.org/source/std/1.7.0) - A revision of the first version of MINIX that adds support for the 32-bit 386 protected mode and some bug fixes.
- [MINIX 2.0.0](https://github.com/leap0x7b/minix-2.0.0) - The second version of MINIX for Intel 8088 real mode, the 16-bit 286 protected mode, and the 32-bit 386 protected mode. Appeared in the second edition of "Operating Systems: Design and Implementation" released in 1997, written by Andrew S. Tanebaum and Albert S. Woodhull.
- [MINIX 3.1.0](https://github.com/Stichting-MINIX-Research-Foundation/minix/tree/v3.1.0) - The third version of MINIX for the 32-bit 386 protected mode. Appeared in the third edition of "Operating Systems: Design and Implementation" released in 2006, written by Andrew S. Tanebaum and Albert S. Woodhull.
- [MINIX From Scratch](https://github.com/o-oconnell/minixfromscratch) - A quick development environment for building the book versions of MINIX 2 and 3.

> **Note**<br>
> Recent versions of MINIX 3 doesn’t count as an educational operating system because it’s too complex compared to the book version of MINIX 3 and previous versions of MINIX. You can still use it as a reference for your operating system project, but if you're a beginner, it’s much more recommended to look on source codes of the book version of MINIX 3 instead.

### Websites
- [OSDev Wiki](https://wiki.osdev.org/Expanded_Main_Page) - The OS development wiki and also the most commonly used resources for OS developers.
- [OSDev Forum](https://forum.osdev.org/) - The OS development forum and also the most commonly used forum for talking about and helping with OS development, also part of the OSDev Wiki.
- [New OSDev Wiki](http://osdev.wiki/wiki/index.html) - An attempt to modernize the original OSDev Wiki. Unlike the original OSDev Wiki, it uses it’s own wiki engine which uses GitHub instead of MediaWiki. It is currently WIP and not ready for use.
- [Lowlevel.eu](http://www.lowlevel.eu/wiki/Lowlevel:Portal) - The German OS development wiki. Also contains most of the resources from the OSDev wiki, but in German instead of English.
- [Wiki DEVSE](https://devse.wiki/) - The French OS development wiki. Not as complete as Lowlevel.eu or the OSDev Wiki, but still a good resource for French OS developers.
- [Bona Fide OS Development](http://www.osdever.net/) - Tutorials and papers for OS developments. This is also where Bran’s Kernel Tutorial lives.
- [OSDev Discord Server](https://discord.gg/RnCtsqD) - Not really a website but a great Discord server for talk about and help with OS development.
- [The Unix Tree](https://minnie.tuhs.org/cgi-bin/utree.pl) - Browse manuals and source codes of various versions of Unix.

### Miscellaneous Books, Papers, and Articles
- [Linux Insides](http://0xax.gitbooks.io/linux-insides/content/index.html)
- [Practical File System Design](https://web.archive.org/web/20170213221835/http://www.nobius.org/~dbg/practical-file-system-design.pdf) [PDF]
- [Computer Science from the Bottom Up](https://www.bottomupcs.com/)
- [A Heavily Commented Linux Kernel Source Code](http://www.oldlinux.org/download/ECLK-5.0.1-WithCover.pdf) [PDF]
- [CPU cores or what SMP is and what it is eaten with](https://sudonull.com/post/9813-CPU-cores-or-what-SMP-is-and-what-it-is-eaten-with)
- [Communication in Microkernel-Based Operating Systems](https://os.inf.tu-dresden.de/papers_ps/aigner_phd.pdf) [PDF]
- [FreeBSD/Linux Kernel Cross Reference](http://fxr.watson.org/fxr/source/?v=MK84)
- [The Evolution of the Unix Time-sharing System](https://www.bell-labs.com/usr/dmr/www/hist.html)
- [A Commentary on the Sixth Edition Unix Operating System](http://warsus.github.io/lions-/)
- [The Design and Implementation of the 4.4BSD Operating System](https://docs.freebsd.org/en/books/design-44bsd/)

### Manuals and Specifications
#### Processors
- [Intel IA-32 and x86-64 Reference Manual](https://software.intel.com/en-us/articles/intel-sdm/)
  - [Intel 8088 Datasheet](https://www.ndr-nkc.de/download/datenbl/i8088.pdf) [PDF]
  - [Intel 80286 Datasheet](http://datasheets.chipdb.org/Intel/x86/286/datashts/intel-80286.pdf) [PDF]
  - [Introduction to the 80386](http://bitsavers.trailing-edge.com/components/intel/80386/231746-001_Introduction_to_the_80386_Apr86.pdf)
  - [80386 Hardware Reference Manual](http://www.s100computers.com/My%20System%20Pages/80386%20Board/1987_80386_Hardware_Reference_Manual.pdf)
  - [Intel Intrinsics Guide](https://software.intel.com/sites/landingpage/IntrinsicsGuide/)
- [AMD x86-64/AMD64 Reference Manual](http://developer.amd.com/resources/developer-guides-manuals/)
- [ARM Architecture Reference Manual](https://documentation-service.arm.com/static/5f8dacc8f86e16515cdb865a?token=) [PDF]
  - [Aarch64 Instruction Set Reference Manual](https://documentation-service.arm.com/static/5e7b694616d2907d594029eb?token=) [PDF]
- [RISC-V Manuals and Specifications](https://riscv.org/technical/specifications/)
  - [RISC-V Instruction Set Manual (Volume 1: Unprivileged ISA)](https://github.com/riscv/riscv-isa-manual/releases/download/draft-20211216-5651528/riscv-spec.pdf) [PDF]
  - [RISC-V Instruction Set Manual (Volume 2: Privileged Architecture)](https://github.com/riscv/riscv-isa-manual/releases/download/draft-20211216-5651528/riscv-privileged.pdf) [PDF]

##### Instruction Set Extensions
- [Intel MMX Technology Overview](https://www.ee.ryerson.ca/~courses/ele818/mmx.pdf) [PDF] ([Intrinsics](https://software.intel.com/content/www/us/en/develop/documentation/cpp-compiler-developer-guide-and-reference/top/compiler-reference/intrinsics/intrinsics-for-mmx-technology.html?wapkw=mmx))
  - [AMD MMX Technology Manual](https://web.archive.org/web/20121125212937/http://www.nondot.org/sabre/os/files/Processors/AMDMMXManual.pdf) [PDF]
- [AMD 3DNow! Technology Manual](https://www.amd.com/system/files/TechDocs/21928.pdf) [PDF]
- [Intel AVX Extensions Programming Reference](https://software.intel.com/sites/default/files/4f/5b/36945) [PDF]
- [Intel AVX-512 - Instruction Set for Packet Processing](https://builders.intel.com/docs/networkbuilders/intel-avx-512-instruction-set-for-packet-processing-technology-guide-1617440657.pdf) [PDF]
- [ARM NEON Programmer’s Guide](https://www.seas.upenn.edu/~ese532/fall2020/handouts/_downloads/b8a011355a55096090c5b62e49f605c7/neon_programmers_guide.pdf) [PDF] ([Intrinsics](https://developer.arm.com/architectures/instruction-sets/simd-isas/neon/intrinsics))

#### Firmware
- [BIOS Boot Specification](https://www.scs.stanford.edu/nyu/04fa/lab/specsbbs101.pdf) [PDF]
- ["El Torito" Bootable CD-ROM Format](https://web.archive.org/web/20121125205058/http://www.nondot.org/sabre/os/files/Booting/BootableCDFormat.doc) [Word]
- [Plug and Play BIOS Specification](http://www.osdever.net/documents/PNPBIOSSpecification-v1.0a.pdf) [PDF]
- [Advanced Power Management BIOS Interface Specification Revision 1.2](https://download.microsoft.com/download/1/6/1/161ba512-40e2-4cc9-843a-923143f3456c/apmv12.rtf) [RTF]
- [Unified Extensible Firmware Interface Specifications](https://uefi.org/specifications/)
  - [UEFI Specification Version 2.0](https://uefi.org/specs/UEFI/2.10/)
  - [ACPI Specification Version 6.5](https://uefi.org/specs/ACPI/6.5/)

#### Input Devices
- [PS/2 Mouse/Keyboard Protocol Specification](https://www.avrfreaks.net/sites/default/files/PS2%2520Keyboard.pdf) [PDF]
  - [PS/2 Keyboard Interface](http://www-ug.eecg.toronto.edu/msl/nios_devices/datasheets/PS2%20Keyboard%20Protocol.htm)
  - [PS/2 Mouse Interface](https://isdaman.com/alsos/hardware/mouse/ps2interface.htm)
- [USB Interface Documentations](http://www.usb.org/documents)
  - [USB EHCI Specification](https://www.intel.com/content/dam/www/public/us/en/documents/technical-specifications/ehci-specification-for-usb.pdf) [PDF]
  - [USB xHCI Specification](http://www.intel.com/content/dam/www/public/us/en/documents/technical-specifications/extensible-host-controler-interface-usb-xhci.pdf) [PDF]
  - [USB OHCI Specification](https://www.usb.org/sites/default/files/usbdi10.pdf) [PDF]
  - [USB HID Specification](https://www.usb.org/sites/default/files/documents/hid1_11.pdf) [PDF]

#### Storage
- [NVM Express Specifications](https://nvmexpress.org/specifications/)
  - [NVM Express Base Specification 2.0c](https://nvmexpress.org/wp-content/uploads/NVM-Express-Base-Specification-2.0c-2022.10.04-Ratified.pdf) [PDF]
  - [NVMe Command Set Specification 1.0c](https://nvmexpress.org/wp-content/uploads/NVM-Express-NVM-Command-Set-Specification-1.0c-2022.10.03-Ratified.pdf) [PDF]
- [T13](http://www.t13.org/) - The working group of the ATA/ATAPI standard
- [PCI IDE Controller Specification](http://www.bswd.com/pciide.pdf) [PDF]
  - [Programming Interface for Bus Master IDE Controller](http://bswd.com/idems100.pdf) [PDF]
  - [ATA/ATAPI-8 Command Set](http://hddguru.com/download/documentation/ATA-ATAPI-standard-8/d1699r2b-ATA8-Command-Set.pdf) [PDF]
  - [ATA/ATAPI-8 Architecture Model](http://hddguru.com/download/documentation/ATA-ATAPI-standard-8/d1700r2-ATA8-Architecture-Model.pdf) [PDF]
- [Serial ATA Revision 3.2 Specification](http://13thmonkey.org/documentation/Hardware/SerialATA_Revision_3_2_Gold%2528with_Links%2529.pdf) [PDF]
  - [Serial ATA AHCI Specification Revision 1.3](https://www.intel.com/content/dam/www/public/us/en/documents/technical-specifications/serial-ata-ahci-spec-rev1_3.pdf) [PDF]
- [SCSI-1 Specification](https://nvlpubs.nist.gov/nistpubs/Legacy/FIPS/fipspub131.pdf) [PDF]
- [SCSI-2 Specification](http://www.bitsavers.org/components/ncr_symbios/scsi/SCSI-2_Standard_1994.pdf) [PDF]
- [SCSI-3 Parallel Interface Specification](https://stuff.mit.edu/afs/sipb/contrib/doc/specs/protocol/scsi-3/spi-r15a.pdf) [PDF]
- [CD-ROM Technical Summary](https://web.archive.org/web/20121125205537/http://www.nondot.org/sabre/os/files/Disk/CDROM.txt) [Text]
- [Floppy Drive Controller Data Sheet](https://web.archive.org/web/20121125205537/http://www.nondot.org/sabre/os/files/Disk/82077AA_FloppyControllerDatasheet.pdf) [PDF]
  - [The 8272A Floppy Disk Controller](https://web.archive.org/web/20121125205537/http://www.nondot.org/sabre/os/files/Disk/FLOPPY.TXT) [Text]
  - [Floppy Media Type ID’s](https://web.archive.org/web/20121125205537/http://www.nondot.org/sabre/os/files/Disk/FloppyMediaIDs.txt) [Text]

##### File System
- [Second Extended File System (Ext2)](https://www.nongnu.org/ext2-doc/ext2.html)
- [Fourth Extended File System (Ext4)](https://www.kernel.org/doc/html/latest/filesystems/ext4/index.html)
- [Btrfs Documentation](https://btrfs.readthedocs.io/en/latest/)
- [OpenZFS Documentation](https://openzfs.github.io/openzfs-docs/)
- [FAT: General Overview of On-Disk Structure](https://web.archive.org/web/20121125180833/http://www.nondot.org/sabre/os/files/FileSystems/FatFormat.pdf) [PDF]
  - [Long File Name Specification](https://web.archive.org/web/20121125180833/http://www.nondot.org/sabre/os/files/FileSystems/LongFileName.pdf) [PDF]
  - [Notes on the structure of the VFAT Filesystem](https://web.archive.org/web/20121125180833/http://www.nondot.org/sabre/os/files/FileSystems/VFATInfo.txt) [Text]
- [Inside the High Performance File System (HPFS)](https://web.archive.org/web/20121125180833/http://www.nondot.org/sabre/os/files/FileSystems/HPFS/index.html)
- [NFS Version 2 Protocol Specification (RFC 1094)](https://datatracker.ietf.org/doc/html/rfc1094)
- [NFS Version 3 Protocol Specification (RFC 1813)](https://datatracker.ietf.org/doc/html/rfc1813)
- [WebNFS Specification (RFC 2054)](https://datatracker.ietf.org/doc/html/rfc2054)
- [NFS Version 4 Protocol Specification (RFC 3530)](https://datatracker.ietf.org/doc/html/rfc3530)
  - [NFS Version 4.1 Protocol Specification (RFC 5661)](https://datatracker.ietf.org/doc/html/rfc5661)
- [ISO 9660 File System Specification (ECMA-119)](https://web.archive.org/web/20121125180833/http://www.nondot.org/sabre/os/files/FileSystems/iso9660.pdf) [PDF]
- [ISO 13346 Universal Disk Format Specification (ECMA-167)](http://www.osta.org/specs/pdf/udf201.pdf) [PDF]
- [Joliet Specification](http://littlesvr.ca/isomaster/resources/JolietSpecification.html)

#### Audio
- [Sound Blaster Series Hardware Programming Guide](https://pdos.csail.mit.edu/6.828/2008/readings/hardware/SoundBlaster.pdf) [PDF]
- [Standard MIDI-File Format Spec v1.1](http://www.music.mcgill.ca/~ich/classes/mumt306/midiformat.pdf) [PDF]
- [MIDI 1.0 Detailed Specification](http://www.shclemen.com/download/The%2520Complete%2520MIDI1.0%2520Detailed%2520Spec.pdf) [PDF]
- [Audio Codec '97 Component Specifications Revision 2.3](http://web.archive.org/web/20171208053110if_/http://download.intel.com/support/motherboards/desktop/sb/ac97_r23.pdf) [PDF]
- [Intel High Definition Audio Specification Revision 1.0a](http://www.intel.com/content/dam/www/public/us/en/documents/product-specifications/high-definition-audio-specification.pdf) [PDF]

#### Networking
- [Realtek RTL8139C Datasheet](http://www.magnesium.net/~wpaul/rt/spec-8139cp(150).pdf) [PDF]
- [Realtek RTL8139D Datasheet](http://www.cs.usfca.edu/~cruse/cs326f04/RTL8139D_DataSheet.pdf) [PDF]
- [Realtek RTL8139 Programmers Guide](http://www.cs.usfca.edu/~cruse/cs326f04/RTL8139_ProgrammersGuide.pdf) [PDF]
- [Realtek RTL8169S Datasheet](http://realtek.info/pdf/rtl8169s.pdf) [PDF]
- [Intel 8254x Family of GbE Controllers Reference Manual](http://www.intel.com/content/dam/doc/manual/pci-pci-x-family-gbe-controllers-software-dev-manual.pdf) [PDF]
- [Intel i217 Ethernet Controller Datasheet](https://www.mouser.com/datasheet/2/612/i217-ethernet-controller-datasheet-257741.pdf) [PDF]

##### NE2000-compatible cards
- [National Semiconductor DP8390D/NS32490D Datasheet](https://web.archive.org/web/20010612150713/http://www.national.com/ds/DP/DP8390D.pdf) [PDF] - The original reference design of the NE2000 standard.
- [Realtek RTL8019AS Datasheet](http://www.ethernut.de/pdf/8019asds.pdf)
- [WinSystems PCM-NE2000 Datasheet](https://resources.winsystems.com/datasheets/pcm-ne2000-bnc-ds.pdf) [PDF]
- [WinSystems LPM-NE2000 Datasheet](https://cdn.datasheetspdf.com/pdf-down/L/P/M/LPM-NE2000_ETC.pdf) [PDF]
- [WinSystems MCM-NE2000 Datasheet](https://cdn.datasheetspdf.com/pdf-down/M/C/M/MCM-NE2000_ETC.pdf) [PDF]

#### Video Display
##### Legacy
- [IBM MDA Reference Manual](http://minuszerodegrees.net/oa/OA%20-%20IBM%20Monochrome%20Display%20and%20Printer%20Adapter.pdf) [PDF]
- [IBM CGA Reference Manual](http://minuszerodegrees.net/oa/OA%20-%20IBM%20Color%20Graphics%20Monitor%20Adapter%20(CGA).pdf) [PDF]
- [IBM EGA Reference Manual](http://minuszerodegrees.net/oa/OA%20-%20IBM%20Enhanced%20Graphics%20Adapter.pdf) [PDF]
- [IBM VGA/XGA Technical Reference Manual](http://www.mcamafia.de/pdf/ibm_vgaxga_trm2.pdf) [PDF]
- [FreeVGA Project](http://www.osdever.net/FreeVGA/home.htm)

##### VESA BIOS Extensions
- [Super VGA BIOS Extensions 1.0 Specification](https://web.archive.org/web/20131211151957/http://www.gemixtes.de/super-vga-bios-extension-standard-vs891001/)
- [VESA BIOS Extensions 1.2 Specification](https://web.archive.org/web/20090114055246/http://docs.ruudkoot.nl/vesasp12.txt) [Text]
- [VESA BIOS Extensions 2.0 Specification](http://www.phatcode.net/res/221/files/vbe20.pdf) [PDF]
- [VESA BIOS Extensions 3.0 Specification](http://www.petesqbsite.com/sections/tutorials/tuts/vbe3.pdf) [PDF]

#### Executable File Format
- [Executable and Linking Format Specification](https://refspecs.linuxfoundation.org/elf/elf.pdf) [PDF]
  - [System V Application Binary Interface Edition 4.1](http://www.sco.com/developers/devspecs/gabi41.pdf) [PDF]
  - [System V ABI, Intel386 Architecture Processor Supplement](http://www.sco.com/developers/devspecs/abi386-4.pdf) [PDF]
  - [System V ABI, AMD64 Supplement](http://refspecs.linuxbase.org/elf/x86_64-abi-0.99.pdf) [PDF]
  - [ELF for the ARM Architecture](http://infocenter.arm.com/help/topic/com.arm.doc.ihi0044b/IHI0044B_aaelf.pdf) [PDF]
  - [RISC-V ELF psABI Document](https://github.com/riscv-non-isa/riscv-elf-psabi-doc/releases/download/v1.0-rc1/riscv-abi.pdf) [PDF]
  - [System V ABI, MIPS RISC Processor Supplement](http://www.sco.com/developers/devspecs/mipsabi.pdf) [PDF]
- [Portable Executable Specification](https://web.archive.org/web/20121125211355/http://www.nondot.org/sabre/os/files/Executables/PE.pdf) [PDF]
- [OS X ABI Mach-O File Format Reference](https://github.com/aidansteele/osx-abi-macho-file-format-reference/raw/master/Mach-O_File_Format.pdf) [PDF]
- [DJGPP COFF File Format Specification](http://www.delorie.com/djgpp/doc/coff/)
- [DOS .com Specification](https://web.archive.org/web/20121125211355/http://www.nondot.org/sabre/os/files/Executables/COM.txt)
- [DOS .sys Specification](https://web.archive.org/web/20121125211355/http://www.nondot.org/sabre/os/files/Executables/SYS.txt)
- [MZ File Format Specification](http://www.delorie.com/djgpp/doc/exe/)
- [a.out Specification](https://web.archive.org/web/20120301023848/http://www.nondot.org/sabre/os/files/Executables/a.out.txt) [Text]
- [Linear Executable Specification](http://hobbes.nmsu.edu/download/pub/os2/dev/info/lxexe.doc) [Word]

#### Miscellaneous
- [Ralf Brown’s Interrupt List](https://www.cs.cmu.edu/~ralf/files.html)
- [Boot Sector Overview](https://web.archive.org/web/20121125205058/http://www.nondot.org/sabre/os/files/Booting/BootSector.html)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.
