# Kabarga RMK Config

This is a configuration repository for the Kabarga keyboard using the RMK firmware.

> ⚠️ This is a **demo version** of the config and currently supports only the **Kabarga CE** variant.

The keymap defined in the config is currently a baseline placeholder. Due to matrix transformation details, full layout configuration is recommended to be done directly in **Vial**.

## Vial Unlock Combo

To unlock layout editing in **Vial**, press the **`Escape`** and **`5`** keys simultaneously (matrix positions `[0, 0]` and `[0, 5]`).

## Bluetooth Controls

Bluetooth profile controls are mapped on **Layer 1** (accessed via `MO(1)`):
- **`1`**: Switch to Profile 0 (`BT0` / `User0`)
- **`2`**: Switch to Profile 1 (`BT1` / `User1`)
- **`3`**: Switch to Profile 2 (`BT2` / `User2`)
- **`5`**: Clear current profile bonding (`Clear BT` / `User5`)
- **`Tab`**: Toggle output mode between USB and Bluetooth (`Switch Output` / `User6`)

> 💡 **In Vial GUI:** Bluetooth keycodes (`BT0`–`BT7`, `Next BT`, `Prev BT`, `Clear BT`, `Switch Output`) are also accessible under the **User** keycode tab in Vial and can be freely assigned to any key or layer.

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
