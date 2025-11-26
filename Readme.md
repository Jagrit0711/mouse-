This project is a completely DIY gaming mouse built around the Pixart PMW3360 sensor — the same kind used in premium gaming mice.
It’s open-source, fully customizable, and focuses on:

Ultra-low latency performance

No double-click problems

Lightweight design (around 55 g)

Fingertip-grip ergonomic shell

The mouse is powered by an RP2040 microcontroller (Raspberry Pi Pico) and uses 3D-printed parts for its body.

Main Features

✅ Zero-latency button debouncing (no double-clicks ever)
✅ 1000 Hz tracking speed (1 ms response time)
✅ Smart, lightweight design with custom 3D-printed shell
✅ Open-source hardware & firmware (you can tweak everything)
✅ Programmable DPI and button mappings

How It’s Built (Simplified Process)

3D Printing the Case

The shell (top, bottom, buttons, scroll wheel) is printed with PLA filament.

Use Cura or another slicer to make G-code.

Print one part at a time for best quality.

Electronics

Microcontroller: Raspberry Pi Pico (acts as the brain).

Sensor: Pixart PMW3360 (must be salvaged from another mouse).

Switches: 6 × Omron D2F-01F (for buttons).

Scroll Wheel Encoder: Alps-compatible 11 mm encoder.

Power: USB cable (wired connection).

Firmware

Written in C++ using Arduino IDE (2.x).

Special debounce algorithm = zero lag.

DPI currently hard-coded to 1200 (can be changed in code).
