Sure! Here’s a more concise version in English:

---

### Changes Made

1. **LED Pin Change (`LED_PAD`)**

   * Changed from GPIO 0 to **GPIO 25** to use the Pico’s **built-in LED**:

     ```c
     #define LED_PAD 25
     ```
   * Allows direct observation of LED patterns without external components.

2. **Added Name and Student ID**

   * Prints your identity at startup:

     ```c
     printf("DRAME SOLO F14218806\n");
     fflush(stdout);
     ```
   * `fflush(stdout);` ensures the output appears immediately on the USB terminal.

3. **Impact**

   * All other functionality, including **CounterAgent blinking and FreeRTOS tasks**, remains unchanged.
   * Enhances visibility of LED patterns and clearly identifies the project owner.
