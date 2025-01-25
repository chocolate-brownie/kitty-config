# 🐱 My Kitty Terminal Configuration

A clean and functional configuration for the [Kitty terminal emulator](https://sw.kovidgoyal.net/kitty/), featuring the beautiful Kanagawa color scheme and FiraCode Nerd Font.
![image](https://github.com/user-attachments/assets/7f06d26c-e442-48d0-bb67-791d2f1a055b)

## ✨ Features

- **Custom Font**: FiraCode Nerd Font Mono with enhanced ligatures and special features (You can choose any type of nerd font)
- **Elegant Window Management**: Flexible layouts with customizable splits and tabs
- **Modern UI**: Semi-transparent background with powerline-style tab bar
- **Performance Optimized**: Configured for smooth operation with minimal input delay
- **Smart Scrollback**: Extended history with intelligent space stripping
- **Mouse Support**: Focus follows mouse with smart clipboard integration

## 🚀 Quick Start

1. Install the required dependencies:
   - Kitty terminal emulator
   - FiraCode Nerd Font
   - Fish shell (default shell in config)
   - Neovim (default editor)

2. Clone this repository:
```bash
git clone [your-repo-url]
cd [your-repo-name]
```

3. Copy the configuration:
```bash
cp kitty.conf ~/.config/kitty/
```

## ⌨️ Key Bindings

### Window Management
- `F1`: New window with current working directory
- `Ctrl+Shift+W`: Close window
- `Ctrl+Shift+[/]`: Navigate between windows

### Split Windows
- `Ctrl+Shift+↑/↓/←/→`: Move window in specified direction

### Tab Management
- `Ctrl+Shift+T`: New tab
- `Ctrl+Shift+←/→`: Navigate between tabs
- `Ctrl+Shift+,/.`: Move tabs

### Layout Management
- `Ctrl+Shift+L`: Next layout
- `Ctrl+Shift+Z`: Toggle stack layout

### Font Size
- `Ctrl+Shift++`: Increase font size
- `Ctrl+Shift+-`: Decrease font size
- `Ctrl+Shift+0`: Reset font size

### Clipboard
- `Ctrl+Shift+C`: Copy
- `Ctrl+Shift+V`: Paste

## 🎨 Theme

This configuration uses the Kanagawa theme. The theme file should be placed in your Kitty themes directory.

## ⚙️ Configuration Details

- **Font Size**: 10.0
- **Opacity**: 0.9 (static)
- **Cursor Style**: Block with 0.5s blink interval
- **Scrollback**: 10,000 lines
- **Layouts**: Tall, Stack, Fat, Grid
- **Tab Style**: Powerline with slanted separators

## 🛠️ Customization

To modify the configuration, edit the `kitty.conf` file in your `~/.config/kitty/` directory. The configuration is well-commented and organized into sections for easy navigation:

- Fonts
- Window Layout
- Layouts
- Tabs
- Performance
- Scrollback
- Mouse
- Bell
- Cursor
- Advanced
- Keyboard Shortcuts

## 🤝 Contributing

Feel free to submit issues and enhancement requests!
