# BinaryHub
**First things first**：Some people distribute binaries with backdoors, for some reason I can't say who they are, but such programs are usually packed with shellcode，and stripped of debug information.

Here are some compiled binaries, mainly for MIPS and ARM platforms.

**For security reason all binary with debug_info, not stripped for easily debug**

## For MIPS32 big endian 
Those binary use to do some hacking in GPON-G140W, Also worked in other mips32 big endian platforme.
```kernel
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

All binary build for ```MIPS32 version 1 (SYSV)```, and statically linked. 

```binary
e8884f5beb37ff66c9d24f3b71584811f8b426b8  mips32_big_endian/strace
429b5f9213b8492b62e8444da551d86a5758ab24  mips32_big_endian/tcpdump
a43067848838ab756216065760307fd4fac8935e  mips32_big_endian/zerotier-one
```
