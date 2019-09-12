# RISC-V asm highlight for gedit

RISC-V汇编在gedit编辑器中的语法高亮，只需把文件`riscv.lang`拷贝到`/usr/share/gtksourceview-3.0/language-specs`中

支持的指令和寄存器从`riscv-asm-manual`中提取，文件分别是`instr-table.tex`和`priv-csrs.tex`

汇编程序指令和重定位函数参考`riscv-isa-manual`

本项目参考`shinyquagsire23/asm-language`，由该项目的`asm.lang`修改

> It is RISC-V assembly highlight for gedit, to use you just copy file `riscv.lang` to `/usr/share/gtksourceview-3.0/language-specs`.
>
> Supporting instructions and registers are from files `instr-table.tex` and `priv-csrs.tex` in  `riscv-asm-manual`. 
>
> Pseudo operations and relocation functions refer to `riscv-isa-manual`.
>
> This project is modified by repository `shinyquagsire23/asm-language` file `asm.lang`

## Reference

### [riscv/riscv-asm-manual](https://github.com/riscv/riscv-asm-manual)

### [riscv/riscv-isa-manual](https://github.com/riscv/riscv-isa-manual)

### [shinyquagsire23/asm-language](https://github.com/shinyquagsire23/asm-language)