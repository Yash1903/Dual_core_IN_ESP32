# Dual_core_IN_ESP32
The ESP32 comes with 2 Xtensa 32-bit LX6 microprocessors: core 0 and core 1. So, it is dual core. When we run code on Arduino IDE, by default, it runs on core 1. In this post we’ll show you how to run code on the ESP32 second core by creating tasks. You can run pieces of code simultaneously on both cores, and make your ESP32 multitasking

#Note: in the code we create two tasks and assign one task to core 0 and another to core 1. Arduino sketches run on core 1 by default. So, you could write the code for Task2 in the loop() (there was no need to create another task). In this case we create two different tasks for learning purposes.

However, depending on your project requirements, it may be more practical to organize your code in tasks as demonstrated in this example.
