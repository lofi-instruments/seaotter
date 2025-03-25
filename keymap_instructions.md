# How to Change Keymaps
[日本語版ページはこちら(Click here for Japanese Instructions)](https://github.com/lofi-instruments/seaotter/blob/main/keymap_instructions_ja.md)

## Via

1. **Download and Install Via / Use Via in Browser**  
   - [Via official website](https://caniusevia.com/)

2. **Connect Your Keyboard**  
   - Plug in your Sea Otter Keyboard to your PC and ensure it's connected properly.
      **Note:**  the USB to your computer without pressing any key switches.
(If you press and hold a key while connecting, the keyboard will enter bootloader mode. Bootloader mode is used when rewriting the entire program, not for changing keymaps. In bootloader mode, the key will not respond, and the keyboard will return to normal mode after 6 seconds.)

3. **Upload the json file**  
   "SETTINGS" tab > Show Design Tab > "DESIGN" tab > Load Draft Definition > Upload the "[SeaOtter_via.json](https://github.com/lofi-instruments/seaotter/blob/main/codes/SeaOtter_via.json)" file

4. **Change the keymaps**  
   "CONFIGURE" tab > Click the square representing the one key displayed at the top of the screen (the selected key will blink faintly) > From the list of keycodes at the bottom of the screen, select and click the one you want to change > Verify that the new key is assigned to the one key displayed at the top.

5. **Confirm the new keymap has been applied**  
   "KEY TESTER" tab > Press the switch on the Sea Otter Keyboard > Confirm that the newly assigned key position turns purple on the screen.

With that, the keymap change is complete.

----

## Remap

1. **Access the Remap website**  
   - [Remap official website](https://remap-keys.app/)

2. **Connect the Keyboard**  
   - Plug in your Sea Otter Keyboard to your PC and ensure it's connected properly.
     **Note:** Connect the USB to your computer without pressing any key switches.  
   (If you press and hold a key while connecting, the keyboard will enter bootloader mode. Bootloader mode is used for reprogramming the entire firmware, not for changing keymaps. In bootloader mode, the key will not respond, and the keyboard will return to normal mode after 6 seconds.)
   - Click the "Customize Keyboard" button.

4. **Upload the json file**  
   After downloading the "[SeaOtter_remap.json](https://github.com/lofi-instruments/seaotter/blob/main/codes/SeaOtter_remap.json)" file, either drop the json file in the square area in the center of the browser window or click the "Import (.JSON)" button to upload the json file.

5. **Change the keymaps**  
   Click the square representing the one key displayed at the top of the screen (the selected key will turn blue) > Enter the desired keycode for the change or select the keycode from the list at the bottom of the screen, then drag and drop it onto the one key displayed at the top > Confirm that the new key has been assigned to the one key displayed at the top.

6. **Write the keymap**  
   Click the "Write" button in the top-right corner of the screen.

With that, the keymap change is complete.

