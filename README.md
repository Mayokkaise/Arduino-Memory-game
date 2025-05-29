# Arduino-Memory-game
This uses an arduino uno r3 with a few buttons, leds, and a buzzer to make a fun memory game.

## Hardware required
- Arduino board
- Breadboard
- 3 leds of different colors
- 3 push-buttons
- 1 buzzer (I used an active buzzer, but passive is also okay)
- 3 220 ohm resistors
- 1 70 ohm resistors (or you can put 3 220 ohm resistors in parallel)
- 8 wires

  ## Steps to make the hardware
  Connect the 3 buttons on the breadboard. Connect the leds according to the video. Connect the buzzer. When wiring, place the led and button wires side by side (on the digital pins) for easy coding. Make sure to wire the buzzer to a pin with PWM (pulse-width-modulation).

  ## Software
  Use the code provided in the .ino file. If you want to change the pins, you can change them in the top, and make sure to change them for the buzzer sounds too. You can also change the notes the buzzer will make by changing the frequency.
