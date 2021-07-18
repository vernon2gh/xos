This is XOS project, base RISC-V qemu virt machine, include function, as follow:

* Allocated pages managed by array
* Allocated bytes managed by list
* running task by FIFO scheduler, max task is 10
    * Cooperative Multitasking from Machine software interrupt
    * Preemptive Multitasking from Machine timer interrupt
* running trap
* external interrupt uart0 by PLIC device
* hardware timer
* software timer
* interrupt lock
* syscall from User-mode level