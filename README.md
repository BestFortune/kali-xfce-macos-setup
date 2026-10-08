# Kali XFCE macOS-Style Desktop Setup

My personal Kali Linux XFCE desktop configuration.

This setup provides:

- macOS-style permanent top panel
- Centered auto-hiding bottom dock
- XFCE workspace switcher
- System tray and system controls
- Rofi-based Spotlight-style launcher
- `Alt + Space` universal search
- Application search with native Rofi `drun`
- Fast file and folder search using `fdfind`
- Automatic background file-search cache refresh
- Custom rounded dark Rofi theme

## Requirements

- Kali Linux
- XFCE
- Rofi
- `fd-find`
- `fdfind`
- systemd user services

Install the file search tool:

```bash
sudo apt install fd-find

