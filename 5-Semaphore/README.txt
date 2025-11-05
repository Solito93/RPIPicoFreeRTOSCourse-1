GPIO Change:

-Original: LED on GPIO 0 (LED_PAD).
-New: Main LED on GPIO 2, with additional LEDs on pins 3, 4, 5, and 6.



Added LED (worker4):

-Original: 3 LEDs controlled.
-New: 4 LEDs, with a fourth BlinkWorker for LED 4.



Semaphore:

-Original: Semaphore with a maximum of 3.
-New: Semaphore with a maximum of 4, allowing better resource management.



User Information:

-New: Display of user information such as name and student ID to identify the code's author.
