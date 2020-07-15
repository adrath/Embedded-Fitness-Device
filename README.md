# Embedded-Fitness-Device

An embedded RTOS fitness device written on an MSP432 amd Educational BoosterPack MKII. Uses a round robin scheduler with 
blocking semaphores, thread sleeping, FIFO queues and periodic event tasks with dedicated timer interrupts. A virtual logic analyzer 
used to assist in debugging. Written in C and ARM assembly.

<img src="./fitness_device_data_flow.png">
