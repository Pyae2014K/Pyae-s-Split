# Pyae-s-Split

My split keyboard is a Corne like wired split keyboard.
It uses QMK firmware

It serves as a split keyboard that I can use to type on without getting sore quickly.

## Features:
- 42 Hot-swappable keys
- 3 Thumb keys on each side
- A TRRS cable for the two different parts to communicate
- [VIA](https://www.caniusevia.com/) support
- Doesn't need a case, only a PCB

## PCB:
My PC was made in Kicad

Schematic

<img width="1436" height="698" alt="Screenshot 2026-10-15 210148" src="https://github.com/user-attachments/assets/c9ef6606-edd2-40d6-88bb-41ab10eb847d" />


PCB

<img width="1163" height="362" alt="Screenshot 2026-10-16 201650" src="https://github.com/user-attachments/assets/3318d418-bc51-4d20-9fdc-683287ae87f6" />


I used [Joe Scotto's](https://www.youtube.com/@joe_scotto) footprints for most of my footprints.

## Firmware
This macropad uses [QMK](https://qmk.fm/) firmware.
- 42 keys
- Split functionality
- TRRS for intercommunication

## BOM:
Here is everything needed to make it.
| Qty | Part | Description | Price | Store |
|-----:|-----|-------------|-------|-------|
| 2 | Custom PCB | One left and one right board | $ 38.93 |  [JLCPCB](https://jlcpcb.com/) |
| 2 | Seeed XIAO RP2040 | Microcontroller | $ 5.00 | [HolyKeebs](https://holykeebs.com/products/xiao-rp2040?variant=49206715318562) |
| 45 | MX-Style Switches | Mechanical keyboard switch | $ 13.99 | [Amazon](https://www.amazon.com/gp/product/B0DP62N1RS/ref=ox_sc_act_title_1?smid=A1QXFO5SK4EVQJ&psc=1) |
| 50 | Kailh Hotswap Sockets | Hot-swap sockets | $ 6.25 | [HolyKeebs](https://holykeebs.com/products/kailh-mx-hotswap-sockets-10-pack?variant=45420412895522) |
| 40 | XDA Keycaps | XDA profile keycap | $ 14.00 | [HolyKeebs](https://holykeebs.com/products/xda-blank-keycaps?variant=48811660804386) |
| 2 | Homing XDA Keycaps | XDA profile keycap | $ 1.00 | [HolyKeebs](https://holykeebs.com/products/xda-blank-keycaps?variant=48811660837154) |
| 50 | 1N4148 Diodes | DO-35 through-hole diode | $ 0.43 | [LCSC](https://www.lcsc.com/product-detail/Switching-Diodes_luJing-1N4148_C49318123.html) |
| 2 | TRRS Port | Allows the halves to communicate | $ 0.13 | [LCSC](https://www.lcsc.com/product-detail/C22355837.html) |
| 1 | TRRS Male to Male Cable | Cable | $ 5.00 | [HolyKeebs](https://holykeebs.com/products/trrs-cable?variant=50301002875170) |
