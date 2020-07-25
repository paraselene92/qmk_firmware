# qmk_firmware

This repository is qmk_firmware(keybord firmware) and is cloned [qmk/qmk_firmware](https://github.com/qmk/qmk_firmware).

For managing own keymap settings.

## How to edit keymaps.(for lily58pro)

1. Edit `keyboards/lily58/keymaps/paraselene92/keymap.c`.
2. Execute 

```
cd qmk_firmware
make lily58:paraselene92`
```

3. Generated `qmk_firmware/lily58_rev1_paraselene92.hex`
4. Write firmware(hex file) using tools (`QMK Toolbox`)

- Local File: Set hex file
- MCU: (anything)

5. Press the reset switch(white switch) on the keyboard.
6. Push Tools `Flash` button.


