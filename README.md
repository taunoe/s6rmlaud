# Sõrmlaud

The USB keyboard PCB has 8 row (R0 - R7 ) and 18 column pins (C0 - C17).

![Front PCB image](img/front.jpg)
![Back PCB image](img/back.jpg)

## Maping

 + |R0         |R1         |R2         |R3               |R4              |R5         |R6               |R7
---|---|---|---|---|---|---|---|---
C0 |pause      |tab        |a          |esc              |z               |<65314>    |ˇ                |1
C2 |q          |caps_lock  |s          |<                |x               |<65315>    |f1               |2
C15|w          |shift      |shift_r    |media_volume_down|media_volume_up |media_next |media_prev       |<269025153>
C3 |e          |f3         |d          |f4               |c               |<65319>    |f2               |3
C4 |r          |t          |f          |g                |v               |b          |5                |4
C5 |u          |y          |j          |h                |m               |n          |6                |7
C6 |i          |õ          |k          |f6               |,               |<0>        |'                |8
C7 |o          |f7         |l          |                 |.               |menu       |f8               |9
C14|+          |.          |enter      |up               |media_play_pause|left       |home             |end
C13|scroll_lock|6          |3          |.                |*               |-          |page_up          |page_down
C12|8          |<65437>5   |2          |0                |/               |right      |insert           |<269025071>
C11|7          |4          |1          |space            |num_lock        |down       |delete           |<269025066>
C10|<0>        |backspace  |'          |f11              |enter           |f12        |f9               |f10
C8 |p          |ü          |ö          |ä                |'               |-          |+                |0
C9 |scroll_lock|0          |           |alt              |                |<65027>    |0                |print_screen
C0 |pause      |<269025066>|alt        |<269025071>      |ctrl_r          |<269025067>|ctrl             |f5
C16|<269025049>|cmd (win)  |<269025063>|<65385>          |<269025062>     |<269025039>|media_volume_mute|<269025051>
C17|<65332>    |<269025072>|cmd_r      |<269025117>      |<269025045>     |<269025045>|<269025048>      |<65329>  

<269025049> Opens mail
<269025071> PC sleep
<269025066> PC OFF
<269025117> Open Home folder
<269025045> Stop ???
<269025045> Opens Calculator

## Links

- Ben Eater [So how does a PS/2 keyboard interface work?](https://www.youtube.com/watch?v=7aXbh9VUB3U)
- USB HID Keyboard scan codes as per USB spec 1.11 [usb_hid_keys.h](doc/usb_hid_keys.h)
- Windows Keyboard Scan Code Specification [usb_scancode.odf](doc/usb_scancode.odt)

__

Copyright Tauno Erik 2021 [taunoerik.art](https://taunoerik.art/)