# Ducky Script Language for VSCode

This extension enables syntax highlighting for the **Ducky Script** scripting language, allowing for easier and more efficient scripting.
<br>

## Features

This extension works with **.txt files**.

Syntax detection features :
*   Detection and highlighting for **comment lines** (`REM` lines),
*   Detection and highlighting for **control keys** (`ENTER`, `ESC`, `GUI`, `ALT`, `CTRL` and so on  -- detailed list below),
*   Detection and highlighting for **timer commands** (`DELAY`, `DEFAULTDELAY`, `REPEAT` and so on -- detailed list below),
*   Detection and highlighting for **strings** (`STRING` lines).

Detailed list of supported commands :

| Keyword                           | Category | Behaviour                               |
| --------------------------------- | :------- | --------------------------------------- |
| `REM`                             | Comment  | Turns the line into a comment           |
| `STRING`                          | Variable | Detects the following value as a string |
| `DELAY`                           | Variable | Detects the following value as a number |
| `DEFAULTDELAY` or `DEFAULT_DELAY` | Variable | Detects the following value as a number |
| `REPEAT`                          | Variable | Detects the following value as a number |
| `GUI`                             | Key      | Detects a keyboard key                  |
| `WINDOWS`                         | Key      | Detects a keyboard key                  |
| `APP`                             | Key      | Detects a keyboard key                  |
| `MENU`                            | Key      | Detects a keyboard key                  |
| `SHIFT`                           | Key      | Detects a keyboard key                  |
| `ALT`                             | Key      | Detects a keyboard key                  |
| `CTRL` or `CONTROL`               | Key      | Detects a keyboard key                  |
| `DOWNARROW` or `DOWN`             | Key      | Detects a keyboard key                  |
| `UPARROW` or `UP`                 | Key      | Detects a keyboard key                  |
| `LEFTARROW` or `LEFT`             | Key      | Detects a keyboard key                  |
| `RIGHTARROW` or `RIGHT`           | Key      | Detects a keyboard key                  |
| `BREAK`                           | Key      | Detects a keyboard key                  |
| `PAUSE`                           | Key      | Detects a keyboard key                  |
| `CAPSLOCK`                        | Key      | Detects a keyboard key                  |
| `DELETE`                          | Key      | Detects a keyboard key                  |
| `END`                             | Key      | Detects a keyboard key                  |
| `ENTER`                           | Key      | Detects a keyboard key                  |
| `ESCAPE` or `ESC`                 | Key      | Detects a keyboard key                  |
| `HOME`                            | Key      | Detects a keyboard key                  |
| `INSERT`                          | Key      | Detects a keyboard key                  |
| `NUMLOCK`                         | Key      | Detects a keyboard key                  |
| `PAGEUP`                          | Key      | Detects a keyboard key                  |
| `PAGEDOWN`                        | Key      | Detects a keyboard key                  |
| `PRINTSCREEN`                     | Key      | Detects a keyboard key                  |
| `SCROLLLOCK`                      | Key      | Detects a keyboard key                  |
| `SPACE`                           | Key      | Detects a keyboard key                  |
| `TAB`                             | Key      | Detects a keyboard key                  |

## Known Issues

This extension does not yet provide syntax error detection, the problematic phrases are just **not highlighted**.

<br>

## Releases

### 1.0.0 - March 3rd, 2020

Initial release of the **Ducky Script Language for VSCode** extension.

<br>

### About this extension

Written by **Ruben Nabet**. The source code to this extension is free to download and tweak or customize for your personnal use only.

This is my very first extension, so feedback is much appreciated ! :)

**Enjoy!**
