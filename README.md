# ledleafs

Please note, this repo is shared as-is, no guarantees

a few attention points to the schematic and pcb that might need fixing
- check your LEDs, WS2812(RGB) vs SK6812(RGBWW), the footprint is 180deg rotated, no change in PCB needed just rotate the components (PCB desgin = WS2812)
- esp32C3 super micro doesn't want to boot when moounted with all pads (no clue why, nothing is connected except power and GPIO), I swapped it out for a Seeed-studio XAIO ESP32 with external antenna
- level shifter not assembled, just hot-wired GPIO of ESP directly to LED1
- no VEML (light sensor support in WLED)

parts used (non affiliate links)
- Conenctors: [https://vi.aliexpress.com/item/1005006028155508.html](https://vi.aliexpress.com/item/1005006028155508.html)https://vi.aliexpress.com/item/1005006028155508.html
- Switches: [https://vi.aliexpress.com/item/4001161324412.html](https://vi.aliexpress.com/item/4001161324412.html)https://vi.aliexpress.com/item/4001161324412.html
- LEDs: [https://vi.aliexpress.com/item/32641663497.html](https://vi.aliexpress.com/item/32641663497.html)https://vi.aliexpress.com/item/32641663497.html
- wires: [https://vi.aliexpress.com/item/1005006125634331.html](https://vi.aliexpress.com/item/1005006125634331.html)https://vi.aliexpress.com/item/1005006125634331.html

