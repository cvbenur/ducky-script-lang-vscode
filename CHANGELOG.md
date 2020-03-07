# Change Log

All notable changes to the **Ducky Script Language for VSCode** extension will be documented in this file.

<br>

## 1.0.4 - March 7th, 2020

Added an icon to the extension. It can be found under `./img/icon.png`.

<br>

## 1.0.2 - March 6th, 2020

Improved detection of single-line command/letter key combinations.

Certain combinations would not get detected in cases with more than 2 successive commands/letter keys.
In those cases, only the 2 first instructions of each line woud get detected.
> **E.g.** `CTRL ALT DELETE` would only detect `CTRL ALT`.

Detection now works for potentially infinite single-line command/letter key combinations.

<br>

## 1.0.1 - March 4th, 2020

Improved detection of error-prone keyword use cases.

Certain inline keyword combinations resulted in false positives, and thus errors in highlighting.
> **E.g.** Certain `REM` lines would highlight other keywords and variables instead of treating them as comments.

<br>

## 1.0.0 - March 4th, 2020

Initial release of the **Ducky Script Language for VSCode** extension.
