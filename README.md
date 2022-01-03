# UnifiedShortcuts

Unified keyboard Shortcuts table for VSCode and PyCharm

# Shortcuts draft table

Symbols definitions:

- ✖: Not available for current IDE
- ✅: Available and configured
- ⛔: Available and **not** configured

Key binding meaning.
For example, `Ctrl+Shift+H` means pressing `Ctrl`, `Shift` and `H` key simultaniously.
In other hand, `Ctrl+B Ctrl+H` means a sequence of shortcuts.
First (prefix) binding is `Ctrl+B` and the second is `Ctrl+H`.

## General hotkeys

| Name                               | Key binding           | VSCode | IDEA | Vim         |
| ---------------------------------- | --------------------- | ------ | ---- | ----------- |
| New Window                         | `Ctrl+Shift+N`        | ✅     | ✖    | ✖           |
| Close Application                  | `Alt+F4`              | ✅     | ✅   | `:qa`       |
| **S**ettings                       | `Ctrl+Alt+S`          | ✅     | ✅   | ✖           |
| Zoom Reset                         | `Ctrl+B Ctrl+Shift+9` | ✅     | ✅   | ✖           |
| Zoom In                            | `Ctrl+B Ctrl+Shift+=` | ✅     | ✅   | ✖           |
| Zoom Out                           | `Ctrl+B Ctrl+Shift+-` | ✅     | ✅   | ✖           |
| **Q**uick Documentation            | `Ctrl+Q`              | ⛔     | ✅   | ✖           |
| Show All Commands                  | `F1`                  | ✅     | ✅   | ✖           |
| Focus Breadcrumbs                  | `Ctrl+B .`            | ✅     | ✅   | ✖           |
| Fold all                           | `Ctrl+Shift+-`        | ✅     | ✅   | ⛔          |
| Fold current                       | `Ctrl+-`              | ✅     | ✅   | ⛔          |
| Unfold all                         | `Ctrl+Shift+=`        | ✅     | ✅   | ⛔          |
| Unfold current                     | `Ctrl+=`              | ✅     | ✅   | ⛔          |
| Go to next change                  | `Ctrl+Alt+Left`       | ✖      | ✅   | `Ctrl+O`    |
| Go to previous change              | `Ctrl+Alt+Right`      | ✅     | ✅   | `Ctrl+I`    |
| **G**o to Line                     | `Ctrl+G`              | ✅     | ✅   | `:<number>` |
| Go to File                         | `Ctrl+E`              | ✅     | ✅   | ⛔          |
| Recent Files                       | `Ctrl+;`              | ✖      | ✅   | ✖           |
| Go to Definition (dec**l**aration) | `Ctrl+L`              | ✅     | ✅   | ✖           |
| Go to Imp**l**ementations (usages) | `Ctrl+Shift+L`        | ✅     | ✖    | ✖           |
| Quick fix                          | `Alt+Enter`           | ✅     | ✅   | ✖           |
| Rename symbol                      | `Shift+F6`            | ✅     | ✅   | ✖           |
| Trigger **P**arameter hints        | `Ctrl+P`              | ✅     | ✅   | ✖           |
| Trigger suggests                   | `Ctrl+Space`          | ✅     | ✅   | ✖           |
| Run task ...                       | `Shift+F10`           | ✅     | ✅   | ✖           |
| Run debug ...                      | `Shift+F9`            | ✖      | ✅   | ✖           |
| Switcher                           | `Ctrl+Tab`            | ✅     | ✅   | ✖           |

### Version control

| Name                  | Key binding    | VSCode         | IDEA     |
| --------------------- | -------------- | -------------- | -------- |
| **(K)** Commit Window | ---            | `Ctrl+B Alt+K` | `Ctrl+K` |
| Push Window           | `Ctrl+Shift+K` | ✅             | ✅       |
| Upda**t**e (pull)     | `Ctrl+T`       | ✅             | ✅       |
| Rollback file         | `Ctrl+Alt+Z`   | ✅             | ✅       |

## File hotkeys

| Name                   | Key binding           | VSCode | IDEA | Vim   |
| ---------------------- | --------------------- | ------ | ---- | ----- |
| Compare With ...       | `Ctrl+B Ctrl+E`       | ✅     | ✅   | ⛔    |
| Compare With clipboard | `Ctrl+B Ctrl+Shift+E` | ✅     | ✅   | ⛔    |
| **Copy Absolute** Path | `Ctrl+Shift+C`        | ✅     | ✅   | ✖     |
| New File               | `Ctrl+N`              | ✅     | ✅   | `:n`  |
| Open File              | `Ctrl+O`              | ✅     | ✖    | `:e`  |
| Save All               | `Ctrl+S`              | ✅     | ✅   | `:wa` |

