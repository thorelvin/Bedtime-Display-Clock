This is for installing on a kids room, when it says "OK" its rise and shine time.

Printed a box for it that shows only screen. Powered by a 5V usb charger.


Bedtime + Time Split Frames with Auto-DST & Blinking Colon

  - 22:00–05:59: show X then time
  - 06:00–21:59: show OK then time
  - During time-phase (4s), split into two 2s sub-frames:
    * First 2s: hours and blinking colon ("16 :")
    * Next 2s: minutes ("19"), displayed on the right side with a space between digits
  Automatically adjusts between CET (UTC+1) and CEST (UTC+2).
