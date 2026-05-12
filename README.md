# Toggle Auto-Lock

https://www.icloud.com/shortcuts/476814ed526f461abd648558910eaf11

Shortcut for Control Center on iOS that first takes you to Settings › Display & Brightness › Auto-Lock, then when you have chosen a setting, the shortcut renames itself to reflect the new auto-lock state, and afterwards you are returned to where you launched the shortcut from (either the previous app or the home screen)

When adding it to Control Center, make sure not to shrink it from widget size to icon size, or you won’t be able see the current auto-lock state

Limitations
- If you change the auto-lock settings without going through the Control Center widget, it’s name won’t be updated to reflect the new state – it will be corrected the next time you use it though
- The shortcut will stop working if you change it’s name to something else (unless you also edit all the name related actions in the shortcut)
- If you try to test run the shortcut from inside the iPhone Mirroring app on macOS, you won’t be returned to the previous app since the Get Current App action currently doesn’t work there
