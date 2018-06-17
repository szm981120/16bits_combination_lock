# 16bits_combination_lock
This is a combination lock with a password of 16-bit binary.
Inputs:
1. 16 switches for password input.
2. 'set_pwd' button for set a password.
3. 'if_right' button for try to unlock.
4. 'reset' button for reset all the light.
5. 'show_present_pwd' button for show the present correct password.

Outputs:
1. 'green' light for the unlock state.
2. 'red' light for the lock state.
3. 'warning' light for the warning state.
4. 'led_light' light for showing the countdown.
5. 'led_present_pwd' light for showing the present password input or the correct password.

Functions:
1. Push the 'set_pwd' button. Store the present switches status into the password.
2. Push the 'if_right' button. Judge whether the present switches status is the same as the password.
3. If the judge is right, then green lights up while red and warning are off.
4. If the judge is wrong, then red lights up while green and warning are off.
  Meanwhile, the countdown begins from 5.
5. If the agent can't unlock the lock in 5 seconds, which means when the countdown is over, the green light is still off,
  the red and warning light up and green is still off.
6. If the agent unlocks the lock in 5 seconds, the green lights up and red and warning are off.
  Besides, the countdown stops.
7. At any time, push the 'reset' button, then green, red and warning are off. The countdown is reset at 5.
8. At any time, there are four leds showing the present switches status(4 Hexadecimal numbers).
  Press the 'show_present_pwd' button, then these 4 leds will show the correct password.

Thank you!

Author: Shen Ziming
Student ID: 1170301007
