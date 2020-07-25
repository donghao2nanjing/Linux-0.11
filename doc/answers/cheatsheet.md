## Registers

* SS : stack segment, points to the area of memory that will be used for the stack.
* EIP : Extended Instruction Pointer, points to the first byte of the next instruction to be executed.
* ESP : Extended Stack Pointer, points to the top of the stack. 
    * ESP is the 32 bits version of the 16bit SP register.
* FLAGS: 16 bits flag register
* EFLAGS: Extra FLAGS, 32 bits flags register, successor of FLAGS 
* RFLAGS: Reserved FLAGS, 64 bits flags register, successor of FLAGS 

## References

[Registers](https://wiki.skullsecurity.org/index.php?title=Registers#eax)