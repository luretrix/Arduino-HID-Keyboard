# Arduino-HID-Keyboard
Arduino HID Project

![Arduino Uno R3 Pinouts](https://github.com/user-attachments/assets/e8337b5d-de47-4654-af83-a9a039d30b17)

Atmega82u som håndterer usb delen er konfigurert som seriell port i utgangspunktet.
Det er mulig å programmere den om til HID.
Det gjøres ved å kortslutte Atmega82u - Reset2 til GND

Bruk FLip software til å laste inn ny firmware på chip.

Dersom arduino sketch skal modifiseres, må atmega 82u flashes om til seriell først.
Litt tungvindt.

Det riktige vil være å heller bruke arduino som støtter HID i utgansgspunktet, som feks: Arduino Pro Micro.



https://www.youtube.com/watch?v=vn-Ulc1_YBM

https://mitchtech.net/arduino-usb-hid-keyboard/
