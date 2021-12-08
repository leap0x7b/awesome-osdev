# Awesome OSDev [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
List of resources and projects for operating system development.

## Table of Contents
- [Projects](#projects)
   - [Indicators](#indicators)
   - [Bootloaders](#bootloaders)
   - [Operating Systems](#operating-systems)
- [Resources](#resources)
   - [Tutorials](#tutorials)
   - [Books](#books)
   - [Reference Projects](#reference-projects)
   - [Websites](#websites)
   - [Manuals and Specifications](#manuals-and-specifications)
      - [Processors](#processors)
          - [Instruction Sets](#instruction-sets)
      - [BIOS](#bios)
      - [Input Devices](#input-devices)
      - [Storage](#storage)
          - [File System](#file-system)
      - [Audio](#audio)
      - [Networking](#networking)
          - [NE2000-compatible cards](#ne2000-compatible-cards)
      - [Executable File Format](#executable-file-format)
      - [Miscellaneous](#miscellaneous)
- [Contributing](#contributing)

## Projects
### Indicators
- 🙂 - Work in progress
- 😀 - Finished
- 🙁 - Unmaintained

### Bootloaders
- 😀 [Limine](https://github.com/limine-bootloader/limine) - x86/x86_64 BIOS/UEFI Bootloader
- 🙂 [Sabaton](https://github.com/FlorenceOS/Sabaton) - aarch64 stivale2 bootloader
- 🙁 [TomatBoot](https://github.com/TomatOrg/TomatBoot) - A UEFI 64bit Bootloader
- 🙂 [Tosaithe](https://github.com/davmac314/tosaithe) - Very minimalistic UEFI boot menu / Stivale2 bootloader
- 🙂 [Ion](https://github.com/Andy-Python-Programmer/ion) - Modern x86_64 UEFI bootloader

### Operating Systems
- 😀 [SerenityOS](https://github.com/SerenityOS/serenity) - Graphical Unix-like operating system for x86 computers.
- 🙂 [BRUTAL](https://github.com/brutal-org/brutal) - An operating system inspired by brutalist design that combines the ideals of UNIX from the 1970s with modern technology and engineering
- 😀 [Managarm](https://github.com/managarm/managarm) - Pragmatic microkernel-based OS with fully asynchronous I/O
- 😀 [ToaruOS](https://github.com/klange/toaruos) - A completely-from-scratch hobby operating system: bootloader, kernel, drivers, C library, and userspace including a composited graphical UI, dynamic linker, syntax-highlighting text editor, network stack, etc.
- 🙁 [SkiftOS](https://github.com/skiftOS/skift) - A hobby operating system built from scratch in modern C++. Featuring a reactive UI library and a strong emphasis on user experience.
- 😀 [Vinix](https://github.com/vlang/vinix) - Vinix is an effort to write a modern, fast, and useful operating system in the V programming language
- 😀 [FlorenceOS](https://github.com/FlorenceOS/Florence) - The Renaissance of Operating Systems
- 🙂 [xtrix](https://git.sr.ht/~pitust/xtrix) - xtrix is a unix-like microkernel designed with a minimal kernel interface.
- 😀 [Lemon OS](https://github.com/LemonOSProject/LemonOS) - Lemon OS is a UNIX-like 64-bit operating system written in C++.
- 🙂 [Emerald](https://github.com/Abb1x/emerald) - An operating system written in C
- 🙂 [Skylight](https://github.com/austanss/skylight) - A clean, well-written minimalist operating system designed to be used as an educational material for operating system development.
- 😀 [SnowflakeOS](https://github.com/29jm/SnowflakeOS) - "It is very special"
- 🙂 [nop](https://github.com/nop-os/nop) - nop is a simple educational x86 kernel made to be as small and simple to understand as possible, while being a fully complete kernel.
- 😀 [EggOS](https://github.com/icexin/eggos) - A Go unikernel running on x86 bare metal
- 😀 [Aero](https://github.com/Andy-Python-Programmer/aero) - Aero is a new modern, experimental, unix-like operating system following the monolithic kernel design. Supporting modern PC features such as long mode, 5-level paging, and SMP (multicore), to name a few.

## Resources
### Tutorials
- [Stivale Bare Bones](https://wiki.osdev.org/Stivale_Bare_Bones) - Bare bones tutorial to make a 64-bit higher half kernel using the Limine bootloader and Stivale boot protocol.
- [Multiboot Bare Bones](https://wiki.osdev.org/Bare_Bones) - Write a basic 32-bit kernel in C for x86.
- [Higher Half Multiboot Bare Bones](https://wiki.osdev.org/Higher_Half_x86_Bare_Bones) - A tutorial that shows how to write a higher half kernel.
- [Meaty Skeleton](https://wiki.osdev.org/Meaty_Skeleton) - A template operating system with a basic libc.
- [Bran's Kernel Tutorial](http://www.osdever.net/tutorials/view/brans-kernel-development-tutorial) - A very dated, but still often referenced, tutorial from the now-moribund "Bona Fide OS Development" site.
- [The Little OS Book](http://littleosbook.github.io/) - A third-party OS demonstrator hosted on GitHub. Goes through periods of updating, and known bugs which haven't yet been fixed are listed in the repo.
- [cfenollosa/os-tutorial](https://github.com/cfenollosa/os-tutorial) - A tutorial to make a complete operating system from a bootloader to a basic shell.
- [Writing a Simple Operating System — From Scratch](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf) [PDF] - A 2010 tutorial based on course material from a class on operating systems at the University of Birmingham, UK, written by Dr. Nicholas Blundell, the original course instructor.
- [isometimes/rpi4-osdev](https://github.com/isometimes/rpi4-osdev) - A tutorial to write a basic operating system for Raspberry Pi 4.
- [Writing an OS in Rust](https://os.phil-opp.com/) - A blog series to write a small operating system in Rust.
- [James A. Molloy's Kernel Tutorials](http://jamesmolloy.co.uk/tutorial_html/) - One of the popular OS development tutorials in the past. It is not recommended to follow this tutorial because it has so many [issues and known flaws](https://wiki.osdev.org/Brokenthorn%27s_Known_Bugs) that have not been corrected.

### Books
| <img width="240px" src="https://m.media-amazon.com/images/I/51lTsD-LGoL.jpg"> | [Operating Systems: Three Easy Pieces](https://www.amazon.com/Operating-Systems-Three-Easy-Pieces-ebook/dp/B00TPZ17O4) |
|:-:|:--|
| | **Author(s):** Remzi Arpaci-Dusseau and Andrea Arpaci-Dusseau |
| | **Publication date:** February 16th, 2015 |
| | **Description:** \nA book covering the fundamentals of operating systems, including virtualization of the CPU and memory, threads and concurrency, and file and storage systems. Written by professors active in the field for 20 years, this text has been developed in the classrooms of the University of Wisconsin-Madison, and has been used in the instruction of thousands of students. |

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
- [Xv6](https://github.com/mit-pdos/xv6-public) ([Book](https://pdos.csail.mit.edu/6.828/2018/xv6/book-rev11.pdf)) - A modernized version of the classic Dennis Richie's and Ken Thompson's UNIX V6, written in ANSI C for the x86 and [RISC-V](https://github.com/mit-pdos/xv6-riscv).
- [MINIX 1.0](https://github.com/gdevic/minix1) - The first version of MINIX for Intel 8088 long mode. First appeared in a book released in 1986 called "Operating Systems: Design and Implementation" written by Andrew S. Tanenbaum.
- [MINIX 1.7.0](https://www.minix-vmd.org/source/std/1.7.0) - A revision of the first version of MINIX, now a 32-bit operating system.
- [MINIX 2.0.0](https://github.com/leapofazzam123/minix-2.0.0) - The second version of MINIX for i386 protected mode. Appeared in the second edition of "Operating Systems: Design and Implementation" released in 1997, written by Andrew S. Tanebaum and Albert S. Woodhull.

*Note: MINIX 3.0.0 isn't included because it's too complex to be an educational operating system compared to previous versions of MINIX.*

### Websites
- [OSDev Wiki](https://wiki.osdev.org/Expanded_Main_Page) - General OS development wiki where most of the resources OSDevers uses
- [Lowlevel.eu](http://www.lowlevel.eu/wiki/Lowlevel:Portal) - German OS development wiki
- [Wiki DEVSE](https://devse.wiki/) - French OS development wiki
- [Bona Fide OS Development](http://www.osdever.net/) - Tutorials and papers for OS developments. This is also where Bran's Kernel Tutorial lives.
- [OSDev Discord Server](https://discord.gg/RnCtsqD) - Not really a website but a great Discord server for OS development hangout

### Manuals and Specifications
#### Processors
- [Intel IA-32 and x86-64 Reference Manual](https://software.intel.com/en-us/articles/intel-sdm/)
    - [Intel Intrinsics Guide](https://software.intel.com/sites/landingpage/IntrinsicsGuide/)
- [AMD x64-64/AMD64 Reference Manual](http://developer.amd.com/resources/developer-guides-manuals/)
- [ARM Architecture Reference Manual](https://documentation-service.arm.com/static/5f8dacc8f86e16515cdb865a?token=) [PDF]
    - [Aarch64 Instruction Set Reference Manual](https://documentation-service.arm.com/static/5e7b694616d2907d594029eb?token=) [PDF]

##### Instruction Sets
- [Intel MMX Technology Overview](https://www.ee.ryerson.ca/~courses/ele818/mmx.pdf) [PDF] ([Intrinsics](https://software.intel.com/content/www/us/en/develop/documentation/cpp-compiler-developer-guide-and-reference/top/compiler-reference/intrinsics/intrinsics-for-mmx-technology.html?wapkw=mmx))
    - [AMD MMX Technology Manual](https://web.archive.org/web/20121125212937/http://www.nondot.org/sabre/os/files/Processors/AMDMMXManual.pdf) [PDF]
- [AMD 3DNow! Technology Manual](https://www.amd.com/system/files/TechDocs/21928.pdf) [PDF]
- [ARM NEON Programmer's Guide](https://www.seas.upenn.edu/~ese532/fall2020/handouts/_downloads/b8a011355a55096090c5b62e49f605c7/neon_programmers_guide.pdf) [PDF] ([Intrinsics](https://developer.arm.com/architectures/instruction-sets/simd-isas/neon/intrinsics))

#### BIOS
- [BIOS Boot Specification](https://www.scs.stanford.edu/nyu/04fa/lab/specsbbs101.pdf) [PDF]
- [Plug and Play BIOS Specification](http://www.osdever.net/documents/PNPBIOSSpecification-v1.0a.pdf) [PDF]

#### Input Devices
- [PS/2 Mouse/Keyboard Protocol Specification](https://www.avrfreaks.net/sites/default/files/PS2%2520Keyboard.pdf) [PDF]
    - [PS/2 Keyboard Interface](http://www-ug.eecg.toronto.edu/msl/nios_devices/datasheets/PS2%20Keyboard%20Protocol.htm)
    - [PS/2 Mouse Interface](https://isdaman.com/alsos/hardware/mouse/ps2interface.htm)
- [USB Interface Documentation](http://www.usb.org/documents)
    - [USB EHCI Specification](https://www.intel.com/content/dam/www/public/us/en/documents/technical-specifications/ehci-specification-for-usb.pdf) [PDF]
    - [USB xHCI Specification](http://www.intel.com/content/dam/www/public/us/en/documents/technical-specifications/extensible-host-controler-interface-usb-xhci.pdf) [PDF]
    - [USB OHCI Specification](https://www.usb.org/sites/default/files/usbdi10.pdf) [PDF]
    - [USB HID Specification](https://www.usb.org/sites/default/files/documents/hid1_11.pdf) [PDF]

#### Storage
- [T13](http://www.t13.org/) - The working group of the ATA/ATAPI standard
- [PCI IDE Controller Specification](http://www.bswd.com/pciide.pdf) [PDF]
    - [Programming Interface for Bus Master IDE Controller](http://bswd.com/idems100.pdf) [PDF]
    - [ATA/ATAPI-8 Command Set](http://hddguru.com/download/documentation/ATA-ATAPI-standard-8/d1699r2b-ATA8-Command-Set.pdf) [PDF]
    - [ATA/ATAPI-8 Architecture Model](http://hddguru.com/download/documentation/ATA-ATAPI-standard-8/d1700r2-ATA8-Architecture-Model.pdf) [PDF]
- [Serial ATA Revision 3.2 Specification](http://13thmonkey.org/documentation/Hardware/SerialATA_Revision_3_2_Gold%2528with_Links%2529.pdf) [PDF]
    - [Serial ATA AHCI Specification Revision 1.3](https://www.intel.com/content/dam/www/public/us/en/documents/technical-specifications/serial-ata-ahci-spec-rev1_3.pdf) [PDF]
- [CD-ROM Technical Summary](https://web.archive.org/web/20121125205537/http://www.nondot.org/sabre/os/files/Disk/CDROM.txt) [TXT]
- [Floppy Drive Controller Data Sheet](https://web.archive.org/web/20121125205537/http://www.nondot.org/sabre/os/files/Disk/82077AA_FloppyControllerDatasheet.pdf) [PDF]
    - [The 8272A Floppy Disk Controller](https://web.archive.org/web/20121125205537/http://www.nondot.org/sabre/os/files/Disk/FLOPPY.TXT) [TXT]
    - [Floppy Media Type ID's](https://web.archive.org/web/20121125205537/http://www.nondot.org/sabre/os/files/Disk/FloppyMediaIDs.txt) [TXT]

##### File System
- [Second Extended File System (Ext2)](https://www.nongnu.org/ext2-doc/ext2.html)
- [ReiserFS Specification](https://web.archive.org/web/20061112034935/http://www.namesys.com/X0reiserfs.html)
    - [ReiserFS FAQ](https://web.archive.org/web/20060705190506/http://www.namesys.com/faq.html)
- [Reiser4 Specification](https://web.archive.org/web/20061112034935/http://www.namesys.com/v4/v4.html)
- [FAT: General Overview of On-Disk Structure](https://web.archive.org/web/20121125180833/http://www.nondot.org/sabre/os/files/FileSystems/FatFormat.pdf) [PDF]
    - [Long File Name Specification](https://web.archive.org/web/20121125180833/http://www.nondot.org/sabre/os/files/FileSystems/LongFileName.pdf) [PDF]
    - [Notes on the structure of the VFAT Filesystem](https://web.archive.org/web/20121125180833/http://www.nondot.org/sabre/os/files/FileSystems/VFATInfo.txt) [TXT]
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

#### Networking
- [Realtek RTL8139C Datasheet](http://www.magnesium.net/~wpaul/rt/spec-8139cp(150).pdf) [PDF]
- [Realtek RTL8139D Datasheet](http://www.cs.usfca.edu/~cruse/cs326f04/RTL8139D_DataSheet.pdf) [PDF]
- [Realtek RTL8139 Programmers Guide](http://www.cs.usfca.edu/~cruse/cs326f04/RTL8139_ProgrammersGuide.pdf) [PDF]
- [Realtek RTL8169S Datasheet](http://realtek.info/pdf/rtl8169s.pdf) [PDF]
- [Intel 8254x Family of GbE Controllers Reference Manual](http://www.intel.com/content/dam/doc/manual/pci-pci-x-family-gbe-controllers-software-dev-manual.pdf) [PDF]
- [Intel i217 Ethernet Controller Datasheet](https://www.mouser.com/datasheet/2/612/i217-ethernet-controller-datasheet-257741.pdf) [PDF]

##### NE2000-compatible cards
- [Realtek RTL8019AS Datasheet](http://www.ethernut.de/pdf/8019asds.pdf) [PDF]
- [WinSystems PCM-NE2000 Datasheet](https://resources.winsystems.com/datasheets/pcm-ne2000-bnc-ds.pdf) [PDF]
- [WinSystems LPM-NE2000 Datasheet](https://cdn.datasheetspdf.com/pdf-down/L/P/M/LPM-NE2000_ETC.pdf) [PDF]
- [WinSystems MCM-NE2000 Datasheet](https://cdn.datasheetspdf.com/pdf-down/M/C/M/MCM-NE2000_ETC.pdf) [PDF]

#### Executable File Format
- [Executable and Linking Format Specification](https://refspecs.linuxfoundation.org/elf/elf.pdf) [PDF]
    - [System V Application Binary Interface Edition 4.1](http://www.sco.com/developers/devspecs/gabi41.pdf) [PDF]
    - [System V ABI, Intel386 Architecture Processor Supplement](http://www.sco.com/developers/devspecs/abi386-4.pdf) [PDF]
    - [System V ABI, AMD64 Supplement](http://refspecs.linuxbase.org/elf/x86_64-abi-0.99.pdf) [PDF]
    - [ELF for the ARM Architecture](http://infocenter.arm.com/help/topic/com.arm.doc.ihi0044b/IHI0044B_aaelf.pdf) [PDF]
    - [System V ABI, MIPS RISC Processor Supplement](http://www.sco.com/developers/devspecs/mipsabi.pdf) [PDF]
- [Portable Executable Specification](https://web.archive.org/web/20121125211355/http://www.nondot.org/sabre/os/files/Executables/PE.pdf) [PDF]
- [OS X ABI Mach-O File Format Reference](https://github.com/aidansteele/osx-abi-macho-file-format-reference/raw/master/Mach-O_File_Format.pdf) [PDF]
- [DJGPP COFF File Format Specification](http://www.delorie.com/djgpp/doc/coff/)
- [MZ File Format Specification](http://www.delorie.com/djgpp/doc/exe/)
- [a.out Specification](https://web.archive.org/web/20120301023848/http://www.nondot.org/sabre/os/files/Executables/a.out.txt) [TXT]
- [Linear Executable Specification](http://hobbes.nmsu.edu/download/pub/os2/dev/info/lxexe.doc) [Word]

#### Miscellaneous
- [Ralf Brown's Interrupt List](https://www.cs.cmu.edu/~ralf/files.html)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.
