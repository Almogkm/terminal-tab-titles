# Changelog

## 0.1.1
- Fix: end-of-command revert no longer renames terminals to literal `${process}`.
- Fix: undedicated terminal revert no longer triggers `No name argument provided`.
- Fix: undedicated terminals now reset using `RESET_NAME = " "` (single-space rename workaround) because some VS Code environments reject empty rename arguments.
- Improved: `Terminal Tab Titles: Get Active Terminal Process Details` now reports terminal state and avoids misleading shell type output.

## 0.1.0
- Initial release (JS/no-build).
- Rename terminal tabs based on run-file commands.
- Dedicated terminal fixed-title enforcement.
- Debug logging and manual test commands.
