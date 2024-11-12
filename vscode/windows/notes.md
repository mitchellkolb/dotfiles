



On Windows, the settings.json and keybindings.json files for Visual Studio Code are stored in your user directory. Here are their full paths:


settings.json
C:\Users\<YourUsername>\AppData\Roaming\Code\User\settings.json

keybindings.json
C:\Users\<YourUsername>\AppData\Roaming\Code\User\keybindings.json





Use the program microsoft powertoys to unbind and the caps lock key to the Esc key to make the vim experience less painful:

Remap Caps Lock to Escape in PowerToys (for VSCode)

    - Install Microsoft PowerToys (if you haven’t already), you can get it from the microsoft store which is the easiest. Then open it and navigate to the Keyboard Manager section.
    - Select Remap a key to add a new key mapping.
    - Click the + icon to create a new remapping.
    - For Key (on the left), choose Caps Lock.
    - For Mapped To (on the right), choose Escape.
    - Click OK to save this mapping.
    - (Optional) If you only want this remapping to apply when VSCode is active, go to Remap shortcuts instead and specify VSCode as the targeted application.
