# Hardware
This repository contains schematics, board layout and the BOM
## Expansion Headers
Blinkenrocket features expansion headers which makes un-used pins available for use. Pins are broken out on standard 2.54mm pin headers (need to be soldered on separately). VCC and GND are added for convenience. If you look at the CPU on the back the layout is as follows:

```
VCC                     VCC
E1         [CPU]         E3
E2         [CPU]         E4
GND                     GND
```

The pins map to the following pins on the microcontroller:

E1: PC0 (ADC0/PCINT8)

E2: PC1 (ADC1/PCINT9)

E3: PC2 (ADC2/PCINT10)

E4: PA1 (ADC7/PCINT25)
