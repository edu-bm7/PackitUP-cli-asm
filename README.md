# PackitUP-cli-asm
PackItUP!-cli in assembly code, just for fun
## Rules for this project:
-  Your functions should not quit unexpectedly (segmentation fault, bus error, double
free, etc) apart from undefined behaviors.
-  Your Makefile must at least contain the rules $(NAME), all, clean, fclean and
re. And must recompile/relink only necessary files.
- You must write 64 bits ASM. Beware of the "calling convention".
- You can’t do inline ASM, you must do ’.s’ files.
- You must compile your assembly code with nasm.
- You must use the Intel syntax, not the AT&T
- You must check for errors during syscalls and properly set them when needed
- Your code must set the variable errno properly.
- For that, you are allowed to call the extern **___error** or **errno_location**
- **It is forbidden to use the compilation flag: -no-pie.**
