# UniformShortcuts

Uniformed keyboard Shortcuts table for VSCode and PyCharm

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

| Name                           | Key binding           | VSCode | IDEA | Vim         |
| ------------------------------ | --------------------- | ------ | ---- | ----------- |
| New Window                     | `Ctrl+Shift+N`        | ⛔     | ⛔   | ✖           |
| Close Application              | `Alt+F4`              | ⛔     | ⛔   | `:qa`       |
| **S**ettings                   | `Ctrl+Alt+S`          | ⛔     | ⛔   | ✖           |
| Zoom In                        | `Ctrl+B Ctrl+Shift+=` | ⛔     | ⛔   | ✖           |
| Zoom Out                       | `Ctrl+B Ctrl+Shift+-` | ⛔     | ⛔   | ✖           |
| Show All Commands              | `F1`                  | ⛔     | ⛔   | ✖           |
| Focus Breadcrumbs              | `Ctrl+B .`            | ⛔     | ⛔   | ✖           |
| Fold all                       | `Ctrl+Shift+-`        | ⛔     | ⛔   | ⛔          |
| Fold current                   | `Ctrl+-`              | ⛔     | ⛔   | ⛔          |
| Unfold all                     | `Ctrl+Shift+=`        | ⛔     | ⛔   | ⛔          |
| Unfold current                 | `Ctrl+=`              | ⛔     | ⛔   | ⛔          |
| Go back                        | `Ctrl+Alt+Left`       | ⛔     | ⛔   | `Ctrl+O`    |
| Go forward                     | `Ctrl+Alt+Right`      | ⛔     | ⛔   | `Ctrl+I`    |
| **G**o to Line                 | `Ctrl+G`              | ⛔     | ⛔   | `:<number>` |
| Go to File                     | `Ctrl+E`              | ⛔     | ⛔   | ⛔          |
| Go to Definition (declaration) | `???`                 | ⛔     | ⛔   | ✖           |
| Go to Implementations (usages) | `???`                 | ⛔     | ⛔   | ✖           |
| Quick fix                      | `Alt+Enter`           | ⛔     | ⛔   | ✖           |
| Rename symbol                  | `Shift+F6`            | ⛔     | ⛔   | ✖           |
| Trigger **P**arameter hints    | `Ctrl+P`              | ⛔     | ⛔   | ✖           |
| Trigger suggests               | `Ctrl+Space`          | ⛔     | ⛔   | ✖           |

### Version control

| Name                  | Key binding    | VSCode | IDEA |
| --------------------- | -------------- | ------ | ---- |
| **(K)** Commit Window | `Ctrl+K`       | ⛔     | ✅   |
| Push Window           | `Ctrl+Shift+K` | ⛔     | ✅   |
| Upda**t**e (pull)     | `Ctrl+T`       | ⛔     | ✅   |
| Rollback file         | `Ctrl+Alt+Z`   | ⛔     | ✅   |

## File hotkeys

| Name                   | Key binding    | VSCode | IDEA | Vim   |
| ---------------------- | -------------- | ------ | ---- | ----- |
| Compare With ...       | `???`          | ⛔     | ⛔   | ⛔    |
| Compare With clipboard | `???`          | ⛔     | ⛔   | ⛔    |
| Copy Absolute Path     | `Ctrl+Shift+C` | ⛔     | ✅   | ✖     |
| New File               | `Alt+Insert`   | ⛔     | ✅   | `:n`  |
| Open                   | `Ctrl+O`       | ✅     | ⛔   | `:e`  |
| Save All               | `Ctrl+S`       | ⛔     | ✅   | `:wa` |

## Editing hotkeys

