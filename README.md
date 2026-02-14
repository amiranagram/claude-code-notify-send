# claude-code-notify-send

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin that sends desktop notifications via `notify-send`. Works on any Linux desktop with a notification daemon (GNOME, KDE, Sway, Hyprland, etc.).

## Notifications

| Event | Urgency | When |
|-------|---------|------|
| Permission prompt | Critical | Claude needs your approval to proceed |
| Response complete | Low | Claude finished responding |
| Tool failure | Normal | A tool call failed |

## Requirements

- `notify-send` (usually provided by `libnotify` — pre-installed on most Linux desktops)

## Install

```
/plugin marketplace add amiranagram/claude-code-notify-send
/plugin install notify-send@claude-code-notify-send
```

## Uninstall

```
/plugin uninstall notify-send@claude-code-notify-send
```

## License

[MIT](LICENSE)
