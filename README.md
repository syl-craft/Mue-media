# Mue — media

Demo clips for [Mue](https://github.com/syl-craft/Mue), kept out of the main repository so cloning it
stays light. The [Mue README](https://github.com/syl-craft/Mue#readme) embeds them from here.

| Clip | Shows |
|---|---|
| `01-update-flow` | The badge finds 1.3.0, the update window downloads it, the app restarts on the new version |
| `02-blockers` | Programs still using the app's files, grouped: « Close 2 programs », « Install without closing them », then one group closed and the others left to the installer |
| `03-badge` | Close-up on the `UpdateBadge`: `v1.2.0`, then `v1.2.0 → 1.3.0`, tooltip, click |
| `04-confirmation` | The host announces what the installation does; Esc postpones it and the update stays ready; « Confirm and install » restarts on 1.3.0 |

Each clip exists in `light` and `dark`, as an MP4 (1920 × 1080, 60 fps) and a GIF (960 × 540,
20 fps) for the README. The host app « Notebook » and every name, PID and release note are demo data.
The update windows reproduce Mue.Wpf 0.3.0 with an amber accent, as a host app would theme them.

These files are **generated**, do not edit them by hand. They are rendered by `motion/` (Chromium headless
and ffmpeg), which writes straight into `videos/` here.