## Editing hotkeys

| Name                               | Key binding              | VSCode | IDEA |
| ---------------------------------- | ------------------------ | ------ | ---- |
| Add Cursor Above                   | `Ctrl+Shift+Alt+Up`      | ✅     | ✅   |
| Add Cursor Below                   | `Ctrl+Shift+Alt+Down`    | ✅     | ✅   |
| Toggle Line Comment                | `Ctrl+/`                 | ✅     | ✅   |
| Cut                                | `Ctrl+X`, `Shift+Delete` | ✅     | ✅   |
| Copy                               | `Ctrl+C`, `Ctrl+Insert`  | ✅     | ✅   |
| Pase                               | `Ctrl+V`, `Shift+Insert` | ✅     | ✅   |
| Copy Line Down                     | `Ctrl+D`                 | ✅     | ✅   |
| Copy Line Up                       | `Ctrl+Shift+D`           | ✅     | ✖    |
| Undo                               | `Ctrl+Z`                 | ✅     | ✅   |
| Redo                               | `Ctrl+Shift+Z`           | ✅     | ✅   |
| Cursor Undo                        | `Ctrl+Shift+Alt+Z`       | ✅     | ✖    |
| Insert Line Above                  | `Ctrl+Shift+Enter`       | ✅     | ✅   |
| Insert Line Below                  | `Ctrl+Enter`             | ✅     | ✅   |
| Move Line Down                     | `Alt+Down`               | ✅     | ✅   |
| Move Line Up                       | `Alt+Up`                 | ✅     | ✅   |
| Smart Move Line Down               | `Shift+Alt+Down`         | ✖      | ✅   |
| Smart Move Line Up                 | `Shift+Alt+Up`           | ✖      | ✅   |
| Remove Line                        | `Ctrl+Y`                 | ✅     | ✅   |
| Join Lines                         | `Ctrl+J`                 | ✅     | ✅   |
| Format Document                    | `Ctrl+Alt+F`             | ✅     | ✅   |
| Toggle Upper/Lower Case            | `Ctrl+Shift+U`           | ✖      | ✅   |
| Transform to Lower Case            | `Ctrl+U`                 | ✅     | ✖    |
| Transform to Upper Case            | `Ctrl+Shift+U`           | ✅     | ✖    |
| Transform to Snake Case            | `Ctrl+Alt+Shift+U`       | ✅     | ✖    |
| Select All                         | `Ctrl+A`                 | ✅     | ✅   |
| Expand Selection (Select **W**ord) | `Ctrl+W`                 | ✅     | ✅   |
| Shrink Selection                   | `Ctrl+Shift+W`           | ✅     | ✅   |

### Search and Replace

| Name                                                            | Key binding        | VSCode | IDEA |
| --------------------------------------------------------------- | ------------------ | ------ | ---- |
| **F**ind in files                                               | `Ctrl+Shift+F`     | ✅     | ✅   |
| **R**eplace in files                                            | `Ctrl+Shift+R`     | ✅     | ✅   |
| **F**ind                                                        | `Ctrl+F`           | ✅     | ✅   |
| Find Next                                                       | `F3`               | ✅     | ✅   |
| Find Prev                                                       | `Shift+F3`         | ✅     | ✅   |
| Add Selection (Cursor) to Next Find Match (**J**oin next match) | `Alt+J`            | ✅     | ✅   |
| **R**eplace                                                     | `Ctrl+R`           | ✅     | ✅   |
| Search Editor: Add Selection (Cursor) to All Matches            | `Ctrl+Alt+Shift+J` | ✅     | ✅   |
| Search Editor: Toggle match **C**ase                            | `Alt+C`            | ✅     | ✅   |
| Search Editor: Toggle match whole **W**ords                     | `Alt+W`            | ✅     | ✅   |
| Search Editor: Toggle match Rege**x**p                          | `Alt+X`            | ✅     | ✅   |
| Search Editor: Match in **S**election                           | `Alt+S`            | ✅     | ✅   |

## View hotkeys

For Vim prefix shortcut is `Ctrl+W` instead of `Ctrl+B`