| Name                      | Key binding              | VSCode | IDEA | Vim |
| ------------------------- | ------------------------ | ------ | ---- | --- |
| Add Cursor Above          | `Ctrl+Shift+Up`          |        |      |     |
| Add Cursor Below          | `Ctrl+Shift+Down`        |        |      |     |
| Toggle Line Comment       | `Ctrl+/`                 |        |      |     |
| Cut                       | `Ctrl+X`, `Shift+Delete` |        |      |     |
| Copy                      | `Ctrl+C`, `Shift+Delete` |        |      |     |
| Pase                      | `Ctrl+V`, `Shift+Insert` |        |      |     |
| Copy Line Down            | `Ctrl+D`                 |        |      |     |
| Copy Line Up              | `Ctrl+Shift+D`           |        |      |     |
| Undo                      | `Ctrl+Z`                 |        |      |     |
| Redo                      | `Ctrl+Shift+Z`           |        |      |     |
| Cursor Undo               | `Ctrl+Shift+Alt+Z`       |        |      |     |
| Insert Line Above         | `Ctrl+Shift+Enter`       |        |      |     |
| Insert Line Below         | `Ctrl+Enter`             |        |      |     |
| Move Line Down            | `Alt+Down`               |        |      |     |
| Move Line Up              | `Alt+Up`                 |        |      |     |
| Remove Line               | `Ctrl+Y`                 |        |      |     |
| Format Document           | `Ctrl+Alt+F`             |        |      |     |
| Toggle Upper/Lower Case   | `Ctrl+Shift+U`           |        |      |     |
| Transform to Snake Case   | `Ctrl+Alt+Shift+U`       |        |      |     |
| Select All                | `Ctrl+A`                 |        |      |     |
| Expand Selection          | `Ctrl+W`                 |        |      |     |
| Shrink Selection          | `Ctrl+Shift+W`           |        |      |     |
| Selection Anchor          | `???`                    |        |      |     |
| Trim trailing whitespaces | `???`                    |        |      |     |

### Search and Replace

| Name                                                 | Key binding        | VSCode | IDEA | TMux | Vim |
| ---------------------------------------------------- | ------------------ | ------ | ---- | ---- | --- |
| Find in files                                        | `Ctrl+Shift+F`     |        |      |      |     |
| Replace in files                                     | `Ctrl+Shift+R`     |        |      |      |     |
| Find                                                 | `Ctrl+F`           |        |      |      |     |
| Find Next                                            | `F3`               |        |      |      |     |
| Find Prev                                            | `Shift+F3`         |        |      |      |     |
| Add Selection (Cursor) to Next Find Match            | `Alt+J`            |        |      |      |     |
| Replace                                              | `Ctrl+R`           |        |      |      |     |
| Replace Next                                         | `???`              |        |      |      |     |
| Replace Prev                                         | `???`              |        |      |      |     |
| Search Editor: Add Selection (Cursor) to All Matches | `Ctrl+Alt+Shift+J` |        |      |      |     |
| Search Editor: Toggle match Case                     | `Alt+C`            |        |      |      |     |
| Search Editor: Toggle match whole Words              | `Alt+W`            |        |      |      |     |
| Search Editor: Toggle match Regexp                   | `Alt+R`            |        |      |      |     |
| Search Editor: Match in selection                    | `???`              |        |      |      |     |

## View hotkeys

| Name                             | Key binding | VSCode | IDEA | TMux | Vim |
| -------------------------------- | ----------- | ------ | ---- | ---- | --- |
| View: Close Tab                  |             |        |      |      |     |
| View: Focus Group Below          |             |        |      |      |     |
| View: Focus Group Above          |             |        |      |      |     |
| View: Focus Group Left           |             |        |      |      |     |
| View: Focus Group Right          |             |        |      |      |     |
| View: Swap Group Below           |             |        |      |      |     |
| View: Swap Group Above           |             |        |      |      |     |
| View: Swap Group Left            |             |        |      |      |     |
| View: Swap Group Right           |             |        |      |      |     |
| View: Move Tab into Group Below  |             |        |      |      |     |
| View: Move Tab into Group Above  |             |        |      |      |     |
| View: Move Tab into Group Left   |             |        |      |      |     |
| View: Move Tab into Group Right  |             |        |      |      |     |
| View: Next Tab                   |             |        |      |      |     |
| View: Previous Tab               |             |        |      |      |     |
| View: Split Verically            |             |        |      |      |     |
| View: Toggle Line Wrap           |             |        |      |      |     |
| View: Split Horizontally         |             |        |      |      |     |
| View: Toggle Side Bar visibility |             |        |      |      |     |
| View: Toggle Word Wrap           |             |        |      |      |     |
| View: Reopen last closed tab     |             |        |      |      |     |
| View: Increase Group Height      |             |        |      |      |     |
| View: Increase Group Width       |             |        |      |      |     |
| View: Decrease Group Height      |             |        |      |      |     |
| View: Decrease Group Width       |             |        |      |      |     |
