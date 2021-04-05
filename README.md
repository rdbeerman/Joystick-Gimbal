# Joystick-Gimbal

Based on okulele's gimbal design.

[Example Video](https://www.youtube.com/watch?v=j4P-fnCBcqE&feature=emb_title)


BoM & Notes:

- Bearing 6802zz * 4
- Bearing 685zz * 12

- M5x20 cross head/hex socket * 4
- M5x25 countersunk/hex socket * 6
- M5x25 cross head/hex socket * 3
- M5x35 cross head/hex socket * 4
- M5x30 cross head/hex socket * 1
- M5 nut * 18

- There are many options for sensors, I use ss495a's in combination with two 5x5mm neodynium magnets per axis for a total of 4.
- Housing has slots for a 60mm wide PCB, personally I used it for a protype board housing a ADS1115 ADC and arduino pro micro running arduino joystick library: https://github.com/MHeironimus/ArduinoJoystickLibrary
- gimbal_level_arm is sized to have the same thread size and mounting as a Thrustmaster Warthog base. 
- A 5/6 pin mini din connector such as this should slot in nicely: https://www.aliexpress.com/item/32848194244.html?spm=a2g0o.productlist.0.0.fdb0b70bCX6qXf&algo_pvid=4f3cc640-867a-458b-b886-f0e44da538c7&algo_expid=4f3cc640-867a-458b-b886-f0e44da538c7-18&btsid=2100bddd16176244921795739e2b2e&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_