| Name                             | Key binding                      | VSCode | IDEA | TMux | Vim  |
| -------------------------------- | -------------------------------- | ------ | ---- | ---- | ---- |
| View: **Close** Tab              | `Ctrl+F4`, `Ctrl+B X`            | ✅     | ✅   | ⛔   | ⛔   |
| View: Focus Group **Below**      | `Ctrl+B J`                       | ✅     | ✖    | ⛔   | ⛔   |
| View: Focus Group **Above**      | `Ctrl+B K`                       | ✅     | ✖    | ⛔   | ⛔   |
| View: Focus Group **Left**       | `Ctrl+B H`                       | ✅     | ✅   | ⛔   | ⛔   |
| View: Focus Group **Right**      | `Ctrl+B L`                       | ✅     | ✅   | ⛔   | ⛔   |
| View: Swap Group Below           | `Ctrl+B Ctrl+Shift+[`            | ✅     | ✖    | ✖    | ⛔   |
| View: Swap Group Above           | `Ctrl+B Ctrl+Shift+]`            | ✅     | ✖    | ✖    | ⛔   |
| View: Swap Group Left            | `Ctrl+B Shift+[`                 | ✅     | ✖    | ⛔   | ⛔   |
| View: Swap Group Right           | `Ctrl+B Shift+]`                 | ✅     | ✖    | ⛔   | ⛔   |
| View: Move Tab into Group Below  | `Ctrl+B Ctrl+Shift+J`            | ✅     | ✖    | ✖    | ✖    |
| View: Move Tab into Group Above  | `Ctrl+B Ctrl+Shift+K`            | ✅     | ✖    | ✖    | ✖    |
| View: Move Tab into Group Left   | `Ctrl+B Ctrl+Shift+H`            | ✅     | ✖    | ✖    | ✖    |
| View: Move Tab into Group Right  | `Ctrl+B Ctrl+Shift+L`            | ✅     | ✖    | ✖    | ✖    |
| View: Next Tab                   | `Ctrl+PageUp`, `Ctrl+B Ctrl+L`   | ✅     | ✅   | ⛔   | `gt` |
| View: Previous Tab               | `Ctrl+PageDown`, `Ctrl+B Ctrl+H` | ✅     | ✅   | ⛔   | `gT` |
| View: Split **Verically**        | `Ctrl+B Shift+-`                 | ✅     | ✅   | ⛔   | ⛔   |
| View: Split **Horizontally**     | `Ctrl+B -`                       | ✅     | ✅   | ⛔   | ⛔   |
| View: Toggle Line Wrap           | `Ctrl+B Alt+Z`                   | ✅     | ✅   | ✖    | ✖    |
| View: Toggle Side Bar visibility | `Ctrl+B Alt+B`                   | ✅     | ✅   | ✖    | ✖    |
| View: Reopen last closed tab     | `Ctrl+Shift+T`                   | ✅     | ✅   | ✖    | ✖    |
| View: Increase Group Height      | `Ctrl+B Shift+K`                 | ✅     | ✅   | ⛔   | ⛔   |
| View: Increase Group Width       | `Ctrl+B Shift+L`                 | ✅     | ✅   | ⛔   | ⛔   |
| View: Decrease Group Height      | `Ctrl+B Shift+J`                 | ✅     | ✅   | ⛔   | ⛔   |
| View: Decrease Group Width       | `Ctrl+B Shift+H`                 | ✅     | ✅   | ⛔   | ⛔   |

### Panels

#### VSCode

| Name        | Key binding             |
| ----------- | ----------------------- |
| Hide panels | `Ctrl+B Alt+B`          |
| Sources     | `Alt+1`, `Ctrl+B Alt+E` |
| Search      | `Alt+2`, `Ctrl+Shift+F` |
| Git         | `Alt+3`, `Ctrl+B Alt+K` |
| Run & Debug | `Alt+4`                 |
| Extensions  | `Alt+8`                 |
| Terminal    | `Alt+9`, `Ctrl+~`       |

#### IDEA

| Name        | Key binding                       |
| ----------- | --------------------------------- |
| Hide panels | `Ctrl+B Alt+B`                    |
| Sources     | `Alt+1`, `Ctrl+B Alt+E`           |
| Search      | `Alt+2`, `Ctrl+Shift+F`           |
| Git         | `Alt+3`, `Ctrl+K`, `Ctrl+B Alt+K` |
| Debug       | `Alt+4`                           |
| Run         | `Alt+5`                           |
| Structure   | `Alt+7`                           |
| Bookmarks   | `Alt+8`                           |
| Terminal    | `Alt+9`, `Ctrl+~`                 |
