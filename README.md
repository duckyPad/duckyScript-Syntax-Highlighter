# duckyPad duckyScript Syntax Highlighter

Provides **syntax highlighting** and **smart snippets** for **duckyScript** on [duckyPad macropads](https://duckypad.com).

Recommended when writing **longer and more complex** scripts.

## Command Palette Shortcut

To open **Command Palette**

* On **Windows/Linux**: Press `Control+Shift+P`
* On **macOS**: Press `Command+Shift+P`

## Install: Visual Studio Code

* [Download Latest Release](https://github.com/duckyPad/duckyScript-Syntax-Highlighter/releases/latest)
	* Pick `VS Code`
* In VS Code side bar, click `Extension` icon.

![Alt text](./resources/ext.png)
* Drag the `.vsix` file into the **extension list**
![Alt text](./resources/drag.png)

---

* Launch **Command Palette** again
* Start typing `Change Language Mode`, press enter.
* Start typing `duckyPad duckyScript`, press enter. 

## Install: Sublime Text

* [Download Latest Release](https://github.com/duckyPad/duckyScript-Syntax-Highlighter/releases/latest)
	* Pick `Sublime Text`
* Unzip
* Launch **Command Palette**
* Start typing `Browse Packages`, press `Enter`.
* Drag **`duckypad_duckyScript`** folder **AS-IS** into the window just opened

----------

* Launch **Command Palette** again
* Start typing "duckyPad" 
* Select `Set Syntax: duckyPad-duckyScript`

## Build

`vsce package`