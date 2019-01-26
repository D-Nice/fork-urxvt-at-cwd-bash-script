# fork-urxvt-at-cwd-bash-script
Bash script for use with i3 or other wm, which will open an new urxvt instance at the cwd of the focused window's deepest bash instance, meaning bash is required somewhere within that windows process chain. This means even from vim or other programs running in your term, you can open up a new term, that has the same cwd as it.

## Getting Started

With i3, insert a keybinding to execute the script into your i3 config.

This is what it may look like if you wish mod+Shift+Enter to run this script:

```bash
# start urxvt from focused window deepest cwd
bindsym $mod+Shift+Return exec --no-startup-id ~/.config/i3/scripts/urxvt-fork-cwd.sh
```

### Prerequisites

Bash & Urxvt


