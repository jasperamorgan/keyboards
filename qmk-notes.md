# Define keymap JSON (in QMK Configurator)

Use the QMK configurator to define the keymap for the board. 

Download the keymap as a JSON file.

# Convert keymap JSON to QMK Keymap

```
qmk json2c keymap.c
```

# Flash on command line

https://docs.qmk.fm/#/newbs_flashing?id=flash-your-keyboard-from-the-command-line

```
qmk flash -kb <my_keyboard> -km <my_keymap>
```
