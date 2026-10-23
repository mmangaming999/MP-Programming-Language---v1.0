# MP Language v0.2.0

VS Code editing support for **MP** files (`.mp`).

## Features
- Syntax highlighting for MP keywords (`if`, `do`, `Make`, `for`, `Long`, `times`, `index`, `set`, `to`, `change`, `by`), built-in `say()` calls, strings, comments, numbers and function calls.
- Plain keyword completions and statement snippets. Press **Ctrl+Space** if suggestions are not displayed while typing.
- Optional **MP Blue Dark** theme that paints MP syntax keywords blue. Enable via **Preferences: Color Theme**. A normal theme may choose different keyword colors.
- Bracket pairs and auto-indent.

## Install
1. Open VS Code -> Extensions (`Ctrl+Shift+X`).
2. Click the `...` menu -> **Install from VSIX...** -> choose `mp-language-0.2.0.vsix`.
3. Create a `.mp` file. Verify the language mode is MP in the status bar.
4. Press `Ctrl+Shift+P`, search **Preferences: Color Theme**, and choose **MP Blue Dark** to make keywords blue.
5. Type `d`, `s` or `M` and check suggestions. Press `Ctrl+Space` if needed.

## Notes
This is a **language editor extension**, not an MP interpreter. The theme affects all editors while selected, though its special syntax rules only target MP. Word-based suggestions can also come from VS Code's built-in word completion.
