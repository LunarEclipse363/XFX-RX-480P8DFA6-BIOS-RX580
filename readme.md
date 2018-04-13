# Modified BIOS for XFX RX480 GTR 8GB 1288MHz XXX
## Modifications comparing to stock bios:
- Changed card identifier to RX580
- Raised core clock to 1340MHz
- Tweaked fan curve
- Raised default power limit to 130W
- Lowered power limit control to 30%
- Tweaked memory timings (Uber v3.1 timings for Samsung memory)
- Added "Mckol" to card bootup message
## Disclaimer:
```
Your warranty is now void.

I am not responsible for bricked graphic cards, dead PSUs, 
thermonuclear war, or your house setting on fire because the GPU overheated. 
Please do some research if you have any concerns about BIOS modding before flashing it! 
YOU are choosing to make these modifications, 
and if you point the finger at me for messing up your GPU, I will laugh at you.
```
## Important information:
- Exact part number of the card this is based on: RX-480P8DFA6
- Take a backup before flashing. You can roll back to root commit to get it in case you lose it BTW.
- You shouldn't flash this on any other GPUs, you risk instability, the card not booting, or permanent damage
- This BIOS supports Samsung memory only
- Secure boot needs to be disabled for custom GPU BIOS
- The timings applied are very aggressive, if you need perfect stability, you should tweak the memory clock speed
- If you want to edit something, search for Polaris Bios Editor
