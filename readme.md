# Modified BIOS for XFX RX480 GTR 8GB 1288MHz XXX
## Modifications comparing to stock bios:
- Changed card identifier to RX580
- Raised core clock to 1340MHz
- Tweaked fan curve to prevent overheating
- Raised default power limit to 130W to avoid throttling
- Lowered power limit control to 30% to prevent board damage
- Tweaked memory timings (Uber v3.1 timings for Samsung memory)
- Added "Mckol" to card bootup message
## Important information:
- Exact part number of the card this is based on: RX-480P8DFA6
- You shouldn't flash this on any other GPUs, you risk permanent malfunction, the card not booting, or permanent damage
- This BIOS supports Samsung memory only
- Secure boot needs to be disabled for custom GPU BIOS
- There are some memory errors at 2000MHz on my GPU. None at 1985MHz. You should check how your card's memory responds to these timings.
- The max core voltage wasn't increased to RX580 default (actually 1200mV was unstable for me, too high)
