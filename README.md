# Shortcut to open Neovide on Mac

## Steps

- Make the terminal to be able to exit if nothing wrong
  - [Step 1 image](https://github.com/t1gu1/Neovide-Mac-shortcut/blob/main/terminal-accept-exit-step1.png)
  - [Step 2 image](https://github.com/t1gu1/Neovide-Mac-shortcut/assets/12479055/f444026a-e090-45d6-9d8c-0309cdd6ccc2)
- Accept terminal as Developper tool
  - [image](https://github.com/t1gu1/Neovide-Mac-shortcut/assets/12479055/4c2508d0-42b0-40a9-ba2f-39a078e9b3a9)
- Create an Automator Script
  - Open Automator (pre-installed on mac)
  - Create executable AppleScript
    - The content of the appleScript: ```
tell application "Terminal"
	activate
	do script "neovide && exit"
end tell
```
- Export the script




