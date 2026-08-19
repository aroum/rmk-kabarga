# Kabarga RMK Config

This is a configuration repository for the Kabarga keyboard using the RMK firmware.

> ⚠️ This is a **demo version** of the config and currently supports only the **Kabarga CE** variant.

The keymap defined in the config is currently a baseline placeholder. Due to matrix transformation details, full layout configuration is recommended to be done directly in **Vial**.

## Vial Unlock Combo

To unlock layout editing in **Vial**, press the **`Escape`** and **`5`** keys simultaneously (matrix positions `[0, 0]` and `[0, 5]`).

## Links

- [Official RMK Documentation](https://rmk.rs/)  
- [Kabarga Hardware Repository](https://github.com/aroum/kabarga)  
- [ZMK Firmware Config](https://github.com/aroum/zmk-kabarga)  

## Feature Support Table

| Feature             | Status |
| ------------------- | ------ |
| USB                 | ✅      |
| Bluetooth           | ✅      |
| Vial over USB       | ✅      |
| Vial over Bluetooth | ✅      |
| LED Indication      | ✅      |
| RGB                 | ❌      |

| LED # | Pin   | Function    |
| ----- | ----- | ----------- |
| 0     | P1_13 | Charge      |
| 1     | P1_11 | Num Lock    |
| 2     | P0_10 | Caps Lock   |
| 3     | P0_09 | Scroll Lock |

## Acknowledgements

Special thanks to everyone who helped with this config:

- [HaoboGu](https://github.com/HaoboGu)  
- [stickpro](https://github.com/stickpro)  
- [FT256](https://github.com/FT256)  
