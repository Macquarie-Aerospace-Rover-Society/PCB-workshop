# Pinouts in tabular form

Symbols, Row number centered on 5V == Row1.

|Sym|Meaning|
|-|-|
|G|GPIO Pin|
|GND|Common reference ground|
|5V|Directly tied to USB 5V|
|3V3|Regulated 3.3V|
|RX?|UART recieve pin for ?|
|TX?|UART transmit pin for ?|
|USB?| USB data positive or negative|
|LED| Builtin LED, allegedly RGB LED|
|STRAP|Strapping pins, need to have certain values at startup|
|JTAG|Strapping pin to enable JTAG|
|J|JTAG Debugging pins|

## ESP32-S3-DevKitC-1

Total PCB width: 25.4, 1.27 in from each edge. 25.4 - 2 * 1.27 = 22.86

|Row|Left|Right|
|-|-|-|
|21|3V3|GND|
|20|3V3|GTX0|
|19|RST|GRX0|
|18|G|G|
|17|G|G|
|16|G|GJ|
|15|G|GJ|
|14|G|GJ|
|13|G|GJ|
|12|GTX1|G|
|11|GRX1|G|
|10|G|G|
|9 |GJTAG|G|
|8 |GSTRAP|GSTRAP|
|7 |G|GSTRAP|
|6 |G|GLED|
|5 |G|G|
|4 |G|G|
|3 |G|GUSB-|
|2 |G|GUSB+|
|1 |5V|GND|
|0 |GND|GND|

## ESP32-DevKitC-v4

Column to Column seperation: 25.4

## ESP32 dev kit v1




