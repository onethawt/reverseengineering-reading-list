# Reverse Engineering Reading List
If any of the links are down and you can't retrieve them on [archive.org](http://archive.org), [contact me](http://one.thawt.io/contact/) and I can give you a copy of the document.

## Software & Libraries
* [IDA Pro](https://www.hex-rays.com/products/ida/): The **KING** IDA is a Windows, Linux or Mac OS X hosted multi-processor disassembler and debugger that offers so many features it is hard to describe them all.
* [Capstone](http://www.capstone-engine.org/): Capstone is a lightweight multi-platform, multi-architecture disassembly framework. Our target is to make Capstone the ultimate disassembly engine for binary analysis and reversing in the security community.
* [Hopper](https://www.hopperapp.com/): Hopper is a reverse engineering tool for OS X and Linux, that lets you disassemble, and decompile your 32/64bits Intel Mac, Linux, Windows and iOS executables! Based on capstone, scriptable.
* [PeachPy](https://github.com/Maratyszcza/PeachPy): Portable efficient assembly code-generator in higher-level python.
* [Radare2](http://www.radare.org/): Portable reversing framework for disassembly, debugging, forensics, etc. Based on capstone, scriptable.

## Android
* [Offensive & Defensive Android Reverse Engineering](https://github.com/rednaga/training/tree/master/DEFCON23)

## Assembly / Disassembly
* [Analyzing Uncommon Firmware](http://blog.ptsecurity.com/2015/07/best-reverser-write-up-analyzing.html)
* [ARM v7 Disassembling](https://drive.google.com/file/d/0B0l-Qo3D3sAoMEhkcFBFVzRiNEk/view)
* [UROBOROS - Reassembling Disassembling](https://www.usenix.org/conference/usenixsecurity15/technical-sessions/presentation/wang-shuai) -  a tool that can disassemble executables to the extent that the generated code can be assembled back to working binaries without manual effort.

## Basics
* [Reverse Engineering 101 Speaker Presentation](https://vimeo.com/6764570)
* [Reverse Engineering 101 - NYU: Poly 2010](https://prezi.com/a5tm-lf0879-/reverse-engineering-101-nyupoly-2010/): Intro to Reverse Engineering given at NYU:Poly on October 4th, 2010 by Aaron Portnoy and Peter Silberman. 
* [Reverse Engineering 102 - NYU: Poly 2010](https://prezi.com/e5a2tumdqocj/reverse-engineering-102-nyupoly-2010/): Intro to Reverse Engineering (Day 2) given at NYU:Poly on October 11th, 2010 by Aaron Portnoy and Peter Silberman.
* [CTF Field Guide](https://trailofbits.github.io/ctf/)

### Books
* [Modern X86 Assembly Language Programming: 32-bit, 64-bit, SSE, and AVX](https://www.amazon.com/Modern-X86-Assembly-Language-Programming/dp/1484200659): Fundamentals of x86 assembly language programming. It focuses on the aspects of the x86 instruction set that are most relevant to application software development.
* [Practical Malware Analysis](https://www.amazon.com/Practical-Malware-Analysis-Hands-Dissecting/dp/1593272901): Practical Malware Analysis will teach you the tools and techniques used by professional analysts. With this book as your guide, you'll be able to safely analyze, debug, and disassemble any malicious software that comes your way.
* [Practical Reverse Engineering](https://www.amazon.com/Practical-Reverse-Engineering-Reversing-Obfuscation/dp/1118787315): The book covers x86, x64, and ARM (the first book to cover all three); Windows kernel-mode code rootkits and drivers; virtual machine protection techniques; and much more. Best of all, it offers a systematic approach to the material, with plenty of hands-on exercises and real-world examples.
* [Reversing: Secrets of Reverse Engineering](https://www.amazon.com/Reversing-Secrets-Engineering-Eldad-Eilam/dp/0764574817): Beginning with a basic primer on reverse engineering-including computer internals, operating systems, and assembly language-and then discussing the various applications of reverse engineering, this book provides readers with practical, in-depth techniques for software reverse engineering.
* [Reverse Engineering for Beginners](https://beginners.re/): Available in english and russian, this ebook is a good introduction for beginners. Numerous topics are touched : Oracle RDBMS, Itanium, copy-protection dongles, LD_PRELOAD, stack overflow, ELF, win32 PE file format, x86-64, critical sections, syscalls, TLS, position-independent code (PIC), profile-guided optimization, C++ STL, OpenMP, win32 SEH.
* [The IDA Pro Book: The Unofficial Guide to the World's Most Popular Disassembler](https://www.amazon.com/IDA-Pro-Book-Unofficial-Disassembler/dp/1593272898): Hailed by the creator of IDA Pro as "profound, comprehensive, and accurate," the second edition of The IDA Pro Book covers everything from the very first steps to advanced automation techniques.

## Data Structures
* [Automatic Reverse Engineering of Data Structures from Binary Execution](https://www.isoc.org/isoc/conferences/ndss/10/pdf/23.pdf) [PDF]
* [Digging For Data Structures](http://ben.ransford.org/srg/papers/cozzie--digging.pdf) [PDF]
* [Howard: a dynamic excavator for reverse engineering data structures](http://www.isoc.org/isoc/conferences/ndss/11/pdf/5_1.pdf) [PDF]
* [MemPick: High-Level Data Structure Detection in C/C++ Binaries](http://www.cs.vu.nl/~herbertb/papers/mempick_wcre13.pdf) [PDF]
* [TIE: Principled Reverse Engineering of Types in Binary Programs](https://reverse.put.as/wp-content/uploads/2011/06/D1T2-Mark-Dowd-Tarjei-Mandt-iOS6-Security.pdf) [PDF]

## Exploitation
* [Automated Vulnerability Discovery Techniques](http://www.crisalis-project.eu/sites/crisalis-project.eu/files/crisalis_deliverable-D5.3.pdf) [PDF]
* [Dismantling Megamos Crypto: Wirelessly Lockpicking a Vehicle Immobilizer](https://www.usenix.org/sites/default/files/sec15_supplement.pdf) [PDF]
* [Memory Graph Approach for Program Data Introspection and Modification](http://software.imdea.org/~juanca/papers/sigpath_esorics14.pdf) [PDF]
* [Remote Exploitation of an Unaltered Passenger Vehicle](http://illmatics.com/Remote%20Car%20Hacking.pdf) [PDF]


## Instruction Sets
* [Intel® 64 and IA-32 Architectures Software Developer Manuals](http://www.intel.com/content/www/us/en/processors/architectures-software-developer-manuals.html): These manuals describe the architecture and programming environment of the Intel® 64 and IA-32 architectures.
* [X86 Opcode and Instruction Reference](http://ref.x86asm.net/): This reference is intended to be precise opcode and instruction set reference (including x86-64). Its principal aim is exact definition of instruction parameters and attributes.
* [JSON x86-64 Intel instruction set](https://github.com/astocko/json-x86-64): The entire x86-64 Intel instruction set in a machine readable JSON format up to AVX-512.
* [X86-64 Reference](http://www.felixcloutier.com/x86/): Derived from the September 2014 version of the Intel® 64 and IA-32 Architectures Software Developer’s Manual, volumes 2A and 2B. **Uses [PDF mining](https://github.com/zneak/x86doc) to generate the reference from official Intel docs.**

## Mac and iOS
* [iOS App Reverse Engineering](https://github.com/iosre/iOSAppReverseEngineering): iOS App Reverse Engineering is the world's 1st book of very detailed iOS App reverse engineering skills
* [iOS Kernel Security](https://reverse.put.as/wp-content/uploads/2011/06/D1T2-Mark-Dowd-Tarjei-Mandt-iOS6-Security.pdf) [PDF]
* [Jailbreaking Techniques](https://reverse.put.as/wp-content/uploads/2011/06/pod2g-jailbreak-techniques-wwjc-2012.pdf) [PDF]
* [Reversing iOS Apps: A Practical Approach](https://s3.amazonaws.com/s3.synack.com/T2_reversingIOSApps.pdf) [PDF]

## Malware Analysis
[Please refer to the additional document](malwareanalysis.md)

## Network
[Reverse Engineering of Protocols from Network Traces](http://www.di.fc.ul.pt/~nuno/PAPERS/WCRE11.pdf) [PDF]

## Obfuscation and Deobfuscation
* [Context-Sensitive Analysis of Obfuscated x86 Executables](http://www.cacs.louisiana.edu/~arun/papers/2010-pepm-lakhotia.pdf) [PDF]
* [Advanced JS Deobfuscation Via AST and Partial Evaluation](http://blog.mindedsecurity.com/2015/10/advanced-js-deobfuscation-via-ast-and.html)

## Research Tools
* [Genetic Programming for Reverse Engineering](https://www.cs.virginia.edu/~weimer/p/weimer-wcre2013-re-preprint.pdf)
* [IR Transformation Synthesis for Assembly Instructions](https://speakerdeck.com/snf/ir-transformation-synthesis-for-assembly-instructions)

## Unpacking
* [The Art of Unpacking](https://www.blackhat.com/presentations/bh-usa-07/Yason/Whitepaper/bh-usa-07-yason-WP.pdf) [PDF]

## Windows
### Driver Signature Enforcement
* [Defeating Windows Driver Signature Enforcement #1: default drivers](http://j00ru.vexillium.org/?p=1169)
* [Defeating Windows Driver Signature Enforcement #2: CSRSS and thread desktops](http://j00ru.vexillium.org/?p=1393)
* [Defeating Windows Driver Signature Enforcement #3: The Ultimate Encounter](http://j00ru.vexillium.org/?p=1455)
* [DSEFix - Defeating x64 Driver Signature Enforcement: Using exploitable signed drivers - VirtualBox driver](http://www.kernelmode.info/forum/viewtopic.php?t=3322&f=11)


### Other
* [HyperV and vmbus internals](https://speakerdeck.com/snf/ir-transformation-synthesis-for-assembly-instructions)

### Patch Guard
* [Bypassing PatchGuard on Windows x64](http://www.uninformed.org/?v=3&a=3&t=txt)
* [Disable PatchGuard Vista & Windows 7](http://fyyre.ivory-tower.de/projects/bootloader.txt)
* [Disable PatchGuard Windows 8 & Windows 10](http://fyyre.ivory-tower.de/projects/bootloader_v2.txt)

### Win32
* [PInvoke.net](http://www.pinvoke.net/): PInvoke.net is primarily a wiki, allowing developers to find, edit and add PInvoke* signatures, user-defined types, and any other information related to calling Win32 and other unmanaged APIs from managed code (written in languages such as C# or VB.NET).
