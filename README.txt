This is the repo for the contols PCB which will control the valves and safety features for the hybrid engine.

PCB Requirements:
 - Take input from a Raspberry Pi (VERSION)
    - Most likely to use I2C protocaul for ease of implementation
 - Output to a driver the commands for the stepper motors being used
 - Take imput form limit switches on the position of the stepper motors, and subsequently the valces
 - Output valce states to LEDs (on = open, off = closed), seperate from board to enable mounting in case
 - Output any ideal diagnostic information to LEDs, can be mounted to board
 - Provide control for 7 stepper motors, each with 2 limit switches, 1 button for manual control, and at least 1 state LED
 - Ideally provide a modular design to enable adding an 8th or 9th motor (with acconpanying LED, limit switches, button) in the future
 - Upload files to Github periodically to ensure version control is kept
 - Will be powered by a 12V or 0-45V power supply
 - Wire Guages: FILL IN
 - Stepper motor: PT NNUMBER
    - Motors take 30V input
 - Limit switch: PT NUMBER
