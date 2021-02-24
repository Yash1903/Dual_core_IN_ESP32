# Dual_core_IN_ESP32
in the code i create two tasks and assign one task to core 0 and another to core 1. Arduino sketches run on core 1 by default. So, you could write the code for Task2 in the loop() (there was no need to create another task). In this case i create two different tasks for learning purposes.
