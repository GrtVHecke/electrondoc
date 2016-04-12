# electrondoc
Particle Electron pinout source code documentation file

## Pinout
                     ┌─────┐
     ┌───────┬─────┬─┤ USB ├───────┐
     │ ● Li+ │ • • │ └─────┘VUSB ● │
    ─┤ ○ VIN └─────┘         3V3 ○ ├─
    ─┤ ○ GND                 RST ○ ├─
    ─┤ ○ TX                 VBAT ○ ├─
    ─┤ ○ RX                  GND ○ ├─
    ─┤ ○ WKP  ◙     □     ◙   D7 ○ ├─
    ─┤ ○ DAC  MODE    RESET   D6 ○ ├─
    ─┤ ○ A5 ┌───────────────┐ D5 ○ ├─
    ─┤ ○ A4 │    Electron   │ D4 ○ ├─
    ─┤ ○ A3 │               │ D3 ○ ├─
    ─┤ ○ A2 │               │ D2 ○ ├─
    ─┤ ○ A1 │               │ D1 ○ ├─
    ─┤ ○ A0 │               │ D0 ○ ├─
    ─┤ ○ B5 │               │ C5 ○ ├─
    ─┤ ○ B4 │               │ C4 ○ ├─
    ─┤ ○ B3 │               │ C3 ○ ├─
    ─┤ ○ B2 │ µblox         │ C2 ○ ├─
    ─┤ ○ B1 └───────────────┘ C1 ○ ├─
    ─┤ ○ B0    ┌───┐          C0 ○ ├─
     │         │ ○ │               │
     │         └───┘           *   │
      \___________________________/

## License
GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
