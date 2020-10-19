# Table of Contents

1. [Introduction](introduction.md)
2. [Building](building/README.md)
   1. [Toolchain and building script](building/toolchain.md)
   2. [Reference project repository](building/project.md)
3. [Running system on targets](quickstart/README.md)
    1. [Running system on `armv7m4-stm32l4x6` (ST STM32L4x)](quickstart/armv7m4-stm32l4x6.md)
    2. [Running system on `armv7m7-imxrt105x` (NXP i.MX RT105x)](quickstart/armv7m7-imxrt105x.md)
    3. [Running system on `armv7m7-imxrt106x` (NXP i.MX RT106x)](quickstart/armv7m7-imxrt106x.md)
    4. [Running system on `armv7m7-imxrt117x` (NXP i.MX RT117x)](quickstart/armv7m7-imxrt117x.md)
    5. [Running system on `armv7a7-imx6ull` (NXP i.MX 6ULL)](quickstart/armv7a7-imx6ull.md)
    6. [Running system on `ia32-generic`](quickstart/ia32-generic.md)
    7. [Running system on `riscv64-virt`](quickstart/riscv64-virt.md)
    8. [Running system on `riscv64-spike`](quickstart/riscv64-spike.md)
4. [Architecture](architecture.md)
5. [Kernel](kernel/README.md)
    1. [HAL](kernel/hal/README.md)
        1. [HAL layer for ARMv7 Cortex-M based based targets](kernel/hal/armv7m.md)
        2. [HAL layer for ARMv7 Cortex-A based based targets](kernel/hal/armv7a.md)
        3. [HAL layer for IA32 based targets](kernel/hal/ia32.md)
        4. [HAL layer for RISC-V 64 based targets](kernel/hal/riscv64.md)
    2. [Memory management](kernel/vm/README.md)
        1. [Page allocator](kernel/vm/page.md)
        2. [Memory mapper](kernel/vm/mapper.md)
        3. [Zone allocator](kernel/vm/zalloc.md)
        4. [Fine-grained allocator](kernel/vm/kmalloc.md)
        5. [Memory objects](kernel/vm/objects.md)
   3. [Processes and threads](kernel/proc/README.md)
      1. [Processes creation](kernel/proc/forking.md)
      2. [Synchronization primitives](kernel/proc/sync.md)
      3. [Message passing](kernel/proc/msg.md)
      4. [Namespace](kernel/proc/namespace.md)
   4. [System calls](kernel/syscalls/README.md)
      1. [Debug (1)](kernel/syscalls/debug.md)
      2. [Memory management (5)](kernel/syscalls/mem.md)
      3. [Processes management (13)](kernel/syscalls/proc.md)
      4. [Threads management (7)](kernel/syscalls/threads.md)
      5. [Threads synchronization (8)](kernel/syscalls/sync.md)
      6. [Inter-process communication (12)](kernel/syscalls/ipc.md)
      7. [File operations (23)](kernel/syscalls/file.md (32))
      8. [Socket operations (13)](kernel/syscalls/socket.md)
      9. [Interrupts management (1)](kernel/syscalls/interrupts.md)
      10. [Performance monitoring (3)](kernel/syscalls/perf.md)
      11. [Time management (2)](kernel/syscalls/time.md)
      12. [Platform management (4)](kernel/syscalls/platform.md)
      13. [RISC-V specific (2)](kernel/syscalls/riscv.md)
   5. [Common routines](kernel/lib.md)
6. [Standard library](libc/README.md)
   1. [IEEE Std 1003.1-2017](libc/ieee_std_1003.1-2017.md)
   2. [Phoenix-RTOS](libc/phoenix-rtos.md)
   3. [GNU/Linux](libc/linux.md)
7. [Device drivers](devices/README.md)
   1. [Device server interface](devices/interface.md)
   2. [Accessing hardware](devices/hwaccess.md)
   3. [Handling interrupts](devices/interrupts.md)
8. [Filesystem servers](filesystems/README.md)
9. [Network stack](lwip/README.md)
10. [USB stack](usb/README.md)
11. [Utilities](utils/README.md)
    1. [psh](devices/psh.md)
    2. [psd](devices/psd.md)
12. [Host utilities](hostutils/README.md)
13. [Loader](loader/README.md)
14. [POSIX server](posixsrv.md)
15. [Ports](ports/README.md)
16. [Tests and testing process](tests/README.md)
17. [Coding convention](coding.md)


