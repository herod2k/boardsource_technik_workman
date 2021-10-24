# Herod2K Layout

Workman Layout for Boardsource Technik Ortholinear

## Compiling and flashing

1. Setup your QMK environment locally (https://docs.qmk.fm/#/newbs_getting_started)
2. Rename this folder to `herod2k`
3. Copy this folder inside: `qmk_firmware/keyboards/boardsource/technik_o/keymaps`
4. Put the keyboard in reset mode (LWR + Button on botton left angle)
5. From the project root folder launch the build using the docker utility:  

```
util/docker_build.sh boardsource/technik_o:herod2k:flash
```

### Edit the current configuration

Edit the `keyboard-layout.json` and generate a new file
```
qmk json2c -o keymap.c keyboard-layout.json
```

## Instructions

- LWR + RSE + Q: Reset mode

