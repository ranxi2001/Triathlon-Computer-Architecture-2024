# 学习资料


硬件资料：https://github.com/aolofsson/awesome-opensource-hardware


## AIB

- 数字电路仿真 
  - https://github.com/chipsalliance/aib-phy-hardware.git
  - https://github.com/chipsalliance/aib-protocols.git
- 模拟电路仿真
  - https://github.com/chipsalliance/aib-phy-generator.git
- aib资料
  - https://github.com/chipsalliance/AIB-specification.git

## CPU

- 铁人三项一期
  - 链接：https://pan.baidu.com/s/1mUYBN7NZCTb5-PBULQY1YQ?pwd=1234 
  - 提取码：1234 
- PULPino
  - https://github.com/pulp-platform/pulpino.git
- cva6
  - https://github.com/pulp-platform/cva6.git
    CVA6 是一个 6 级、单发射、有序 CPU，可实现 64 位 RISC-V 指令集。它完全实现了卷 I：用户级 ISA V 2.3 中指定的 I、M、A 和 C 扩展以及草案特权扩展 1.10。它实现了三个特权级别 M、S、U，以完全支持类 Unix 操作系统。
- tinyriscv
  - https://gitee.com/liangkangnan/tinyriscv?_from=gitee_search
- 蜂鸟
  - https://github.com/SI-RISCV/e200_opensource
- 木心
  - https://github.com/microdynamics-cpu/tree-core-ide
- 外设DDR
  - https://github.com/pulp-platform/serial_link.git

## 编译器和操作系统

- [RISC-V 手册-一本开源指令集的指南](.\RISC-V-Reader-Chinese-v1.pdf)
- [硬件描述语言——数字电路教程](https://vlab.ustc.edu.cn/guide/doc_verilog.html)
- 论文资料：
  - [The RISC-V Instruction Set Manual Volume I: Unprivileged ISA Document Version 20191213](./riscv-spec-20191213.pdf)
  - [The RISC-V Instruction Set Manual Volume II: Privileged Architecture 20211203](./riscv-privileged-20211203.pdf)

- 指令测试：
  - 1、riscv-tests：https://github.com/riscv-software-src/riscv-tests
  - 2、riscv-tools：https://github.com/riscv-software-src/riscv-tools
- 模拟器：
  - 1、riscv-isa-sim：https://github.com/riscv-software-src/riscv-isa-sim
- 编译器教程：
  - qemu：https://risc-v-getting-started-guide.readthedocs.io/en/latest/linux-qemu.html
- 编译器前端
  - https://juejin.cn/post/6958347736924192782
  - https://github.com/PacktPublishing/Learn-LLVM-12/tree/master/Chapter02/tinylang
- 中端
  - https://www.bilibili.com/video/BV1b7411K7P4/
  - https://www.youtube.com/watch?v=S_OeRTePeXg&list=PL0qj8UdnOw30ZGMcM6DwvM1J2tttyy_D6
- 后端
  -  https://github.com/kobayashi-compiler/kobayashi-compiler/tree/main/src/backend
- 实验最低要求
  - https://github.com/Jiantastic/c-to-mips-compiler   MIPS 的 C 编译器 采用了开源前端工具 flex 和 Bison
  - https://github.com/whatlulumomo/MiniCompiler  MIPS 架构的 C 编译器，实现了前端，LLVM 后端和自行设计的后端
- 支持 RISC-V 的编译器
  - Rust 支持 RV32IMC 官方支持
  - Clang LLVM 支持 RV32IMC 官方支持
  - GCC 支持 RV32IMC https://github.com/riscv-collab/riscv-gnu-toolchain
- 操作系统
  - https://www.bilibili.com/video/BV1Q5411w7z5?vd_source=ba4ea5e27f6f24509b43e9fb048796e8
  - https://github.com/manbing/mini-riscv-os
  - https://github.com/swetland/os-workshop
  - https://gist.github.com/cb372/5f6bf16ca0682541260ae52fc11ea3bb
  - https://github.com/mit-pdos/xv6-riscv
  - https://github.com/chyyuu/os_kernel_lab

