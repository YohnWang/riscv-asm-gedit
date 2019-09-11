# RISC-V asm highlight for gedit

RISC-V汇编在gedit编辑器中的语法高亮，只需把文件`riscv.lang`拷贝到`/usr/share/gtksourceview-3.0/language-specs`中

目前指令还未完善，指令来自`spike`项目中的`insn`文件夹，伪指令仅摘录手册中的部分常用指令

寄存器仅含有通用寄存器，浮点寄存器和控制与状态寄存器也不完善

> It is RISC-V assembly highlight for gedit, you just copy file `riscv.lang` to `/usr/share/gtksourceview-3.0/language-specs`.
>
> Instructions is incomplete. They are from floder `insn` of project `spike`.The pseudo-instruction only extracts some of the commonly used instructions in the manual.
>
> The register contains only general registers, and the floating-point registers and control and status registers are not perfect.

## Reference

### [riscv/riscv-isa-sim](https://github.com/riscv/riscv-isa-sim)

### [riscv/riscv-asm-manual](https://github.com/riscv/riscv-asm-manual)

### [riscv/riscv-isa-manual](https://github.com/riscv/riscv-isa-manual)

### [shinyquagsire23/asm-language](https://github.com/shinyquagsire23/asm-language)