# BinaryHub
**First things first**：Some people distribute binaries with backdoors, for some reason I can't say who they are, but such programs are usually packed with shellcode，and stripped of debug information.

Here are some compiled binaries, mainly for MIPS and ARM platforms.

**For security reason all binary with debug_info, not stripped for easily debug**

Before download any binary, these few files will help you and save your time.

- [Sha1sum.txt](https://raw.githubusercontent.com/ihexon/BinaryHub/main/mips32_big_endian/sha1sum.txt)
- [Release](https://raw.githubusercontent.com/ihexon/BinaryHub/main/mips32_big_endian/Release)
- [ChangeLog](https://github.com/ihexon/BinaryHub/blame/main/mips32_big_endian/ChangeLog)
- [BinaryNote.md](./mips32_big_endian/BinaryNote.md)

## For MIPS32 big endian 

Prebuild binary location: `./mips32_big_endian`. Those binary use to do some hacking in GPON-G140W, Also worked in other mips32 big endian platform.

```
# ELF Header:
  Magic:   7f 45 4c 46 01 02 01 00 00 00 00 00 00 00 00 00
  Class:                             ELF32
  Data:                              2's complement, big endian
  Version:                           1 (current)
  OS/ABI:                            UNIX - System V
  ABI Version:                       0
  Type:                              EXEC (Executable file)
  Machine:                           MIPS R3000
  Version:                           0x1

# Kernel version
Linux (none) 3.18.21 #4 SMP Tue Nov 22 16:34:26 CST 2022 mips GNU/Linux

# CPU INFO
system type             : EcoNet EN751221 SOC
machine                 : Unknown
processor               : 0
cpu model               : MIPS 34Kc V5.8
MIPS            : 1195.21
wait instruction        : yes
microsecond timers      : yes
tlb_entries             : 32
extra interrupt vector  : yes
hardware watchpoint     : yes, count: 4, address/irw mask: [0x0ffc, 0x0ffc, 0x0ffb, 0x0ffb]
isa                     : mips1 mips2 mips32r1 mips32r2
ASEs implemented        : mips16 dsp mt
```
